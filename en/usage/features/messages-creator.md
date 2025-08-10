---
description: >-
  Learn everything you need to know about John-Bot's message creator system. Learn how to set it up and understand how it works.
---

**Video tutorial related to this page:** [Create and Send an Editable Embed on Discord - Tutorial #10](https://jnbt.xyz/tutorials/embeds)

## :rocket: Introduction

The message creator system allows you to send messages on behalf of John-Bot. These messages can be modified later and enhanced with various options that are not directly available in the Discord application for a regular user.

## :tools: Accessing the Message Creator

To start, access the John-Bot dashboard using your preferred method. To learn how to do this, refer to this guide: [How to access the dashboard](../../guide/guide.md#pushpin-access-the-dashboard).

Next, look for the `Messages` option in the right column, located under your server's logo and banner. You will then arrive on a page where you can access all the necessary settings to create your first message.

## :pencil: Message Settings

### Creating a Message

To create a new message, use the button at the bottom of the list of existing messages, or at the top of the page if it's your first one.

### Duplicating an Embed

You can also create a message from an existing one to keep the same settings and customize it by duplicating it (also known as "copy-paste"). This saves you from having to reconfigure all the settings for a minor difference between the two messages. To do this, simply click on the `Duplicate` button corresponding to the desired embed and confirm your choice via the window that appears.

### Modifying a Message

To adjust the settings of an existing message, simply click on the `Modify` button associated with the message of your choice in the list. You will then directly access the settings of the selected message to make your modifications.

### Deleting a Message

To delete an existing message, simply click on the `Delete` button corresponding to the desired message and confirm your choice via the window that appears.

### Modifying a Message

Once in the settings of a message, you can modify many options to customize it according to your needs.

Once the configurations are completed, simply click on the green `Save & Modify` button located at the top right of the configuration window. If you do not wish to keep your modifications, simply click on `Cancel`.

### Saving and Sending an Embed

Once your modifications are completed, if your message has never been sent, you must create the corresponding embed in the predefined channel. To do this, use the green `Create` button located at the top right. You will then need to send it to the predefined channel using the `Send` button.

### Message Configuration

#### Message Name

The message name allows server administrators to organize themselves in the John-Bot dashboard. It will not be visible to members. To define it, write it in the corresponding field.

#### Sending Channel

The sending channel is the server channel in which the message will be sent. To define it, choose the desired channel using the corresponding selection menu.

#### Sending Type

You have the choice as to how your message will be sent. Simply select the option that best suits your needs:

- **Single-send message:** This message will only be sent once and will gradually be buried among the other messages in the channel.

- **Persistent message:** Each time a new message is posted in the channel, John-Bot will resend your message so that it always remains visible and is the last one in the channel. If the message has already been sent before, only the most recent version will be kept to avoid saturating the channel.

#### Text Message

The text message is the text that will be displayed outside the embed, like a regular Discord user. You can use emojis and markdown¹ to customize your text. To disable the text message, leave the field blank.

![Example of a message with the text message highlighted](../../.gitbook/assets/embed_message_partie%20texte.png)

#### Embed

The embed is the part of the message that can include several customizable elements and will be displayed under the text message. It is impossible to send for a regular Discord user. You can use the available fields to customize your embed.

![Example of a message with the embed highlighted](../../.gitbook/assets/embed_message_partie%20embed.png)

- **Embed author icon:** You can illustrate your embed by adding an image (which can be animated) to your author, only visible when the author has a name.

- **Embed author name:** You can customize your embed by adding an author, which you can name as you wish.

- **Embed author link:** You can customize your embed by adding a link to an external site to the author.

- **Embed title:** You can customize your embed by adding a title.

- **Embed description:** You can customize your embed by adding a description.

- **Embed color:** You can choose a color to customize your embed using the selector.

- **Embed thumbnail link:** You can illustrate your embed by adding a thumbnail.

- **Embed image link:** You can illustrate your embed by adding an image.

- **Embed footer icon:** You can complete your embed with a footer image.

- **Embed footer text:** You can complete your embed with the footer.

---

1: Discover what Markdown is: [Text Markdown 101 (Chat formatting: bold, italic, underline)](https://support.discord.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline)