---
description: How to open long positions for stocks & options.
---

# Opening Long Position

### Stocks Format

{% hint style="success" %}
**BTO \<ticker> @ \<price>**\
I.e. _`BTO AAPL @ 150.20`_
{% endhint %}

To open a **long** stock position, use the trigger **`BTO`** followed by the ticker, then the symbol @ before the price.\


<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>Example of submitting a long position for $AAPL for the price of $188.00</p></figcaption></figure>

### Options Format

{% hint style="success" %}
**BTO \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
I.e. _`BTO SPY 1/23 450 call @ 1.23`_\
_`BTO SPY 1/23 450c @ 1.23`_
{% endhint %}

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. `BTO SPY 450c 1/23 @ 1.23`
{% endhint %}

To open **long** options position, use the trigger **`BTO`** followed by the _ticker,_ then the expiration date using MM/DD format, your strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put`.&#x20;

<figure><img src="../../.gitbook/assets/image (1).png" alt=""><figcaption><p>Example of submitting a long position for $SPY, 9/07 expiration date, $450 strike price, and $1.27 for the price by using CMP</p></figcaption></figure>



{% hint style="warning" %}
#### You can enter in your actual price or use `CMP` or `M` for submitting at the current market price.
{% endhint %}
