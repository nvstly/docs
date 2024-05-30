---
description: How to open crypto positions
---

# Opening Trades

Opening triggers;\
**`BTO`** is used to open long\
**`STO`** is used to open short

There are many ways to open crypto positions, this documentation will go over the most basic way using the full format. Formats for submitting crypto trades can be shorter & more effecient by utilizing the [defaults.md](defaults.md "mention")settings.

### Opening Long

> **BTO \<ticker>/\<pair> @ \<price> \[exchange]**\
> I.e. _`BTO BTC/USDT @ 26952 binance`_

To open a **long** crypto position, use the trigger **`BTO`** followed by the ticker/pair (I.e. BTC/USDT), then the symbol @ before the price. By default on new accounts, the crypto exchange is set to Binance and if an exchange name is not specified the bot will log the trade for the Binance exchange. \
The default exchange, among other (market, pair) defaults, can be changed. See [defaults.md](defaults.md "mention")for more info.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a long position for BTC/USDT at the price of $27154.580 on Binance</p></figcaption></figure>

### Opening Short

> **STO \<ticker>/pair @ \<price> \[exchange]**\
> I.e. _`STO BTC/USDT @ 26951 binance`_

To open a **short** crypto position, use the trigger **`STO`** followed by the ticker/pair (I.e. BTC/USDT), then the symbol @ before the price. By default on new accounts, the crypto exchange is set to Binance and if an exchange name is not specified the bot will log the trade for the Binance exchange. \
The default exchange, among other (market, pair) defaults, can be changed. See [defaults.md](defaults.md "mention")for more info.

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption><p>Example of opening a short position for BTC/USDT at the price of $27171.00 on default exchange</p></figcaption></figure>



{% hint style="warning" %}
Final Notes:\
\- **Do not use `$` with tickers.** \
\- Submit using a specified price, or use `CMP` or `M` for submitting at the current market price.\
\- Multiple trades can be submitted in a single message by using 3 back ticks (\`\`\`) before and after the whole message.
{% endhint %}



## Using Slash Commands

Submitting trades through slash commands has a more user friendly aspect to it but can take some seconds longer than text messages.

Type in `/open` then select `crypto`.

Type in or select the direction `Long` or `Short`.&#x20;

Type in or select an exchange.

Input the ticker & pair with a separator. (I.e. BTC/USDT)

Enter in the price or use `0` for the current market price.

ADD GIF HERE of submitting trade (may need new screenshot for matching data)

Notes can be added and are optional. Trade Styles (swing, scalp, etc.), [Risk Factor Flags](broken-reference), and a Take Profit and/or Stop Loss can all be added by using the notes.

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1).png" alt=""><figcaption><p>Example of opening a long BTC/USDT position on the Binance exchange using 0 for the current market price, and setting style to Long Term</p></figcaption></figure>
