BÀI 01 - LÝ THUYẾT C#
Câu 1
Value Types là kiểu dữ liệu lưu trực tiếp giá trị của biến. Reference Types lưu tham chiếu đến đối tượng trong bộ nhớ.

Trong C#, Value Type thường được lưu trên Stack khi là biến cục bộ, còn đối tượng của Reference Type được cấp phát trên Heap. Tuy nhiên, Stack và Heap là cách mô tả phổ biến chứ không phải quy tắc tuyệt đối cho mọi trường hợp.

Câu 2
Init-only Properties sử dụng từ khóa init, cho phép gán giá trị cho thuộc tính khi khởi tạo đối tượng nhưng không thể thay đổi sau khi đối tượng đã được tạo.

Khác với set, thuộc tính có set có thể thay đổi giá trị sau khi khởi tạo.

Ví dụ thực tế: sử dụng init cho mã sản phẩm hoặc mã nhân viên không muốn thay đổi sau khi tạo đối tượng.

Câu 3
virtual được khai báo ở lớp cha để cho phép lớp con ghi đè phương thức.

override được sử dụng ở lớp con để triển khai lại phương thức virtual của lớp cha.

Đây là cơ chế thực hiện tính đa hình trong C#.

Câu 4
static là thành phần thuộc về lớp chứ không thuộc về từng đối tượng.

Vì vậy, thành phần static được truy cập thông qua tên lớp thay vì thông qua đối tượng được tạo bằng toán tử new.
