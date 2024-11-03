---
description: How to submit crypto trades via the Discord bot.
---

# Overview

{% hint style="danger" %}
When submitting a crypto trade, you need to use a separator between the coin and the trading pair. Available separators are: `/` `-` `_` `&` or `.`
{% endhint %}

### Important

Crypto trade tracking is generally the same as stocks/options, but has more sophisticated additional features to provide better timely trade submissions. Be sure to check out the [defaults.md](defaults.md "mention")section to learn all about these features and how to submit crypto trades most efficiently.&#x20;

{% hint style="info" %}
When your Default Market is set to `crypto`, you will need to use `-S` or `-F` syntaxes attached to the tickers when submitting stocks or forex trades.\
I.e. `BTO AAPL-S @ cmp` or `BTO USDCAD-F @ cmp`\
\
When submitting options trades, the `-S` syntax is **not** required.
{% endhint %}

### Prices

The bot checks against real-time market prices when trades are submitted. To allow for volatility and time it takes to submit, the submitted price can be off by a small threshold based on our price tolerance system. This is to prevent traders manipulating stats and cheating ranks.

This video will guide you through on how to properly use the Discord bot for submitting (stock only) trades. This is an old version 1 video, and a lot has been added & changed since then but is still helpful for covering the basics and seeing it in action. All features and functionalities can be found in the articles below.

#### Newer Quick Demonstration of Tracking/Submitting Stocks & Options Trades

{% embed url="https://youtu.be/DEysIkX5QQo" %}
Quick demonstration of submitting or tracking crypto trades
{% endembed %}

Here's a quick demo (no audio) of how tracking or submitting crypto trades work, utilizing Default Market and Default Exchange, specifying different exchanges, averaging up/down, trimming or partially closing, using trade notes, etc. Video recorded October 2024. _(Refer to the_ [_stocks/options how to video_](../submit-stocks-options-trades-on-discord/overview.md#stocks-and-options-trade-tracking-submitting-how-to-video) _for a more in-depth explanation with audio, but it doesn't cover crypto and it's an old early Beta v0.2 video which a lot has been added and improved since, but stil covers general basics.)_

Currently only spot trading is available, futures contracts will be added soon.
