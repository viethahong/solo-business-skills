---
name: no-code-mvp
description: Xây dựng sản phẩm, công cụ nhanh nhất với No-code.
triggers:
  - build sản phẩm
  - làm MVP
  - dùng tool gì
  - không biết code
  - thuê dev hay tự làm
---

# 🚀 No-Code MVP — Ra sản phẩm nhanh nhất có thể

MVP không phải "sản phẩm chưa hoàn thiện". MVP là **sản phẩm ĐỦ để thu tiền sớm nhất**
và học được từ khách hàng thật. Xây nhanh, ra thị trường nhanh, học nhanh.

> **Triết lý Solopreneur:** Mua/dùng tool > Tự code từ đầu. Nếu có thể ghép 3 tool lại
> mà vẫn ra được sản phẩm hoạt động, đó là MVP hợp lệ.

---

## Framework thiết kế sản phẩm 3 tầng (ABC — Sellator)

Trước khi build, hãy xác định sản phẩm của bạn nằm ở tầng nào:

| Tầng | Mô tả | Giá | Ví dụ |
|---|---|---|---|
| **A (Alone)** | Sản phẩm tự phục vụ (self-serve), người dùng tự dùng | $9–$99/lần hoặc $9–$49/tháng | Template, plugin, SaaS nhỏ |
| **B (Beside)** | Coaching, tư vấn, hướng dẫn — bạn ở cạnh khách | $200–$2.000/tháng | Cohort course, mentoring |
| **C (Complete)** | Done-for-you — bạn làm toàn bộ cho khách | $2.000–$20.000/dự án | Agency, dịch vụ cao cấp |

> Gợi ý: Bắt đầu bằng **C** (bán dịch vụ thủ công) để hiểu khách hàng sâu nhất.
> Sau đó **productize** thành **B**, rồi cuối cùng tự động hóa thành **A**.

Chi tiết framework ABC: xem `references/abc-framework.md`

---

## Chọn công cụ theo loại sản phẩm

### Loại 1: Landing Page / Pre-sell / Directory
**Dùng khi**: Đang test ý tưởng, chỉ cần thu email, hoặc xây trang danh bạ.

| Công cụ | Tốt nhất cho | Chi phí |
|---|---|---|
| Carrd | Trang đơn giản, test nhanh | $0–$19/năm |
| Framer | Thiết kế đẹp, nhiều animation | $0–$25/tháng |
| Webflow | SEO mạnh, blog, CMS | $0–$23/tháng |
| Typedream | Nhanh nhất, Notion-like | $0–$15/tháng |

### Loại 2: App / Portal / Micro-SaaS
**Dùng khi**: Cần logic xử lý dữ liệu, user login, dashboard.

| Công cụ | Tốt nhất cho | Chi phí |
|---|---|---|
| **Softr + Airtable** | Đơn giản nhất, ra app trong 1 ngày | $0–$49/tháng |
| **Glide** | Biến Sheet thành app mobile | $0–$25/tháng |
| **Bubble** | Logic phức tạp, database riêng | $0–$29/tháng |
| **Pocketbase** | Dev cần backend mạnh, self-host | Miễn phí |

### Loại 3: Sản phẩm số (Course, Template, eBook)
**Dùng khi**: Bán kiến thức, template, hoặc nội dung có thể download.

| Công cụ | Tốt nhất cho | Chi phí |
|---|---|---|
| Gumroad | Nhanh nhất, phổ biến nhất | 10% fee |
| Lemon Squeezy | Stripe-like, tốt cho SaaS nhỏ | 5% fee |
| Whop | Cộng đồng + sản phẩm số | 3% fee |
| Podia / Teachable | Course có video | $33–$119/tháng |

### Loại 4: Bắt buộc phải code
**Dùng khi**: Logic quá phức tạp cho No-code (AI wrapper, Chrome Extension, API riêng).

- Dùng boilerplate (Shipfast, Supastarter, Makerkit) — tiết kiệm 40-80h setup
- BaaS: Supabase (database + auth), Stripe (payment), Resend (email)
- AI Coding: Claude Code, Cursor để tăng tốc 3-5x

---

## Concierge MVP — Giả lập trước, tự động hóa sau

Nếu mới có 1-10 khách hàng đầu tiên: **đừng build**. Hãy làm bằng tay và giả vờ
đã có hệ thống. Khi đủ 20-50 khách thì mới build tự động.

Ví dụ:
- "AI tự động tóm tắt email" → Thực ra bạn đang ngồi tóm tắt bằng ChatGPT và gửi thủ công
- "Dashboard phân tích dữ liệu" → Thực ra bạn đang làm Google Sheet và gửi PDF hàng tuần

Khách hàng không cần biết. Bạn cần học nhu cầu thật sự của họ.

---

## Related Skills
- Tự động hóa sau khi ra sản phẩm: `workflow-automation/`
- Phân phối sản phẩm: `personal-branding/`
