---
title : "Bắt đầu với Quick Sight"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
---

# Bắt đầu với Quick Sight

Trong workshop này chúng ta sẽ thực hiện xây dựng một dashboard để visualize (biểu diễn) data của mình. Bắt đầu bằng việc sử dụng dữ liệu mẫu, chúng ta sẽ đi qua các phần trong workshop tập trung vào việc thực hiện phân tích và biểu diễn data qua QuickSight.

Chúng ta sẽ sử dụng Region Singapore (ap-southeast-1), bạn có thể lựa chọn region khác tùy ý.

#### Nội dung
1. [Chuẩn bị](1-initial-setup)
2. [Xây dựng Dashboard](2-first-dashboard)
3. [Cải tiến Dashboard](3-enhancing-dashboard)
4. [Tính tương tác của Dashboard](4-add-interactivity)

#### Một số khái niệm cơ bản trong QuickSight

**Data source** là một kho lưu trữ dữ liệu bên ngoài và bạn cần cấu hình việc truy cập dữ liệu trong kho dữ liệu bên ngoài này, ví dụ. Amazon S3, Amazon Athena, Salesforce, v.v.

**Dataset** xác định dữ liệu cụ thể trong Data source mà bạn muốn sử dụng. Ví dụ: Data source có thể là một bảng nếu bạn đang kết nối với Data source cơ sở dữ liệu. Nó có thể là một file nếu bạn đang kết nối với Data source Amazon S3. Dataset cũng lưu trữ bất kỳ quá trình chuẩn bị dữ liệu nào mà bạn đã thực hiện trên dữ liệu đó, chẳng hạn như đổi tên một trường hoặc thay đổi kiểu dữ liệu của nó. Việc này giúp bạn không phải sửa chữa lại dữ liệu mỗi khi bạn muốn tạo một  Analysis mới dựa trên nó.

**Analysis** là nơi chứa đựng một tập hợp các Visual và câu chuyện có liên quan, ví dụ như tất cả các câu chuyện áp dụng cho một mục tiêu kinh doanh nhất định hoặc KPI. Bạn có thể sử dụng nhiều Dataset trong một analysis, tuy nhiên 1 **Visual** chỉ có thể sử dụng một trong những Dataset đó.

**Visual** là một biểu diễn đồ họa cho dữ liệu của bạn. Bạn có thể tạo nhiều loại Visual khác nhau trong một analysis, sử dụng các bộ dữ liệu và loại Visual khác nhau.

**Dashboard** là một trang bao gồm một hoặc nhiều Analysis chỉ cho phép xem mà bạn có thể chia sẻ với những người dùng Amazon QuickSight khác cho mục đích báo cáo. Dashboard lưu giữ cấu hình của bản Analysis tại thời điểm bạn xuất bản nó, bao gồm những thứ như lọc, tham số, điều khiển và thứ tự sắp xếp. Khi bạn xem Dashboard, trang này phản ánh dữ liệu hiện tại trong các Dataset được **Analysis** sử dụng.