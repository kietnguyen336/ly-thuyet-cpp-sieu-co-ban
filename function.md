<div align="center">
  
# HÀM
</div>

## Định nghĩa
- Hàm (function) là một các khối lệnh có nhiệm vụ thực hiện một chức năng nào đó.
![image](https://github.com/user-attachments/assets/f36339b8-7781-41ea-83f1-9503c56e95ba)

### Cú pháp
```
[kiểu dữ liệu] [tên hàm] ( [kiểu dữ liệu 1] [tham số 1], [kiểu dữ liệu 2] [tham số 2],...){
  // ...code...
}
```
### Ví dụ
```C++
int vidu (int ngu, bool checkIQ){
  // ...code...
}
```
- kiểu dữ liệu : Kiểu trả về của hàm, có thể là các kiểu dữ liệu như int, long long, float, char, double, hoặc void (tương ứng với kiểu trả về là rỗng)
- tên hàm : Tên của hàm, cần tuân theo quy tắc như đặt tên biến ( rắn (day_la_kieu_ran ) , hoặc lạc đà ( dayLaKieuLacDa ) )
- tham số : Tham số của hàm, đây được coi như đầu vào của hàm. Có thể xây dựng bao nhiêu tham số tùy ý và lựa chọn kiểu dữ liệu cho từng tham số.
- code : Các câu lệnh bên trong của hàm

## Cách gọi hàm
![image](https://github.com/user-attachments/assets/ef4ea69c-c437-4f85-8d99-5f3634b586a4)
### Ví dụ

```C++
#include <iostream>
using namespace std;

void check(){
  cout << "Nghe bài trình chưa ??";
}

// Hàm chính ( hàm chương trình chính - hàn chạy đầu tiên khi biên dịch )
int main(){
  // gọi hàm check
  check()
  return 0;
}
```

## Đối số (Argument) và Tham số (Parameter)
- Tham số : Là "chỗ trống" để hàm có thể nhận giá trị khi được gọi ( giống như khai báo biến nhưng chưa có giá trị )
- Đối số : Là dữ liệu thực tế truyền vào để chạy hàm ( giống như khai báo biến nhưng đã có sẵn giá trị )

|Đặc điểm | Tham số (Parameter) | Đối số (Argument) |
|-|-|-|
|Vị trí|Trong định nghĩa/khai báo hàm|Trong lúc gọi hàm|
|Vai trò|Biến trung gian trong hàm|Giá trị thực tế cung cấp cho hàm|
|Ví dụ| int value (int a, int b) | value(4,5) |

