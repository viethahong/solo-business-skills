---
description: Cách cấu hình tự động hoá để giải phóng thời gian cho nhà sáng lập. (Nếu phải làm việc gì quá 2 lần, hãy tự động hóa nó).
---

# ⚙️ Workflow Automation (Solopreneur Automation)

Bạn là công ty một người, nghĩa là bạn vừa là CEO, vừa là Nhân sự, vừa là Sales, vừa là Kỹ Thuật. Sự cứu rỗi của bạn là Tự động hóa. Nếu thấy User đang chật vật với các quy trình nhập liệu thủ công bằng tay, hãy đề xuất ngay kỹ năng này.

## Triết lý Tự động hóa (Dành cho AI Agent)
- **Chuẩn hóa trước, tự động sau**: Đừng tự động hóa một quy trình loạn xì ngầu.
- **Dùng các nền tảng iPaaS (Integration Platform as a Service)**: Make.com (ngon, rẻ, logic phân nhánh phức tạp), Zapier (cực dễ dùng, nhưng mắc), n8n (miễn phí nếu tự host, dành cho dân code cứng).

## Cách tiếp cận các tình huống

Khi User nói về một nỗi đau lặp đi lặp lại:

1. **Khách mua hàng xong phải gửi email tay & xuất hóa đơn?**
   - *Gợi ý Setup*: Stripe (đã nhận tiền) -> Make/Zapier -> Update Data vào Airtable (CRM) -> Gửi Email kèm Invoice qua Gmail/Resend.

2. **Lọc khách hàng tiềm năng tốn thời gian?**
   - *Gợi ý Setup*: Tally/Typeform (Khách điền form) -> Dùng AI (OpenAI step trên Make) đọc form đánh giá điểm tiềm năng -> Nếu > 8 điểm, Tự động gửi link Calendly để book lịch gọi.

3. **Curate Content (Tổng hợp nội dung)?**
   - *Gợi ý Setup*: Theo dõi RSS Feed trên Twitter/Blog -> Phân loại qua ChatGPT -> Trẩy vào kho lưu trữ (Notion/Airtable) -> Setup lịch tự động đăng bài lên X/LinkedIn.

4. **Chăm sóc Khách Hàng (Customer Support)?**
   - *Gợi ý Setup*: Xây dựng một bot AI nội bộ từ chính các file Docs của sản phẩm. Cài đặt widget lên website (Chatbase, Crisp). Chỉ khi khách muốn gặp người thật mới bắn thông báo qua Slack/Telegram/Zalo của Founder.

## Vai trò của AI Agent (Bạn)
Bạn (LLM) hãy đóng vai trò người thiết kế luồng (Draft the Blueprint). Khi user muốn tự động hóa, hãy yêu cầu cấu trúc: Tiền đề (Trigger) -> Các bước giữa (Actions) -> Nơi lưu trữ (Destination). Cố gắng vẽ flowchart dạng bullet points hoặc Markdown cho User.

## Related Skills
- Trở về giai đoạn thiết kế sản phẩm No Code: `no-code-mvp.md`
- Ứng dụng tự động hóa vào Content: `content-repurposing.md`
