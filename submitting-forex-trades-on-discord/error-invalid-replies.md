---
description: Explanation of error or invalid message replies you might run into
---

# Error/Invalid Replies

### **Invalid:** Your input format is invalid, please recheck the format of your message.

The format of your message is wrong. Common cases include mistyping triggers or `cmp`, misplacing or excluding ticker, or not including the `@` before price.

### That ticker symbol is invalid!

The specified tickers do not exist, was spelled wrong, or (unlikely) is not in our system. Please only click the Report button if it's actual tickers, not a typo.

### Your price is too far off the current market price of...

This occurs when the specified price of the trade is outside the tolerated range of the current price at the time of submission.

{% hint style="info" %}
**Did you know?**\
_&#x59;_&#x6F;u may use the `/fixtrade` or `$fixtrade` command to request a trade to be forced in on your behalf if you run into an error or issue preventing a legitimate trade from being submitted.
{% endhint %}

### You do not have a position in...

This occurs when you attempt to submit a closing trade for a position that is not currently opened. _Double check that the open position is long or short, and that the proper trigger is being used when closing._

### You already have an open position in _`TICKER`_

There cannot be two opposite direction open positions (long & short) for the same base & quote currency tickers. If a long position has been submitted and a short sell position with the same tickers is attempted to be submitted, this error will occur.

### You cannot set your `TP`/`SL` `above`/`below` the current market price.

This occurs when you attempt to set a TP below the current market price, or a SL above the current market price.
