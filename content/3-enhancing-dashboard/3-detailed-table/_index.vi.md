---
title : "Bảng chi tiết dữ liệu"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 4.3 </b> "
---


### Nội dung

- [Nội dung](#nội-dung)
  - [Định dạng trang tính](#định-dạng-trang-tính)
  - [Tạo bảng dữ liệu chi tiết](#tạo-bảng-dữ-liệu-chi-tiết)
  - [Định dạng theo điều kiện](#định-dạng-theo-điều-kiện)
  - [Định dạng bảng dữ liệu](#định-dạng-bảng-dữ-liệu)
  - [Xuất bản Dashboard](#xuất-bản-dashboard)

#### Định dạng trang tính

1. Để đổi tên trang tính, chọn mũi tên cạnh trang tính cần đổi tên, chọn **Rename** và nhập tên tùy chọn (VD: `Summary`).

![AWS](/images/3/1.3-7a.png?featherlight=false&width=90pc)

2. Chọn biểu tượng **+** cạnh sheet **Summary**. Lặp lại bước trên để đổi tên thành **Details**.

![AWS](/images/3/1.3-7b.png?featherlight=false&width=90pc)

#### Tạo bảng dữ liệu chi tiết
1. Ở mục Fields list, chọn **Order ID**, **Order Date**, **Contact Name**, **Country**, **Customer**, **Industry**, **Product**, **Discount** and **Sales**.

2. Chọn mũi tên cạnh **Discount (Sum)** > **Aggregate: Sum** > **Average** để chuyển tổng giảm giá thành mức giảm giá trung bình.

![AWS](/images/3/1.3-8a.png?featherlight=false&width=90pc)

2. Chọn mũi tên cạnh **Sales (Sum)** > biểu tượng giảm để sắp xếp dữ liện từ lớn đến nhỏ.
3. Chọn mũi tên cạnh **Sales (Sum)** > **Show as: Currency** > **Format** > **More formatting options...**
4. Ở mục Field, chọn **Data Type** và đổi thành **Currency**. Ở mục **Decimal places**, chọn **2**. Như vậy, khi nào bạn sử dụng trường thông tin này, dữ liệu sẽ hiển thị dưới dạng ngoại tệ đô-la và đồng.

![AWS](/images/3/1.3-9a.png?featherlight=false&width=90pc)

#### Định dạng theo điều kiện
1. Chọn ký hiệu **...** góc bên phải biểu đồ, chọn **Conditional formatting**.

![AWS](/images/3/1.3-9b.png?featherlight=false&width=90pc)

2. Chọn **Select a column** > **Discount**.

![AWS](/images/3/1.3-9c.png?featherlight=false&width=90pc)

3. Chọn **Add background color**.

![AWS](/images/3/1.3-9d.png?featherlight=false&width=90pc)

4. Ở Conditional #1, chọn **Greater than or equal to**. Ở mục Value, điều kiện ở **0.5**, và chọn màu bất kỳ (VD: màu đỏ). Chọn **ADd condition**.
5. Ở Conditional #2, chọn **Greater than or equal to**. Ở mục Value, điều kiện ở **0.2**, và chọn màu bất kỳ (VD: màu vàng). Chọn **ADd condition**.
6. Ở Conditional #3, chọn **Less than**. Ở mục Value, điều kiện ở **0.2**, và chọn màu bất kỳ (VD: màu xanh lá).
7. Chọn **Apply** > **Close**.

![AWS](/images/3/1.3-9e.png?featherlight=false&width=90pc)

8. Chọn **Select a column** > **[Entire row]**.

![AWS](/images/3/1.3-9f.png?featherlight=false&width=90pc)


1. Ở **Format field based on** chọn **Order Date**, ở **Conditional**, chọn **After**. Ở mục **Date**, chọn ngày 01/01/2021, và chọn màu bất kỳ (VD: màu xanh dương). Chọn **Apply** > **Close**.

![AWS](/images/3/1.3-9h.png?featherlight=false&width=90pc)

#### Định dạng bảng dữ liệu

1. Chọn biểu tượng bánh răng góc bên phải biểu đồ. Chọn **Group-by column name**. Ở phần **Contact Name**, chọn `Contact`.

![AWS](/images/3/1.3-10a.png?featherlight=false&width=90pc)
2. Chọn **Value column name**. Ở phần **Discount (Average)**, chọn `Avg Discount`.

![AWS](/images/3/1.3-10b.png?featherlight=false&width=90pc)


#### Xuất bản Dashboard
1. Ở góc bên phải, chọn **Share** > **Publish dashboard**.

![AWS](/images/3/1.3-11a.png?featherlight=false&width=90pc)
2. Nhập tên dashboard (VD: Module 2). Chọn **Publish Dashboard**.

![AWS](/images/3/1.3-11b.png?featherlight=false&width=90pc)

Sau đây là kết quả dashboard được xuất bản.
![AWS](/images/3/1.3-12a.png?featherlight=false&width=90pc)

![AWS](/images/3/1.3-12b.png?featherlight=false&width=90pc)
