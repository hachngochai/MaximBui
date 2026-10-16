# 🎂 Maxim Golden Birthday — Bùi Phạm Hoàng Minh

Một món quà sinh nhật 3D dành riêng cho **cốt Bùi Phạm Hoàng Minh**. Bản này phát triển từ concept Birthday VR V3, với **tông vàng chủ đạo**, hiệu ứng chạm nhân vật và khả năng chuyển **ngày ↔ đêm**.

## 🌐 View Demo

### ✨ [MỞ WEBSITE SINH NHẬT HOÀNG MINH](https://hachngochai.github.io/MaximBui/)

Link dự kiến: **https://hachngochai.github.io/MaximBui/**

> Nếu chưa mở được, vào **Settings → Pages** của repo → chọn **Deploy from a branch**, nhánh **main**, thư mục **/ (root)** → Save, rồi chờ GitHub Pages phát hành. Link sẽ hoạt động sau khi triển khai thành công.

## 🎨 Những điểm đặc biệt

- Áo chibi, quà, bánh sinh nhật, bóng bay và đảo nổi đều mang bảng màu **vàng – mật ong – kem**.
- **Nút ☀ NGÀY / ☾ ĐÊM** trên góc màn hình thay đổi bầu trời, sao, ánh sáng và mặt đất. Mặc định là ban ngày.
- **Chạm trực tiếp vào nhân vật**: hiện tên tiếng Trung **裴范煌明** (*Péi Fàn Huáng Míng*) trong bong bóng chữ 3D, nhân vật vẫy tay và có lời chào “Hello!” trên trình duyệt hỗ trợ phát giọng nói.
- Chữ **煌** trong tên là cách chọn mang ý nghĩa *huy hoàng, rực rỡ*; không phải xác nhận cách viết Hán tự pháp lý của tên.
- Nhãn nổi nhỏ gọn trên vật phẩm; giao diện desktop, mobile và góc nhìn 360°.
- Chạm vào bánh để cắm **5 cây nến**; thổi nến bằng micro (hoặc chạm thay thế nếu không cấp quyền), nghe giai điệu Happy Birthday rồi mở lá thư chúc mừng.
- Có hỗ trợ WebXR trên thiết bị tương thích.

## 🛠 Chạy ở máy cá nhân

Sử dụng Live Server (VS Code) hoặc:

```bash
python -m http.server 5500
```

Sau đó mở `http://localhost:5500/`. Cần kết nối internet để tải Three.js và Google Fonts.

## 🔒 Quyền micro

Micro chỉ được yêu cầu khi tới phần thổi nến. Dữ liệu âm thanh được phân tích ngay trên thiết bị để phát hiện một tín hiệu thổi, không gửi ghi âm lên máy chủ.

---

**Happy Birthday, cốt Hoàng Minh! 🌟**
