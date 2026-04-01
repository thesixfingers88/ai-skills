# SKILL: seo-title-meta

## PURPOSE
Tạo **title** và **meta description** cho bài **review nhà cái / betting**, tối ưu CTR và giới hạn ký tự, **không cường điệu** vượt dữ liệu bài viết.

## USE WHEN
- Cần cặp title + meta cho landing review bookmaker
- User chỉ yêu cầu SEO title/meta (không cả bài)

## INPUT (tối thiểu)
- `brand_name`, `primary_keyword`
- (Tuỳ chọn) năm hiển thị; góc bài (uy tín / bonus / thanh toán) — chỉ dùng nếu bài thực sự có phần đó

## TITLE RULES
- Có **brand name** + gợi **review / nhà cái / đánh giá** (hoặc từ khoá chính)
- **≤ 60 ký tự** (tính cả khoảng trắng). Nếu chỉ một từ vượt: rút bớt từ phụ, không cắt nửa ý
- Tránh: *“#1 Việt Nam”*, *“100% uy tín”*, *“chắc chắn”* nếu bài không chứng minh được
- **Năm hiện tại** (ví dụ 2026) chỉ thêm khi phù hợp chiện dụng / bài cập nhật — không cứng nhắc

## META RULES
- **≤ 155 ký tự**; 1 ý chính + 1 phụ (lợi ích đọc hoặc phạm vi review)
- Gợi **trust có điều kiện**: “đánh giá dựa trên…” / “cập nhật…”, không hứa kết quả cá nhân
- **Không nhồi keyword**; không lặp gần như nguyên title trong meta

## PATTERNS (chỉnh theo brand/keyword)
- `Review [Brand] | Đánh giá nhà cái & trải nghiệm nạp rút`
- `[Brand] là gì? Review chi tiết & lưu ý khi tham gia`
- `Đánh giá [Brand] [năm]: Kèo, thanh toán, khuyến mãi (cập nhật)`

## OUTPUT (định dạng cố định)
```
Title: …
Meta description: …
```
Hai dòng đủ dùng; không thêm lời bình trừ khi user yêu cầu giải thích.
