---
description: >-
  Explanation and how to use Default Trading Market, Default Exchange, & Default
  Trading Pair
---

# Defaults

{% hint style="info" %}
To set or change any of the defaults, use the `/defaults` or `$defaults` command.
{% endhint %}

## Default Trading Market

There are currently 3 trading markets, `stocks`,`forex`, and `crypto`- and by default a users default trading market is set to `stocks`.\
The default market setting is what informs the bot whether submitted trades are on crypto, stock, or forex markets. When the default market is stocks, submitting crypto trades requires a complete format (I.e. BTO BTC/USDT @ CMP) where a `/` separator and the trading pair ticker need to be specified- or if using a [#default-trading-pair](defaults.md#default-trading-pair "mention") when submitting then the `.X` syntax can be used in replace of the `/` separator and pair ticker. (I.e. BTO BTC.X @ CMP)

{% hint style="warning" %}
When attempting to trade stocks while the default market is set to `crypto`, a `-S` syntax attached to the ticker is required.\
I.e. `BTO AAPL-S @ cmp`\
\
Syntaxes are not case sensitive, and can be used with any special character `-` `.` `_` and others. (I.e. `BTO ABC.S @ cmp`)\
When submitting options trades, the `-S` syntax is **not** required. No syntax is needed when submitting forex trades while default market is `crypto`.
{% endhint %}

Submitting crypto trades can still be allowed when the default market is set to `stocks`. But the trading pair ticker or `.X` syntax for the default pair will be required.

> `BTO BTC/USDT @ CMP [exchange]`\
> or\
> `BTO BTC.X @ CMP`

When default market is set to `crypto` and when submitting a crypto trade, the trading pair isn't required, and when one isn't specified it will use the default pair. See [#default-trading-pair](defaults.md#default-trading-pair "mention")

> `BTO BTC @ CMP`\
> Will be submitting the cryptocurrency BTC using the default pair or USDT if default pair hasn't been changed, and using the default exchange or Binance if default exchange hasn't been changed.

### How to set or change the Default Trading Market

Use the `/defaults` or `$defaults` command to bring up the defaults settings interface. Click on the button labeled "Default Market".\
![](<../.gitbook/assets/image (17).png>)\
A prompt will appear where the name of the default market can be entered.\
![](<../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)\
Type in `crypto` to set the default trading market to crypto, then hit Submit.

If successful the bot will then respond with an ephemeral message stating that the default market has been changed. If it responds with "That is not a supported market!" try again and double check the spelling of `stocks` or `crypto`.

## Default Crypto Exchange

The default crypto exchange setting is what allows trades to be submitted without needing to specify the exchange name within the trade notes. When submitting a trade on a different exchange than what the default exchange is set to, the exchange name needs to be included in the trade notes.

We currently support \~25 crypto exchanges used to check real-time crypto prices. Here's the full list:

* Binance
* Binance.US
* BingX
* Bitfinex
* Bitget
* BitMart
* BitMEX
* Bitrue
* CEX.IO
* Coinbase
* Coinsbit
* Crypto.com
* DigiFinex
* Gate.io
* Gemini
* HitBTC
* Huobi/HTX
* Kraken
* KuCoin
* LBank
* MEXC
* OKX
* Poloniex
* XT

By default, a new users default exchange is set to `binance`. Specifying an exchange name in the trade notes can be used to submit a trade on an exchange that is not the default exchange.

### How to set or change the Default Exchange

Use the `/defaults` or `$defaults` command to bring up the defaults settings interface. Click on the button labeled "Default Exchange".\
![](<../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)\
A prompt will appear where the name of the exchange can be entered.\
![](<../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1).png>)\
Type in any one of the 26 exchanges and hit Submit.

If successful the bot will then respond with an ephemeral message stating that the default exchange has been set to the specified exchange. If it responds with "That isn't a support crypto exchange!" try again and double check that the spelling matches one of the exchanges listed above.

## Default Trading Pair

The default trading pair allows submitted trades to **not** require a `/` separator and pair ticker to be specified. When a separator and pair ticker are not specified, the default trading pair is used.

{% hint style="info" %}
The trading pair is the second ticker, or the asset being traded with the main crypto.\
I.e. BTC/USDT - where USDT is the pair.
{% endhint %}

### How to set or change the Default Trading Pair

Use the `/defaults` or `$defaults` command to bring up the defaults settings interface. Click on the button labeled "Default Pair".\
![](<../.gitbook/assets/image (4) (1) (1) (1) (1) (1).png>)\
A prompt will appear where the ticker of the default trading pair can be entered.\
![](<../.gitbook/assets/image (5) (1) (1) (1) (1).png>)\
Type in the desired ticker for the default pair.

If successful the bot will then respond with an ephemeral message stating that the default pair has been set to the specified ticker. If it responds with "Your default pair is invalid." try again and double check that the ticker is a valid trading pair.



## Many examples to demonstrate submitting crypto trades with or without default settings

> `BTO BTC/USDT @ CMP [exchange]`

_Standard submission, typically used when submitting a trade that is not using any default settings._

> `BTO BTC.X @ CMP`

&#x57;_&#x68;ere `.X` is used for the default trading pair, default market can be either `stocks`, `forex`, or `crypto`._

> `BTO BTC @ CMP`

_Where default market is set to `crypto`, and not specifying a trading pair or `.X` is not required because default pair is used._

> `BTO BTC @ CMP Coinbase`

&#x44;_&#x65;fault market is set to `crypto`, using the default trading pair, and `Coinbase` in trade notes to specify the trade is not using the default exchange._
