# Hướng dẫn Đóng góp (Contributing Guide)

Cảm ơn bạn đã muốn đóng góp cho **Solopreneur Business Skills**! 🙌

## Quy tắc chung

- Nội dung phải thực tế, dựa trên kinh nghiệm thực chiến (không viết lý thuyết chung chung).
- Ngôn ngữ viết: Tiếng Việt (ưu tiên) hoặc Tiếng Anh.
- Mỗi kỹ năng phải là một bài hướng dẫn hành động (action-oriented), không phải bài blog.

## Cấu trúc một file Kỹ năng chuẩn

Tạo file mới trong thư mục `skills/` theo mẫu sau:

```markdown
---
description: Mô tả ngắn gọn về kỹ năng này, dành cho AI đọc.
---

# 🎯 Tên Kỹ năng

Đoạn mô tả giải thích tại sao kỹ năng này quan trọng với Solopreneur.
Giải thích ngắn gọn AI sẽ làm gì khi kỹ năng này được kích hoạt.

## Nguyên tắc cốt lõi
(2-3 nguyên tắc hướng dẫn tư duy)

## Workflow (Các bước thực hiện)

### Bước 1: ...
### Bước 2: ...

## Ví dụ thực tế / Tình huống mẫu
(Ví dụ khi nào và làm gì cụ thể)

## Tool Stack gợi ý (nếu có)
(Các công cụ miễn phí / giá rẻ phù hợp Solopreneur)

## Related Skills
- Kỹ năng liên quan 1: `tên-file.md`
- Kỹ năng liên quan 2: `tên-file.md`
```

## Quy trình gửi Pull Request

1. **Fork** repository này về tài khoản GitHub của bạn.
2. **Clone** fork đó về máy tính.
3. Tạo **branch** mới: `git checkout -b feat/ten-ky-nang-moi`
4. Tạo file kỹ năng mới trong `skills/` theo cấu trúc chuẩn ở trên.
5. **Commit**: `git commit -m "feat: thêm kỹ năng [tên kỹ năng]"`
6. **Push** lên fork của bạn và mở **Pull Request**.

## Ý tưởng kỹ năng đang cần

Những kỹ năng sau đây đang được cộng đồng mong đợi:

- [ ] `solo-finance.md` — Quản lý dòng tiền, thuế, và Pricing cho Solopreneur
- [ ] `email-newsletter.md` — Xây dựng danh sách email từ đầu
- [ ] `freelance-pitching.md` — Viết Proposal thuyết phục khách hàng cao cấp
- [ ] `launch-strategy.md` — Kịch bản ra mắt sản phẩm trên Product Hunt, Reddit
- [ ] `outsourcing.md` — Khi nào và cách nào thuê Freelancer đầu tiên

Nếu bạn thấy ý tưởng nào phù hợp với kinh nghiệm của mình, hãy bắt đầu từ đó!
