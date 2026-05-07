# CLAUDE.md — Solopreneur Business Skills

Đây là bộ kỹ năng (skills) dành cho Solopreneur. Khi người dùng làm việc với bạn trong
dự án này, hãy tham chiếu các skill phù hợp trong thư mục `skills/`.

## Cách đọc Skills

Mỗi skill là một thư mục có cấu trúc:
```
skills/<tên-skill>/
├── SKILL.md          ← Đọc file này để hiểu quy trình
├── evals/            ← Checklist kiểm tra chất lượng
│   └── test-cases.md
└── references/       ← Tài liệu phụ, frameworks chi tiết
    └── *.md
```

## Skills có sẵn

| Tên skill | Kích hoạt khi nào |
|---|---|
| `solo-business-context` | **Luôn đọc trước tiên** — context về dự án của user |
| `idea-validation` | User muốn test ý tưởng mới |
| `solo-competitor-analysis` | User hỏi về đối thủ hoặc tìm ngách |
| `no-code-mvp` | User muốn build sản phẩm / tool |
| `workflow-automation` | User muốn tự động hóa quy trình |
| `personal-branding` | User muốn xây thương hiệu cá nhân |
| `content-repurposing` | User muốn tạo / tái chế nội dung |

## Nguyên tắc hoạt động (System Rules)

1.  **State Awareness**: Luôn đọc `solo-business-context/SKILL.md` trước khi chạy bất kỳ skill nào. Nếu thông tin trong đó bị trống `[...]`, hãy nhắc user điền vào.
2.  **Explicit Thinking**: Trước khi thực thi, hãy tóm tắt: "Tôi đang dùng skill [X] để giải quyết [Y]. Bối cảnh hiện tại của bạn là [Z]".
3.  **Strict Adherence**: Tuân thủ tuyệt đối các framework được chỉ định (BUY, GAMES, 5T, VALUE).
4.  **No Placeholders**: Không tạo nội dung chung chung. Nếu cần ví dụ, hãy dùng chính bối cảnh của user.
5.  **Viet-Viet Tone**: Mọi bài đăng Facebook, email, blog phải dùng phong cách `viet-viet` (câu ngắn, hook mạnh, tư duy phản biện).

## Quy chuẩn đầu ra (Output Standards)

- **Chiến lược**: Trình bày dạng bảng hoặc bullet points rõ ràng.
- **Quy trình**: Luôn có sơ đồ Mermaid minh họa.
- **Nội dung**: Phải bao gồm cả Hook (5T) và Body (VALUE).
- **Tooling**: Đề xuất công cụ cụ thể (Make, Zapier, Carrd) thay vì nói chung chung.
