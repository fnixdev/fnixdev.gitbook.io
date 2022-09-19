# LOG\_CHANNEL\_ID

LOG\_CHANNEL\_ID

Here, You need Log Channel ID to get all logs and Traceback errors of your UserBot.

* Create a **Private Channel** on your Telegram.
* Type and send any Message on your channel.
* Now, Forward your Message to [@ShowJsonBot](https://telegram.me/ShowJsonBot).
* Bot will send you json formated data of your message.
* Find “forward\_from\_chat” section in the message. you’ll see the “id” starting with `-100.....`
* Copy the id with included hyphen ( `-` ) and Paste into LOG\_CHANNEL\_ID Var.

{% hint style="warning" %}
**Note**:- _Don’t forget to add your_ [_**Bot**_](https://theuserge.github.io/deployment#2-bot-mode) _as administrator in log channel._
{% endhint %}

**For more information… Watch this** [Video](https://youtu.be/M4T\_BJvFqkc?t=1025)

**—- \[Optional] —-**

Instead of making Channel, you can also create a Group to get your logs and this is the very easy way to get. Let’s Do it.

* You just need to make a new **Private Group** on Telegram.
* Add [@MissRose\_Bot](https://t.me/MissRose\_bot) in your Private Group from Add Member > Search “[@MissRose\_Bot](https://t.me/MissRose\_bot)” and then Add.
* After added, Just type “`/id`” in the chat.
* You’ll get the ID of your channel or group.

> Note: Changing Group Type to Public may give you an issue in Userbot. To Fix this, Put Public group ID in var.
