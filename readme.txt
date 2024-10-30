=== Plugin Name ===
Contributors: tristanchambers
Donate link: https://github.com/tristanchambers/WP-Columnizer/wiki
Tags: columns, column, shortcode, layout, pages, posts, content, grid, magazine, magazine columns, magazine layout, jQuery, client side
Requires at least: 3.0
Tested up to: 3.4
Stable tag: 3.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Wordpress Plugin to columnize content automatically

== Description ==

Columnizer is a jQuery based Wordpress plugin that formats your content into columns. All you need to do is embrace your content in a single set of shortcodes denoting the number of columns you'd like. Like this:

`
[threecolumns]
Lorem ipsum...vitae nunc.
Curabitur fringilla...consectetur arcu.
Proin id...pretium eros.
etc...
[/threecolumns]
`

The rest is taken care of for you. Just write out the number of columns (up to twelve) followed by the word 'columns' with no space (as above) and your column formatting needs will be satisfied most splendidly. Other column plugins need you to divvy up the content between sets of tags. Columnizer does it for you!

To customize the margins between columns edit *columnizer.css*. Alternatively you could override the rules in your own css file by adding an extra level of hierarchy. Something like this:

`
#main #columnizer .first div {
	margin-right: 8px; /*changed spacing to 8px*/
	margin-left: 0 !important;
}
#main #columnizer .last div {
	margin-left: 8px; /*changed spacing to 8px*/
	margin-right: 0 !important;
}
#main #columnizer .column div {
	margin-left: 8px; /*changed spacing to 8px*/
	margin-right: 8px; /*changed spacing to 8px*/
        border-left: 1px solid grey; /*new rule to add slick dividers*/
        border-right: 1px solid grey; /*new rule to add slick dividers*/
}
`

WP Columnizer is based on the jQuery plugin "Columnizer" by Adam Wulf.

== Installation ==

To install the plugin simply download the zip file. Then extract the directory into wp-content/plugins/ Next go to the plugins page on the Wordpress admin panel and enable Columnizer. Once enabled you may begin using the plugin by inserting sets of short codes in your content.

