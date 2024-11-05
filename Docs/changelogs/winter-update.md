---
description: This version offers new Modules and Fixes minute bugs in previous versions
---

# Winter Update

Hey,\
\
We are glad to inform you, Raiden **Winter Build** is now Live. There is new Logo, new Website and 2 new Modules. From now, we will be focusing on small and big things equally.\
\
**New Modules:** We have released **Giveaway and Reaction Role module** to Public Build. Hope you guys enjoy it. Reaction Role supports all kind of Role Selection from Reaction to Menu. Giveaway module is customizable to make your Server look more professional.

## New Giveaway Module

Our very own Giveaway System is here. It is not just limited to host a giveaway and draw a winner. It's far more than of what you can expect from us. Let's dive into depth of the Giveaway System.

### Starting, Ending, Re-Rolling and Dropping

* Use `/giveaway start` to start a very customized giveaway, with as many entries that you could imagine. You can add multipliers and requirements to match your use case.
* Use `/giveaway end` to end a giveaway. This requires a giveaway ID. Giveaway ID is same as the Message ID of the Giveaway Message \[the one with Enter Button].
* Use `/giveaway reroll` to reroll winners of a giveaway.
* Use `/giveaway drop` to drop a quick giveaway.

{% hint style="info" %}
Starting Giveaway either from `/giveaway start` or `/giveaway drop`takes effect of all Giveaway Configurations.
{% endhint %}

### Giveaway Configs

You can set default configurations for the giveaway. Configurations can be managed by running `/giveaway config`. You can configure following things:

* Giveaway Manager Roles
* Giveaway Emoji on Buttons and Messages
* Color of Giveaway Embed
* Winner Role
* Ping Role
* Giveaway Message
* Banner

&#x20;                                               ![](<../.gitbook/assets/image (8).png>)

### Different Requirements

Giveaway Module supports many different types of requirements such as:

* Giveaway Entry Limit
* Required Role
* OG Member Age
* Discord Account Age
* Blacklisting Roles

### At the End of Giveaway Module

Here's a picture of giveaway running in our Support Server:\
&#x20;                                               ![](<../.gitbook/assets/image (18).png>)

## Advanced Reaction Role System

Reaction role system supports each type of reaction role/pick up role available on Discord. This system has the following reaction role types in one place:

* Reaction Based Reaction Roles
* Button Based Reaction Roles
* Select Menu Based Reaction Roles

Reaction roles has different type of working. You will be prompted to ask for the type of the reaction role while creation. These types are as follows:

* Normal
* Pick
* Drop
* Bind
* Limit
* Unique

{% hint style="info" %}
Creation of a reaction role is very simple, as you press the **Create** button, Bot will start asking you for entries and information. As you complete each step in it, reaction role will be ready for use.
{% endhint %}

## Auto Ban System

* Auto Bans those leaving members who are having certain roles.
* Comes in two modes, i.e. _Any Role_ and _All Role_. One checks for any one role, and other checks for all provided roles before banning.
* Panel Interface, and Logs are integrated with Moderation Logs.

### Bug Fixes

* New Servers are getting Infinite Loading time
* Ai chat will now try to answer questions from its past 1min memory. It is made more stable than before
* Fixed a bug for new Server, who directly uses Ticket Module
* Components of `/tickets` will now get disabled in case of inactivity.
* Fixed messy logs of Message Edit
* Ai Chat has been removed from bot's DM
* Access Handler is now implemented.
* Can use same/different panels at once in a channel without any clashes
* **Ban Command Fix:** Issue with Ban Command has been resolved
* **Timeout Command Fix:** Same Issue with timeout has been resolved.
* **Warn Command:** Warn count was not increasing has been fixed.
* **Logs:** Channels with follower webhooks, were not having Logs, fixed.
* **Embed Editor:** Use of Application Webhook denies the req, fixed.

### Anything else?

* I am glad to launch **Bug Hunter Program** for Raiden. If you encounter any bug or malfunction in the bot. Kindly report it and help us improve our service. \
  \
  I know some people just Kick the bot from there server, cz they just encountered a bug. I want to make this clear, any bug, you encounter gets logged with me. I fix most of them in 24h of there occurrence. \
  \
  **Bug Hunter Program** is here to encourage you to report the problems, you are facing with the Bot and most importantly give us a chance to improve.
* **Special thanks to the Bug Hunters and our beta testers for their lovely help.**
* Currently, we will be focusing on to Build the bot, so we can shard it up. Some UI changes will come into play, without such changelogs.
* After this ^, we will start the work on **v4.5**. No more wait now ;)
