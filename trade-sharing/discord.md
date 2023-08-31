---
description: You can share your trades to Discord via webhooks instantly
---

# Discord

{% embed url="https://youtu.be/6WDa5jnrTJg" %}
How to setup Trade Sharing for Discord & customize messages/embeds
{% endembed %}

### Webhooks

You need to add webhooks for the app to use for sending your trades. To do this go to your [Account Settings](https://thetradehub.net/settings) and expand the Trade Sharing section. Click on the `Webhooks` button then hit `New Webhook`, it will create a new wbehook named `My Webhook` where you can then set the desired name and avatar. Paste the Discord webhook link in the URL text box.\
![](<../.gitbook/assets/image (195).png>)

To add a webhook hit the _New Webhook_ button. Here you can choose the name that will be used when messages are posted to Discord along with an avatar- these settings will over-ride the settings chosen in Discord.\
![](<../.gitbook/assets/image (181).png>)\
_You can submit an unlimited number of webhooks to send trades through._

### Pings (@everyone/@here/@role)

Any @mentions such as role pings should be specified for each webhook when submitting it to the app from account settings, _if none then leave blank. (Any pings set in the message/embed builder will be used for all webhooks)_\
\
You can choose a ping (@everyone, @here) or a role ping by clicking on the @Mentions button. \
![Mentions](https://i.imgur.com/8TdBdpx.png)\
We've made it convienent by fetching the list of roles from the server belonging to the webhook, you can choose from the list, or enter a role ID. Multiple @mention pings can be used.

#### Creating Webhooks on Discord

To create webhooks on Discord, right click on the desired channel you want trades to be sent to and click `Edit Channel.` In the settings click on `Integrations` then `Webhooks` and click `New Webhook` to create a webhook. You can set the webhook name and avatar here, but the webhook name and avatar set in the web app will over-ide these settings.

## How It Works

To share your trades to Discord via webhooks, you can either enable it in your [account settings](https://thetradehub.net/settings), or just check the _Share to Discord_ box when submitting a trade through the [New Trade](https://thetradehub.net/submit) feature.\
![](<../.gitbook/assets/image (112).png>)![](<../.gitbook/assets/image (158).png>)

{% hint style="info" %}
_When enabled in settings, will always be enabled in New Trade_
{% endhint %}



You have full permissions of how your message or embed looks when sent. We've built a 'no-code' message builder for your Discord trade sharing, scope it out in your [account settings](https://thetradehub.net/settings). There is where you'll also specify the webhooks you wish Trade Hub to use for sending out your trades.

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
* [And so much more](https://docs.thetradehub.net/trade-sharing/customize-messages-or-embeds)

### To learn how to customize your trade's message content, see the [customize-messages-or-embeds.md](customize-messages-or-embeds.md "mention") section.

## Your Bot

COMING SOON

## Our Bot

COMING SOON
