=== MCE Accessible Language Change ===
Contributors: Sylvia Egger (sprungmarker.de)
Donate link: http://sprungmarker.de
Tags: editor, WYSIWYG, buttons, language change, accessibility, tinymce, rich text editor, accessible, language
Requires at least: 3.0
Tested up to: 3.0.1
Stable tag: trunk
License: GNU General Public License v2.0

Adds language change buttons in the WordPress WYSIWYG editor.

== Description ==

Adds language change buttons in the WordPress WYSIWYG editor.

A very light weight plug-in with two button for adding language change. The buttons will
be added in the first row of the editor.

First you can add language changeon the basis of an span element. Just highlight the word
or phrase you want to add language change, klick on the "lang" button an add the appropriate
language (e.g. "fr" for a french word or phrase).

Second you can add language change to existing html elements as paragraphs, headlines and links.
Just klick in the context of a block element, klick on the button "lang attr" and add the appropriate language
(e.g. "fr" for a french word or phrase).

The plugin ist localized for englisch and german; please let me know if you would like additional
localizations added.

Hoping to add more features in a future update.

== Installation ==

1. Upload `mce-accessible-lang` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. To show your language change in the editor - not on your website:

   If your have already editor-style.css in your theme, you have to copy the styles into your editor-styles.css
   to get your language changes visible.
   If you don't have editor-styles.css in your theme, you can either copy the one in the plugin folder (css > editor-styles.css)
   to your theme folder or you can use the default editor-styles css of the plugin.
   
---- CSS styles begin ----
span[lang],
.lang {
    background: #f8f8f8;
    border: 1px solid #d2d0ce;
    padding: 2px;
}
---- CSS styles end ----

== Frequently Asked Questions ==

= No questions right now =

== Screenshots ==

1. The editor with the new button for language change "lang" and "lang attr" and showing the language change in the text highlighted.
2. The editor popup showing language change options.
3. The editor popup showing language attributes options.

== Changelog ==

=1.0=

* First release

== Upgrade Notice ==

= 1.0 =
No upgrades right now.