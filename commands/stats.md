---
description: Display a trader's performance stats
---

# Stats

{% hint style="info" %}
`$stats [@user/username] [-t time]`

**and**

`/stats <user> <timeframe>`

_User & time syntax are optional_
{% endhint %}

> `$stats`\
> `$stats`_`@Hubert`_ \
> &#xNAN;_`$stats @Hubert -t 2w`_ \
> &#xNAN;_`$stats Hubert`_

Check your own or another trader's performance stats based on all their closed trades by using the `$stats` or `/stats` command. By default, if no timeframe is specified, the stats displayed are based on the last 30 days.

Stats can be shown for days, weeks, months, and years using `d` `w` `mo` `y` after the timeframe number value.

> $stats @Hubert -t 2w\
> Will show the last two weeks of trading performance stats for the trader Hubert.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption><p>Stats command for trader Ellie displaying past year of statistics</p></figcaption></figure>
