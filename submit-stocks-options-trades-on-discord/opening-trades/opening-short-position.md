---
description: >-
  This page will show you how to open short stocks & options positions. STO
  (Sell to Open) is the trigger to open short sell positions.
---

# Opening Short Position

### Stocks Input

{% hint style="info" %}
**STO \<ticker> @ \<price>**\
I.e. _`BTO AAPL @ 150.20`_
{% endhint %}

To open your **short** stock position, use the trigger `STO` followed by the ticker and use `@` before your price.\
![](<../../.gitbook/assets/image (180).png>)\


### Options Input

{% hint style="info" %}
**STO \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
I.e. _`STO SPY 1/23 450 call @ 1.23`_\
_`STO SPY 1/23 450c @ 1.23`_
{% endhint %}

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. _`STO SPY 450c 1/23 @ 1.23`_
{% endhint %}

To open your **short** options position, use the trigger **`BTO`** followed by the _ticker,_ then the expiration date using MM/DD format, your strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put`. \
![](<../../.gitbook/assets/image (66).png>)\
\
_Note: You can use single digit months, but days always need to be double digits. I.e. 6/01_



{% hint style="warning" %}
#### You can enter in your actual price or use `CMP` or `M` for the current market price.
{% endhint %}
