---
description: >-
  The bot listens for 4 triggers when submitting trades for open/close &
  long/short
---

# Triggers

#### Long positions

* **`BTO`** - Buy to Open
* **`STC`** - Sell to Close

#### Short positions

* **`STO`** - Sell to Open
* **`BTC`** - Buy to Close

{% hint style="info" %}
**Triggers & tickers are not case sensitive.**&#x20;
{% endhint %}

## Trigger Aliases

These work just as triggers do and are used at start of input.

{% tabs %}
{% tab title="Open (Long/Short)" %}
Open _(long)_ / Open Long / Open Short\
Opening _(long)_ / Opening Long / Opening Short\
Long / Going Long\
Short / Shorting / Going Short\
Buy / Buying / Bought - _Note: As of now, these are long or BTO. Not closing short._\

{% endtab %}

{% tab title="Close (Long/Short)" %}
Close / Closing\
Sell / Selling / Sold - _Note: As of now, these are closing long or STC. Not opening short._&#x20;

Cut / Cutting - _Note: Not to be mistaken with trim/partial._&#x20;
{% endtab %}
{% endtabs %}
