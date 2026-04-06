---
name: workflow-automation
description: Tự động hóa các quy trình lặp đi lặp lại.
triggers:
  - tự động hóa
  - dùng Zapier
  - Make
  - tiết kiệm thời gian
  - liên kết tool
---

# ⚙️ Workflow Automation — Làm ít, ra nhiều hơn

Với Solopreneur, thời gian là tài sản khan hiếm nhất. Rule of thumb: **nếu bạn làm
một việc quá 3 lần, lần thứ 4 phải để máy làm**.

> **Nguyên tắc:** Chuẩn hóa quy trình trước, tự động hóa sau.
> Đừng tự động hóa một quy trình vẫn còn lộn xộn — bạn sẽ chỉ tạo ra sự hỗn loạn nhanh hơn.

---

## Chọn công cụ tự động hóa

| Công cụ | Tốt nhất cho | Chi phí |
|---|---|---|
| **Make.com** | Logic phân nhánh phức tạp, giá tốt | $0–$29/tháng |
| **Zapier** | Đơn giản nhất, nhiều app tích hợp nhất | $0–$49/tháng |
| **n8n** | Toàn quyền kiểm soát, self-host miễn phí | $0 (self-host) |
| **Pabbly** | Giá rẻ, trả 1 lần | $249 lifetime |

Gợi ý cho beginner: Bắt đầu với **Make.com** — giao diện trực quan, đủ mạnh, giá hợp lý.

---

## Blueprint tự động hóa theo tình huống

### Tình huống 1: Onboarding khách hàng mới

**Vấn đề**: Mỗi khách mới phải gửi email chào, hướng dẫn, invoice thủ công.

**Blueprint:**
```
Stripe (thanh toán thành công)
  → Airtable (ghi record khách hàng mới)
  → Gmail/Resend (gửi email chào + tài liệu onboarding)
  → Slack/Telegram (thông báo bạn về đơn mới)
```

### Tình huống 2: Lead qualification tự động

**Vấn đề**: Mất nhiều thời gian đọc form, không biết ai đáng follow up.

**Blueprint:**
```
Tally/Typeform (khách điền form)
  → ChatGPT (đọc câu trả lời, chấm điểm 1-10)
  → Nếu ≥7 điểm: gửi link Calendly tự động
  → Nếu <7 điểm: gửi email tài liệu tự học
  → Airtable (lưu tất cả leads)
```

### Tình huống 3: Content pipeline tự động

**Vấn đề**: Muốn tự động lên lịch nội dung sau khi viết xong.

**Blueprint:**
```
Notion (viết bài xong, đổi status = "Ready")
  → Make (detect status change)
  → Buffer/Typefully (schedule post cho X/LinkedIn)
  → Email list (gửi newsletter bản tóm tắt)
```

### Tình huống 4: Customer support tối giản

**Vấn đề**: Câu hỏi lặp đi lặp lại, tốn thời gian trả lời.

**Blueprint:**
```
Chatbase/Crisp (AI bot trên website, học từ docs của bạn)
  → Xử lý 80% câu hỏi thường gặp tự động
  → Nếu cần escalate: gửi thông báo qua Telegram/Zalo
  → Bạn chỉ tiếp những case thực sự cần người thật
```

Xem thêm blueprint templates: `knowledge/frameworks/automation-blueprints.md`

---

## Cách thiết kế một luồng tự động hóa

Khi user mô tả quy trình muốn tự động hóa, AI hãy giúp xác định rõ:

1. **Trigger** (Tiền đề): Điều gì kích hoạt quy trình? (form submit, thanh toán, file mới, v.v.)
2. **Actions** (Hành động): Các bước xảy ra theo thứ tự là gì?
3. **Conditions** (Điều kiện): Có trường hợp ngoại lệ nào không?
4. **Destination** (Đích đến): Kết quả cuối cùng lưu/gửi ở đâu?

Sau khi xác định 4 yếu tố trên, vẽ blueprint dạng bullet points và đề xuất tool cụ thể.

---

## Related Skills
- Áp dụng automation cho content: `content-repurposing/`
- Kết hợp với sản phẩm No-code: `no-code-mvp/`
