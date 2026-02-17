---
description: >-
  Learn everything you need to know about John-Bot's message creator system. Learn how to set it up and understand how it works.
---

# Message Creator

**Video tutorial related to this page:** [Create and Send a Custom Embed on Discord - Tutorial #10](https://jnbt.xyz/tutorials/embeds)

### :rocket: Introduction

The message creator system lets you send messages on behalf of John-Bot. These messages can be edited later and enhanced with various options that are not available to regular users directly through the Discord app.

### :tools: Accessing the Message Creator

First, go to the John-Bot dashboard using your preferred method. Learn how: [How to access the dashboard](../../guide/guide.md#pushpin-access-the-dashboard)

Then, look for `Messages` in the right-hand column, under your server's logo and banner. You'll land on a page where you can access all the settings needed to create your first message.

### :pencil: Message Settings

#### Creating a Message

To create a new message, use the button at the bottom of the existing message list, or at the top of the page if it's your first one.

#### Duplicating an Embed

You can also create a message from an existing one to keep the same settings and customize it by duplicating it (also known as "copy-pasting"). This saves you from having to reconfigure every setting for a minor difference between two messages. Simply click the `Duplicate` button next to the desired embed and confirm your choice in the popup window.

#### Editing a Message

To adjust the settings of an existing message, simply click the `Edit` button next to the message of your choice in the list. You'll go straight to the selected message's settings to make your changes.

#### Deleting a Message

To delete an existing message, simply click the `Delete` button next to the desired message and confirm your choice in the popup window.

#### Saving Changes

Once in a message's settings, you can modify many options to customize it to your needs.

When you're done configuring, click the green `Save & Edit` button at the top right of the configuration window. If you don't want to keep your changes, simply click `Cancel`.

#### Saving and Sending an Embed

Once your edits are done, if your message has never been sent, you need to create the corresponding embed in the predefined channel. To do so, use the green `Create` button at the top right. You'll then need to send it to the predefined channel using the `Send` button.

#### Message Configuration

**Message Name**

The message name helps server administrators stay organized on the John-Bot dashboard. It won't be visible to members. To set it, type it in the corresponding field.

**Sending Channel**

The sending channel is the server channel where the message will be posted. To set it, choose the desired channel from the corresponding dropdown.

**Sending Type**

You can choose how your message will be sent. Simply select the option that best suits your needs:

* **Single-send message:** This message will only be sent once and will gradually get buried among other messages in the channel.
* **Persistent message:** Every time a new message is posted in the channel, John-Bot will re-send your message so it always stays visible and remains the last message in the channel. If the message was previously sent, only the most recent version will be kept to avoid flooding the channel.

**Text Message**

The text message is the text displayed outside the embed, like a regular Discord user's message. You can use emojis and markdown¹ to customize your text. To disable the text message, leave the field empty.

![Example message with the text portion highlighted](<../../.gitbook/assets/embed_message_partie texte.png>)

**Embed**

The embed is the part of the message that can contain several customizable elements, displayed below the text message. It's impossible to send as a regular Discord user. You can use the available fields to customize your embed.

![Example message with the embed portion highlighted](<../../.gitbook/assets/embed_message_partie embed.png>)

* **Embed author icon:** Illustrate your embed by adding an image (which can be animated) to your author, only visible when the author has a name.
* **Embed author name:** Customize your embed by adding an author, which you can name as you wish.
* **Embed author link:** Customize your embed by adding a link to an external website for the author.
* **Embed title:** Customize your embed by adding a title.
* **Embed description:** Customize your embed by adding a description.
* **Embed color:** Choose a color to customize your embed using the color picker.
* **Embed thumbnail link:** Illustrate your embed by adding a thumbnail image.
* **Embed image link:** Illustrate your embed by adding an image.
* **Embed footer icon:** Complete your embed with a footer image.
* **Embed footer text:** Complete your embed with footer text.

***

1: Learn more about Markdown: [Markdown Text 101 (Chat Formatting: Bold, Italic, Underline)](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline)
