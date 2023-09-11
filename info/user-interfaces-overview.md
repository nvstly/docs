---
description: Important UIs & what they are.
---

# User Interfaces Overview

### Trades Feed

The T[rades feed ](https://trhub.net/trades)displays all the trades that are submitted by traders. Each time a trader submits a trade it's displayed on this page in real-time or on a 15 minute delay for free users. Any time a trade is opened, averaged. trimmed/partially closed, or exited, the trade is refreshed to the top of this list.\
\
Each row shows the trader who made the trade and important information for that trade. It shows the ticker being traded with the direction (long/short) along with the options data (if any), the current status, and the price it was opened at and a profit/loss stat.

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Trade Row</p></figcaption></figure>

The row can be expanded which displays any notes about the trade the trader has provided.\
\
Users can give +Rep or drop comments directly from these trade rows.

## New Trade

This interface is used to submit trades and modify existing positions. It is used to open trades and the Active Positions tab is used to average, trim/partial close, or exit your open positions.

To learn how to use this interface, see [submit-trades.md](../submit-trades-from-browser/submit-trades.md "mention")

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>New Trade</p></figcaption></figure>

{% hint style="info" %}
Did you know?\
You can auto share your submitted trades directly to Discord with the use of webhooks and fully customized messages and/or embeds? Check out LINK HERE for more info. _With X (previously Twitter) support soon._
{% endhint %}

## Push Notifications

{% hint style="info" %}
All push notifications are enabled by default.
{% endhint %}

* [x] Trades _(enable/disable for each trader you follow)_
* [x] New followers
* [x] Reputation received
* [ ] Social Mentions _(coming soon)_

Notifications can be modified in your Account Settings within the [Notifications](https://nvst.ly/settings/notifications) section.. From here you can enabled/disable all or some events as well modify them for each trader you follow.

<figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1).png" alt=""><figcaption><p>Customize Notifications for Each Trader</p></figcaption></figure>

## Trade Insight

Trades have their own individual interfaces where additional data for that trade is displayed. Everything pertaining to a submitted trade will be shown on this UI such as every position update, TP/SL change, and notes or media uploads, including additional elements such as ticker data and our unique POV Charts that gives viewers a traders perspective of a chart when they were taking and updating positions.

To access these interface displays, click the trade info from trade rows that are listed on the [Trades](user-interfaces-overview.md#trades-feed) feed, trader [Dashboards](user-interfaces-overview.md#dashboard), or [Stock Info](user-interfaces-overview.md#stock-info-page) displays.

<figure><img src="../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""><figcaption><p>Trade Insight Interface <em>(comments section soon)</em></p></figcaption></figure>

{% hint style="info" %}
You can update positions and add or modify your TP/SL directly from this interface.
{% endhint %}

## Leaderboards

The [rankings](https://nvst.ly/ranks) interface are side by side leaderboards that lists the ranks of the top traders for any and all markets. We've formulated a scoring system that ranks traders based on their total number of closed trades, win rate, & average return. Traders need a minimum of seven (7) trades for ranking eligibility.\
_Winning stock trades will have a multiplier soon as bigger gains are harder than options. This should help level the leaderboard for stocks vs options traders._

{% hint style="warning" %}
The ranking formula is subject to change as we stride to keep rankings fair for each type of trader and calculate scores that don't favor heavily of one stat over another.
{% endhint %}

#### Server-Only Leaderboards

Servers can access their own leaderboards which rank only traders within their community. These leaderboards display the ranks of every trader who is a signed up user on our platform and also meets the the seven (7) trade minimum quantity for eligibility.

{% hint style="info" %}
**How to see server-only leaderboards?**\
`https://trd.ng/ranks?guild=server-id-here`\
or\
`https://nvst.ly/ranks?guild=server-id-here`
{% endhint %}

## Dashboard

A trader's Dashboard is like a mix between their social profile and portfolio, displaying their latest trades, trading performance stats, and some general info about the trader such as their join date, badges earned, reputation count, and their bio.

#### Stats

Stats are primarily based on all your closed trades, with the exception of a few. By default dashboards are a reflection of a traders activity and performance for the past 30 days, but time ranges can be filtered using the dropdown above the stats component.

<figure><img src="../.gitbook/assets/image (5) (1) (1) (1) (1).png" alt=""><figcaption><p>First set of stats</p></figcaption></figure>

{% hint style="danger" %}
Stats cannot be reset, ever. We plan to add a feature that will allow traders to reset their stats 1-2 times a year, but even then there will be a historical archive publicly available of stats prior to a reset.
{% endhint %}

#### Reputation

<img src="https://cdn.discordapp.com/emojis/1084784995912142868.webp?size=96&#x26;quality=lossless" alt=":rep~1:" data-size="line"> +Rep is our community karma system and is short for Reputation. It's similar to giving likes or upvoting, and is a helpful stat to distinguish top traders, active users, and helpful community members- which is why it's displayed on all trader's dashboards. +Rep can be given for top trades, and soon for content posted or shared.

{% hint style="info" %}
You can only +Rep another trader once per day to prevent trading rep and abuse.
{% endhint %}

#### Badges

PRO/PRO+ icons on dashboards and avatars distinguish subscribed members, you can acquire these by [upgrading your membership.](https://trhub.net/pro)\
\
Badges help traders distinguish themselves from the pack, representing top traders or those with a high win rate. Badges also represent which traders are official analysts or NVSTly staff.

<details>

<summary>List of Badges</summary>

Top Trader - Ranked top 10 on all-time or 30 day leaderboards

High Win Rate - 70% or higher win rate

Tier 1-4 - Measure of a traders length of time and contributions in the Discord server

ELITE Analyst - An official Trade Hub analyst, we back their trades are of quality

Analyst - Prospects for ELITE & guest analysts

Developer - App developer for Trade Hub. You may see bizarre trades, likely for testing.

Staff - Official Trade Hub staff or support team

Founder - Just a back-end permissions & access for administrators

</details>

## Settings

Everything you think that can be set or configured will be found in [Account Settings](https://thetradehub.net/settings), if available. Set your dashboard info, link your social media accounts, manage your account & membership plan, modify notification preferences, etc.

For more info on how to setup and configure the many elements in your Account Settings, see LINK HERE

#### Download Data

You can download all your trade data with performance stats in a .csv or spreadsheet format using this feature.

## Ticker Info

Each stock and cryptocurrency ticker _(futures & forex soon)_ has it's own interactive interface. You will find it's chart, statistical data, analytic graphs, news, latest trades, & more.&#x20;

Ticker Info interfaces can be accessed by clicking on a ticker symbol you see anywhere throughout the app, or by using the search function on the top navbar.

{% hint style="info" %}
Coming Soon:\
Here you can add tickers to your watchlists or set a variety of alerts.
{% endhint %}







{% hint style="success" %}
Stay up to date:\
New features, changes, revisions, and changelogs are posted through our Blog in the Updates category. Here you can stay up to date with the latest app updates or learn what we're working on next.
{% endhint %}
