# FitPlan Studio – Trang Danh sách học viên

## Tên đề tài
FitPlan Studio (BTL-29) – website lập kế hoạch tập luyện và duy trì thói quen với 4 vai trò: người tập, huấn luyện viên, điều phối cộng đồng, quản trị viên.

## Trang đã thực hiện
**Danh sách học viên** (vai trò Huấn luyện viên).

## Mục đích
Giúp huấn luyện viên xem nhanh học viên mình phụ trách, tìm kiếm theo tên, xem lịch sử log tập và tóm tắt mức độ hoàn thành của từng người.

## Chức năng chính
- Render danh sách học viên từ mảng JavaScript.
- Tìm kiếm theo tên (không phân biệt hoa thường, có hoặc không dấu).
- Lọc theo mục tiêu: Giảm cân, Tăng cơ, Duy trì.
- Mở/đóng modal chi tiết: lịch sử log và tóm tắt AI theo luật (đóng bằng nút ×, phím Esc hoặc bấm ra ngoài).
- Hiển thị số kế hoạch đang chờ duyệt.
- Các trạng thái: đang tải, lỗi tải (bật bằng ô "Giả lập lỗi tải" ở chân trang), không có kết quả, không đủ dữ liệu.
- Responsive cho Desktop, Tablet và Mobile.

## Công nghệ sử dụng
HTML5 (semantic), CSS3 (Flexbox, Grid, Media Query), JavaScript thuần (DOM, Event). Không dùng framework.

## Cấu trúc thư mục
```
├── index.html
├── css/style.css
├── js/main.js
├── assets/
└── README.md
```

## Liên kết
- Figma: (dán link)
- Video: (dán link)
- GitHub: (dán link)
