---
title: "Sử dụng AWS CLI"
date: "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 4. </b> "

---

### Sử dụng AWS CLI 
AWS CLI của AWS là công cụ để quản lý các dịch vụ AWS.Bạn có thể kiểm soát nhiều dịch vụ AWS bằng command line và dễ dàng tự động hóa các dịch vụ của AWS bằng cách tạo ra các file script 
Và CLI đã đuợc cài sẵn trên Cloud 9
  1. Chạy lệnh AWS CLI để kiểm tra các instance đang chạy của chúng ra 
  ```
  aws ec2 describe-instances
  ```
![cloud9](/images/4.awscli/inlist.png )
Vây là bạn đã hoàn thành bài lab cơ bản về Cloud 9, nhớ **Dọn dẹp tài nguyên** nhé 