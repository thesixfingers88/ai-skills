# SKILL: bookmaker-review-seo

## PURPOSE
Viết bài **review nhà cái (bookmaker / betting)** chuẩn SEO: cấu trúc cố định, ưu tiên **trust, clarity, conversion**, phù hợp snippet và tìm kiếm có ý định.

## USE WHEN
- User muốn bài review nhà cái / bookmaker / cá cược thể thao
- Bài đánh giá / giới thiệu brand cụ thể trong ngành cược
- Outline hoặc bài đầy đủ cho landing review

## RELATED SKILLS (gọi khi phù hợp)
- `seo-title-meta` — cụm **title + meta description** (chuẩn độ dài, pattern)
- `faq-snippet-writer` — block **FAQ** (featured snippet / People Also Ask)
- `cta-conversion-writer` — đoạn **CTA cuối bài**

## REQUIRED DATA
- `brand_name`, `primary_keyword`
- Facts bookmaker từ nguồn được giao (ví dụ Qdrant): **giấy phép, sản phẩm, thanh toán, bonus, hỗ trợ** — chỉ dùng có kiểm chứng
- Quy tắc SEO nội bộ từ nguồn được giao (nếu có)

## HARD RULES (YMYL / betting)
- **Không bịa**: giấy phép, tỷ lệ cược, số tiền bonus cụ thể, link chính thức, tên app store, năm thành lập, thời gian nạp/rút cụ thể
- Thiếu dữ liệu: ghi **đang cập nhật** / **nên xác minh trên trang chính thức** / câu **trung tính**, không đoán
- Không **spam** keyword; không **giật tít** vượt dữ liệu
- Không khẳng định **uy tín / an toàn / không lừa đảo** nếu không có **tín hiệu đủ** (ví dụ license có thể kiểm tra, thông tin minh bạch). Có thể nêu **tiêu chí** người đọc tự đánh giá
- Nhắc **cá cược có rủi ro**, chỉ dành cho người đủ tuổi theo pháp luật nơi reader; không khuyến khích nợ / vay để cược
- **Không cam kết thắng / lợi nhuận**

## TIÊU CHÍ REVIEW (lồng vào nội dung, có dữ liệu mới đi sâu)
| Khía cạnh | Gợi ý nội dung |
|-----------|----------------|
| Sản phẩm | Thể thao trước/sống, eSports, casino, kèo phổ biến (không liệt kê giả nếu không chắc) |
| Giao diện / UX | App / mobile web, tốc độ, dễ tìm kèo (trải nghiệm chung, không số đo bịa) |
| Thanh toán | Phương thức, xác minh (KYC) khái quát, **không hứa** thời gian cụ thể |
| Hỗ trợ | Kênh (chat/email), ngôn ngữ nếu biết |
| Khuyến mãi | Mô tả **điều kiện chung**; chi tiết số phải khớp nguồn |
| Tin cậy | Giấy phép (nếu có URL/cơ quan), minh bạch điều khoản — thiếu thì nói thẳng |

## OUTPUT STRUCTURE (thứ tự cố định)
1. **Title** — theo `seo-title-meta`
2. **Meta description** — theo `seo-title-meta`
3. **H1** — một dòng, khác title nhẹ nếu cần (brand + góc review)
4. **Intro** — ai nên đọc, promise rõ, có `primary_keyword` tự nhiên
5. **Overview table** — 5–8 dòng: ví dụ tên thương hiệu, sản phẩm chính, thanh toán (khái quát), hỗ trợ, điểm nổi bật / lưu ý (không ô “uy tín 10/10” nếu không có cơ sở)
6. **Tổng quan thương hiệu** — 2–4 đoạn
7. **Review chi tiết** — chia **H2/H3** theo tiêu chí bảng trên
8. **Ưu và nhược điểm** — bullet cân bằng, không chỉ pr
9. **Độ tin cậy & lưu ý pháp lý** — trung thực, hướng dẫn reader tự kiểm tra (trang chủ, license)
10. **Hướng dẫn đăng ký / bắt đầu** — bước logic, không dẫn link giả
11. **FAQ** — theo `faq-snippet-writer` (5–8 cặp)
12. **CTA** — theo `cta-conversion-writer`

## STYLE
- Giọng chuyên gia, **quét nhanh** (đoạn ngắn, bullet, bảng)
- Thuật ngữ betting hiểu được (kèo chấp, live, nạp/rút) — không giảng dài không cần thiết

## SEO (tối thiểu)
- Title ≤ 60 ký tự; meta ≤ 155 ký tự
- `primary_keyword` trong title, H1, đoạn mở, ≥ 1 H2
- Semantic tự nhiên: *nhà cái, review, cá cược bóng đá, uy tín (cẩn trọng)*, *nạp rút*, *khuyến mãi*, *app*
- Một **bảng tổng quan** + **FAQ** dạng H2/H3 + câu trả lời súc tích → hỗ trợ snippet

## SAU KHI VIẾT (self-check nhanh)
- [ ] Mọi con số, bonus, license đều gắn nguồn / hoặc đã hedge rõ
- [ ] Không câu “chắc chắn thắng” / “100% an toàn”
- [ ] Có nhắc rủi ro / đủ tuổi phù hợp
- [ ] Title/meta/chunky paragraph phù hợp snippet
