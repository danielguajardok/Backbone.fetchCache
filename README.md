This project is a fork of Backbone dualStorage Adapter by lucian1900 https://github.com/lucian1900/Backbone.dualStorage.

Backbone Fetch Cache v0.1
=================================

Fetch Cache is a plug and play extension for Backbone Collections that let your application access cached content of a URL until the TTL is expired.

This project is based con Backbone dualStorage. All requests are stored in localStorage for off-line access. This plugin use it for caching, keeping cached-content updated even wen you create update, or delete models of a collection. For more information on using dualStorage plugin, please refer to https://github.com/lucian1900/Backbone.dualStorage.

Fetch Cache Usage
-----

Include Backbone.dualStorage:

    <script type="text/javascript" src="backbone.js"></script>
    <script type="text/javascript" src="backbone.dualstorage.js"></script>

If you want to use cache:

    Collection = Backbone.Collection.extend({
        cache: {
            ttl: 30
        }
    });

Credits
-------

Thanks to [Jerome Gravel-Niquet](https://github.com/jeromegn) for Backbone.localStorage.

Thanks to [lucian1900](https://github.com/lucian1900/Backbone.dualStorage) for Backbone.dualStorage 