# Scrape Báo Mới

Đây là script tự động lấy dữ liệu tin tức từ website Báo Mới (https://baomoi.com/) trong danh mục "Xã hội". Script sử dụng thư viện `requests` và `BeautifulSoup` để lấy dữ liệu (Tiêu đề, Mô tả, Hình ảnh, Nội dung bài viết) và lưu vào file CSV. Script được lên lịch chạy tự động vào 6h sáng mỗi ngày.

## Tính năng
- Tự động lấy dữ liệu từ danh mục "Xã hội" trên website Báo Mới.
- Lấy thông tin: Tiêu đề, Mô tả, Hình ảnh, Nội dung bài viết.
- Lưu dữ liệu vào file `baomoi_articles.csv`.
- Lên lịch chạy tự động lúc 6h sáng mỗi ngày.

## Yêu cầu
- Máy tính cài đặt Python (phiên bản 3.6 trở lên).

## Hướng dẫn cài đặt
1. **Cài đặt Python**:
   - Tải Python từ https://www.python.org/downloads/.
   - Cài đặt và đảm bảo thêm Python vào PATH.

2. **Cài đặt thư viện**:
   - Mở Command Prompt hoặc PowerShell.
   - Di chuyển đến thư mục chứa project:
     ```
     cd D:\TuDongHoaQuyTrinh\DoAn
     ```
   - Cài đặt các thư viện:
     ```
     pip install -r requirements.txt
     ```

## Cách chạy
1. python scrape_baomoi.py
