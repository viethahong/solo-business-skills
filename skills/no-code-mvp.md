---
description: Hướng dẫn tư duy xây dựng MVP cực gọn nhẹ hoặc bằng No-code cho các Solo-founders để không bị ngộp trong kỹ thuật.
---

# 🚀 Tốc độ & No-Code MVP

Khi đã là Solo, viết toàn bộ ứng dụng bằng MERN/NextJS Fullstack từ đầu tới cuối đôi khi tốn 3-6 tháng, và khi tung ra thì hết động lực hoặc thị trường đã đổi. MVP (Minimum Viable Product) không phải là "sản phẩm chưa hoàn thiện", mà là "sản phẩm ĐỦ dùng nhất để thu được tiền sớm nhất".

## Triết lý Xây dựng (Cho AI Agent truyền đạt lại)
1. **Buy > Build**: Nếu chức năng A đã có người làm Auth / Payment rồi, ĐỪNG tự code lại Auth / Stripe từ đầu. 
2. **Frankenstein MVP**: Ghép nhiều tool lại với nhau là một MVP tuyệt vời. (Airtable chạy database, Softr làm UI, Zapier xử lý logic). 
3. **Concierge MVP (Làm bằng tay)**: Giả vờ là có AI bên dưới, nhưng nếu mới có 5 khách, người Founder hãy CHÍNH TAY làm nghiệp vụ đó và gửi output cho khách. Rất hiệu quả bước đầu.

## Workflow khuyên dùng No-code (AI gợi ý cho User)
Phân loại yêu cầu sản phẩm của User để gợi ý Tech Stack chuẩn "Solo":

### 1. Dạng Website tĩnh / Sales / Directory / Chờ Email
- **Công cụ khuyên dùng**: Carrd.co (rẻ nhất), Framer (thiết kế cực đỉnh, nhanh), hoặc Webflow (dành cho SEO).
- **Trường hợp**: User chỉ muốn "Thử nghiệm dự án 1 cái newsletter", "Bảng danh bạ các AI Tools". Tích hợp Mailchimp/Convertkit.

### 2. Dạng Ứng dụng quản trị (Internal Tool/ Client Portal / Micro-SaaS)
- **Công cụ khuyên dùng**: Bubble (mạnh nhất nhưng khó học), Softr + Airtable (dễ học nhất, xây trong 1 ngày), Glide (Biến Google Sheet thành App trên điện thoại).
- **Trường hợp**: Bán access vào database chuyên biệt, phần mềm CRM nhỏ cho cá nhân, portal cho khách vào tải tài liệu.

### 3. Dạng Sản phẩm đòi hỏi Code (Chrome Extension, Native App, AI wrapper)
- Nếu BẮT BUỘC phải code: 
  - Khuyên dùng Boilerplates/Templates (ví dụ: Shipfast, Supastarter... để tiết kiệm 40h cấu hình ban đầu).
  - Sử dụng BaaS (Backend as a Service) như Supabase, Firebase thay vì tự viết Node.js riêng trừ khi logic vô cùng phức tạp.
  - Sử dụng AI Coding tools (Cursor, Claude Code) để tăng lực đòn bẩy.

## Related Skills
- Để kết nối logic tự động: `workflow-automation.md`
- Nếu là giai đoạn trước đó: `idea-validation.md`
