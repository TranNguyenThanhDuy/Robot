# 📘 Tên đề tài: Hệ thống băng chuyền phân loại sản phẩm theo màu sắc sử dụng STM32

## 📌 Mô tả đề tài
Đề tài này triển khai một hệ thống băng chuyền tự động có khả năng phân loại sản phẩm dựa trên màu sắc.  
Sản phẩm được đưa qua cảm biến màu sắc (TCS3200), dữ liệu thu thập được xử lý bởi vi điều khiển STM32 để xác định màu.  
Sau đó, hệ thống điều khiển các khay phân loại (dùng servo) đưa sản phẩm đến đúng vị trí.  
LCD hiển thị số lượng sản phẩm theo từng màu và còi cảnh báo sẽ phát tín hiệu nếu có sản phẩm lỗi hoặc không xác định được màu.

---

## 🛠️ Yêu cầu phần cứng

| Thiết bị                    | Số lượng | Ghi chú thêm                         |
|----------------------------|----------|--------------------------------------|
| Vi điều khiển STM32F103C8T6| 1        | Bluepill                             |
| Cảm biến màu sắc TCS34725   | 1        | Phát hiện màu RGB                    |
| Stepper Nema 17 + Driver A4988      | 1        | Di chuyển băng chuyền (DM556/Nema17) |
| Servo SG90    | 1     | Điều khiển khay phân loại            |
| LCD 16x2 I2C               | 1        | Hiển thị số lượng sản phẩm           |
| Buzzer (còi cảnh báo)      | 1        | Báo động khi có lỗi                  |
| Adapter 12V              |1
| Khung cơ khí + băng chuyền | 1        | Tuỳ chỉnh theo thiết kế              |

### STM32F103C8T6:

---
### TCS34725:

---
### Nema 17 + A4988:

---
### Servo SG90:

---
### LCD 16x2:

---
### Buzzer:

---
### Adaper 12V:

---
### Khung băng chuyền:

---

