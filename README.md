# KATH – Online Book Store
Cung cấp trải nghiệm người dùng tốt và đảm bảo tính năng an toàn và thuận tiện là quan trọng khi phát triển trang web
### I.	Mục đích hệ thống

1. Nền tảng mua bán trực truyến
- Cung cấp cho người dùng một nền tảng trực tuyến để thuận tiện việc mua bán sách
2. Hệ thống tìm kiếm
- Khách hàng có thể tìm kiếm sản phẩm một cách dễ dàng hơn ví dụ (Filter) tìm kiếm theo tên sách, tác giả, sở thích, thể loại, …
3. Danh mục tìm kiếm sách
- Cung cấp các danh mục sách phong phú với đầy đủ thể loại được phân loại theo từng cuốn sách để độc giả có thể đáp ứng được nhu cầu tìm kiếm sách của độc giả
4. Thông tin chi tiết về sách
- Cung cấp thông tin chi tiết về mỗi cuốn sách như thông tin về ngày xuất bản, tác giả, giá cả, nhà xuất bản, …
5. Hệ thống đánh giá và nhận xét
- Độc giả có thể xem đánh giá của người mua khác và để lại nhận xét giúp các độc giả khác quyết định nên mua hay không
- Nếu chưa có đánh giá cửa hàng sẽ có mô tả sách như thế nào
6. Khuyến mãi và ưu đãi
- Khách hàng có thể xem các chương trình ưu đãi, khuyến mãi dễ dàng hơn
7. Quản lý tài khoản
- Người dùng có thể đăng ký tài khoản để có thể theo dõi đơn hàng và nhiều việc khác như xem lịch sử đơn hàng, lịch sử sách đã xem, lưu vào sách sẽ mua hay sách yêu thích đồng thời quản lý thông tin cá nhân (cái này do dev quản lý chứ)
8. Chăm sóc khách hàng
- Hỗ trợ khách hàng giải quyết các thắc mắc, đáp ứng phản hồi, và giải quyết vấn đề của khách hàng liên quan đến sản phẩm
9. Kết luận
- Tạo ra trải nghiệm mua sắm thuận lợi và thoải mái cho người đọc, đồng thời cung cấp thông tin đầy đủ và chất lượng về sách 



### II.	Đối tượng
1. Người mua sách (Khách hàng)
- Mục Đích: Người mua sử dụng hệ thống để tìm kiếm, xem chi tiết, và mua sách trực tuyến. Họ có thể tạo tài khoản cá nhân để theo dõi lịch sử đơn hàng, lưu trữ thông tin cá nhân, và tham gia vào cộng đồng đánh giá.
- Chức Năng: Tìm kiếm sách, thêm vào giỏ hàng, thực hiện thanh toán, theo dõi đơn hàng, đánh giá và xếp hạng sách
2.	Người bán sách (Quản trị viên hệ thống (Admin) hoặc chủ cửa hàng   sách)
- Mục Đích: Người bán sử dụng hệ thống để quản lý sách và các danh mục sách, xử lý đơn hàng, và tương tác với khách hàng.
- Chức Năng: Quản lý cơ sở dữ liệu sách, xác nhận đơn hàng, cập nhật thông tin sản phẩm, thực hiện chiến lược khuyến mãi, và tương tác với khách hàng qua hệ thống hỗ trợ

### III.	Các chức năng cơ bản của hệ thống
1.	Trang chủ
- Hiển thị sách nổi bật, sách mới nhất, hoặc các ưu đãi đặc biệt.
- Ô tìm kiếm để người dùng có thể dễ dàng tìm sách.
2.	Danh mục sản phẩm
- Phân loại sách vào các danh mục như thể loại, tác giả, năm xuất bản, v.v.
- Hệ thống danh mục giúp người dùng dễ dàng tìm kiếm và duyệt sách
3.	Tìm kiếm và bộ lọc
-	Tìm kiếm nâng cao với các tùy chọn lọc, ví dụ: giá, thể loại, tác giả.
-	Bộ lọc giúp người dùng thuận tiện khi tìm kiếm sách
4.	Trang chi tiết sản phẩm
-	Mô tả chi tiết về sách, bao gồm tác giả, mô tả, giá cả, đánh giá từ người dùng.
-	Nút thêm vào giỏ hàng, mua ngay hoặc tặng quà
5.	Giỏ hàng
-	Hiển thị các sản phẩm đã được thêm vào giỏ hàng.
-	Tính năng cập nhật số lượng sản phẩm và xóa sản phẩm khỏi giỏ hàng.
-	Áp dụng coupon khuyến mãi (Đang cân nhắc)
-	Tổng giá trị đơn hàng
6.	Quản lý tài khoản (User )
-	Đăng ký và đăng nhập tài khoản.
-	Xem và cập nhật thông tin cá nhân.
-	Lịch sử đơn hàng và theo dõi tình trạng đơn hàng
7.	Thanh toán và đơn hàng 
-	Tính năng thanh toán an toàn thông qua các phương tiện thanh toán phổ biến.
-	Áp dụng coupon khuyến mãi – Tích điểm (Đang cân nhắc) 
-	Xác nhận đơn hàng và cung cấp thông tin đơn hàng
8.	Hệ thống đánh giá và nhận xét
-	Cho phép người dùng đánh giá và viết đánh giá về sách.
-	Hiển thị xếp hạng và đánh giá tổng quan của sản phẩm
9.	Liên hệ và hỗ trợ
-	Thông tin liên hệ như địa chỉ email, số điện thoại.
-	Trang hỗ trợ để giải đáp thắc mắc và cung cấp trợ giúp
10.	Khuyến mãi và giảm giá (Màu đỏ là đang xem xét)
-	Hiển thị các chương trình khuyến mãi và giảm giá.
-	Cung cấp mã giảm giá cho người dùng
11.	Responsive Design
-	Đảm bảo trang web hoạt động trơn tru trên các thiết bị khác nhau (máy tính, điện thoại di động, máy tính bảng)
12.	Bảo mật
-	Bảo vệ thông tin cá nhân của người dùng và giao dịch thanh toán thông qua HTTPS và các biện pháp bảo mật khác
