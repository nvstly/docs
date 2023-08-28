---
description: >-
  This section will go over how to submit your trades that are logged to your
  Trade Hub dashboard and calculated towards stats. Generally the same as
  stocks, but with some changes & extra features.
---

# Overview

{% hint style="danger" %}
When submitting a crypto trade, you need to use a separator between the coin and the trading pair. Available separators are: `/` `-` `_` `&` or `.`
{% endhint %}

### Important

If your default market is set to crypto, ou don't need to add a separator or pair if the intended pair is set as your default. If your default market is set to stocks, you will need to either use the `.x` syntax after the crypto ticker, or specify the pair using a separator after the ticker.\
\
By default, your crypto exchange is set to `binance`. To submit trades on any other exchange you will need to specify it after your input price, or change the default.\
\
You can learn more about these in [defaults.md](defaults.md "mention")

### Prices

The bot checks against current real-time market prices at the time of submitting your trade. It allows you to be off by a small amount to help with volatility and time it takes to submit. It's best to submit your trades with the bot as soon after filling the order within your exchange.\
\
This is to prevent traders manipulating stats and cheating ranks.\


Even though old and regarding only stocks, this video will guide you through on how to properly use the Discord bot. Keep in mind that our app is still in it's beta stages and features are added constantly, so there may be some functionalities that are missing from this video. _When version 1 is released a new video will be published._

{% embed url="https://trhub.net/howto" %}

{% hint style="danger" %}
This video was recorded during week 2 BETA (v0.2). Although it doesn't cover everything, it's a great short video to see how the bot works and the basics of submitting your trades.
{% endhint %}



Currently only spot trading is available, futures contracts will be added soon.
