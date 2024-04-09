# ANALYSIS OF SUPPLY CHAINS DATA (PHÂN TÍCH DỮ LIỆU CHUỖI CUNG ỨNG)

![SCM](https://github.com/lephuocyen20/Build-a-Data-Platform-with-Open-Source/assets/134000205/1ef6a5a4-d37d-49a5-9410-b67e85ec35de)

### 1. Nội dung dự án

Bộ dữ liệu DataCo Smart Supply Chain for Big Data Analysis trên Kaggle là một tập hợp các dữ liệu về chuỗi cung ứng thông minh,
bao gồm thông tin về đơn hàng, sản phẩm, khách hàng và các hoạt động vận chuyển liên quan.Bộ dữ liệu này cung cấp cho chúng ta
một cái nhìn tổng quát về hoạt động của các doanh nghiệp trong lĩnh vực này và có thể đượcsử dụng để phân tích và tối ưu hóa các quy trình kinh doanh
liên quan đến chuỗi cung ứng. Trong bài báo cáo của mình, chúng ta có thể sử dụng bộ dữ liệu này để tìm hiểu về xu hướng và mối quan hệ giữa các yếu tố
khác nhau trong chuỗi cung ứng, từ đó đưa ra các khuyến nghị và giải pháp để cải thiện hiệu quả và giảm chi phí cho các hoạt động kinh doanh.

### 2. Dữ liệu
Tập dữ liệu DataCo Smart Supply Chain for Big Data Analysis trên Kaggle bao gồm một tập hợp các thuộc tính (cột) sau:
-	Type: Phương thức thanh toán trong đơn hàng (GHI NỢ, CHUYỂN KHOẢN, TIỀN MẶT, v.v.).
-	Days for shipping (real): Số ngày thực tế mất để vận chuyển đơn hàng.
-	Days for shipment (scheduled): Số ngày dự kiến sẽ mất để giao đơn hàng.
-	Benefit per order: Lợi nhuận thu được từ đơn hàng.
-	Sales per customer: Tổng doanh số từ một khách hàng.
-	Delivery Status: Trạng thái giao hàng (Giao hàng sớm, Giao hàng trễ, Hủy giao hàng, Giao hàng đúng hạn.).
-	Late_delivery_risk: Biến phân loại cho biết nếu gửi hàng trễ (1), không trễ (0).
-	Category Id: Id của danh mục mà sản phẩm thuộc về.
-	Category Name: Tên danh mục mà sản phẩm thuộc về.
-	Customer City: Thành phố nơi khách hàng mua hàng.
-	Customer Country: Quốc gia nơi khách hàng mua hàng.
-	Customer Email: Địa chỉ email của khách hàng.
-	Customer Fname: Tên của khách hàng.
-	Customer Id: Id của khách hàng.
-	Customer Lname: Họ của khách hàng.
-	Customer Password: Mật khẩu của khách hàng.
-	Customer Segment: Loại khách hàng: Tiêu dùng, Doanh nghiệp, Văn phòng tại nhà.
-	Customer State: Tiểu bang nơi cửa hàng đăng ký mua hàng thuộc về.
-	Customer Street: Đường phố nơi cửa hàng đăng ký mua hàng thuộc về.
-	Customer Zipcode: Mã zip của khách hàng.
-	Department Id: Mã bộ phận của cửa hàng.
-	Department Name: Tên bộ phận của cửa hàng.
-	Latitude: Vĩ độ tương ứng với vị trí của cửa hàng.
-	Longitude: Kinh độ tương ứng với vị trí của cửa hàng.
-	Market: Thị trường mà đơn hàng được giao hàng.
-	Order City: Thành phố nơi đặt hàng.
-	Order Country: Quốc gia nơi đặt hàng.
-	Order Customer Id: Id của khách hàng đã đặt hàng.
-	Order Id: Id của đơn hàng.
-	Order Item Cardprod Id: Mã sản phẩm được tạo ra thông qua đầu đọc RFID.
-	Order Item Discount: Giá trị chiết khấu cho sản phẩm đặt hàng.
-	Order Item Discount Rate: Tỷ lệ chiết khấu áp dụng cho sản phẩm trong đơn hàng.
-	Order Item Id: Id của mặt hàng trong đơn hàng.
-	Order Item Product Price: Giá sản phẩm không có chiết khấu.
-	Order Item Profit Ratio: Tỷ lệ lợi nhuận của sản phẩm trong đơn hàng.
-	Order Item Quantity: Số lượng sản phẩm trong đơn hàng.
-	Sales: Tổng doanh số từ đơn đặt hàng.
-	Order Region: Khu vực nơi đặt hàng.
-	Order State: Tỉnh/thành phố giao hàng.
-	Order Status: Trạng thái của đơn hàng.
-	Order Zipcode: Mã zip nơi đặt hàng.
-	Product Card Id: Id của sản phẩm.
-	Product Category Id: Id của danh mục mà sản phẩm thuộc về.
-	Product Description: Mô tả về sản phẩm.
-	Product Image: Hình ảnh của sản phẩm.
-	Product Name: Tên của sản phẩm.
-	Product Price: Giá của sản phẩm.
-	Product Status: Trạng thái của sản phẩm.
-	Shipping Mode: Phương thức giao hàng: (Chuẩn, Nhanh, Nhanh hơn, Trong ngày)
-	Shipping Date(DateOrders): Ngày vận chuyển.

### 3. Thiết kế kho dữ liệu

Thực hiện thiết kế mô hình hình sao (Star schema)
![StarChema](https://github.com/lephuocyen20/Build-a-Data-Platform-with-Open-Source/assets/134000205/43f6af51-27ea-4ea8-9dce-8236c43fc04b)

Cách thực hiện mình đã đính kèm theo trong file word trong thư mục report.

Cuối cùng đây là video báo cáo của nhóm: https://drive.google.com/drive/folders/1VgWU4ulFDPCmzToFqp-kjijxcKtl-c9R
