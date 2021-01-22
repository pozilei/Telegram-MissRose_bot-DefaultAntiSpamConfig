# [@RoseBot](https://missrose.org/) Default Anti Spam Configuration

A basic set of settings for an instance of [@RoseBot](https://missrose.org/) Telegram bot in order to prevent spam and flooding attacks. Make sure that your group is a [supergroup](https://telegram.org/blog/supergroups5k), which means, that you have to activate history for new members.

To successfully deploy the bot into your channel, just invite ```@RoseBot``` into your channel.
After inviting ```@RoseBot``` to your channel, make sure to give it admin rights. At this point and at any point, where new admins are introduced to the channel, run ```/admincache```, to let ```@RoseBot``` know the current list of admins.

Find [here](https://missrose.org/guide/) a complete list of commands and documentation.

Download and send the ```RoseBotDefaultAntiSpamConfig.txt``` file to your channel. Reply with ```/import``` to the message containing the file.

Following is a set of pre-configured settings.

Command | Action | Pre-configured value 
------------ | ------------- | -------------
```/setflood <value>``` | Set the number of messages after which to take action on a user. Set to '0', 'off', or 'no' to disable. | 7
```/setfloodmode <action type>``` | Choose which action to take on a user who has been flooding. Options: ```ban/kick/mute/tban/tmute``` | tban 2h
```/joinfed <FedID>``` | Join the current chat to a federation. A chat can only join one federation. | ```15e7f0b0-5614-4fa4-b414-ae7bcd003a5a```*
```captcha <value>```| All users that join will need to solve a CAPTCHA. This proves they aren't a bot! | yes
```/captchamode <value>```| Choose which CAPTCHA type to use for your chat. | math
```/lock <item(s)>``` | Lock one or more items. Now, only admins can use this type! | sticker
```/reports <value>``` | Enable/disable user reports. | yes

\* pre-set is the ["Admins gegen Rechts"](https://t.me/GegenRechts)-Federation.
