<h3><b>Giới thiệu</b></h3>
Giáo dục kỹ thuật thiết kế IC phụ thuộc nhiều vào các bài thực hành để củng cố hiệu quả việc học các nguyên tắc thiết kế IC. Ngày nay, các trường đại học đang phải
đối mặt với chi phí mua sắm đắt đỏ cho các thiết bị phòng thí nghiệm thiết kế IC. Bài báo này giới thiệu một phòng thí nghiệm FPGA ảo dành cho giáo dục kỹ thuật 
thiết kế IC. Ứng dụng phòng thí nghiệm web mô phỏng một bảng FPGA với các tiện ích và chức năng tương tự được sử dụng trong phòng thí nghiệm kỹ thuật thiết kế IC. 
Đầu tiên, người dùng tạo ra một thiết kế Verilog và kiểm tra bằng cách sử dụng trình soạn thảo. Thứ hai, người dùng kiểm tra cú pháp của thiết kế và kiểm tra. Thứ ba,
người dùng kích hoạt các đầu vào của thiết kế theo kết nối trong kiểm tra thông qua các công tắc và nút nhấn của GUI FPGA được mô phỏng (tức là ứng dụng phòng thí nghiệm FPGA ảo). 
Cuối cùng, người dùng theo dõi đầu ra của thiết kế trên các đèn LED của GUI FPGA được mô phỏng. Nguyên mẫu được lập trình bằng JavaScript và có khả năng mô phỏng các thiết kế
phòng thí nghiệm đại học điển hình như cổng AND, mux, bộ mã hóa, bộ giải mã, flipflop, bộ đếm, FSM, v.v. Ứng dụng này sẽ cho phép giáo dục kỹ thuật thiết kế IC 
không cần phòng thí nghiệm và học thiết kế IC miễn phí cho bất kỳ ai ở bất kỳ đâu và bất kỳ lúc nào. Các nhu cầu, yêu cầu, kiến trúc, triển khai và trường hợp sử dụng của 
hệ thống FPGA ảo được nghiên cứu và trình bày. Ứng dụng này là mã nguồn mở trên GitHub.
</br>
</br>
<h3><b>Hướng dẫn sử dụng</b></h3>
<a href="https://youtu.be/z-P2tgsCf-o?si=hTQa8TL97sMyHyaJ" target="_blank">Video demo</a>
</br>
1.Tải dự án từ github về
</br>
2.Mở thư mục có tên Front-end GUI
</br>
3.Click chuột phải lên tệp tên: index và chọn Open with
</br>
4.Chọn một trình duyệt
</br>
5.Nhập thiết kế và kểt nối vào "Code editor" hoặc mở một file trên máy của bạn hoặc mở file có sẵn trong thư mục "File lab" trong project bằng cách nhập vào nút "Open"
</br>
**Vui lòng nhập theo thứ tự: tệp thiết kế trước và sau đó là tệp kết nối
</br>
**File được mở trên máy phải chứa cả tệp thiết kế và tệp kết nối theo thứ tự: tệp thiết kế trước và tệp kết nối sau
</br>
6.Bấm nút "Run" (**tệp thiết kế và tệp kết nối sẽ được kiểm tra cùng lúc)
</br>
7.Kiểm tra thông báo (lỗi hoặc không lỗi) ở Console
</br>
8.Nếu không có lỗi thì bắt đầu thực hiện mô phỏng với các công tắc, nút bấm .
</br>
</br>
<h3><b>Phần đã thực hiện</b></h3>
- Xử lý Input và Output
