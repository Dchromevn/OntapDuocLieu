# Ôn tập Dược liệu
**Vào web:** https://dchromevn.github.io/OntapDuocLieu/

Web ôn tập nhận biết dược liệu, dùng được trên cả máy tính và điện thoại, không cần đăng nhập:

- **Thư viện**: tra cứu từng dược liệu (tên, tên khoa học, họ, bộ phận dùng, thành phần chính, công dụng, đặc điểm nhận dạng, ảnh), lọc theo họ và bộ phận dùng.
- **Flashcard**: chọn mặt trước là hình ảnh, tên hoặc đặc điểm nhận dạng, rồi lật thẻ xem đáp án. Có thể xáo trộn thẻ.
- **Kiểm tra tự luận**: nhìn ảnh dược liệu, tự gõ các mục rồi bấm **Kiểm tra** để so với đáp án.
- **Trắc nghiệm**: câu hỏi chọn đáp án, tạo ngẫu nhiên từ dữ liệu.

Ở chế độ kiểm tra, ảnh có nhãn ghi tên được ẩn đi để không lộ đáp án.

---

## Dành cho người quản lý

### Thêm hoặc sửa dược liệu

1. Mở web, vào tab **Quản lý dữ liệu**.
2. Đăng nhập: nhập **mật khẩu quản lý** do chủ kho cung cấp (mỗi máy chỉ cần làm một lần).
3. Bấm **Thêm dược liệu mới**, hoặc **Sửa** ở một cây có sẵn. Điền thông tin và chọn ảnh:
   - Ảnh đầu tiên nên là ảnh lọ có nhãn ghi tên, các ảnh sau là ảnh cận cảnh.
   - Ảnh được tự động thu nhỏ. Ảnh **HEIC** của iPhone cần đổi sang **JPG** trước.
4. Thêm hoặc sửa xong thì bấm **Đăng lên web**. Khoảng 1–2 phút sau, mọi người tải lại trang sẽ thấy.

Có thể quản lý từ nhiều máy cùng lúc: khi đăng, web chỉ cập nhật những cây đã sửa trên máy đó, không ghi đè thay đổi từ máy khác. Dùng máy chung thì nhớ bấm **Đăng xuất trên máy này** sau khi xong.

### Sao lưu

Ở cuối tab **Quản lý dữ liệu**:
- **Tải bản sao lưu (.json)**: lưu toàn bộ dữ liệu về máy.
- **Nạp từ file sao lưu**: thay *toàn bộ* dữ liệu bằng file đã lưu (sau đó bấm **Đăng lên web**).

---

## Cấu trúc thư mục

| Đường dẫn | Nội dung |
|---|---|
| `index.html` | Toàn bộ trang web |
| `data/plants.json` | Dữ liệu dược liệu |
| `data/plants.js` | Bản dữ liệu nhúng, dùng khi mở `index.html` trực tiếp trên máy, không qua mạng |
| `data/admin.json` | Thông tin đăng nhập quản lý đã được mã hóa |
| `images/` | Ảnh dược liệu |
