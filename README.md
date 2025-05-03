# 🔧 NebulaForge – Dự án phần cứng bảo mật với ESP32

NEBULAFORGE là thiết bị gây nhiễu tần số 2.4GHz, có khả năng làm gián đoạn nhiều loại tín hiệu như:
+ Wi-Fi (có thể chọn kênh gây nhiễu)
+ Bluetooth
+ BLE (Bluetooth Low Energy)
+ Drone RC
+ Thiết bị IoT & các thiết bị không dây khác

## 📦 Linh kiện cần thiết

| STT | Tên linh kiện                         | Số lượng | Ghi chú |
|-----|----------------------------------------|----------|---------|
| 1   | ESP32 NodeMCU                          | 1        |         |
| 2   | Mạch sạc TP4056 (Micro USB / Type-C)   | 1        |         |
| 3   | JST PH 2.0 connector                    | 1        |         |
| 4   | Pin Li-Ion 3.7V                         | 1        |         |
| 5   | Ăng-ten SMA                             | 2        |         |
| 6   | E01-2G4M27D RF Module                   | 2        |         |
| 7   | Tụ điện 10µF 50V                        | 2        |         |
| 8   | LED 5mm                                 | 2        |         |
| 9   | Điện trở 220Ω                           | 2        |         |
| 10  | Công tắc SK12D07 chân cong              | 1        |         |
| 11  | PCB mẫu                                 | 1        | Cần thiết kế lại từ file Gerber |

⚠️ **Lưu ý:** Dự án không cung cấp sơ đồ mạch chi tiết vì mục đích bảo mật. Người dùng cần tự nghiên cứu và xây dựng sơ đồ mạch từ dữ liệu Gerber hoặc từ ảnh.

## 🛠️ Hướng dẫn lắp ráp

1. Chuẩn bị đầy đủ linh kiện như bảng ở trên.
2. Dựa theo file Gerber hoặc ảnh nguyên lý, tiến hành đặt linh kiện vào PCB đúng vị trí.
3. Hàn chắc chắn các linh kiện vào bo mạch.
4. Lắp pin Li-Ion vào mạch sạc TP4056 qua cổng JST.
5. Kết nối Ăng-ten SMA và mô-đun RF với ESP32 theo sơ đồ nguyên lý.

> Lưu ý: Dự án yêu cầu người dùng có kiến thức cơ bản về điện tử, đọc sơ đồ mạch, và kỹ năng hàn linh kiện.

## 🔌 Nạp Firmware

Hiện tại, firmware sẽ được cung cấp riêng cho từng thiết bị. Phần mềm hỗ trợ flash sẽ được công bố sau. Bạn có thể theo dõi cập nhật tại:

- [Kênh Telegram](https://t.me/czdeveloper_news)
- [Website chính thức](https://czdeveloper.gitbook.io/main/hardware/cyber-security/nebulaforge)

## 📚 Tham khảo

- GitBook chính thức: [NebulaForge](https://czdeveloper.gitbook.io/main/hardware/cyber-security/nebulaforge)
- Hướng dẫn thiết lập: [Hướng dẫn chi tiết](https://czdeveloper.gitbook.io/main/hardware/cyber-security/nebulaforge/huong-dan-thiet-lap)

---
