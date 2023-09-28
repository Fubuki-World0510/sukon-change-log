

## COMMAND DOCUMENT

```http
  SLASH COMMAND (/)
```


| Anime | Option         | Mô tả                |
| :-------- | :------- | :------------------------- |
| `hentai` | `<sub reddit>` | Xem hentai, .... sử dụng subreddit, sử dụng **/help** nếu bạn không biết phải làm gì, nó như ZeroTwo bot ấy mà |
| `neko` | `<>` | Random ảnh mèo anime |
| `search_waifu` | `<text> <gif>` | Tìm waifu art ( Độ chính xác 70% 💀💀💀) |


| Config | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `247`      | `<>` | Bạn chỉ cần enter lệnh và Sukon sẽ treo voice 24/7 không rời, gõ lại lệnh để tắt nó |
| `language` | `<select>` | Thay đổi ngôn ngữ, ngôn ngữ hỗ trợ: vi/en |
| `setting` | `<command>` | Gõ tên lệnh trong option "command" để lấy thông tin lệnh và setting nó |
| `youtube-notify` | `<action> <ytchannel> <notifychannel> <help> <message> <role>` | Setup 1 hệ thống thông báo video mới từ youtube - ytchannel = [ID youtube channel](https://github.com/Fubuki-World0510/sukon-change-log/blob/main/how-to-get-youtube-channel-id.md) |

| Information | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `changelog` | `<version>` | Sukon Change Log |
| `help` | `<>` | List toàn bộ command hiện có trong Sukon |
| `invite` | `<>` | Mời Sukon vào máy chủ của bạn |
| `npmjs` | `<package>` |Lấy thông tin package từ npm server |
| `ping` | `<>` | Hiển thị Sukon ping |
| `server-avatar` | `<>` | Lấy avatar của máy chủ Discord của bạn |
| `server-info` | `<>` | Thông tin máy chủ Discord của bạn |
| `websc` | `<url>` | ScreenShot một website mà bạn muốn, để check trước web có gì |
| `Wikipedia` | `<keyword>` | Tra mọi thứ với Wikipedia API |
| `yt-search` | `<video>` | Tìm thông tin video trên youtube |
| `ytchannel-info` | `<url>` | Hiển thị thông tin kênh trên youtube, bạn có thể gõ tên kênh vào option "url" |

| Minigames | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `count` | `<channel>` | Setup count channel :LLL |

| Moderator | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `autosend` | `<trigger> <reply> <action>` | Một hệ thống tự động phản hồi khi bạn chat một cái gì đó giống với text mà bạn đã setup cho Sukon giống như Mimu, tôi sẽ update nhiều tính năng hơn |
| `ban` | `<user> <reason>` | Ban mấy em láo nháo khỏi máy chủ|
| `banid` | `<id>` | Vẫn là ban nhưng bằng ID, tôi quên không biết nó có hiệu quả không |
| `bocchi` | `<user> <time> <reason>` | Timeout người dùng = mute |
| `kick` | `<user> <reason>` | Đá mấy em láo nháo khỏi máy chủ |
| `nuke` | `<>` | Kích hoạt 1 quả bom nổ chậm trên kênh của bạn!!! 💥 |
| `say` | `<text> <have_user_tag>` | Nhờ bot nói gì đó |
| `snipe` | `<>` | Snipe 1 tin nhắn đã từng bị xóa trước đó, chỉ snipe được 1 tin nhắn trước đó xóa |
| `unban` | `<userid>` | Gỡ ban cho mấy ông bị ban trong server bằng id user |

| Music | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `autoplay` | `<>` | Setup cho Sukon tự động chơi 1 bài mới có nội dung có thể liên quan đến bài bạn vừa nghe, chúng chỉ random thôi |
| `clearqueue` | `<>` | Xóa toàn bộ nhạc trong hàng đợi |
| `grab` | `<>` | Lấy thông tin nhạc hiện đang nghe và gửi vào DMs |
| `join` | `<>` | Cho phép Sukon vào voice của bạn |
| `leave` | `<>` | Sukon rời voice |
| `loop` | `<loopmode>` | Lặp hàng chờ hoặc là lặp nhạc |
| `lyrics` | `<song>` | Lệnh này bị bảo trì nên không có mô tả |
| `nowplaying` | `<>` | Show nhạc hiện tại đang chơi |
| `pause` | `<>` | Tạm dừng nhạc |
| `play` | `<input>` | Chơi mọi nhạc với mọi source mà Sukon hỗ trợ như Spotify, SoundCloud, cdn, ..... |
| `queue` | `<> / <page>` | Show tất cả bài hát trong phòng chờ, à mà bạn không cần phải gõ số trang "page" nếu muốn |
| `remove` | `<number>` | Xóa 1 bài hát trong hàng chờ |
| `resume` | `<>` | Tiếp tục bài hát |
| `search` | `<input>` | Tìm kiếm mọi bài hát trên youtube, ... |
| `seek` | `<time>` | Tua nhạc về, theo prompt sau **<10s - 10m - 10h / HH:mm:ss - mm:ss - mm ss>** |
| `shuffle` | `<>` | Trộn bài hát trong hàng chờ |
| `filters` | `<filter>` | Hiệu ứng âm thanh khi nghe nhạc |
| `skip` | `<>` | Skip nhạc hiện tại đang chơi và sang nhạc khác nếu có |
| `skipto` | `<number>` | Skip đến 1 nhạc nào đó trong hàng chờ |
| `stop` | `<>` | Dừng nhạc |
| `volume` | `<number>` | Thay đổi âm lượng, max 100% |

| Playlist | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `create` | `<name>` | Tạo 1 playlist riêng trên Sukon |
| `delete` | `<name>` | Xóa playlist của bạn |
| `info` | `<name>` | Xem thông tin playlist của bạn |
| `list` | `<>` | List toàn bộ playlist bạn có |
| `load` | `<name>` | Sử dụng playlist để yêu cầu Sukon phát nhạc |
| `removetrack` | `<name> <number>` | Xóa nhạc trên playlist |
| `savecurrent` | `<name>` | Thệm nhạc hiện đang nghe vào playlist của bạn |
| `savequeue` | `<name>` | Thêm toàn bộ nhạc trong hàng chờ vào playlist của bạn |

| User | Option     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `afk` | `<reason>` | Set cho bạn AFK |
| `google` | `<search>` | Tìm kiếm với Google |
| `ip-location` | `<ip>` | Lấy thông tin vị trí IP :) với 60% độ chính xác 💀 tôi nghĩ vậy, bạn lấy 1 số đứa nó vẫn có độ chính xác gần đúng nha nhưng biết được ở thành phố nào luôn |
| `issue` | `<issue_image>` | Trung tâm báo cáo Sukon, khi bạn sử dụng Sukon và gặp phải lỗi, hãy report ngay và nó sẽ gửi đến trung tâm, trong trường hợp nếu được gắn là đã tự động gửi thì bạn không cần gửi lại !!! |
| `tts` | `<text> <language>` | Chuyển văn bản thành giọng nói |
| `ytmp3` | `<url>` | Tải mp3 từ youtube |

