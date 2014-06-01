# Changelog

## 5.1
* Add WordPress 3.8 styles

## 5.0 
* Forked from wp-hashcash-extended
* Fixed Depreciated Functions
* Updated code to be HTML5 complaint.

## 4.7
* Fixed capability for WordPress 3.1+

## 4.6
* Removed links from the blog linking back to Hashcash homepage to comply with WordPress.org plugin guidelines. Props Ryan Hellyer.

## 4.5.1
* Fix a javascript error

## 4.5
* Support clean interoperation with jQuery and Prototype
* Protect BuddyPress (BP) signup pages

## 4.4
* Admin users can now comment from Dashboard
* Tested on WP 2.9.2 in Chrome, IE, and FF
* Fix a potential JS error

## 4.1
* Added a new options page under Options, Wordpress Hashcash
* Fixed XHTML standards compliance
* Added validation options for pingbacks and trackbacks (stolen from here)
* Added a logging option for moderated comments

## 4.0.5
* Added an option for handling comments via moderation, the akismet queue, or deletion
* Removed database dependencies
* Removed error message for hash fail
* Added the noscript tag for users without javascript
* Corrected the widget formatting
* Changed zip file format from winrar to 7zip, hopefully it will be more compatible

## 4.0.4
* Removed version checking
* Removed an unnecessary link element in the head section

## 4.0.3
* Suppress errors on loading remote version by any method
* Fix typo-bugs everywhere affecting the widget reporting, date checking, etc
* Strip tags from remote version
* Try various methods to get remote version, ignore if we can't open sockets
* Fix a bug with one of the javascripts