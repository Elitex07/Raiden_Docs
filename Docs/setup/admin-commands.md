# Admin Commands

### Lock Channels - /lock

You can permanently/temporary lock a channel. Best part here is Raiden only allows Administrators to speak in a locked channel, don't worry about the channel permission, it gets restored when you unlock the channel or when specified time ends.

Required Permissions: Manage Channels and Manage Roles

{% hint style="danger" %}
Discord has a weird way of managing an overwrite permission. i.e., "Manage Permission". If bot is unable to lock a channel, then probably you are required to look into the channel overwrite permissions.
{% endhint %}

#### Permanent Lock - /lock permanent

To lock the channel permanently, simply execute `/lock permanent`. This command will permanently lock the channel. Hence, no one (expect Administrators) will be allowed to talk in the channel.

Raiden removes permissions from all roles inside Advanced channel permissions. Do not worry about the permissions, whenever you unlock the channel in future, bot will restore the permissions for you.

#### Temporary Lock - /lock temporary

To Lock the channel temporary, simply execute `/lock temporary`. This command will temporarily lock the channel. Hence, no one (expect Administrators) will be allowed to talk in the channel for the specified duration.

Raiden removes permissions from all roles inside Advanced channel permissions. Do not worry about the permissions, whenever you or the bot itself unlock the channel in future, bot will restore the permissions for you.

#### Unlocking a Channel

This command will also restore all the permissions which were present before the channel was locked. You cannot unlock a channel with Raiden which has been locked by other bots.

To unlock the channel, simply execute `/unlock`&#x20;
