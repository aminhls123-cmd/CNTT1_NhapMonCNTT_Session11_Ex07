# Bài 7: Gỡ Lỗi Tài Liệu Kế Hoạch Hội Nghị Khoa Học Sinh Viên
## Phần 1: Phân tích lỗi
### 1. Lỗi định dạng & Cơ chế Auto TOC
* **Lỗi cụ thể:** Các tiêu đề trong file đang được định dạng thủ công bằng cách chỉnh sửa trực quan trên nền kiểu mặc định, hoặc để trống không định dạng.
* **Cơ chế hoạt động:** Tính năng Mục lục tự động trong Microsoft Word không quét tài liệu dựa trên **hình thức trực quan**, mà quét dựa trên hệ thống **Paragraph Styles** có cấu trúc. Do toàn bộ tiêu đề giữ nguyên `Normal` hoặc định dạng tay, Word không nhận diện được cấu trúc, dẫn đến việc bảng mục lục trả về kết quả rỗng.
### 2. Vấn đề nhầm cấp Heading
* Gán nhầm cấp làm sai lệch độ thụt đầu dòng trong mục lục.
* Điều này phá vỡ cấu trúc logic của tài liệu, khiến mục chi tiết bị đẩy lên ngang hàng với phần mục lớn, làm người xem không phân biệt được cấp bậc phân cấp thông tin.
## Phần 2: Sửa lỗi & Nghiệm thu
### 3. Các bước sửa cấu trúc Heading cho 7 dòng tiêu đề
Để Auto TOC hiển thị đúng đủ 3 cấp, thực hiện lần lượt các bước sau:
* **Bước 1:** Đặt con trỏ chuột hoặc bôi đen dòng tiêu đề cần sửa.
* **Bước 2:** Sử dụng phím tắt gán chuẩn Heading trên thanh Ribbon:
  * **Cấp 1:** Nhấn `Ctrl + Alt + 1`
    * `1. Thông tin chung hội nghị`
    * `2. Cơ cấu ban tổ chức`
    * `3. Lịch trình sự kiện`
  * **Cấp 2:** Nhấn `Ctrl + Alt + 2`
    * `1.1. Tên hội nghị`
    * `1.2. Thời gian & địa điểm`
    * `2. Ban Nội dung`
  * **Cấp 3:** Nhấn `Ctrl + Alt + 3`
    * `2.1.1. Tiểu ban Kỹ thuật`
* **Bước 3:** Vào tab **References** → chọn **Table of Contents** → Chọn kiểu hiển thị để tạo lại mục lục.

### 4. Xử lý bẫy dữ liệu
* **Vấn đề:** Khi soạn thảo thêm nội dung khiến mục *'3. Lịch trình sự kiện'* dịch chuyển từ trang 2 sang trang 4, bảng mục lục cũ **không tự động cập nhật số trang mới**.
* **Cách khắc phục:**
  * **Cách 1:** Click vào bảng mục lục → Chọn **Update Table** → Chọn **Update entire table** → Bấm `OK`.
  * **Cách 2:** Chọn bảng mục lục và nhấn phím **`F9`**, sau đó chọn **Update entire table**.

---

## Thông tin nộp bài
* **Tên Repository chuẩn:** `B26DTCN097_IT108_Session11_Bai7`
* **Hướng dẫn:** Đẩy file Word bài làm và file `README.md` này lên GitHub ở chế độ **Public**, sau đó lấy link dán vào hệ thống Portal của trường.
