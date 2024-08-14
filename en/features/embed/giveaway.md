---
description: >-
  Here you will find information about creating and configuring giveaways or
  contests.
---

# Copy of Giveaway

**Video tutorial linked to this page:** [Organize a giveaway on your server with John-Bot - Tutorial #8](https://youtu.be/UsfRXtH8Rcg)

## :rocket: Introduction

A giveaway is the perfect way to reward your members by putting a prize at stake and letting chance decide. Indeed, a giveaway is simply a contest in the form of a lottery. Participants can enter via a simple button, and the drawing is conducted at the chosen time.

There are two ways to create a giveaway: one is quick but less customizable, while the other is more customizable but requires more time and precision. Choose the one that suits you best by comparing them, and learn how to set them up.\
Also, discover how to interact with a giveaway to participate, as well as the commands for managing a giveaway.

## :zap: Quick and Simple Method

If you want to create a giveaway quickly and efficiently, opt for this method.

First, access the server where you want to launch the giveaway. Make sure you have administrator permission.\
Then, enter the command /giveaway create. You will have access to several options:

* You need to choose the duration of the giveaway, i.e., the amount of time that will elapse before the automatic drawing and announcement of the results.\
  To do this, enter the number of second·s, minute·s, hour·s, or day·s, followed by the unit (`s` for second, `min` for minute, `h` for hour, and `d` for day).
* You need to choose the number of winners who will be selected to receive the prize at stake. Simply enter an integer greater than 0.
* You need to choose the prize you want to put up for grabs. The field is completely free; simply enter the name of the prize, whether it is physical, virtual, or otherwise.
* Finally, you can choose the channel in which the giveaway will take place if it differs from the channel in which you are entering the command to set up the giveaway. This option is optional; if left blank, the giveaway will be launched directly in the channel where the command was sent.

![Example of a configuration with the /giveaway create command](../../.gitbook/assets/giveaway\_command\_create.png)

## :tools: More Comprehensive and Customizable Method

If you want to create a complex and detailed giveaway by integrating original elements, opt for this method.

### Accessing the Dashboard

First, go to John-Bot's dashboard using the method of your choice. Learn how to do this: [How to access the dashboard](../../guide/base.md#pushpin-accessing-the-dashboard)

### Accessing Settings

Next, look for `Giveaways` in the right column, under your server's logo and banner. You will now be on a page where you can view all the giveaways on your server, whether they are finished or ongoing.

### Creating and Configuring

You arrive at the page where you can configure your giveaway. Here's how to configure the different settings:

#### Name

In this field, choose the name that can define your giveaway. It will be displayed in the title of the sent message as well as on the dashboard to be able to spot it among the others.

#### Sending Channel

In this field, choose where the giveaway will be sent and visible to members. After sending the giveaway, you will not be able to change the channel.

#### Reward

In this field, choose the prize you want to put up for grabs. The field is completely free; simply enter the name of the prize, whether it is physical, virtual, or otherwise. It is not possible to automate the distribution of the prize; you will have to handle it manually.

#### End Date

This field allows you to set the exact date and time of the drawing. On this date, a message will be automatically sent in response to the original giveaway message to announce the winner(s).

#### Number of Winners

In this field, define how many members can be declared winners of the prize at stake.

#### Maximum Number of Participants :gem:

In this field, you can choose to limit the number of members who can enter the drawing.

#### Display of Participant List

You can disable the display of the participant list by unchecking the associated box.

{% hint style="info" %}
Find out how this button works in the [direct interaction with the giveaway](giveaway.md#direct-interaction-with-the-giveaway) section.
{% endhint %}

#### Allowed & Ignored Roles

In these two fields, you can restrict the giveaway to certain roles or, conversely, disallow certain roles from participating in the giveaway.\
To do this, select the desired roles from the corresponding dropdown menu.

#### Embed

The `embed` section allows you to format the message that will be sent and visible to the member in the channel.\
You can customize it as you like using the many options provided.

#### Button :gem:

The `button` section allows you to customize the button that will be attached to the giveaway message and allows members to participate in the giveaway.\
You can customize it as you like using the many options provided, such as color, displayed text, or displayed emoji.

### Finalize and Send

Once your giveaway is fully configured, check that everything is correct and click on the green button located at the top left, `Create & Send`. Your giveaway will be sent and started in the specified channel with all its customizations. It is advisable to write an announcement message to inform your members if the giveaway is organized in honor of an important event.

## :gear: Giveaway Operation

### Giveaway Information

In the embed message, you will find some information about the giveaway. Here are explanations for each piece of information available on the message.

* **Name or Title** : You can find the giveaway name in the embed title (bold and titled upper part).
* **End Date and Time** : You can find the remaining time as well as the date and time at which the giveaway will end. The corresponding field is `Ends:`, located below the title in the embed body. The field is renamed `Ended` once the giveaway is over.
* **Giveaway Author** : You can find out the user who initiated the giveaway. Their Discord account is directly identified in the `Launched by:` field.
* **Number of Participants** : You can know the number of members who are registered for the drawing in the `Participants:` field.
* **Number of Winners or Winner(s)** : You can know the number of members who will be declared winners of the prize after the drawing in the `Winners:` field. This field then displays the winner(s) by mention.

### Direct Interaction with the Giveaway

#### Participate Button

You can enter the drawing with the customizable button by the giveaway author located under the giveaway embed, to the left of the `Participants` button.

#### Participants Button

You can view the list of people entered into the drawing by clicking the `Participants` button located under the giveaway embed, to the right of the participation button.

{% hint style="info" %}
Find out how to configure this button in the [create and configure](giveaway.md#create-and-configure) section of this page.
{% endhint %}

!\[Example of a typical giveaway message]\(../../.gitbook

/assets/giveaway\_example.png)

### Commands

| Command          | Description                                   |
| ---------------- | --------------------------------------------- |
| /giveaway create | Starts a giveaway.                            |
| /giveaway delete | Deletes a giveaway.                           |
| /giveaway end    | Ends a giveaway.                              |
| /giveaway list   | Displays the list of giveaways on the server. |
| /giveaway reroll | Chooses new winners for a giveaway.           |
