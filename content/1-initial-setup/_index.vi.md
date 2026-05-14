---
title : "Các bước chuẩn bị"
date: 2024-01-01
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

#### Các bước chuẩn bị

Trong phần này chúng ta sẽ tạo tài khoản QuickSight Enterprise để sử dụng cho việc thực hiện biểu diễn dữ liệu.
Nếu bạn chưa đăng ký QuickSight, hãy làm theo các bước sau.

Bạn có thể download dataset đính kèm trực tiếp dưới đây.
{{%attachments style="orange" title="Sample Dataset" pattern=".*(csv)"/%}}

#### Đăng ký QuickSight
1. Truy cập [**AWS Console**](https://console.aws.amazon.com), nhập `QuickSight` trên thanh tìm kiếm và truy cập dịch vụ.
![AWS](/images/1/1.1-1.png?featherlight=false&width=90pc)

2. Click **Sign up for QuickSight**.
![AWS](/images/1/1.1-2.png?featherlight=false&width=90pc)

3. Chúng ta sẽ đăng ký phiên bản QuickSight Enterprise (Sau khi thực hiện lab xong bạn có thể cancel subscription). Chọn **Enterprise** > **Continue**.
![AWS](/images/1/1.1-3.png?featherlight=false&width=90pc)

4. Chọn **Use IAM federated identities & QuickSight-managed users**.
  - Mục **Select a region** , click chọn **Asia Pacific(Singapore)**.
  - Đặt **QuickSight account name** tùy ý (VD: `admin-ngày tạo`).
  - Đặt email để nhận notification tùy ý.
  - Kéo xuống cuối trang và click **Finish**.
![AWS](/images/1/1.1-4.png?featherlight=false&width=90pc)

5. Sau khi tạo thành công, chọn **Go to Amazon QuickSight** để được dẫn tới trang chủ QuickSight.
![AWS](/images/1/1.1-5.png?featherlight=false&width=90pc)

6. Tại trang Welcome to QuickSight, click biểu tượng **X** để đóng trang Welcome.

![AWS](/images/1/1.1-6.png?featherlight=false&width=90pc)

Chúng ta sẽ tiến hành xây dựng QuickSight dashboard trong bước kế tiếp.