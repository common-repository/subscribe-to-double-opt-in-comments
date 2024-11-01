=== Subscribe to Double-Opt-In Comments ===
Contributors: Tobiask
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3736248
Tags: comments, subscribe, double opt in, kommentar, abonnieren, opt in, optin, kommentare, benachrichtigung, doi, doube-opt-in, comment, blog post
Requires at least: 4.7.0
Tested up to: 5.7.2
Stable tag: 6.6.12
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allows readers to receive notifications via e-mail of new comments that are posted to a blog post. The first e-mail for a blog post is validated with a double-opt-in feature to ensure the user itself registered for notifications. Based on version 2 of "Subscribe to Comments" from Mark Jaquith (http://txfx.net/).

== Changelog ==

= 6.6.12 =
* Tested with WP 5.7.2
* Fixed bug that broke the mail sending process

= 6.6.11 =
* Tested with WP 5.7

= 6.6.10 =
* Tested with WP 5.6

= 6.6.9 =
* Tested with WP 5.5.1

= 6.6.8 =
* Fixed PHP 7.2 warning
* Tested with WP 5.4.1

= 6.6.7 =
* Tested with WP 5.4.0

= 6.6.6 =
* Tested with WP 5.3.2

= 6.6.5 =
* Tested with WP 5.2.4
* Minor Bugfixes for strict error handling

= 6.6.4 =
* Tested with WP 5.2.2

= 6.6.3 =
* Tested with WP 5.1.1

= 6.6.2 =
* Removed deprecated functions

= 6.6.1 =
* Fixed non-visible checkbox (some themes were affected)

= 6.6.0 =
* Moved checkbox for subscriptions above the submit button
* Please help translating this plugin into your language: https://translate.wordpress.org/projects/wp-plugins/subscribe-to-double-opt-in-comments

= 6.5.9 =
* Added missing translations
* Fixed options page layout
* Please help translating this plugin into your language: https://translate.wordpress.org/projects/wp-plugins/subscribe-to-double-opt-in-comments

= 6.5.8 =
* Please help translating this plugin into your language: https://translate.wordpress.org/projects/wp-plugins/subscribe-to-double-opt-in-comments
* Fixed textdomain in plugin

= 6.5.7 =
* Please help translating this plugin into your language: https://translate.wordpress.org/projects/wp-plugins/subscribe-to-double-opt-in-comments
* Fixed textdomain in plugin

= 6.5.6 =
* Added new languages

= 6.5.5 =
* Removed unwanted space before checkbox text

= 6.5.4 =
* Tested up to 4.9.6
* Added FAQ entry for GDPR/DSGVO

= 6.5.3 =
* Tested up to 4.9.5
* Enabled translations through https://translate.wordpress.org/projects/wp-plugins/subscribe-to-double-opt-in-comments - please help translating!

= 6.5.2 =
* Checked DSGVO/GDPR requirements: this plugin stores the following additional information to the normal comment data of Wordpress: 
** flag if the user has received a doube-opt-in e-mail, 
** flag if the user successfully subscribed, 
** anonymous hash to identify the double-opt-in e-mail. 
* Thus no further actions are necessary to ensure DSGVO/GDPR compatibility. No personal user information is stored!
* Hint: Wordpress, by itself, stores the IP address of the user commenting! You have to ensure that this personal information is handled according to the law of your country!

= 6.5.1 =
* Bugfix PHP 7.1 Fatal error on subscription manager page (operator not supported for strings), thanks to sir-apfelot.de

= 6.5.0 =
* Compatibility checks

= 6.4.13 =
* Removed deprecated calls

= 6.4.12 =
* Fixed PHP 7.x constructor
* Removed deprecated calls
* Compatibility checks

= 6.4.11 =
* compatibility checks

= 6.4.10 =
* compatibility checks

= 6.4.9 =
* fixed layout bug

= 6.4.8 =
* security bug fix

= 6.4.7 =
* changed the e-mail which is sent to the user, the link now points directly towards the written comment

= 6.4.6 =
* checked with WP 4.1

= 6.4.5 =
* added nofollow to subscription management page, thanks to Monika, https://wordpress.org/support/topic/increase-of-error-404-comment-subscriptions
* fixed duplicated MIME version information in e-mails, thanks to jaegerschnitzel, https://wordpress.org/support/topic/invalid-header-17

= 6.4.4 =
* fixed call_user_func_array() bug, thanks to Shimapan

= 6.4.3 =
* improved code quality

= 6.4.2 =
* tested with WP 4.0
* new icon added - Icon made by <a href="http://www.freepik.com">Freepik</a> from <a href="http://www.flaticon.com">www.flaticon.com</a>

= 6.4.1 =
* fixed warning: illegal string offset

= 6.4.0 =
* small bugfixes

= 6.3.1 =
* removed deprecated mysql_*() calls

= 6.3.0 =
* tested with WP 3.9

= 6.2.1 =
* repaired wrong translations and generated a new .pot file

= 6.2.0 =
* removed deprecated code

= 6.1.8 =
* tested with WP 3.7.1

= 6.1.7 =
* tested with WP 3.6

= 6.1.6 =
* multisite bugfixes

= 6.1.5 =
* minor bugfixes

= 6.1.4 =
* bugfixes
* more translations

= 6.1.3 =
* .pot language file updated
* Screenshot update
* German translation update
* Copyright notice could be made invisible for customer projects, donation via paypal is appreciated!

= 6.1.2 =
* Tested with 3.4.1

= 6.1.1 =
* Added Romanian translation, big thanks to: Web Geek Science (<a href="http://webhostinggeeks.com/">Web Hosting Geeks</a>)

= 6.1.0 =
* Merged multisite and normal version!

= 6.0.10 =
* added new translation: Dutch. Thanks to Florian!
* minor bug fixes

= 6.0.9 =
* minor bug fixes

= 6.0.8 =
* added 3.3 support
* added multisite version, but currently disabled, you have to enable it manually if you like to

= 6.0.7 =
* fixed some minor bugs

= 6.0.6 =
* Added new language: Lithuanian (thx to Nata, webhostinghub.com)

= 6.0.5 =
* Fixed some HTML markup
* Fixed double footer problem
* Tested with 3.2

= 6.0.4 =
* Fixed headline bug 

= 6.0.3 =
* Fixed bug with lost footer (using own style)

= 6.0.2 =
* Added support for Portuguese (Brazilian) [thanks to Leandro]
* 3.1.3 compatible

= 6.0.1 =
* Fixed minor bugs

= 6.0 =
* Fixed Bugfix within deletion of subscriptions

= 5.9 =
* Changed apostrophe compatibility
* Minor bugfixes within e-mail sending function

= 5.8 =
* Minor bug fixes
* Checked WP 3.1 compatibility

= 5.7 =
* Minor bug fixes

= 5.6 =
* New css class to style the Verify-Page: verify_succeeded and verify_failed
* Higher security for generated verify-token implemented
* Improved code formatting

= 5.5 =
* Checked 3.0.4 compatibility
* Bugfix with standalone subscribe

== Upgrade Notice ==

Currently none.

== Description ==

Allows readers to receive notifications of new comments that are posted to an entry, after they successfully used the mandatory double-opt-in process to verify their e-mail address. 
First, the user will get an e-mail with a confirmation link, after the user has confirmed the subscription, he or she will be noticed about new comments. This reduces junk and other unwanted e-mail communication.
This plugin is based on Mark Jaquith´s "Subscribe to Comments" plugin. More information on my blog: <a href="https://sjmp.de/internet/subscribe-to-comments-mit-double-opt-in-pruefung/">sjmp.de</a>.

== Installation ==

The most used way is to use the WordPress plugin installation process in your admin panel. Just search for the plugin name and click "Install". After that, you can configure the plugin within its settings page.

Another, manual, way would be:

1. Upload all files to the "/wp-content/plugins/" directory
2. Activate the plugin through the "Plugins" menu in your WordPress admin panel
3. Set settings via "Settings" menu in WordPress
4. Ready, steady, go :)

