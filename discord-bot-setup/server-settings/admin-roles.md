---
description: Set admin roles that allow access to all setup commands.
---

# Admin Roles

The bot's setup commands will only work for users with server _Administrator_ or roles that have been added to the bot using the `$adminroles` command. These roles will be allowed access to all available setup commands without being a server admin such as for management or staff.

### Add Admin Role

{% hint style="info" %}
**`$adminroles add @role`**
{% endhint %}

To add a role that gives access to the bot's setup commands use the command `$adminroles add <@role>` and mention the role you would like to add. You can add multiple roles in one command by just spacing out each role.\
\
If successful, the bot will react with :white\_check\_mark:\
![](<../../.gitbook/assets/image (50).png>)

### Remove Admin Role

{% hint style="info" %}
**`$adminroles remove @role`**
{% endhint %}

To remove a role, use the command `$adminroles remove` and mention the role you would like to remove. You can remove multiple roles in one command by just spacing out each role.\
\
If successful, the bot will react with :white\_check\_mark:\
![](<../../.gitbook/assets/image (59).png>)

### Admin Roles List

To view a list of all admin roles, use the command `$adminroles` without any syntax.\
![](<../../.gitbook/assets/image (14) (1).png>)



{% hint style="info" %}
The /slash command version of `$adminroles` is `/adminperms`
{% endhint %}

