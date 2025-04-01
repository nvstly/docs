---
description: >-
  How to set and change a Take Profit and/or Stop Loss. Trades are automatically
  closed when the asset prices reaches these specified values
---

# Setting TP/SL

There are various methods in setting and changing Take Profits and Stop Losses.

## Using the "Add TP/SL" button

When the bot replies to an open trade submission, a blue button titled `Add TP/SL` is attached with it's response. Clicking this will prompt a user friendly popup where values can be specified for Take Profit and/or Stop Loss. Set the value for one or both.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Set TP/SL popup upon clicking the "Add TP/SL" button</p></figcaption></figure>

The bot will not allow a value below the current market price to be set for a Take Profit, and a value above the current market price to be set for a Stop Loss- and vice versa for short positions.

#### Changing or removing TP/SL using "Add TP/SL" button

This button can also be used to change or remove existing TPs and SLs. To change, simply specify a new value. To remove one or both, set the value to 0 (zero).

{% hint style="info" %}
Did you know?\
Using the `$list` or `/list` command will display all open trades where each one has a button to add or change TP/SL.
{% endhint %}

After successfully setting or changing a TP/SL, the bot sends a ephemeral message to confirm the values specified. The bot will also edit it's response embed to the submitted trade to display the TP/SL values.

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Successfully setting or changing TP/SL</p></figcaption></figure>

## Setting TP/SL with trade submission

Take Profit and/or Stop Loss values can be specified anywhere within the trade notes when submitting a trade. When using the keyword letters `TP` and/or `SL`, any numbers following after them will be the values used. It's sophisticated in a way where symbols or words can be used between `TP`/`SL` and the number values.

> Specify the price after the keyword letters **`TP`** & **`SL`** | To cancel or remove a TP/SL, set it to **0** (zero).\
> Examples;\
> `TP 2.34 SL 1.23`\
> `TP @ 2.34 and SL @ 1.23`\
> `TP is 2.34 & SL is 1.23`\
> &#xNAN;_(Any symbol or word can be used where `@` and `is` are.)_

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Example of setting TP/SL values with trade submission notes</p></figcaption></figure>

### Changing TP/SL using List command

{% hint style="info" %}
The `$list` or `/list` command displays all open trades ordered by most recent. Specifying a ticker with the command will show only open trades for that ticker symbol.
{% endhint %}

A TP/SL can be added, changed, or removed at any time by using the `$list` or `/list` command.  It displays all your open trades 4 at a time. Each trade has a TP/SL button that can be used to specify new or remove values.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>List command display example</p></figcaption></figure>

### When TP/SL is Hit

Trades are intended to auto close when the asset's price reaches or exceeds the specified TP/SL values. When this occurs, the bot will send a message notification in the originating server channel the trade was opened in, as well send a DM notification (if enabled) to the trader or user.

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1).png" alt=""><figcaption><p>Notification sent to channel the trade originates in</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>DM notification for TP/SL being triggered</p></figcaption></figure>

{% hint style="danger" %}
Note: Auto closing at TP/SL when hit is not always 100% successful with volatility. If you have them set and a trade didn't close when it should, please use the `$fixtrade` command or reach out to [support.](https://discord.gg/rhAvzyzk9J)
{% endhint %}

~~Editor notes: Add .gif of setting TP/SL and bot editing the embed.~~
