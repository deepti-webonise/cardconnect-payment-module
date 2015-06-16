=== Woo Commerce CardConnect Payment Gateway ===
Contributors: jle1
Tags: woocommerce, payment, gateway, cardconnect
Requires at least: 3.5
Tested up to: 4.2.2
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

The WooCommerce CardConnect Payment Gateway allows you to accept Visa, MasterCard, American Express and Discover payments in your WordPress WooCommerce store. CardConnect payment processing tokenizes sensitive data, safeguarding your customers from a data breach and removing the burden of PCI compliance.

CardConnect allows customers to checkout with a saved card.  Card details are saved on CardConnect servers and not on your site. The plugin supports the Woo Commerce Subscription extension.

Visit [CardConnect](http://cardconnect.com) for more information.

Please note that WooCommerce (2.1+) must be installed and active.

== Installation ==

* Upload plugin files to your plugins folder, or install using WordPress built-in Add New Plugin installer;
* Activate the plugin;
* Configure the plugin settings in WooCommerce > Settings > Checkout > Card Connect
* Contact your CardConnect representative for your merchant ID and credentials

== Frequently Asked Questions ==

= Does this plugin require that an SSL be installed? =

It is recommended that you install an SSL on your site for the checkout page, however the plugin does not require it.

= Is there an option for a sandbox account for testing? =

Yes. When you sign-up for a merchant account with CardConnect you will receive credentials for a sandbox account as well as a live account.

= Are there any special requirements needed from my hosting provider? =

You may need to request that your hosting provider open certain ports. Specific instructions will be provided when you activate your CardConnect account.

= Who do I contact if I need assistance? =

For further info or support, contact your CardConnect representative.

== Changelog ==

= 1.0.0 =
* Public Release
* Bug Fixes
* UI Tweaks

= 0.6.0 =
* New feature: Now integrate with WooCommerce Subscriptions

= 0.5.0 =
* New feature: Allow customer to store payment information on CardConnect servers for easy re-use
* Better tokenization handling
* Allow for template overrides

= 0.4.0 =
* Implement immediate tokenization of credit card number, with improved error feedback
* Allow unique CardConnect site names to be specified in gateway configuration
* Allow customer to supply discrete cardholder name if necessary
* UI Tweaks
* Bug fixes

= 0.1.0 =
* Beta release. Initial functionality includes tokenized transactions, easy toggle between prod/test environments,
and auth only/capture transactions.

== Upgrade Notice ==

= 1.0.0 =
Initial repository version
