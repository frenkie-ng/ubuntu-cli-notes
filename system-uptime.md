## ⏱️ Kiểm tra thời gian hoạt động của máy (System Uptime)

Tổng hợp các lệnh cơ bản để kiểm tra thời điểm bật máy và lịch sử hoạt động trên Linux.

---

### 1. `uptime -p` — Thời gian máy đã chạy từ lúc bật

Hiển thị thời gian máy đã hoạt động kể từ lần khởi động gần nhất.

```bash
uptime -p
```

### 2. `who -b` Thời điểm bật máy gần nhất
Hiển thị chính xác thời điểm hệ thống được khởi động.

```bash
who -b
```

### 3. `last -x` Lịch sử bật/tắt máy trong 6 tháng gần nhất

Hiển thị lịch sử:
- Bật máy (boot)
- Tắt máy (shutdown)
- Reboot
- Các phiên đăng nhập
```bash
last -x
```