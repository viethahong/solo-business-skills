# 🦸 Solopreneur Business Skills

> Bộ AI Skills có thể giúp bạn — người làm chủ doanh nghiệp một mình — có một Co-founder ảo
> hiểu rõ giới hạn nguồn lực và luôn gợi ý giải pháp thực tế, tinh gọn, có thể tự động hóa.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **Được xây dựng từ 13+ năm kinh nghiệm thực chiến của [Hạ Hồng Việt — Founder Sellator](https://hahongviet.com)**,
> tích hợp Sellator Knowledge System vào từng workflow.

---

## Đây là gì?

**Solopreneur Business Skills** là thư viện các file hướng dẫn (Markdown) dành cho AI Agent.
Khi tích hợp vào dự án, AI sẽ có khả năng:

- Hiểu bạn đang kinh doanh theo mô hình nào và giới hạn nguồn lực là bao nhiêu
- Áp dụng đúng framework theo từng tình huống (không gượng ép, không dàn trải)
- Ưu tiên giải pháp tinh gọn, tự động hóa được, phù hợp làm một mình

---

## 🧠 Skills có sẵn (Bản đồ 21 Kỹ năng V3)

| Skill | Kích hoạt khi nào | Framework tích hợp |
|---|---|---|
| **🔍 Khám phá & Định hướng** | | |
| `solo-health-check` | ⭐ **Meta-skill:** Tự định vị dự án đang ở giai đoạn nào | 4-Stage Roadmap |
| `solo-business-context` | **Khởi tạo:** Khai báo bối cảnh dự án | GAMES (Sellator) |
| `customer-research` | Nghiên cứu khách hàng mục tiêu | BUY + VALUE (Sellator) |
| `idea-validation` | Test ý tưởng trước khi triển khai sản phẩm | BUY (Sellator) |
| `solo-competitor-analysis` | Tìm ngách, phân tích đối thủ | RARE (Sellator) |
| **📦 Thiết kế sản phẩm** | | |
| `product-model` | Thiết kế mô hình sản phẩm và dịch vụ | ABC + GAMES |
| `no-code-mvp` | Xây sản phẩm/dịch vụ với nguồn lực tối thiểu | ABC (Sellator) |
| **🚀 Ra mắt & Bán hàng** | | |
| `launch-strategy` | Chiến lược ra mắt sản phẩm mới | GAMES + FOMO |
| `sales-script` | Kịch bản bán hàng và thuyết phục | BUY + VALUE + FOMO + 5T |
| `freelance-proposal` | Viết Proposal/báo giá không thể từ chối | Grand Slam Offer, UỒI |
| **📣 Truyền thông & Nội dung** | | |
| `personal-branding` | Xây thương hiệu cá nhân trên social | 4T (Sellator) |
| `media-channel` | Xây kênh truyền thông bền vững | — |
| `content-creation` | Sáng tạo nội dung thu hút khách hàng | 5T + VALUE + 5E |
| `content-repurposing` | Biến 1 bài thành nội dung cho 5 kênh | 5T + VALUE + 5E (Sellator) |
| `email-newsletter` | Xây dựng và duy trì Email List | Volume, 5E |
| **⚙️ Vận hành & Nâng cao** | | |
| `workflow-automation` | Tự động hóa việc lặp đi lặp lại | — |
| `solo-finance` | Quản lý dòng tiền, định mức Runway | Value Equation |
| `customer-onboarding` | Đón tiếp khách mới, xoá bỏ hoài nghi | VALUE |
| `retention` | Giữ chân khách hàng, giảm Churn | VALUE, ABC |
| `referral-program` | Thiết kế hệ thống mạng lưới giới thiệu | Double-sided Incentive |
| `solo-productivity` | Quản trị năng lượng, chống Burn-out | Eliminate - Automate - Delegate |
| `decision-making` | Mental model tự ra quyết định | Expected Value, Inversion |

### Cấu trúc mỗi Skill & Hệ thống Knowledge

```
solopreneur-business-skills/
├── knowledge/                ← [MỚI] Trung tâm dữ liệu dự án
│   ├── frameworks/           ← Tổng hợp các Framework của Sellator & Hormozi
│   ├── macro/                ← Dữ liệu vĩ mô
│   ├── micro/                ← Dữ liệu vi mô/ngách
│   └── personal/             ← Dữ liệu cá nhân (đã được .gitignore)
└── skills/<tên-skill>/
    ├── SKILL.md              ← AI đọc file này — quy trình và hướng dẫn
    └── examples/
        └── checklist.md      ← Checklist & Ví dụ để bạn tự kiểm tra AI
```

---

## ⚡ Cài đặt

### Dùng với Claude Code

```bash
# Clone repo
git clone https://github.com/viethahong/solo-business-skills.git

# Copy vào project của bạn
cp -r solo-business-skills/skills .claude/skills/
```

Hoặc nếu dùng chuẩn `.agents/`:

```bash
cp -r solo-business-skills/skills .agents/skills/
```

> Claude Code tự đọc `CLAUDE.md` ở root — không cần config thêm.

### Dùng với Antigravity (Antigravity AI)

```bash
cp -r solo-business-skills/skills .agents/skills/
```

> Antigravity tự đọc `AGENTS.md` ở root.

### Dùng với Cursor

Thêm vào `.cursorrules` của bạn:

```
When helping with business decisions, read the skill files in skills/ directory.
Start with skills/solo-business-context/SKILL.md for context about my project.
```

### Dùng với OpenAI Codex CLI

```bash
cp -r solo-business-skills/skills .agents/skills/
```

> Codex CLI tự đọc `AGENTS.md` ở root.

### Dùng với Windsurf

Thêm đường dẫn skills vào Windsurf Rules hoặc project instructions của bạn.

---

## 🗺 Cách các Skill liên kết

```
solo-business-context  ← Đọc trước tiên
│
├── idea-validation ──────────► solo-competitor-analysis
│         │
│         ▼
│   no-code-mvp ──────────────► workflow-automation
│
└── personal-branding ────────► content-repurposing
```

---

## 💬 Ví dụ câu lệnh

```bash
# Kiểm chứng ý tưởng
"Dùng kỹ năng idea-validation, giúp tôi test ý tưởng làm app quản lý kho cho tiệm tạp hóa"

# Xây thương hiệu
"Dùng personal-branding, phân tích thương hiệu cá nhân của tôi và lên lịch content 1 tháng"

# Tìm ngách
"Tôi muốn làm SaaS về kế toán, dùng solo-competitor-analysis tìm ngách cho tôi"

# Tái chế nội dung
"Đây là bài blog của tôi [paste nội dung], dùng content-repurposing tạo thread Twitter và LinkedIn post"
```

---

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón! Xem `CONTRIBUTING.md` để biết cấu trúc chuẩn của một skill.

**Skill đang mở rộng thêm:**
- Nếu bạn có ý tưởng skill mới, hãy Submit Issue hoặc Pull Request trên GitHub.

---

## 📄 Giấy phép

MIT License — Xem [LICENSE](LICENSE) để biết thêm.

---

*Xây dựng từ tri thức của [Hạ Hồng Việt — Sellator](https://sellator.net) · Dành cho cộng đồng Solopreneur Việt Nam* 🇻🇳
