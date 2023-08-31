---
description: >-
  How to set or change TP/SL, one or both can be set. These can auto close your
  trade when their specified levels are hit.
---

# Setting TP/SL

### How To Set

{% hint style="info" %}
**Take Profit & Stop Loss can be set, or just one**. The format is not strict, just need to specify the price after the letters **`TP`** or **`SL`** | To cancel one, set it to **0** (zero)\
Example;\
`TP 2.34`\
`SL 1.23`
{% endhint %}

You can set a _Take Profit_ and/or a _Stop Loss_ on your trades. It helps to set a stop loss on your trades as you would in your real trading account, otherwise your options trades can expire for -100% and impact your stats if you forget to submit the exit.\
\
Each time you submit an opening trade a temporary blue button labeled _Set TP/SL_ will be available. When clicking this button the bot will prompt you with an ephemeral message that only you can see noting the format to use when setting a TP and/or SL.\
![](<../.gitbook/assets/image (89).png>)\
The format is simple, just be sure to note **`TP`** before the price of your _Take Profit_ and **`SL`** before the price of your _Stop Loss_. Characters can be used between **`tp`**/**`sl`** and the price, a space between TP/SL and price, or even none  at all.\
\
When successfully setting your TP/SL the bot will react with :white\_check\_mark: and it's ephemeral message will edit to _Added new TP/SL._ and you will see that the original bots confirmation message reply to your trade has been edited with the set prices for your _Take Profit_ and/or _Stop Loss_.\
![](<../.gitbook/assets/image (151).png>)\
**You can either set one or the other.**\
**To cancel one just set it to 0.**\
\
The bot will not allow you to set a _TP_ under the current market price or an _SL_ above the current market price for _long_ trades, and vice versa for _short_. But _TP/SL_ can be changed at any time as the market price moves.

### Changing TP/SL

{% hint style="info" %}
$list Displays 5 latest open trades
{% endhint %}

You can change your _TP/SL_ anytime by hitting the same button again, or using the **`$list`** command which will show your last 5 open trades. (We're working on the ability to show or select more trades to display)\
![](<../.gitbook/assets/image (69).png>)

### When TP/SL is Hit

Trades are intended to auto close when your specified TP/SL levels are reached. When this occurs you will receive a DM notification from the bot, _be sure you don't have DM's disabled for the server you're using it in._

{% hint style="danger" %}
_**Auto closing at TP/SL when hit is not always 100% success with volatility, if you have them set and your play didn't close when hit please use `$fixtrade` or reach out to**_ [_**support**_](https://trhub.net/discord)_**.**_
{% endhint %}
