=== Enhanced Meta Widget===
Contributors: NeuroDawg
Donate Link: http://neurodawg.worpdress.com/enhanced-meta-widget/
Version: 1.6
Tags: meta, widget, links, admin, administration, dashboard
Requires at least: 2.8
Tested up to: 2.8.4
Stable Tag: 1.6
License: GPL v.3

This plugin replaces the meta sidebar included with WordPress, and displays links based upon user roles.

== Description ==
This plugin replaces the meta sidebar included with WordPress, and displays links based upon user roles. It is also a multi-widget; it can be used in multiple instances on the same or different sidebars. Want your admin links only on a right-hand sidebar, but your general meta links on the left? Can be done. Want one widget just for the standard meta RSS and wordpress.org links, and a section below, with a different title for admin links? That can be done too, just add two separate widgets to the same sidebar and enable different options.

If a user is not logged in it will present a log-in form, as well as a link to register (if allowed in site settings).

For logged in users all links are based upon that user's role/permissions. Can the user write posts? A link for "Write Post" is presented. On a post/page that the user can edit? There are links for "Edit Post" or "Edit Page". If the user is an administrator, then there are links to all the main sections of the administrator pages, plus a few of the subsections like "Manage Widgets" and "Manage Drafts".

There are also links for the standard entries and comments RSS feeds, as well as to wordpress.org, like in the original meta widget.

All links can be turned on/off, and a different title for the sidebar widget can be set in the settings.

Please note that this plugin/widget was written using the new programming method in WP 2.8, and will not work with previous versions.

This plugin was using ideas gathered from a number of different WordPress plugins. Please see the Credits and Copyright information at the end of the readme file for further information.

== Installation ==
1. Extract admin-links-enhanced.php into your wp-content/plugins folder (or any subfolder)
2. Activate the plugin in Wordpress
3. Add the widget to your page
4. Set the options to select which links you want displayed

If you want to keep the original meta widget, then comment out or remove line #30 in the php file, it's commented.

Please inform me of any problems/issues. Recommendations for improvement are always welcome!

== Frequently Asked Questions ==

None so far.

== Screenshots ==
1. **Sidebar**: This is what the widget looks like when you're logged in as admin. (Not all possible links are shown).
2. **Sidebar**: This is what the widget looks like when a user isn't admin, but can edit or write a new post.
3. **Sidebar**: This is the sidebar when you're not logged in. Note that the widget includes both the "meta" and "Log In" sections. (Shown using the WordPress Classic 1.5 theme.)
4. **Sidebar**: Sidebar showing login form with the WordPress Default 1.6 theme.
5. **Options**: You can select which links you want displayed. No links are displayed unless they're relevant to the currently logged in user, on the page they're currently viewing.

== Change Log ==

= 1.6 =
* Coded for I18n. Now just looking for translators.
* As part of I18n, the POT file is included with each distribution.
* Fixed bug where $after_widget was being displayed inappropriately.
* Fixed improper insertion of a couple of br tags.
* Moved the display of "username is logged in." to the bottom of the sidebar widget. I didn't like it at the top.

= 1.5 =
* Added New Features
  *Can choose to display login link or login form*
  *Separated logout link from login link/form*
  *Display "username is logged in."*
* Fixed display of login form if it's the only thing showing on the sidebar (now surrounded by $before_widget and $after_widget).

= 1.4.1 =
* Fixed a typo that prevented the "edit this post" link from working correctly.

= 1.4 =
* Fixed problem with display of too many line breaks/spaces showing in sidebar depending on the options selected.

= 1.3 =
* Fixed error that would place widget title on the sidebar without content if user logged out and if links for register, RSS, and wordpress.org are not to be visible (log in form still displays).
* Fixed a couple of spelling and html code errors

= 1.2 =
* Fixed the proper display of the "register link" based upon whether or not the Administration > Settings > General > **Membership: Anyone can register** box is checked.
* Fixed the proper display of RSS and wordpress.org links for users that are not logged in.

= 1.1 =
* Fixed to show the RSS and wordpress.org links for logged in, non-admin, users.

= 1.0 =
* Initial release.

== Credits and Copyright ==
Copyright 2009 NeuroDawg.

The devlopment of this plugin took inspiration from the plugins, Admin Links Plus (http://alicious.com/admin-links-plus-sidebar-widget/), Admin Links (http://kdmurray.net/2007/08/14/wordpress-plugin-admin-links-widget/) and Quick Admin Links (http://www.4-14.org.uk/wordpress-plugins/quick-admin-links), created by pbhj, Keith Murray (kdmurray), and Mark Barnes, respectively.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

A copy of the GNU General Public License can be downloaded from http://www.gnu.org/licenses