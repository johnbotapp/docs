---
description: >-
  Here you'll find information about configuring John-Bot's join and leave system.
---

**Video tutorial related to this page:** [Configure John-Bot's Join and Leave Actions - Tutorial #3](https://jnbt.xyz/tutorials/welcome)

## :rocket: Introduction

John-Bot's join and leave system lets you announce when a member joins or leaves the server, and automatically assign roles to new members upon arrival.

## :tools: Accessing Configuration

### Accessing the Dashboard

First, go to the John-Bot dashboard using your preferred method. Learn how: [How to access the dashboard](../../guide/guide.md#pushpin-access-the-dashboard)

### Accessing Settings

Next, look for `Join & Leave` in the right-hand column, under your server's logo and banner. You'll now be on a page where you can access all settings for the join and leave system.

## :inbox_tray: Join Message

Join messages are automatically sent whenever a new member joins the server. They announce the arrival of a new member and are fully customizable — you can include details like the server's member count, a user mention, and more.

![Example of a join message](../../.gitbook/assets/welcome_message%20d'arrivée_example.png)

### Configuration

#### Sending Channel

In this field, select the channel that will receive join messages using the dropdown menu.

#### Formatting

In this section, you can customize the message that will be sent when a new member joins the server.

{% hint style="info" %}
To add dynamic elements like the server's member count, user mention, and more, you can use variables: [How to use variables](../../ressources/variables.md)
{% endhint %}

**Text Message**

The text message is displayed outside the embed, just like a regular Discord message. You can use emojis and Markdown¹ to style your text. To disable the text message, leave the field blank.

![Example of a join message with the text message highlighted](<../../.gitbook/assets/ticket\_message d'ouverture\_partie texte.png>)

**Embed**

The embed is the part of the message that supports multiple customizable elements and appears below the text message. Regular Discord users can't send embeds — this is a bot-exclusive feature. Use the available fields to customize your embed.

![Example of a join message with the embed highlighted](<../../.gitbook/assets/ticket\_message d'ouverture\_partie embed.png>)

* **Enable Join Embed:** Check this box to enable the embed in your join message. Uncheck it to disable the embed.
* **Embed Author Icon :gem: :** Add an image (can be animated) to your embed's author section — only visible when the author has a name.
* **Embed Author Name :gem: :** Add an author to your embed, with any name you like.
* **Embed Author Link :gem: :** Add a link to an external site on the author.
* **Embed Title:** Add a title to your embed.
* **Embed Description:** Add a description to your embed.
* **Embed Color:** Pick a color for your embed using the color picker.
* **Embed Thumbnail URL:** Add a thumbnail image to your embed.
* **Embed Image URL:** Add an image to your embed.
* **Embed Footer Icon :gem: :** Add a footer image to your embed.
* **Embed Footer Text :gem: :** Add footer text to your embed.

## :outbox_tray: Leave Message

Leave messages are automatically sent whenever a member leaves the server. They announce the departure of a member and are fully customizable — you can include details like the server's member count, the username, and more.

![Example of a leave message](../../.gitbook/assets/welcome_message%20de%20départ_example.png)

### Configuration

#### Sending Channel

In this field, select the channel that will receive leave messages using the dropdown menu.

#### Formatting

In this section, you can customize the message that will be sent when a member leaves the server.

{% hint style="info" %}
To add dynamic elements like the server's member count, user mention, and more, you can use variables: [How to use variables](../../ressources/variables.md)
{% endhint %}

**Text Message**

The text message is displayed outside the embed, just like a regular Discord message. You can use emojis and Markdown¹ to style your text. To disable the text message, leave the field blank.

**Embed**

The embed is the part of the message that supports multiple customizable elements and appears below the text message. Regular Discord users can't send embeds. Use the available fields to customize your embed.

* **Enable Leave Embed:** Check this box to enable the embed in your leave message. Uncheck it to disable the embed.
* **Embed Author Icon :gem: :** Add an image (can be animated) to your embed's author section — only visible when the author has a name.
* **Embed Author Name :gem: :** Add an author to your embed, with any name you like.
* **Embed Author Link :gem: :** Add a link to an external site on the author.
* **Embed Title:** Add a title to your embed.
* **Embed Description:** Add a description to your embed.
* **Embed Color:** Pick a color for your embed using the color picker.
* **Embed Thumbnail URL:** Add a thumbnail image to your embed.
* **Embed Image URL:** Add an image to your embed.
* **Embed Footer Icon :gem: :** Add a footer image to your embed.
* **Embed Footer Text :gem: :** Add footer text to your embed.

## :robot: Autoroles

Autoroles are roles pre-selected by administrators that will be automatically assigned to any new member who joins the server.

### Configuration

To set the roles that will be assigned, select the ones you want using the corresponding dropdown menu.

---
1: Learn about Markdown: [Markdown Text 101 (Chat Formatting: Bold, Italic, Underline)](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline)
