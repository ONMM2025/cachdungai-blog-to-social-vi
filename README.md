# Tái sử dụng bài blog thành nội dung mạng xã hội

> **Một repository, một skill.** Workflow độc lập bằng tiếng Việt cho AI Agent.
>
> **Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)

## Giới thiệu

Chuyển bài blog đã có thành nội dung Facebook, carousel hoặc brief video ngắn. Dùng để phân phối một nguồn; không dùng để soạn bài Facebook mới từ chủ đề.

Mở **SKILL.md** để xem đầu vào, quy trình, đầu ra, giới hạn và prompt mẫu. Gói cài đặt chứa SKILL.md và giấy phép MIT, không kèm script thực thi.

## Tải gói cài đặt

Tải ZIP sẵn dùng: [blog-to-social-vi.zip](blog-to-social-vi.zip). ZIP có thư mục gốc tên **blog-to-social-vi** và chứa **SKILL.md**, phù hợp để tải lên như một skill riêng.

## Cách cài

### Claude.ai

1. Nếu Skills chưa hiện, kiểm tra Settings > Capabilities và bật code execution nếu tài khoản/workspace hỗ trợ.
2. Mở **Customize > Skills**, bấm **+ > Create skill > Upload a skill**.
3. Chọn tệp **blog-to-social-vi.zip** vừa tải và bật skill sau khi upload.

Khả năng tạo và dùng skill phụ thuộc gói tài khoản, bật code execution và chính sách workspace.

### Claude Code

Chép **SKILL.md** vào **.claude/skills/blog-to-social-vi/SKILL.md** trong dự án hoặc **~/.claude/skills/blog-to-social-vi/SKILL.md** để dùng cá nhân. Gọi bằng **/blog-to-social-vi** hoặc mô tả yêu cầu để Claude tự chọn khi phù hợp.

### ChatGPT

Skills chỉ xuất hiện ở các tài khoản/workspace đủ điều kiện; hiện trang trợ giúp OpenAI nêu Business, Enterprise, Healthcare và Edu, tùy thiết lập workspace.

1. Mở **Plugins > Plugin Directory > Skills**.
2. Chọn **Create > Upload from your computer**.
3. Chọn **blog-to-social-vi.zip**.

Nếu không có mục Skills, mở **SKILL.md** rồi dán nội dung vào yêu cầu hoặc Project instructions nếu có. Đây là cách dùng thủ công, không phải cài skill tự động.

### Codex

Trong repo dự án, chép **SKILL.md** vào **.agents/skills/blog-to-social-vi/SKILL.md**, rồi yêu cầu Codex dùng skill này.

## Prompt mẫu

“Chuyển bài blog này thành 3 bài Facebook trong một tuần: một bài checklist, một bài kể tình huống người mới hay gặp và một bài dẫn về hướng dẫn đầy đủ. Không lặp caption; CTA đều về URL tôi đưa.”

Gửi thêm mục tiêu, độc giả, tài liệu đầu vào, nền tảng và giới hạn cần giữ để kết quả sát hơn. Kiểm tra dữ kiện và duyệt nội dung trước khi xuất bản.

## Giấy phép

MIT License — xem file **LICENSE** trong repository.

---

**Watermark:** [https://cachdungai.blog/](https://cachdungai.blog/)
