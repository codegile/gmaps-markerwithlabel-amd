gmaps-markerwithlabel-amd
=========
Based on [Google Maps MarkerWithLabel 1.1.9](http://google-maps-utility-library-v3.googlecode.com/svn/tags/markerwithlabel/1.1.9/).
This is basically a fork that adds src/markerwithlabel-amd.js.

This extension offers AMD support for Google Maps MarkerWithLabel utility library of Google Maps Javascript API v3. Also fixes the problem with requirejs optimizer.
Dependencies
----
[requirejs async plugin](https://github.com/millermedeiros/requirejs-plugins/)
Install
----
```
bower install google-markerwithlabel
```

```
git clone https://github.com/lupugabriel1/gmaps-markerwithlabel-amd
```
Usage
----
```
paths: {
    require.config({
        /* Bower Libraries */
        async: '../bower_components/requirejs-plugins/src/async',
        markerlabel: '../bower_components/google-makerwithlabel/src/markerwithlabel-amd',
...
```

```
var MarkerLabel = require('markerlabel');
...
var myMarker = new MarkerLabel({ ... })
```
License
----
Apache 2.0
