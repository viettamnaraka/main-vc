# Portfolio cá nhân – Nguyễn Viết Tâm

Website portfolio cá nhân giới thiệu Nguyễn Viết Tâm, sinh viên năm 3 ngành Công nghệ thông tin. Trang web trình bày thông tin cá nhân, thiết bị học tập, kỹ năng, ngoại ngữ và các kênh liên hệ.

## Nội dung

- Trang chủ với ảnh đại diện và lời giới thiệu ngắn.
- Phần giới thiệu bản thân.
- Danh sách thiết bị đang sử dụng: iPhone 14 Pro và Xiaomi Redmi 14S Pro Book.
- Kỹ năng: HTML, CSS, JavaScript và teamwork.
- Ngoại ngữ: IELTS 6.0 và HSK 3.
- Liên kết GitHub, Facebook và Zalo.
- Giao diện responsive cho máy tính, máy tính bảng và điện thoại.

## Công nghệ

- HTML5
- CSS3

Website không cần framework, JavaScript, bước build hay cài đặt thư viện.

## Cấu trúc dự án

```text
porf_nguyen_viet_tam/
├── index.html
├── style.css
└── images/
    ├── 14.webp
    ├── avatar.jpg
    ├── hsk.webp
    ├── iel.webp
    └── lap.webp
```

## Chạy website trên máy

1. Tải hoặc clone repository về máy.
2. Mở `index.html` bằng trình duyệt.

## Đưa website lên GitHub Pages

1. Tạo repository trên GitHub và tải các tệp của website lên.
2. Vào **Settings → Pages**.
3. Trong **Build and deployment**, chọn **Deploy from a branch**.
4. Chọn nhánh cần xuất bản (thường là `main`) và thư mục `/ (root)`, sau đó nhấn **Save**.
5. Mở URL GitHub Pages được hiển thị sau khi quá trình xuất bản hoàn tất.

Nếu các tệp website nằm trong thư mục con của repository, hãy chọn đúng thư mục chứa `index.html` hoặc chuyển nội dung website vào thư mục gốc.

## Hình ảnh

Các ảnh hiện có trong `images/` được trang sử dụng gồm `avatar.jpg`, `14.webp`, `lap.webp`, `iel.webp` và `hsk.webp`. Tên tệp và đường dẫn ảnh trong HTML/CSS phải khớp chính xác (kể cả chữ hoa, chữ thường) khi xuất bản.

**Lưu ý:** `index.html` đang tham chiếu `images/about.jpg`, còn `style.css` tham chiếu `images/background.jpg`. Hai tệp này hiện chưa có trong thư mục `images/`. Hãy thêm ảnh tương ứng trước khi xuất bản hoặc cập nhật đường dẫn trong mã nguồn. Nếu không có ảnh nền, lớp màu nền của trang chủ vẫn hiển thị.

## Tùy chỉnh

- Cập nhật nội dung, thông tin cá nhân và các URL mạng xã hội trong `index.html`.
- Thay ảnh trong `images/` và giữ nguyên tên tệp đang được tham chiếu, hoặc sửa đường dẫn tương ứng trong mã nguồn.
- Điều chỉnh màu sắc, bố cục và breakpoint responsive trong `style.css`.

## Giấy phép

Chưa khai báo giấy phép sử dụng. Hãy bổ sung tệp `LICENSE` nếu muốn quy định cách người khác sử dụng hoặc phân phối mã nguồn.
