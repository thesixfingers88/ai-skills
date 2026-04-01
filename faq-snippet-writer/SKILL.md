# SKILL: faq-snippet-writer

## PURPOSE
Tạo **FAQ** cho bài review bookmaker: câu hỏi dạng tìm kiếm thật, câu trả lời **ngắn — rõ — trích được** (featured snippet / PAA). Dùng sau khi đã có `brand_name` và phạm vi bài.

## USE WHEN
- User cần block FAQ cho review nhà cái
- Tối ưu **snippet**: câu trả lời 40–80 từ cho câu hỏi “có… không?”

## STRUCTURE MỖI CẶP
- **H2/H3 hoặc Q đậm**: câu hỏi hoàn chỉnh (có brand khi phù hợp)
- **Đoạn trả lời**: **2–4 câu**, câu đầu trả lời thẳng ý; có thể 1 bullet nếu liệt kê ngắn

## CÂU HỎI GỢI Ý (chọn 5–8, không copy hết nếu trùng ý)
1. **[Brand] có uy tín không?** — tiêu chí đánh giá + gợi reader kiểm tra license / điều khoản
2. **[Brand] có phải lừa đảo không?** — trung tính; khuyên xác minh kênh chính thức, không khẳng định hình sự nếu không có nguồn
3. **[Brand] có những sản phẩm cược / trò chơi nào?** — khái quát theo dữ liệu
4. **Nạp và rút tiền tại [Brand] có thuận tiện không?** — không hứa thời gian cụ thể; nhắc KYC nếu liên quan
5. **Khuyến mãi tại [Brand] cần lưu ý gì?** — điều kiện chung; không bịa số tiền
6. **Có cần tải app [Brand] không?** — theo thực tế (web/app); không bịa tên store
7. **Ai không nên chơi tại [Brand]?** — rủi ro, giới hạn tuổi, cá cược có trách nhiệm (1 câu hỏi “bảo vệ”)
8. **Link / trang chính thức [Brand] là gì?** — chỉ ghi nếu có URL xác thực; không thì hướng dẫn tìm trên nguồn chính thống

## HARD RULES
- Thiếu dữ liệu → **“nên kiểm tra trên trang chính thức”** / **“thông tin thay đổi”**, không đoán
- **Không bịa** khẳng định pháp lý, số tiền, thời gian xử lý
- Tránh đoạn dài một khối; **ưu tiên câu đầu là đáp án trực tiếp** cho snippet

## OUTPUT
Chỉ nội dung FAQ (các cặp Q/A), không cần JSON trừ khi user yêu cầu schema.
