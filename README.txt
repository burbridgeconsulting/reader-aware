=== Plugin Name ===
Contributors: chrisbee
Donate link: http://chrisburbridge.com/plugins/donate/
Tags: jquery, css, 
Requires at least: 3.5.1
Tested up to: 3.5.1
Version: 1.1

A wrapper for the aware.js plugin, by http://xoxco.com/. See more at http://xoxco.com/projects/code/aware/

== Description ==

Aware.js bundles several features into one easy to implement library. To add it to your site, include the script tag, and then initiate the plugin:

	$().aware();

	.first-visit - This is the reader's first visit on record.
	.repeat-visitor - This reader has been to the site at least once before.
	.first-visit-of-day - This is a reader who has visited before, but not today.

	.daytime
	    .morning
	        .earlymorning
	        .latemorning
	    .afternoon
	        .noonish
	        .earlyevening
	.nighttime
	    .evening
	    .night
	    .latenight
	    .early

Read more at http://xoxco.com/projects/code/aware/

== Installation ==

1. Upload `reader-aware.zip` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

= 1.0 =
* First release

= 1.1 = 
* Added aware.js as submodule.

== To Do ==

* Add support for the class that allows you to add support for seen/not seen at the post level