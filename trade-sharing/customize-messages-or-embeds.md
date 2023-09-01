---
description: You can customize your Discord message or embed, and your Twitter post.
---

# Customize Messages or embeds

{% hint style="info" %}
This can be seen as intimidating with all the available configurations & properties, but we wanted to allow for very detailed messages or embeds. We've set a default embed that shows you how the embeds are built using some of the available properties.
{% endhint %}

{% embed url="https://youtu.be/6WDa5jnrTJg" %}

## Discord

You can customize the Discord message or embed you intend on using to share your trades to Discord, for both stocks & options- and crypto soon. **Open, average, trim, & exit trades can be shared with fully customize message or embed content for each event.**&#x20;

To customize your Discord message or embed, go to [account settings ](https://thetradehub.net/settings) and under _Trade Sharing_ click the _Embed_ button.\
![](<../.gitbook/assets/image (199).png>)

This will prompt you with the message/embed builder as shown below. The message builder is pretty self-explanatory. To start, choose either stocks or options at the top to begin building custom embeds for. Then choose either Open, Average, Partial, or Exit to specify which trade event you want to customize the shared message for.

![](<../.gitbook/assets/image (7) (1).png>)\
You can edit the message for every trade position event.\
There is a checkbox to choose whether to use a regular text message or embed, which is set as default.



![](<../.gitbook/assets/image (101).png>)

There is a selection of properties that get prefilled with the data they represent when a trade is made and is shared on Discord. When clicking these, they will be automatically filled in where your cursor is. Some properties will be hidden depending on the trade event selected—for example, there are no options properties available when Stocks are selected, or `Trade Exit Price` isn't an option for the Open trade event.\
You can hit the Show Advanced button to see more properties, such as stock volume and other stats related to a stock. In the [Account & Trade Properties](customize-messages-or-embeds.md#properties) section below you can see all the available properties and what they represent.

The embed builder is easy to use, there is a text box for each aspect of an embed. In the [Message & Embed Properties](customize-messages-or-embeds.md#undefined) section below you can see which each text box represents.\


<figure><img src="../.gitbook/assets/image (191).png" alt=""><figcaption><p>Choose which properties of your trade to share and how it looks.</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (161).png" alt=""><figcaption><p>You can get a preview of your trade by using an advanced trade input format in the <em>Test Input</em> field.</p></figcaption></figure>

{% hint style="success" %}
You can see a **preview** of how your message or embed will look by typing out a sample trade input- knowledge of [advanced input](../submit-trades-from-web/advanced-input.md#how-to-use-advanced-method) is required for this. _Use `bto aapl @ cmp` as an example._
{% endhint %}

{% hint style="info" %}
@everyone and role pings should be set with your webhooks settings so you can specify a ping for each webhook your trade is shared with. [#pings-everyone-here-role](discord.md#pings-everyone-here-role "mention")
{% endhint %}

## Account, Trade, & Stock Properties

Properties are a menu of data sets that can display stock tickers, current price, your account username & avatar, and so many others including advanced data sets such as the volume and the days high/low prices.

![](<../.gitbook/assets/image (95).png>)

**NOTE:**\
You can have properties punctuated to start with capital letters, or have the whole value of that property in all caps.\
For example: \
\[\[stock.name]] the ticker would be `aapl`\
\[\[Stock.name]] the ticker would be `Aapl`\
\[\[STOCK.name]] the ticker would be `AAPL`\
\[\[trade.type]] would be `open,` `average,` p`artial,` or `close`\
\[\[Trade.type]] would be `Open,` `Average,` `Partial,`or `Close`

#### Account Properties

<table><thead><tr><th width="221" align="center">Property Name</th><th align="center">Info</th></tr></thead><tbody><tr><td align="center">Account Username</td><td align="center">Your username on the web app</td></tr><tr><td align="center">Account Avatar</td><td align="center">Your avatar or profile picture on the web app</td></tr><tr><td align="center">Account Link</td><td align="center">Your <a href="https://thetradehub.net/dashboard">dashboard</a> link</td></tr><tr><td align="center">Account Rep</td><td align="center">Your reputation count</td></tr></tbody></table>

#### Trade Properties

<table><thead><tr><th width="236" align="center">Property Name</th><th align="center">Info</th></tr></thead><tbody><tr><td align="center">Trade Position Type</td><td align="center">Direction or type of the position. (long/short)</td></tr><tr><td align="center">Trade Price</td><td align="center">The submitted price of your trade. I<em>f cmp is used when submitting a trade, then uses that price</em></td></tr><tr><td align="center">Trade Entry Price</td><td align="center">The entry price of trade. (can use Trade Price instead)</td></tr><tr><td align="center">Trade Exit Price</td><td align="center">The exit price of trade. (can use Trade Price instead)</td></tr><tr><td align="center">Trade Average Price</td><td align="center">New average price if a trade has been averaged up/down</td></tr><tr><td align="center">Trade TP</td><td align="center">Take Profit of your trade- blank if none - <em>Advanced Menu</em></td></tr><tr><td align="center">Trade SL</td><td align="center">Stop Loss of your trade- blank if none - Advanced Menu</td></tr><tr><td align="center">Trade Type</td><td align="center">The type of your trade. (open/average/trim/exit)</td></tr><tr><td align="center">Trade Style</td><td align="center">The style of your trade. (daytrade/scalp/swing/long term)</td></tr><tr><td align="center">Trade Flags</td><td align="center">The flag of your trade, if specified, or blank if none is specified. (risky or high risk, lotto or yolo, earnings)</td></tr><tr><td align="center">Trade Notes</td><td align="center">The notes of of your trade, blank if none</td></tr><tr><td align="center">Trade Timestamp</td><td align="center">Timestamp of the current submitted trade input</td></tr><tr><td align="center">Trade Opened At</td><td align="center">Timestamp of when the open trade input was submitted</td></tr><tr><td align="center">Trade Closed At</td><td align="center">timestamp of when the close trade input was submitted (Trade Timestamp can be used instead).</td></tr><tr><td align="center">Trade First Note</td><td align="center">The trade notes of the first submitted trade entry</td></tr><tr><td align="center">Trade Gain</td><td align="center">The gain percentage of a partial/trim or exit</td></tr><tr><td align="center">Trade Link</td><td align="center">The Trade Insight URL link</td></tr><tr><td align="center"><strong>OPTIONS PROPERTIES</strong></td><td align="center"><strong>INFO</strong></td></tr><tr><td align="center">Trade Options Exp Date</td><td align="center">Options expiration dates are written in mm/dd/yy format.</td></tr><tr><td align="center">Trade Options Exp NoYY</td><td align="center">Options expiration dates in mm/dd format</td></tr><tr><td align="center">Trade Options Strike</td><td align="center">Option trade strike price</td></tr><tr><td align="center">Trade Options Strategy</td><td align="center">Option trade, call or put</td></tr></tbody></table>

#### Stock Properties

<table><thead><tr><th width="220" align="center">Property Name</th><th align="center">Info</th></tr></thead><tbody><tr><td align="center">Stock Name</td><td align="center">Stock ticker symbol</td></tr><tr><td align="center">Stock Icon</td><td align="center">Company logo</td></tr><tr><td align="center">Stock CMP</td><td align="center">Current market price of stock at time of trade submission</td></tr><tr><td align="center">Stock Volume</td><td align="center">Trading volume of stock - Advanced Menu</td></tr><tr><td align="center">Stock Day High</td><td align="center">Highest price of stock today - Advanced Menu</td></tr><tr><td align="center">Stock Day Low</td><td align="center">Lowest price of stock today - Advanced Menu</td></tr><tr><td align="center">Stock Previous Close</td><td align="center">Closing price from the previous market day - Advanced Menu</td></tr></tbody></table>

### Message & Embed Properties

![](<../.gitbook/assets/image (9) (1).png>)\


<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption><p>Embed example</p></figcaption></figure>

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption><p>Example of how inline Field's work</p></figcaption></figure>

<table><thead><tr><th width="182">Property</th><th>Value</th></tr></thead><tbody><tr><td>Author Name</td><td>The name of author of the embed author</td></tr><tr><td>Author URL</td><td>Used to link the Author Name</td></tr><tr><td>Author Image</td><td>An avatar for author, shown with the teal logo in the example above</td></tr><tr><td>Title</td><td>The embed title</td></tr><tr><td>Title URL</td><td>Used to link the Title</td></tr><tr><td>Color</td><td>The embed color, shown as the teal strip in the example above</td></tr><tr><td>Description</td><td>The content within the embed</td></tr><tr><td>Thumbnail URL</td><td>The thumbnail image, shown as the white logo in the example above</td></tr><tr><td>Image URL</td><td>Adds an image below the description and the above footer</td></tr><tr><td>Footer Name</td><td>The small footer text at the bottom</td></tr><tr><td>Footer Img URL</td><td>The footer image, shown as the black logo in the example above</td></tr><tr><td>Timestamp</td><td>Used to show date/time at end of footer</td></tr><tr><td>Field (w/ inline)</td><td>Creates text fields with headers &#x26; values. These can be 'inline' to put 2-3 of them on the same row.</td></tr></tbody></table>

{% hint style="info" %}
Author Name & Author Image URL are not to be confused with the username & avatar that the webhook name & avatar uses.
{% endhint %}

## Twitter

To customize your Twitter tweets, go to [account settings ](https://thetradehub.net/settings) and under _Trade Sharing_ click the _Embed_ button.\
![](<../.gitbook/assets/image (165).png>)

\
This will prompt you with the tweet builder as shown below. You can edit the message for every trade position event.

<figure><img src="../.gitbook/assets/image (136).png" alt=""><figcaption><p><em>Choose which properties of your trade to share and how it looks.</em></p></figcaption></figure>

## Examples

Here are some examples of custom messages & embeds to give inspiration on how you can make yours look.

{% embed url="https://photos.app.goo.gl/6YKLn44UtrdsWRPN9" %}
Discord Trade Sharing Examples
{% endembed %}

{% embed url="https://photos.app.goo.gl/EmTM1LhsFUrYz2KXA" %}
Twitter Trade Sharing Examples
{% endembed %}
