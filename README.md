# 🏥 Website Theo Dõi Sức Khỏe Bệnh Nhân

## 👩‍💻 Thông tin sinh viên
- **Họ và tên:** Lê Thị Thảo  
- **MSSV:** 23110321  

---

## 📌 Giới thiệu dự án
Dự án xây dựng hệ thống website hỗ trợ **theo dõi sức khỏe bệnh nhân**, cho phép người dùng quản lý thông tin cá nhân và cập nhật hồ sơ một cách an toàn.

Hệ thống được xây dựng theo mô hình **3-tier architecture**, đảm bảo tách biệt rõ ràng giữa các tầng xử lý và dễ dàng mở rộng.

---
## 🚀 Chức năng đã thực hiện

### 👤 Edit Profile
- API: `PUT /api/users/profile`
- Cho phép cập nhật:
  - Họ tên
  - Tuổi
  - Giới tính
  - Số điện thoại

### 🔒 Bảo mật API
- Yêu cầu token hợp lệ
- Từ chối truy cập nếu token sai hoặc không có

---

## 🛠️ Công nghệ sử dụng

### 🔹 Backend
- NodeJS
- ExpressJS
- Sequelize ORM
- MySQL
- JWT (JSON Web Token)
- Joi (Validation)

### 🔹 Frontend
- ReactJS
- Tailwind CSS

---

## 🏗️ Kiến trúc hệ thống

Dự án áp dụng mô hình **3 tầng (3-tier architecture):**
