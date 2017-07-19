=== Connections Business Directory Login  ===
Contributors: shazahm1@hotmail.com
Donate link: http://connections-pro.com/
Tags: address book, addressbook, business, businesses, business directory, business-directory, business directory plugin, directory plugin, directory widget, church, contact, contacts, connect, connections, directory, directories, member directory, members directory, members directories, people, profile, profiles, shortcode, staff, user, users, wordpress business directory, wordpress directory, wordpress directory plugin, wordpress business directory, login, form, login form, widget, login widget
Requires at least: 4.1
Tested up to: 4.8
Stable tag: 2.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Extension for the Connections Business Directory that adds a shortcode and widget to display a login form.

== Description ==

This is an extension plugin for the [Connections Business Directory Plugin](http://wordpress.org/plugins/connections/) please be sure to install and active it before adding this plugin.

What does this plugin do?
It adds an [entry content block](http://connections-pro.com/documentation/login/#Content_Block), a [shortcode](http://connections-pro.com/documentation/login/#Shortcode) and a [highly configurable widget](http://connections-pro.com/documentation/login/#Widget) which displays a login form when a user is not logged into your site.

Ok, great, but how does this benefit me?
Well, if you have the directory setup to require login, you can add the [[connections_login] shortcode](http://connections-pro.com/documentation/login/#Shortcode) to the [login required message setting](http://connections-pro.com/documentation/settings/#Require_Login) (or any page you want, the shortcode is not limited to this setting). When it is added and the user is not logged in and visit your directory, they'll be shown your message plus the login form.

The content block login form and the login widget are best used with [Link](http://connections-pro.com/add-on/link/) installed and activated. You can setup the login form content block to be shown on a single entry, that way when a user visits the page and they are not logged in, they'll be shown a login form right on their page. Alternatively, you could use the widget which will only be displayed on the single entry page when a user is not logged in. It's your choice, you could use either one or both.

[Checkout the screenshots.](http://connections-pro.com/add-on/login/)

Here are other great extensions that enhance your experience with the Connections Business Directory:

* [Business Hours](http://wordpress.org/plugins/connections-business-directory-hours/)
* [Toolbar](http://wordpress.org/plugins/connections-toolbar/)
* [Income Levels](http://wordpress.org/plugins/connections-business-directory-income-levels/)
* [Education Levels](http://wordpress.org/plugins/connections-business-directory-education-levels/)
* [Languages](http://wordpress.org/plugins/connections-business-directory-languages/)

== Installation ==

= Using the WordPress Plugin Search =

1. Navigate to the `Add New` sub-page under the Plugins admin page.
2. Search for `connections business directory login`.
3. The plugin should be listed first in the search results.
4. Click the `Install Now` link.
5. Lastly click the `Activate Plugin` link to activate the plugin.

= Uploading in WordPress Admin =

1. [Download the plugin zip file](http://wordpress.org/plugins/connections-business-directory-login/) and save it to your computer.
2. Navigate to the `Add New` sub-page under the Plugins admin page.
3. Click the `Upload` link.
4. Select Connections Business Directory Login zip file from where you saved the zip file on your computer.
5. Click the `Install Now` button.
6. Lastly click the `Activate Plugin` link to activate the plugin.

= Using FTP =

1. [Download the plugin zip file](http://wordpress.org/plugins/connections-business-directory-login/) and save it to your computer.
2. Extract the Connections Business Directory Login zip file.
3. Create a new directory named `connections-business-directory-login` directory in the `../wp-content/plugins/` directory.
4. Upload the files from the folder extracted in Step 2.
4. Activate the plugin on the Plugins admin page.

== Frequently Asked Questions ==

None yet...

== Screenshots ==

[Screenshots can be found here.](http://connections-pro.com/add-on/login/)

== Changelog ==

= 2.0.1 03/17/2016 =
* NEW: Introduce the `cn_login_widget_link_anchor` filter.
* BUG: Use correct bbPress function to return the user topics created URL.
* TWEAK: Default logout link redirect URL to the current page.
* OTHER: Correct version number in changelog section of readme.txt.

= 2.0 03/02/2016 =
* FEATURE: Option to configure widget to be visible site wide in the sidebar or limited to only the entry detail/profile page in Connections.
* FEATURE: Configurable widget title based on if user is logged in or not.
* FEATURE: Option to disable the "Remember me" checkbox in the login form.
* FEATURE: Option to disable the "Lost Password" link in the login form.
* FEATURE: Add support for adding custom links which can be displayed to a logged out user.
* FEATURE: Option to display the users Gravatar when they are logged in.
* FEATURE: Option to set the Gravatar's image size.
* FEATURE: Option to display the user's admin profile link.
* FEATURE: Option to display the logout link.
* FEATURE: Add support for adding custom links which can be displayed to a logged in user.
* FEATURE: Support for bbPress.
* FEATURE: Support for BuddyPress.
* FEATURE: Extension support and integration with the [Link extension](http://connections-pro.com/add-on/link/).
* FEATURE: Add shortcode options to the [[connections_login] shortcode](http://connections-pro.com/documentation/login/#Shortcode) so the labels can be configured.
* NEW: Introduce the `cn_login_supported_tokens` filter.
* NEW: Introduce the `cn_login_avatar_size` filter.
* NEW: Introduce the `cn_login_logout_url` filter.
* NEW: Introduce the `cn_login_login_url` filter.
* NEW: Introduce the `cn_login_replace_tokens` filter.
* NEW: Introduce the `cn_login_image_types` filter.
* NEW: Introduce the `cn_login_widget_update_settings` filter.
* NEW: Introduce the `cn_login_before_widget_common_settings` action.
* NEW: Introduce the `cn_login_after_widget_common_settings` action.
* NEW: Introduce the `cn_login_before_widget_logged_out_settings` action.
* NEW: Introduce the `cn_login_after_widget_logged_out_settings` action.
* NEW: Introduce the `cn_login_after_widget_logged_in_settings` action.
* NEW: Introduce the `cn_login_widget_before` action.
* NEW: Introduce the `cn_login_widget_logged_in_before` action.
* NEW: Introduce the `cn_login_widget_logged_in_after` action.
* NEW: Introduce the `cn_login_widget_logged_out_before` action.
* NEW: Introduce the `cn_login_widget_logged_out_after` action.
* NEW: Introduce the `cn_login_widget_after` action.
* NEW: Introduce the `cn_login_display_image_{$type}` action.
* NEW: Introduce the `cn_login_widget_lost_password_url` filter.
* NEW: Introduce the `cn_login_widget_register_url` filter.
* NEW: Introduce the `cn_login_widget_register_url` action.
* NEW: Introduce the `cn_login_widget_{$context}_links` filter.
* NEW: Introduce the `cn_login_widget_before_{$context}_links` action.
* NEW: Introduce the `cn_login_widget_after_{$context}_links` action.
* TWEAK: Escape translated strings.
* I18N: Update POT file.
* I18N: Update es_ES PO/MO files.

= 1.1 07/06/2015 =
* BUG: Load the text domain immediately on plugins_loaded action so the translation files will be loaded.
* BUG: Remove stray period from version number.
* TWEAK: Refactor loadTextDomain() so it is consistent with the other extensions for Connections.
* I18N: Include the POT file.
* I18N: Add a Spanish (Spain) translation (machine translated).
* DEV: Update .gitignore.

= 1.0 08/08/2014 =
* Initial release.
