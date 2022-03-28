### Người thực hiện: Lê Trần Văn Chương
Ngày làm: 21 - 25/03/2022.

Mục lục:

- HTML và vai trò của HTML
- Cấu trúc HTML
- Các thẻ khai báo thông tin web cơ bản
- Các thẻ định dạng chữ viết và văn bản
- Thẻ tạo liên kết và liên kết neo
- Chèn tập tin kỹ thuật số vào web
- Tạo danh sách (List)
- Tạo form nhập liệu
- Task 1 - HTML5

## HTML và vai trò của HTML
- HTML: Là chữ viết tắt của cụm từ HyperText Markup Language. Là ngôn ngữ đánh dấu siêu văn bản

- Vai trò: HTML giúp chia khung sườn, tạo nên bố cục của trang web, định dạng các yếu tố siêu văn bản bao gồm ảnh, video, infographic và nhiều một vài thành phần khác.

## Cấu trúc HTML
### HTML bao gồm 4 yếu tố chính:
- Thẻ khai báo loại tập tin/tài liệu.
- Thẻ đóng và mở tài liệu HTML.
- Thẻ đóng và mở phần thông tin website.
- Thẻ đóng và mở phần nội dung website.

#### Thẻ khai báo loại tập tin:
```html
<!DOCTYPE html>
<html>
</html>
```
- Trong đó, <!DOCTYPE> làm cho trình duyệt web biết được website đang sử dụng phiên bản ngôn ngữ đánh dấu (hay còn gọi markup language) nào.

#### Thẻ đóng và mở tài liệu HTML:
- Thẻ html có nhiệm vụ khai báo cho trình duyệt biết rằng những nội dung bên trong cặp thẻ này là HTML.
- Thẻ html còn có thuộc tính lang để tùy chọn mã ngôn ngữ mà website sử dụng
  
#### Thẻ đóng và mở phần thông tin website:
- Thẻ head chứa phần khai báo thông tin website như meta, title - tên website, style - khai báo CSS, script - khai báo javascript và một số thông tin khác.

#### Thẻ đóng và mở phần nội dung website:
- Thẻ body là phần thân của website, nó chứa toàn bộ nội dung của website.

## Các thẻ khai báo thông tin web cơ bản
### Thẻ title: 
- Có tác dụng khai báo tên cho trang web
- Ví dụ:
    ```html
    <meta charset="utf-8" />
    ```

### Thẻ meta
- Có điểm đặc biệt là dùng /> để đóng thẻ thay vì thẻ đóng.
- Luôn được khai báo kèm theo ít nhất là một thuộc tính và mỗi thuộc tính phải luôn có giá trị.
  - Thuộc tính charset: có nhiệm vụ khai báo cho trình duyệt biết bảng mã ký tự siêu văn bản bên trong tài liệu.
  - Thuộc tính name: luôn đi với thuộc tính content
  - Ví dụ:
    ```html
    <<title>Website sieu cap vip pro</title>/>
    ```
  - Thuộc tính name hỗ trợ một số giá trị như:
    - author: Khai báo tên tác giả của tài liệu.
    - description: Khai báo mô tả của tài liệu.
    - keyword: Khai báo từ khóa của tài liệu, các từ khóa này sẽ giúp tìm kiếm văn bản hoặc máy tìm kiếm website dò tìm (Hiện tại rất ít dùng thuộc tính này).

## Các thẻ định dạng chữ viết và văn bản
### Tiêu đề và đoạn văn bản:
- Thẻ p dùng để khai báo các đoạn văn bản và mỗi đoạn sẽ cách nhau một khoảng nhất định.
- Ví dụ:
  ```html
    <p>Đây là đoạn văn bản thứ 1</p>
    <p>Đây là đoạn văn bản thứ 2</p>
  ```

- Thẻ h dùng khai báo các tiêu đề và có 6 cấp độ.

### Các thẻ định dạng chữ viết:
- strong: In đậm chữ viết.
- i: In nghiêng chứ viết.
- u: Gạch chân chữ viết.
- strike: Gạch ngang chữ viết.
- em: Nhấn mạnh câu.
- code: Định dạng cho một đoạn mã nào đó.
- hr: Thước kẻ ngang trên tài liệu.
- mark: Tô sáng chữ viết.
- quote: Trích dẫn
- pre: Hiển thị ra đúng định dạng khi soạn mà không cần chỉnh sửa
- Ví dụ:
  ```html
    <p>Tên:<strong>Trần Ngọc Nam</strong>, trường <i>Hutech</i>, lớp <u>18DTHD3</u>. Hiện đang là thực tập sinh của <strike>HPT Cyber Security</strike>.</p>

    <hr>

    <p>Tình trạng bản thân<code>FA</code>.</p>

    <p>Điểm trung bình hiện tại: <em>3.70</em>.</p>

    <p><mark>Câu nói thích nhất trong Naruto</mark></p>

    <p>
        <quote>
            <p>Shinra Tensei!</p>
            <cite>Pain - Nagato</cite>
        </quote>
    </p>

    <pre>
    Hello World!
    </pre>
    ```

### Các thuộc tính style để định dạng chữ viết:
- color: màu chữ.
- background: màu nền.
- size: kích thước chữ.
- font-family: font chữ.
- text-align: căn lề chữ.

