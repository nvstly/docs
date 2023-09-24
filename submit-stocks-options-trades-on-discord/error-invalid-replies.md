---
description: Explanation of error or invalid message replies you might run into.
---

# Error/Invalid Replies

### **Invalid:** Your input format is invalid, please recheck the format of your message.

The format of your message is wrong. Common cases include mistyping triggers or `cmp`, misplacing or excluding ticker, expiration date, strike price, missing `call`/`put`, or not including the `@` before price.

{% hint style="info" %}
**Did you know?**\
_Y_ou may use the `/fixtrade` or `$fixtrade` command to request a trade to be forced in on your behalf if you run into an error or issue preventing a legitament trade from being submitted.
{% endhint %}

### That ticker symbol is invalid!

The specified ticker does not exist, was spelled wrong, or is not yet in our system. Typically, IPOs take 48-72 hours to be added. Please only click the Report button if it's an actual ticker, not a typo.

### Your price is too far off the current market price of...

This occurs when the specified price of the trade is outside the tolerated range of the current price at the time of submission.

### Your premium price is too far off the current price of...

This occurs when the specified premium price for an options trade submission is outside the tolerated range of the current price at the time of submission.

### You do not have a position in...

This occurs when you attempt to submit a closing trade for a position that is not currently opened. _Double check that the open position is long or short, and that the proper trigger is being used when closing._

### I don't recognize that expiration date! Use mm/dd format or recheck.

This occurs if the specified expiration date is incorrect or non-existent. _This typically happens when a date is mistyped, or sometimes requires the mm/dd/yy format if next years date._

### I don't recognize that strike price.

This occurs if the specified strike price is not a real strike for that options contract.

### You already have an open position in _`TICKER`_

There cannot be two opposite direction open positions (long & short) for the same stock or options contract. If a long position has been submitted and a short sell position with the same ticker or options contract is attempted to be submitted, this error will occur.

### You cannot set your `TP`/`SL` `above`/`below` the current market price.

This occurs when you attempt to set a TP below the current market price, or a SL above the current market price.
