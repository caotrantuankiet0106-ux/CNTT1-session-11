# Phần 1: Phân tích lỗi
## Lỗi định dạng thủ công và mục lục trống:

### Nguyên nhân: Nam sử dụng định dạng thủ công (chọn bôi đen rồi chỉnh tăng cỡ chữ, in đậm) thay vì dùng hệ thống Styles tích hợp sẵn của Word.

#### Hậu quả: Word không nhận diện được các đoạn này là tiêu đề phân cấp mà chỉ coi là văn bản thông thường (Normal). Khi chèn bảng mục lục tự động (Auto TOC), công cụ quét không tìm thấy nhãn Heading nào nên trả về thông báo lỗi "No table of contents entries found" và để trống. Đồng thời, việc sửa thủ công khiến Nam không thể đồng bộ hóa định dạng hàng loạt.

Lỗi đoạn văn dài 5 trang hiện lên mục lục:

Nguyên nhân: Nam đã vô tình quét chọn và áp dụng nhãn Heading 1 cho toàn bộ một đoạn văn bản nội dung dài 5 trang (hoặc đoạn văn này dính chung khối định dạng với tiêu đề mà không được xuống dòng ngắt đoạn).

Hậu quả: Word hiểu toàn bộ khối văn bản mang nhãn Heading là một tiêu đề lớn, dẫn đến việc mục lục gom cả đoạn văn bản 5 trang hiển thị thành một dòng mục lục khổng lồ.

Phần 2: Hướng dẫn sửa lỗi
Khắc phục lỗi đoạn văn 5 trang:

Bôi đen đoạn văn bản 5 trang đang bị lỗi hiển thị trong mục lục, đổi định dạng của đoạn này về lại Normal trên thẻ Home.

Đặt con trỏ chuột ở cuối câu tiêu đề và nhấn phím Enter để tách biệt hoàn toàn giữa tiêu đề và phần nội dung bên dưới.

Gán lại Heading Styles chuẩn cấp bậc:

Chọn mục "1. Giới thiệu" và "2. Yêu cầu chức năng", sau đó gán nhãn Heading 1.

Chọn các tiểu mục con bên trong (nếu có) và gán nhãn Heading 2.

Chèn lại và cập nhật Auto TOC:

Đặt con trỏ tại vị trí muốn đặt mục lục, vào thẻ References -> Table of Contents -> Chọn mẫu mục lục tự động (Automatic Table).

Khi phát sinh thêm nội dung hoặc thay đổi số trang, chỉ cần click chuột vào bảng mục lục, chọn Update Table -> Update entire table để Word tự động cập nhật lại toàn bộ.
