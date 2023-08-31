---
description: >-
  This page will show you how to close short stocks & options positions. BTC
  (Buy to Close) is the trigger to close long positions.
---

# Closing Short Position

### Stocks Input

{% hint style="info" %}
**BTC \<ticker> @ \<price>**\
I.e. _`BTC AAPL @ 150.20`_
{% endhint %}

To close your **short** stock position, use the trigger **`BTC`** followed by the _ticker_ and use `@` before your price. \
![](<../../.gitbook/assets/image (60).png>)

### Options Input

{% hint style="info" %}
**BTC \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
I.e. _`BTC SPY 1/23 450 call @ 1.23`_\
_`BTC SPY 1/23 450c @ 1.23`_
{% endhint %}

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. _`BTC SPY 450c 1/23 @ 1.23`_
{% endhint %}

To close your **short** options position, use the trigger **`BTC`** followed by the _ticker,_ then the expiration date using MM/DD format, your strike price and attaching **`c`** or **`p`** to it or specifying **`call` or `put`.** \
![](<../../.gitbook/assets/image (144).png>)\
\
_Note: You can use single digit months, but days always need to be double digits. I.e. 6/01_



{% hint style="warning" %}
#### You can enter in your actual price or use `CMP` or `M` for the current market price.
{% endhint %}
