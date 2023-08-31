---
description: A quick & efficient way of submitting trades.
---

# Advanced Input



## Advanced Input

The advanced input feature allows for a quicker and more efficient method of submitting trades. When using the general settings, you can see what the advanced format of your trade would be. The advanced method uses a strict format starting with 3 letter 'triggers', stock or crypto/pair tickers, and the price followed by the `@` symbol. With options, the expiration date (mm/dd format), strike price, and call/put need to be specified after the ticker.

\
[**Triggers:**](https://docs.thetradehub.net/submit-stocks-options-trades-on-discord/triggers)\
**BTO** - Buy to Open _(open long)_\
**STC** - Sell to Close _(close long)_\
**STO** - Sell to Open _(open short)_\
**BTC** - Buy to Close _(close short)_

&#x20;**Examples:**\
Stocks:\
`BTO AAPL @ 123.33` - Buying AAPL for $123.33 to open a long position (STO would be used if the position is short)\
`STC AAPL @ 130.45` - Selling AAPL for $130.45 to close the long position (BTC would be used if closing the short position)\
\
Options:\
`BTO SPY 1/23 400p @ 1.23` - Buying SPY contracts with a January 23rd expiration date, $400 strike price, and strategy is put.\
Same trade, alternative formats: `BTO SPY 400p 1/23 @ 1.23` - `BTO SPY 1/23 400 put @ 1.23` - `BTO SPY 400put 1/23 @ 1.23`

`STC SPY 1/23 400p @ 2.34` - Selling the open SPY contracts, you can use the same alternatives above. \
`STO` & `BTC` would be used if these were short-selling positions.

Crypto:\
Pairs needed to be attached to the tickers but always separated by the `/` symbol. Exchanges are to be specified at the end of the input\
`BTO BTC/USDT @ 19,000 binance` - Buying Bitcoin with USDT as the trading pair on the Binance exchange.\
\
[Notes](https://docs.thetradehub.net/submit-stocks-options-trades-on-discord/extra/adding-notes) can be added anywhere after the price. [Trade style](https://docs.thetradehub.net/submit-stocks-options-trades-on-discord/extra/trade-styles-and-flags-daytrade-swing-or-risky-lotto) (daytrade/swing/etc) keywords can be detected anywhere in the notes, along with [trade flags](https://docs.thetradehub.net/submit-stocks-options-trades-on-discord/extra/trade-styles-and-flags-daytrade-swing-or-risky-lotto#flags) (risky/lotto/etc), as well as [crypto exchanges.](https://docs.thetradehub.net/submit-crypto-trades-on-discord/defaults#default-crypto-exchange)

{% hint style="info" %}
You can get a clearer idea of how the advanced input works by checking out the [Broken link](broken-reference "mention") section
{% endhint %}

{% hint style="info" %}
When submitting a trade, you can see the advanced format of it.\
![](<../.gitbook/assets/image (36).png>)
{% endhint %}
