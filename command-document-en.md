# COMMAND DOCUMENT

### Notification:

This document is already synchronized with sukonJS, during this process sukonTS is not synchronized, but all the commands are here, you can find them

```http
  SLASH COMMAND (/)
```

| Anime    | Option         | Description                                                                                                                               |
| :------- | :------------- | :---------------------------------------------------------------------------------------------------------------------------------------- |
| `hentai` | `<sub reddit>` | watch hentai or other nsfw content through subreddit, if you don't know what to do type **help** in the "sub reddit" box like ZeroTwo bot |

| Information      | Option      | Description                                                                     |
| :--------------- | :---------- | :------------------------------------------------------------------------------ |
| `changelog`      | `<version>` | Sukon Change Log                                                                |
| `help`           |             | Show all command in Sukon                                                       |
| `invite`         |             | Invite Sukon to your server                                                     |
| `npmjs`          | `<package>` | Get npm package information in npm server                                       |
| `ping`           |             | Display Sukon bot ping                                                          |
| `server-avatar`  |             | Get the server's avatar                                                         |
| `server-info`    |             | Server information                                                              |
| `websc`          | `<url>`     | ScreenShot A website                                                            |
| `Wikipedia`      | `<keyword>` | Wiki anything with wikipedia api                                                |
| `yt-search`      | `<video>`   | Find videos on youtube                                                          |
| `ytchannel-info` | `<url>`     | Display youtube channel information, you can enter channel name in "url" option |

| Minigames | Option      | Description              |
| :-------- | :---------- | :----------------------- |
| `count`   | `<channel>` | Setup count channel :LLL |

| Backup          | Option             | Mô tả                                                |
| :-------------- | :----------------- | :--------------------------------------------------- |
| `backup-info`   | `<name>`           | View Backup information                              |
| `backup-list`   |                    | List the entire backup that is active in your server |
| `backup-load`   | `<name> <open>`    | Restore the backup in your server                    |
| `backup`        | `<name>`           | Create a backup in your server (Max 5 backup)        |
| `backup-remove` | `<name>`           | Delete Backup                                        |
| `backup-share`  | `<name> <guildid>` | Share your backup for another server                 |

| Moderator        | Option                                                         | Description                                                   |
| :--------------- | :------------------------------------------------------------- | :------------------------------------------------------------ |
| `autosend`       | `<trigger> <reply> <action>`                                   | Autoresponder like Mimu i think                               |
| `ban`            | `<user> <reason>`                                              | Ban a member in your server                                   |
| `banid`          | `<id>`                                                         | Ban ID user                                                   |
| `mute`         | `<user> <time> <reason>`                                       | Timeout user = mute                                           |
| `kick`           | `<user> <reason>`                                              | Kick a user in your server                                    |
| `nuke`           |                                                                | Destroy your channel and BOOM!!! 💥                           |
| `language`       | `<select>`                                                     | change your sukon language, supported languages: vi/en        |
| `setting`        | `<command>`                                                    | Enter command in "option" to get the settings of that command |
| `youtube-notify` | `<action> <ytchannel> <notifychannel> <help> <message> <role>` | Set up a new YouTube video notification system                |
| `say`            | `<text> <have_user_tag>`                                       | say something                                                 |
| `snipe`          |                                                                | Snipe any last delete message                                 |
| `unban`          | `<userid>`                                                     | Unban a user in your server                                   |

