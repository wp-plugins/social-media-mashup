=== Social Media Mashup ===
Contributors: bravenewmedia, aliso
Tags: social media, facebook, twitter, google+, google plus, youtube, flickr, stream
Requires at least: 3.0
Tested up to: 3.2.1
Stable tag: 1.0

Combine your Twitter, Facebook, Google+, Flickr, YouTube, and any RSS feeds into one stream.

== Description ==

Social Media Mashup provides a widget and template tag to display a combined social media & RSS stream. A simple options panel and minimal CSS make this plugin easy to install and visually compatible on any WordPress site.

See the [screenshots](http://wordpress.org/extend/plugins/social-media-mashup/screenshots/) for an example of the plugin in action.

== Installation ==

1. Unzip the file and upload the `social-media-mashup` folder to the `/wp-content/plugins/` directory
1. Make sure the `smm-cache` folder inside the plugin folder is writeable by the server (permissions set to 755, 775, or 777 depending on your web host)
1. Activate the plugin through the **Plugins** menu in WordPress
1. Go to **Settings > Social Media Mashup** to enter social media & feed information
1. Use the widget or template tag to display the social stream: `<?php if ( function_exists( 'social_media_mashup' ) ) social_media_mashup(5); ?>`

== Frequently Asked Questions ==

= How do I display this in my theme, without using the widget? =

Use this template tag:

`<?php if ( function_exists( 'social_media_mashup' ) ) social_media_mashup(5); ?>`

Change the number to customize how many entries are displayed in the stream.

= I have a question about this plugin. =

Contact us at [Brave New Media](http://bravenewmedia.net/contact-us/?plugin_support=Yes+(Social+Media+Mashup)) or on Twitter [@BraveNewTweet](http://twitter.com/#!/bravenewtweet).

== Credits ==

* Icons by [Komodo Media](http://www.komodomedia.com/blog/2008/12/social-media-mini-iconpack/)
* Icons by [FastIcon.com](http://www.fasticon.com/)
* Icons by [Picons.me](http://picons.me/)
* Settings API class by [Aliso the Geek](http://alisothegeek.com/2011/01/wordpress-settings-api-tutorial-1/)
* RSS feed mashing by [SimplePie](http://simplepie.org/)

== Screenshots ==

1. Social stream displaying as a widget
2. Plugin settings

== Changelog ==

= 1.0 =
* Initial release