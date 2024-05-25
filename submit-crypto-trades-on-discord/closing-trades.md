---
description: How to close crypto positions
---

# Closing Trades

Closing triggers;\
**`STC`** is used to close long\
**`BTC`** is used to close short

### Closing Long

> **STC \<ticker>/\<pair> @ \<price> \[exchange]**\
> I.e. _`STC BTC/USDT @ 26995 binance`_

To close a **long** crypto position, use the trigger **`STC`** followed by the ticker/pair (I.e. BTC/USDT), then the symbol @ before the price. By default on new accounts, the crypto exchange is set to Binance and if an exchange name is not specified the bot will log the trade for the Binance exchange. \
The default exchange, among other (market, pair) defaults, can be changed. See [defaults.md](defaults.md "mention")for more info.

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption><p>Example of closing a long position for BTC/USDT at the price of $27154.50 on default exchange</p></figcaption></figure>

### Closing Short

To close a **short** crypto position, use the trigger **`STC`** followed by the ticker/pair (I.e. BTC/USDT), then the symbol @ before the price. By default on new accounts, the crypto exchange is set to Binance and if an exchange name is not specified the bot will log the trade for the Binance exchange. \
The default exchange, among other (market, pair) defaults, can be changed. See [defaults.md](defaults.md "mention")for more info.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption><p>Example of closing a short position for BTC/USDT at the price of $27160.00 on default exchange</p></figcaption></figure>



{% hint style="warning" %}
Final Notes:\
\- **Do not use `$` with tickers.** \
\- Submit using a specified price, or use `CMP` or `M` for submitting at the current market price.\
\- Multiple trades can be submitted in a single message by using 3 back ticks (\`\`\`) before and after the whole message.
{% endhint %}



## Using Slash Commands

Submitting trades through slash commands has a more user friendly aspect to it but can take some seconds longer than text messages.

Type in `/close` then select `crypto`.

Type in or select the direction `Long` or `Short`.&#x20;

Type in or select an exchange.

Input the ticker & pair with a separator. (I.e. BTC/USDT)

Enter in the price or use `0` for the current market price.

ADD GIF HERE of submitting trade (may need new screenshot for matching data)

Notes can be added and are optional. Trade Styles (swing, scalp, etc.), [Risk Factor Flags](broken-reference), and a Take Profit and/or Stop Loss can all be added by using the notes.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of closing a long BTC/USDT position on the Binance exchange using 0 for the current market price</p></figcaption></figure>
