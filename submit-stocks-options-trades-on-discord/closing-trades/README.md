---
description: How to close both stocks & options positions
---

# Closing Trades

{% hint style="info" %}
Closing triggers;\
&#xNAN;**`STC`** is used to close long\
&#xNAN;**`BTC`** is used to close short
{% endhint %}

## Stocks Format

### Closing Long

> **STC \<ticker> @ \<price>**\
> I.e. _`STC AAPL @ 178.70`_

To close a **long** stock position, use the trigger **`STC`** followed by the ticker, then the symbol @ before the price.

<figure><img src="../../.gitbook/assets/image (222).png" alt=""><figcaption><p>Example of closing a long position for $AAPL at the price of $178.70</p></figcaption></figure>

### Closing Short

> **BTC \<ticker> @ \<price>**\
> I.e. _`BTC AAPL @ 177.94`_

To close a **short** stock position, use the trigger **`BTC`** followed by the ticker, then the symbol **@** before the price.

<figure><img src="../../.gitbook/assets/image (223).png" alt=""><figcaption><p>Example of closing a short position for $AAPL at the price of $178.72</p></figcaption></figure>

##

## Options Format

### Closing Long

> **STC \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`STC SPY 9/15 450 call @ .88`_\
> &#xNAN;_`STC SPY 9/15 450c @ .88`_

To close **long** options position, use the trigger **`STC`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../../.gitbook/assets/image (224).png" alt=""><figcaption><p>Example of closing a long Call position for $SPY, 9/15 expiration date, $450 strike price, and $0.88 for the price.</p></figcaption></figure>

{% hint style="info" %}
You can also use the format with expiration after strike & call/put\
I.e. `BTO SPY 450c 9/15 @ .88`
{% endhint %}

### Closing Short

> **BTC \<ticker> \<exp. date> \<strike> \<call/put> @ \<price>**\
> I.e. _`BTC SPY 9/15 440 put @ 1.08`_\
> &#xNAN;_`BTC SPY 9/15 440p @ 1.08`_

To close **short** options position, use the trigger **`BTC`** followed by the _ticker,_ then the expiration date using MM/DD format _(and /YY if next year)_, the strike price, and either attaching **`c`** or **`p`** to it or specifying `call` or `put` followed by the symbol **@** and the price.

<figure><img src="../../.gitbook/assets/image (225).png" alt=""><figcaption><p>Example of closing a short Put position for $SPY, 9/15 expiration date, $440 strike price, and $0.88 for the price.</p></figcaption></figure>

{% hint style="danger" %}
Final Notes:\
\- **Do not use `$` with tickers.** \
\- Submit using a specified price, or use `CMP` or `M` for submitting at the current market price.\
\- Multiple trades can be submitted in a single message by using 3 back ticks (\`\`\`) before and after the whole message.
{% endhint %}



## Using Slash Commands

Submitting trades through slash commands has a more user friendly aspect to it but can take some seconds longer than text messages.

### Stocks

Type in `/close` then select `stocks`.

Type in or select the direction `Long` or `Short`.&#x20;

Input the ticker or select a provided ticker matching your input.

Enter in the price or use `0` for the current market price.

Notes can be added and are optional. Trimming or partially closing positions can be done by using the [Trim/Partial Close](../trim-partial-close.md) keywords (trim, trimming, partial, etc.) within the notes.

<figure><img src="../../.gitbook/assets/image (228).png" alt=""><figcaption><p>Example of closing a long position for $AAPL at $181.26, with exit notes.</p></figcaption></figure>

### Options

Type in `/close` and select `options`.

Type in or select the direction `Long` or `Short`.

Input the ticker or select a provided ticker matching your input.

For State, select `Call` or `Put`.

Enter in the date using the format MM/DD. _(Use /YY if next year.)_

Put in the strike price.

Enter in the price or use `0` for the current market price.

Notes can be added and are optional. Trimming or partially closing positions can be done by using the [Trim/Partial Close](../trim-partial-close.md) keywords (trim, trimming, partial, etc. ) within the notes.

<figure><img src="../../.gitbook/assets/image (229).png" alt=""><figcaption><p>Example of partially closing a long options call for $SPY with $450 strike &#x26; exp. date of 9/07. Partially closing by using keyword 'trimming' in notes.</p></figcaption></figure>



{% hint style="info" %}
Did you know?\
Quickly closing trades can be done by using the `$list` or `/list` command to show all open trades, where each one has a button to immediately close it at the current market price. Check out [Broken link](broken-reference "mention") for a list of all commands and how to use them.
{% endhint %}
