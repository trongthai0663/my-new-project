git init:

Ý nghĩa: Khởi tạo một Local Repository (kho lưu trữ cục bộ) mới ngay tại thư mục hiện hành trên máy tính.

git remote add origin <URL>:

Ý nghĩa: Liên kết Local Repository trên máy tính với Remote Repository (kho lưu trữ từ xa) trên GitHub với tên đại diện mặc định là origin.

git add README.md:

Ý nghĩa: Đưa tệp README.md vào khu vực chờ (Staging Area / chỉ mục của Git) để chuẩn bị cho lượt commit.

git commit -m "Add README.md file":

Ý nghĩa: Lưu lại ảnh chụp trạng thái (snapshot) các thay đổi từ Staging Area vào Local Repository kèm theo câu thông điệp mô tả (-m).

git push origin main:

Ý nghĩa: Đẩy (tải) các commit từ nhánh main ở Local Repository lên Remote Repository (origin) trên GitHub.
