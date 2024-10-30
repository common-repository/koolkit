=== Koolkit ===
Contributors: Nectarine Imp
Tags: weather, post preview, yql
Requires at least: 2.0
Tested up to: 3.1
Stable tag: trunk

Adds functions and short codes for post preview, weather. More to come.

== Description ==

Koolkit adds functions and short codes to let you enhance your theme, posts and pages. Currently there are two 'Kools' in the kit. The first is the post preview function which lets you show miniatureized snippets of your next set of posts in a pleasing format. The layout is fully CSS controllable and ready for jQuery. Just add <?php kool_preview_boxes(); ?> to your code.

The second 'Kool' in this release is Kool Weather which provides weather for any location (assuming the data exists!) This one uses a short code ([KoolWeather location='your location']) so it can be easily added to posts and pages, widgets and so forth. Location can be a city,state combination or a city, country combination. Try Addis Abeba, Ethiopia or Caen, France. Right now it is just showing Farenheit but an additional code will be added in the next update to allow it to show celcius.

3 more Kools are coming. If you have suggestions you can contact us at http://nectarineimpllc.com

== Installation ==

Standard plugin installation

1. Upload `koolkit.zip` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Place `<?php kool_preview_boxes(); ?>` in your templates and/or add the `[KoolWeather]` shortcode to your posts and pages. More to come!

== Frequently Asked Questions ==

= I've got an idea for a 'Kool' where do I send it? =

[Nectarine Imp](http://nectarineimpllc.com/koolkit "Koolkit homepage")

= Can I reuse your YQL code? =

Yes and I suggest it! YQL is great and I made it as easy as possible to take YQL select statements and generate PHP objects. Absolutely, reuse the functions as you see fit and spread the word.

== Screenshots ==

1. screenshot-1.png This is an example 3 x 2 layout of the preview boxes added with kool_preview_boxes(). It shows the next set from the current page. It shows the same number as the your standard number of posts per page. If there are less posts remaining than that it only shows the remaining ones.
2. screenshot-2.png This is an example of KoolWeather. Most locations on the planet care accessible. Experiment with the name of the location. Using the most up to date name is best.

== Changelog ==

= 0.3 =
* Finally unveiled to the public.

= 0.2 =
* Added KoolWeather, cleaned up YQL processor. 

= 0.1 =
* Added kool_preview_boxes()
