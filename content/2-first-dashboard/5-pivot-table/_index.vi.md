---
title : "Tạo Pivot Table"
date: 2024-01-01
weight : 5
chapter : false
pre : " <b> 3.5 </b> "
---

#### Thêm Pivot Table

1. Ở góc trái, chọn **Add** > **Add visual**.
2. Ở mục Visua types góc trái phía dưới, chọn **Pivot Table**.
3. Ở muc Fields list, chọn **Sales**, **Region**, and **Subregion**.
4. Kéo thả **Order Date** vào mục **Columns** ở phần Field wells. 
![AWS](/images/2/1.2-10a.png?featherlight=false&width=90pc)

5. Chọn mũi tên mục **Order Date** tại phần Field wells. Chọn **Aggregate:Day** > **Year**. Pivot Table lúc này sẽ được chia theo từng năm.
![AWS](/images/2/1.2-10b.png?featherlight=false&width=90pc)

6. Chọn biểu tượng bánh răng ở góc phải của biểu đồ. Chọn **Styling** > **Hide single metric** để chữ Sale dưới từng năm biến mất. 
![AWS](/images/2/1.2-10c.png?featherlight=false&width=90pc)

7. Chọn mục **Subtotal** > **Show subtotals for rows**. Lúc này, Pivot Table sẽ có những số liệu tổng cộng theo từng năm và vùng.
![AWS](/images/2/1.2-10d.png?featherlight=false&width=90pc)

