<div align="center" >
  
# Struct( Cấu trúc )
</div>

### Định nghĩa
- struct (viết tắt của structure, nghĩa là "cấu trúc") là một kiểu dữ liệu do người dùng định nghĩa, cho phép nhóm nhiều biến khác kiểu (hoặc cùng kiểu) lại với nhau thành một đơn vị logic duy nhất

### Cú pháp
```c++
struct tenCauTruc {
    kieu_du_lieu1 ten_bien1;
    kieu_du_lieu2 ten_bien2;
    ...
};
```
### Ví dụ
```c++
#include <stdio.h>
#include <string.h>

// Khai báo struct
struct SinhVien {
    char ten[50];
    int tuoi;
    float diemTB;
};

int main() {
    // Khởi tạo biến struct
    struct SinhVien sv1;

    // Gán giá trị cho các thành phần
    strcpy(sv1.ten, "Nguyen Van A");
    sv1.tuoi = 20;
    sv1.diemTB = 8.5;

    // In ra thông tin
    printf("Thong tin sinh vien:\n");
    printf("Ten: %s\n", sv1.ten);
    printf("Tuoi: %d\n", sv1.tuoi);
    printf("Diem trung binh: %.2f\n", sv1.diemTB);

    return 0;
}
```

