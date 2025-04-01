---
description: >-
  We continually add useful commands to the bot to help traders see real time
  market data without leaving Discord. Asset info, prices, charts, & more.
---

# Market Data (Charts, Data Prices, etc.)

{% hint style="warning" %}
Crypto charts, stats, & prices will be modified soon where you can choose to request data from a specific exchange.
{% endhint %}

## Charts

### Stocks

{% hint style="info" %}
`$chart` _(or)_ `$c TICKER [time]`

**or**

`/chart TICKER [time]`
{% endhint %}

> `$c AAPL`\
> `$c TSLA 1w`\
> `$chart SPY 15min`

The bot can display stock charts by using the `$chart`, `$c`, or `/chart` commands. By default, the timeframe used for charts is 5 minutes if one is not specified.\
To specifiy a timeframe after the ticker, use `minute`, `min`, or `m`, `hour` or `h`, `day` or `d`, and `week` or `w`.

![](<../.gitbook/assets/image (246).png>)

### Crypto

UNDER DEVELOPMENT

## Stock Stats

{% hint style="info" %}
`$stock` _(or)_ `$s TICKER`
{% endhint %}

> `$stock TSLA`
>
> `$s AMC`

The `$stock` command provides some data for any stock ticker specified. The following is the data provided;

* Price (Including extended hours price)
* Price Movement / % Movement
* Volume & Avg. Volume
* Open & Previous Close
* Daily High & Low
* Year High & Low

![](<../.gitbook/assets/image (247).png>)

## Crypto Stats

UNDER DEVELOPMENT

## Prices

#### Stocks

{% hint style="info" %}
`$price` _(or)_ `$p TICKER`
{% endhint %}

> `$price TSLA`
>
> `$p AAPL`

The `$price` or `$p` command gets only the stock ticker price.

![](<../.gitbook/assets/image (6) (1) (1).png>)

#### Crypto

UNDER DEVELOPMENT

## Top Gainers/Losers

{% hint style="info" %}
$gainers, $topgainers, $topg\
$losers, $toplosers, $topl
{% endhint %}

The `$gainers` command displays the top 10 highest gainers of the day in reference to the last closing price.\
\
The `$losers` command displays the top 10 losing stocks of the day in reference to the last closing price.

![](<../.gitbook/assets/image (4) (1) (1) (1) (1).png>)![](<../.gitbook/assets/image (5) (1) (1) (1).png>)



{% hint style="info" %}
When using data commands for tickers containing special characters, such as dots or dashes, or any index ticker symbols, be sure to use their alias. They are all listed in [tickers-with-special-characters.md](../submit-stocks-options-trades-on-discord/tickers-with-special-characters.md "mention")
{% endhint %}
