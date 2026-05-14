---
title : "Biểu đồ đường thẳng"
date: 2024-01-01
weight : 2
chapter : false
pre : " <b> 3.2 </b> "
---

#### Biểu đồ đường thẳng:
Trong bước này chúng ta sẽ tạo biểu đồ đường thẳng sử dụng tính năng autograph, và thử thêm số liệu dự đoán sử dụng tính năng Forecast của QuickSight.

#### Nội dung
- [Biểu đồ đường thẳng:](#biểu-đồ-đường-thẳng)
- [Nội dung](#nội-dung)
- [Biểu đồ doanh số qua từng tháng](#biểu-đồ-doanh-số-qua-từng-tháng)
- [Thêm số liệu dự đoán tương lai](#thêm-số-liệu-dự-đoán-tương-lai)

#### Biểu đồ doanh số qua từng tháng

1. Trong mục Fields list, chọn **Sales** sau đó là  **Order Date**.
  - Chúng ta sẽ thấy biểu đồ autograph tự động sinh ra biểu đồ tổng Sales theo ngày. 

![AWS](/images/2/1.2-5a.png?featherlight=false&width=90pc)

2. Chọn mũi tên cạnh **Order Date** > **Aggregate: Day** > **Month** để chuyển đơn vị thành tháng.
 
![AWS](/images/2/1.2-5b.png?featherlight=false&width=90pc)

3. Chúng ta sẽ thấy biểu đồ được chuyển thành tổng **Sales** theo tháng như hình dưới.

![AWS](/images/2/1.2-5c.png?featherlight=false&width=90pc)

#### Thêm số liệu dự đoán tương lai

Số liệu dự đoán được tạo từ dữ liệu dataset và model Machine Learning của QuickSight. Hãy thực hiện các bước sau để áp dụng các số liệu dự đoán vào biểu đồ:

1. Đảm bảo bạn biểu đồ đang active bằng cách click vào bên trong biểu đồ.
  - Click biểu tượng **...** góc bên phải biểu đồ, chọn **Add Forecast**.

![AWS](/images/2/1.2-6a.png?featherlight=false&width=90pc)

2. Ở phần **Periods backward**, nhập **6**.
  + Click **Apply**.
  + Đường biểu đồ dự đoán hiển thị số liệu 6 tháng trước để chúng ta thể so sánh với số liệu thật trong Dataset.

![AWS](/images/2/1.2-6b.png?featherlight=false&width=90pc)

3. Chúng ta có thể rê chuột lên trên biểu đồ đường thẳng để kiểm tra giá trị của Forecast và giá trị thực.

![AWS](/images/2/1.2-6c.png?featherlight=false&width=90pc)

Tiếp theo chúng ta sẽ tạo biểu đồ KPI và sử dụng tính năng Insights của QuickSight.