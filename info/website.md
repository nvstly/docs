---
description: Important web pages & what they are.
---

# Website

## Trades Page

The [trades page](https://trhub.net/trades) displays all the trades that are put in by traders. Each time a trader submits a trade it's displayed on this page in real-time or on a 15 minute delay for free users. Any time a trade is, averaged or trimmed/partially closed the trade is refreshed to the top of this list.\
\
Each row shows the trader who made the trade and all the data for that trade. It shows the ticker being traded along with the options data (if any) and the price it was opened at and tracks the trades profit/loss. The row expands by clicking the arrow on the right end, this will display any notes about the trade the trader as given.\
\
Traders can follow others & give reputation directly from these trade rows.

## New Trade

This where you can submit your trades or modify open trades to average, trim/partial, or close. Learn how to here [submit-trades.md](../submit-trades-from-browser/submit-trades.md "mention")\
\
What's To Come::\
\-Ability to send your trades instantly to Discord using webhooks, with customized messages or embeds\
\-Ability to post and share your trade on Twitter or Stocktwits with a customized preset message

## Push Notifications

{% hint style="info" %}
All push notifications are enabled by default.
{% endhint %}

* [x] Trades - Open/Average/Partial or Trim/Close
* [x] New followers
* [x] Reputation received
* [ ] Social Mentions

Notifications can be modified in your [Account Settings](https://thetradehub.net/settings) under the Account Management section by clicking on the Notifications button. From here you can disabled all or some events as well modify them for each user you follow\
.![](<../.gitbook/assets/image (178).png>)

## Trade Insight display

Trades have their own individual pages where additional data for that trade is displayed. This concept is still under development and will include data based on that stock, options contract, or crypto including screenshots of charts at entry and exits to show what a trader was looking at when making this play and potentially why.\
\
To see these pages click anywhere on the trade row from Trades, Dashboard, or Stock info pages, except on usernames, tickers, or dropdown arrow.\
<img src="../.gitbook/assets/image (39).png" alt="" data-size="line">\
<img src="../.gitbook/assets/image (4).png" alt="" data-size="original">

{% hint style="info" %}
You can add or modify your TP/SL directly from this display.
{% endhint %}

## Rankings / Leaderboards

The [rankings page](https://trhub.net/ranks) is a leaderboard that lists the ranks of the top 50 traders. There is a minimum requirement of seven (7) trades to be eligible for rank.\
\
The formula takes into account the following; total closed trades, win rate, & average gain. You are given a score based on these and ranked according to that score.\
\
This formula is subject to change as we stride to keep rankings fair for each type of trader and calculate scores than don't favor one stat over another.\
_Winning stock trades will have a multiplier soon as bigger gains are harder than options. This should help level the leaderboard for stocks vs options traders._

### Server Leaderboards

Servers also have their own leaderboard to rank traders only within that server. Server leaderboards rank every trader who is signed up and meets the minimum quantity of trades needed to rank.

{% hint style="info" %}
**trhub.net/ranks?guild=server-id-here**\
or\
**thetradehub.net/ranks?guild=server-id-here**
{% endhint %}

## Dashboard

Dashboard's are like a traders portfolio, they display the traders last 200 trades and all their trading statistics. Reputation points are displayed here and brief bio or about me section.\
\
When sharing your short URL dashboard link on social media or Discord, it produces an embed image displaying contents from your profile including your stats. [(See below for short URL)](website.md#undefined)\
![](<../.gitbook/assets/image (34).png>)

### Stats

Stats are based on all your closed trades. By default dashboards are a reflection of the past 30 days trading stats, but can be toggled using the `Stat Range` dropdown menu to toggle different time ranges.\
\
The following stats are currently functional;\
Total Trades, Closed Trades, Win Rate, Average Gain, Most Traded Stocks

{% hint style="danger" %}
Stats cannot be reset, ever. We plan to add a feature that will allow traders to reset their stats twice a year.
{% endhint %}

{% hint style="success" %}
What's to come;\
In-depth stats such as average loss, average time in position, minimum dollar values for total gain, average gain/loss, and more.
{% endhint %}

### Reputation

Reputation is our own karma system given between traders. Rep can be given to however many traders, but can only be given to the same trader once in a day. Traders might receive rep for having a top trade of the day, or being noticed on the leaderboards each week or month.

### Badges

PRO/PRO+ icons on dashboards and avatars distinguish subscribed members, you can acquire these by [upgrading your membership.](https://trhub.net/pro)\
\
Badges help traders distinguish themselves from the pack, representing top traders or those with a high win rate. Badges also represent which traders are official analysts or Trade Hub staff.

<details>

<summary>List of Badges</summary>

Top Trader - Ranked top 10 on all-time or 30 day leaderboards

High Win Rate - 80% or higher win rate

Tier 1-4 - Measure of a traders length of time and contributions in the Discord server

ELITE Analyst - An official Trade Hub analyst, we back their trades are of quality

Analyst - Prospects for ELITE & guest analysts

Developer - App developer for Trade Hub. You may see bizarre trades, likely for testing.

Staff - Official Trade Hub staff or support team

Founder - The only two with full administrator

</details>

### Social Media Links

Through your settings you can link your social media accounts and opt-in for them to be publicly displayed on your dashboard.

## Settings

Everything you think that can be set or configured will be found in [settings](https://thetradehub.net/settings), if available. Set your dashboard info, link your social media accounts, manage your account & membership plan, etc.\


### Download Data

\
You can download all your trade data & stats from this page by hitting the _Download CSV_ button and it provides a .csv file for spreadsheet format.

## Stock Info Page

Each stock ticker has it's own page displaying data for that ticker such as it's price, percentage & price movement, description about the stock, chart, and it's latest trades. Each stock also has it's own stats based on it's number of trades of app users including it's rank, total trades, and currently opened trades- along with displaying it's recent trades below the chart.\
\
To visit these pages you can click on any ticker in the trade rows on the trades page or dashboards, along with clicking on any of the hot stocks scrolling at the top of all pages.\
![](<../.gitbook/assets/image (64).png>)

{% hint style="info" %}
What's to come;\
TradingView charts built into this page with it's library of indicators.
{% endhint %}

## Crypto Info Page

COMING SOON

## Blog

The blog is where you can stay up to date on all the latest updates to the app, changelogs, announcements, and anything important.\
\
We also have categories for _analysis_ and _educational content_ where we plan to provide solid material useful for new traders or beginners.&#x20;

{% hint style="info" %}
If you're an experienced traders and have a hobby or passion for writing, we invite you to write for our blog! Please reach out to us in our [Discord server](https://trhub.net/discord) or by email.
{% endhint %}

## Short Links (URL)

We know, our web link is long. We've acquired a shorter web domain to be used for sharing your dashboard, trades, stock pages, and blogs.\
\
Currently functional is dashboards & blog posts. But taking anything after the forward slash after `thetradehub.net` and adding it after `trhub.net/` will redirect to that page. Blogs & dashboards can be used this way, but they have their own setups that we plan to add to individual trade pages & stock pages.

{% hint style="info" %}
**Dashboard Profiles**\
u.trhub.net/username\
![](<../.gitbook/assets/image (33).png>) _Blogs & dashboards have a share icon on their pages that uses the short URL._
{% endhint %}
