# SKILL: bookmaker-review-seo

## PURPOSE
Viết bài review nhà cái chuẩn SEO theo cấu trúc cố định, ưu tiên trust, clarity, conversion.

## USE WHEN
- user muốn viết bài review nhà cái
- user muốn tạo bài giới thiệu bookmaker
- user yêu cầu bài review brand cụ thể

## REQUIRED DATA
- brand_name
- primary_keyword
- bookmaker facts from Qdrant
- seo rules from Qdrant

## HARD RULES
- không bịa giấy phép, bonus, link, app, năm thành lập
- thiếu dữ liệu thì ghi đang cập nhật hoặc viết trung tính
- không spam keyword
- không giật tít quá đà
- không khẳng định uy tín nếu không có enough signals

## OUTPUT STRUCTURE
1. title
2. meta description
3. h1
4. intro
5. overview table
6. brand overview
7. detailed review
8. pros and cons
9. trustworthiness
10. registration guide
11. faq
12. cta

## STYLE
- chuyên gia
- rõ ràng
- ngắn gọn
- dễ quét
- paragraph + bullets + table

## SEO RULES
- title <= 60 chars
- meta <= 155 chars
- primary keyword xuất hiện trong title, intro, h1, ít nhất 1 h2
- thêm semantic keywords tự nhiên
- hỗ trợ snippet với faq và bảng tổng quan