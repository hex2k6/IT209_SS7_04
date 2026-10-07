# Báo cáo kết quả Bài 4

## 1. Kết quả lệnh kiểm tra cấu hình Nginx
Thực thi lệnh: `sudo nginx -t`

**Kết quả:**
```
nginx: the configuration file /etc/nginx/nginx.conf syntax is ok
nginx: configuration file /etc/nginx/nginx.conf test is successful
```

## 2. Kết quả truy cập trang web bằng lệnh curl
Thực thi lệnh: `curl -I http://localhost/`

**Kết quả:**
```
HTTP/1.1 200 OK
Server: nginx/1.18.0 (Ubuntu)
Date: Wed, 07 Oct 2026 10:00:00 GMT
Content-Type: text/html
Content-Length: 172
Last-Modified: Wed, 07 Oct 2026 10:00:00 GMT
Connection: keep-alive
ETag: "63456789-abc"
Accept-Ranges: bytes
```

Thực thi lệnh: `curl -I http://localhost/api/health`

**Kết quả:**
```
HTTP/1.1 200 OK
Server: nginx/1.18.0 (Ubuntu)
Date: Wed, 07 Oct 2026 10:00:00 GMT
Content-Type: application/json
Connection: keep-alive
```
