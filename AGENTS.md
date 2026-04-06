# AGENTS.md — Solopreneur Business Skills

Đây là bộ kỹ năng (skills) hỗ trợ Solopreneur được thiết kế để làm việc với mọi
AI Agent tương thích (Antigravity, OpenAI Codex, Cursor, Windsurf, v.v.)

## Cách sử dụng

Mỗi skill nằm trong `skills/<tên-skill>/SKILL.md`. Khi cài vào dự án của bạn,
agent sẽ tự động tham chiếu skill phù hợp dựa trên yêu cầu của user.

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
