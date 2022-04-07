# 1. DOCKER OVERVIEW
* Docker là một nền tảng mã nguồn mở giúp phát triển, chuyển giao và chạy các ứng dụng
* Docker cho phép tách các ứng dụng khỏi các nền tảng phần cứng để có thể phân phối phần mềm một cách nhanh chóng
* Giúp quản lý cơ sở hạ tầng phần cứng tương tự như cách quản lý các ứng dụng
  => Docker là một công nghệ giúp đóng gói ứng dụng cùng toàn bộ các thư viện thực thi thành 1 package duy nhất và nó 
  có thể chạy trên bất kỳ môi trường nào
    + Các gói (packages) được tạo ra gọi là **image**
    + Khi thực thi các **image** ta có các **container** (Container có chức năng như 1 máy ảo với đầy đủ tính năng để cài đặt và chạy phàn mềm như file system, network interface, process tree... )
    + Điểm khác biệt giữa **container** và máy ảo là container k có HĐH kernel của riêng nó mà các container chia sẻ dùng chung bộ nhân của máy chủ vật lý 
    + Hiểu đơn giản thì **container** là các tiến trình chạy trên HĐH và được quản lý bởi Docker
