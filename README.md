# Giới thiệu
Đã có ai dùng `GitHub` bao lâu nay vẫn không biết các tệp với đuôi mở rộng .md là gì không?

`Markdown` là ngôn ngữ đánh dấu có cú pháp khá đơn giản và dễ hiểu, tạo thuận tiện cho việc chuyển đổi từ văn bản thuần sang HTML.

Thay vì dựa vào `HTML`, `Markdown` cho phép bạn định dạng văn bản mà trực quan hơn nhiều so với `HTML`.

Có thể bạn chưa biết: `Markdown` có thể được sử dụng tại [Github](https://github.com/) và [Discord](https://discord.com/).

>If you can, feel free to translate this repo into other languages, thanks!

>Tài liệu được viết tay bởi [Lục Thiên Phong](https://github.com/lucthienphong1120), để giúp bạn có thêm hiểu biết và làm chủ về Markdown.

# Mục lục
[Sơ lược](https://github.com/kainlee2304/learnMarkdown/edit/main/README.md#i-s%C6%A1-l%C6%B0%E1%BB%A3c)
[1. MarkDown (Markup languages)](https://github.com/kainlee2304/learnMarkdown/edit/main/README.md#1-markdown-markup-languages)
[2. Một số trình soạn thảo Markdown](https://github.com/kainlee2304/learnMarkdown/edit/main/README.md#2-m%E1%BB%99t-s%E1%BB%91-tr%C3%ACnh-so%E1%BA%A1n-th%E1%BA%A3o-markdown)
# I. Sơ lược
## 1. MarkDown (Markup languages)
Sự thật là cái tên __"Markdown"__ chính là một phép chơi chữ của từ __"Markup"__.

Mardown được sử dụng để xuất văn bản thô trên trình duyệt nhưng các ngôn ngữ đánh dấu khác lại có thể giao tiếp trực tiếp với máy tính. Đơn cử như `XML` là một ngôn ngữ đánh dấu văn bản mà cả con người lẫn máy móc có thể đọc được.

Một ngôn ngữ đánh dấu văn bản khác mà mọi người chắc hẳn ai học CNTT cũng biết vì độ nổi tiếng của nó, chính là `HTML`, `Markdown` không mang trong mình sứ mệnh __"Kẻ huỷ diệt HTML"__ hay gì, mà mục đích của nó chính là làm đơn giản hoá việc đánh dấu văn bản và tăng cường tốc độ viết lách một cách đáng kể.

## 2. Một số trình soạn thảo Markdown
- Mac, Windows, và Linux
  - Typora
  - MacDown
- Online
  - StackEdit
  - Dillinger
  - Hashify
- Sau bài viết này, bạn có thể viết md mà không cần chuyển đổi
  - Notepad
  - Visual Studio Code
  - Visual Code
  - Notepad++
  - Vi,nano,...
  - Github,Discord,...
# II. Cách sử dụng
## 1. Văn bản thuần
### 1. Tiêu đề - Heading
Bạn có thể viết loại tiêu đề `<h1>, <h2>,... <h6>` bằng cách thêm các dấu `#` tương ứng vào đầu dòng.

Một dấu `#` tương đương với `<h1>`, hai dấu `#` tương đương với `<h2>` ...

__Cú pháp:__

`` # Tiêu đề loại 1``

``## Tiêu đề loại 2``

``### Tiêu đề loại 3``

``#### Tiêu đề loại 4``

``##### Tiêu đề loại 5``

``###### Tiêu đề loại 6 ``

__Kết quả__

# Tiêu đề loại 1
## Tiêu đề loại 2
### Tiêu đề loại 3
#### Tiêu đề loại 4
##### Tiêu đề loại 5
###### Tiêu đề loại 6

### 2. Đoạn văn - Paragraph

Để xuống dòng giữa các văn bản `<p>`, sử dụng một dòng trống để tách các dòng văn bản.

__Cú pháp:__

``Đây là dòng 1``

``                          ``

``Đây là dòng 2``

__Kết quả:__

Đây là dòng 1

Đây là dòng 2

### 3. Chữ in nghiêng - Italic

Để in nghiêng văn bản `<i>`, thêm một dấu `*` hoặc dấu ` _` trước và sau từ cần in nghiêng.

__Cú pháp:__

``*Từ cần in nghiêng 1*``

``__Từ cần in nghiêng 2_``

__Kết quả:__

*Từ cần in nghiêng 1*

_Từ cần in nghiêng 2_

### 4. Chữ in đậm - Bold

Để in đậm văn bản `<b>`, thêm hai dấu `*` hoặc dấu `_` trước và sau từ cần in đậm.

__Cú pháp:__

``**Từ cần in đậm 1**``

``__Từ cần in đậm 2__``

__Kết quả:__

**Từ cần in đậm 1**

__Từ cần in đậm 2__

### 5. In đậm và in nghiêng

Đơn giản, bạn chỉ cần ba dấu `*` hoặc dấu `_` trước và sau từ đó.

__Cú pháp:__
``***Từ in đậm và in nghiêng 1***``

``___Từ in đậm và in nghiêng 2___``


__Kết quả:__


***Từ in đậm và in nghiêng 1***

___Từ in đậm và in nghiêng 2___

### 6. Chữ gạch giữa - Strikethrough

Để tạo `chữ gạch giữa`, thêm 2 dấu `~` trước và sau từ đó.

__Cú pháp:__

``~~Khuyến mại~~``
__Kết quả:__

~~Khuyến mại~~

### 7. Code trong dòng - Inline Code

Để viết `inline <code>`, bạn dùng 2 dấu ` ` ở trước và sau từ đó.

__Cú pháp:__

``inline code``
__Kết quả:__

`inline code`

## 2. Các khối
### 1. Trích dẫn - Blockquote

Để tạo một `<blockquote>`, thêm dấu `> `vào trước mỗi dòng trích dẫn.

__Cú pháp:__

``> Trích dẫn dòng 1``
``> Trích dẫn dòng 2``
__Kết quả:__

>Trích dẫn dòng 1 
>Trích dẫn dòng 2

### 2. Danh sách có thứ tự - Ordered List
Để tạo danh sách `<ol><li>`, bạn chỉ cần thêm các số, dấu chấm trước nội dung (dùng tab để phân cấp)

__Cú pháp:__

``1. Mục thứ nhất``

``2. Mục thứ hai``

``3. Mục thứ ba``

__Kết quả:__

1. Mục thứ nhất
2. Mục thứ hai
3. Mục thứ ba
### 3. Danh sách không có thứ tự - Unordered List

Để tạo danh sách `<ul><li>`, bạn chỉ cần thêm dấu `*` hoặc `-` hoặc `+` trước nội dung (dùng tab để phân cấp)

__Cú pháp:__

``- Mục thứ nhất``
``- Mục thứ hai``
``- Mục thứ ba``

__Kết quả:__

- Mục thứ nhất
  
- Mục thứ hai
  
- Mục thứ ba
### 4. Khối lệnh - Block Code

Để viết 1 đoạn `<code>`, bạn dùng 3 dấu  ở trước và sau đoạn đó (có thể thêm format ngôn ngữ đó).

__Cú pháp:__

`` \`\`\`image`\`\`\ ``

__Kết quả:__

print("hello world")

### 5. Bảng - Table

Để tạo bảng `<table><tbody><tr><th><th>`, bạn chỉ cần ngăn cách bởi dấu | và cách đầu bảng với thân bảng bằng :--- (số dấu - tuỳ ý)

__Cú pháp:__

``| Cột 1 | Cột 2 | Cột 3 | Cột 4 |``

``| :--- | :--- | :--- | :--- |``

``| A | B | C | D |``

``| E | F | G | H |``

``| I | K | L | M |``

___Kết quả___

| Cột 1 | Cột 2 | Cột 3 | Cột 4 |
| :--- | :--- | :--- | :--- |
| A | B | C | D |
| E | F | G | H |
| I | K | L | M |
## 3. Đặc biệt
### 1. Đường kẻ ngang - Horizonal rules

Để tạo đường kẻ ngang, sử dụng ba dấu `*` hoặc `-` hoặc `_` trên một dòng.

__Cú pháp:__

``---``
``***``
``___``
__Kết quả:__
---
***
___

## 2. Liên kết - Link
Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn liên kết `` <a href="https://github.com">Github</a>, bạn dùng [text](link).``

__Cú pháp:__

``Trực tiếp: https://github.com/lucthienphong1120``

``Gián tiếp: [Github](https://github.com/lucthienphong1120)``
__Kết quả:__

Trực tiếp: https://github.com/lucthienphong1120

Gián tiếp: [Github](https://github.com/lucthienphong1120)

### 3. Hình ảnh - Image
Để chèn trực tiếp, bạn có thể paste thẳng nó như bình thường.

Để dẫn ảnh ``<img src="https://avatars.githubusercontent.com/u/583231 alt="Github">, bạn dùng ![text](link ảnh).``

Hoặc ![](link ảnh) nếu không cần chữ khi hover.

__Cú pháp:__

``![](https://avatars.githubusercontent.com/u/583231)``
__Kết quả:__
![](https://avatars.githubusercontent.com/u/583231)



Để chèn liên kết vào ảnh ``<a href="link"><img src="link ảnh" alt="chữ"></a>`` thì chỉ cần kết hợp đúng cú pháp là được.

``` [ ![chữ](link ảnh) ] (link) ```
### 4. Biểu tượng cảm xúc - Icon
Phần này tuỳ vào nền tảng (Github, Discord, ...) có icon đó không, bạn ghi dấu : và tên icon.

__Cú pháp:__

![](https://user-images.githubusercontent.com/90561566/160245877-ccf277ff-094f-482c-801b-4a8fe46471b7.png)

__Kết quả:__

👁️

> More information: [github](https://github.com/lucthienphong1120/Github-Emojis)

### 5. Checkbox

Để chèn `checkbox/checked` (thường dùng cho to do list trên github) thì ta đánh dấu như list và thêm 1 cặp ngoặc vuông.

__Cú pháp:__

``- [ ] Checkbox``

``- [x] Checked```
__Kết quả:__

- [ ] Checkbox
- [x] Checked
### 6. Escape markdown

Đôi khi bạn sẽ cần những kí hiệu trùng với cú pháp của markdown. Để phân biệt, bạn chỉ cần thêm dấu \ trước những kí hiệu đó là được.

__Cú pháp:__

\`hai dấu nháy\`

\*\*\*ba dấu sao hai bên\*\*\*
Kết quả:

`hai dấu nháy`

***ba dấu sao hai bên***

### III. Kết thúc
Hy vọng qua bài viết này, bạn sẽ không còn thấy `Markdown` khó nữa và sẽ nắm được cách dùng Markdown trong nhiều việc của mình hơn nhé.

Nếu thấy hay hãy đừng ngần ngại mà thả 1 sao cho tôi, chúc bạn 1 ngày làm việc thật tốt!

Bạn có thể thoải mái đóng góp (contribute) hoặc liên kết (fork) dự án này.

You are free to contribute or fork this repo.
Nguồn:[lucthienphong1120](https://github.com/lucthienphong1120/Markdown-syntax?tab=readme-ov-file#3-danh-s%C3%A1ch-kh%C3%B4ng-c%C3%B3-th%E1%BB%A9-t%E1%BB%B1---unordered-list)
