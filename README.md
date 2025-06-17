

## 1. WP-Optimize – Cache

###  Mục đích sử dụng
`WP-Optimize` là một plugin tất cả trong một giúp:
- Tối ưu hóa cơ sở dữ liệu WordPress (xóa dữ liệu thừa, bản nháp cũ, bình luận spam…).
- Bật nén Gzip và tối ưu hóa CSS, JavaScript.
- Lưu cache trang để tăng tốc độ tải.
- Tích hợp Lazy Load cho hình ảnh.

###  Trường hợp nên sử dụng
- Website đang dùng hosting thông thường, không tích hợp LiteSpeed Web Server.
- Khi bạn cần giải pháp nhẹ, dễ sử dụng cho cả dọn dẹp database và tăng tốc website.
- Thích hợp với mọi loại website nhỏ đến trung bình (blog, portfolio…).

---

## 2. LiteSpeed Cache

###  Mục đích sử dụng
`LiteSpeed Cache` (LSCache) là một plugin tăng tốc website chuyên sâu được phát triển bởi LiteSpeed Technologies, cung cấp:
- Cache server-side mạnh mẽ tích hợp với máy chủ LiteSpeed.
- Nén và gộp CSS/JS.
- Lazy load hình ảnh, tối ưu hình ảnh, hỗ trợ CDN.
- Tối ưu hóa database và Object Cache.

### ⚠ Lưu ý quan trọng
**LiteSpeed Cache chỉ hoạt động hiệu quả khi máy chủ web là LiteSpeed hoặc OpenLiteSpeed.** Trên Apache hoặc NGINX, tính năng cache server-side sẽ không hoạt động.

###  Trường hợp nên sử dụng
- Website đặt trên hosting hỗ trợ LiteSpeed hoặc OpenLiteSpeed (ví dụ: các gói hosting của Vietnix có bật LiteSpeed).
- Website có lượng truy cập lớn, cần tối ưu hóa hiệu suất cao.
- Khi muốn tận dụng các công nghệ tối ưu hình ảnh, cache nâng cao, QUIC.cloud CDN...

---

##  Gợi ý sử dụng
| Plugin             | Khi nào nên cài?                                                            |
|--------------------|-----------------------------------------------------------------------------|
| WP-Optimize        | Hosting thường, cần nhẹ, dễ dùng, kết hợp dọn dẹp DB và cache               |
| LiteSpeed Cache    | Hosting dùng LiteSpeed, cần tối ưu sâu, tận dụng cache máy chủ và CDN tích hợp |

---
