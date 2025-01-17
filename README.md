# DemoGit
Demo what I was learn about git

BẢNG TỔNG HỢP CÂU LỆNH GIT CƠ BẢN

| Chức năng               | Câu lệnh                       | Mô tả                                        |
|-------------------------|--------------------------------|----------------------------------------------|
| Khởi tạo và sao chép    | git init                       | Tạo một repository Git mới.                  |
|                         | git clone [url]                | Sao chép repository từ remote về local.      |
| Theo dõi thay đổi       | git status                     | Hiển thị trạng thái hiện tại của repository. |
|                         | git add [file/folder]          | Thêm tệp/thư mục vào staging area.           |
|                         | git commit -m "message"        | Lưu trạng thái thay đổi với thông điệp mô tả.|
| Quản lý nhánh           | git branch                     | Liệt kê các nhánh hiện có.                   |
|                         | git branch [branch_name]       | Tạo nhánh mới.                               |
|                         | git checkout [branch_name]     | Chuyển sang nhánh chỉ định.                  |
|                         | git merge [branch_name]        | Gộp nhánh chỉ định vào nhánh hiện tại.       |
| Làm việc với remote     | git remote add origin [url]    | Kết nối repo local với remote repository.    |
|                         | git push origin [branch_name]  | Đẩy thay đổi từ local lên remote.            |
|                         | git pull origin [branch_name]  | Lấy và gộp thay đổi từ remote về local.      |
| Lịch sử và kiểm tra     | git log                        | Hiển thị lịch sử commit.                     |
|                         | git diff                       | So sánh thay đổi giữa các commit hoặc nhánh. |
| Undo và sửa lỗi         | git reset [file]               | Gỡ tệp ra khỏi staging area.                 |
|                         | git checkout [file]            | Khôi phục tệp về trạng thái trước đó.        |
|                         | git revert [commit_hash]       | Tạo commit để hoàn tác thay đổi từ commit.   |


BẢNG QUY TRÌNH CƠ BẢN PHỔ BIẾN 

| Bước | Mô tả                                         | Câu lệnh                                    |
|------|-----------------------------------------------|---------------------------------------------|
| 1    | Clone repository từ remote                    | git clone [url]                             |
| 2    | Tạo nhánh mới để phát triển tính năng         | git branch [branch_name]                    |
|      |                                               | git checkout [branch_name]                  |
| 3    | Thực hiện thay đổi, thêm vào staging area     | git add [file/folder]                       |
| 4    | Commit thay đổi với thông điệp mô tả          | git commit -m "message"                     |
| 5    | Push nhánh lên remote repository              | git push origin [branch_name]               |
| 6    | Tạo Pull Request và review code               | (Thực hiện trên GitHub/GitLab/Bitbucket)    |
| 7    | Merge nhánh sau khi review hoàn tất           | git merge [branch_name]                     |
| 8    | Cập nhật thay đổi từ remote về local (nếu cần)| git pull origin [branch_name]               |
