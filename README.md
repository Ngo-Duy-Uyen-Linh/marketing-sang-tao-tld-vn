<!-- TẠO TỰ ĐỘNG bằng dong-bo.cjs từ marketing-skills-tld-vn. Không sửa ở đây. -->
# marketing-sang-tao-tld-vn: Marketing: sáng tạo nội dung

Bản 0.6.1. Hỗ trợ tổ chức viết và chấm câu mở đầu, viết kịch bản video ngắn, bài đăng mạng xã hội, kịch bản livestream, ảnh trích dẫn, tiêu đề và ảnh bìa, cắt video dài thành video ngắn, viết tự nhiên không giọng văn máy, dựng giọng văn của tổ chức từ bài thật.

Gói này là một vai trong bộ **Marketing-skills-tld-vn**, tách riêng để nhân sự AI chỉ nạp kỹ năng của đúng vai mình, đỡ tốn chi phí mỗi lượt chạy. Dùng được trong Claude Code và nạp được vào hệ thống quản trị Thế Là Được.

## Kỹ năng
- `viet-cau-mo-dau`
- `cham-cau-mo-dau`
- `viet-kich-ban-video-ngan`
- `viet-bai-dang-mang-xa-hoi`
- `cat-video-dai-thanh-video-ngan`
- `tieu-de-va-anh-bia`
- `viet-anh-trich-dan`
- `kich-ban-livestream`
- `bo-giong-van-may`
- `dung-giong-van-thuong-hieu`

## Các vai khác của bộ
- `marketing-nghien-cuu-tld-vn`: nghiên cứu và kế hoạch
- `marketing-giu-quy-tac-tld-vn`: giữ quy tắc nội dung
- `marketing-binh-luan-tld-vn`: trả lời bình luận và xử lý sự cố

## Cấu trúc
```
quy-tac-chung.md        quy tắc mọi kỹ năng làm theo
skills/<tên>/SKILL.md   kỹ năng (dạng Claude Code)
ky-nang/<tên>/SKILL.md  bản cho hệ thống quản trị
goi.json, vai-tro.md    tệp cho hệ thống quản trị
bai-kiem-tra/           tình huống kiểm tra vào việc của vai này
tai-lieu-to-chuc/       tệp mẫu để tổ chức điền rồi nạp vào kho tri thức
```

Mọi tệp trong gói được sinh tự động từ bản gốc; sửa ở bản gốc. Nguồn tham khảo và giấy phép: `NOTICE.md`.
