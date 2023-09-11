---
description: How to close both stocks & options positions
---

# Closing Trades

{% hint style="info" %}
Closing triggers;\
**`STC`** is used to close long\
**`BTC`** is used to close short
{% endhint %}

## Stocks Format

### Closing Long

> **STC \<ticker> @ \<price>**\
> I.e. _`STC AAPL @ 178.70`_

To close a **long** stock position, use the trigger **`STC`** followed by the ticker, then the symbol @ before the price.

<figure><img src="../.gitbook/assets/image (222).png" alt=""><figcaption><p>Example of closing a long position for $AAPL at the price of $178.70</p></figcaption></figure>

### Closing Short

> **BTC \<ticker> @ \<price>**\
> I.e. _`BTC AAPL @ 177.94`_

To close a **short** stock position, use the trigger **`BTC`** followed by the ticker, then the symbol **@** before the price.

<figure><img src="../.gitbook/assets/image (223).png" alt=""><figcaption><p>Example of closing a short position for $AAPL at the price of $178.72</p></figcaption></figure>

##

## Options Format

### Closing Long

> **STC \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`STC SPY 9/15 450 call @ .88`_\
> _`STC SPY 9/15 450c @ .88`_

To close **long** options position, use the trigger **`STC`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../.gitbook/assets/image (224).png" alt=""><figcaption><p>Example of closing a long Call position for $SPY, 9/15 expiration date, $450 strike price, and $0.88 for the price.</p></figcaption></figure>

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. `BTO SPY 450c 9/15 @ .88`
{% endhint %}

### Closing Short

> **BTC \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`BTC SPY 9/15 440 put @ 1.08`_\
> _`BTC SPY 9/15 440p @ 1.08`_

To close **short** options position, use the trigger **`BTC`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../.gitbook/assets/image (225).png" alt=""><figcaption><p>Example of closing a short Put position for $SPY, 9/15 expiration date, $440 strike price, and $0.88 for the price.</p></figcaption></figure>



{% hint style="danger" %}
Final Notes:\
\- **Do not use `$` with tickers.** \
**-** You can enter in your actual price or use `CMP` or `M` for submitting at the current market price.
{% endhint %}
