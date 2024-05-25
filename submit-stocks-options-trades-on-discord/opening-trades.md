---
description: How to open both stocks & options positions
---

# Opening Trades

{% hint style="info" %}
Opening triggers;\
**`BTO`** is used to open long\
**`STO`** is used to open short
{% endhint %}

## Stocks Format

### Opening Long

> **BTO \<ticker> @ \<price>**\
> I.e. _`BTO AAPL @ 188`_

To open a **long** stock position, use the trigger **`BTO`** followed by the ticker, then the symbol @ before the price.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a long position for $AAPL at the price of $188.00</p></figcaption></figure>

### Opening Short

> **STO \<ticker> @ \<price>**\
> I.e. _`STO AAPL @ 177.94`_

To open a **short** stock position, use the trigger **`STO`** followed by the ticker, then the symbol **@** before the price.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a short position for $AAPL at the price of $177.94</p></figcaption></figure>

##

## Options Format

### Opening Long

> **BTO \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`BTO SPY 9/07 450 call @ 1.27`_\
> _`BTO SPY 9/07 450c @ 1.27`_

To open **long** options position, use the trigger **`BTO`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a long Call position for $SPY, 9/07 expiration date, $450 strike price, and $1.27 for the price by using CMP</p></figcaption></figure>

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. `BTO SPY 450c 9/07 @ 1.27`
{% endhint %}

### Opening Short

> **STO \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`STO SPY 9/08 450 call @ .32`_\
> _`STO SPY 9/08 450c @ .32`_

To open **short** options position, use the trigger **`STO`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a short Call position for $SPY, 9/08 expiration date, $450 strike price, and $0.32 for the price by using CMP</p></figcaption></figure>

{% hint style="warning" %}
Final Notes:\
\- **Do not use `$` with tickers.** \
\- Submit using a specified price, or use `CMP` or `M` for submitting at the current market price.\
\- Multiple trades can be submitted in a single message by using 3 back ticks (\`\`\`) before and after the whole message.
{% endhint %}



## Using Slash Commands

Submitting trades through slash commands has a more user friendly aspect to it but can take some seconds longer than text messages.

### Stocks

Type in `/open` then select `stocks`.

Type in or select the direction `Long` or `Short`.&#x20;

Input the ticker or select a provided ticker matching your input.

Enter in the price or use `0` for the current market price.

ADD GIF HERE of submitting trade (may need new screenshot for matching data)

Notes can be added and are optional. Trade Styles (swing, scalp, etc.), [Risk Factor Flags](broken-reference), and a Take Profit and/or Stop Loss can all be added by using the notes.

<figure><img src="../.gitbook/assets/image (10) (1) (1).png" alt=""><figcaption><p>Example of opening a long position for $AAPL at $177.90, adding the Earnings risk flag, and setting both TP/SL</p></figcaption></figure>

### Options

Type in `/open` and select `options`.

Type in or select the direction `Long` or `Short`.

Input the ticker or select a provided ticker matching your input.

For State, select `Call` or `Put`.

Enter in the date using the format MM/DD. _(Use /YY if next year.)_

Put in the strike price.

Enter in the price or use `0` for the current market price.

ADD GIF HERE of submitting trade (may need new screenshot for matching data)

Notes can be added and are optional. Trade Styles (swing, scalp, etc.), [Risk Factor Flags](broken-reference), and a Take Profit and/or Stop Loss can all be added through by the notes.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a long options call position for $SPY with $450 strike &#x26; expiration date of 9/07, adding the YOLO high risk flag, and setting both TP/SL</p></figcaption></figure>



{% hint style="info" %}
Did you know?\
Multiple trades can be submitted in a single text message by starting the message with 3 backticks (\`\`\`) and ending the message with 3 backticks.
{% endhint %}
