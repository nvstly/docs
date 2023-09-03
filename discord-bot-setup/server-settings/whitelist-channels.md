---
description: >-
  By default the bot works in any channel it has required permissions unless a
  channel whitelist has been created.
---

# Whitelist Channels

Setting a whitelist of channels is recommended as it will not allow users to submit trades in channels not designated for submitting them, but all other commands will still function in non-whitelisted channels.\
\
If a whitelist has not been set, when the bot is used in a channel that it doesn't have the required permissions in, it will reply or send a DM to that user with a permissions checklist noting which perms are missing.

### Add Channels To Whitelist

{% hint style="info" %}
**`$whitelist add #channel`**
{% endhint %}

To add a channel to the whitelist use the command `$whitelist add` and specify the channel to add. You can add multiple channels to the whitelist in one command by spacing out each channel.\
\
If successful, the bot will react with :white\_check\_mark:\
![](<../../.gitbook/assets/image (33).png>)

### Remove Channels From Whitelist

{% hint style="info" %}
**`$whitelist remove #channel`**
{% endhint %}

To remove a channel from the whitelist use the command `$whitelist remove` and specify the channel to remove. You can remove multiple channels from the whitelist in one command by spacing out each channel.\
\
If successful, the bot will react with :white\_check\_mark:\
![](<../../.gitbook/assets/image (98).png>)

### List Whitelisted Channels

You can view all the whitelisted channels by using the command `$whitelist`![](<../../.gitbook/assets/image (30).png>)



{% hint style="info" %}
Use `$whitelist clear` to clear all channels from a whitelist
{% endhint %}
