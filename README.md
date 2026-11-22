# Web/app học tập — Hóa học 9, Ôn tập kiểm tra giữa kì II

**Ôn tập kiểm tra giữa kì II (Bài 29–32: Carbohydrate, Tinh bột và cellulose, Protein, Polymer)**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

Phạm vi ôn tập đọc từ PDF gốc `OnTap_Giua_Ki_II_Hoa_9.pdf`: Bài 29–32.

## Nội dung

Web/app học tập 6 phần: Khởi động, Hệ thống kiến thức, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng gồm:
1. Phản ứng tráng bạc của glucose (Bài 29, 4 bước).
2. Hồ tinh bột tác dụng với iodine (Bài 30, 3 bước).
3. Đông tụ và phân huỷ protein — 3 ống lòng trắng trứng (Bài 31).
4. Đốt phân biệt tơ tằm với tơ nylon (Bài 31).
5. Tính tan của PE, PVC, tinh bột trong nước lạnh/nước nóng (Bài 32, 6 ống).

Khóa đáp án trắc nghiệm: **1A 2D 3C 4A 5B 6C 7D 8C 9A 10B** (đã xáo vị trí phương án ở Câu 2 và Câu 7 so với khóa gốc PDF 1A 2B 3C 4A 5B 6C 7B 8C 9A 10B để cân bằng — khóa gốc không có câu nào đáp án D).

Châm ngôn: intro “Ôn lại những hợp chất của sự sống.” — outro “Hiểu hoá học trong cơ thể sống, em thêm yêu môn học này.”

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm hiện chỉ lưu trên máy học sinh (điểm cao nhất). Xem mục dưới.

## Trạng thái gửi điểm: CHỜ /exec

Bản này **CHƯA** có liên kết Web App Apps Script (registry chưa có webAppUrl cho khóa `hoa9-ontap-gkii`) nên file `index.html` **không** chứa code gửi điểm về Google Sheets. Khi có liên kết, bổ sung khối fetch vào hàm nộp bài (`doSubmit`) rồi giao lại. File `Code.gs` kèm theo đã sẵn sàng để gắn với Sheet kết quả.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_OnTap_GKII.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script Web App nhận điểm về Sheet (tab KetQua).
- `README.md` — file này.
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768) + logo thầy Lê Văn Thắng (PNG 500×500, nền trong suốt).
