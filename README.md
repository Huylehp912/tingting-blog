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

Commit và push lên nhánh `main` sẽ tự build và publish bằng GitHub Actions.
Để xem trước trên máy, cài Ruby và Bundler rồi chạy `bundle install` và
`bundle exec jekyll serve` trong thư mục repo này.

## Bật GitHub Pages lần đầu

Thêm DNS record CNAME `blog` trỏ tới `huylehp912.github.io`. Repository dùng
GitHub Actions để publish; sau khi DNS cập nhật, vào Settings → Pages để xác
nhận domain và bật Enforce HTTPS.
