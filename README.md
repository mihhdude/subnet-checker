# 🛠️ Subnet & IP Calculator

Một công cụ nhỏ gọn, trực quan chạy trực tiếp trên trình duyệt giúp tính toán Subnet Mask, Wildcard, Network ID, Broadcast Address và Dải IP khả dụng.

## 🚀 Tính năng chính
* **Quy đổi linh hoạt:** Chuyển đổi qua lại giữa Subnet Mask dạng X.X.X.X và prefix CIDR (/24, /28,...).
* **Tính toán chi tiết IP Subnet:** Nhập IP kèm mask (ví dụ: `192.168.1.50/24`) để tính:
  * Network Address (Network ID)
  * Broadcast Address
  * Dải IP khả dụng (Usable IP Range)
  * Wildcard Mask
  * Số lượng Host khả dụng
* **Giao diện tự động:** Cập nhật kết quả tức thì ngay khi gõ.
* **Không cần cài đặt:** Đã được deploy sẵn qua GitHub Pages.

## 💻 Công nghệ sử dụng
* HTML5
* CSS3 (Responsive, hiển thị tốt trên cả Desktop và Mobile)
* JavaScript Pure (Client-side, xử lý không giật lag, không cần backend server)

## 📌 Cách sử dụng
1. Mở trang web.
2. Nhập IP và Subnet theo các định dạng hỗ trợ:
   * `192.168.1.50/24`
   * `192.168.1.50 255.255.255.0`
   * `255.255.255.0`
   * `/24` hoặc `24`