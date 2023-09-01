---
description: Set roles to allow access to all setup commands.
---

# Admin Roles

The bot's setup commands will only work for users with server _Administrator_ or roles that have been added to the bot using the _$adminroles_ command. These roles will be allowed access to all available settings commands without being a server admin such as management or staff.

### Add Admin Role

{% hint style="info" %}
**`$adminroles add @role`**
{% endhint %}

To add a role to allow access to the bots setting commands use the command `$adminroles add` and mention the role you would like to add. You can add multiple roles in one command by just spacing them out, or using the command for each role.\
\
If successful, the bot will react with :white\_check\_mark:\
![](<../../.gitbook/assets/image (50).png>)

### Remove Admin Role

{% hint style="info" %}
**`$adminroles remove @role`**
{% endhint %}

To remove a role that was previously added to access the settings commands use the command `$adminroles remove` and mention the role you would like to remove. You can remove multiple roles in one command by just spacing them out, or using the command for each role.\
\
If successful, the bot will react with :white\_check\_mark:\
![](<../../.gitbook/assets/image (59).png>)

### Admin Roles List

You can view all the admin roles that are set by using the command `$adminroles`\
![](<../../.gitbook/assets/image (14) (1).png>)

