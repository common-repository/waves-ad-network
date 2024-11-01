=== Plugin Name ===
Waves Ad Network
Plugin URI: https://t.me/turtleadnetwork
Contributors: gord0b
Donate link: https://t.me/turtleadnetwork
Tags: Ad, Ad Network, blockchain, wavesplatform, waves, peer to peer
Requires at least: 4.9.8
Tested up to: 5.1.1
Stable tag: 1.0.0
Requires PHP: 5.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl.html


== Description ==

Plugin receive Ad from transaction with https://nodes.wavesplatform.com using decode Base58 text attachment 

Example:
https://nodes.wavesplatform.com/transactions/address/3PA8GR3PLpGmwYhSdQjTSK7sGnjeC2XQQS2/limit/10

Example result info: attachment":"nEcn4rV3nXrtFBFLJbhs25Mqus1gghBAzubzZf5enhXJCCV15JwaizPcE4VJNz1mQ9by4DBryhBM1P2RG4d5RoQEHnzUqpFitD2u2DCBnvqMgVZGqbcnA2Qvrgt8"

nEcn4rV3nXrtFBFLJbhs25Mqus1gghBAzubzZf5enhXJCCV15JwaizPcE4VJNz1mQ9by4DBryhBM1P2RG4d5RoQEHnzUqpFitD2u2DCBnvqMgVZGqbcnA2Qvrgt8 => Base58 decode => Ad (Waves Ad Network 2)(Ad Network using the Waves blockchain)(https://t.me/wavesadnetwork)


Peer-to-Peer Ad Network using the Waves blockchain
https://wordpress.org/plugins/waves-ad-network/

**KEY FEATURES & HIGHLIGHTS:**
  * Text Ad Network
  * Peer-to-Peer transactions
  * Ad payments in WAVES (Receive 100%, no middlemen)
  * Send Ad text and payment in one easy transaction
  * 0.001 WAVES transaction fee per Ad
  * Zero license costs
  
**REQUIREMENTS:**
  * Wordpress installation to host Ads
  * Waves Wallet to send/receive payments & send Ad: https://client.wavesplatform.com (Note: Save SEED securely & dont share)
  * WAVES can be purchased on the DEX: https://client.wavesplatform.com
  * Note: View transactions for wallet on explorer - https://wavesexplorer.com

== Installation ==

1. Activate the plugin

2: Visit Wordpress Dashboard > Waves Ad Network > Settings.
2a: 'Set API Server' = Server hardset but can be changed.
2b: 'Minimum Amount in WAVES' = "Set the Minimum payment required for an Ad to be displayed, paid in WAVES", a payment that does not meet the minimum will be ignored.
2c: 'Ad Display Cost / Impressions' = "Set the cost, in WAVES, per amount of Ad impressions displayed, for all Ad Segments, multiple ads will round-robin", monitor Ad status in the 'Ad Approval' page.
2d: 'BlackList / Spam Management' = "Insert blacklist details, allow auto Ad blocking based on wallet addresses, words or expressions. In the comma separated format 'word1,address,word2'", Ads will be ignored based on blacklist data.
2e: 'Ad Approval' = "Enable or Disable Ad approvals, if enabled, manually managed in Ad Approvals page, by approve or reject action"

3: Visit Wordpress Dashboard > Waves Ad Network > Wallet Address
3a: 'Address Label' = "Insert a reference label of the Wallet Address"
3b: 'Wallet Address' = "Insert a Waves Wallet Address"
Note: Only use one Wallet Address per Ad Segment.

4: Visit Wordpress Dashboard > Waves Ad Network > Ad Segments
4a: 'Ad Segment Name' = "Insert an Ad Segment reference name"
4b: 'Assign Wallet Address' = "Assign a Wallet Address, configured in section 3
4c: 'Ad Size' = "Select an Ad display size"
Click 'Add Ad Segment' to complete the Ad Segment setup and note the new 'Shortcode' created for the Ad Segment.

5: Visit Wordpress Dashboard > Waves Ad Network > Ad Approval
5a: When 'Ad Approval' is activated in the 'Settings' page, Ads will be required to be manually approved by 'Approving' or 'Rejecting' the Ad.
Note: All Ads will be shown on the 'Ad Approval' page except incorrectly formatted Ads, blacklisted Ads.

6: Inserting an Ag Segment into a Wordpress website
Visit the 'Ad Segments' page and copy the required 'Shortcode', Insert the 'Shortcode' into a Wordpress page, blog, sidebar, widget etc.
Note: You are now ready to receive an Ad

7: ## Process for Sending an Ad ##
Send a transaction on the Waves, using the wallet, with the amount of WAVES required to purchase impressions. In the transaction attachment section, insert the correctly formatted Text Ad details and SEND.

8a: Ad details;
- Text Ad Format: 'Ad (headline)(description)(url)'
- Text Ad Example: Ad (Waves Ad Network)(Ad Network using the Waves blockchain)(https://t.me/wavesadnetwork)
- Text Ad submission process: Send a transaction on the Waves, with an attachment in the above format, to an assigned address. An assigned address is configured/linked to an Ad Segment.
- Text Ad Note: Maximum of 140 characters allowed, Headline text is bold with 35 character limit & URL is clickable in Ad. Utilize a URL shortener service to track analytics and shorten URL's.
Note: Ads that dont meet to format requirements will be ignored.


== Frequently Asked Questions ==

= Will there be Image Ads in future? =

This is an option that is under review.

== Screenshots ==

1. Setting page.
2. Wallet Address page.
3. Ad Segments page.
4. Ad Approval page.
5. Example page with Ad
6. Shortcodes in example page

== Changelog ==

= 1.0.0 =
* Initial Production release.
* Settings Page: Hardset a default API server to 'https://nodes.wavesplatform.com'.
* Settings page: Changed the notes formatting, remove space requirement between ')('.
* Ad Approval Page: 'Start Time' changed to 'Start Date' and included the Date & Time the Ad starts.
* Ad Approval Page: 'Txid' column, text changed to clickable hyperlink to the web explorer.
* [Fixed]: Removed the 'Action' column in 'Ad Approval page, when Ad approvals are disabled.
* [Fixed]: Special character escaping in Ad text.

== Upgrade Notice ==

= 1.0.0 =
This version is the initial production release.
