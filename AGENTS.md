# AGENTS.md — Solopreneur Business Skills

Đây là bộ kỹ năng (skills) hỗ trợ Solopreneur được thiết kế để làm việc với mọi
AI Agent tương thích (Antigravity, OpenAI Codex, Cursor, Windsurf, v.v.)

## Giao thức thực thi (Execution Protocol)

Để đạt hiệu quả cao nhất, Agent phải tuân thủ quy trình sau:

1.  **Context First**: Luôn đọc `skills/solo-business-context/SKILL.md` trước tiên để nắm bắt bối cảnh của User (nguồn lực, mục tiêu).
2.  **Skill Mapping**: Xác định skill phù hợp nhất từ Skill Map bên dưới.
3.  **Step-by-Step**: Thực hiện theo đúng workflow trong file `SKILL.md`. Nếu thiếu thông tin từ User, hãy dừng lại và hỏi thay vì giả định.
4.  **Style Check**: Sử dụng phong cách `viet-viet` cho mọi nội dung truyền thông/viết lách.

## Skill Map

```
solo-business-context  (Đọc trước tiên — context nền tảng)
│
├── idea-validation          Kiểm chứng ý tưởng
├── solo-competitor-analysis Phân tích đối thủ, tìm ngách
├── no-code-mvp              Build sản phẩm nhanh
├── workflow-automation      Tự động hóa quy trình
├── personal-branding        Xây thương hiệu cá nhân
└── content-repurposing      Tái chế nội dung đa kênh
```

## Cài đặt

```bash
# Cách 1: Copy thẳng vào project
cp -r skills/ .agents/skills/

# Cách 2: Symlink (giữ nguyên khi update)
ln -s /path/to/solopreneur-business-skills/skills .agents/skills

# Cách 3: Git submodule
git submodule add https://github.com/viethahong/solo-business-skills .agents/solopreneur-skills
```

## Yêu cầu

- Agent phải có khả năng đọc file Markdown
- Không cần vector store hay embedding — skills đủ nhỏ để load vào context
- Tương thích: Claude Code, Antigravity, Cursor (via .cursorrules), Codex CLI, Windsurf
