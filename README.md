# Đề 3: Hệ thống Website Quảng bá Sản phẩm (WordPress)
- **Mã số sinh viên**: DTC245160065
- **Kiến trúc hệ thống**: WordPress + MySQL 8.0 + phpMyAdmin + Nginx Reverse Proxy
- **Giám sát (Monitoring)**: Prometheus + Grafana + cAdvisor + Nginx Exporter + MySQL Exporter + Node Exporter
- **Quản lý Log (Logging)**: Loki + Promtail (Truy vấn qua LogQL)
- **Bảo mật (Hardening)**: Network Isolation (3 mạng độc lập), Non-root containers, Security Headers, biến môi trường `.env` phân quyền `600`, tường lửa UFW.
## 🚀 Hướng dẫn Cài đặt & Chạy hệ thống (Quick Start)

### Yêu cầu hệ thống trước khi bắt đầu
- Máy chủ chạy **Ubuntu Linux** (hoặc WSL2 trên Windows).
- Đã cài đặt sẵn **Docker** và **Docker Compose**.

### Bước 1: Clone Repository về máy chủ
```bash
git clone [https://github.com/DTC245160065/DTC245160065.git](https://github.com/DTC245160065/DTC245160065.git)
cd DTC24516006
