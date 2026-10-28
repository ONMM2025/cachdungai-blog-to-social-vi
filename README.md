# Tái sử dụng bài blog thành nội dung mạng xã hội

> **Một repository, một skill.** Gói workflow độc lập bằng tiếng Việt để dùng với AI Agent.
>
> **Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)

## Giới thiệu

Chuyển bài blog tiếng Việt hoặc tài liệu dài thành nội dung riêng cho từng nền tảng mà vẫn giữ đúng dữ kiện và ý chính. Dùng khi phân phối bài đã xuất bản lên fan page Facebook và các kênh xã hội khác.

Skill nằm ở file `SKILL.md` ngay thư mục gốc. Mở file để xem đầy đủ phạm vi, đầu vào, quy trình, định dạng đầu ra, giới hạn và ví dụ.

## Cách cài

### Claude.ai

Nén repository này thành ZIP (hoặc tải ZIP của repository từ GitHub), rồi trong Claude mở mục **Skills / Customize → Upload a skill**. Bật skill sau khi tải lên. Tính năng custom Skills và code execution tùy thuộc gói tài khoản và cấu hình workspace.

### Claude Code

Chép `SKILL.md` vào `.claude/skills/blog-to-social-vi/SKILL.md` trong dự án, hoặc `~/.claude/skills/blog-to-social-vi/SKILL.md` để dùng cá nhân. Sau đó yêu cầu Claude dùng skill theo tên hoặc mô tả công việc.

### ChatGPT

Nếu tài khoản có mục **Skills**, chọn **Upload from your computer** và tải ZIP của repository này. Nếu chưa có mục Skills, mở `SKILL.md`, sao chép hướng dẫn vào Project instructions hoặc dán vào cuộc trò chuyện để dùng thủ công. Quyền sử dụng Skills trong ChatGPT phụ thuộc gói và thiết lập workspace.

### Codex

Chép `SKILL.md` vào `.agents/skills/blog-to-social-vi/SKILL.md` trong dự án, rồi yêu cầu Codex dùng skill này.

## Prompt mẫu

“Chuyển bài blog này thành 3 bài Facebook trong một tuần: một bài checklist, một bài kể tình huống người mới hay gặp và một bài dẫn về hướng dẫn đầy đủ. Không lặp caption; CTA đều về URL tôi đưa.”

Để có kết quả sát hơn, gửi thêm mục tiêu, độc giả, tài liệu đầu vào, kênh xuất bản và giới hạn cần giữ. Đọc lại dữ kiện và duyệt nội dung trước khi xuất bản; skill không tự đăng bài thay bạn.

## Giấy phép

MIT License — xem file `LICENSE` trong repository.

---

**Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)
