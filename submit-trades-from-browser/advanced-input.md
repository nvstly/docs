---
description: A quick & efficient way of submitting trades.
---

# Advanced Input

## Advanced Input

The advanced input feature allows for a quicker and more efficient method of submitting trades. When using general elements on the New Trade interface, you can see what the advanced format version of your trade would be. The advanced method uses abbreviations and keywords that describe your trade data.\
It starts with a trigger that specifies if the submissions is opening or closing a trade, and the direction of it. A ticker symbol if always followed after the trigger, and if options then the expiration date, strike price, and call/put. For crypto trades the pair is included with with the ticker while using a `/` as the separator. It the ends with `@ <price>` where \<price> is replaced with your submitted price. See below for more info and examples.

{% hint style="info" %}
If you're experienced or familiar with using the NVST.ly Discord bot, the advanced input method is exactly the same as submitting trades via text commands.
{% endhint %}

[**Triggers:**](../submit-stocks-options-trades-on-discord/triggers.md)\
**BTO** - Buy to Open _(open long)_\
**STC** - Sell to Close _(close long)_\
**STO** - Sell to Open _(open short)_\
**BTC** - Buy to Close _(close short)_\
\
**Partial/Trim Keywords:**\
`part` `partial` `trim` `trimming` `scal` `scale` `scaling`\
These keywords can be used anywhere within the notes.\
\
**Notes:**\
Notes are used after the price. They can be used to set the S[tyle](../submit-stocks-options-trades-on-discord/trade-styles-risk-flags-and-trade-notes.md#trade-styles) of a trade, set [Take Profit and/or Stop Loss](../submit-stocks-options-trades-on-discord/setting-tp-sl.md), [Partial/Trim](../submit-stocks-options-trades-on-discord/trim-partial-close.md) a position, mark a trade with R[isk Factor Flags](../submit-stocks-options-trades-on-discord/trade-styles-risk-flags-and-trade-notes.md#risk-flags), or specify a crypto exchange,&#x20;

### &#x20;**Examples:**

**Stocks:**\
`BTO AAPL @ 123.33` - Buying AAPL for $123.33 to open a long position (STO would be used if the position is short)\
`STC AAPL @ 130.45` - Selling AAPL for $130.45 to close the long position (BTC would be used if closing the short position)\
\
**Options:**\
`BTO SPY 1/23 400p @ 1.23` - Buying SPY contracts with a January 23rd expiration date, $400 strike price, and strategy is put. \
Same trade, using alternative formats: `BTO SPY 400p 1/23 @ 1.23` - `BTO SPY 1/23 400 put @ 1.23` - `BTO SPY 400put 1/23 @ 1.23`

`STC SPY 1/23 400p @ 2.34` - Selling the open SPY contracts, you can use the same alternative formats above. \
`STO` & `BTC` would be used if this SPY contact was a short-selling positions.

**Crypto:**\
Pairs need to be attached to the tickers but always separated by the `/` symbol. Exchanges are to be specified at the end of the input or anywhere in the trade notes.\
`BTO BTC/USDT @ 19,000 binance` - Buying Bitcoin with USDT as the trading pair on the Binance exchange.

{% hint style="info" %}
It might be helpful in getting more in-depth insight on how the advanced method works by checking out the [Broken link](broken-reference "mention") section
{% endhint %}

<figure><img src="../.gitbook/assets/image (204).png" alt=""><figcaption><p>When submitting a trade, you can preview the advanced format of it</p></figcaption></figure>
