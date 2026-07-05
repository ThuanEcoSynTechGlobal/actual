# 💰 Actual Budget — Quản Lý Tài Chính Cá Nhân & Gia Đình

> **Fork bởi ThuanEcoSynTechGlobal** | Dự án gốc: [actualbudget/actual](https://github.com/actualbudget/actual)

## Giới thiệu

**Actual Budget** là ứng dụng quản lý tài chính cá nhân self-hosted, miễn phí, mã nguồn mở. Giúp bạn theo dõi thu chi, lập ngân sách, phân tích tài chính một cách trực quan — dữ liệu hoàn toàn riêng tư trên server của bạn.

## Tính năng chính

- 💳 **Quản lý tài khoản**: nhiều tài khoản, thẻ tín dụng, tiền mặt
- 📊 **Lập ngân sách**: theo dõi chi tiêu theo danh mục
- 📈 **Báo cáo trực quan**: biểu đồ thu chi, dòng tiền, net worth
- 🔄 **Đồng bộ hóa**: dùng chung dữ liệu giữa nhiều thiết bị
- 🔒 **Riêng tư tuyệt đối**: dữ liệu nằm trên server của bạn
- 💸 **Hỗ trợ đa tiền tệ**: VND, USD, EUR...
- 📱 **PWA**: chạy như app trên điện thoại
- 📥 **Import**: từ CSV, QIF, OFX

## Triển khai nhanh

```bash
docker run -d -p 5006:5006 \
  -v actual-data:/data \
  --name actual \
  actualbudget/actual-server:latest
```

## Mục đích fork

Phục vụ quản lý tài chính cho các dự án nông trại, hộ kinh doanh nông nghiệp — theo dõi chi phí đầu tư IoT, NLMT, nhân công, doanh thu bán hàng.

🌐 https://github.com/ThuanEcoSynTechGlobal