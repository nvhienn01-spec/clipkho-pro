# ClipKho Pro

Công cụ trên Windows để quét kênh TikTok, tìm video theo từ khóa, lọc theo ngày đăng / lượt xem / thích / bình luận / chia sẻ, và tải video hàng loạt.

## Tải về

Vào **[Releases → bản mới nhất](https://github.com/nvhienn01-spec/clipkho-pro/releases/latest)**, tải file `ClipKho_Pro_vX.Y.zip`, giải nén rồi chạy `ClipKho_Pro.exe`.

- Chạy được trên Windows 10/11 (64-bit). Không cần cài Python.
- Windows SmartScreen có thể hiện cảnh báo vì file chưa ký số. Bấm **Thông tin thêm → Vẫn chạy**.
- Hãy để file exe trong một thư mục riêng. Cấu hình, nhóm kênh và video tải về được lưu cạnh file exe.

## Tính năng chính

- **Tải theo kênh:** quét nhiều kênh cùng lúc, lọc theo ngày đăng, sắp xếp, chọn video bằng ảnh bìa rồi tải.
- **Nhóm kênh:** lưu các kênh hay dùng thành nhóm. Link video được tự đổi thành link kênh, kênh trùng được tự bỏ.
- **Tải theo link:** dán nhiều link video / ảnh, bấm Quét link để xem ảnh bìa, lượt xem, ngày đăng... như trang kênh, rồi tích chọn và tải.
- **Tìm theo từ khóa:** tìm video trên TikTok theo từ khóa, chọn khu vực / thời gian đăng, lọc theo lượt xem, thích, bình luận, chia sẻ (cần API key).
- **Cookie TikTok:** dán chuỗi cookie (dạng `ten=gia_tri; ...`) ở trang Cấu hình để yt-dlp quét / tải ít bị chặn, đỡ tốn lượt API.
- **Xuất Excel (.xlsx):** xuất danh sách video đã quét.
- **Quét lại khi lỗi:** kênh lỗi được thử lại bằng cách miễn phí trước, rồi mới dùng API key.
- **Tự cập nhật:** tool tự kiểm tra bản mới ở trang này khi mở. Bạn cũng có thể vào **Cấu hình → Cập nhật phần mềm → Kiểm tra cập nhật**.

## API key

Một số chức năng cần API key của dịch vụ tikwm. Nhập key ở **Cấu hình → API key**. Xem file `HUONG_DAN_SU_DUNG.txt` trong file zip để biết chi tiết.

## Cập nhật thủ công

Nếu tự cập nhật không chạy được, hãy tải file zip mới ở trang Releases, rồi chép `ClipKho_Pro.exe` mới đè lên file cũ. Cấu hình và video đã tải vẫn được giữ nguyên.

## Lưu ý

ClipKho Pro không liên kết với TikTok hay ByteDance. Bạn tự chịu trách nhiệm về việc dùng video đã tải và cần tôn trọng bản quyền của người sáng tạo nội dung.
