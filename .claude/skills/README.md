# YouTube Strategy Thinking Partner (Tiếng Việt)

Bộ skill làm việc với AI dựa trên transcript Jake Trinder được người dùng cung cấp. Mục tiêu: **hỏi đáp + brainstorming + phản biện chiến lược YouTube**, không chỉ sinh ý tưởng.

## Cài đặt

**Claude Code (cấu trúc skill):** sao chép toàn bộ thư mục `youtube-strategy-thinking-partner` vào `~/.claude/skills/` hoặc `.claude/skills/` của project. Sau đó nhờ Claude "Dùng skill youtube-strategy-thinking-partner để brainstorm...". Tùy phiên bản/giao diện, cách khám phá skill có thể khác nhau.

**Môi trường hỗ trợ skills kiểu `SKILL.md`:** đặt nguyên thư mục trong khu vực skills tương ứng và để công cụ đọc `SKILL.md`. Kiểm tra hướng dẫn của môi trường cụ thể.

**ChatGPT chat thông thường:** không phải mọi giao diện hỗ trợ cài skill trực tiếp. Có thể tải `SKILL.md` + `references/` vào Project hoặc GPT tùy tính năng bạn có và hướng dẫn AI dùng theo nội dung file. Đây là cách dùng như knowledge/instructions, không đồng nghĩa đã cài skill ở cấp nền tảng.

## Dùng nhanh

- `/ask Vì sao biết khách hàng cần nội dung không có nghĩa họ muốn xem?`
- `/brainstorm Tôi bán dịch vụ kế toán cho SME, hãy tìm 3 hướng nội dung có thể thu hút khách hàng.`
- `/critic Phản biện video: 10 công cụ AI thay thế nhân viên.`
- `/validate Kiểm tra nhu cầu cho ngách quản trị dòng tiền doanh nghiệp.`
- `/package Đóng gói ý tưởng: giảm 50% thời gian xử lý đơn hàng (có case thật).`
- `/review Đây là các số liệu 5 video gần đây...`

## Nội dung

- `SKILL.md`: chỉ thị vận hành chính.
- `references/`: kiến thức tóm tắt và transcript gốc.
- `workflows/`: 6 chế độ thao tác.
- `templates/`: scorecard, CSV nghiên cứu và video brief.
- `examples/`: mẫu đối thoại.

## Nguyên tắc nguồn

Các case study và doanh thu trong transcript là lời tự thuật của diễn giả, chưa được xác minh độc lập. Skill buộc AI phân biệt chứng cứ thực và giả thuyết; nếu không có truy cập web/YouTube thì chỉ lập phương án nghiên cứu, không được nói đã xác minh.
