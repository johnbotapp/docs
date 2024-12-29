---
description: >-
  Here, you will find information about John-Bot's join and leave system configuration.
---

**Video tutorial related to this page:** [Configure John-Bot's Join and Leave Actions - Tutorial #3](https://jnbt.xyz/tutorials/welcome)

## :rocket: Introduction
John-Bot's join and leave system announces when a member joins or leaves the server and automatically assigns certain roles upon arrival.

## :tools: Accessing Configuration

### Accessing the Dashboard

First, go to John-Bot's dashboard using your preferred method. Find out how: [How to Access the Dashboard](../../guide/base.md#pushpin-access-the-dashboard)

### Accessing Settings

Next, look for `Join and Leave` in the right column, under your server's logo and banner. You will now arrive on a page where you can access all settings related to the join and leave system.

## :inbox_tray: Join Message

Join messages are messages that will be automatically sent when a new member joins the server. They announce the arrival of a new member and are fully customizable to include details such as the number of members on the server, user mention, and more.

![Example of a join message](../../.gitbook/assets/welcome_message%20d'arrivée_example.png)

### Configuration

#### Sending Channel

In this field, select the channel that will receive the join messages using the associated dropdown menu.

#### Formatting

In this category, you can customize the message that will be sent when a new user joins the server.

{% hint style="info" %}
To add dynamic elements such as the number of members on the server, user mention, and more, you can use variables: [How to Use Variables](../../ressources/variables.md)
{% endhint %}

**Text Message**

The text message is the message that will be displayed outside of the embed, like a regular Discord user. You can use emojis and Markdown¹ to customize your text. To disable the text message, leave the field blank.

![Example of a join message with text message highlighted](<../../.gitbook/assets/ticket\_message d'ouverture\_partie texte.png>)

**Embed**

The embed is the part of the message that can contain multiple customizable elements and will be displayed below the text message. It cannot be sent by a regular Discord user. You can use the available fields to customize your embed.

![Example of a join message with embed highlighted](<../../.gitbook/assets/ticket\_message d'ouverture\_partie embed.png>)

* **Enable Join Embed:** Check this box if you want to enable the embed in your join message. Uncheck this box if you want to disable the embed.
* **Embed Author Icon :gem: :** You can illustrate your embed by adding an image (which can be animated) to your author, visible only when the author has a name.
* **Embed Author Name :gem: :** You can customize your embed by adding an author, which you can name as you like.
* **Embed Author Link :gem: :** You can customize your embed by adding a link to an external site for the author.
* **Embed Title:** You can customize your embed by adding a title.
* **Embed Description:** You can customize your embed by adding a description.
* **Embed Color:** You can choose a color to customize your embed using the color selector.
* **Embed Thumbnail Link :** You can illustrate your embed by adding a thumbnail.
* **Embed Image Link:** You can illustrate your embed by adding an image.
* **Embed Footer Icon :gem: :** You can complete your embed with a footer image.
* **Embed Footer Text :gem: :** You can complete your embed with a footer text.

## :outbox_tray: Leave Message

Leave messages are messages that will be automatically sent when a member leaves the server. They announce the departure of a member and are fully customizable to include details such as the number of members on the server, user mention, and more.

![Example of a leave message](../../.gitbook/assets/welcome_message%20de%20départ_example.png)

### Configuration

#### Sending Channel

In this field, select the channel that will receive the leave messages using the associated dropdown menu.

#### Formatting

In this category, you can customize the message that will be sent when a member leaves the server.

{% hint style="info" %}
To add dynamic elements such as the number of members on the server, user mention, and more, you can use variables: [How to Use Variables](../../ressources/variables.md)
{% endhint %}

**Text Message**

The text message is the message that will be displayed outside of the embed, like a regular Discord user. You can use emojis and Markdown¹ to customize your text. To disable the text message, leave the field blank.

**Embed**

The embed is the part of the message that can contain multiple customizable elements and will be displayed below the text message. It cannot be sent by a regular Discord user. You can use the available fields to customize your embed.

* **Enable Leave Embed:** Check this box if you want to enable the embed in your leave message. Uncheck this box if you want to disable the embed.
* **Embed Author Icon :gem: :** You can illustrate your embed by adding an image (which can be animated) to your author, visible only when the author has a name.
* **Embed Author Name :gem: :** You can customize your embed by adding an author, which you can name as you like.
* **Embed Author Link :gem: :** You can customize your embed by adding a link to an external site for the author.
* **Embed Title:** You can customize your embed by adding a title.
* **Embed Description:** You can customize your embed by adding a description.
* **Embed Color:** You can choose a color to customize your embed using the color selector.
* **Embed Thumbnail Link :** You can illustrate your embed by adding a thumbnail.
* **Embed Image Link:** You can illustrate your embed by adding an image.
* **Embed Footer Icon :gem: :** You can complete your embed with a footer image.
* **Embed Footer Text :gem: :** You can complete your embed with a footer text.

## :robot: Autorole

Autoroles are roles pre-selected by administrators that will be instantly assigned to a new member who joins the server.

### Configuration

To set the roles that will be assigned, choose the ones you want using the corresponding dropdown menu.

---
1 : Discover what Markdown is: [Text Markdown 101 (Chat Formatting: Bold, Italics, Underline)](https://support.discord.com/hc/fr/articles/210298617-Markdown-de-Texte-101-Formatage-du-chat-gras-italique-soulign%C3%A9)