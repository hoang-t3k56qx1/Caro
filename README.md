![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 001](https://user-images.githubusercontent.com/91744029/234307686-71ea6867-8c62-46f0-aa4e-667376275a3a.png)
**1,Phân tách quy trình thành các hành động chi tiết:**

Quy trình “Đặt phòng khách sạn” được chia ra thành các hành động chi tiết sau:

`    `Bước 1:Khách hàng truy cập hệ thống đặt phòng khách sạn

`    `Bước 2:Khách hàng chọn địa điểm đến, thời gian lưu trú, số lượng người lớn / trẻ em

`    `Bước 3:Xác định xem sự kiện có hợp lệ không ?

`    `Bước 4:Nếu sự kiện không hợp lệ thì quay lại bước 2

`    `Bước 5:Hệ thống cung cấp thông tin các khách sạn và chi tiết các phòng của từng khách sạn mà khách hàng tìm kiếm, có cả bộ lọc để lọc dữ liệu

`    `Bước 6:Khách hàng chọn một phòng và cung cấp thông tin đặt phòng (tên, số điện thoại, email, tên người khác nếu đặt hộ)

`    `Bước 7:Xác định xem sự kiện có hợp lệ không ?

`    `Bước 8:Nếu sự kiện không hợp lệ thì quay lại bước 4

`    `Bước 9:Xác định xem khách hàng có xác nhận hành động đặt vé và thanh toán không?

`    `Bước 10:Nếu khách hàng từ chối xác nhận thì kết thúc chương trình

`    `Bước 11:Xác minh từ chối thủ công

`    `Bước 12:Gửi email chứa mã vé về email khách hàng đăng ký

`    `Bước 13:Cập nhật lại lịch sử đặt phòng

`    `Bước 14:Kết thúc quy trình

**2,Lọc bỏ các hành động không phù hợp**:

Quy trình “Đặt phòng khách sạn” được chia ra thành các hành động chi tiết sau:

`    `Bước 1:Khách hàng truy cập hệ thống đặt phòng khách sạn

`    `Bước 2:Khách hàng chọn địa điểm đến, thời gian lưu trú, số lượng người lớn / trẻ em

`    `Bước 3:Xác định xem sự kiện có hợp lệ không ?

`    `Bước 4:Nếu sự kiện không hợp lệ thì quay lại bước 2

`    `Bước 5:Hệ thống cung cấp thông tin các khách sạn và chi tiết các phòng của từng khách sạn mà khách hàng tìm kiếm, có cả bộ lọc để lọc dữ liệu

`    `Bước 6:Khách hàng chọn một phòng và cung cấp thông tin đặt phòng (tên, số điện thoại, email, tên người khác nếu đặt hộ)

`    `Bước 7:Xác định xem sự kiện có hợp lệ không ?

`    `Bước 8: Nếu sự kiện không hợp lệ thì quay lại bước 4

`    `Bước 9:Xác định xem khách hàng có xác nhận hành động đặt vé và thanh toán không?

`    `Bước 10:Nếu khách hàng từ chối xác nhận thì kết thúc chương trình

`    `Bước 11:Gửi email chứa mã vé về email khách hàng đăng ký

`    `Bước 12:Cập nhật lại dữ liệu trong cơ sở dữ liệu

`    `Bước 13:Kết thúc quy trình

3\.XÁC ĐỊNH ỨNG VIÊN DỊCH VỤ THỰC THỂ

3\.1Xác định và phân loại những hành động được coi là bất khả tri. Những người được phân loại như không bất khả tri được in đậm:

- `    `**Bước 1:Khách hàng truy cập hệ thống đặt phòng khách sạn**
- `    `**Bước 2:Khách hàng chọn địa điểm đến, thời gian lưu trú, số lượng người lớn / trẻ em**
- `    `**Bước 3:Xác định xem sự kiện có hợp lệ không ?**
- `    `**Bước 4:Nếu sự kiện không hợp lệ thì quay lại bước 2**
- `    `Bước 5:Hệ thống cung cấp thông tin các khách sạn và chi tiết các phòng của từng khách sạn mà khách hàng tìm kiếm(bao gồm tiện ích phòng tắm, tiện ích phòng)
- `    `Bước 6:Khách hàng chọn một phòng và cung cấp thông tin đặt phòng (tên, số điện thoại, email, tên người khác nếu đặt hộ)
- `    `**Bước 7:Xác định xem sự kiện có hợp lệ không ?**
- `    `**Bước 8: Nếu sự kiện không hợp lệ thì quay lại bước 4**
- `    `**Bước 9:Xác định xem khách hàng có xác nhận hành động đặt vé và thanh toán không?**
- `    `**Bước 10:Nếu khách hàng từ chối xác nhận thì kết thúc chương trình**
- `    `Bước 11:Gửi email chứa mã vé về email khách hàng đăng ký
- `    `Bước 12:Cập nhật lại lịch sử đặt phòng

-Các hành động bất khả tri được phân loại là các ứng viên khả năng dịch vụ sơ bộ và được nhóm tương ứng thành các ứng viên dịch vụ

3\.2Hotel Service Candidate

-Xác định ứng viên dịch vụ thực thể

Để hỗ trợ quy trình nghiệp vụ tìm khách sạn các hành động “cung cấp thông tin các khách sạn” là một phần của ứng cử viên dịch vụ thực thể có tên Hotel.

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 002](https://user-images.githubusercontent.com/91744029/234307905-0ac4ee13-6ac5-4c19-8e52-910ce6a71c39.png)

3\.3Room Service Candidate

-Hành động “cung cấp phòng của từng khách sạn” là một phần của ứng cử viên dịch vụ thực thể có tên Room.

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 003](https://user-images.githubusercontent.com/91744029/234307979-bcf4a7cd-1768-4508-b83a-c9641bae27b4.png)

3\.4 Convenient-room Service Candidate

-Hành động “cung cấp tiện ích phòng của từng khách sạn” là một phần của ứng cử viên dịch vụ thực thể có tên Convenient-room

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 004](https://user-images.githubusercontent.com/91744029/234308049-40479736-f726-41b3-bba8-cbe80e599c02.png)

3\.5 Convenient-bathroom Service Candidate

-Hành động “cung cấp tiện ích phòng tắm của từng phòng ” là một phần của ứng cử viên dịch vụ thực thể có tên Convenient-bathroom

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 005](https://user-images.githubusercontent.com/91744029/234308125-5ab796cf-9dba-4d5d-917c-6fe3e286bbf2.png)

3\.6 User Service Candidate

-Hành động nhận yêu cầu từ người dùng “cung cấp thông tin cá nhân đặt phòng” được xây dựng dưới service Get Details.

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 006](https://user-images.githubusercontent.com/91744029/234308186-e1d86f6c-23a3-46a5-87ae-e29448445002.png)

3\.7Booking Service Candidate

-Hành động Initiate Conferral Application được dịch thành một ứng viên năng lực dịch vụ Start đơn giản như một phần của ứng viên dịch vụ nhiệm vụ Đặt phòng khách sạn. Dự kiến, "Start" sẽ được gọi bởi một chương trình phần mềm riêng biệt, chương trình này sẽ hoạt động như một bộ khởi tạo thành phần.

-Hành động “ cập nhập lịch sử đặt phòng” được định vị là các ứng cử viên khả năng dịch vụ riêng lẻ có tên là “Update History Booking”

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 007](https://user-images.githubusercontent.com/91744029/234308231-10b50a90-2ee7-4349-b6af-3cae9993ecb0.png)

-Xác định các ứng viên dịch vụ tiện ích:

+Chức năng:Gửi email chứa mã vé về email khách hàng đăng ký

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 008](https://user-images.githubusercontent.com/91744029/234308281-4366b553-137e-433a-b7da-54e0dacb08ab.png)

-Xác định ứng viên vi dịch vụ

-Khởi tạo một microservice là Verify Application với dịch vụ là Confirm purchase

Chức năng:xác nhận hành động đặt vé và thanh toán

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 009](https://user-images.githubusercontent.com/91744029/234308515-98bdf0ac-d53e-444c-a467-d18b79772c38.png)

4\. Xác định các tài nguyên

- /Process/
- /Application/
- /Hotel/
- /Room/
- /ConvenientRoom/
- /ConvenientBathroom/
- /User/
- **/Email/**

-Ánh xạ giữa thực thể và tài nguyên:

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 010](https://user-images.githubusercontent.com/91744029/234308596-c83e5d30-5b4e-4669-a63d-5c6e5b3951a3.png)

5\.Liên kết khả năng dịch vụ với tài nguyên và phương thức

- Booking Service Candidate (Task)
  ![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 011](https://user-images.githubusercontent.com/91744029/234308637-7da77ab8-8907-4d81-b80f-fd157564ec58.png)
- Hotel Service Candidate (Entity)
  ![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 012](https://user-images.githubusercontent.com/91744029/234308683-e55f9957-7039-45ac-af00-4dc0dae06bd0.png)
- Room Service Candidate (Entity)
  ![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 013](https://user-images.githubusercontent.com/91744029/234308725-d0072e80-e8be-424c-9ef5-a10c01da3da0.png)
- User Service Candidate (Entity)
  ![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 014](https://user-images.githubusercontent.com/91744029/234308765-fda44bf5-5381-4fa8-9ad6-d332dfaf907d.png)
- Convenient-room Service Candidate(Entity)
  ![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 015](https://user-images.githubusercontent.com/91744029/234308789-68dbd2ad-2128-4520-98ea-be0b383dd11f.png)
- Convenient-bathroom Service Candidate(Entity)
  ![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 016](https://user-images.githubusercontent.com/91744029/234308828-25de62bb-e490-4f0a-b8ce-47eb4f1795cf.png)

- Email

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 017](https://user-images.githubusercontent.com/91744029/234308900-c9039fa2-c17b-4605-b87d-e7699e452a02.png)

- Confirm purchase

![Aspose Words 18a8b1f7-e64f-4c68-b6e4-42ca5393e0a8 018](https://user-images.githubusercontent.com/91744029/234308962-d619df57-1041-4f42-83f7-44ec8a3840de.png)

**3,Ứng cử viên thành phần dịch vụ sửa đổi kết hợp các dịch vụ tiện ích mới và vi dịch vụ.**
![Ứng cử viên dv](https://user-images.githubusercontent.com/91744029/234451139-ced10ac7-c8ac-45a1-81a3-6296e3a4c8bf.png)


**4,Thiết kế các dịch vụ REST**  
1, Hợp đồng dịch vụ Room (Thực thể):  
![Dịch vụ Room](https://user-images.githubusercontent.com/88083752/234367980-23fe22e2-075f-4b2c-8ec2-af27aaae5e8a.png)  
- Dịch vụ Room là một dịch vụ thực thể bao gồm tất cả chức năng liên quan đến phòng khách sạn và quyền truy cập dữ liệu.  
- Dịch vụ Room cung cấp phương thức GET để truy vấn thông tin chi tiết về Phòng, với yêu cầu đối số kèm theo là id phòng.  
- Dịch vụ Room cung cấp phương thức POST để tạo mới một phòng, với yêu cầu các params kèm theo là các trường thông tin về phòng.  
- Dịch vụ Room cung cấp phương thức PUT để cập nhật thông tin phòng, với yêu cầu các params kèm theo là các trường thông tin về phòng và đối số kèm theo là id phòng.  
- Dịch vụ Room cung cấp phương thức DELETE để xóa thông tin phòng, với yêu cầu đối số kèm theo là id phòng.  
  
2, Hợp đồng dịch vụ User (Thực thể):  
![Dịch vụ User](https://user-images.githubusercontent.com/88083752/234367413-c7a60993-5c37-4534-9dde-5b68f7c7c073.png)  
- Dịch vụ User là một dịch vụ thực thể bao gồm tất cả chức năng liên quan đến người dùng và quyền truy cập dữ liệu.  
- Dịch vụ User cung cấp phương thức GET để truy vấn thông tin chi tiết về người dùng, với yêu cầu đối số kèm theo là id người dùng.  
- Dịch vụ User cung cấp phương thức POST để tạo mới một người dùng, với yêu cầu các params kèm theo là các trường thông tin về người dùng.  
- Dịch vụ User cung cấp phương thức PUT để cập nhật thông tin người dùng, với yêu cầu các params kèm theo là các trường thông tin về người dùng và đối số kèm theo là id người dùng.  
- Dịch vụ User cung cấp phương thức DELETE để xóa thông tin người dùng, với yêu cầu đối số kèm theo là id người dùng.  
  
3, Hợp đồng dịch vụ Hotel (Thực thể):  
![Dịch vụ Hotel](https://user-images.githubusercontent.com/88083752/234368661-03c5e39a-902e-424f-9265-6eb74690f179.png)  
- Dịch vụ Hotel là một dịch vụ thực thể bao gồm tất cả chức năng liên quan đến khách sạn và quyền truy cập dữ liệu.  
- Dịch vụ Hotel cung cấp phương thức GET để truy vấn thông tin chi tiết về khách sạn, với yêu cầu đối số kèm theo là id khách sạn.  
- Dịch vụ Hotel cung cấp phương thức POST để tạo mới một khách sạn, với yêu cầu các params kèm theo là các trường thông tin về khách sạn.  
- Dịch vụ Hotel cung cấp phương thức PUT để cập nhật thông tin khách sạn, với yêu cầu các params kèm theo là các trường thông tin về khách sạn và đối số kèm theo là id khách sạn.  
- Dịch vụ Hotel cung cấp phương thức DELETE để xóa thông tin khách sạn, với yêu cầu đối số kèm theo là id khách sạn.  
  
4, Hợp đồng dịch vụ Convenient Room (Thực thể):  
![Dịch vụ Convenient Room](https://user-images.githubusercontent.com/88083752/234370115-fb95b4e9-5ca7-4acb-b6d9-4840054195b0.png)  
- Dịch vụ Convenient Room là một dịch vụ thực thể bao gồm tất cả chức năng liên quan đến tiện ích phòng và quyền truy cập dữ liệu.  
- Dịch vụ Convenient Room cung cấp phương thức GET để truy vấn thông tin chi tiết về tiện ích phòng, với yêu cầu đối số kèm theo là id tiện ích phòng.  
- Dịch vụ Convenient Room cung cấp phương thức POST để tạo mới một tiện ích phòng, với yêu cầu các params kèm theo là các trường thông tin về tiện ích phòng.  
- Dịch vụ Convenient Room cung cấp phương thức PUT để cập nhật thông tin tiện ích phòng, với yêu cầu các params kèm theo là các trường thông tin về tiện ích phòng và đối số kèm theo là id tiện ích phòng.  
- Dịch vụ Convenient Room cung cấp phương thức DELETE để xóa thông tin tiện ích phòng, với yêu cầu đối số kèm theo là id tiện ích phòng.  
  
5, Hợp đồng dịch vụ Convenient Bathroom (Thực thể):  
![Dịch vụ Convenient Bathroom](https://user-images.githubusercontent.com/88083752/234371720-beb853eb-c7c1-4b8b-9822-83982731b828.png)  
- Dịch vụ Convenient Bathroom là một dịch vụ thực thể bao gồm tất cả chức năng liên quan đến tiện ích phòng và quyền truy cập dữ liệu.  
- Dịch vụ Convenient Bathroom cung cấp phương thức GET để truy vấn thông tin chi tiết về tiện ích phòng tắm, với yêu cầu đối số kèm theo là id tiện ích phòng tắm.  
- Dịch vụ Convenient Bathroom cung cấp phương thức POST để tạo mới một tiện ích phòng tắm, với yêu cầu các params kèm theo là các trường thông tin về tiện ích phòng tắm.  
- Dịch vụ Convenient Bathroom cung cấp phương thức PUT để cập nhật thông tin tiện ích phòng tắm, với yêu cầu các params kèm theo là các trường thông tin về tiện ích phòng tắm và đối số kèm theo là id tiện ích phòng tắm.  
- Dịch vụ Convenient Bathroom cung cấp phương thức DELETE để xóa thông tin tiện ích phòng tắm, với yêu cầu đối số kèm theo là id tiện ích phòng tắm.  
  
6, Hợp đồng dịch vụ Booking (Tác vụ):  
![Dịch vụ Booking](https://user-images.githubusercontent.com/88083752/234373741-640a3d85-f2f3-4818-a5de-dfe64232c1e0.png)  
- GET /bookings/{id} – phương thức này cho phép truy vấn trạng thái của một đơn đặt phòng với yêu cầu kèm theo id đơn đặt.  
- POST /bookings – phương thức này cho phép tạo mới một đơn đặt phòng với yêu cầu các params kèm theo là các trường thông tin về đơn đặt.  
- PUT /bookings/{id} – phương thức này cho phép cập nhật một đơn đặt phòng với yêu cầu các params kèm theo là các trường thông tin và id đơn đặt.  
- DELETE /bookings/{id} – phương thức này cho phép xóa một đơn đặt phòng với yêu cầu kèm theo id đơn đặt.  
  
7, Hợp đồng dịch vụ Confirm Purchase (Vi dịch vụ):  
![Dịch vụ Confirm Purchase](https://user-images.githubusercontent.com/88083752/231297155-c58bbca4-c205-49da-b2f8-5fd9840b1115.png)  
- Dịch vụ Confirm Purchase chỉ cung cấp 1 chức năng duy nhất và không bất khả tri.  
- POST /confirm-purchase{booking-id}  
  
8, Hợp đồng dịch vụ Send email (Tiện ích):  
![Dịch vụ Send email](https://user-images.githubusercontent.com/88083752/234376942-236babc1-4ee0-4547-a278-698fd2f5b387.png)  
- Dịch vụ Send email cung cấp chức năng gửi các thông báo qua email khi có cập nhật mới về đơn đặt phòng hoặc chương trình quảng cáo.  
  
**5,Stack công nghệ.**

**Microservices và API Gateway sử dụng Nodejs**

- Node.js là một nền tảng mã nguồn mở dựa trên JavaScript, được xây dựng trên V8 JavaScript Engine của Google Chrome. Node.js cho phép chạy JavaScript trên máy chủ (server-side) và cho phép tạo các ứng dụng web phía server, cũng như làm cho các ứng dụng JavaScript trở nên đa nền tảng.

- Với Node.js, việc xây dựng các ứng dụng và dịch vụ web phía server trở nên đơn giản hơn, nhờ vào khả năng xử lý các yêu cầu I/O một cách bất đồng bộ (asynchronous) và khả năng chạy các đoạn mã JavaScript trên server-side. Điều này giúp cho việc phát triển các ứng dụng và dịch vụ web phía server nhanh hơn, hiệu quả hơn và dễ dàng quản lý hơn.

- Với việc sử dụng Node.js để thực thi các microservice, ta có thể tận dụng các tính năng của nền tảng để xây dựng các ứng dụng và dịch vụ web có khả năng mở rộng và linh hoạt. Node.js cũng có nhiều thư viện hỗ trợ việc phát triển các ứng dụng và dịch vụ web phía server, giúp cho việc xây dựng các microservice và API Gateway trở nên đơn giản hơn.

**Microservices và API Gateway sử dụng Koajs (Framework của Nodejs)**

- KoaJS là một framework web NodeJS nhẹ nhàng, dựa trên ES6 (ECMAScript 2015) và được thiết kế để giúp phát triển các ứng dụng web và API một cách dễ dàng, đơn giản hơn. KoaJS là một trong những framework phổ biến cho việc phát triển microservice và API Gateway.

- Một số ưu điểm của KoaJS để phát triển microservice và API Gateway:

&nbsp;&nbsp;&nbsp;&nbsp;+Middleware-based: KoaJS là một framework middleware-based, giúp bạn thực hiện các nhiệm vụ như định tuyến, xử lý trung gian, xác thực, bảo mật, phân tích và xử lý lỗi một cách dễ dàng.

&nbsp;&nbsp;&nbsp;&nbsp;+Lightweight: KoaJS có kích thước nhỏ và không có các tính năng quá phức tạp, giúp nó hoạt động nhanh và hiệu quả.

&nbsp;&nbsp;&nbsp;&nbsp;+Async/await support: KoaJS hỗ trợ async/await, giúp viết mã bất đồng bộ trở nên dễ dàng và dễ đọc hơn.

&nbsp;&nbsp;&nbsp;&nbsp;+Tùy biến cao: KoaJS cho phép ta tùy chỉnh các middleware theo nhu cầu của dự án.

&nbsp;&nbsp;&nbsp;&nbsp;+Error handling: KoaJS cung cấp một cơ chế xử lý lỗi đơn giản và hiệu quả.

&nbsp;&nbsp;&nbsp;&nbsp;+Scalable: Với KoaJS, ta có thể phát triển các ứng dụng nhỏ và linh hoạt, giúp dễ dàng mở rộng về sau.

**Config server**

- Sử dụng nodejs + koajs để tạo server như sau

  ![image](https://user-images.githubusercontent.com/101472891/234364076-1114c951-88af-4af0-8d8c-61d7291c78d1.png)

  ![image](https://user-images.githubusercontent.com/101472891/234364251-018dc49f-736c-4e75-9a14-3b2b61fe0f6c.png)

  ![image](https://user-images.githubusercontent.com/101472891/234364459-d639d9c6-f1f5-4667-b742-b369b001bce1.png)

- Sau khi cài đặt và khởi chạy một dịch vụ sẽ như sau
  ![image](https://user-images.githubusercontent.com/101472891/234366066-4b2430dd-fd74-4b09-afb9-3f03ff5fc4a1.png)

**Items Service**

- Có thể tạo các enpoint trong từng dịch vụ như sau

  ![image](https://user-images.githubusercontent.com/101472891/234366909-d45d86ee-feaa-4640-831e-f3b4643aa8a6.png)

- Khi đó các dữ liệu sẽ đươc lấy ra từ **ctx** được cấp bởi **koa** theo các kiểu như **param, query, body** để lấy các dữ liệu được truyền vào để xử lý và trả về theo kiểu body, có thể truyền thêm trạng thái trả về

**API Gateway**

- API Gateway là một lớp phần mềm trung gian giúp điều hướng các lệnh gọi yêu cầu HTTP đến từ các ứng dụng Máy khách đến Microservice cụ thể mà không trực tiếp hiển thị chi tiết Microservice cho Máy khách và trả về các phản hồi được tạo từ Microservice tương ứng.

- Ở đây ta tạo ra các api gateway để nhận dữ liệu từ người dùng, có thể truy cập đến các dịch vụ cụ thể để lấy dữ liệu rồi xử lý dữ liệu trả lại cho người dùng

- Tương tự ta vẫn sử dụng **nodejs + koajs** nhưng ta cần có thêm 1 thư viện hỗ trợ như **axios**

- Ở đây, axios được sử dụng để gửi yêu cầu HTTP giữa các dịch vụ khác nhau

- Khi xây dựng một API gateway, Axios có thể được sử dụng để gọi các API endpoint của các microservice khác để lấy dữ liệu và trả về cho khách hàng. Điều này giúp tách biệt các dịch vụ nhỏ hơn và đơn giản hóa việc giao tiếp giữa chúng.

**Một số tính năng của Axios bao gồm:**

- Gửi yêu cầu HTTP bằng nhiều phương thức khác nhau, bao gồm GET, POST, PUT, DELETE, PATCH, vv.
- Có thể gửi yêu cầu với các tham số và headers tùy chỉnh
- Hỗ trợ Promise và interceptors
- Cho phép dễ dàng xử lý lỗi và lấy dữ liệu trả về từ các yêu cầu HTTP

![image](https://user-images.githubusercontent.com/101472891/234370937-57a286d1-fce9-458f-bdf7-3d5aa58b369c.png)

=> Khi người dùng truy cập vào một enpoint của phền mềm trung gian, nó sẽ chuyển dữ liệu đó sang một dịch vụ cụ thể bằng axios
