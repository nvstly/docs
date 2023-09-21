---
description: Explanation of error or invalid message replies you might run into.
---

# Error/Invalid Replies

### **Invalid:** Your input format is invalid, please recheck the format of your message.

The format of your message is wrong. Common cases include typos of triggers or `cmp`, misplacing ticker, expiration date, strike price, missing `call`/`put`, or not including the `@` before price.



### That ticker symbol is invalid!

The specified ticker does not exist, was spelled wrong, or is not yet in our system. Typically, IPOs take 48-72 hours to be entered. Please only click the Report button if it's an actual ticker, not a typo. You may use $fixtrade to request a trade if this occurs for an actual ticker.

### Your price is too far off the current market price of...

This occurs when your specified price for the stock trade is out of the allowed range of the current stock price at the time of submission. _Use `$fixtrade` if you can't get in your actual price._



### Your premium price is too far off the current price of...

This occurs when your input premium price is outside of the allowed range of the current premium price at the time of submission. Some prices move fast, so the speed of input is imperative. Use `$fixtrade` if you can't get in your actual price.



### You don't have an open position in...

This occurs when you are using a closing input for a stock or options contract that you do not currently have an open position for. Check if your open position is long or short, and that you are using the proper triggers when closing. Use `$fixtrade` if your open position closed or expired unexpectedly.



### I don't recognize that expiration date! Use mm/dd format or recheck.

This occurs if the specified expiration date is incorrect. This typically happens when you use an expiration date that is not a real or existing date for that options contract. Do not add the year.



### I don't recognize that strike price.

This occurs if the specified strike price is not a real strike for that options contract.



### You already have an open position in _`TICKER`_

You cannot have two opposite direction open positions (long & short) for the same equity or options contract. If you've submitted a long position and try to submit a short sell position on the same ticker or options contract, you will get this error- and the same vice versa.
