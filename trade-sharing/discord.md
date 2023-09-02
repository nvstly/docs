---
description: You can share your trades to Discord via webhooks instantly
---

# Discord

### Webhooks

Webhooks are required for sharing your trades to Discord. To do this go to [Accounts & Sharing](https://nvst.ly/settings/sharing) within your account settings. Under the webhooks section click Add Webhook > Discord to be prompted with the New Webhook interface. \
\
Select a name for the webhook that will act as a username in Discord, an image that will be used for the avatar, and the webhook URL. An optional note can be added to help keep track of webhooks.\
\
You can limit which markets and style of trades you want sent to webhooks by selecting them under Markets and Trade Styles. You need to select at least 1 market, and if no Trade Styles are selected it will send all trades regardless of style.

#### Role Pings & @mentions

If you intend on @mentioning or sending a ping with your shared trade, they should be set with each individual webhook rather than in the custom message/embed builder- _as those mentions/pings would be used across all webhooks._

<figure><img src="../.gitbook/assets/image (206).png" alt=""><figcaption><p>You can have an unlimited number of webhooks</p></figcaption></figure>

#### Creating Webhooks on Discord

To create webhooks on Discord, right click on the desired channel you want trades to be shared in and click `Edit Channel.` In the settings click on `Integrations` then `Webhooks` and click `New Webhook`. You can set the webhook name and avatar here, but the webhook name and avatar set in the web app will over-ride these settings.

## Enable/Disable Sharing Trades to Webhooks

To share your trades to Discord via webhooks, you can either enable it in your account settings, or just check the _Share to Discord_ box when submitting a trade through the New Trade feature.\


![](<../.gitbook/assets/image (210).png>)![](<../.gitbook/assets/image (209).png>)

{% hint style="info" %}
When enabled in settings, it will always be enabled in New Trade
{% endhint %}

You have full customization of how your message or embed content looks when sent. We've built a 'no-code' message builder for sharing trades to Discord, scope it out in your account settings. There is where you'll also specify the webhooks you wish Trade Hub to use for sending out your trades.

**You can customize each trade event message:**

* Open
* Average
* Trim/Partial
* Closing

**With every data property of the trade, and more:**

* Direction (long/short)
* Ticker (and ticker logo)
* Expiration date
* Strike Price
* Call/put
* Notes
* Link to Trade Insight page
* Styles & flags
* Curent market price of ticker
* Daily high/low price of ticker
* Volume
* [And so much more](https://docs.thetradehub.net/trade-sharing/customize-messages-or-embeds)

## Your Bot

COMING SOON

## Our Bot

COMING SOON
