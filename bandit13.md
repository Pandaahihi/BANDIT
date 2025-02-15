Đầu tiên ta sẽ tạo ra 1 file tạm trong /tmp\
![alt text](image/13.1.png.png)\

Sau đó ta coppy file data từ thư mục chính vào trong thư mục hiện tại. Tiếp theo ta sẽ reverse lại file hexdump này với xxd\
![alt text](image/13.2.png.png)\

Xác định loại file bằng lệnh file\
![alt text](image/13.3.png)\

Sau đó thêm định dạng file vào sau tên file và giải nén cho file. Và ta dc 1 file mới file1\
![alt text](image/13.4.png)\

Tiếp tục làm lại các bước như trên cho đến khi nhận dc flag\
![alt text](image/13.5.png)\

![alt text](image/13.6.png)\

![alt text](image/13.7.png)\

![alt text](image/13.8.png)\

![alt text](image/13.9.png)\

![alt text](image/13.10.png)\

![alt text](image/13.11.png)\

![alt text](image/13.12.png)\

Ta thấy file data8.bin là file ascii. Mở ra và nhận dc flag