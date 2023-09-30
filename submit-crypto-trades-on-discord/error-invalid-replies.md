---
description: Explanation of error or invalid message replies you might run into
---

# Error/Invalid Replies

### That ticker symbol is invalid!

The specified ticker does not exist, was spelled wrong, or is not on the default or specified exchange. Please only click the Report button if it's an actual ticker, not a typo.

### Your price is too far off the current market price of...

This occurs when the specified price of the trade is outside the tolerated range of the current price at the time of submission.

{% hint style="info" %}
**Did you know?**\
_Y_ou may use the `/fixtrade` or `$fixtrade` command to request a trade to be forced in on your behalf if you run into an error or issue preventing a legitimate trade from being submitted.
{% endhint %}

### You do not have a position in...

This occurs when you attempt to submit a closing trade for a position that is not currently opened. _Double check that the open position is long or short, and that the proper trigger is being used when closing._

### You already have an open position in _`TICKER`_

There cannot be two opposite direction open positions (long & short) for the same stock or options contract. If a long position has been submitted and a short sell position with the same ticker or options contract is attempted to be submitted, this error will occur.

### You cannot set your `TP`/`SL` `above`/`below` the current market price.

This occurs when you attempt to set a TP below the current market price, or a SL above the current market price.

