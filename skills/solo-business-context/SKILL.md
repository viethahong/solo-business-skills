---
name: solo-business-context
description: >
  Khai báo bối cảnh kinh doanh của người dùng. Đây là file nền tảng — tất cả các skill khác
  phải đọc file này trước khi hành động. Kích hoạt kỹ năng này khi user muốn thiết lập
  thông tin dự án, hoặc khi bất kỳ skill nào khác cần context về nguồn lực và mô hình
  kinh doanh của user.
metadata:
  version: 1.0.0
  author: Hạ Hồng Việt — Sellator
---

# 🗺️ Solo Business Context

**Đây là file nền tảng.** Trước khi chạy bất kỳ kỹ năng nào, AI phải đọc file này để hiểu:
ai là user, họ làm gì, họ có gì, và họ bị giới hạn điều gì.

Triết lý cốt lõi: **Nguồn lực hữu hạn → ưu tiên đòn bẩy → tự động hóa những gì lặp lại.**

---

## Nguyên tắc hoạt động (AI cần ghi nhớ)

### 1. Đòn bẩy trước tiên
Code, Content, và Capital là 3 đòn bẩy có chi phí cận biên gần bằng 0. Nếu phải làm
đi làm lại một việc, hãy tìm cách để AI, No-code tool, hoặc Script tự làm.

### 2. Ngách cụ thể, không dàn trải
Solopreneur không thể thắng bằng cách làm tất cả mọi thứ. Thắng bằng cách làm 1 thứ
tốt hơn bất kỳ ai khác cho 1 nhóm khách hàng rất cụ thể.

### 3. Phân phối song song với sản phẩm
Sản phẩm hay mà không ai biết = không tồn tại. Xây kênh phân phối (content, cộng đồng,
SEO) ngay từ đầu, song song với việc xây sản phẩm.

### 4. Kiếm tiền sớm, dù ít
Tiền từ khách hàng thật là tín hiệu duy nhất có giá trị. Bán trước khi hoàn thiện sản phẩm.

---

## Hướng dẫn phân tích chiến lược (GAMES framework — Sellator)

Khi user hỏi về chiến lược tổng thể hoặc cần định hướng lớn, AI gợi ý phân tích theo:

- **G — Goal**: Mục tiêu trong 6-12 tháng tới là gì? Cụ thể và đo được?
- **A — Advantage**: Lợi thế độc quyền bạn đang có là gì mà đối thủ khó copy?
- **M — Market**: Thị trường ngách của bạn đủ lớn để nuôi sống bạn một mình không?
- **E — Execution**: Bạn có thể thực thi trong bao nhiêu giờ/tuần với ngân sách hiện tại?
- **S — Signals**: Tín hiệu ngoài thị trường đang chỉ vào hướng nào? (trend, công nghệ, v.v.)

---

## 📝 Thông tin dự án (User điền vào)

*Hãy thay thế phần trong `[...]` bằng thông tin thực tế của bạn.*

### Cơ bản
- **Tên dự án / Sản phẩm:** [VD: NewsletterAI, Agency thiết kế cho nhà hàng]
- **Mô tả ngắn:** [Làm gì, cho ai, giải quyết vấn đề gì?]
- **Mô hình kinh doanh:** [Subscription / One-time / Agency / Course / SaaS]
- **Đối tượng khách hàng (ICP):** [VD: Freelance designer thu nhập > $2k/tháng]
- **Giá bán / Gói dịch vụ:** [VD: $49/tháng hoặc $499 trọn đời]

### Nguồn lực hiện tại
- **Thời gian thực tế/tuần:** [VD: 10h — vì đang làm Fulltime]
- **Ngân sách/tháng:** [VD: $0 — organic only / $300 ads]
- **Kỹ năng mạnh nhất:** [VD: Viết content / No-code / Marketing]
- **Điểm yếu cần bổ sung:** [VD: Không biết code, không giỏi bán hàng]

### Tech Stack
- **Landing Page:** [Carrd / Framer / Webflow / ...]
- **Core App / Tool:** [Bubble / Softr / Next.js / ...]
- **Email:** [Mailchimp / ConvertKit / Resend / ...]
- **Thanh toán:** [Stripe / Gumroad / ...]
- **Automation:** [Make / Zapier / n8n / ...]

---

## Hướng dẫn cho AI Agent

Khi đọc xong file này, AI cần:
1. **Nhớ giới hạn thời gian và ngân sách** — không đề xuất chiến lược tốn 40h/tuần cho
   người có 10h/tuần.
2. **Không khuyên outbound sales kiểu B2B Enterprise** — Solopreneur cần Inbound,
   Product-led, Content-led.
3. **Ưu tiên No-code / automation** trước khi đề xuất code từ đầu.
4. **Gợi ý tái sử dụng tài nguyên** — 1 bài blog → Thread Twitter → Email → Short video.

## Related Skills
- Kiểm chứng ý tưởng: `idea-validation/`
- Phân tích đối thủ và ngách: `solo-competitor-analysis/`
- Xây dựng sản phẩm: `no-code-mvp/`
