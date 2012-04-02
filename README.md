fancyBox 2 with Fullscreen
========

We had the feeling fancyBox has to support the new "fullscreen" mode enabled in some recent browsers.
That's why we made it!

Please note that the development is in early stage, you may consider this as very BETA code.

More information on fancyBox 2: http://www.fancyapps.com/fancybox/

How to use
----------

To get started, download the plugin, unzip it and copy files to your website/application directory.
Load files in the <head> section of your HTML document. Make sure you also add the jQuery library.

    <head>
        <script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
        <link rel="stylesheet" href="/fancybox/jquery.fancybox.css" type="text/css" media="screen" />
        <script type="text/javascript" src="/fancybox/jquery.fancybox.pack.js"></script>
        <script type="text/javascript" src="/fancybox/jquery.fullscreen.js"></script>
    </head>

Create your links with a `title` if you want a title to be shown, and add a class:

    <a href="large_image.jpg" class="fancybox" title="Sample title"><img src="small_image.jpg" /></a>

If you have a set of related items that you would like to group,
additionally include a group name in the `rel` (or `data-fancybox-group`) attribute:

    <a href="large_1.jpg" class="fancybox" rel="gallery" title="Sample title 1"><img src="small_1.jpg" /></a>
    <a href="large_2.jpg" class="fancybox" rel="gallery" title="Sample title 1"><img src="small_2.jpg" /></a>

Initialise the script like this:

    <script>
        $(document).ready(function() {
            $('.fancybox').fancybox({fsBtn:true});
        });
    </script>

More examples are available at https://github.com/fancyapps/fancyBox
