# Department Manager

### Mô tả
Cơ sở dữ liệu Company của một Công ty lưu trữ thông tin chi tiết về Nhân viên, Phòng ban mà nhân viên làm việc, Dự án mà nhân viên tham gia và Người phụ thuộc của nhân viên đó.
- Công ty có một số phòng ban.
- Mỗi phòng ban có thể có nhiều Địa điểm làm việc (Location).
- Các phòng ban (Department) được xác định bằng Mã phòng ban (D_No), Tên phòng ban (Name), Địa điểm phòng ban (Location).
- Mỗi phòng ban sẽ có một nhân viên làm Trưởng phòng.
- Mỗi phòng ban quản lý một số dự án (Project).
- Nhân viên (Employee) được xác định theo Mã nhân viên (Id), tên (Name), địa chỉ (Address), giới tính (Gender), ngày sinh (DOB), ngày vào công ty (DOJ).
- Một nhân viên chỉ làm việc trong một phòng ban nhưng có thể làm việc trên một số dự án.
- Chúng ta cũng theo dõi số giờ làm việc của một nhân viên trong một số dự án.
- Mỗi nhân viên đều có người phụ thuộc.
- Người phụ thuộc (Dependent) có tên (Dependent_name), giới tính (Gender), mối quan hệ (cha/mẹ/vợ/chồng...)

### Công việc
- Tạo CSDL Company và định nghĩa cấu trúc các bảng trong Laravel.
- Dùng Seeder/Faker để sinh dữ liệu giả.
- Thực hiện các chức năng: Hiển thị, thêm, sửa, xóa phòng ban.
