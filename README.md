# Telegra.ph-Uploader

> A star ⭐ from you means a lot to us !

<p align="center"><a href="https://github.com/Captainamarica/NightVissio.-TELEGRAPH"><img src="https://telegra.ph/file/554341d5c7e0d0dcd2daf.jpg" width="5000"></a></p>

Telegram bot to upload media to telegra.ph

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Usage

### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/LuziferDevil/Limited_TelegraphBot)

1. Tap on above button and fill `API_ID`, `API_HASH`, `BOT_TOKEN`.
2. Then tap "Deploy App" below it. Wait till deploying is complete (will take atmost 2 minutes).
3. After deploying is complete, tap on "Manage App"
4. Check the logs to see if your bot is ready!

### Local Deploying

1. Clone the repo
   ```markdown
   git clone https://github.com/Captainamarica/NightVissio.-TELEGRAPH
   ```

2. Edit `Config.py` and fill the needed variables

3. Enter the directory
   ```markdown
   cd Telegra.ph-Uploader
   ```
5. Run the file
   ```markdown
   python3 main.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `OWNER_ID` - Your Telegram ID
- `DATABASE_URL` - Will be automatically added by Heroku.
  
#### Optional Vars

> Don't forget to add your bot in the chat you fill in MUST_JOIN.

- `MUST_JOIN` - Username/ID of your telegram channel/group.

#### Owner Special Command

- `/stats` - Get Total Users and Chats using your bot.

## Functions

> More features soon, this is a minimal example :)

Upload one of the below supported media type to Telegra.ph

1) Image
2) Video
3) Sticker
4) Gifs or Animation
5) Videos
6) Video Note
7) Document (Video/Photo/Gif)


## License

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)


## Credits

- [Dan Tès](https://github.com/delivrance) for his [Pyrogram](https://docs.pyrogram.org) Library
- [NAVANJANA](https://t.me/NA_VA_N_JA_NA1) - ``Dev``

## Support

Channel :- [@NIGHT VISSION BOTS🇱🇰](https://t.me/NightVission)

Group Chat :- [@NIGHT VISSION SUPPORT🇱🇰](https://t.me/NightVissionSupport)
