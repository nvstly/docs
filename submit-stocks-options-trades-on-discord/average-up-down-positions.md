---
description: >-
  Positions can be averaged up or down, but cannot be 100% accurate as position
  sizes are not a factor. Position averaging is calculate based on a single
  share or contract
---

# Average Up/Down Positions

There is no extra trigger or syntax to average positions. Using the same opening submission for an existing trade that is still open will average the position.\
\
For example, if you submit `BTO AAPL @ 180` and do not close it, when you submit another opening position the same as an existing one, such as `BTO AAPL @ 170,` it will already know you have an existing open trade for this ticker and will auto calculate the new average for this trade to 175- the average of 180 & 170.\
\
Averaging is the same with options, as long as the ticker, expiration date, call/put, & strike price are the same.\


<figure><img src="../.gitbook/assets/image (231).png" alt=""><figcaption><p>Example of averaging down</p></figcaption></figure>



## Using Slash Commands

The same concept applies to slash commands as with text commands. Submitting an open position for the same existing open position will average it.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of averaging a position using slash command</p></figcaption></figure>

{% hint style="danger" %}
Averages can't be 100% accurate due to the app not tracking position sizes. If only 1 share/contract is being traded, it will be 100%. The app only recognizes that order quantity is always 1, and it can't be specified otherwise. \
\
_An example of inaccuracy; trade opened with 5 shares for $10.00, then averaged with 2 shares for $9.00 which creates a new average price of \~$9.71. The app only recognizes that 1 share has been opened for $10.00, and 1 additional share for $9.00- therefore calculating the average to $9.50._
{% endhint %}
