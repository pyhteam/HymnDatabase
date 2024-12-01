Mục bình luận của [Luyện Code](https://luyencode.net) có sử dụng Markdown để tiện cho chúng ta sử dụng. Hướng dẫn ngắn gọn sau đây sẽ giúp bạn sử dụng markdown cơ bản để viết bình luận đẹp hơn. Tại mỗi ví dụ, phía trên sẽ là ví dụ và phía dưới sẽ là kết quả của ví dụ đó.

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgist.github.com%2Fnguyenvanhieuvn%2Fd3e5e20c44ef9d565fa3d7b9ebabfc65&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=views&edge_flat=true)](https://hits.seeyoufarm.com)

- [Quy tắc thảo luận](#quy-tắc-thảo-luận)
- [Cách chèn code](#cách-chèn-code)
- [Cách ẩn lời giải](#cách-ẩn-lời-giải)
- [Hiệu ứng chữ](#hiệu-ứng-chữ)
- [Chèn ảnh](#chèn-ảnh)
- [Trả lời bình luận](#trả-lời-bình-luận)
- [Tài liệu đầy đủ](#tài-liệu-đầy-đủ)

# Quy tắc thảo luận
- Không đăng các nội dung SPAM
- Không bình luận ngoài chủ đề LẬP TRÌNH
- Các nội dung chia sẻ gợi ý, source cần được ẩn (Xem hướng dẫn [Cách ẩn lời giải](#cách-ẩn-lời-giải))
- Tuyệt đối không để lộ thông tin cá nhân (email, facebook, số điện thoại, ...) để bảo vệ chính mình

# Cách chèn code
Có 2 chế độ chèn code là inline và block.
## Chèn code inline
```
Tìm `x` biết `x + 2 = 5`
```
Tìm `x` biết `x + 2 = 5`

## Chèn block code

Đối với chèn block code, bạn để code vào trong cặp 3 dấu "```" (là phím dưới phím `ESC` đó). Ví dụ:

<pre>
```cpp
#include <stdio.h>
int main() {
  printf("Lap Trinh Khong Kho!");
  return 0;
}
```
</pre>

```cpp
#include <stdio.h>
int main() {
  printf("Lap Trinh Khong Kho!");
  return 0;
}
```
**Lưu ý:** Bạn có thể sử dụng nhãn sau để làm đẹp code theo ngôn ngữ nhé:

- `cpp`: Ngôn ngữ C/C++
- `java`: Ngôn ngữ Java
- `py`: Ngôn ngữ Python
- `go`: Ngôn ngữ Golang
- Mặc định nếu không điền sẽ là `txt` và không có màu mè gì hết.

# Cách ẩn lời giải
- Các bạn **không nên** đăng code đã được Accecpted của mình vào mục bình luận này. Thay vì đăng lời giải, hãy đăng gợi ý cách làm.
- Nếu bạn đăng gợi ý, hãy ẩn nó đi để người khác chỉ thấy khi họ thực sự cần được giúp đỡ:

```
Đây là lời giải của mình đã AC. Nếu bạn đã cố gắng mà chưa làm được thì có thể tham khảo lời giải của mình.
<details><summary>Xem code AC</summary>
<p>

// Khối code ở đây, theo hướng dẫn cách chèn code ở trên. (để thừa 1 khoảng trắng phía trước và sau).

</p>
</details>
```

Đây là lời giải của mình đã AC. Nếu bạn đã cố gắng mà chưa làm được thì có thể tham khảo lời giải của mình.
<details><summary>Xem code AC</summary>
<p>

// Khối code ở đây, theo hướng dẫn cách chèn code ở trên. (để thừa 1 khoảng trắng phía trước và sau).

</p>
</details>

# Hiệu ứng chữ
## Chữ bôi đậm
```
**Dòng này được bôi đậm**
```

**Dòng này được bôi đậm**

## Chữ in nghiêng

```
_Dòng này được in nghiêng_
```
_Dòng này được in nghiêng_

# Chèn ảnh
Đầu tiên, hãy upload ảnh của bạn lên một host nào đó. Ví dụ như https://imgur.com/. Sau đó copy đường dẫn ảnh có kết thúc là `jpg`, `png`, ... và chèn vào như sau:

```
![thẻ alt của ảnh](đường dẫn ảnh)
```

**Ví dụ:**
```
![Just a fun gif](https://media.giphy.com/media/PiQejEf31116URju4V/giphy.gif)
```
![Just a fun gif](https://media.giphy.com/media/PiQejEf31116URju4V/giphy.gif)

# Trả lời bình luận
Bạn có thể nhắc (mention) người đó hoặc trích dẫn bình luận của người đó để trả lời.
## Trích dẫn

Ví dụ:

```
> Khi nào thì phép chia không thực hiện được?

Khi số chia bằng 0
```

Kết quả:

> Khi nào thì phép chia không thực hiện được?

Khi số chia bằng 0

## Nhắc tên
Copy username của người đó và thêm `@` vào trước username đó.

Ví dụ, username của một bạn nào đó là `nguyenvanhieuvn` thì ta có thể nhắc tên như sau:
```
@nguyenvanhieuvn đúng rồi bạn
```
Kết quả thì nó chỉ hoạt động trên chỗ comment của web thôi =))))

# Tài liệu đầy đủ
1. [Full hướng dẫn sử dụng Markdown](https://guides.github.com/features/mastering-markdown/)
