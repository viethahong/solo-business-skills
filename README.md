# 🦸 Solopreneur Business Skills

> AI Skills giúp bạn — một người làm chủ doanh nghiệp độc lập — kiểm chứng ý tưởng, xây sản phẩm, tự động hóa công việc và phát triển mà không cần đội ngũ lớn.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Đây là gì?

**Solopreneur Business Skills** là một thư viện các file hướng dẫn (Markdown) dành cho các AI Agent như Claude, Cursor, Windsurf, GitHub Copilot, v.v.

Khi tích hợp bộ kỹ năng này vào dự án của bạn, AI sẽ hoạt động giống như một **Co-founder ảo** — hiểu rõ những giới hạn về thời gian và tiền bạc của bạn — và luôn gợi ý những giải pháp **thực tế, tinh gọn, có khả năng tự động hóa cao**.

Bộ kỹ năng này lấy cảm hứng từ kiến trúc của [marketingskills](https://github.com/coreyhaines31/marketingskills), và được tái thiết kế hoàn toàn theo góc nhìn của người kinh doanh một mình (Solopreneur).

---

## 🧠 Các kỹ năng có sẵn

Mỗi file trong thư mục `skills/` là một "kỹ năng" độc lập được AI đọc khi bạn ra lệnh.

| Tên File | Mô tả | Dành cho giai đoạn |
|---|---|---|
| `solo-business-context.md` | **Bắt đầu ở đây.** Khai báo thông tin dự án, giới hạn nguồn lực cho AI | Tất cả giai đoạn |
| `idea-validation.md` | Kiểm chứng ý tưởng bằng Landing Page & khảo sát — trước khi code | Ý tưởng |
| `solo-competitor-analysis.md` | Phân tích đối thủ và tìm Ngách nhỏ không ai đụng tới | Ý tưởng & Chiến lược |
| `no-code-mvp.md` | Xây dựng sản phẩm tối giản bằng công cụ No-code / Low-code | Xây dựng |
| `workflow-automation.md` | Thiết kế luồng tự động hóa bằng Make, Zapier, n8n | Vận hành |
| `personal-branding.md` | Xây thương hiệu cá nhân trên X (Twitter) và LinkedIn | Phát triển |
| `content-repurposing.md` | Biến 1 bài viết thành nội dung cho 5 nền tảng | Phát triển |

> Mỗi kỹ năng đều có mục **Related Skills** để liên kết tuần tự và logic.

---

## ⚡ Cài đặt & Sử dụng

**Bước 1: Clone repo về máy**

```bash
git clone https://github.com/<username>/solopreneur-business-skills.git
```

**Bước 2: Sao chép thư mục `skills/` vào dự án của bạn**

```bash
# Dành cho Claude Code (hoặc agent tương thích)
cp -r solopreneur-business-skills/skills .agents/skills/

# Hoặc đặt vào thư mục .claude
cp -r solopreneur-business-skills/skills .claude/skills/
```

**Bước 3: Cấu hình bối cảnh của bạn**

Mở file `.agents/skills/solo-business-context.md` và **điền các thông tin thật của dự án bạn** vào các ô được đánh dấu `[...]`.

**Bước 4: Ra lệnh cho AI**

Mở Claude Code, Cursor, hoặc AI Agent bất kỳ, rồi dùng câu lệnh:

```
Hãy sử dụng kỹ năng idea-validation và solo-business-context,
kiểm chứng giúp tôi ý tưởng làm ứng dụng quản lý kho hàng
dành cho các tiệm tạp hóa nhỏ lẻ.
```

---

## 🗺 Cách các kỹ năng liên kết với nhau

```
solo-business-context (Đọc trước tiên)
│
├── idea-validation ──────────► solo-competitor-analysis
│         │
│         ▼
│   no-code-mvp ──────────────► workflow-automation
│
└── personal-branding ────────► content-repurposing
```

---

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón!

Nếu bạn có một kỹ năng mới muốn thêm vào (ví dụ: `solo-finance.md`, `freelance-pricing.md`, `email-newsletter.md`), hãy:

1. Fork repo này
2. Tạo file theo cấu trúc mẫu trong `CONTRIBUTING.md`
3. Mở một Pull Request

---

## 📄 Giấy phép

MIT License — Xem file [LICENSE](LICENSE) để biết thêm chi tiết.

---

*Được xây dựng với ❤️ dành cho cộng đồng Solopreneur Việt Nam.*
