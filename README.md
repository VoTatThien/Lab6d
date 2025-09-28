# 🌐 Lap6 - Local Passport Website  

---

## ⚙️ SET UP nơi lưu trữ cho session bằng **FileStore**  
![code in project](images/image1.png)  

---

## 🚫 Truy cập `/profile` khi chưa đăng nhập  
Kết quả: bị chuyển hướng lại trang login vì chưa đăng nhập.  

![code in project](images/image2.png)  

🔒 Đây là **middleware check login** dùng để bảo vệ URI `/profile`.  
👉 Yêu cầu phải đăng nhập mới có thể truy cập.  

---

## 📝 Tiến hành tạo tài khoản  
![code in project](images/image3.png)  

### ✍️ Tạo tài khoản thông qua giao diện website  
![create account](images/image4.png)  

### 🗄️ Kiểm tra database đã có thông tin chưa  
![create account](images/image5.png)  

---

## 🔑 Đăng nhập  

### 📌 Đoạn mã gọi đăng nhập  
![login](images/image7.png)  

### 📌 Đoạn mã kiểm tra tên đăng nhập & mật khẩu  
![login](images/image8.png)  

---

## 💾 Lưu trữ thông tin đăng nhập ở FileStore  
Kết quả khi đăng nhập thành công:  

![FILESTORE](images/image9.png)  

---

## 🏠 Sau khi đăng nhập thành công → vào trang chủ  
![display result](images/image6.png)  


---

## 🚪 Đăng xuất  

- Sau khi đăng xuất, thông tin đăng nhập trong **FileStore** đã bị xóa.  

![result filestore](images/image10.png)  

### 📌 Đoạn mã đăng xuất  
![result LOGOUT](images/image11.png)  

---
