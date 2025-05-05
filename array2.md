<div align="center">

 # Mảng hai chiều 
</div>

## Định nghĩa
- Mảng 2 chiều tương tự như một bảng số gồm hàng và cột, mảng 2 chiều chính là một mảng các mảng 1 chiều
## Cú pháp
```
(Kiểu dữ liệu) (Tên mảng)[hàng][cột];
```
### Ví dụ
```C++
int a[3][3]
```
||0|1|2|
|-|-|-|-|
|0|a[0][0]|a[0][1]|a[0][2]
|1|a[1][0]|a[1][1]|a[1][2]
|2|a[2][0]|a[2][1]|a[2][2]
|3|a[3][0]|a[3][1]|a[3][2]
### Ví dụ với dữ liệu cụ thể
```C++
#include <iostream>

using namespace std;

int main(){
    int a[3][3] = {
        {1, 2, 3},
        {4, 5, 6},
        {7, 8, 9}
    };
    cout << "a[0][1] = " << a[0][1] << endl;
    cout << "a[1][2] = " << a[1][2] << endl; 
    return 0;
}
```
### Kết quả
```C++
a[0][1] = 4
a[1][2] = 6
```