```http
  CONTEXT MENU
```

| Menu | Loại     | Mô tả                       |
| :-------- | :------- | :-------------------------------- |
| `google` | `Message` | Lấy tin nhắn của bạn ra và đưa lên Google search |
| `play` | `Message` | Lấy tên nhạc từ tin nhắn của bạn/người khác và chơi chúng trên voice, [có tính năng tự động phát hiện bài hát, xem DEMO nếu bạn không biết](https://github.com/Fubuki-World0510/sukon-change-log/blob/main/demo-music-detect.md), hỗ trợ tìm kiếm url |
| `translate` | `Message` | Lấy tin nhắn của người khác/bạn để dịch chúng sang ngôn ngữ mà bạn đang sử dụng cho giao diện Discord [Xem video nếu bạn không hiểu](https://github.com/Fubuki-World0510/sukon-change-log/blob/main/demo-translate.md) |
| `wiki` | `Message` | Lấy tin nhắn của bạn/người khác và tra wiki, hãy lấy tin nhắn có keyword |

## WEBSITE DOCUMENT
[Sukon Web 1 - player](http://sukondiscord.ddns.net:2323/) (Bạn có thể xóa port trong url kia và truy cập panel của Sukon nhưng bạn không thể tắt chúng, đừng để tôi phải thấy ai đó bị ban khỏi dịch vụ web nếu bạn có nghịch ngợm trong cái web của tôi)

| Option | Loại     | Mô tả               | Trạng thái |
| :-------- | :------- | :--------------------- | :-----------------|
| `Music` | `User` | Chơi nhạc, thêm nhạc vào hàng chờ (THỬ NGHIỆM), `nên nhớ, nó chỉ chơi nhạc và không thể làm gì khác như dừng nhạc, .. tôi sẽ update nó sau` | ✅ |
| `Youtube Notification System` | `Moderator` | Setup 1 new video notification trên youtube | ❌ |
