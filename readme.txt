=== Social Path ===
Contributors: samikeijonen
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=E65RCFVD3QGYU
Tags: name-days, nordic, names, name
Requires at least: 3.4
Tested up to: 3.4.1
Stable tag: 0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Register shortcode [sk_nnd_name_days] to display current day of the weeek, day and name day.

== Description ==

This mini plugin register shortcode [sk_nnd_name_days] to display current name days in Nordic countries. Supported countries are Finland,
Norway, Sweden and Denmark. By default shortcode [sk_nnd_name_days] displays current day of the week, day and name days in Finland. You can use
use shortcode in posts, pages and text widget.

= Shorcode usage and attributes in other countries =

Here is how you use shortcode in other languages.

1. Norway: [sk_nnd_name_days language="nb_NO"]
1. Sweden: [sk_nnd_name_days language="sv_SE"]
1. Denmark: [sk_nnd_name_days language="da_DK"]

Other shortcode attributes are before, after, language, separator (default is |) and dateformat (default is l j.n.Y). You can use these attributes
like this.

`[sk_nnd_name_days language="nb_NO" before="Name days: " after="" separator="-" dateformat="j.n.Y"]`

If you want to display name days in your theme template file, add this code.

`
  <?php 
	// Display name of the day
	if ( function_exists( 'sk_nnd_name_days_shortcode' ) ) {
	
		echo do_shortcode( '[sk_nnd_name_days]' ); 
		
	}
	?>
`

== Installation ==

1. Upload `nordic-name-days` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

= Why was this plugin created? =

I needed this feature and someone else might need it too.

== Screenshots ==

1. Name Days in Finland

== Changelog ==

= 0.2 =
* Everything's brand new.