---
description: >-
  Set your default trading market to crypto, your crypto exchange, and trading
  pair
---

# Defaults

{% hint style="warning" %}
**To set or change your defaults use the `$defaults` command**
{% endhint %}

## Default Trading Market

> Why set my default trading market?
>
> > The default market setting is what tells the bot whether your trades are crypto or stocks. When set to crypto, you don't need to specify your trading pair _(unless it's different than your default pair)_ which can allow for a faster trade submission.

When trying to trade stocks/options while your default market is set to crypto, you'll need to add the `-s` syntax to the end of your ticker. \
I.e. `bto aapl-s @ cmp`\
\
When trading options you don't need to use the `-s` syntax.

{% hint style="info" %}
When trading options you don't need to use the `-s` syntax.
{% endhint %}

You can still trade crypto when your default market is set to crypto. You will just need to specify the trading pair with your ticker, or use the `.x` syntax at the end of your ticker to use your default trading pair. \
I.e. `bto btc/usdt @ cmp`\
or\
`bto btc.x @ cmp`&#x20;

{% hint style="info" %}
The -s and .x syntax's can be used with any of these characters:\
`-` `.` `_` `*` `^` `>` `<` **except** `@` and `/`
{% endhint %}

## Default Crypto Exchange

We currently support 12 crypto exchanges used to check real-time crypto prices. Here's the full list:\
\- Binance\
\- Binance.us\
\- Gate.io\
\- Bybit\
\- Kucoin\
\- Kraken\
\- Huobi\
\- Bitfinex\
\- Coinbase\
\- Crypto.com

By default your exchange is set to `binance` and can be changed using the `$defaults` command. You can also specify the exchange for any trade after your input price.\
I.e. `bto btc/usdt @ 0.00000 gate.io`



## Default Trading Pair

> Trading pairs consist of two assets that can be traded with each other on an exchange and are also used to quote one crypto against the other.

The default trading pair allows you to not have to specify the pair when submitting a trade, it will automatically use your default pair- so long your default market is set to `crypto`.\
The trading pair is the second ticker after the `/` separator. I.e. `btc/usdt`
