# 🌮 Tacos Gio Linh – Financial Decision Support System (DSS)

## 📖 Giới thiệu

Tacos Gio Linh DSS là hệ hỗ trợ ra quyết định tài chính được xây dựng trên nền tảng Microsoft Excel nhằm hỗ trợ Ban giám đốc đánh giá hiệu quả đầu tư, tối ưu hóa nguồn lực sản xuất và quản trị rủi ro kinh doanh dựa trên dữ liệu thực tế.

---

## 🎯 Bối cảnh bài toán (Giả định)

Tacos Gio Linh là chuỗi cửa hàng F&B chuyên kinh doanh 4 dòng sản phẩm:

* Chicken Taco
* Beef Taco
* Pork Taco
* Veggie Taco

Sau 7 năm hoạt động ổn định, doanh nghiệp chuẩn bị bước vào năm kinh doanh thứ 8 và đối mặt với nhiều quyết định chiến lược quan trọng liên quan đến đầu tư, sản xuất và vận hành.

Để hỗ trợ Ban giám đốc ra quyết định, hệ thống DSS được xây dựng nhằm giải quyết ba bài toán chính:

### 1. Đánh giá khả thi tài chính

Doanh nghiệp cần xác định liệu dòng tiền tích lũy trong 7 năm qua có tạo ra giá trị đủ lớn để tiếp tục đầu tư trong giai đoạn tiếp theo hay không thông qua các chỉ tiêu NPV và IRR.

### 2. Tối ưu hóa nguồn lực sản xuất

Ngân sách nguyên liệu bị giới hạn bởi các ràng buộc chuỗi cung ứng:

* Nguyên liệu chung ≤ 450 triệu VNĐ
* Nguyên liệu thịt ≤ 200 triệu VNĐ
* Nguyên liệu chay ≤ 150 triệu VNĐ

Đồng thời phải đảm bảo các yêu cầu kinh doanh:

* Chicken Taco ≥ 5.000 phần
* Veggie Taco chiếm 30% – 45% tổng sản lượng

Mục tiêu là tìm cơ cấu sản phẩm tối ưu nhằm tối đa hóa doanh thu.

### 3. Quản trị rủi ro kênh phân phối

Doanh nghiệp triển khai ứng dụng đặt hàng riêng và chính sách miễn phí giao hàng.

Tuy nhiên, tỷ lệ khách đặt qua App và chi phí giao hàng tăng có thể làm suy giảm lợi nhuận. Hệ thống cần đánh giá mức độ ảnh hưởng của các yếu tố này để xác định ngưỡng rủi ro và hỗ trợ hoạch định chiến lược.

---

## 🚀 Chức năng chính

### 📊 Capital Budgeting

* Phân tích dòng tiền dự án trong 7 năm.
* Tính toán NPV và IRR.
* Đánh giá tính khả thi của dự án đầu tư.

### 📈 Linear Programming

* Xây dựng mô hình tối ưu hóa sản lượng.
* Sử dụng Solver để tìm cơ cấu sản phẩm tối ưu.
* Tối đa hóa doanh thu dưới các ràng buộc nguồn lực.

### ⚠️ Sensitivity Analysis

* Mô phỏng nhiều kịch bản kinh doanh.
* Phân tích tác động của tỷ lệ đặt hàng qua App và chi phí giao hàng.
* Xác định mức độ suy giảm lợi nhuận trong các tình huống bất lợi.


---

## 💡 Đề xuất chiến lược

Dựa trên kết quả phân tích, hệ thống đề xuất:

### Chiến lược 1: Định giá phân biệt (Pricing Strategy)

Do chi phí giao hàng cao hơn phục vụ tại cửa hàng, doanh nghiệp nên áp dụng mức giá khác nhau giữa các kênh bán hàng.

* Tăng giá trên App từ 10% – 15% để bù đắp chi phí giao hàng.
* Duy trì giá gốc đối với khách hàng ăn tại quán.

### Chiến lược 2: Bán theo Combo (Up-selling)

Khuyến khích khách hàng đặt các combo như:

* Taco + Nước uống
* Taco + Khoai tây chiên
* Taco + Nước uống + Khoai tây chiên

Việc tăng giá trị trung bình mỗi đơn hàng giúp giảm tỷ trọng chi phí giao hàng trên doanh thu.

---

## 📊 Kết quả nổi bật

| Chỉ tiêu                      | Kết quả               |
| ----------------------------- | --------------------- |
| NPV                           | 138.104.263 VNĐ       |
| IRR                           | 24%                   |
| Quyết định đầu tư             | Tiếp tục đầu tư       |
| Doanh thu tối ưu              | 507.256.000 VNĐ/tháng |
| Mức suy giảm lợi nhuận tối đa | 19%                   |

---

## 🛠️ Công nghệ sử dụng

* Microsoft Excel
* Excel Solver (Simplex LP)
* What-If Analysis
* Data Table
* Conditional Formatting (Heatmap)


---

## 👤 Tác giả
Phan Hồng Phúc

