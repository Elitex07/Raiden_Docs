# Auto Moderation

### Antispam

Antispam is a great way to avoid spammers in your server. We allow you to customize the bot strictness over spams. It's totally your choice whether to keep it too strict or too easy going. Antispam module has its own whitelisting roles and channels aka more customization for your customized needs.

To setup or customize antispam in your server, you just need to run `/antispam` command once. We are not going to make you to run several commands in order to setup a simple module.

### Antilink

Antilink is great way to avoid spammy links in your server. We allow you to customize the bot strictness over links. You can also whitelist/blacklist some specific domain ('youtube.com' is the domain for the website 'https://youtube.com/\<anything>'), its all upon you. Antilink module has its own whitelisting roles and channels aka more customization for your customized needs.\
\
Note: Anti-link will not trigger on the links ending with .gif, .png, .jpeg, .jpg, .mp4 or other media extensions.

### AntiBadWords

Antibadword is great way to keep cursing out of your friendly community. We allow you to add your own custom banned words. Bot take care of Wildcard and Exact words. AntiBadWords module has its own whitelisting roles and channels aka more customization for your customized needs.

Bot take cares of the usage of bad words in any other language. Bot is powered by Google Translator to provide each possible translation in any language around the globe.

### Get Started with Modules

When you run the any modular command, Raiden returns you an Embedded interface to interact with. Have a look at the Embed first, it has all the information about the current settings, of the module, in your server.

&#x20;                                                 ![](<../.gitbook/assets/image (9).png>)

At last, there is a menu of different options to configure the module, which includes options from Enable/Disable to Adding Ignored roles.

&#x20;               ![](<../.gitbook/assets/image (24).png>)![](<../.gitbook/assets/image (4).png>)

{% hint style="success" %}
As you interact with the options, the values in Embed will start changing according to the option and setting chosen. You can go through your settings \[after each change] without running the command multiple times.
{% endhint %}

### Setup

To setup auto moderation in your server, just go through these steps:

* **Enable/Disable any Module**\
  It's the easiest step, just choose the Enable/Disable option from the menu, and the Module will be enabled. Cross check the module **Status** from the embed.\

* **Configure Suitable Punishment**\
  Once you choose the Configure Punishment option, Bot sends you the punishment panel, which contains different type of punishments. Choose your favorable punishments for the module, you are configuring. We recommend keeping at least: Delete Message and 15m of Timeout.\
  &#x20;                                           ![](<../.gitbook/assets/image (16).png>)\
  &#x20;![](<../.gitbook/assets/image (7).png>)![](<../.gitbook/assets/image (20).png>)\
  \
  If you have chosen Mute option, bot will further ask you for Permanent or Temporary Option, choose the one you like. In case of any timed punishment, bot will also ask for the time for the punishment (for e.g., 5 min of Mute).\
  \
  If you have chosen any Send Message punishment, bot will ask you for the Message that will be sent after someone breaks the rate limit. Variables for the same are also provided by the bot itself.\

* **Set Log Channel**\
  Choose the Set Log Channel option and mention the channel in which you want the bot to create the logs. You are done with this step :)\
  \
  Some points to keep in mind:\
  \- Bot should have Manage Webhook Permission in the channel, though it can still create the logs but the webhook logs are faster and reliable than the normal logs.\
  \- If you keep the entry as Null, bot will send logs to the Moderation Log Channel (if exists).\

* **Configuring Rate Limit/Links/Banned Words**\
  **Rate Limit**\
  Choose the configure rate limit option in the panel. Bot will ask you to send your desired rate limit in a specific manner. Just follow the manner and cross check the values in the Embed after setup. By default, Raiden has a rate limit of 5 message in 5 seconds.\
  \
  **Ignored/Allowed Domains**\
  Choose the Ignored Domain option in the panel. Bot will return you a prompt, similar to what you see in adding role/channel. This option works on two different modes, either to allow all links and blacklist some of them \[Blacklist Mode] or to deny all links and whitelist some of them \[Whitelist Mode].\
  \
  **Custom Bad Words**\
  Choose the Manage Bad Words option in the panel. Bot will return you a prompt with three options, Add/Remove/Change\_Mode and Exit. While adding a bad word, bot asks for selection between two types: 'Exact Match' and 'Partial Match'. Partial match will take down words which contains same letter in sequence whereas Exact Match will take exact word only.\
  \
  For Example, you add 'wild' in partial match, then the messages with words like 'wildcard' and 'awild' will also be targeted whereas in exact match, the messages with 'wild' word will be taken down.\
  \
  If you want to use our default list of bad words, you can opt-in/opt-out using the 'Change Mode' button.\

* **Adding Ignored Roles/Channels:**\
  After choosing your desired action, Raiden will send you a prompt with a Embed with values and 3 buttons (Add, Stop, Remove). As you click Add button, you have to mention the desired Role or Channel (ID will also work). \
  \
  As soon as you add the role/channel, value in the Embed will be edited and you can review it time to time with each entry. When you are done with the process you can simply click Stop button and return to the panel.\


#### Extra information

* If you have setup, warn thresholds with the bot and has configured warn punishment in any module and the spammer crossed any warn threshold, then bot will execute both punishments of warn threshold and the module.
* Administrators are not affected by any of these module. Bot will not take any action against them.
* Webhook Logs are a most preferrable way to create logs. Kindly provide Manage Webhook permission to Raiden in the log channel.
* Antispam will only target the member when, he/she crosses the rate limit. Bot will not take any action if they have reached the limit. Configure your rate limit accordingly.
* Antilink will only target messages with either a Blacklisted link or with no Whitelisted link. Links with media extension, are untouched.
* Bot should have View Channel permission, in the entire server. Bot also informs about this while setting up the module.
* You are required to have Manage Server permission to manage this module.
