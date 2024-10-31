=== Pushwoosh ===
Contributors: Pushwoosh
Website link: https://www.pushwoosh.com
Tags: pushwoosh, push notifications, push
Requires at least: 3.0.1
Tested up to: 5.5.3
Stable tag: 2.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Push notifications plugin for WordPress by Pushwoosh. Send push notifications when you publish or update a post or a page.

== Description ==

Push notifications plugin for WordPress by <a href="https://pushwoosh.com">Pushwoosh</a>. It helps you automatically send push notifications when you publish or update a post or page, using Pushwoosh Remote API. The plugin also notifies users when scheduled posts are published.

Please note that you must have at least Developer account with Pushwoosh in order to use the plugin. The plugin is handy to send <a href="https://docs.pushwoosh.com/platform-docs/pushwoosh-sdk/web-push-notifications">Web Push Notifications</a> to your readers. You can also connect the plugin to mobile app and send push messages to your users’ mobile devices.

Please see the <a href="https://docs.pushwoosh.com/platform-docs/pushwoosh-sdk/cross-platform-frameworks/wordpress">WordPress Plugin Guide</a> page on our website.

== Installation ==
1. Download the Pushwoosh plugin.
2. Unzip and upload it to your plugins directory ("/wp-content/plugins" is default)
3. Configure the plugin on its settings page (Set Pushwoosh Application Code and API Access token)
4. That's it - enjoy pushing news to all your visitors!

== Screenshots ==

1. Pushwoosh Administration Panel
2. Pushwoosh Publishing Widget

== Changelog ==

= 2.3.23 =
* Now "Send push" checkbox works properly with scheduled posts
* There are updates in documentation links
* Tested plugin for latest Wordpress releases

= 2.3.22 =
* Fixed plugin information

= 2.3.21 =
* Fix bug: do not save push information for scheduled posts after WP update

= 2.3.20 =
* Fix bug: do not send push for scheduled posts

= 2.3.19 =
* Firefox icon and title support

= 2.3.18 =
* Fix bug: do not send push on every post editing

= 2.3.17 =
* Fix bug: push content from title instead of message box

= 2.3.16 =
* Add filter for push segmentation

= 2.3.15 =
* Fix push on restore page from revision

= 2.3.14 =
* Chrome url support

= 2.3.13 =
* Chrome icon and title support

= 2.3.12 =
* Fix error with un-trashed posts

= 2.3.11 =
* Add support of custom post types

= 2.3.10 =
* Refactoring plugin for shared hosting

= 2.3.9 =
* Refactoring get URL logic

= 2.3.8 =
* Saving push notification data in widget for pending post

= 2.3.7 =
* Saving push notification data in widget for draft post

= 2.3.6 =
* Saving push notification data in widget for draft post

= 2.3.5 =
* Fixed bug with twice push

= 2.3 =
* Added default Safari title field in plugin settings.
* If Safari message field is empty, WordPress post title is used as a push text.

= 2.2 =
* Added WordPress 3.8 support

= 2.1 =
* Fixed bugs

= 2.0 =
* Integration Safari notifications

= 1.1 =
* Support for PHP 5.2
