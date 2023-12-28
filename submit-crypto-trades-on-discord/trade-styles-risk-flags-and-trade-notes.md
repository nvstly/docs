---
description: Specifying trade styles, adding risk factor flags, and adding notes to trades
---

# Trade Styles, Risk Flags, & Trade Notes

Trade Styles

{% hint style="info" %}
**Available trade styles & keywords:**\
Daytrade - Swing - Scalp - Long Term
{% endhint %}

Specifying the style of a trade has no functionality other than cosmetic and informational purposes. It can help viewers whether the trade is short or long term. By default, all trades use the `Daytrade` style unless specified otherwise.&#x20;

![](<../.gitbook/assets/image (236).png>)![](<../.gitbook/assets/image (237).png>)

To set the style of a trade, mention any one of the style keywords anywhere in the trade notes.

<figure><img src="../.gitbook/assets/image (238).png" alt=""><figcaption><p>Trade Style keyword "swing" used in notes will mark the trade as a swing</p></figcaption></figure>

## Risk Flags

{% hint style="info" %}
**Risk Factor Keywords:**\
YOLO\
Risk, Risky
{% endhint %}

> `yolo` will be marked as _High Risk YOLO Play_
>
> \
> `risk` or `risky` or `high risk` will be marked as _High Risk Play_

To specify risk factors on trades, use trade flag keywords anywhere in the notes. More than one trade flag can be applied.

Trades flagged with a risk factor are displayed as such on the [Trades](https://nvst.ly/trades) and Trade Insight interfaces.

<figure><img src="../.gitbook/assets/image (239).png" alt=""><figcaption><p>Risk Flag "High Risk" added by using the keyword in Trade Notes</p></figcaption></figure>

![](<../.gitbook/assets/image (240).png>)![](<../.gitbook/assets/image (241).png>)

{% hint style="danger" %}
YOLO trades are exempted from main Win Rate and all main Loss/Gain/Return stats, and have their own stats for each.
{% endhint %}

## Trade Notes

Trade Notes are comments that are attached to trades when they are submitted. They give more insight from the trader about the position. Notes are displayed for each event (open, close, etc.) on [Trades](https://nvst.ly/trades) and Trade Insight interfaces.

![](<../.gitbook/assets/image (244).png>)![](<../.gitbook/assets/image (245).png>)

Adding notes with trade submissions are done by commenting or writing anything after the trade price.

<figure><img src="../.gitbook/assets/image (242).png" alt=""><figcaption><p>Comments added to trade submission using Trade Notes</p></figcaption></figure>

{% hint style="info" %}
Remember

Trim/Partial keywords, setting TP/SL, Trade Styles, & Risk Flags, are all done by utilizing Trade Notes, and all can be used in a single trade's notes.
{% endhint %}

### Standalone Notes

You can add individual notes without necessitating a position update, such as an average or trim/partial. There are two methods of adding standalone notes through Discord, there are additional methods when using the web or mobile apps, see [update-notes-and-media.md](../submit-trades-from-web/submit-trades/update-notes-and-media.md "mention")

To add a standalone note, just reply to the bot's confirmation response for any of your trade submissions. These notes will be displayed individually on the Trade Insight interface. Up to 3 images can be attached with the message and will be displayed on the Trade Insight interface- a feature for PRO members.

<figure><img src="../.gitbook/assets/image (269).png" alt=""><figcaption><p>Replying to the bot's response with a message will be logged as standalone notes</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (270).png" alt=""><figcaption><p>Standalones notes are displayed as updates on Trade Insight interfaces</p></figcaption></figure>

Another method for adding standalone notes is through the use of the /list or $list command. Each trade displayed in the response of the command will have an "Update" button which will prompt a popup of a text box to enter in notes. _Images can't be added using this method._

<figure><img src="../.gitbook/assets/image (271).png" alt=""><figcaption><p>The /list command UI</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (268).png" alt=""><figcaption><p>This prompt appears when hitting the Update button on the /list UI</p></figcaption></figure>

{% hint style="success" %}
For PRO members, up to 3 images can be included with notes. Whether attached to your Discord message when submitting a trade, or uploading through the app, they will appear on the Trade Insight interface.
{% endhint %}
