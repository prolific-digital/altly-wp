=== Altly ===
Contributors: millertchris
Donate link: https://altly.ai
Tags: accessibility, alt text, AI, images, seo
Requires at least: 5.6
Tested up to: 6.7
Requires PHP: 7.2
Stable tag: 0.0.1
License: GPL-2.0-or-later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Altly is a cutting-edge plugin that seamlessly integrates Altly’s AI-powered alt text generation into your WordPress website, transforming your media library into an accessibility and SEO asset.

== Description ==
Altly is a cutting-edge plugin that seamlessly integrates Altly’s AI-powered alt text generation into your WordPress website, transforming your media library into an accessibility and SEO asset. By automatically creating detailed, optimized alt text without overwriting your existing content—and allowing for manual adjustments when needed—Altly saves you time, ensures compliance with accessibility standards, and boosts your site’s search engine performance.

== Installation ==
1. Upload the plugin files to the `/wp-content/plugins/altly` directory, or install the plugin through 
   the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Navigate to **Media > Generate Alt Text > Settings** to enter your API license key.
4. Use the dashboard to view images missing alt text, bulk generate alt text, or clear alt text as needed.

== Frequently Asked Questions ==
= How does this plugin generate alt text? =
Altly sends images from your media library to an external AI service which analyzes them and returns descriptive alt text. 
This text is then saved as the image's alt attribute.

= Is my API key secure? =
Yes. The plugin uses WordPress nonces and capability checks to ensure that API operations are performed only by authorized 
users. However, ensure you only use API keys that are meant for public exposure.

= Can I revert changes if needed? =
Yes, you can clear all alt text via the settings page. It is recommended to back up your site before performing bulk actions.

== Screenshots ==
1. **Dashboard View:** Displays images missing alt text along with overall stats.
2. **Settings Page:** Allows you to configure your API key and manage alt text generation.

== Changelog ==
= 0.0.1 =
* Initial release.
* Generates alt text for images using an external AI API.
* Includes bulk generation and clearing of alt text features.
* Provides an intuitive admin interface for API key configuration.