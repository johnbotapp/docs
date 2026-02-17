---
description: >-
  Before you start configuring and customizing John-Bot on your server, here are a few basic tips to get you ready.
---
**Video tutorial related to this page:** [Preparing Your Server for John-Bot Configuration (Prerequisites) - Tutorial #2](https://jnbt.xyz/tutorials/start)

# :clipboard: Verify Permissions
For John-Bot to work properly, it needs certain permissions. We strongly recommend granting it the Administrator permission to avoid any conflicts.
<br/> You likely already assigned these permissions when adding John-Bot, but it's worth double-checking. To do so, go to your Discord server settings, then to the "Roles" tab. Select the John-Bot role, go to its permissions, and make sure the Administrator permission is toggled on.

# :pushpin: Access the Dashboard
To configure John-Bot, you need to access the dashboard.
<br/> Here are the different ways to get there:

## Using the /dashboard command
Go to the Discord server you want to configure and open any text channel. Type the `/dashboard` command and click the `Dashboard` button.
<br/> You'll be redirected to your server's dashboard page. You may need to log in with your Discord account — if so, simply click `Authorize` at the bottom right.

![/dashboard command on a Discord server with John-Bot](../.gitbook/assets/base_command_dashboard.png)

## Via the website
Go to John-Bot's website at: https://johnbot.app/ and click the `Dashboard` button at the top. You may need to log in with your Discord account — if so, simply click `Authorize` at the bottom right. Then, pick the Discord server you want to configure and click on it. You'll be redirected to your server's dashboard page.

## Using the direct URL
You can go directly to your server's dashboard by entering the following URL in your browser: `https://johnbot.app/dashboard/guildId`
<br/> Replace `guildId` with your server's ID¹.

# :flag_gb: Set the Language
Before you start any configuration, we recommend choosing John-Bot's display language.
Find out how: [Change Your Server's Language](../usage/configuration/language.md)

# :gem: Activate John-Bot Premium

John-Bot Premium is the paid version of John-Bot that unlocks additional features to take your Discord server to the next level. Subscribing to a Premium plan also helps cover the costs of running the bot, which is what makes it possible to offer a fully-featured free version of John-Bot to everyone.

{% hint style="info" %}
You can view the full list of Premium benefits compared to the free version at: [https://johnbot.app/premium](https://johnbot.app/premium)
{% endhint %}

## Subscribe to John-Bot Premium

First, head to [https://johnbot.app/premium](https://johnbot.app/premium) and choose the plan that suits you. You'll be redirected to the Patreon payment page, where you'll need to create an account. Follow the steps on Patreon until your subscription is confirmed.

## Link Your Patreon Account

Next, you'll need to link your Patreon account on the John-Bot dashboard. To do this, go to the dashboard of one of your servers and click on your profile picture in the top left corner. Make sure your Patreon account is properly linked.

## Activate John-Bot Premium on a Server

Finally, activate John-Bot Premium on the servers of your choice by running the `/premium` command on each one and confirming the activation. To deactivate John-Bot Premium, run the `/premium` command again and click `reset`.

## Manage or Cancel Your Subscription

To switch plans, go to the [Subscription section on the John-Bot Patreon page](https://www.patreon.com/c/johnbot/membership). You'll see all three available plans and can pick the one that fits your needs.
<br/> To cancel your subscription, go to the [Memberships section in your Patreon settings](https://www.patreon.com/settings/memberships). Expand the additional options and click `Cancel subscription`.

---
1: Find your server's ID: [Where can I find my User/Server/Message ID?](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID)
