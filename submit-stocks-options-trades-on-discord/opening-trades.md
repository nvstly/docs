---
description: How to open both stocks & options positions
---

# Opening Trades

{% hint style="info" %}
Opening triggers;\
**`BTO`** is used to open long\
**`STO`** is used to open short
{% endhint %}

## Stocks Format

### Opening Long

> **BTO \<ticker> @ \<price>**\
> I.e. _`BTO AAPL @ 188`_

To open a **long** stock position, use the trigger **`BTO`** followed by the ticker, then the symbol @ before the price.

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>Example of submitting a long position for $AAPL at the price of $188.00</p></figcaption></figure>

### Opening Short

> **STO \<ticker> @ \<price>**\
> I.e. _`BTO AAPL @ 177.94`_

To open a **short** stock position, use the trigger **`STO`** followed by the ticker, then the symbol **@** before the price.

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption><p>Example of submitting a short position for $AAPL at the price of $177.94</p></figcaption></figure>

## Options Format

### Opening Long

> **BTO \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`BTO SPY 1/23 450 call @ 1.23`_\
> _`BTO SPY 1/23 450c @ 1.23`_

To open **long** options position, use the trigger **`BTO`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption><p>Example of submitting a long position for $SPY, 9/07 expiration date, $450 strike price, and $1.27 for the price by using CMP</p></figcaption></figure>

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. `BTO SPY 450c 1/23 @ 1.23`
{% endhint %}

### Opening Short

> **STO \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`STO SPY 1/23 450 call @ 1.23`_\
> _`STO SPY 1/23 450c @ 1.23`_

To open **short** options position, use the trigger **`STO`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Example of submitting a short position for $SPY, 9/08 expiration date, $450 strike price, and $0.32 for the price by using CMP</p></figcaption></figure>

{% hint style="danger" %}
Final Notes:\
\- **Do not use `$` with tickers.** \
**-** You can enter in your actual price or use `CMP` or `M` for submitting at the current market price.
{% endhint %}



## Using Slash Commands

Submitting trades through slash commands has a more user friendly aspect to it but can take some seconds longer than text messages.

### Stocks

Type in `/open` then select `stocks.`\


Type in or select the direction `Long` or `Short`. \


Type in the ticker or select a matching ticker provided.\


Enter in the price or use `0` for the current market price.

ADD GIF HERE

Notes can be added and are optional. Trade Styles (swing, scalp, etc.), [Risk Factor Flags](extra/trade-styles-and-flags-daytrade-swing-or-risky-lotto.md), and a Take Profit and/or Stop Loss can all be added through using the notes.

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Example of submitting a long position for $AAPL at $177.90, adding the Earnings risk flag, and setting both TP/SL</p></figcaption></figure>
