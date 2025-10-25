=== Cores Pay ===
Contributors: zARNIGOR
Tags: payment, invoice, shortcode, button, checkout
Requires at least: 5.0
Tested up to: 6.4
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Add payment link buttons to your WordPress site using simple shortcodes.

== Description ==

Cores Pay allows you to easily add payment link buttons to your WordPress posts and pages using a simple shortcode. Perfect for e-commerce sites, service providers, and anyone who needs to direct users to a payment or invoice page.

= Features =

* Simple `[cores_pay]` shortcode
* Customizable button text and URL
* Admin panel for easy configuration
* Responsive design that works on all devices
* Support for custom parameters
* Clean uninstall - removes all data when deleted
* Translation ready
* Accessibility friendly
* Secure and follows WordPress coding standards

= Usage =

After installation, simply add the shortcode to any post or page:

`[cores_pay]`

Or customize it with parameters:

`[cores_pay url="https://example.com/invoice" text="Pay Now" target="_self"]`

= Available Parameters =

* **url** - The invoice/payment page URL (overrides admin setting)
* **text** - Button text (overrides admin setting)
* **target** - Link target: `_blank` (new tab) or `_self` (same tab)
* **class** - Additional CSS class for custom styling

= Use in Templates =

You can also use the shortcode in your theme template files:

`<?php echo do_shortcode('[cores_pay]'); ?>`

== Installation ==

= Automatic Installation =

1. Log in to your WordPress admin panel
2. Navigate to Plugins > Add New
3. Search for "Cores Pay"
4. Click "Install Now" and then "Activate"

= Manual Installation =

1. Download the plugin ZIP file
2. Extract the ZIP file
3. Upload the `cores-pay` folder to `/wp-content/plugins/`
4. Activate the plugin through the 'Plugins' menu in WordPress

= Configuration =

1. Go to Settings > Cores Pay
2. Enter your invoice/payment page URL
3. Customize the button text (optional)
4. Save settings
5. Use the `[cores_pay]` shortcode on any page or post

== Frequently Asked Questions ==

= How do I use the shortcode? =

Simply add `[cores_pay]` to any post or page where you want the payment button to appear.

= Can I customize the button? =

Yes! You can customize the button text, URL, and styling through the admin panel or by using shortcode parameters.

= What parameters are available? =

Available parameters are:
* url - Payment page URL
* text - Button text
* target - Link target (_blank or _self)
* class - Additional CSS class

= Can I use multiple buttons on one page? =

Yes, you can use the shortcode multiple times on the same page with different parameters.

= How do I style the button? =

The button has the class `.cores-pay-button`. You can add custom CSS in your theme's stylesheet or use the `class` parameter to add your own class.

= Does it work with page builders? =

Yes, it works with most popular page builders including Elementor, WPBakery, Divi, and Gutenberg.

= Is it translation ready? =

Yes, the plugin is fully translation ready and includes a .pot file for translations.

= What happens when I uninstall the plugin? =

The plugin cleanly removes all its data from the database when uninstalled.

== Screenshots ==

1. Admin settings page
2. Button on frontend - desktop view
3. Button on frontend - mobile view
4. Shortcode in Gutenberg editor
5. Multiple buttons with different styles

== Changelog ==

= 1.0.0 =
* Initial release
* Shortcode functionality
* Admin settings panel
* Responsive design
* Translation ready
* Clean uninstall

== Upgrade Notice ==

= 1.0.0 =
Initial release. Install and enjoy!

== Additional Information ==

= Support =

For support, please visit our website or contact us through the support forum.

= Contribute =

If you'd like to contribute to the development of this plugin, please visit our GitHub repository.

= Privacy Policy =

This plugin does not collect or store any user data. It only stores the settings you configure in the WordPress admin panel.

== Credits ==

Developed with ❤️ for the WordPress community.

================================================================================
FILE: cores-pay/languages/cores-pay.pot
================================================================================
# Copyright (C) 2024 Cores Pay
# This file is distributed under the same license as the Cores Pay package.
msgid ""
msgstr ""
"Project-Id-Version: Cores Pay 1.0.0\n"
"Report-Msgid-Bugs-To: https://wordpress.org/support/plugin/cores-pay\n"
"POT-Creation-Date: 2024-01-01 00:00:00+00:00\n"
"MIME-Version: 1.0\n"
"Content-Type: text/plain; charset=UTF-8\n"
"Content-Transfer-Encoding: 8bit\n"
"PO-Revision-Date: 2024-MO-DA HO:MI+ZONE\n"
"Last-Translator: FULL NAME <EMAIL@ADDRESS>\n"
"Language-Team: LANGUAGE <LL@li.org>\n"

#: includes/class-cores-pay-admin.php:35
msgid "Cores Pay Settings"
msgstr ""

#: includes/class-cores-pay-admin.php:36
msgid "Cores Pay"
msgstr ""

#: includes/class-cores-pay-admin.php:62
msgid "Main Settings"
msgstr ""

#: includes/class-cores-pay-admin.php:72
msgid "Invoice URL"
msgstr ""

#: includes/class-cores-pay-admin.php:80
msgid "Button Text"
msgstr ""

#: includes/class-cores-pay-admin.php:99
msgid "Settings Saved"
msgstr ""

#: includes/class-cores-pay-admin.php:116
msgid "Save Settings"
msgstr ""

#: includes/class-cores-pay-admin.php:127
msgid "Configure your payment button settings below."
msg