## Thẻ tạo liên kết và liên kết neo
### Thẻ liên kết - a:
- Tạo ra các đừng liên kết trong HTML.
- Các thuộc tính thường dùng:
  - href: Địa chỉ của tài liệu muốn liên kết đến.
  - title: Tiêu đề của liên kết.
  - target: Xác định nơi mở tài liệu như _blank mở trong của sổ mới, _self (giá trị mặc định) mở trong cửa sổ hiện tại, _self mở trong nội dung trang hiện tại, _parent mở trên khung trình duyệt mẹ của nó.
  - Ví dụ:
    ```html
    <p>Link facebook <a href="https://github.com/bluecrypt47" title="BlueC">BlueC</a></p>
    ```

### Liên kết neo
- Dẫn đến vị trí được đánh dấu trên trang web.
- Khu vực neo sẽ đánh dấu bằng id.
- Thuộc tính `href` của thẻ `a` sẽ chữ `#` + `id` dùng để đánh dấu trước đó.

## Chèn tập tin kỹ thuật số vào web:
### Chèn ảnh:
- Thẻ img dùng để chèn ảnh và không có thẻ đóng.
- Các thuộc tính của thẻ đóng:
	- src : Đường dẫn đến ảnh.
	- title: Tiêu đề ảnh.
	- alt: tên hiển thị lúc kết nổi không ổn định.
- Ngoài ra còn có thuộc tính width và height để chỉnh kích thước ảnh.
- Ví dụ:
  ```html
  <img src="https://lafactoriaweb.com/wp-content/uploads/2020/09/Meme_la_gi_03-600x375.jpg" title="meme" alt="meme" />
  ```

### Chèn tài liệu HTML vào web:
- Thẻ iframe cho phép bạn nhúng một trang web vào web của bạn.
- Các thuộc tính thường dùng src, width, height, name.
- Ví dụ:
  ```html
  <iframe src="http://daotao.hutech.edu.vn/" width="500px" height="800px" scrolling="auto"></iframe>

  Hoặc

  <p><a target="window" href="http://daotao.hutech.edu.vn/">Truy cập</a></p>
  <iframe src="http://thachpham.com" name="window" width="500px" height="800px"></iframe>
  ```
- Lưu ý giá trị thuộc tính target của thẻ a phải trùng với giá trị thuộc tính name của thẻ iframe.

### Chèn đối tượng:
- Thẻ object cho phép chèn nhiều loại dữ liệu như ảnh, video, âm thanh hoặc nhúng trang web vào web của bạn nhưng không tốt bằng các loại thẻ chuyên dụng riêng biệt.
- Các thuộc tính thường dùng data(source), width, height, name, type.
- Ví dụ:
  ```html
  <object data="https://www.w3schools.com/tags/pic_trulli.jpg" width="300" height="200"></object>
  ```

#### Còn chèn cả video, âm thanh và nhạc 3 phần này sẽ trình bày bên `Task 2 - HTML5`
## Tạo danh sách (List):
### Kiểu sắp xếp:
- Danh sách được sắp xếp theo thứ tự bằng số hoặc chữ cái.
- Ví dụ:
  ```html
  <p>Các thể loại Loli:</p>
  <ol type="i">
    <li>Tsudere</li>
    <li>Yandere</li>
    <li>Dandere</li>
    <li>Deredere</li>
    <li>Hinedere</li>
  </ol>
  ```
### Kiểu không sắp xếp:
- Danh sách không được sắp xếp theo thứ tự bằng số hoặc chữ cái mà chỉ được đánh dấu bằng một ký tự đặc trưng.
- Ví dụ:
  ```html
  <p>Các thể loại Loli:</p>
  <ul style="list-style-type: square">
    <li>Tsudere</li>
    <li>Yandere</li>
    <li>Dandere</li>
    <li>Deredere</li>
    <li>Hinedere</li>
  </ul>
  ```
### Kiểu mô tả:
-  Các mục con của danh sách sẽ không được đánh dấu thứ tự, nhưng sẽ có kèm theo một đoạn miêu tả.
-  Ví dụ:
  ```html
  <p>Sơ yếu lí lịch</p>
  <dl>
    <dt>Họ tên:</dt>
    <dd> Trần Ngọc Nam</dd>
    
    <dt>Năm sinh:</dt>
    <dd> 2000</dd>
    
    <dt>Trường:</dt>
    <dd> HUTECH</dd>
    
    <dt>Lớp: </dt>
    <dd> 18DTHD3</dd>
  </dl>
  ```
## Tạo form nhập liệu:
- Để tạo form chúng ta sẽ tạo thẻ form, thẻ này sẽ chứa cac thuộc tính và nội dung của form sẽ được nhập liệu thông qua các thẻ input.
- Ví dụ:
  ```html
  <form action="#" method="post" name="dangnhap">
    Tên đăng nhập:
    <input type="text" name="username" placeholder="Nhập username" /> <br />
    Mật khẩu:
    <input type="password" name="password" placeholder="Nhập mật khẩu" /> <br />
    <input type="submit" name="submit" value="Đăng nhập" />
  </form>
  ```
### Các thuộc tính trong thẻ form:
- action: Đường dẫn đến một trang xử lý dữ liệu sau khi người dùng ấn nút gửi dữ liệu.
- method: Phương thức gửi dữ liệu.
- name: Tên của form.

### Các thuộc tính trong thẻ input:
- type: Loại dữ liệu muốn nhập(23 loại).
- name: Tên của thẻ.
- placeholder: Hiện chữ mờ để gợi ý.
## Task 1 - HTML

Trong task này, tôi sử dụng các tag cơ bản của html để có thể tạo thành 1 trang web cơ bản bằng html. Các tag tôi sử dụng là `<link>`, `<img>`, `<ul> <li>`, `<div>` các thẻ `<h>`, `<a>` và `<p>`.
