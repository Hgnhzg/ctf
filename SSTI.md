# Teamplete engine là gì?
- Template đó chính là 1 mẫu bố cục chung cho tất cả các trang có sử dụng những thành phần giống nhau mà không phải viết lại toàn bộ, từ đó trên mỗi trang, chỉ cần thay đổi ở một số nơi được quy định trên trang từ template.
- Template engine có tác dụng giúp sạch đi những đoạn code PHP nằm tỏng view nên tách biệt hoàn toàn giữa người cắt CSS và người code PHP.
-  Hiện nay có khá nhiều template thông dụng như Twig, Blade,...

# Cách thức hoạt động của Template Engine
![image](https://github.com/Hgnhzg/ctf/assets/125167136/6087781f-80e4-4fcb-ad24-048565994327)
Một template engine thường sẽ làm các nhiệm vụ sau:
- Nhận thông tin đầu vào ( data và template ) :
  + Nhận dữ liệu ( data) từ nguồn cung cấp.
  + Nhận khuôn mẫu giao diện ( template ) từ các file quy định cấu trúc khung HTML; các nơi cần trình diễn dữ liệu...
- Xuất dữ liệu đầu ra ( HTML file ) : sau khi nhận data và template, bộ máy sẽ thực hiện thao tác hòa trộn/xuất ( render ) từ template thành file HTML để trả về người dùng.

  # SSTI ( Server Side Template Injection )
  - SSTI là lỗ hổng bảo mật xảy ra do khi ứng dụng nhúng các dữ liệu đầu vào từ phía người dùng theo cách không an toàn vào trong template.
  - Nguyên nhân chính là do máy chủ sử dụng Template engine mà không kiểm soát đâu vào của người dùng. Hoặc là do nhà phát triển cố ý cho phép người dùng submit các template.
  - Tác hại :
    + SSTI có thể khiến các trang web phải đối mặt với nhiều cuộc tấn công khác nhau tùy thuộc vào loại template engine được sử dụng và cách ứng dụng nó.
    + SSTI có thể được sử dụng để tấn công trực tiếp vào bên trong máy chủ web và thường làm bay màu máy chủ.
    + Trogn trường hợp không thể RCE, hacker vẫn có thể sử dụng SSTI làm cơ sở cho nhiều cuộc tấn công khác như XSS, CSRF,...
  - Cách phòng tránh:
    + Không cho phép người dùng exit hoặc submit các template mới.
    +  Kiểm tra và xác thực đầu vào người dùng sử dụng regex, whitelist, blacklist,...
    +  Sử dụng các template engine "logic-less" an toàn như Mustache có tính năng escape các ký tự đặc biệt.
    +  Chỉ thực thi mã của người dùng trong môi trường sandboxed khi mà các module và chức năng tiềm ẩn nguy hiểm đã bị loại bỏ.
    +  Áp dụng sanboxing của riêng bạn bằng cách triển khai môi trường template trong một vùng chứa Docker bị locked-down.
