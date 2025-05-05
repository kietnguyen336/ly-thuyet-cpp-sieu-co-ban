<div align="center" >

# Mảng 1 chiều
</div>

## Định nghĩa
- Mảng 1 chiều là cấu trúc dữ liệu (data structure) dùng để lưu trữ nhiều phần tử có cùng kiểu dữ liệu, các phần tử trong mảng được lưu trữ tại các ô nhớ cạnh nhau trong bộ nhớ
## Tính chất
- Đơn giản và dễ sử dụng
- Thuận tiện trong việc truy xuất giá trị của các phần tử
- Các phần tử trong mảng được gán chỉ số để thuận tiện trong việc quản lý
- Là cấu trúc dữ liệu được sử dụng nhiều nhất  
- Kích thước cố định, không thể mở rộng và thu hẹp
## Cú pháp
```
(Kiểu dữ liệu) (Tên mảng)[Số lượng phần tử];
```
### Ví dụ
```C++
int mang_mot_chieu[10];
```
|Khai báo|Ý nghĩa|
|-|-|
|int a[100];|Khai báo mảng chứa các số int tối đa 100 phần tử
float b[1000];|Khai báo mảng chứa các số float tối đa 1000 phần tử
double c[200];|Khai báo mảng chứa các số double tối đa 200 phần tử
char d[20000];|Khai báo mảng chứa các ký tự tối đa 20000 phần tử

## Nên nhớ
- Vị trí phần tử trong mảng luôn bắt đầu từ 0
```c++
int a[5] = {5, 3, 6, 8, 10};
```
|Vị trí|Giá trị|
|-|-|
|0|5|
|1|3|
|2|6|
|3|8|
|4|10|


