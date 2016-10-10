# d4s_bootstrap theme requirement

## Modules and dependency modules
### [Nivo slider](https://www.drupal.org/project/nivo_slider)
- Install [Libraries API](https://www.drupal.org/project/libraries)
- Install [jQuery Update](https://www.drupal.org/project/jquery_update) - configured to use jQuery 1.7 or higher.
- Copy [Nivo Slider jQuery plugin](https://github.com/gilbitron/Nivo-Slider) to sites/all/libraries/nivo-slider
### [Quick Tabs](https://www.drupal.org/project/quicktabs)
### [Bootstrap Quicktabs](https://www.drupal.org/project/bootstrap_quicktabs)
### [Owl Carousel](https://www.drupal.org/search/site/Owl%20Carousel)
- Copy [Owl Carousel library](http://www.owlcarousel.owlgraphic.com/download/owl.carousel.zip) to sites/all/libraries/owlcarousel
###[Font Awesome](https://www.drupal.org/project/fontawesome)
- Copy [Font Awesome](https://github.com/FortAwesome/Font-Awesome) to sites/all/libraries/fontawesome

##Should be enabled modules
- Nivo Slider
- jQuery Update
- Libraries
- Quicktabs
- Quicktabs Styles
- Owl Carousel
- Owl Carousel Fields
- Owl Carousel UI
- Owl Carousel Views
- Views
- Views Bootstrap
- Views UI
- Variables
- Font Awesome
- System
- Chaos tools
- Calendar
- Date
- Date API
- Date Popup
- Date Views


<!-- @file Instructions on how to sub-theme the Drupal Bootstrap base theme using the CDN Starterkit. -->
<!-- @defgroup subtheme_cdn -->
<!-- @ingroup subtheme -->
# CDN Starterkit

The CDN Starterkit is rather simple to set up. You don't have to do anything
until you wish to override the default [Drupal Bootstrap] base theme settings
or provide additional custom CSS.

- [Prerequisite](#prerequisite)
- [Override Styles](#styles)
- [Override Settings](#settings)
- [Override Templates and Theme Functions](#registry)

## Prerequisite
Read the @link subtheme Sub-theming @endlink parent topic.

## Override Styles {#styles}
Open `./subtheme/css/style.css` and modify the file to your liking.

## Override Settings {#settings}
Please refer to the @link subtheme_settings Sub-theme Settings @endlink topic.

## Override Templates and Theme Functions {#registry}
Please refer to the @link registry Theme Registry @endlink topic.

[Drupal Bootstrap]: https://www.drupal.org/project/bootstrap
[Bootstrap Framework]: http://getbootstrap.com
[jsDelivr CDN]: http://www.jsdelivr.com
