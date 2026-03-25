# ⬛ QR Code Generator – Web Tĩnh

Web tĩnh tạo mã QR tùy chỉnh, chạy hoàn toàn trên trình duyệt, không cần server.

## Tính năng

- Nhập URL hoặc bất kỳ nội dung nào
- Chọn mức chịu lỗi (L / M / Q / H)
- Tùy chỉnh kích thước ảnh (px) và viền yên lặng
- Chọn màu QR và màu nền bằng color picker
- Xuất **PNG**, **JPG**, hoặc **SVG**
- Hỗ trợ **nền trong suốt** (PNG)
- Copy ảnh vào clipboard
- Giao diện dark mode, responsive

## 🚀 Deploy lên GitHub Pages (miễn phí)

### Bước 1: Đẩy code lên GitHub

```bash
git init
git add index.html README.md
git commit -m "Add QR code generator"
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

### Bước 2: Bật GitHub Pages

1. Vào repo trên GitHub → **Settings** → **Pages**
2. Phần **Source** chọn **Deploy from a branch**
3. Branch: `main`, Folder: `/ (root)` → **Save**
4. Sau ~1 phút, site sẽ live tại:
   ```
   https://<username>.github.io/<repo>/
   ```

## Chạy local

Chỉ cần mở `index.html` bằng trình duyệt, hoặc dùng Live Server trong VS Code.

## Công nghệ

- HTML + CSS + Vanilla JS (không framework)
- [qrcode.js](https://github.com/davidshimjs/qrcodejs) – tạo QR phía client
- Google Fonts (Inter)
