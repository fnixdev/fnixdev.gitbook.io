# Mode

### Hilzu Modes <a href="#userge-modes" id="userge-modes"></a>

A mode defines the client, whether you want to use Userge on user account or as an Assistant bot.

This both also can be possible, Userge as a userbot and as an Assistant bot. You need to fill all vars for User Mode and Bot Mode. check [Dual Mode](https://theuserge.github.io/deployment#3-dual-mode)

#### 1. USER MODE <a href="#1-user-mode" id="1-user-mode"></a>

UserGe as a userbot with a user account requires this var.

**SESSION\_STRING**

You can get this Var value using two ways.

The First Way:

* Get this using [**@genStr\_Bot**](https://t.me/genStr\_Bot)

The Second Way:

* Type `skip` in the value while deploying the bot.
* After deployed, You must off the Dyno from **Resource** tab.
* Then click on **More** in the top right corner and **Run Console**.
* In Console, Type `bash genStr` and fill the details.

For more details, check this video: on [11:04](https://youtu.be/M4T\_BJvFqkc?t=664) then [19:40](https://youtu.be/M4T\_BJvFqkc?t=1180) to [23:00](https://youtu.be/M4T\_BJvFqkc?t=1380)

#### 2. BOT MODE <a href="#2-bot-mode" id="2-bot-mode"></a>

UserGe as an Assistant bot to execute your commands only from the Bot.

**BOT\_TOKEN** & **OWNER\_ID**

* **BOT\_TOKEN** - Get it from [**@Botfather**](https://t.me/botfather) in Telegram.
* **OWNER\_ID** - Your user id (not username) Get it by using command `/id` on the Group in the reply to your message where Rose Bot was added.

**Make sure you’ve set up these settings while making bot via BotFather.**

1. [Group privacy](https://t.me/usergeot/356150) - Turn this OFF
2. [Allow groups](https://t.me/usergeot/356614) - Turn this ON
3. [Inline mode](https://t.me/usergeot/354104) - Turn this ON
4. Add bot to your Log Channel

#### 3. DUAL MODE <a href="#3-dual-mode" id="3-dual-mode"></a>

Use Hilzu with both Userbot and Assistant bot.

* Fill both [USER MODE](https://theuserge.github.io/deployment#1-user-mode) and [BOT MODE](https://theuserge.github.io/deployment#2-bot-mode) vars values.
