plugins.js
==========

What's this?
------------

plugins.js is a file that you can include in your project to have all your
javascript plugins in the same place (useful for having different projects
pointing to the same JS file to have the javascript plugins unified).

How it works
------------

Include the file and after the plugins var start adding plugins like this:

    if (plugins.get(pluginName)) {
        
        // Plugin code
        
    }

Then when you include your plugins.js file in your page you do:

    <script id='pluginsjs' src='path/to/plugins.js?jquery&lightbox'></script>

That means that you want to have the jquery and lightbox plugins in that
specific web page.

In another project, the query string may change and so the plugins included.

In the template plugins.js file a couple of plugins are added as a example.


