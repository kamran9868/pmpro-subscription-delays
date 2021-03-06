=== PMPro Subscription Delays ===
Contributors: strangerstudios
Tags: paid memberships pro, pmpro, memberships, ecommerce
Requires at least: 3.0
Tested up to: 3.5.1
Stable tag: .3.1

Adds a "delay" field to PMPro membership levels and discount codes, allowing you to set a variable-length period between your initial payment (if required) and recurring subscription payment.

== Description ==
This plugin requires Paid Memberships Pro to function.

Adds a "delay" field to PMPro membership levels and discount codes, allowing you to set a variable-length period between your initial payment (if required) and recurring subscription payment.

Set "delay" to be:
- a number of days (i.e. 7 for 1 week trial)
- a specific date (i.e. 2015-01-01)
- a date calculated based on signup (i.e. Y2-01-01 or Y1-M2-01)

== Installation ==

1. Upload the `pmpro-subscription-delays` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. That's it. No settings.

== Changelog ==
= .3.1 =
* Fixed bug where specific date delays were showing up as integers (e.g. 2015-01-01 would become just 2015) on the edit levels page.

= .3 =
* Added ability to set a specific date for the delay. Use format YYYY-MM-DD and the plugin will calculate the # of days until that date and use that for the delay value.

= .2 =
* Now adds delay box to basic levels as well as discount codes.
* Adds "after your X day trial" to the end of the level cost text.
