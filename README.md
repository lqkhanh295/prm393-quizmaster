# 📱 PRM393 QuizMaster — Ôn Thi Lập Trình Di Động (FTES Bank)

Ứng dụng web ôn thi trắc nghiệm môn **PRM393 — Lập trình di động (Flutter / Dart)** phong cách Quizlet, tích hợp ngân hàng 116 câu hỏi độc nhất đã chuẩn hóa từ 5 bộ đề ôn tập trên nền tảng **FTES (FPT Training & Examination System - AI Learning)**.

🌐 **Trải nghiệm trực tiếp trên Web:** [https://lqkhanh295.github.io/prm393-quizmaster/](https://lqkhanh295.github.io/prm393-quizmaster/)

---

## ✨ Tính Năng Nổi Bật

### 1. 🎯 Thi Thử 50 Câu (Mock Exam)
- **Thuật toán trộn ngẫu nhiên:** Tự động lấy ngẫu nhiên 50 câu hỏi từ kho 116 câu chuẩn, không trùng lặp trong cùng một đề thi.
- **Tính giờ chuẩn 50 phút:** Đồng hồ đếm ngược, cảnh báo khi sắp hết giờ.
- **💡 Chế độ học tập (Hiện giải thích ngay):** Bật/Tắt tùy biến. Khi bật, vừa chọn đáp án sẽ lập tức hiển thị Đúng/Sai kèm hộp giải thích chi tiết bản chất câu hỏi.
- **Lưới điều hướng 50 câu (Palette):** Xem nhanh câu đã làm, câu chưa làm, đánh dấu cờ xem lại (Flag).
- **Phím tắt tiện lợi:** Bấm phím 1, 2, 3, 4 tương ứng để chọn A, B, C, D; phím F để gắn cờ.
- **Bảng điểm & Phân tích chi tiết:** Chấm điểm, quy đổi thang 10, hiển thị đánh giá ĐẠT/CHƯA ĐẠT và hỗ trợ lọc chỉ xem lại các câu bị sai.

### 2. 🃏 Thẻ Ghi Nhớ Flashcards 3D (Quizlet Style)
- Hiệu ứng lật thẻ 3D mượt mà.
- Phím tắt bàn phím: Phím Space để lật thẻ, phím ← / → để chuyển câu.
- Đánh dấu trạng thái **Đã thuộc** / **Chưa thuộc** và nút **Trộn thẻ (Shuffle)** ngẫu nhiên.

### 3. ⚡ Luyện Tập Từng Câu (Practice Mode)
- Trả lời từng câu với phản hồi và giải thích tức thì.

### 4. 📚 Ngân Hàng Đề & Tra Cứu (Question Bank)
- Tra cứu nhanh câu hỏi theo từ khóa (vd: jwt, loc, state, widget...).
- Lọc theo chuyên đề: *State Management, Flutter UI, Dart Basics, Network & Auth, Data & Storage, Testing, Architecture...*

---

## 📂 Cấu Trúc Dự Án

`
prm393-quizmaster/
├── index.html                   # Ứng dụng web Single-Page Application (HTML + Tailwind CSS + Vanilla JS)
├── PRM393_116_Cau_Unique.md     # Ngân hàng 116 câu hỏi duy nhất (kèm đáp án chuẩn và giải thích chi tiết)
├── PRM393_5_De_On_Tap.md        # Toàn bộ 250 câu hỏi từ 5 bộ đề gốc trên FTES
└── README.md                    # Tài liệu hướng dẫn sử dụng
`

---

## 🚀 Chạy Cục Bộ (Local)

Chỉ cần mở trực tiếp file index.html bằng bất kỳ trình duyệt nào (Chrome, Edge, Firefox, Safari) mà không cần cài đặt thêm bất kỳ môi trường hay máy chủ backend nào.

---

## 🎓 Bản Quyền & Nguồn Dữ Liệu
- Dữ liệu trích xuất từ các bộ đề thi thử kỳ SP26 & SU26 môn PRM393 trên FTES.
- Đáp án tham khảo được cung cấp bởi hệ thống FrosTES.