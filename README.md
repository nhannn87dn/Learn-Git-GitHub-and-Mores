# Learn Git - Github and Mores

## 💛Github

### 🔥Github là gì ?

GitHub là một nền tảng lưu trữ mã nguồn và quản lý phiên bản dựa trên web cho phép các nhà phát triển phần mềm lưu trữ, quản lý, theo dõi và kiểm soát thay đổi đối với mã nguồn của họ. Được thành lập vào năm 2008, GitHub đã trở thành một trong những công cụ phổ biến nhất cho phát triển phần mềm hợp tác, với các tính năng như quản lý nhiệm vụ, yêu cầu kéo (pull requests), và tích hợp liên tục. Nó hỗ trợ cộng tác và là một nền tảng tuyệt vời cho các dự án mã nguồn mở và tư nhân.

### 🔥Tính năng chính của GitHub

1. **Lưu trữ mã nguồn**: GitHub cung cấp kho lưu trữ Git trực tuyến để lưu trữ, quản lý và theo dõi mã nguồn.
2. **Kiểm soát phiên bản**: Giúp theo dõi và kiểm soát các thay đổi trong mã nguồn, cho phép người dùng quay lại các phiên bản trước của mã nếu cần.
3. **Cộng tác**: Cho phép nhiều người dùng cùng làm việc trên một dự án, quản lý các thay đổi của nhau thông qua các nhánh và yêu cầu kéo.
4. **Tích hợp liên tục và triển khai liên tục (CI/CD)**: Hỗ trợ tự động hóa các quy trình như xây dựng, kiểm thử và triển khai ứng dụng.
5. **Theo dõi vấn đề và quản lý nhiệm vụ**: Cung cấp công cụ để theo dõi sự cố, yêu cầu tính năng và quản lý nhiệm vụ trong các dự án.
6. **Wiki và trang web dự án**: Cho phép tạo và lưu trữ tài liệu dự án và trang web ngay trong kho lưu trữ.

GitHub không chỉ là một công cụ cho các nhà phát triển phần mềm mà còn là một cộng đồng lớn mà ở đó mọi người có thể khám phá các dự án của người khác, đóng góp vào mã nguồn mở và học hỏi từ nhau.

### 🔥Đăng ký tài khoản Github

Để đăng ký tài khoản GitHub, bạn có thể làm theo các bước sau:

