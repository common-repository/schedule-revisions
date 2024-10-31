=== Schedule Revisions ===
Contributors:      Aurorum
Tags:              schedule content, revisions, gutenberg, time, block
Requires at least: 5.3.2
Tested up to:      5.7
Stable tag:        1.0
Requires PHP:      7.0.0
License:           GPL-2.0-or-later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

Control when content (or revisions) appear or disappear in your posts through a new Gutenberg block.

== Description ==

This plugin provides a way to make content either magically appear or disappear at a given time in the Block Editor. The block is based on your site's timezone, giving you complete control over the timing. Possible usage for this includes:

* Displaying special messages for a certain period of time (eg. "Merry Christmas!" only on the 25th December)
* Starting a sale and offering temporary vouchers or coupons
* Holding a giveaway that prevents entries after a certain time has passed

In all cases, your content would be revised automatically once the time has passed - no more having to be online exactly at a certain date and time to update your site!

== Instructions ==

After activating the plugin, you can insert the "Schedule Revisions" block in the Block Editor, and then schedule any blocks of your choosing. 

== Frequently Asked Questions ==

= If I've hidden content, is there any way for my readers to view it before the time has passed? =

No, there isn't - your content will be safely hidden until that time has passed.

= Can I preview all my content even if the time hasn't passed yet? =

Yes! You can add the `?schedulerevisions=1` parameter to the end of your site's URL in order to preview the scheduled content, irrespective of the time. 

This parameter will only work if you are logged into an administrator's account. 

= Do you provide support for this plugin? =

Feel free to send an email or a message with any issues - I'll try to respond quickly!

== Screenshots ==

1. On inserting the block, you will be prompted with a way to schedule when the content should appear/disappear
2. You can always change your mind about the timing of your content's appearance/disappearance.

== Changelog ==

= 1.1 =
* Allow administrators to bypass the selected time

= 1.0 =
* Release
