## 7K Image Uploader Meta Box 

Contributor: Kharis Sulistiyono  
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=ACYNA5XNUGBUL
Tags: posts, uploader, meta box, custom meta box, image uploader   
Requires at least: 3.0  
Tested up to: 3.8  
Stable tag: 1.1
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Sometimes only single featured image is not enough. So you can have one more by using this plugin. It is just 7 kilobytes PHP file which adds image uploader field under post editor.  

### Description

<img src="https://raw.github.com/kharissulistiyo/7K-Image-Uploader-Meta-Box/master/screenshot-1.png" alt="7K Image Uploader Meta Box WordPress Plugin" />

Printing the image output is very simple. Just use this code in your template file.

<pre>
$id = get_post_meta($post->ID, 'iumb', true);
$image = wp_get_attachment_image_src($id, 'full-size');
echo $image;
</pre>

This very first release doesn't support custom post type. Worry not, for the next version it does.

### Installation

1. Download the 7K Image Uploader Meta Box Plugin.
2. In your WordPress Administration, go to Plugins > Add New > Upload, and select the plugin ZIP file.
3. Activate the plugin.
4. The image uploader meta box will appears on add/edit post.


### Changelog

= 1.0 =
* Initial release

### Download

http://wordpress.org/plugins/7k-image-uploader-meta-box/


### Support

Contact me: <a href="http://kharissulistiyono.com/">Kharis Sulistiyono</a>