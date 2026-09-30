# Blog TingTing (Jekyll)

Blog dùng Jekyll và GitHub Pages miễn phí. Viết bài mới bằng Markdown trong
`_posts/`, theo tên file `YYYY-MM-DD-ten-bai.md`:

```markdown
---
layout: post
title: "Tiêu đề bài viết"
date: 2026-10-01 09:00:00 +0700
categories: [Mẹo mua sắm]
description: "Mô tả ngắn hiện trên trang blog và kết quả tìm kiếm."
---

Nội dung bài viết ở đây.
```

Commit và push lên nhánh `main` sẽ tự build và publish bằng GitHub Pages.
Để xem trước trên máy, cài Ruby và Bundler rồi chạy `bundle install` và
`bundle exec jekyll serve` trong thư mục repo này.

## Bật GitHub Pages lần đầu

Trong Settings → Pages, chọn **Deploy from a branch**, nhánh `main`, thư mục
`/(root)`. Thêm DNS record CNAME `blog` trỏ tới `huylehp912.github.io`. Sau khi
DNS cập nhật, xác nhận domain trong Pages và bật Enforce HTTPS.
