# Client Sever là mô hình mạng máy tính gồm  :
- máy khách (client): Client bao gồm máy tính cũng như các loại thiết bị điện tử nói chung sẽ tiến hành gửi yêu cầu đến server.
- máy chủ (server): chính là nơi giúp lưu trữ tài nguyên cũng như cài đặt các chương trình dịch vụ theo đúng như yêu cầu của client.

Hiểu  là Client là nguồn yêu cầu và Server phải phục vụ theo nó.

Hệ điều hành của mô hình Client server sẽ cho phép người dùng chia sẻ đồng thời cùng một loại tài nguyên mà không giới hạn vị trí địa lý.

![Mô hình](https://codelearn.io/Upload/Blog/tim-hieu-ve-mo-hinh-client-server-63739412528.8042.jpg)

*Cách thức hoạt động*

Máy khách ( client ) nhận yêu cầu từ người dùng sau đó gửi yêu cầu xử lý về máy chủ ( server ) dưới dạng chuỗi truy vấn. Máy chủ sau khi tiếp nhận, phân tích, xử lý dữ liệu sẽ gửi kết quả về máy khách.

*Ví dụ*
Người dùng tìm kiếm 1 trang web từ máy khách, máy khách gửi yêu cầu đến trang web chủ, sau đó trang web chủ sẽ gửi mọi thông tin của trang web đến máy khách.

# Cấu trúc URL
URL là viết tắt của Uniform Resource Locator, dịch sang tiếng Việt là định vị tài nguyên thống nhất. Cụ thể, URL là địa chỉ của một tài nguyên duy nhất trên Web.

Nếu ví website như là một căn nhà, vậy URL chính là địa chỉ của căn nhà đó.

Mỗi URL hợp lệ sẽ trỏ đến một tài nguyên duy nhất.

Ngoài ra URL có thể trỏ đến một tài nguyên không tồn tại.

*Cấu trúc của 1 URL*

Một URL bao gồm 5 phần chính: scheme, subdomain, top-level domain , second-level domain, và subdirectory.

![95dc3314-aad9-466a-82e1-dfc6ab144304](https://user-images.githubusercontent.com/125167136/220327346-a1cbdb17-1f8e-42d7-924d-f700b025820c.png)

- Scheme hiển thị cho máy chủ web sử dụng giao thức nào khi truy cập một trang trên web.

![dd0c0511-94ad-4b2e-a790-bfeab0d39565](https://user-images.githubusercontent.com/125167136/220328667-dceb7246-6ba4-420c-bef0-d73232add040.png)

Ngày nay, HTTPs (Hypertext Transfer Protocol Secure) được coi là giao thức phổ biến nhất. Giao thức bảo mật này bảo vệ khách truy cập trang web và triển khai nó sẽ giúp trang web xếp hạng tốt hơn trên Google. 

Trong các trình duyệt hiện đại, về mặt kỹ thuật Scheme không nhất thiết là một phần của URL. Tuy nhiên, một số ứng dụng khác (và giao thức) lại yêu cầu sử dụng scheme.

- subdomain là tên miền con của tên miền chính. Chính vì là miền con của miền chính nên tên miền con này mang đầy đủ những tính chất như một miền chính và chúng ta có thể sử dụng nó giống như miền chính. 

Một Subdomain là một trang web thứ hai được tạo theo tên miền chính.

![850f788e-15b0-4804-b834-63d17965696a](https://user-images.githubusercontent.com/125167136/220330723-702db251-14eb-4aa8-b87a-4c42183eea52.png)

ví dụ : Bạn đã có website tenten.vn và bạn muốn tạo một diễn đàn thảo luận cho người dùng. Bạn có thể tạo tên miền phụ là forum.tenten.vn. Đây là một ý tưởng hay để bạn tạo nên một diễn đàn. Diễn đàn này là nơi thảo luận của những người dùng hay khách hàng của bạn trên website chính. 
Thay vì mua một tên miền mới, việc tạo tên miền phụ giúp bạn vừa tiết kiệm chi phí, vừa tạo nên một cộng đồng diễn đàn. Phục vụ nhu cầu thiết yếu của người dùng. 

- Second-level domain (SLD) được coi như là tên của website mà người dùng đặt cho nó. Đứng ngay sau tên miền phụ.

![583fa451-91d4-4b64-8253-a3e9deea7f41](https://user-images.githubusercontent.com/125167136/220331704-afe7517b-cb98-426f-9165-886eedb210a6.png)

SLD giúp người dùng nhận ra họ đang truy cập vào trang web của một thương hiệu hay cá nhân nhất định. 

Chẳng hạn, những người truy cập "MLB.com" biết rằng họ đang ở trên trang web của Major League Basketball, mà không cần thêm thông tin.

- Top-level domain (hay còn được gọi với cái tên là tên miền) chỉ định loại miền mà bạn đã đăng kí. Đứng ngay sau tên trang web.

ví dụ:

    .com: là kí hiệu viết tắt của từ commercial, nghĩa là thương mại, là phần mở rộng tên miền phổ biến nhất thế giới hiện nay.

    .net: viết tắt của từ network, nghĩa là mạng lưới, thường được sử dụng bởi các nhà cung cấp dịch vụ Internet, các công ty kinh doanh website, và các tổ chức khác có liên hệ trực tiếp đến hạ tầng Internet.

    .edu: tên miền dành cho các tổ chức giáo dục, trường học.

    Và những tên miền quốc gia (.vn, .com.vn) thường được người trong nước tin tưởng hơn là tên miền quốc tế (.com, .net, .org).

- Subdirectory (subfolder) cung cấp cho người dùng cái nhìn trực quan về phần cụ thể của trang web mà người dùng đang truy cập.

![45913cb2-3a52-4204-a2b4-9370b2f4a9d9](https://user-images.githubusercontent.com/125167136/220333406-8f0b1629-50a3-43e3-a168-b91565f3c7a4.png)

Ví dụ : nếu một trang web bán hàng muốn kinh doanh một loại hàng như t-shirt, hat, thì một trong những URL của website đó nên là https://shop.banhangvjppro.hehe/hat/ Trong đó, /hat chính là subdirectory, còn shop. là subdomain (tên miền phụ).

-  URL Parameters (còn được gọi là "chuỗi truy vấn" hay thuật ngữ Tiếng Anh là "query string") là các phần tử được thêm vào URL giúp phân loại, sắp xếp theo dõi thông tin trên trang web của mình.

Để xác định một URL Parameter, chúng ta xem phần URL đứng sau dấu chấm hỏi (?). Các URL Parameters được tạo bằng một khóa và một giá trị  {key=value}, được phân tách bằng dấu bằng (=). Nhiều tham số sau đó được phân tách bằng dấu và (&).

![Screenshot 2023-02-21 220045](https://user-images.githubusercontent.com/125167136/220380724-dc070fa8-9fe9-4eca-8c6e-e4ca055de5d7.png)

Mục đích sử dụng URL parameter phổ biến bao gồm:

    + Phân loại trang trong một gallery

    + Phân loại trang sản phẩm trên một trang thương mại điện tử (e-commerce)

    +  Kết quả tìm kiếm trên bộ máy tìm kiếm nội bộ của website

    +  UTM Tracking để theo dõi các chiến dịch: Campaign Name, Campaign Source, Campaign Medium
    
Cách hoạt động của tham số URL Parameter, có hai loại tham số URL Parameter:

URL Parameter sửa đổi nội dung (chủ động): tham số sẽ sửa đổi nội dung hiển thị trên trang

Ví dụ: đưa người dùng trực tiếp đến một sản phẩm cụ thể có tên là 'xyz'

https://by.com.vn?productid=xyz

URL Parameter tracking (thụ động) để theo dõi nâng cao: thông số sẽ theo dõi các thông tin như: nguồn truy cập, tên chiến dịch hoặc tên nhóm quảng cáo nào, v.v. - nhưng sẽ không thay đổi nội dung trên trang. 

Ví dụ: để theo dõi lưu lượng truy cập từ bản tin của bạn 

https://by.com.vn/?utm_source=newsletter&utm_medium=email

- Anchor link là một đường liên kết giúp chuyển tiếp nội dung trên trang. Đó là một ID duy nhất (mã định danh) được gắn vào nội dung hoặc phần cụ thể nào đó.

Về bản chất, anchor link được xem xét từ hai khía cạnh khác nhau. Một anchor link riêng lẻ có thể coi là điểm đánh dấu giúp bạn tiếp cận thông tin mà không cần tìm kiếm trên toàn bộ trang.

Mặt khác, tập hợp các anchor link có thể được xem như một bảng nội dung tương tác, giống như phần mục lục của một cuốn sách. Điều khác biệt là bạn có thể nhấp vào phần được liệt kê và đến đó một cách nhanh chóng.

Đối với SEO, anchor link đóng một vai trò rất quan trọng. Các đường liên kết anchor này giúp xác định phần quan trọng của nội dung bài viết, xác định cấu trúc trang và cải thiện dữ liệu phân tích SEO trên trang. Google luôn rất thông minh, nó sẽ tiếp nhận thông tin cụ thể hơn bằng cách kiểm tra cấu trúc anchor link ở website của bạn.

        ( SEO là viết tắt của Search Engine Optimization (tối ưu hóa công cụ tìm kiếm) và là một kỹ thuật đặc biệt trong Internet Marketing. Mục đích giúp website đạt            được thứ hạng cao trên các trang tìm kiếm, tiêu biểu là Google. )
        
Một anchor link bao gồm 2 phần:

    + Phần đầu tiên là anchor – một mã định danh duy nhất mà bạn có thể gắn vào các phần của trang. Trong CSS, ký tự anchor được thể hiện dưới dạng id = “unique-id” và có thể được sử dụng làm tham chiếu đến các kí tự (elements) trong CSS hoặc JavaScript.
    
    + Phần thứ hai là một đường liên kết. Sự khác biệt ở đây là URL này bao gồm hash symbol – một chuỗi các kí tự liên tiếp nhau được đặt sau dấu thăng (thường được gọi là hashtag) và đường liên kết độc nhất – #unique-id.
    
Cách tạo anchor link trong WordPress

  + Đầu tiên, chúng ta sẽ tạo một liên kết anchor trên trang.
  
  + Tiếp theo, chuyển sang chế độ văn bản của TinyMCE.

  + Sau đó điều hướng đến phần nội dung mà bạn muốn gắn liên kết anchor.

  + Cuối cùng thêm ID có tên liên kết độc nhất (ví dụ: id = ”anchor-name”). Có thể áp dụng một ID cho bất kỳ kí tự nào trong bố cục.

Bước tiếp theo là liên kết đến anchor mà bạn đã tạo ra: 

  + Chọn phần văn bản cần gắn link và nhấp vào “Chọn/Chỉnh sửa liên kết” (“Select/Edit link”).

  + Bạn sẽ thấy một cửa sổ để chỉnh sửa các thông số liên kết.

  + Thêm hash symbol cùng tên liên kết bạn đã tạo trước đó.

  + Nhấn lưu các thay đổi.

Cách tạo anchor link ở Visual Composer

  + Chọn ký tự bạn muốn “nhảy” đến (còn gọi là điểm đến);

  + Mở cửa sổ chỉnh sửa ký tự;

  + Thêm một ID độc nhất “Element ID” (không sử dụng dấu cách).    

Sau khi ID đã được thêm vào, tiếp theo bạn sẽ gắn anchor link:

  + Mở cửa sổ chỉnh sửa ký tự có chứa anchor link sẽ được thêm vào;

  + Nhấp vào “Chọn URL”;

  + Thêm “Element ID” độc nhất;
  
Lưu ý rằng phải đảm bảo chỉ sử dụng các chữ cái và số không có khoảng cách.

Sau đó Chọn “tùy chỉnh” tại URL là xong.

*Ngoài ra còn 2 thành thành khác trong URL*

- Thông tin người dùng : URL cũng có thể chứa tên người dùng và mật khẩu của trang web bạn đang truy cập. Ngày nay, bạn có thể ít bắt gặp cấu trúc URL này. VD : //username:password@www.example.com
Chúng theo sau bởi tên người dùng.

- Số cổng: Thiết bị mạng sử dụng địa chỉ IP để nhận thông tin đến máy tính phù hợp trên mạng. Khi lưu lượng truy cập đến, số cổng thông báo với máy tính biết ứng dụng mà lưu lượng truy cập đó đang nhắm đến. Bạn thường không thấy số cổng khi lướt web, nhưng có thể thấy nó trong các ứng dụng mạng như trò chơi yêu cầu nhập URL. Nếu URL chứa số cổng, nó xuất hiện ở sau tên máy chủ và trước dấu hai chấm. Bạn sẽ thấy nó trông giống như này:
//www.example.com:8080

# HTTP

HTTP (HyperText Transfer Protocol) là giao thức truyền tải siêu văn bản được sử dụng trong World Wide Web dùng để truyền tải dữ liệu giữa Web server đến các trình duyệt Web và ngược lại. Đây là phương thức cơ bản được phát triển để lấy các tài nguyên ở dạng văn bản tĩnh. Nó đã được mở rộng và phát triển theo nhiều cách để hỗ trợ cho những ứng dụng phức tạp mà ngày nay đã trở nên phổ biến.

 HTTP rất đơn giản để hoạt động. Bất cứ khi nào thông tin được trao đổi, máy khách (chẳng hạn như trình duyệt Web) đưa ra yêu cầu và máy chủ sẽ phản hồi. Quy tắc một yêu cầu (request) thì chỉ trả lại một phản hồi (response) duy nhất. Và response cho một request sẽ luôn giống nhau trong cùng một điều kiện.
 
![2e1b627a-3273-4072-8835-00fd34a3cc6e](https://user-images.githubusercontent.com/125167136/220337958-d72052d5-a71f-49b1-9030-339b2b09c6dd.png)

Trong HTTP, giao tiếp được thiết lập bởi yêu cầu do client gửi và phản hồi của server bằng TCP/IP. Mỗi trường của tiêu đề (header) và thông báo có trong request và thao tác chúng ta muốn thực hiện được chỉ định bởi phương thức (method) của request. Các dòng trạng thái, các trường tiêu đề (header) và phần thông báo trong response và kết quả xử lý được hiển thị bằng mã trạng thái.

Dòng đầu tiên của mỗi HTTP request gồm ba mục, được phân tách với nhau bằng dấu cách:

- HTTP method: Phương thức được sử dụng phổ biến nhất là GET , có chức năng lấy tài nguyên từ máy chủ web mà không cần có request body.
- Requested URL: URL thường hoạt dộng như tên của tài nguyên đang được request, cùng với một chuỗi truy vấn tùy chọn chứa các tham số mà Client đang chuyển đến tài nguyên đó. Chuỗi truy vấn được biểu thị bằng ký tự ? trong URL. Ví dụ trên chứa một tham số với tên là uid và giá trị là 129.
- HTTP version: Các phiên bản HTTP được sử dụng phổ biến là 1.0 và 1.1 và hầu hết các trình duyệt đều dùng phiên bản 1.1 theo mặc định. (Tên Host là bắt buộc)

*HTTP www*

WWW (World Wide Web - gọi tắt là Web) là một dịch vụ lưu trữ các tài liệu được tạo ở định dạng gọi là siêu văn bản trên máy chủ và cung cấp chức năng duyệt chúng qua mạng.

WWW chủ yếu sử dụng HTML (HyperText Markup Language) để viết siêu văn bản này. Để nhận ra siêu văn bản, chúng ta cần một phương pháp để trỏ đến các tài liệu và các tệp tồn tại trên Web. Phương pháp là chúng ta sẽ sử dụng URL (Uniform Resource Locator).

- HTTP localhost : Có một URL chẳng hạn như http://localhost:3000 . localhost đề cập đến hệ thống hiện đang được sử dụng, giao tiếp với máy khách (máy cục bộ) như thể nó là một máy chủ, và chủ yếu thử nghiệm các ứng dụng và trang Web khi phát triển ứng dụng Web và tạo trang Web. Nó được sử dụng khi thực hiện sản xuất hoặc phát triển ứng dụng, web.

Hiện nay có nhiều phần mềm giả lập server:

![Screenshot 2023-02-21 195853](https://user-images.githubusercontent.com/125167136/220351160-b41d279b-ca96-445e-a13f-4d462e192834.png)

- HTTP HEADERS

HTTP Header là phần đầu của HTTP trong mỗi request mà Client gửi tới Server, cũng như response của Server gửi về cho Client. Cụ thể, mỗi khi ta truy cập vào một URL thì đồng nghĩa với việc ta sẽ thực hiện gửi và nhận nhiều HTTP request, đồng thời cũng là gửi và nhận nhiều HTTP Header kèm theo. HTTP Header chứa thông tin chủ yếu về Client và Server gồm: thông tin của trình duyệt, thông tin cấu hình Server, ngày tháng, thông tin về request page, kiểu dữ liệu truyền tải,

   + General Headers

       Connection: để cho biết có nên đóng kết nối TCP sau khi quá trình truyền HTTP hoàn tất hay vẫn mở cho các message tiếp theo.
       
      Content-Encoding: để chỉ định loại mã hóa nào đang được sử dụng cho nội dung message, chẳng hạn như gzip, được sử dụng để nén response nhằm truyền tải nhanh hơn.
      
      Content-Length: để chỉ độ dài của nội dung message tính bằng byte.
      
      Content-Type: để chỉ ra loại nội dung trong nội dung message. VD: text/html chỉ tài liệu HTML.
      
      Transfer-Encoding: để chỉ ra kiểu truyền tải nào được áp dụng tới phần nội dung message để cho việc truyền tài một cách an toàn.
  
  + Request Headers

      Accept: để cho Server biết loại nội dung mà Client sẵn sàng chấp nhận.
Accept – Encoding: để cho Server biết loại nội dung mã hóa mà Client sẵn sàng chấp nhận.
Authorization: để gửi đến Server thông tin xác thực của một user agent trong phạm vi nguồn đang được yêu cầu.
  
      Cookie: để gửi cookie đến Server mà Server đã cấp trước đó.
      
      Host: để tên Server xuất hiện trong URL đầy đủ của nguồn được request.
      
      If-Modified-Since: chỉ thời điểm trình duyệt nhận được tài nguyên được request lần cuối. Nếu tài nguyên không thay đổi kể từ thời điểm đó, Server có thể hướng dẫn Client sử dụng bản sao được lưu trong bộ nhớ cache của nó, sự dụng response có mã trạng thái 304.
      
      If-None-Match: để yêu cầu Server trình bày method được yêu cầu chỉ khi một trong số giá trị đã cho của thẻ này kết nối với các thẻ đối tượng đã được cung cấp biểu diễn bởi Etag.
      
      Origin: sử dụng trong Ajax Cross-domain để chỉ ra nguồn gốc của request.
      
      Referer: để cho phép Client xác định địa chỉ URI của nguồn mà từ đó URL đã được yêu cầu.
      
      User-Agent: để cung cấp thông tin về trình duyệt hoặc phần mềm Client dùng để tạo ra request.
      
   + Response Headers

      Access-Control-Allow-Origin: để chỉ ra liệu tài nguyên có thể được truy xuất thông qua request Ajax Cross-domain.

      Cache-Control: để chuyển chỉ thị bộ nhớ đệm đến trình duyệt.

      Etag: để Client có thể gửi số nhận dạng này trong các request tương tự trong tương lai đối với cùng một tài nguyên trong If-None-Match để thống báo cho Server phiên bản tài nguyên nào mà trình duyệt hiện đang giữ trong bộ nhớ cache của nó.

      Expires: cho biết nội dung của message có giá trị trong bao lâu. Trình duyệt có thể sử dụng bản sao lưu trong bộ nhớ cache của tài nguyên cho đến thời điểm đó.

      Location: sử dụng trong các response chuyển hướng (có mã trạng thái bắt đầu bằng 3) để chỉ định mục tiêu của chuyển hướng.
 
      Pragma: để chuyển các chỉ thị bộ nhớ đệm đến trình duyệt.

      Server: để cung cấp thông tin về phền mềm web server đang sử dụng.

      Set-Cookie: cấp cookie cho trình duyệt mà nó sẽ được gửi lại Server trong các request tiếp theo.

      WWW-Authenticate: sử dụng trong response có mã trạng thái là 401 để cung cấp chi tiết về các loại xác thực mà Server hỗ trợ.

      X-Frame-Options: để chỉ ra liệu response hiện tại có thể load trong khung trình duyệt hay không.
      
- HTTP Request : HTTP request là thông tin được gửi từ client lên server, để yêu cầu server tìm hoặc xử lý một số thông tin, dữ liệu mà client muốn. HTTP request có thể là một file text dưới dạng XML hoặc Json mà cả hai đều có thể hiểu được. 

Cấu trúc của HTTP Request : 

   + Request line : Request line là dòng đầu tiên trong HTTP request. Gồm 3 phần 
       
       Phương thức HTTP được sử dụng
       
       URI( Uniform Resource Identifier) giúp xác định các tài nguyên mà client yêu cầu.
       
       Phiên bản của giao thức HTTP
       
    VD : GET/BookStore/v1/Books HTTP/1.1
       
   + Body request ( có thể có hoặc không ): Cho phép client gừi đến yêu cầu bổ sung cần server thực hiện như: tạo mới hoặc cập nhật dữ liệu mà không thể truyền trên Header Parameters.
                            
Các phương thức của HTTP request:

  + Phương thức GET : Get là phương thức được Client gửi dữ liệu lên Server thông qua đường dẫn URL nằm trên thanh địa chỉ của Browser. Server sẽ nhận đường dẫn đó và phân tích trả về kết quả cho bạn. Hơn nữa, nó là một phương thức được sử dụng phổ biến mà không cần có request body.
  
      Ví dụ điển hình là khi bạn mở một trang web, Client sẽ gửi một phương thức Get lên server để truy xuất nội dung hiển thị của trang web. Nó tương đương với thao tác đọc.
      
      Một số đặc điểm chính của phương thức Get là:

      Giới hạn độ dài của các giá trị là 255 kí tự.

      Chỉ hỗ trợ các dữ liệu kiểu String.

      Có thể lưu vào bộ nhớ cache.

      Các tham số truyền vào được lưu trữ trong lịch sử trình duyệt.

      Có thể được bookmark (đánh dấu rồi xem lại sau) do được lưu trong lịch sử trình duyệt.
      
  + Phương thức POST : Post là phương thức gửi dữ liệu đến server giúp bạn có thể thêm mới dữ liệu hoặc cập nhật dữ liệu đã có vào database.
  
     Chúng ta sẽ gửi thông tin cần thêm hoặc cập nhật trong phần body request.
     
     Một số đặc điểm chính của Post là:

     Dữ liệu cần thêm hoặc cập nhật không được hiển thị trong URL của trình duyệt.

     Dữ liệu không được lưu trong lịch sử trình duyệt.

     Không có hạn chế về độ dài của dữ liệu.

     Hỗ trợ nhiều kiểu dữ liệu như: String, binary, integers,..

 + Phương thức PUT : Cách hoạt động tương tự như Post nhưng nó chỉ được sử dụng để cập nhật dữ liệu đã có trong database. Khi sử dụng nó, bạn phải sửa toàn bộ dữ liệu của một đối tượng.
 
 + Phương thức PATCH : Tượng tự như Post và Put, nhưng Patch được sử dụng khi phải cập nhật một phần dữ liệu của đối tượng.
 
 + Phương thức DELETE : Giống như tên gọi, khi sử dụng phương thức Delete sẽ xoá các dữ liệu của server về tài nguyên thông qua URI. Cũng giống như GET, phương thức này không có body request.

+ Phương thức HEAD
    HEAD gần giống giống với lại GET, tuy nhiên nó không có response body.

    Nói một cách khác, nếu sử dụng phương thức GET tới đường dẫn /Books thì sẽ trả về danh sách các sản phẩm, còn khi sử dụng HEAD tới đường dẫn /Books nhưng không nhận được danh sách các sản phẩm.

    Truy vấn HEAD hữu ích khi chúng ta sử dụng nó để kiểm tra API có hoạt động không do không có response body nên thời gian phản hồi nhanh hơn so với phương thức Get. Và thường được sử dụng để kiếm tra trước khi download file do cứ gọi đến api dowload sẽ download file nên thêm phương thức head vào nó kiểm tra xem api có đang hoạt động tốt không tránh down nhiều.

- HTTP Response : response có nghĩa là lời phản hồi. Trong thế giới lập trình web, HTTP response là thông báo phản hồi HTTP. Đây được hiểu là kết quả server trả về cho client. 

Cấu trúc của HTTP Response :
  
   + Status-line : 
   
       HTTP-version: phiên bản HTTP cao nhất mà server sẽ hỗ trợ. 
       
       Status-Code: mã kết quả trả về.
       
       Reason-Phrase: mô tả về Status-Code.
       
- HTTP Proxies : Proxy HTTP là một máy chủ làm trung gian truy cập giữa trình duyệt Client và web server đích. Khi một trình duyệt sử dụng proxy server, nó sẽ gửi tất cả các request tới server đó. Proxy chuyển tiếp các request đến các web server có liên quan và chuyển tiếp response trở lại trình duyệt. Hầu hết các proxy cũng cung cấp các dịch vụ bổ sung, bao gồm bộ nhớ đệm, xác thực và kiểm soát truy cập.

- HTTP Authentication : Là giao thức HTTP bao gồm các cơ chế riêng để xác thực người dùng bằng cách sử dụng các lược đồ xác thực khác nhau, bao gồm các cơ chế sau:

     + Basic : là một cơ chế xác thực đơn giản gửi thông tin đăng nhập của người dùng dưới dạng chuỗi được mã hóa Base64 trong tiêu đề yêu cầu với mỗi thông báo.
     + NTLM : là một cơ chế challenge-response và sử dụng một phiên bản của giao thức Windows NTLM.
     + Digest : là một cơ chế challenge-response và sử dụng tổng kiểm tra MD5 không có gì khác với thông tin đăng nhập của người dùng.
     
# HTTPS

HTTPS (Hypertext Transfer Protocol Secure) là phiên bản an toàn của HTTP, nó có nghĩa là tất cả các giao tiếp giữa trình duyệt và trang web đều được mã hóa.

Các trang HTTPS thường sử dụng một trong hai giao thức bảo mật để mã hóa thông tin liên lạc – SSL (Secure Sockets Layer, tầng ổ bảo mật) hoặc TLS (Transport Layer Security, bảo mật tầng truyền tải). Cả hai giao thức TLS và SSL đều sử dụng hệ thống PKI (Public Key Infrastructure, hạ tầng khóa công khai) không đối xứng. Một hệ thống không đối xứng sử dụng hai “khóa” để mã hóa thông tin liên lạc, khóa “công khai” và khóa “riêng”. Bất cứ thứ gì được mã hóa bằng khoá công khai (public key) chỉ có thể được giải mã bởi khóa riêng (private key) và ngược lại.
