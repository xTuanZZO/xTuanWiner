# 💰 xTuanWiner - Quản Lý Tài Chính Cá Nhân

Ứng dụng web đơn giản, hiệu quả để quản lý 4 ví tiền cá nhân - tất cả trong **1 file HTML duy nhất**!

## 🎯 Tính Năng Chính

✅ **4 Ví Độc Lập** - Quản lý từng ví riêng biệt  
✅ **Cộng/Trừ 5.000 VNĐ** - Thao tác nhanh với 2 nút bấm  
✅ **Chỉnh Sửa Tên Ví** - Bấm vào tên để đổi tên trực tiếp  
✅ **Tự Động Lưu Dữ Liệu** - LocalStorage tự động lưu, không bao giờ mất dữ liệu khi reload  
✅ **Dark Mode Hiện Đại** - Giao diện tối, dễ nhìn, thiết kế phẳng  
✅ **Tối Ưu Mobile** - Hoàn hảo trên iPhone/iOS, loại bỏ delay 300ms  
✅ **Reset Dữ Liệu** - Nút reset ẩn góc màn hình để đặt lại về mặc định  

## 📱 Giao Diện

- **Lưới 2×2** chiếm toàn bộ màn hình (100vh), không cần cuộn trang
- **Mỗi ô đại diện 1 ví** với tên, số dư và 2 nút bấm
- **Màu động cho số dư**:
  - 🟢 **Xanh lá** - Số dương
  - 🔴 **Đỏ** - Số âm  
  - ⚪ **Xám/Trắng** - Bằng 0

## 🚀 Cách Sử Dụng

### Trực Tuyến (Recommended)
Truy cập ngay tại: **https://xTuanZZO.github.io/xTuanWiner/**

### Hoặc Tải Về Máy
1. Clone hoặc download file `index.html`
2. Mở file bằng trình duyệt bất kỳ
3. Bắt đầu sử dụng ngay!

## 💡 Hướng Dẫn Chi Tiết

### Cộng/Trừ Tiền
- Bấm nút **"- 5k"** để trừ 5.000 VNĐ
- Bấm nút **"+ 5k"** để cộng 5.000 VNĐ

### Đổi Tên Ví
1. Bấm vào tên ví (mặc định "Ví 1", "Ví 2", ...)
2. Chỉnh sửa text tùy ý (tối đa 32 ký tự)
3. Nhấn **Enter** hoặc bấm ra ngoài để lưu

### Lưu Dữ Liệu
- Dữ liệu được **tự động lưu** vào localStorage
- Tất cả thay đổi sẽ được giữ ngay cả khi:
  - Reload trang
  - Đóng trình duyệt rồi mở lại
  - Chuyển sang ứng dụng khác

### Reset Toàn Bộ
- Bấm nút **"RESET"** nhỏ (góc phải dưới, ẩn nhẹ)
- Xác nhận để đặt lại 4 ví về mặc định (0 VNĐ, tên gốc)

## 📋 Yêu Cầu Kỹ Thuật

- ✅ Hoạt động trên tất cả trình duyệt hiện đại
- ✅ Tối ưu iOS/iPhone (tắt delay 300ms, không bôi đen)
- ✅ Hỗ trợ Private/Incognito Mode (không crash, nhưng dữ liệu sẽ mất khi reload)
- ✅ Responsive: Desktop, Tablet, Mobile
- ✅ Không cần internet (hoạt động offline)

## 🎨 Tùy Chỉnh

Bạn có thể dễ dàng tùy chỉnh:
- **Màu sắc**: Chỉnh sửa các giá trị hex trong phần `<style>`
- **Giá trị cộng/trừ**: Thay đổi `5000` thành giá trị tùy ý
- **Số lượng ví**: Sửa `DEFAULT_WALLETS` array

## 📝 Lưu Ý

- Dữ liệu được lưu **cục bộ trên thiết bị** của bạn (không đồng bộ giữa các thiết bị)
- Trên Private/Incognito Mode của Safari, localStorage có thể bị chặn (không crash nhưng dữ liệu sẽ mất)
- File `index.html` chứa 100% code cần thiết - không cần file bổ sung

## 🤝 Đóng Góp

Nếu bạn có ý tưởng cải thiện, hãy:
1. Fork repo này
2. Tạo branch mới
3. Commit thay đổi
4. Tạo Pull Request

## 📄 License

MIT License - Tự do sử dụng, sửa đổi và chia sẻ!

---

**Được tạo bởi:** xTuanZZO  
**Ngày cập nhật:** 2026-02-14  
**Phiên bản:** 1.0.0