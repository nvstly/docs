---
description: Explanation of error or invalid message replies you might run into.
---

# Error/Invalid Replies

## **Will be written soon, doesn't use all the same errors as stocks/options trades- finishing them up and will note them here.**

### **Invalid:** Your input format is invalid, please recheck the format of your message.

The format of your message is wrong. Common cases include typos of triggers or `cmp`, misplacing ticker/pair, not using the right format, or not including the `@` before price.



### That ticker and/or pair is invalid!

The ticker or trading pair you used was not found on the exchange the trade was specified on. Double check your default exchange or the one you specified in the trade submit input is correct.\
\
If you feel it's a mistake, hit the _Report_ button and we'll look into it. You can also hit the _Report & Fixtrade_ button to report the issue and request a fixtrade at the same time.



### Your price is too far off the current market price of...

This occurs when your specified price for the crypto trade is outside of the allowed range of the current market price at the time of submission. _Use `$fixtrade` if you can't get in your actual price._



### You don't have an open position in...

This occurs when you are using a closing input for a crypto ticker/pair that you do not currently have an open position for. Check if your open position is long or short, and that you are using the proper triggers when closing, or that you're specifying the correct exchange. Use `$fixtrade` if your open position closes unexpectedly.



### You already have an open position in _`TICKER`_

On the same exchange, you cannot have two open positions in opposite directions (long/short) for the same crypto token and pair.If you've submitted a long position and try to submit a short sell position on the same ticker/pair, you will get this error- and the same vice versa.

