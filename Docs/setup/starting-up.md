# Starting Up

### Raiden's Integration role

Once you add Raiden to your server with the proper permissions it asked for, you should actually notice a new **Raiden role** in your server (probably at the bottom of the role list). **You need to move that role and place it at the top**.

{% hint style="warning" %}
This step is required for the bot to function with its Moderation and Security related features.
{% endhint %}

### Mute Role for Raiden

Mute Role or Quarantine Role is a role which has no permissions, throughout the server (from Channel Overwrites). Such role is used to separate malicious users out of the server.&#x20;

In order to Setup a Mute Role for Raiden, run `/muterole @Role`. Bot will setup the Role accordingly throughout the server (only if it has Manage Channel and Role Permission). This role should be kept right under **Raiden's Integration Role**.

{% hint style="warning" %}
This step is required for the bot to function with its Moderation and Security related features.
{% endhint %}

### Be updated about Raiden \[optional]

Sometimes, we release an update which deprecates some older functionality of the bot. We recommend being updated with each and every update of Raiden. This can be done either by joining our Support Server or by getting updates right in your server.

To get updates in your server, run: `/botupdate #Channel`. All the changes will come in the provided channel.
