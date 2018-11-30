## Hướng dẫn sử dụng Markdown 
### Mục lục
[1. Thẻ tiêu đề](#thetieude)

[2. Kiểu chữ](#kieuchu)

[3. Kiểu danh sách](#kieudanhsach0

[4. Trích dẫn, bo chữ](#trichdan,bochu)

[5. Tạo bảng](#taobang)

[6. Chèn link, chèn ảnh](#chenlink,chenanh)
*********************************

<a name="thetieude"></a>
### 1. Thẻ tiêu đề
Markdown sử dụng các ký tự `#` để đánh dấu các tiêu đề. Mức độ các tiêu đề sẽ giảm dần từ 1 đến 6 tương ứng vứi từ 1 đến 6 ký tự `#` liên tiếp 

Ví dụ dòng lệnh 
`# Thẻ cấp 1
## Thẻ cấp 2 
### thẻ cấp 3`
Kết quả là:
# Thẻ cấp 1
## Thẻ cấp 2 
### Thẻ cấp 3
<a name="kieuchu"></a>
### 2. Kiểu chữ
Nội dung không nằm trong thẻ nào, Markdown mặc định sẽ nằm trong thẻ `p` của html
- Sử dụng ký tự `_` hoặc `*` để in nghiêng
Ví dụ: 
`_Chữ in nghiêng_
* Chữ in nghiêng*`
Kết quả là:
_Chữ in nghiêng_
* Chữ in nghiêng*
- Sử dụng ký tự `__` hoặc `**` để in đậm
Ví dụ:
`**In đậm**`
Kết quả là:
**In đậm**
<a name="kieudanhsach"></a>
### 3. Kiểu danh sách
- Để đánh dấu 1 danh sách không có thứ tự ta sử dụng các ký tự `-`, `*`, `+` trước mỗi dòng.
Ví dụ: 
`- Danh sách 1
- Danh sách 2
- Danh sách 3`
Kết quả là:
- Danh sách 1
- Danh sách 2
- Danh sách 3
- Đánh dấu 1 danh sách có thứ tự ta sử dụng các số
Ví dụ: 
`1. Danh sách 1
2. Danh sách 2
3. Danh sách 3`
Kết quả là:
1. Danh sách 1
2. Danh sách 2
3. Danh sách 3
<a name="trichdan,bochu"></a>
### 4. Trích dẫn, bo chữ
Để bo 1 đoạn text sử dụng ``
Ví dụ: 
```
`Bo đoạn text`
```
Kết quả là:
`Bo đoạn text`

Làm nổi bật đoạn cần bo
Ví dụ:
```sh
<a name="taobang"></a>
### 5. Tạo bảng
```sh|Thời khóa biểu|Thứ 2| Thứ 3| Thứ 4|
|Kíp 1| abc| abc| abc|
|Kíp 2| xyz| xyz| xyz|```
Kết quả là:
|Thời khóa biểu|Thứ 2| Thứ 3| Thứ 4|
|Kíp 1| abc| abc| abc|
|Kíp 2| xyz| xyz| xyz|

<a name "chenlink,chenanh"></a>
### 6. Chèn link, chèn ảnh
