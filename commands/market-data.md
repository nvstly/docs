---
description: >-
  We continually add useful commands to the bot to help traders see real time
  market data without leaving Discord. These subpages will go over all the
  available commands and how to properly use them.
---

# Market Data

{% hint style="warning" %}
Crypto charts, stats, & prices will be modified soon where you can choose to request data from a specific exchange.
{% endhint %}

## Charts

### Stocks

{% hint style="info" %}
**$c TICKER \<time>** | **$chart TICKER \<time>**\
I.e. _`$c AAPL`_ | _`$c TSLA 1w`_ | _`$chart SPY 15m`_
{% endhint %}

The bot can display charts in Discord by using the `$chart` or `$c` command. By default, the timeframe shown for charts is 5 minutes if one is not specified. Specify the timeframe after the ticker using **`m`** or **`min`** or **`minute`**, **`h`** or **`hour`**, **`d`** or **`day`**, **`w`** or **`week`**\
![](<../.gitbook/assets/image (171).png>)![](<../.gitbook/assets/image (62).png>)

### Crypto

{% hint style="info" %}
I.e _`$c BTCUSD`_ | _`$chart DOGE`_ | _`$chart ETHEUR`_
{% endhint %}

Charts also work for crypto coins just by specifying the ticker & currency pair.\
![](<../.gitbook/assets/image (73).png>)![](<../.gitbook/assets/image (174).png>)

## Stock Stats

{% hint style="info" %}
**$s \<ticker>** | **$stock \<ticker>**\
I.e. _`$s TSLA`_ | _`$stock AMC`_
{% endhint %}

The `$stock` command provides some data for any ticker specified. The following is the data provided;

* Price (Including extended hours price)
* Price Movement / % Movement
* Volume & Avg. Volume
* Open & Previous Close
* Daily High & Low
* Year High & Low

![](<../.gitbook/assets/image (131).png>)

{% hint style="info" %}
This command can also be used for crypto if the currency is attached to the ticker.\
I.e. _$stock BTCUSD_\
We'll add a separate `$crypto` command just for cryptocurrencies.
{% endhint %}

## Prices

#### Stocks

{% hint style="info" %}
**$p TICKER** | **$price TICKER**\
I.e. _`$p TSLA`_ | _`$price AAPL`_
{% endhint %}

The `$price` or `$p` command gets any ticker price without any extra data.![](<../.gitbook/assets/image (81).png>)

#### Crypto

{% hint style="info" %}
**$p TICKER/Cuurrency**\
I.e. _`$p BTCUSD`_ | _`$price ETHUSD`_
{% endhint %}

The `$price` command can also get crypto prices Be sure to attach the currency to the crypto ticker. \
![](<../.gitbook/assets/image (80).png>)

## Top Gainers/Losers

{% hint style="info" %}
**`$gainers`** | **`$topgainers`** | **`$topg`**\
**`$losers`** | **`$toplosers`** | **`$topl`**
{% endhint %}

The `$gainers` command displays the top 10 highest gainers of the day in reference to the last closing price.\
\
The `$losers` command displays the top 10 losing stocks of the day in reference to the last closing price.

![](<../.gitbook/assets/image (34).png>)![](<../.gitbook/assets/image (155).png>)
