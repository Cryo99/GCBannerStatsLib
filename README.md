# GCStatsBannerLib

A userscript library that provides core functionality for cache series statistics banners on geocaching.com.

The stats banner was originally conceived and implemented by BaSHful for sadexploration's
[Church Micro Series](https://www.15ddv.me.uk/geo/cm/index.html), a hugely popular series of caches covering
the entire UK, with a few in other countries as well.

In order for the library to function, the cache series must have a means of serving data to the banner. The
library currently understands the series of web sites designed by Chris ~ AKA Bus.Stop, based on that provided
for the [SideTracked](https://sidetrackedseries.info/about.php) series of caches.

Sites also exist for:

* [A Fine Pair Series](https://www.afinepair.co.uk/)
* [Little Bridges Series](https://littlebridgesseries.co.uk/)
* [Village Sign Series](https://villagesignseries.co.uk/)
* [War Memorial Series](https://warmemorialseries.co.uk/)

 These sites provide URLs which serve the data and images which comprise the banner. This library uses these services
 to add the banners to the appropriate pages on geacaching.com:

* the specific cache pages for each series
* your user dashboard
* the About tab of your user profile

Both the new and old page styles are supported.

## The Future

I would love to see more series able to take advantage of this. There are quite a few candidate series but work will be
required in order to create the service which provides the data and images, whatever method is used.

The [Village Hall Series](https://villagehallseries.wixsite.com/geocaching) now has a banner graphic but its use is entirely
manual on the part of the cacher. I'd like to see whether it's possible to automate the process of determining a cacher's
level and displaying the graphic.

## Version History

### Version 1.0.0

* Initial release.

### Versions 0.0.1 - 0.0.23

* Development versions.
* Added the new account page.
  * Much work to develop and debug the collapsible widget which hosts the banners and debug the loading issues.
  * More work trying and debugging asynchronous loading.
