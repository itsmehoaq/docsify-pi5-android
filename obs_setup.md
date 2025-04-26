# OBS
- Vào folder fonts, chọn toàn bộ file font và click chuột phải -> Install
- Cài timer plugin bằng file Installer trong link tải phía trên
- Scene Collection -> Import -> Add -> `DKH.json` -> Import
- Nếu OBS báo thiếu file, chọn Search Directory rồi tìm tới folder Stream Kit
- Docks -> Countdown Timer -> để nó vào chỗ nào gọn và không vướng UI của OBS
- Trong dock Countdown Timer, nhấn vào icon Settings và chỉnh như hình dưới:

![](https://s.hoaq.works/mE3oC81Axu.png)

- Trong OBS settings, chỉnh các mục sau:
  - General: bật Automatically record when streaming
  - Stream: **tắt** Enable Enhanced Broadcasting
    - Output:
        - Streaming: Constant Bitrate 6000kbps; Tuning: Low Latency
        - Recording: Constant Bitrate 10000kbps; Tuning: High Quality
    - Audio: Disable toàn bộ audio devices, Advanced / Monitoring Device chỉnh thành tai nghe đang dùng (output chính) + Disable Windows audio ducking
- Vào các scene audio để chỉnh capture audio:
    - DISCORD: như tên, chọn window Discord
    - Streamer Mic: cũng như tên (với những streamer không cast giải, có thể xoá source này). Lưu ý, giữ nguyên filter Noise Suppression trong source này bật để tránh tiếng "noise"
    - osu! Audio: Chọn window Tournament Client 0
- Nếu đã chỉnh osu! height trong file `tournament.cfg` thành 720, chỉnh lại kích thước các client trong OBS thành size 960 x 360
- Nếu streamer không cast, chỉnh CSS của `vc_showcase` source:
  - `[data-userid=""]`: thêm discord id của streamer (nhấn vào chỗ chỉnh offline/online) -> Copy User ID

### Others
- Trong Discord, mở Settings -> Streamer Mode -> bật Automatically Enable/Disable và **tắt** Hide Personal Information