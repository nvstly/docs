---
description: >-
  This page will show you how to close long stocks & options positions. STC
  (Sell to Close) is the trigger to close long positions.
---

# Closing Long Position

### Stocks Input

{% hint style="info" %}
**STC \<ticker> @ \<price>**\
I.e. _`STC AAPL @ 150.20`_
{% endhint %}

To close your **long** stock position, use the trigger **`STC`** followed by the _ticker_ and use `@` before your price. \
![](<../../.gitbook/assets/image (82).png>)

### Options Input

{% hint style="info" %}
**STC \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
I.e. _`STC SPY 1/23 450 call @ 1.23`_\
_`STC SPY 1/23 450c @ 1.23`_
{% endhint %}

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. _`STC SPY 450c 1/23 @ 1.23`_
{% endhint %}

To close your **long** options position, use the trigger **`STC`** followed by the _ticker,_ then the expiration date using MM/DD format, your strike price and attaching **`c`** or **`p`** to it or specifying **`call` or `put`.** \
![](<../../.gitbook/assets/image (160).png>)\
\
_Note: You can use single digit months, but days always need to be double digits. I.e. 6/01_



{% hint style="warning" %}
#### You can enter in your actual price or use `CMP` or `M` for the current market price.
{% endhint %}
