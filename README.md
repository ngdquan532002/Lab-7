# Lab-7
Học công cụ kiểm thử Postman qua video sau: https://www.youtube.com/watch?v=MFxk5BZulVU
# BÁO CÁO BÀI TẬP: TÌM HIỂU VÀ THỰC HÀNH CÔNG CỤ KIỂM THỬ POSTMAN

## 1. Thông tin sinh viên
- **Họ và tên:** Nguyễn Duy Quân
- **Mã sinh viên:** 22012288

## 2. Tài liệu học tập và tham khảo
- Video hướng dẫn chính: [Học Postman qua YouTube](https://www.youtube.com/watch?v=MFxk5BZulVU)
- Tài liệu bổ sung: [Postman Official Documentation](https://learning.postman.com/docs/getting-started/introduction/)

## 3. Nội dung và Kết quả thực hiện

### Kịch bản 1: Gửi Request GET (Lấy dữ liệu)
- **Mô tả:** Gửi yêu cầu GET đến API công khai `https://jsonplaceholder.typicode.com/posts/1` để lấy thông tin bài viết. Kết quả trả về Status `200 OK`.
- **Kết quả thực hiện:**
RequestGet.PNG


---

### Kịch bản 2: Gửi Request POST (Tạo dữ liệu mới)
- **Mô tả:** Gửi yêu cầu POST đến `https://jsonplaceholder.typicode.com/posts` với Body định dạng JSON để giả lập thêm bài viết mới. Kết quả trả về Status `201 Created`.
- **Kết quả thực hiện:**
RequestPost.PNG

---

### Kịch bản 3: Viết Test Script tự động kiểm tra Status Code
- **Mô tả:** Sử dụng tính năng Snippets trong tab **Tests** của Postman để viết script tự động kiểm tra xem mã phản hồi trả về có phải là 200 hay không (`pm.test("Status code is 200", function () { ... })`).
- **Kết quả thực hiện:**
TestScript.PNG

## 4. Kết luận
- Đã hoàn thành việc tìm hiểu công cụ Postman, biết cách tạo Request (GET/POST), truyền Body dữ liệu và kiểm tra kết quả phản hồi.
- Biết cách sử dụng Test Script cơ bản để tự động hóa việc kiểm tra kết quả API.
