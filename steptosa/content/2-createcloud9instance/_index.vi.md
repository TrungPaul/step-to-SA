---
title: "Tạo cloud9 instance"
date: "`r Sys.Date()`" 
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

### Tạo 1 Cloud9 instance

  Trong buớc này chúng ta sẽ vào giao diện dịch vụ Cloud9 và tạo 1 cloud9 instance
  1. Đăng nhập vào AWS Management Console. 
    ![cloud9](/images/2.createinstance/home.png)
  2. Click vào khung tìm kiếm và gõ "**Cloud9**"
  - Click vào biểu tuợng **Cloud9** để đi đến trang quản trị **Cloud9** 
    ![cloud9](/images/2.createinstance/search.png)
  
  3. Tại màn hình "**Cloud9**"
  - Click ***Create Environment**
    ![cloud9](/images/2.createinstance/create1.png)
  - 
  4. Tại step 1 "**Name environment**"
  - Đặt tên Cloud9 của bạn
  - VD: firstcloud9
  - Click **Next Step**
    ![cloud9](/images/2.createinstance/name.png)
  - 
  5. Tại step 2 "**Configure settings.**"
  - Environment type : Chọn Create a new EC2 instance for environment (direct access).
  - Instance type : Chọn t2.micro.
  - Platform : Chọn Amazon Linux2.
  -Cost-saving setting : chọn **After 30 minutes**. Cho phép tự động stop Cloud9 instance để tiết kiệm chi phí.
    ![cloud9](/images/2.createinstance/config.png)
    
  6. Tại trang **Review**.
  -Kiểm tra cấu hình đã chọn.
  -Kéo xuống cuối trang, 
    ![cloud9](/images/2.createinstance/review.png)
  7. Bạn sẽ mất vài phút để tạo
    ![cloud9](/images/2.createinstance/inprpgress.png)
  8. Chúc mừng bạn đã tạo thành công cloud instance
    ![cloud9](/images/2.createinstance/doen.png)



  - Click **Next step**.

