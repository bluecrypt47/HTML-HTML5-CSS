#### Người thực hiện: Lê Trần Văn Chương
# Mục lục
- HTML5 là gì?
- HTML5 có gì mới?
- Ưu điểm
- Nhược điểm

## HTML5 là gì?
- Là phiên bản thứ 5 của ngôn ngữ HTML, được giới thiệu bởi World Wide Web Consortium (W3C).
- Giữ lại những đặc điểm cơ bản của HTML4 và bổ sung thêm các đặc tả nổi trội của XHTML, DOM cấp 2, đặc biệt là JavaScript.

## HTML5 có gì mới?
- HTML5 được xây dựng dựa trên các nguyên tắc:
  - Ít phụ thuộc vào các plugin cho các chức năng.
  - Script nên được thay thế bằng markup bất cứ khi nào có thể.
  - Chạy được trên bất kỳ thiết bị.
  - Hỗ trợ và chạy trên bất kỳ trình duyệt nào.
- HTML5 đã bổ sung thêm rất nhiều các thẻ đánh dấu (markup) mới:
  - Các thẻ header và footer.
    ```html
    <header>
        <h1>HTML5 Cho Người Mới Bắt Đầu</h1>
    </header>

    <footer>
            Copyright 2022 - BlueC
    </footer>
    ```
  - Thẻ article giúp xác định một phần cụ thể về nội dung như blog hoặc comment.
    ```html
    <article>
    <p>Tin trong ngày</p>
    <p>Xăng tiếp tục tăng giá "nhè nhẹ"</p>
    </article>
    ```
  - Thẻ nav dùng để bao bọc các vị trí liên quan đến liên kết và điều hướng chính cho trang web. Thường đó sẽ là các menu chính, menu phụ, danh sách chuyên mục bên sidebar,...
    ```html
    <nav>
        <a href="#">HTML</a> |
        <a href="#">CSS</a> |
        <a href="#">JavaScript</a> |
        <a href="#">jQuery</a>
    </nav>
    ```
  - Các thẻ audio và video để đánh dấu những nội dung bao gồm âm thanh hoặc video.
    ```html
    <video width="200" height="auto" control>
        <source src="https://www.w3schools.com/tags/movie.mp4" type="video/mp4">
        Trình duyệt của bạn không hỗ trợ HTML5.
    </video>

    <audio width="200" height="auto" control>
        <source src="https://www.w3schools.com/tags/horse.mp3" type="audio/mp3">
        Trình duyệt của bạn không hỗ trợ HTML5.
    </audio>
    ```
  - Thẻ section dùng để khai báo cho các vị trí trên giao diện của một trang web.
    ```html
    <section id="sidebar">
        <section id="vitri1"> 
        </section>

        <section id="vitri2">
        </section>

        <section id="vitri3">
        </section>
    </section>
    ```
  - Thẻ hgroup dùng để gom nhóm các thẻ từ h1 -> h6 lại với nhau, với điều kiện là các thẻ h này phải nằm chung trong một thẻ header.
    ```html
    <header>
        <hgroup>
            <h1>TIêu đề chính</h1>
            <h2>Tiêu đề phụ</h2>
        </hgroup>
    </header>
    ```
  - Thẻ aside dùng trong các vị trí nằm một bên như sidebar.
    ```html
    <aside>
        <h3>Học lập trình</h3>
        <a href="#">Học C++</a>
        <a href="#"> Học Javascript</a>
        <a href="#">Học Python</a>
    </aside>
    ```
  - Thẻ canvas cho phép bạn vẽ đồ họa sử dụng một ngôn ngữ kịch bản riêng biệt.
    ```html
    <h3>Thực hành về Canvas</h3>
    <canvas id="myCanvas" style="border: 1px solid #888; height: 300px; width: 600px;"></canvas>

    Sau đó khai báo script để thực hiện vẽ đường thẳng:
    <script type="text/javascript">
        var canvas = document.getElementById('myCanvas'),
        ctx = canvas.getContext('2d');
        ctx.strokeStyle = "#FF0000";
        ctx.moveTo(0,0);
        ctx.lineTo(200,100);
        ctx.stroke();
    </script>
    ```
  - Thẻ embed dùng để nhúng các nội dung hoặc các ứng dụng bên ngoài vào trang web.
    ```html
    <embed src="html.swf" />
    ```
- HTML5 cũng bỏ đi một số thẻ: `acronym, applet, font, frame, frameset, noframes,...`
- HTML5 không còn thuộc tính type trong thẻ `script` và `link`.
- HTML5 sử dụng web SQL databases, application cache để lưu dữ liệu tạm trong khi HTML chỉ có cache của trình duyệt.
- HTML5 hỗ trợ hoàn toàn cho JavaScript để chạy nền nhờ vào JS web worker API.
  
## Ưu điểm:
- Đa nền tảng và responsive.
- Hỗ trợ âm thanh và video.
- Có nhiều layout elements hơn cho nội dung.
- Xử lý lỗi tốt hơn.

## Nhược điểm:
- Yêu cầu các trình duyệt hiện đại để sử dụng.
- Vấn đề bản quyền.
- HTML5 vẫn đang hoàn thiện từng ngày.
## Task 2 - HTML5

Trong task này, tôi sử dụng các tag cơ bản của html để có thể tạo thành 1 trang web cơ bản bằng html5. Các tag tôi sử dụng là `<link>`, `<img>`, `<ul> <li>`, `<div>` ,các thẻ `<h>`, `<a>` và `<p>`, `<audio>`, `iframe` và `<video>`.
