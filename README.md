# ```@MissRose_bot``` Default Anti Spam/Flood/Alt-Right Configuration

### A basic set of settings for an instance of [@MissRose_bot](https://missrose.org/) Telegram bot in order to prevent spam and flooding attacks.
#### Follow the three steps below to run your own pre-configured instance of ```@MissRose_bot``` in your group.

*  Make sure that your group is a [supergroup](https://telegram.org/blog/supergroups5k), which means, that you have to activate history for new members.

* To successfully deploy the bot into your channel, invite ```@MissRose_bot``` into your channel. After inviting ```@MissRose_bot``` to your channel, make sure to give it admin rights. **At this point and at any point, where new admins are introduced to the channel, run ```/admincache```, to let ```@MissRose_bot``` know the current list of admins.**

* Download and send the ```RoseBotDefaultConfig.txt``` file to your channel. Reply with ```/import``` to the message containing the file.

Find [here](https://missrose.org/guide/) a complete list of commands and documentation. You can override any configuration according to your needs and ```/export``` your settings to an extra ```YourConfigFile.txt``` file. 


Following is the set of pre-configured settings.

Command | Action | Pre-configured value 
------------ | ------------- | -------------
```/setflood <value>``` | Set the number of messages after which to take action on a user. Set to '0', 'off', or 'no' to disable. | 7
```/setfloodmode <action type>``` | Choose which action to take on a user who has been flooding. Options: ```ban/kick/mute/tban/tmute``` | tban 2h
```/joinfed <FedID>``` | Join the current chat to a federation. A chat can only join one federation. | ```15e7f0b0-5614-4fa4-b414-ae7bcd003a5a```*
```/captcha <value>```| All users that join will need to solve a CAPTCHA. This proves they aren't a bot! | yes
```/captchamode <value>```| Choose which CAPTCHA type to use for your chat. | math
```/lock <item(s)>``` | Lock one or more items. Now, only admins can use this type! | sticker, bot, gif
```/reports <value>``` | Enable/disable user reports. | yes

\* pre-set is the ["Admins gegen Rechts"](https://t.me/GegenRechts)-Federation. :heart:
