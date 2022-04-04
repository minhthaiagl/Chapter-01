# Cơ chế hoạt động của internet
## Internet là gì?
Internet là mạng toàn cầu bao gồm hàng tỷ máy tính và các thiết bị điện tử khác. Với Internet, bạn có thể truy cập hầu hết mọi thông tin, giao tiếp với bất kỳ ai khác trên thế giới và bạn còn làm được nhiều hơn thế nữa.
## Internet hoạt động như thế nào?
Internet là một mạng lưới **cáp vật lý** *** (có thể bao gồm dây đồng điện thoại, cáp TV và cáp quang,kết nối không dây)***toàn cầu. 
Bạn cần dựa vào các cáp vật lý này để truy cập Internet.

### Cơ chế hoạt động khi bạn truy cập vào một trang web
> 1. Máy tính của bạn sẽ gửi một yêu cầu qua các dây này tới một máy chủ.
> 2. Khi yêu cầu đến, máy chủ sẽ truy xuất trang web và gửi dữ liệu chính xác trở lại máy tính của bạn.

 Tài liệu tham khảo
  [BRANDINFO](https://brandinfo.biz/website/internet-la-gi-/144-260-373.html)
# Giải thích về protocol của HTTP/HTTPS
## HTTP
* HTTP là viết tắt của HyperText Transfer Protocol , là 1 giao thức cơ bản dùng cho World Wide Web (www) để truyền tải siêu văn bản.
* HTTP dùng bộ giao thức TCP/IP.
* HTTP sẽ không bảo mật và mã hóa các thông tin gửi đi.
* HTTP dùng port 80
## HTTPS
* HTTPS là viết tắt của Hypertext Transfer Protocol Secure), là 1  là giao thức truyền tải siêu văn bản an toàn.
* HTTPS = HTTP + SSL(Secure Sockets Layer) 
* HTTPS  hoạt động giống như HTTP nhưng bổ sung thêm SSL hoặc TLS để mã hóa và bảo * mật thông tin.
* HTTPS dùng port 443 – đây chính là cổng hỗ trợ mã hóa kết nối từ máy tính client đến server.
## Nên dùng HTTP hay HTTPS 
**Nên dùng HTTPS hơn**
> 1. HTTPS bảo mật tốt hơn
> 2. Tăng uy tín Website
> 3. Tối ưu SEO
> 4. Tốc dộ HTTPS sẽ chậm hơn HTTP nhưng không đáng kể

### Tài Liệu Tham khảo 
[CyStack](https://cystack.net/vi/blog/http-va-https-la-gi)

# Cơ chế hoạt động của browser và sự khác nhau giữa các browser
## Cơ chế hoạt động của browser
**Các thánh phần chính: **
> 1. The user interface:  Tương tác chủ yếu giữa người dùng và trình duyệt
> 2. The browser engine: Cầu nối giữa User Interface & Rendering Engine
> 3. The rendering engine: Đóng vai trò xử lý (rendering) các thẻ – câu lệnh HTML, CSS, XML, JS để hình thành giao diện (layout) hiển thị lên tầng User Interface.
> 4. Networking: Gọi các giao thức về mạng
> 5. UI backend:   Xử lý và hiển thị các UI components phổ biến
> 6. JavaScript interpreter: Xử lý và thực thi các đoạn mã JavaScript
> 7. Data storage:  Lưu trữ thông tin và dữ liệu trên máy local

**Flow of rendering engine**
> 1. Parsing (HTML to DOM and CSS to CSSOM).
> 2. Render tree (Combine DOM and CSSOM together).
> 3. Layout of the render tree.
> 4. Painting the render tree.

## Sự khác nhau giữa các browser
**Các trình duyệt họ dùng những bộ xử lý Rendering Engine không giống nhau**
> * IE: Trident Engine
> * Firefox: Gecko Engine
> * Safari & Chrome: WebKit (Note: Chrome uses Blink after version 27)
> * Opera: Presto

Đây cũng là lý do tại sao trang web của bạn lại hiểu thị không giống nhau giữa các trình duyệt, vì các trình duyệt họ sử dụng những Rendering Engine khác nhau để xử lý nên không thể giống nhau được. 
** Tài liệu tham khảo**
[VIBLO](https://viblo.asia/p/browser-lam-viec-nhu-the-nao-3Q75wWWM5Wb)

# Cơ chế hoạt động của DNS và domain
> 1. Domain là địa chỉ trang web
> 2. DNS (Domain Name System) là hệ thống phân giải tên miền.

**Cách thứ hoạt động**
> *  Nếu “có” thì nó sẽ gửi trả lại địa chỉ IP của máy có tên miền đó
> * Nếu “không có” nó sẽ hỏi lên các máy chủ tên miền ở mức cao nhất (ROOT)

**Nguyên tắc làm việc**
DNS là việc dựa trên nguyên tắc tra vấn hệ thống DNS  server. DNS server được tổ chức và quản lý bởi nhà cung cấp.

** Nguồn Tham khảo **
[Wikipedia](https://vi.wikipedia.org/wiki/H%E1%BB%87_th%E1%BB%91ng_ph%C3%A2n_gi%E1%BA%A3i_t%C3%AAn_mi%E1%BB%81n)

# Giải thích về hosting server
> Server hosting đề cập đến việc quản lý offsite, duy trì các tài nguyên phần cứng . Bằng cách trả phí hàng tháng cho dịch vụ hosting, các công ty có thể thu được lợi ích từ việc có cơ sở hạ tầng CNTT đầy đủ, mà không phải trả chi phí liên quan đến bảo trì, đào tạo và cập nhật thiết bị.

## Hosting hoạt động như thế nào?
### Phía nhà cung cấp 
>Các nhà cung cấp dịch vụ sẽ chuẩn bị server lưu trữ cho người sử dụng hosting

### Phía người dùng
> * Người thuê hosting chỉ việc upload các files lên hosting và cấu hình hoạt động cho chúng
> *  Truy cập hosting từ các thiết bị kết nối internet, thông qua việc gửi request đến domain name (tên miền) hoặc địa chỉ IP của hosting.

**Tài Liệu tham khảo**
[MATBAO](https://wiki.matbao.net/hosting-la-gi-tong-hop-tat-ca-thong-tin-can-biet-khi-mua-hosting/#:~:text=Hosting%20hay%20Web%20hosting%20l%C3%A0,online%20c%E1%BB%A7a%20b%E1%BA%A1n%20ch%E1%BA%A1y%20%C4%91%C6%B0%E1%BB%A3c.)