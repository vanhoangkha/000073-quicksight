+++
title = "Biểu đồ hình tròn"
date = 2020
weight = 4
chapter = false
pre = "<b>2.4. </b>"
+++

### Nội dung
- [Tạo biểu đồ](#tạo-biểu-đồ)
- [Thêm thông số chi tiết](#thêm-drill-down-layer)
- [Lọc dữ liệu toàn dashboard theo ngành tùy chọn](#lọc-dữ-liệu-toàn-dashboard-theo-ngành-tùy-chọn)

#### Tạo biểu đồ

1. Chọn **Add** > **Add visual**.
2. Ở mục Visual types góc trái, chọn **Donut chart**.
3. Ở mục Fields list, chọn **Sales** và **Order date**.
![AWS](/images/2/1.2-9a.png?width=90pc)

### Thêm Drill-down Layer
Bạn có thể thêm các chi tiết liên qua đến dữ liệu bằng các thêm Drill-down layer. 

1. Kéo thả mục **Customer** từ Fields list vào phần Group/Color. Giữ ở mục này và thả chuột khi thấy báo **Add drill-down layer**.
![AWS](/images/2/1.2-9b.png?width=90pc)

2. Click chuột phải ở một đơn vị **Industry** bất kỳ (VD: Finance).
![AWS](/images/2/1.2-9c.png?width=90pc)

3. Nhờ bước 4, bạn sẽ thấy mục **Drill down to Customer**, chọn mục này.
![AWS](/images/2/1.2-9d.png?width=90pc)

4. Khi này, biểu đồ đường tròn sẽ hiện thông số **Customer** của **Industry** bạn đã chọn. Trong trường hợp này là ngành Finance.
![AWS](/images/2/1.2-9e.png?width=90pc)

Sau khi hoàn thành, bạn có thể chọn **Undo** để trở lại biểu đồ chính.

### Thêm thông số chi tiết

1. Chọn họa tiết bánh răng ở góc phải của biểu đồ.
2. Chọn mục **Data labels** > **Show metrics**.
![AWS](/images/2/1.2-9f.png?width=90pc)

### Lọc dữ liệu toàn dashboard theo ngành tùy chọn

1. Ở thanh điều hướng bên trái, chọn **Actions** > **Filter same sheet visuals**.
![AWS](/images/2/1.2-12a.png?width=90pc)

2. Khi hoàn thành bước 1, nếu bạn chọn một ngành bất kỳ (VD: Finance), các thông số ở các biểu đồ khác sẽ được lọc và hiển thị dữ liệu của ngành được chọn.
![AWS](/images/2/1.2-12b.png?width=90pc)

