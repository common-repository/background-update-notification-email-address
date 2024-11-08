=== Background Update Notification Email Address ===
Contributors: iwebsolutions, mustardbees, lauravaq
Tags: admin, manage, plugin, updates, background updates, automatic updates
Requires at least: 3.7
Tested up to: 4.8
Stable tag: 1.1.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Change the email address update notifications are sent to following an automatic background update.

== Description ==

**This plugin changes the email address update notifications are sent to following an automatic background update.**

Automatic background updates were introduced in WordPress 3.7. An email notification is sent following the success or failure. The email is sent to the website administrator specified in WordPress under Settings > General. This may not always be the best recipient.

This plugin is ideal for those who manage WordPress on their clients behalf. The client carries on receiving WordPress emails as before, with automatic background update notifications being redirected to the developers email address specified in this plugins settings.

We originally [published a solution](https://www.iweb.co.uk/2013/10/change-wordpress-auto-update-email-address/) following the release of WordPress 3.7.1. This plugin provides a simple interface for setting the email address without having to touch code.

**Once installed, navigate to Settings > Update Notifications. From here you can set the email address where background update notifications should be sent to. Background update notifications can be sent to multiple recipients by entering a comma-separated list of email addresses.**

== Installation ==

= Using The WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Search for 'Background Update Notification Email Address'
3. Click 'Install Now'
4. Activate the plugin on the Plugin dashboard
5. Set email address under Settings > Update Notifications

= Using FTP =

1. Download and extract the plugin
2. Upload the `background-update-notification-email-address` folder to the `/wp-content/plugins/` directory.
3. Activate the plugin in the Plugin dashboard
4. Set email address under Settings > Update Notifications

== Screenshots ==

1. Settings page.

== Changelog ==

= 1.1.1 =
* Maintain backwards compatibility with previous option format, accept either a string or array of email addresses.

= 1.1.0 =
* Add multiple email address support. You can now enter a comma-separated list of email addresses.
* Save default value when we prepare the option.
* Delete settings when the plugin is uninstalled.

= 1.0.3 =
* Move localisation functions to admin file as there are no public facing strings.

= 1.0.2 =
* Prepare option if it does't exist.

= 1.0.1 =
* Improved configuration instructions.

= 1.0.0 =
* Initial release.