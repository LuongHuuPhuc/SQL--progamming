# SQL progamming on SQLite

# Ngôn ngữ SQL là gì ? 

* SQL (Structured Query Language – Ngôn ngữ truy vấn có cấu trúc) là ngôn ngữ tiêu chuẩn mà bất cứ hệ quản trị cơ sở dữ liệu quan hệ (RDBMS) nào cũng phải đáp ứng,điển hình như Oracle, Sybase, Microsoft SQL Server, Access, Ingres,…
* Nói một cách đơn giản, SQL là ngôn ngữ bạn sử dụng để tương tác với cơ sở dữ liệu.
* Các câu lệnh SQL được sử dụng để thực hiện các tác vụ như cập nhật dữ liệu trên cơ sở dữ liệu hoặc truy xuất dữ liệu từ cơ sở dữ liệu. SQL có thể được sử dụng để chèn, tìm kiếm, cập nhật và xóa các bản ghi cơ sở dữ liệu; thực hiện nhiều hoạt động khác bao gồm tối ưu hóa và bảo trì cơ sở dữ liệu.
* SQL là nền tảng cho cho các công cụ cơ sở dữ liệu được sử dụng phổ biến nhất như MySQL, SQL Server, SQLite và PostgreSQL.

## Coding SQL trên SQLite ~
### *** SQLite là gì ? ***
- SQLite là 1 hệ thống quản trị dữ liệu quan hệ, nhấn mạnh vào tốc dộ và cần sự hỗ trợ từ môi trường máy chủ (máy tính).
- SQLite là một thư viện C gọn nhẹ để quản lý cơ sở dữ liệu quan hệ bằng Ngôn ngữ SQL (Ngôn ngữ truy vấn có cấu trúc).
- Nó không phải database dộc lập mà là database nhúng -  không có máy chủ.
- SQLite cho phép người dùng có chức năng cơ sở dữ liệu bên trong cơ sở mã của họ mà không cần cài đặt thêm rdbms( Relational Database Manangement System).
- SQLite là hệ quả trị cơ sở dữ liệu (DBMS) quan hệ tương tự như Mysql, ... Đặc điểm nổi bật của SQLite so với các DBMS khác là gọn, nhẹ, đơn giản, đặt biệt không cần mô hình server-client, không cần cài đặt, cấu hình hay khởi động nên không có khái niệm user, password hay quyền hạn trong SQLite Database. Dữ liệu cũng được lưu ở một file duy nhất.
