---
description: >-
  Here you will find information about John-Bot's reminder command system. Learn how it works with its many commands.
---

**Video tutorial related to this page:** [Use John-Bot Reminders on Discord - Tutorial #11](https://jnbt.xyz/tutorials/reminders)

# :rocket: Introduction

If you have a task you must not forget, you can use John-Bot's reminder system. With a simple command executable on any server or in private messages, you can schedule an alert that will be sent as a private message at a specific time.

# :alarm_clock: Managing Reminders

## Create a reminder

To schedule a reminder message, enter the command `/reminder add`. Then, choose from the provided fields the reason (which will be sent back to you at the time of the reminder) and the time that should elapse before the alert is sent. A confirmation message will then be sent to you.

{% hint style="warning" %}
Note that the time that should elapse before the alert is sent cannot be less than one minute or more than 365 days.
{% endhint %}

## Delete a reminder

If you no longer need a previously scheduled reminder, you can easily delete it. Enter the command `/reminder remove` and select the reminder to delete. A confirmation message will then be sent to you.

## List ongoing reminders

To view all your reminders and anticipate them, enter the command `/reminder list`.

# :clipboard: Command List

 Command | Description | Example |
| -------- | ----------- | ------- |
| /reminder add | Sets a reminder. | ![Command /reminder add](../../.gitbook/assets/rappels_command_add.png) |
| /reminder list | Displays the list of all your reminders. | ![Command /reminder list](../../.gitbook/assets/rappels_command_list.png) |
| /reminder remove | Deletes a reminder. | ![Command /reminder remove](../../.gitbook/assets/rappels_command_remove.png) |