1. Truy cập trang web GitHub tại [github.com](https://github.com/).
2. Nhấp vào nút **Sign up** ở góc trên bên phải của trang.
3. Điền thông tin cần thiết vào biểu mẫu đăng ký, bao gồm:
   - **Email address**: Địa chỉ email của bạn.
   - **Password**: Mật khẩu cho tài khoản của bạn.
   - **Username**: Tên người dùng mà bạn muốn sử dụng.
4. Nhấp vào nút **Create account** để tiếp tục.
5. GitHub sẽ gửi một email xác nhận đến địa chỉ email bạn đã cung cấp. Mở email và nhấp vào liên kết xác nhận để kích hoạt tài khoản của bạn.
6. Sau khi xác nhận email, bạn sẽ được chuyển đến trang thiết lập tài khoản. Tại đây, bạn có thể chọn các tùy chọn như:
   - **Plan**: Chọn gói dịch vụ (miễn phí hoặc trả phí) phù hợp với nhu cầu của bạn.
   - **Preferences**: Cài đặt các tùy chọn cá nhân và thông báo.
7. Hoàn tất quá trình thiết lập và bắt đầu sử dụng GitHub.

Chúc mừng! Bạn đã đăng ký thành công tài khoản GitHub và có thể bắt đầu tạo kho lưu trữ, quản lý mã nguồn và cộng tác với các nhà phát triển khác.

## 💛Git

### 🔥Git là gì ?

Git là một hệ thống quản lý phiên bản phân tán (Distributed Version Control System - DVCS) được tạo ra bởi Linus Torvalds vào năm 2005. Git cho phép nhiều người làm việc trên cùng một dự án mà không ảnh hưởng đến công việc của nhau. Dưới đây là một số đặc điểm chính của Git:

1. **Phân tán**: Mỗi người dùng có một bản sao đầy đủ của kho lưu trữ, bao gồm toàn bộ lịch sử thay đổi. Điều này giúp tăng cường tính linh hoạt và khả năng phục hồi của hệ thống.

2. **Hiệu suất cao**: Git được thiết kế để xử lý các dự án lớn với tốc độ nhanh. Các thao tác như commit, merge, và branch đều được thực hiện một cách hiệu quả.

3. **Bảo mật**: Git sử dụng SHA-1 để đảm bảo tính toàn vẹn của dữ liệu. Mỗi commit được xác định duy nhất bằng một mã băm (hash) SHA-1.

4. **Linh hoạt**: Git hỗ trợ nhiều mô hình làm việc khác nhau, từ các dự án nhỏ đến các dự án lớn với hàng ngàn cộng tác viên.

5. **Cộng đồng lớn**: Git có một cộng đồng người dùng và nhà phát triển lớn, cung cấp nhiều tài liệu, công cụ và hỗ trợ.

Git thường được sử dụng cùng với các dịch vụ lưu trữ mã nguồn như GitHub, GitLab, và Bitbucket để quản lý mã nguồn và cộng tác trong các dự án phần mềm.

### 🔥Cài đặt Git

#### Windows

1. Tải xuống và cài đặt Git từ [git-scm.com](https://git-scm.com/download/win).
2. Chạy file cài đặt và làm theo các bước hướng dẫn trên màn hình.
3. Sau khi cài đặt, mở Git Bash để bắt đầu sử dụng Git.

#### macOS

1. Cài đặt Git bằng Homebrew bằng cách mở Terminal và chạy lệnh:

   ```
   brew install git
   ```

2. Nếu bạn không có Homebrew, bạn có thể tải xuống và cài đặt Git từ [git-scm.com](https://git-scm.com/download/mac).

#### Linux

1. Mở Terminal.
2. Cài đặt Git bằng cách sử dụng trình quản lý gói của bạn. Ví dụ, trên Ubuntu bạn có thể chạy:

   ```
   sudo apt-get update
   sudo apt-get install git
   ```

3. Xác nhận việc cài đặt bằng cách kiểm tra phiên bản của Git:

   ```
   git --version
   ```

Sau khi cài đặt, bạn có thể cấu hình Git với tên người dùng và email của bạn:

### 🔥Cấu hình Git sau khi cài đặt

Sau khi cài đặt Git, bạn cần cấu hình thông tin cá nhân để sử dụng trong mọi dự án Git. Điều này bao gồm tên người dùng và địa chỉ email của bạn. Đây là các bước để cấu hình Git:

1. Mở Terminal (trên macOS và Linux) hoặc Git Bash (trên Windows).
2. Đặt tên người dùng của bạn:

   ```
   git config --global user.name "Tên của bạn"
   ```

   Tên username lúc đăng ký github

3. Đặt địa chỉ email của bạn:

   ```
   git config --global user.email "email@example.com"
   ```

### 🔥 Cách lệnh Git

Dưới đây là một số lệnh Git cơ bản mà bạn cần biết:

1. **git init**: Khởi tạo một kho lưu trữ Git mới.

   ```
   git init
   ```

2. **git clone**: Sao chép một kho lưu trữ từ xa về máy tính của bạn.

   ```
   git clone <repository_url>
   ```

3. **git status**: Kiểm tra trạng thái của kho lưu trữ, xem các thay đổi nào đã được staged, unstaged hoặc untracked.

   ```
   git status
   ```

4. **git add**: Thêm các thay đổi vào staging area để chuẩn bị commit.

   ```
   git add <file_name>
   git add .
   ```

5. **git commit**: Ghi lại các thay đổi từ staging area vào kho lưu trữ.

   ```
   git commit -m "Thông điệp commit"
   ```

6. **git push**: Đẩy các commit từ kho lưu trữ cục bộ lên kho lưu trữ từ xa.

   ```
   git push origin <branch_name>
   ```

7. **git pull**: Kéo các thay đổi từ kho lưu trữ từ xa về kho lưu trữ cục bộ.

   ```
   git pull origin <branch_name>
   ```

8. **git branch**: Quản lý các nhánh trong kho lưu trữ.
   - Tạo một nhánh mới:

     ```
     git branch <branch_name>
     ```

   - Xem danh sách các nhánh:

     ```
     git branch
     ```

9. **git checkout**: Chuyển đổi giữa các nhánh hoặc khôi phục các tệp.

   - Chuyển sang một nhánh khác:

     ```
     git checkout <branch_name>
     ```

   - Tạo và chuyển sang một nhánh mới:

     ```
     git checkout -b <branch_name>
     ```

    - Tạo một bản sao từ nhánh khác và nhảy sang:

        ```
        git checkout -b <new_branch_name> <target_branch_name> 
        ```

10. **git merge**: Hợp nhất các thay đổi từ một nhánh khác vào nhánh hiện tại.

    ```
    git merge <branch_name>
    ```

11. **git log**: Xem lịch sử commit của kho lưu trữ.

    ```
    git log
    ```

12. **git diff**: So sánh sự khác biệt giữa các commit, nhánh, hoặc tệp.

    ```
    git diff
    ```

13. **git branch -d**: Xóa một nhánh cục bộ.

    ```
    git branch -d <branch_name>
    ```

14. **git push origin --delete**: Xóa một nhánh từ xa.

    ```
    git push origin --delete <branch_name>
    ```

Những lệnh trên chỉ là một phần nhỏ trong số rất nhiều lệnh mà Git cung cấp. Tuy nhiên, chúng là những lệnh cơ bản và thường được sử dụng nhất trong quá trình làm việc với Git.

### 🔥 Git Branch

Git Branch là một tính năng mạnh mẽ của Git, cho phép các nhà phát triển tạo ra các nhánh độc lập để phát triển tính năng mới, sửa lỗi, hoặc thử nghiệm mà không ảnh hưởng đến nhánh chính (thường là nhánh `main` hoặc `master`). Việc sử dụng các nhánh giúp quản lý phiên bản và phát triển song song trở nên dễ dàng và hiệu quả hơn.

#### Tại sao cần sử dụng Git Branch?

- **Phân tách công việc**: Mỗi nhánh có thể đại diện cho một tính năng mới hoặc một bản sửa lỗi, giúp phân tách công việc rõ ràng.
- **Không làm ảnh hưởng đến nhánh chính**: Các nhà phát triển có thể thoải mái thử nghiệm và phát triển trên nhánh của mình mà không sợ ảnh hưởng đến hoạt động chính của dự án.
- **Dễ dàng hợp nhất**: Khi một tính năng mới hoàn thành, nhánh đó có thể dễ dàng được hợp nhất trở lại với nhánh chính thông qua pull request, cho phép đánh giá và thảo luận trước khi tích hợp.

#### Ví dụ minh họa

Giả sử bạn đang làm việc trên một tính năng mới cho ứng dụng của mình và bạn không muốn các thay đổi của mình ảnh hưởng đến code chính đang hoạt động. Bạn có thể tạo một nhánh mới từ nhánh chính và gọi là `feature-x`.

1. **Tạo nhánh mới**:

   ```
   git branch feature-x
   ```

2. **Chuyển sang nhánh mới**:

   ```
   git checkout feature-x
   ```

   Hoặc bạn có thể sử dụng một lệnh để tạo và chuyển nhánh:

   ```
   git checkout -b feature-x
   ```

3. Sau khi hoàn thành công việc, bạn có thể chuyển lại nhánh chính và hợp nhất nhánh `feature-x`:

   ```
   git checkout main
   git merge feature-x
   ```

Sử dụng các nhánh trong Git không chỉ giúp quản lý dự án một cách hiệu quả mà còn tạo điều kiện cho việc cộng tác và phát triển đa nhánh, từ đó nâng cao năng suất và chất lượng sản phẩm cuối cùng.

### 🔥 Quy trình Release ứng dụng với Github, tạo tag, phiên bản

---

## 💛 GitHub Actions

### 🔥 GitHub Actions là gì ?

GitHub Actions là một tính năng CI/CD của GitHub, cho phép tự động hóa các quy trình làm việc (workflows) ngay trong kho lưu trữ GitHub của bạn. Với GitHub Actions, bạn có thể tự động hóa, tùy chỉnh và thực thi các quy trình phát triển phần mềm của mình ngay trong GitHub. Bạn có thể viết các tác vụ riêng lẻ, gọi là actions, và kết hợp chúng thành một quy trình làm việc để chạy các script sau khi xảy ra sự kiện nhất định trong kho lưu trữ của bạn, chẳng hạn như đẩy mã mới (push) hoặc yêu cầu kéo (pull request).

Các tính năng chính của GitHub Actions bao gồm:

- **Tự động hóa quy trình làm việc**: Tự động hóa mọi khía cạnh của quy trình làm việc, từ việc kiểm tra và triển khai mã, đến quản lý vấn đề và phát hành phần mềm.
- **Hỗ trợ ngôn ngữ và hệ điều hành đa dạng**: Hỗ trợ nhiều ngôn ngữ lập trình và hệ điều hành, cho phép bạn chạy các quy trình làm việc trên Linux, macOS, Windows, ARM, và Docker.
- **Tích hợp sâu với GitHub**: Dễ dàng triển khai các quy trình làm việc với mã nguồn của bạn mà không cần rời khỏi GitHub.
- **Cộng đồng và thị trường**: Truy cập vào thị trường của GitHub để tìm và chia sẻ actions đã được xây dựng sẵn, hoặc tạo và chia sẻ actions của riêng bạn với cộng đồng.

Để minh họa, chúng ta sẽ tạo một quy trình làm việc đơn giản sử dụng GitHub Actions để tự động kiểm tra và triển khai một ứng dụng web mỗi khi có thay đổi được đẩy lên nhánh `main`.

### 🔥 Triển khai GitHub Actions

#### Bước 1: Tạo một tệp YAML cho GitHub Actions

Trong thư mục `.github/workflows` của kho lưu trữ, tạo một tệp mới có tên `ci-cd.yml`. Nội dung của tệp này sẽ định nghĩa các bước cần thiết để thực hiện quy trình kiểm tra và triển khai.

```yaml
```
