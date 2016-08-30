# Hệ thống tưới cây tự động sử dụng mạch Arduino
## Chức năng
- Tự động tưới cây khi cây thiếu nước
- Hệ thống sẽ tự động dừng khi bơm đủ nước cho cây
- Có hệ thống đèn led báo thông tin của bơm và lượng nước của cây

## Chuẩn bị thiết bị
- 01 Arduino UNO
- 01 Led 5mm màu đỏ
- 01 Led 5mm màu xanh
- 01 Led 5mm màu vàng
- 03 điện trở 220Ω
- 01 Cảm biến độ ẩm
- 01 Nguồn cho máy bơm (6,9,12v tùy thuộc vào máy bơm)
- 01 Bơm mini
- 01m Ống dẫn nước cho máy bơm.

## Thiết kế mạch
Thiết kế mạch như hình dưới đây: 
![alt text](https://github.com/htpl/tuoicay-tudong-arduino/blob/master/AutomaticWatering_bb.png "AutomaticWatering Breadboard")

## Viết mã nguồn chương trình cho Arduino
- Xem file  [AutomaticWatering.ino](https://github.com/htpl/tuoicay-tudong-arduino/blob/master/AutomaticWatering.ino)

## Lắp đặt
- Lắp đặt mạch như sơ đồ ở trong breadboard.
- Cắm ngập cảm biến xuống đất ở chậu cây.
- Chuẩn bị chậu nước, nối ống dẫn với bơm đúng chiều.
- Cắm mạch vào máy tính qua usb, và nạp chương trình vào mạch uno.
- Chạy thử
## Thử nghiệm
- Kiểm tra đấu nối với nguồn nước.
- Kiểm tra cảm biến độ ẩm đã ngập sâu vào đất hay chưa.
- Kiểm tra độ ẩm đất.
- Bật hệ thống tưới tự động.
- Kiểm tra thông tin thông qua đèn báo.
- Đợi để kiểm tra hệ thống hoạt động với 3 chế độ (Thiếu nước, đủ nước, thừa nước).
