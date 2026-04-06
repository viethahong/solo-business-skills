# Tham chiếu — Automation Blueprints
*Các mẫu luồng tự động hóa phổ biến cho Solopreneur*

---

## Blueprint 1: Onboarding khách hàng mới (SaaS / Course)

**Trigger:** Stripe / Gumroad nhận thanh toán thành công

```
Stripe (webhook: payment.succeeded)
  ↓
Make.com
  ├── Airtable: Tạo record khách hàng mới (tên, email, gói, ngày mua)
  ├── Resend/Gmail: Gửi email chào + link tài liệu / access
  ├── Slack/Telegram: Thông báo bạn có đơn mới (kèm tên, gói mua)
  └── ConvertKit: Thêm vào sequence email onboarding (5 email / 2 tuần)
```

---

## Blueprint 2: Lead Qualification tự động (Freelance / Agency)

**Trigger:** Khách điền Contact Form

```
Tally / Typeform (form submit)
  ↓
Make.com
  ├── OpenAI: Đọc câu trả lời, chấm điểm 1-10 dựa trên ICP criteria
  ├── Nếu điểm ≥ 7:
  │     ├── Gmail: Gửi email cảm ơn + link Calendly đặt lịch
  │     └── Notion/Airtable: Tag "Hot Lead", giao task follow-up
  └── Nếu điểm < 7:
        └── Gmail: Gửi email kèm tài liệu tự học, không mời call
```

---

## Blueprint 3: Content Pipeline (Newsletter + Social)

**Trigger:** Bài viết trong Notion đổi status → "Ready to Publish"

```
Notion (status changed to "Ready")
  ↓
Make.com
  ├── Typefully: Schedule Twitter thread (48h sau)
  ├── Buffer: Schedule LinkedIn post (24h sau)
  └── ConvertKit: Tạo draft newsletter từ tóm tắt bài viết
```

---

## Blueprint 4: Customer Support AI đầu tiên

**Setup một lần:** Không cần trigger tự động, là hệ thống thường trực

```
Chatbase / Crisp AI
  ↑ Học từ: FAQ page, documentation, product guide của bạn
  │
  ├── Xử lý 70-80% câu hỏi thường gặp tự động
  ├── Nếu câu hỏi phức tạp / khách yêu cầu người thật:
  │     └── Webhook → Telegram/Slack: Ping bạn với nội dung câu hỏi
  └── Tất cả conversations lưu vào Airtable để review hàng tuần
```

---

## Blueprint 5: Weekly Business Review tự động

**Trigger:** Mỗi thứ Hai 8h sáng (scheduled)

```
Make.com (scheduled trigger)
  ↓
  ├── Stripe API: Pull doanh thu tuần qua
  ├── ConvertKit API: Pull số subscriber mới, unsubscribe
  ├── Airtable: Pull số lead mới, lead đã chốt
  └── Gmail/Notion: Tổng hợp thành báo cáo 1 trang + gửi cho bạn
```
