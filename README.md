# GrandTakeClothing

Công cụ quản lý, dựng và chụp ảnh quần áo addon cho **GTA V / FiveM**.

Repo này chỉ chứa **file phát hành** (bản build sẵn). Tải bản mới nhất ở mục
[**Releases**](https://github.com/cobeometri/GrandTakeClothing/releases/latest).

---

## Cài đặt

1. Vào [Releases](https://github.com/cobeometri/GrandTakeClothing/releases/latest), tải `GrandTakeClothing.zip`.
2. Giải nén ra một thư mục riêng (đừng để trong `Downloads` hay `Desktop` chung với file khác).
3. Chạy `GrandTakeClothing.exe`.

Bản build đã kèm sẵn .NET runtime, không cần cài thêm gì.

---

## Tự cập nhật

Tool tự hỏi GitHub xem có bản mới không mỗi lần khởi động.
Muốn kiểm tra thủ công thì bấm vào **số phiên bản** ở góc phải thanh tiêu đề.

Khi có bản mới, tool sẽ tải về, thay file rồi tự khởi động lại — không cần cài đè bằng tay.

### Đổi nguồn cập nhật (tuỳ chọn)

Nếu muốn lấy bản cập nhật từ repo khác mà không phải build lại, tạo file
`update.json` đặt cạnh `GrandTakeClothing.exe`:

```json
{
  "owner": "cobeometri",
  "repo": "GrandTakeClothing",
  "token": ""
}
```

Repo công khai thì để trống `token`.

---

## Tính năng chính

- Quản lý nhiều project quần áo addon, gộp/tách addon, kiểm tra trùng lặp.
- Xem trước 3D trực tiếp trên nhân vật nam/nữ.
- **Xưởng texture**: vẽ, tô, dán ảnh, ghép layer lên texture và xem kết quả ngay trên model 3D.
- Chụp ảnh hàng loạt cho `ox_inventory` theo `clothingmap.json`.
- Xuất project ra `.rpf` / stream dùng luôn trong FiveM.

---

## Ghi chú

Bản này được Việt hoá và đổi thương hiệu riêng, phát triển trên nền
[grzyClothTool](https://github.com/grzybeek/grzyClothTool) của grzybeek — cảm ơn tác giả gốc.
