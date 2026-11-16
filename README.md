# Ôn tập Dược liệu

Web ôn tập dược liệu: thư viện, flashcard, kiểm tra tự luận, trắc nghiệm.

- Dữ liệu: `data/plants.json`
- Ảnh: thư mục `images/`

## Người quản lý: thêm dược liệu mới mỗi tuần

1. Mở web → tab **Quản lý dữ liệu**.
2. Bấm **Thêm dược liệu mới**, điền thông tin, chọn ảnh (ảnh đầu tiên nên là ảnh lọ có nhãn, các ảnh sau là ảnh cận cảnh).
3. Thêm xong tất cả → bấm **Đăng lên web**. Khoảng 1–2 phút sau mọi người tải lại trang là thấy.

## Kết nối GitHub (làm 1 lần trên mỗi máy dùng để quản lý)

1. Vào https://github.com/settings/personal-access-tokens/new
2. **Token name**: `on-duoc-lieu` — **Expiration**: chọn thời hạn dài (ví dụ 1 năm).
3. **Repository access** → *Only select repositories* → chọn kho `on-duoc-lieu`.
4. **Permissions** → *Repository permissions* → **Contents: Read and write**.
5. Bấm **Generate token**, sao chép mã (bắt đầu bằng `github_pat_...`).
6. Trên web, tab **Quản lý dữ liệu** → mục **Kết nối GitHub** → dán mã → **Kiểm tra kết nối**.

Mã chỉ lưu trên trình duyệt của máy đó, không nằm trong mã nguồn. Không gửi mã này cho người khác.
