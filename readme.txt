=== SodaHead Polls ===
Contributors: SodaHead.com
Tags: poll, polls, polling, vote, wppolls, sodahead, surveys, widget
Version: 2.0.8
Requires at least: 2.8
Tested up to: 3.5.1
Stable tag: trunk

== Description ==

**Quickly and easily create free, customized polls for your blog with the best WordPress poll widget available.**

Add polls to your blog to create an engaging experience for your audience and keep them coming back for more.

Many of the web's top publishers, including ABCnews, Fox News, NYPost.com, and Technorati, have selected SodaHead as their poll of choice to collect and display results in real-time.

**SodaHead polls are easy to customize and even easier to publish:**

* Customize size, colors, and background skins - add your logo
* Include images and videos
* Save and organize themes for future use
* Include 10+ answer choices
* Security against vote fraud (flash-based)
* Grabbable by readers... make your poll go viral!
* One-click post

= Additional Features: =

* Wordy answers - over 250 characters allowed per answer
* One-click sharing to Twitter and Yahoo
* Optional voter comments
* Optionally add your poll to the SodaHead network for more exposure!

All of your polls and themes are stored so you can return later to add or update as desired.

Polls enhance interactivity and "stickiness" by engaging your audience and encouraging readers to come back to your blog to read results. Whether you blog about the presidential elections just around the corner, something controversial in the news, or the latest celebrity gossip, your readers can actively participate in the discussion through polls. Chances are they'll send their friends to vote too, increasing traffic and interactivity on your site.

= About Sodahead: =

SodaHead is a dynamic discussion community where you can discover, debate and discuss issues that get you fired up. Over 1.5 million SodaHeads share their unique views on hot topics, breaking news and controversial issues, and a diverse panel of staff writers provide original and exclusive content daily. With poll widgets, discussions can by shared and syndicated across the web, allowing publishers to leverage the interactivity of SodaHead on their own sites.

== Installation ==

= Installation Instructions =

To install the plugin, you can use the built-in installer and upgrader in WP-Admin, or install manually by following these steps:

1. Download the plugin here and use your FTP program to upload it to your wp-content/plugins directory. In addition to uploading all the php files to /wp-content/plugins/, make sure to also move the extracted folder "sodahead-polls" into this directory
1. Open the Wordpress Admin Interface (WP-Admin) and click the "Plugins" heading
1. Find the "SodaHead Polls" plugin in the listing, and click the "Activate" link

= Usage =

**Adding a poll to a post**

1. Click on the "Posts" heading in the WordPress Admin Interface (WP-Admin)
1. Click on "Add New"
1. Click on the SodaHead Icon in the "Upload/Insert" listing
1. Screen will open up to create and embed a poll

**Adding a poll to the sidebar**

1. Click on the "Appearance" heading in the WordPress Admin Interface (WP-Admin)
1. Click on "Widgets"
1. Find "Polls" and drag it into the desired sidebar on the right
1. Open the drop down under polls. You can now create or modify a poll site-wide. Don't forget to press save after you are done creating and customizing a poll

== Upgrade Notice ==

= 2.0 =

This upgrade will require you to re-configure your widget(s) on the side bar.

= 2.0.2 =

In order to get the poll widget showing in the sidebar showing in
Internet Explorer, push the "save" button on all your poll widget
in the Appearance->widget section.

= 2.0.4 =

Fix Medium risk level vulnerabilities issue HTB22893 and HTB22894

= 2.0.5 =

Fix Regular expression sanitizer

= 2.0.6 =

Fix question ask form bug.

= 2.0.7 =

Fix poll customizer pop-up window on sidebar widget in admin

= 2.0.8 =

Fix bug preventing a sidebar poll widget to appear.

== Screenshots ==

1. How to create a poll in a blog post
1. Question create screen
1. Options for the site-wide widget
1. One of the many looks of the widget. It is fully customizable

== Changelog ==

= 2.0.8 =

* Add SWFObject as a general dependency.

= 2.0.7 =

* YUI and thickbox JS are now queue-loaded on admin init

= 2.0.6 =

* html patch to jQuery got removed
* JS/HTML are now separated during transaction
* Plugin is setup to talk to wpapi

= 2.0.5 =

* Fix plugin

= 2.0.4 =

* Fix vulnerability HTB22893

= 2.0.3 =

* Fix vulnerability HTB22894

= 2.0.2 =

* Fix bug when sidebar polls were not showing on Internet Explorer
* Monkey patch jquery.html method to ensure JS eval.

= 2.0.1 =

* Logout user on deactivate

= 2.0 =

* Adds SodaHead media selector to the plugin.
* Adds Videos
* Uses more built-in functions from WordPress.
* Allows usage without registration.
