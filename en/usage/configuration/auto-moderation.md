---
description: >-
  Learn how to set up John-Bot's auto-moderation system here!
---

# Auto-Moderation

**Video tutorial related to this page:** [Effectively Moderate Your Server with John-Bot - Tutorial #5](https://jnbt.xyz/tutorials/moderation)

### :rocket: Introduction

An auto-moderation system on Discord is an essential tool for maintaining a healthy and secure environment without requiring constant human oversight. It lets you define precise rules that John-Bot will automatically enforce based on detected behavior on the server.

John-Bot's auto-moderation system is built around three main categories: automatic sanctions, reports, and moderation logs.

You can also customize many settings to tailor the system to your needs: choice of sanctions, detection thresholds (e.g., number of repeated messages within a time window), ignored channels, and the presentation of reports and logs.

### :tools: Accessing the System Settings

First, go to the John-Bot dashboard using your preferred method. Learn how: [How to access the dashboard](../../guide/guide.md#pushpin-access-the-dashboard).

Next, look for `Moderation` in the right-hand column, under your server's logo and banner. You'll now be on a page where you can access all settings related to the auto-moderation system.

### :hammer: Automatic Sanctions

To create your first automatic sanction, you need to define its parameters. When a member accumulates a certain number of warnings, John-Bot will automatically apply the configured sanction against them.

#### Choosing the Sanction

First, choose a sanction that John-Bot will automatically apply when a member reaches a certain warning threshold. Select the one you want from the list and, if applicable, set a duration.

A sanction can take several forms, some requiring a duration. Here is the full list of sanctions John-Bot can apply:

* Warn: the member receives a DM informing them of the warning. John-Bot keeps a record of it, accessible via the `/warnings list` command or in the logs.

* Mute (Timeout): the member is fully silenced on the server for a set duration (up to 28 consecutive days). They won't be able to send messages, join voice channels, react, or interact in any way. However, they can still read server messages.

* Kick: the member is removed from the server, but not permanently. They can rejoin at any time if they have an invite or if the server is public.

* Ban: the member is permanently removed from the server and cannot rejoin unless a moderator lifts the ban using the `/unban` command.

* Temporary ban: same as a ban, but time-limited. After a set duration (up to 365 consecutive days), the user can rejoin the server if they have an invite or the server is public.

#### Setting the Conditions

For the selected sanction to be triggered, a member must have accumulated a certain number of warnings — whether applied automatically by John-Bot or manually by moderators.

You can define the number of warnings required within a given time period to trigger the automatic sanction.

### 🚨 Reports

The reporting system allows members to flag bad behavior that moderators might miss.

It's very difficult for moderators to be present in every channel at the same time, or even in DMs. This system lets members report issues themselves.

When a member notices bad behavior, they can click the three dots on a message, select the "Apps" category, and choose the "Report Message" option. John-Bot will then ask for the reason of the report. The moderators will receive this report in a pre-defined channel showing who made the report and who was reported.

Moderators have several options: they can claim the report (signaling to other moderators that they're handling it), view the message context, or resolve the report. When resolving, the bot will offer several action options.

### Ignored Channels

Any activity in ignored channels won't be logged, regardless of the event type. To set one or more ignored channels, select them from the list in the corresponding field.

### Global Color :gem:

This option lets you set the color of the log embeds sent to your server. Choose from the 6 preset colors or use the color picker.

### Specialized Channels

For each event type in the system, you can assign a dedicated channel. Select the event you want and assign a channel using the corresponding dropdown menu.

{% hint style="warning" %}
If the global log channel is set to the same channel as one or more specific events, log messages will be sent twice.
{% endhint %}