Questions? Go to <a href="https://sjmp.de/internet/subscribe-to-comments-mit-double-opt-in-pruefung/">this page</a> and leave a comment!

== Frequently Asked Questions ==

= What do I need to know regarding the GDPR / DSGVO? =

This plugin stores the following information additionally to the regular WordPress comment data:
- flag if the user has received a doube-opt-in e-mail,
- flag if the user successfully subscribed,
- anonymous hash to identify the double-opt-in e-mail.

This plugin also uses cookies to:
- check if the user has commented on a blog post with a specific e-mail address (Name: comment_author_email_<random_hash>, Lifespan: stored for 1 year),
- check if the user has checked or unchecked the double-opt-in checkbox for a blog post (Name: subscribe_checkbox_<random_hash>, Lifespan: stored for 1 year),
- optionally if used, check whether the feature "subscribe to a blog post without commenting" was used by the user (Name: comment_withoutCommentToken_<random_hash>, Lifespan: stored for 3 days).

Hint: WordPress, by itself, stores the IP address of the user commenting! You have to ensure that this personal information is handled according to the law of your country!

= How can I change the place of the subscription checkbox? =

Use this code (within the loop) in your template file, to change the place of the checkbox: <code><?php show_subscription_checkbox(); ?></code>

= Can people subscribe manually without commenting? =

Yes, just place this code snippet in your template (outside the comments form): <code><?php show_manual_subscription_form(); ?></code>

= I use Hosteurope.de as my website hoster and I cannot send e-mails via this plugin =

See this (german) comment for a solution: <a href="http://www.sjmp.de/internet/subscribe-to-comments-mit-double-opt-in-pruefung/comment-page-10/#comment-4460">Go to Comment</a>

== Screenshots ==

1. Part of the settings menu.
2. The checkbox to subscribe to a comment thread.
