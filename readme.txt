=== WordPress PayPal ===
Contributors: naa986
Donate link: http://wphowto.net/
Tags: paypal, button, e-commerce, sell
Requires at least: 3.0
Tested up to: 4.1
Stable tag: 1.0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Accept PayPal payments in WordPress

== Description ==

This plugin allows you to easily create PayPal Buy Now, Add to Cart, Donation or Subscription type buttons. It generates dynamic buttons using shortcodes that enable PayPal checkout on your WordPress site. 

Once you have installed this plugin you need to go to the settings menu to configure some default options (WP PayPal -> Settings).

* PayPal Email: Your PayPal email address
* Currency Code: The default currency code

In order to create a button insert the shortcode like the following:

*PayPal Buy Now*

Buy Now buttons are for single item purchases. In order to create a buy button you need to specify it in the button parameter of the shortcode.

`[wp_paypal button="buynow" name="My product" amount="1.00"]`

*PayPal Add to Cart*

Add To Cart buttons let users add multiple items to their PayPal shopping cart and checkout.

`[wp_paypal button="cart" name="My product" amount="1.00"]`

*PayPal Donation*

Donation buttons let you accept donations from your users.

`[wp_paypal button="donate" name="My product" amount="1.00"]`

*PayPal Subscription*

Subscribe buttons let you set up payment subscriptions. 

`[wp_paypal button="subscribe" name="My product" amount="1.00" recurrence="1" period="M"]`

For detailed documentation please check out the [WP PayPal Plugin](http://wphowto.net/wordpress-paypal-plugin) page.

== Installation ==

1. Go to the Add New plugins screen in your WordPress Dashboard
1. Click the upload tab
1. Browse for the plugin file (wp-paypal.zip) on your computer
1. Click "Install Now" and then hit the activate button

== Frequently Asked Questions ==

= Can I accept PayPal payments in WordPress using this plugin? =

Yes.

== Screenshots ==

1. PayPal Button Demo
2. PayPal Orders

== Upgrade Notice ==
none

== Changelog ==

= 1.0.1 =
* First commit
