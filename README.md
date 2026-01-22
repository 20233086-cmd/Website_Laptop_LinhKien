# Website ban laptop va linh kien may tinh
<a>MVC được hình thành bởi các nghiên cứu của Trygve Reenskaug vào khoảng các năm 1978-1979. Sau đó nó được điều chỉnh và được cài đặt lần đầu tiên vào các lớp của thư viện Xerox PARC Smalltalk-80. Mô hình MVC cổ điển hiện tại ít được sử dụng trong môi trường lập trình desktop như trước đây nhưng hiện tại nó vẫn được sử dụng cực kì rộng rãi như là kiến trúc cơ bản trong các môi trường lập trình web.</a>
<h2>Tổng quan mô hình MVC</h2>
<img width="850" height="657" alt="image" src="https://github.com/user-attachments/assets/2bab9b04-2735-4072-ba75-9e6a3db60c8b" />
<h2>MVC là gì?</h2>
<a>Mô hình MVC – Model-View-Controller là phương pháp chia nhỏ các các thành phần dữ liệu (data), trình bày (output) và dữ liệu nhập từ người dùng (input) thành những thành phần riêng biệt.</a>

<h2>MVC hoạt động như thế nào?</h2>
<a>Thông thường, chúng ta biết rằng mô hình MVC gồm 3 thành phần: Model, View và Controller</a>
<ul>
<li>View – Nơi người dùng tương tác.</li>
<li>Controller – Xử lý yêu cầu và gửi phản hồi đến view.</li>
<li>Model – Middleware xử lý các thao tác cơ sở dữ liệu.</li>
</ul>
<img width="755" height="510" alt="image" src="https://github.com/user-attachments/assets/15776c01-4b27-448f-ab01-2d1c6ed85abe" />
<h2>View</h2>
<a>Về cơ bản, View đại diện cho cách dữ liệu được trình bày trong ứng dụng (UI). Các view được tạo ra dựa trên dữ liệu thu thập từ model. Bằng cách yêu cầu thông tin từ model, sau đó sẽ trả kết quả tới người dùng. Ngoài việc hiển thị dữ liệu từ các biểu đồ, sơ đồ và bảng, view còn hiển thị dữ liệu từ các nguồn khác. Tất cả các thành phần giao diện người dùng, chẳng hạn như hộp văn bản, menu thả xuống, v.v., sẽ xuất hiện trong bất kỳ view nào của khách hàng.</a>

<h2>Controller</h2>
<a>Controller là thành phần xử lý tương tác của người dùng. Dữ liệu đầu vào của người dùng được controller phân tích và xử lí, khi người dùng thao tác bất kì với hệ thống controller sẽ gửi thông tin đến model để xử lí và sau đó trả về kết quả view</a>

<a>Người dùng -tương tác-> Controller => Model => View (output) -trả kết quả-> Người dùng</a>

<a>Bằng cách giao tiếp với view liên quan của controller, người dùng có thể thay đổi giao diện của view (ví dụ: cuộn qua một tài liệu) và cập nhật trạng thái của model liên quan (ví dụ: lưu một tài liệu).<a>

<h2>Model</h2>
<a>Model là nơi lưu trữ dữ liệu và logic. Ví dụ, khi Controller truy xuất thông tin khách hàng từ cơ sở dữ liệu, dữ liệu được chuyển đổi giữa các thành phần controller hoặc giữa các yếu tố logic nghiệp vụ. Nó thao tác dữ liệu và gửi lại cơ sở dữ liệu, hoặc được sử dụng để hiển thị thông tin tương tự.</a>

<a>Ngoài ra, nó phản hồi các yêu cầu từ view và có các chỉ thị từ controller cho phép nó tự cập nhật. Nó cũng là mức thấp nhất của mô hình chịu trách nhiệm duy trì dữ liệu.</a>
