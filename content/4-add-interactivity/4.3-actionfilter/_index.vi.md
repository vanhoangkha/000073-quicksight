---
title : "Filter Actions"
date: 2024-01-01
weight : 3
chapter : false
pre : " <b> 5.3 </b> "
---

#### Filter Actions

**Filter Actions** cho phép bạn thực hiện các action lọc các biểu đồ hoặc toàn bộ trang dashboard tùy thuộc vào lựa chọn được thực hiện trong một biểu đồ nhất định. 
Đây là cách để cho phép bạn đặt thêm các câu hỏi tiếp theo bằng cách đi sâu vào dữ liệu theo bộ lọc. Mặc dù chúng ta đã áp dụng tính năng Action filter đơn giản trong lúc xây dựng dashboard, nhưng trong phần này, chúng ta sẽ thực hành một số tùy chọn phức tạp hơn cho các actions..

1. Chọn biểu đồ gốc. Trong trường hợp này là biểu đồ đường thẳng. Ở thanh điều hướng bên trái, chọn **Actions** > **Filter same sheet visuals**.

![AWS](/images/4/1.4-3a.png?featherlight=false&width=90pc)

![AWS](/images/4/1.4-3b.png?featherlight=false&width=90pc)

Khi chọn một điểm dữ liệu, các biểu đồ sẽ được lọc trong theo khoản thời gian của dữ liệu đó. Bạn có thể thấy biểu đồ **Forecast** và **Period over period** bị ảnh hưởng. Các bước sau sẽ giúp hai biểu đồ này không bị ảnh hưởng bởi tác động lọc:

2. Ở thanh điều hướng bên trái, chọn **Actions**. Chọn mũi tên ở phía bên phải của mục lọc, và chọn **Edit**

![AWS](/images/4/1.4-3c.png?featherlight=false&width=90pc)

3. Ở mục Targer visuals, chọn **Select visuals**, và bỏ chọn **Period over period** và **Forecast**. Chọn **Save**.

![AWS](/images/4/1.4-3d.png?featherlight=false&width=90pc)

Lúc này khi bạn chọn một điểm dữ liệu, tất cả biểu đồ đều hoạt động.
