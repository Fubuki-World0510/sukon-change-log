# COMMAND DOCUMENT

### Thông báo:

document này đang đồng bộ sẵn với sukonJS, trong quá trình này sukonTS chưa được đồng bộ, nhưng toàn bộ lệnh đều nằm ở đây, bạn có thể tìm thấy chúng

---

```http
  SLASH COMMAND (/)
```

| Anime    | Option         | Mô tả                                                                                                          |
| :------- | :------------- | :------------------------------------------------------------------------------------------------------------- |
| `hentai` | `<sub reddit>` | Xem hentai, .... sử dụng subreddit, sử dụng **/help** nếu bạn không biết phải làm gì, nó như ZeroTwo bot ấy mà |

| Information      | Option      | Mô tả                                                                         |
| :--------------- | :---------- | :---------------------------------------------------------------------------- |
| `help`           |             | List toàn bộ command hiện có trong Sukon                                      |
| `invite`         |             | Mời Sukon vào máy chủ của bạn                                                 |
| `npmjs`          | `<package>` | Lấy thông tin package từ npm server                                           |
| `ping`           |             | Hiển thị Sukon ping                                                           |
| `server-avatar`  |             | Lấy avatar của máy chủ Discord của bạn                                        |
| `server-info`    |             | Thông tin máy chủ Discord của bạn                                             |
| `websc`          | `<url>`     | ScreenShot một website mà bạn muốn, để check trước web có gì                  |
| `Wikipedia`      | `<keyword>` | Tra mọi thứ với Wikipedia API                                                 |
| `yt-search`      | `<video>`   | Tìm thông tin video trên youtube                                              |
| `ytchannel-info` | `<url>`     | Hiển thị thông tin kênh trên youtube, bạn có thể gõ tên kênh vào option "url" |

| Minigames | Option      | Mô tả                    |
| :-------- | :---------- | :----------------------- |
| `count`   | `<channel>` | Setup count channel :LLL |

| Backup          | Option           | Mô tả                                                           |
| :-------------- | :--------------- | :-------------------------------------------------------------- |
| `backup-info`   | <name>           | Xem thông tin bản backup                                        |
| `backup-list`   |                  | Liệt kê toàn bộ bản backup đang hoạt động trong máy chủ của bạn |
| `backup-load`   | <name> <open>    | Restore bản backup có trong máy chủ của bạn                     |
| `backup`        | <name>           | Tạo bản backup trong máy chủ của bạn (Tối đa 5 bản)             |
| `backup-remove` | <name>           | Xóa bản backup                                                  |
| `backup-share`  | <name> <guildid> | Chia sẻ bản backup của bạn cho máy chủ khác                     |

| Moderator        | Option                                                         | Mô tả                                                                                                                                               |
| :--------------- | :------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------- |
| `autosend`       | `<trigger> <reply> <action>`                                   | Một hệ thống tự động phản hồi khi bạn chat một cái gì đó giống với text mà bạn đã setup cho Sukon giống như Mimu, tôi sẽ update nhiều tính năng hơn |
| `ban`            | `<user> <reason>`                                              | Ban mấy em láo nháo khỏi máy chủ                                                                                                                    |
| `banid`          | `<id>`                                                         | Vẫn là ban nhưng bằng ID, tôi quên không biết nó có hiệu quả không                                                                                  |
| `mute`           | `<user> <time> <reason>`                                       | Timeout người dùng = mute                                                                                                                           |
| `language`       | `<select>`                                                     | Thay đổi ngôn ngữ, ngôn ngữ hỗ trợ: vi/en                                                                                                           |
| `youtube-notify` | `<action> <ytchannel> <notifychannel> <help> <message> <role>` | Setup 1 hệ thống thông báo video mới từ youtube                                                                                                     |
| `setting`        | `<command>`                                                    | Gõ tên lệnh trong option "command" để lấy thông tin lệnh và setting nó                                                                              |
| `kick`           | `<user> <reason>`                                              | Đá mấy em láo nháo khỏi máy chủ                                                                                                                     |
| `nuke`           |                                                                | Kích hoạt 1 quả bom nổ chậm trên kênh của bạn!!! 💥                                                                                                 |
| `say`            | `<text> <have_user_tag>`                                       | Nhờ bot nói gì đó                                                                                                                                   |
| `snipe`          |                                                                | Snipe 1 tin nhắn đã từng bị xóa trước đó, chỉ snipe được 1 tin nhắn trước đó xóa                                                                    |
| `unban`          | `<userid>`                                                     | Gỡ ban cho mấy ông bị ban trong server bằng id user                                                                                                 |

