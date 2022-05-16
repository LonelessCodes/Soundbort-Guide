---
description: How do I change modification access of my server's soundboard?
---

# Server Guide

### Setting permissions

By default, the actions (_commands or buttons_) to add or remove samples from the server soundboard, or to use the `/config` command, can only be used by **members with the Administrator permissions**.

To set your own permissions for these, Discord now has a way for server admins to set permissions for a command themselves with finer control over who can use what commands where.

{% hint style="info" %}
Permissions to alter the server soundboard will be based on the permissions you set for the `/config` command. This means you only need to set permissions in one place and they will apply to all administrative actions within Soundbort by default.
{% endhint %}

**This is how you do it:**

{% embed url="https://cdn.discordapp.com/attachments/970611601407361054/970611714116681758/Soundbort_Config_Permissions0001-0736.mp4" %}
A video showcasing how to set permissions for the /config command
{% endembed %}

{% hint style="info" %}
To change any permissions users must have the **"Manage Server" permission**!

To **allow/disallow a role** for a specific command, the user must have the permissions to manage the role they want to allow/disallow.

To **restrict a command to a specific channel(s)** the user must have the permissions to manage the channel they want to restrict.
{% endhint %}

That's it, you've now disallowed any non-moderator modification of the server's soundboard. :tada:&#x20;

### Adding samples to your server soundboard

By default `/upload` always adds samples to your personal soundboard. To add samples to your server soundboard type `/upload name:the sample name [TAB] to:` and choose "_Upload into server soundboard for every member to use._".

![Add samples to your server soundboard.](<../.gitbook/assets/grafik (27).png>)

Everything else stays the same. You just need to add the `to: server` to your command.

{% hint style="info" %}
You can only add samples to your server soundboard if you have permissions to use the `/config` command!
{% endhint %}

### Removing samples from your server's soundboard

This is exactly the same as in [First Steps](first-steps.md#removing-samples-from-your-soundboard). If you execute the command and you have the permissions for the server soundboard, the command will be deleted permanently.

![Delete command with a sample name suggestion for a server sample.](<../.gitbook/assets/grafik (25).png>)

If the sample exists in both your user and server soundboard it will just ask you where you want to delete it from.

![Delete command choice wether to delete the sample from the user or server soundboard.](<../.gitbook/assets/grafik (26).png>)

{% hint style="info" %}
You can only remove samples from your server soundboard with the previously [set permissions](server-guide.md#setting-permissions) for the `/config` command.
{% endhint %}

### Showing a list of all server samples

To make Soundbort only show the server soundboard, type `/list from` and choose "_Output this server's soundboard only._".

![Command for showing only the server soundboard.](<../.gitbook/assets/grafik (23).png>)

### Additional tips

#### Channel with all server samples

If you have a bigger community I recommend setting up a channel for the list of server samples, or pinning the response to a bot channel. This way users can quickly find and play the samples.

![Setup of a channel which shows the server's soundboard.](<../.gitbook/assets/grafik (6).png>)

#### Bot command channel

Discord allows commands to be restricted to specific channels only. The commands will not be available in other channels. It's great to keep other channels from being cluttered with commands.

Like in [Setting Permissions](server-guide.md#setting-permissions), go to Server Settings -> Integrations -> Soundbort and set it up something like this:

![Setup of permissions that only allows commands in #bot-spam](<../.gitbook/assets/grafik (22).png>)
