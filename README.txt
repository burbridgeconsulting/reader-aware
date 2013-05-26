=== Plugin Name ===
Contributors: chrisbee
Donate link: http://chrisburbridge.com/plugins/donate/
Tags: jquery, css, 
Requires at least: 3.5.1
Tested up to: 3.5.1
Version: 0.1 beta

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

== Frequently Asked Questions ==

= A question that someone might have =

An answer to that question.

= What about foo bar? =

Answer to foo bar dilemma.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot is taken from
the directory of the stable readme.txt, so in this case, `/tags/4.3/screenshot-1.png` (or jpg, jpeg, gif)
2. This is the second screen shot

== Changelog ==

= 1.0 =
* A change since the previous version.
* Another change.

= 0.5 =
* List versions from most recent at top to oldest at bottom.

== Upgrade Notice ==

= 1.0 =
Upgrade notices describe the reason a user should upgrade.  No more than 300 characters.

= 0.5 =
This version fixes a security related bug.  Upgrade immediately.

== Arbitrary section ==

You may provide arbitrary sections, in the same format as the ones above.  This may be of use for extremely complicated
plugins where more information needs to be conveyed that doesn't fit into the categories of "description" or
"installation."  Arbitrary sections will be shown below the built-in sections outlined above.

== A brief Markdown Example ==

Ordered list:

1. Some feature
1. Another feature
1. Something else about the plugin

Unordered list:

* something
* something else
* third thing

Here's a link to [WordPress](http://wordpress.org/ "Your favorite software") and one to [Markdown's Syntax Documentation][markdown syntax].
Titles are optional, naturally.

[markdown syntax]: http://daringfireball.net/projects/markdown/syntax
            "Markdown is what the parser uses to process much of the readme file"

Markdown uses email style notation for blockquotes and I've been told:
> Asterisks for *emphasis*. Double it up  for **strong**.

`<?php code(); // goes in backticks ?>`
