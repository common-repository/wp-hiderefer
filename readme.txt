=== WP-HideRefer ===
Contributors: ulfben
Donate link: https://www.amazon.com/gp/registry/wishlist/2QB6SQ5XX2U0N/105-3209188-5640446?reveal=unpurchased&filter=all&sort=priority&layout=standard&x=21&y=17
Tags: anonymise, anonymize, blank referrer, hide referrer, mask, privacy, referral, hiderefer, referer, private
Requires at least: 3.9
Tested up to: 5.1.1
Requires PHP: 5.2
Stable tag: 1.12
License: GPLv2 or later

WP-HideRefer adds proxies to your outgoing links, keeping your site private! 

== Description ==

When your readers follow links from your blog, the linked site can see where they come from. Thus; your blog is known by every site you've ever linked to.

WP-HideRefer adds proxies to your outgoing links, keeping your site private! 

There are many plugins to anonymize links. What makes WP-HideRefer better is:

* it's 100% WordPress API compliant
* it's entirely server-side (= cacheable & no JavaScript!)
* therefore; supports [infinite-scroll](http://wordpress.org/extend/plugins/infinite-scroll/) (AJAX / streaming)
* it correctly filters your feeds and comments
* [it can handle your manually anonymized links](http://wordpress.org/extend/plugins/wp-hiderefer/faq/)!


//*[Ulf Benjaminsson](http://www.ulfbenjaminsson.com)*

(Please note that WP-HideRefer requires PHP 5 or newer.)

== Changelog ==

= 1.12 =
Tested for WordPress 5.x and PHP 7.x

= 1.11 =
Don't display warnings to end user when HTML is poorly formated.

= 1.1 =
Handle relative links correctly (ergo; don't proxy internal links)

= 1.0 =
Public release.

== Upgrade Notice ==

= 1.11 = 
Update to avoid displaying warnings over poorly formated HTML.

= 1.1 = 
Update to handle internal (relative) links correctly.

= 1.0 =
First release.

== Frequently Asked Questions ==
= What's the White List for? =
Once the plugin is activated it redirects all links via a proxy, except for the URLs you enter in this list.

If you used to manually add proxies to your links, add those proxies to the White List to avoid double-proxying. You should also white list your own domain.

= What anonymizing services are supported? =
You can use any service which runs of URL parameters. 

== Installation ==

1. Extract the `wp-hiderefer`-folder and transfer it to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to Settings->WP-HideRefer to adjust settings.

== Screenshots ==

1. The settings panel

== Additional Notes ==
Copyright (C) 2012-2019 Ulf Benjaminsson (hello at my full name dot com)

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