| Music        | Option          | Description                                                                                                                                                                                                                                                                                                                                                             |
| :----------- | :-------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `autoplay`   |                 | Set Sukon autoplay video. When the music ends, they're just random                                                                                                                                                                                                                                                                                                      |
| `clearqueue` |                 | Removes all songs in the music queue                                                                                                                                                                                                                                                                                                                                    |
| `grab`       |                 | Grabs and sends you the song that is currently playing                                                                                                                                                                                                                                                                                                                  |
| `join`       |                 | Allow Sukon into your voice                                                                                                                                                                                                                                                                                                                                             |
| `leave`      |                 | Sukon leave voice                                                                                                                                                                                                                                                                                                                                                       |
| `loop`       | `<loopmode>`    | Loop queue or loop music                                                                                                                                                                                                                                                                                                                                                |
| `lyrics`     | `<song>`        | Maintenance this command                                                                                                                                                                                                                                                                                                                                                |
| `nowplaying` |                 | Show the current playing song                                                                                                                                                                                                                                                                                                                                           |
| `pause`      |                 | Pause music                                                                                                                                                                                                                                                                                                                                                             |
| `play`       | `<input>(:add)` | Play all music with every source that Sukon supports like Spotify, SoundCloud, CDN, ....., **Type ":add" and then Enter to add more music at the same time** [demo](https://cdn.discordapp.com/attachments/998438182389567548/1218211162676793435/2024-03-15_21-52-08.mp4?ex=6606d68e&is=65f4618e&hm=f3e63c8170ce359d7683ea0f3a40523acb5431dde29e4dd26993a2a3a0f7be24&) |
| `queue`      | `<> / <page>`   | Show all song in queue, you may not need to type page number                                                                                                                                                                                                                                                                                                            |
| `remove`     | `<number>`      | Removes a song from the queue                                                                                                                                                                                                                                                                                                                                           |
| `resume`     |                 | Resume music                                                                                                                                                                                                                                                                                                                                                            |
| `search`     | `<input>`       | Search any song on youtube                                                                                                                                                                                                                                                                                                                                              |
| `seek`       | `<time>`        | Seek the currently playing song. **<10s - 10m - 10h / HH:mm:ss - mm:ss - mm ss>**                                                                                                                                                                                                                                                                                       |
| `shuffle`    |                 | Shuffle the queue                                                                                                                                                                                                                                                                                                                                                       |
| `filters`    | `<filter>`      | Set sukon sound filter                                                                                                                                                                                                                                                                                                                                                  |
| `skip`       |                 | Skip the song currently playing                                                                                                                                                                                                                                                                                                                                         |
| `skipto`     | `<number>`      | Skip to a specific song                                                                                                                                                                                                                                                                                                                                                 |
| `stop`       |                 | Stop the music                                                                                                                                                                                                                                                                                                                                                          |
| `volume`     | `<number>`      | Change volume                                                                                                                                                                                                                                                                                                                                                           |

| Playlist      | Option (Autocomplete) | Description                                         |
| :------------ | :-------------------- | :-------------------------------------------------- |
| `create`      | `<name>`              | Create a playlist for you                           |
| `delete`      | `<name>`              | Delete your saved playlist                          |
| `info`        | `<name>`              | Get information about your saved playlist           |
| `list`        |                       | List all playlist you have                          |
| `load`        | `<name> <manual>`     | Load the saved playlist                             |
| `removetrack` | `<name> <number>`     | Remove a track from playlist                        |
| `savecurrent` | `<name>`              | Add the current playing to song your saved playlist |
| `savequeue`   | `<name>`              | Save the current queue in your saved playlist       |

| User     | Option              | Description                                               |
| :------- | :------------------ | :-------------------------------------------------------- |
| `afk`    | `<reason>`          | Set your afk                                              |
| `google` | `<search>`          | Google search                                             |
| `issue`  | `<issue_image>`     | Sukon Report Center !!! Report any issue/problem in Sukon |
| `tts`    | `<text> <language>` | Text to speak                                             |

```http
  CONTEXT MENU
```

| Menu        | Type      | Description                                                                                                                                                                                                               |
| :---------- | :-------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `google`    | `Message` | Get text in any message you want and search it on Google                                                                                                                                                                  |
| `translate` | `Message` | Get text in any message you want and translate it according to your discord interface language [Watch the demo if you don't understand](https://github.com/Fubuki-World0510/sukon-change-log/blob/main/demo-translate.md) |
| `wiki`      | `Message` | Get text in any message you want and search it on Wikipedia API                                                                                                                                                           |

## WEBSITE DOCUMENT

Nothing: Sukon dashboard inprogress ⚠

### Web Player

- If you see on embed they have webplayer true (enabled/yes) or false (disabled/no), then that is the web player request feature

| Condition | Request from   | Description                                                                       | Web player status |
| :-------- | :------------- | :-------------------------------------------------------------------------------- | :---------------- |
| `1`       | `Sukon web`    | If someone on sukon web requests a song on there                                  | true              |
| `2`       | `join command` | If there is 1 person use the command `/join` and request a song from that command | true              |
| `2`       | `play command` | If there is 1 person just use `/play` command and request music from it           | false             |
