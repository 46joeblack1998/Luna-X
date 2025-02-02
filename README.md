[![Repository state](https://github-readme-stats.vercel.app/api/pin/?username=5hojib&repo=hk-upstream&theme=react&border_color=61dafb&border_radius=10)](https://github.com/5hojib/hk-upstream)

[![Support Group](https://img.shields.io/badge/Support%20Group-Join-000000)](https://t.me/Luna073xChat)     [![Render](https://img.shields.io/badge/Deploy%20to%20Render-Deploy-000000)](https://render.com/deploy?repo=)

### Instructions for Render
1. Fork and star this repository.
2. Go to your forked repository.
3. Click on 'Deploy to Render' button.
4. Fill in all variables correctly and start the deployment.
5. After deployment, fill in `BASE_URL` using the `bsetting` command from the bot.
6. Fill in the other variables using the `bsetting` command or by writing them in `sample_config.env` and renaming the file to `config.env`.
7. Upload `token.pickle` and other private files using the `bsetting` command from the bot.

### Instructions for Railway
1. Fork and star this repository.
2. Go to your forked repository.
3. Delete `README.md` and `sample_config.env`.
4. Go to your Railway account and start deploy from GitHub repository.
5. Select forked repository and fill in these variables:
* `BOT_TOKEN`
* `OWNER_ID`
* `DATABASE_URL`
* `TELEGRAM_API`
* `TELEGRAM_HASH` 
6. After deployment, fill in the other variables using the `bsetting` command from the bot.
7. Upload `token.pickle` and other private files using the `bsetting` command from the bot.

### Bot commands
```
mirror - or /m Mirror
zipmirror - or /zm Mirror and upload as zip
unzipmirror - or /uzm Mirror and extract files
qbmirror - or /qm Mirror torrent using qBittorrent
qbzipmirror - or /qzm Mirror torrent using qb and upload as zip
qbunzipmirror - or /quzm Mirror torrent using qb and extract files
leech - or /l Leech
zipleech - or /zl Leech and upload as zip
unzipleech - or /uzl Leech and extract files
qbleech - or /ql Leech torrent using qBittorrent
qbzipleech - or /qzl Leech torrent using qb and upload as zip
qbunzipleech - or /quzl Leech torrent using qb and extract
clone - Copy file/folder to Drive
count - Count file/folder from Drive
ytdl - or /y Mirror yt-dlp supported link
ytdlzip - or /yz Mirror yt-dlp supported link as zip
ytdlleech - or /yl Leech through yt-dlp supported link
ytdlzipleech - or /yzl Leech yt-dlp support link as zip
usetting - User settings
bsetting - Bot settings
status - Get Mirror Status message
btsel - Select files from torrent
rss - Rss menu
list - Search files in Drive
search - Search for torrents with API
cancel - Cancel a task
cancelall - Cancel all tasks
del - Delete file/folder from Drive
log - Get the Bot Log
shell - Run commands in Shell
restart - Restart the Bot
stats - Bot Usage Stats
ping - Ping the Bot
help - All cmds with description
```

### Modified from
* [JMDKH](https://github.com/junedkh/jmdkh-mltb)
* [MLTB](https://github.com/anasty17/mirror-leech-telegram-bot)
* [WZML](https://github.com/weebzone/WZML)

### Thanks To
* [Juned KH](https://github.com/junedkh)
* [Anas](https://github.com/anasty17)
* [Karan Adhikary](https://github.com/weebzone)
* ChatGPT

You can't donate me! 🤣