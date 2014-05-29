=== Hashcash Updated ===
Contributors: azizmb, ecb29, donncha, wormeyman
Tags: spam, antispam, anti-spam, comments, comment, pingback, trackback, wp-hashcash, plugin, security, wordpress, javascript, js, signup, sign-up, wp-login.php, wp-signup.php, buddypress, bp, WPMU
Tested up to: 3.9.1
Stable tag: 5.0
Requires at least: 3.8
License: GPLv2 or later
Donate link: http://wormeyman.com

Client-side javascript blocks all spam bots. HTML5 compliant. Now with support for WordPress Versions 3.1+

== Description ==

= No More Spam =

Hashcash Updated is an antispam plugin that eradicates comment spam on Wordpress blogs. It works because your visitors must use obfuscated javascript to submit a proof-of-work that indicates they opened your website in a web browser, not a robot. If the javascript check fails, Hashcash Updated now gives you three options; it can either put the comment into moderation (default), put the comment in the akismet queue, or delete it.

Hashcash Updated is 100% GPL compatible.

= History =
This plugin started out 9 years ago by Elliott Back (ecb29) with the name WP-Hashcash, later down the road Donncha Ó Caoimh (donncha) started helping with development. In February 2011 the plugin was abanondoned and did not recive any more updates.

In April 2012 (azizmb) forked WP-Hashcash and released it under the name WP-Hashcash Extended fixing the problem with not being able to change the settings in the origional plugin. After the update in April it did not recieve any more updates.

In May 2014 Eric Johnson (wormeyman) forked WP-Hashcash Extended from the GitHub WordPress plugins mirror and renamed it [Hashcash Updated](https://github.com/wormeyman/wp-hashcash-updated), Pull Requests are encouraged!

= Features =

1. Blocks all comment spam, but not real comments
1. Also prevents most trackback / pingback spam
1. Also protects signup pages for Wordpress (WP), BuddyPress (BP), and Wordpress Multi-User (WPMU)
1. Widget support to display spam statistics and edit the configuration
1. Works with IE, Firefox, and Safari
1. 100% standards compliant HTML5, works with jQuery and Prototype
1. Tested with Wordpress 3, Firefox, Safari, IE, and Chrome
1. Akismet compatibility

= Limitations =

Hashcash Updated relies on the presence of two hooks in your theme, `wp_head` and `comment_form`. If your theme doesn't include these actions, you will need to add them immediately before the end head and end form tags respectively.
== Frequently Asked Questions ==

= Can you add a Whitelist for IP addresses? =
I do not know how to do this but if someone would like to help that would be awesome!

= Please update this plugin =
I have!

= Will this work with a 3rd party commenting service like Disqus? =
No this will not, however they have their own anti-spam technology.

== Installation ==

= Installation Instructions =

To install Hashcash Updated, please download the plugin and unzip it, then copy the wp-hashcash.php file to wp-content/plugins. Activate the plugin and drag into your Widgetized sidebar for public statistics, or visit Options, Hashcash Updated from the admin panel to configure options.

= Notes =

If you are upgrading from a previous version of WP-Hashcash, please disabled the plugin, then delete its files entirely.  Then, upload the latest plugin files and activate!

== Screenshots ==

1. Hashcash Updated Options Screen

== Testimonials ==

* "One of my favorites"
* "this is a clever idea that I think might work well"
* "I haven't had a single comment spam in my comment moderation queue for over a week now. I'm feeling the love!"
* "The least annoying one I have found"
* "this thing was a trivial install"
* "a fancier technique"
* "Comment Spam is a thing of the past, and I owe it to Spam Stopgap Extreme. If you use WordPress, I highly recommend installing this plugin. It has completely eliminated the comment spam problem I was having. I no longer need the spammer Tarpit plugin, or anything."
* "Why am I not worried about comment spam anymore? Because of my awesome new blog plugin, Spam Stopgap Extreme. This baby blocks any bot trying to post to my blog. No blacklists, no moderation, no 'spam points', no nothing. You won't even know that it's working."
* "I haven't had anything to 'deal' with in several weeks. That's a nice thing. I've also had a bunch of folks leave legitimate comments that have gotten through. It's all good."

== Upgrade Notice ==
= 5.0 =
Fixed Depreciated Funcions & Made the code truly HTML5 compliant.

== Changelog ==
= 5.0 =
* Forked from wp-hashcash-extended
* Fixed Depreciated Funcions
* Updated code to be HTML5 complaint.

= 4.7 =
* Fixed capability for WordPress 3.1+

= 4.6 =
* Removed links from the blog linking back to Hashcash homepage to comply with WordPress.org plugin guidelines. Props Ryan Hellyer.

= 4.5.1 =
* Fix a javascript error

= 4.5 =
* Support clean interoperation with jQuery and Prototype
* Protect BuddyPress (BP) signup pages

= 4.4 =
* Admin users can now comment from Dashboard
* Tested on WP 2.9.2 in Chrome, IE, and FF
* Fix a potential JS error

= 4.1 =
* Added a new options page under Options, Wordpress Hashcash
* Fixed XHTML standards compliance
* Added validation options for pingbacks and trackbacks (stolen from here)
* Added a logging option for moderated comments

= 4.0.5 =
* Added an option for handling comments via moderation, the akismet queue, or deletion
* Removed database dependencies
* Removed error message for hash fail
* Added the noscript tag for users without javascript
* Corrected the widget formatting
* Changed zip file format from winrar to 7zip, hopefully it will be more compatible

= 4.0.4 =
* Removed version checking
* Removed an unnecessary link element in the head section

= 4.0.3 =
* Suppress errors on loading remote version by any method
* Fix typo-bugs everywhere affecting the widget reporting, date checking, etc
* Strip tags from remote version
* Try various methods to get remote version, ignore if we can't open sockets
* Fix a bug with one of the javascripts
