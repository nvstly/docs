---
description: >-
  Positions can be averaged up or down, but cannot be 100% accurate as position
  sizes are not a factor. Position averaging is calculate based on a single coin
---

# Average Up/Down Positions

There is no extra trigger or syntax to average positions. Using the same opening submission for an existing trade that is still open will average the position.\
\
For example, if you submit `BTO BTC/USDT @ 25000` and do not close it, when you submit  another opening position the same as an existing one, such as `BTO BTC/USDT @ 24000,` it will already know you have an existing open trade for this ticker and will auto calculate the new average for this trade to 24500- the average of 25000 & 24000.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1).png" alt=""><figcaption><p>Example of averaging up</p></figcaption></figure>

## Using Slash Commands

The same concept applies to slash commands as with text commands. Submitting an open position for the same existing open position will average it.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of averaging with slash command</p></figcaption></figure>



{% hint style="danger" %}
Averages can't be 100% accurate due to the app not tracking position sizes. If only 1 coin is being traded, it will be 100%. The app only recognizes that order quantity is always 1, and it can't be specified otherwise. \
\
_An example of inaccuracy; trade opened with 5 coins for $10.00, then averaged with 2 more coins for $9.00 which creates a new average price of \~$9.71. The app only recognizes that 1 coin has been opened for $10.00, and 1 additional coin for $9.00- therefore calculating the average to $9.50._
{% endhint %}
