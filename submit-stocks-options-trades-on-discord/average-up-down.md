---
description: >-
  Our app calculates your averages when you submit an opening trade for a
  position you already have open. This can't be 100% accurate as it doesn't
  track trade size.
---

# Average Up/Down

There is no extra trigger or syntax to average your trades. If you have an open trade, and submit the same trade again with an opening trigger, it will calculate your new average.\
\
For example, if you input `BTO AAPL @ 180` and do not close it, when you put in another entry such as `BTO AAPL @ 170` it will already know you have an existing open trade for this ticker and will auto calculate the new average for this trade to 175.\
\
This is also done with options as well so long as the ticker, expiration date, & strike price is the same.\
![](<../.gitbook/assets/image (96).png>)

{% hint style="danger" %}
Averages can't be 100% accurate due to the app not tracking your order size. If you're only trading 1 share/contract, it will be 100%. The bot/app thinks your order quantity is 1, you can't tell it how much more you bought/shorted. So for example, if your original entry was 5 shares, then you buy 2 more it will be different- a lower average.
{% endhint %}
