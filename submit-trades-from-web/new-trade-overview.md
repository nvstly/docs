---
description: Explanation of all New Trade and Active Positions interface elements.
---

# New Trade Overview

<figure><img src="../.gitbook/assets/image (10) (1) (1) (1).png" alt=""><figcaption><p>New Trade Interface</p></figcaption></figure>

## New Trade

**Market**\
\- Toggle between stocks, options, or crypto markets.\
\
**Position**\
\- Toggle for submitting a long or short trade.\
\
**Symbol**\
\- The ticker symbol of asset being submitted.\
\- When entering a ticker that our platform doesn't recognize, you will be prompted with an error and the option to report the missing ticker if you believe it is valid.\
\
**Pair** (crypto)\
\- The trading pair being used for trade, the 2nd ticker symbol. (I.e. BTC/USDT where USDT is the pair.)\
\
**Price**\
\- The price of your trade.\
\- A real-time price is auto-filled when a ticker symbol has been entered, which can be used to submit rather than inputting a price.

{% hint style="warning" %}
We check real-time prices when a trade is submitted, and allow a small threshold of how far you can be off the current market price to allow for volatility and time it takes when submitting a trade.
{% endhint %}

**Style Dropdown Menu**\
\- To mark your trade as daytrade, scalp, swing, or long term.

#### When options is toggled

**State**\
\- To select whether the trade is a call or put.\
\
**Exp. Date**\
\- Type in an expiration date or select one.\
\
**Strike**\
\- The strike price of your options contract.

<figure><img src="../.gitbook/assets/image (14) (1).png" alt=""><figcaption><p>Second &#x26; Optional Final Step of New Trade</p></figcaption></figure>

**Take Profit & Stop Loss**\
\- Set TP and/or SL.\
\- Not required

{% hint style="info" %}
Did you know?\
Trades will automatically close when your specified Take Profit or Stop Loss has been triggered. See more info regarding this feature [setting-tp-sl.md](../submit-stocks-options-trades-on-discord/setting-tp-sl.md "mention")
{% endhint %}

**Trade Notes**\
\- Include notes or upload media.\
\- Not required\
\
**Flags**\
\- Flag a trade with three different types of risks.\
\
**Sharing Settings**\
\- Auto share trade to your Discord webhooks or via Tweet.

{% hint style="info" %}
Trade Sharing\
To add Discord webhooks or link your Twitter for automatic trade sharing, read more about [trade-sharing-overview.md](../trade-sharing/trade-sharing-overview.md "mention").
{% endhint %}

## Active Positions

<figure><img src="../.gitbook/assets/image (15) (1).png" alt=""><figcaption><p>Active Positions Interface</p></figcaption></figure>

**Quick Close** ![](<../.gitbook/assets/image (17) (1).png>)\
\- Instantly close a position at it's current market price.\
\
**Status**\
\- Average, partial/trim, or close a position.\
\
**Price**\
\- Use the provided current market price or input your own\
\
**Trade Notes**\
\- Add optional notes or upload media.\
\
Share position update to Discord or Twitter. See [trade-sharing-overview.md](../trade-sharing/trade-sharing-overview.md "mention") for more info.