| Music        | Option          | Mô tả                                                                                                                                                                                                                                                                                                                                            |
| :----------- | :-------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `autoplay`   |                 | Setup cho Sukon tự động chơi 1 bài mới có nội dung có thể liên quan đến bài bạn vừa nghe, chúng chỉ random thôi                                                                                                                                                                                                                                  |
| `clearqueue` |                 | Xóa toàn bộ nhạc trong hàng đợi                                                                                                                                                                                                                                                                                                                  |
| `grab`       |                 | Lấy thông tin nhạc hiện đang nghe và gửi vào DMs                                                                                                                                                                                                                                                                                                 |
| `join`       |                 | Cho phép Sukon vào voice của bạn                                                                                                                                                                                                                                                                                                                 |
| `leave`      |                 | Sukon rời voice                                                                                                                                                                                                                                                                                                                                  |
| `loop`       | `<loopmode>`    | Lặp hàng chờ hoặc là lặp nhạc                                                                                                                                                                                                                                                                                                                    |
| `lyrics`     | `<song>`        | Lệnh này bị bảo trì nên không có mô tả                                                                                                                                                                                                                                                                                                           |
| `nowplaying` |                 | Show nhạc hiện tại đang chơi                                                                                                                                                                                                                                                                                                                     |
| `pause`      |                 | Tạm dừng nhạc                                                                                                                                                                                                                                                                                                                                    |
| `play`       | `<input>(:add)` | Chơi mọi nhạc với mọi source mà Sukon hỗ trợ như Spotify, SoundCloud, cdn, ....., **gõ ":add" rồi enter để thêm nhiều nhạc cùng lúc** [demo](https://cdn.discordapp.com/attachments/998438182389567548/1218211162676793435/2024-03-15_21-52-08.mp4?ex=6606d68e&is=65f4618e&hm=f3e63c8170ce359d7683ea0f3a40523acb5431dde29e4dd26993a2a3a0f7be24&) |
| `queue`      | `<> / <page>`   | Show tất cả bài hát trong phòng chờ, à mà bạn không cần phải gõ số trang "page" nếu muốn                                                                                                                                                                                                                                                         |
| `remove`     | `<number>`      | Xóa 1 bài hát trong hàng chờ                                                                                                                                                                                                                                                                                                                     |
| `resume`     |                 | Tiếp tục bài hát                                                                                                                                                                                                                                                                                                                                 |
| `search`     | `<input>`       | Tìm kiếm mọi bài hát trên youtube, ...                                                                                                                                                                                                                                                                                                           |
| `seek`       | `<time>`        | Tua nhạc về, theo prompt sau **<10s - 10m - 10h / HH:mm:ss - mm:ss - mm ss>**                                                                                                                                                                                                                                                                    |
| `shuffle`    |                 | Trộn bài hát trong hàng chờ                                                                                                                                                                                                                                                                                                                      |
| `filters`    | `<filter>`      | Hiệu ứng âm thanh khi nghe nhạc                                                                                                                                                                                                                                                                                                                  |
| `skip`       | `<> / <number>` | Skip nhạc hiện tại đang chơi và sang nhạc khác nếu có hoặc skip theo số bài hát trong danh sách                                                                                                                                                                                                                                                  |
| `stop`       |                 | Dừng nhạc                                                                                                                                                                                                                                                                                                                                        |
| `volume`     | `<number>`      | Thay đổi âm lượng, max 100%                                                                                                                                                                                                                                                                                                                      |

| Playlist      | Option (Autocomplete) | Mô tả                                                 |
| :------------ | :-------------------- | :---------------------------------------------------- |
| `create`      | `<name>`              | Tạo 1 playlist riêng trên Sukon                       |
| `delete`      | `<name>`              | Xóa playlist của bạn                                  |
| `info`        | `<name>`              | Xem thông tin playlist của bạn                        |
| `list`        |                       | List toàn bộ playlist bạn có                          |
| `load`        | `<name> <manual>`     | Sử dụng playlist để yêu cầu Sukon phát nhạc           |
| `removetrack` | `<name> <number>`     | Xóa nhạc trên playlist                                |
| `savecurrent` | `<name>`              | Thệm nhạc hiện đang nghe vào playlist của bạn         |
| `savequeue`   | `<name>`              | Thêm toàn bộ nhạc trong hàng chờ vào playlist của bạn |

| User     | Option              | Mô tả                                                                                                          |
| :------- | :------------------ | :------------------------------------------------------------------------------------------------------------- |
| `afk`    | `<reason>`          | Set cho bạn AFK                                                                                                |
| `google` | `<search>`          | Tìm kiếm với Google                                                                                            |
| `issue`  | `<issue_image>`     | Trung tâm báo cáo Sukon, khi bạn sử dụng Sukon và gặp phải lỗi, hãy report ngay và nó sẽ gửi đến trung tâm !!! |
| `tts`    | `<text> <language>` | Chuyển văn bản thành giọng nói                                                                                 |
| `avatar` | `<target>`          | Lấy avatar của chính bạn hoặc người khác                                                                       |

```http
  CONTEXT MENU
```

| Menu        | Loại      | Mô tả                                                                                                                                                                                                                  |
| :---------- | :-------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `google`    | `Message` | Lấy tin nhắn của bạn ra và đưa lên Google search                                                                                                                                                                       |
| `translate` | `Message` | Lấy tin nhắn của người khác/bạn để dịch chúng sang ngôn ngữ mà bạn đang sử dụng cho giao diện Discord [Xem video nếu bạn không hiểu](https://github.com/Fubuki-World0510/sukon-change-log/blob/main/demo-translate.md) |
| `wiki`      | `Message` | Lấy tin nhắn của bạn/người khác và tra wiki, hãy lấy tin nhắn có keyword                                                                                                                                               |

## WEBSITE DOCUMENT

Nothing: Sukon Dashboard đang trong làm việc

### Web Player

- Nếu bạn thấy trên embed chúng có webplayer true (bật/có) hoặc false (tắt/không), thì đó là tính năng web player request

| Điều kiện | Yêu cầu từ  | Mô tả                                                               | Web player status |
| :-------- | :---------- | :------------------------------------------------------------------ | :---------------- |
| `1`       | `Sukon web` | Nếu có 1 người trên sukon web yêu cầu 1 bài hát trên đó             | true              |
| `2`       | `Lệnh join` | Nếu có 1 người sử dụng lệnh `/join` và yêu cầu 1 bài hát từ lệnh đó | true              |
| `2`       | `lệnh play` | Nếu có 1 người chỉ sử dụng lệnh `/play` và yêu cầu nhạc từ nó       | false             |
