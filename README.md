# E-Book-Reader
# 📖 Sách Điện Tử - E-Book Reader

![E-Book Banner](https://via.placeholder.com/1200x400/1E3A8A/60A5FA?text=SÁCH+ĐIỆN+TỬ)  
*(Thay bằng ảnh thực tế của thiết bị khi có)*

**Sách Điện Tử** là dự án thiết bị đọc sách điện tử (e-reader) tự chế, hỗ trợ đọc file PDF, EPUB, TXT, Markdown và hình ảnh. Thiết bị sử dụng màn hình lớn, tiết kiệm pin, giao diện thân thiện, phù hợp để đọc sách lâu dài mà không mỏi mắt.

## ✨ Tính năng nổi bật

- Hỗ trợ nhiều định dạng sách: **PDF, EPUB, TXT, MD, HTML**
- Màn hình cảm ứng lớn (7 inch hoặc 10 inch)
- Chế độ **Dark/Light mode** (giảm ánh sáng xanh)
- Điều chỉnh font size, khoảng cách dòng, độ sáng
- Thư viện sách cá nhân (lưu trữ trên thẻ SD)
- Đánh dấu trang (Bookmark)
- Tìm kiếm từ khóa trong sách
- Pin lâu (lên đến 15-20 giờ sử dụng)
- Giao diện tiếng Việt + tiếng Anh
- Hỗ trợ điều khiển bằng nút bấm hoặc cảm ứng

## 🛠️ Công nghệ sử dụng

- **Mainboard**: ESP32 (hoặc ESP32-S3)
- **Màn hình**: 7" hoặc 10" Waveshare / Good Display e-Paper / TFT / IPS
- **Bộ nhớ**: Thẻ Micro SD (FAT32)
- **Ngôn ngữ lập trình**: C++ (Arduino IDE / ESP-IDF)
- **Thư viện chính**:
  - LVGL (Giao diện đồ họa đẹp)
  - PDF-Parser / EPUB decoder
  - Adafruit GFX / TFT_eSPI
  - LittleFS / SD

## 📁 Cấu trúc dự án

## 🚀 Hướng dẫn cài đặt

1. **Clone repository**
   ```bash
   git clone https://github.com/tonight386/SachDienTu.git
   cd SachDienTu
