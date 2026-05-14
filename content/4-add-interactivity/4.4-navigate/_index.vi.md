---
title : "Navigation Actions"
date: 2024-01-01
weight : 4
chapter : false
pre : " <b> 5.4 </b> "
---


#### Navigation Actions (Hành động điều hướng)

**Các hành động điều hướng** chủ yếu được thiết kế để đưa người dùng đến các trang tính khác dựa trên một lựa chọn, thường áp dụng với các bộ lọc. 

Ví dụ: đưa người dùng từ một trang tính có số liệu tóm tắt sang một trang tính có nhiều chi tiết hơn khi lựa chọn.

1. Chọn biểu đồ gốc. Trong trường hợp này là biểu đồ hình tròn. Ở thanh điều hướng bên trái, chọn **Parameters** > **Create one...**.

2. Đặt tên tùy chọn (VD: `Industry`). Chọn **Create**.

![AWS](/images/4/1.4-4a.png?featherlight=false&width=90pc)

3. Chọn **Custom actions**.

![AWS](/images/4/1.4-4b.png?featherlight=false&width=90pc)

4. Chọn biểu tượng **+** phía bên phải cột Actions.

![AWS](/images/4/1.4-4c.png?featherlight=false&width=90pc)

5. Đặt tên hành động tùy ý (VD: `See orders from «Industry» customers`).

{{%notice tip%}} 
Nếu không muốn đánh chữ **<<Industry>>**, bạn có thể chọn biểu tượng **...** ở góc phải và chọn **<<Industry>>**.
{{% /notice %}}

6. Ở phần Action type, chọn **Navigation action**. Mục Target sheet, chọn **Details**. Chọn biểu tượng **+** phía bên phải cột Parameters.

![AWS](/images/4/1.4-4d.png?featherlight=false&width=90pc)
 
7. Ở mục Parameter, chọn **Industry** bạn vừa tạo ở bước 1 và 2. Chọn **Add** > **Save**.

![AWS](/images/4/1.4-4e.png?featherlight=false&width=90pc)

Lúc này khi bạn chọn vào một ngành trong biểu đồ hình tròn, bạn sẽ thấy lựa chọn **See orders from Tech customers**. Khi chọn bạn sẽ được dẫn tới sheet **Details**.

![AWS](/images/4/1.4-4f.png?featherlight=false&width=90pc)
  
Bạn có thể làm theo các bước sau để sheet **Details** được lọc dựa trên lực chọn ngành của bạn:

8. Ở thanh điều hướng bên trái, chọn **Filter** > **Create one...** > **Industry**.

![AWS](/images/4/1.4-4g.png?featherlight=false&width=90pc)
  
9. Chọn **Use parameters** > **Industry** > **Apply**.

![AWS](/images/4/1.4-4h.png?featherlight=false&width=90pc)

Lúc này nếu bạn chọn ngành **Tech**, trang tính **Details** chỉ hiện thị dữ liệu của ngành **Tech**.

![AWS](/images/4/1.4-4i.png?featherlight=false&width=90pc)
  