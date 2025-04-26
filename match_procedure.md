# Match Procedure
Dưới đây là phần guide quan trọng nhất để stream có thể vận hành trơn tru.

### Stream Start
- Mở các thứ liên quan theo đúng thứ tự sau: osu! -> tosu -> OBS **30 phút trước giờ bắt đầu trận**
- Set thời gian bắt đầu trận trong dock Countdown Timer và nhấn chạy timer (nút play)
  - Khuyến nghị đổi qua mode `D` và nhập ngày giờ bắt đầu trận để countdown chạy đúng thời gian
- Mở screenshare cho caster trong Discord 
  1. Nếu audio output của osu! **không** phải output chính (tai nghe or smth) 
  - Chuột phải vào preview OBS -> chọn Windowed Projector
  - Share cửa sổ này trên Discord
  2. Nếu audio output của osu! **trùng với output chính**
  - Bật Virtual Camera trong OBS
  - Mở Camera trong Discord và share view OBS
  - Screenshare **Tournament Client 0** trong Discord
- Trong client osu!, chọn trận chuẩn bị stream **sau khi ref xác nhận đã addref** và chỉnh Best of của round tương ứng:
  - Ro16 - 9
  - QF & SF - 11
  - F & GF - 13
- **10 phút trước giờ bắt đầu trận, nhấn bắt đầu stream**
- Khi countdown kết thúc, OBS sẽ tự chuyển vào scene Gameplay (nếu setting Countdown timer đúng)
- Chuột phải vào source **Overlay** và chọn Interact

### Hướng dẫn control overlay
- Khi bắt đầu trận, chuyển vào scene Mappool bằng nút Toggle Mappool
- Hướng dẫn tương tác với Mappool:
  - Click trái: Red team PICK
  - Click phải: Blue team PICK
  - Shift + Click trái: Red team BAN
  - Shift + Click phải: Blue team BAN
  - Ctrl + Click trái: reset (huỷ ban / huỷ pick)
- Khi team call ban hoặc pick, nhấn vào slot tương ứng theo hướng dẫn trên rồi chờ khoảng vài giây rồi Toggle về lại Gameplay cũng bằng nút nêu trên

### Hướng dẫn control KHI CÓ AMPLIFIER HOẠT ĐỘNG
- Khi team call sử dụng Amp hoặc Trap, chọn theo tên amp / trap tương ứng ở phía bên phải overlay controller
- Với các amp có multiplier cố định (Booster / Double-edge sword), mult của amp đã được tính sẵn, nhớ bật là được
- Với các amp có mult không cố định (Cameraman), nhập giá trị mult vào ô Custom Multiplier (ví dụ: mult x1.1 -> nhập giá trị `1.1`)
- Chọn các player bị ảnh hưởng bởi Amp (client left 0/1 = team red player 1 / 2), tương tự với client right (client 2/3 = team blue player 1 / 2)
- **Nếu có amp nào streamer không rõ các sử dụng, ping Hoaq ngay lập tức**
- Sau khi hết map, untick client nhận amp và bấm nút reset trên amp

### Nếu stream liên tục nhiều trận
- Chọn source Overlay rồi nhấn Refresh để trả trạng thái overlay về mặc định khi chuyển trận stream

### Nếu gặp bất cứ rắc rối nào
- Ping ref để hỏi lại ban pick nếu cần thiết
- Ping Hoaq để hỏi các thiết lập amp nếu không rõ
- Ping Rin@mi_1 nếu overlay gặp lỗi hiển thị hoặc không hoạt động