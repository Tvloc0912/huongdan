
<h1>Đối với Replit - Dùng trên ĐT hoặc PC</h1> 

**Công cụ cần chuẩn cài đặt**

- **Một tài khoản trên [Replit](https://replit.com/)**

**Thứ tự các thao tác trên [Replit](https://replit.com/)**

- **+ New repl**
- Qua tab **Import from github**
- Nhập link **github** vào **from** và **click** vào nút **Import from github**
- Đợi repl **Cloning**
- Chọn **select language** là **Bash** và **configure the run button** là **npm start** xong rồi ấn **done**
- Đợi tầm 10s nếu không tự **refesh trang thì refesh thủ công bằng phím F5 hoặc nút refesh trên thanh địa chỉ**

**Cách cài đặt - gõ từng lệnh theo thứ tự dưới đây và đợi cài đặt**

- Chuyển qua tab **console** và gõ các lệnh theo thứ tự sau:
- **npm install** - đợi khoảng 3-5p tùy theo tốc độ mạng
- **npm audit fix**
- **Ấn nút run trên màn hình** - đợi khoảng 3-5p tùy theo tốc độ mạng
- **Lưu Ý: Khi cài đặt xong phải tắt đi và khởi động lại để tránh gặp lỗi không mong muốn.**

**Cách cài đặt treo 24/24 trên uptimerobot**

- Vào chỉnh sửa file **mirai.js**
- Thêm đoạn code sau vào dòng 1 của file **mirai.js**

```diff
const app = require ("express") ();  app.get ('/', (req, res) => {res.send ("Nguyen Manh Tuan");});app.listen(process.env. PORT);    
```

- **npm install express**
- **npm audit fix**
- **Ấn nút run trên màn hình** - đợi khoảng 3-5p tùy theo tốc độ mạng
- **Copy link** ở trang replit. Link có định dạng **https://miraiv2.nameuser.repl.co**
- **Tạo tài khoản trên trang [UptimeRobot](https://uptimerobot.com/)**

**Thứ tự các thao tác trên [UptimeRobot](https://uptimerobot.com/)**


- **+  Add New Monitor**
- **Monitor Type** chọn **HTTP(s)**
- **Friendly Name** đặt tùy ý
- **URL (or IP)**: Dán link vừa copy bên **[Replit](https://replit.com/)** 
- Ấn **tick** vào ô  **Select "Alert Contacts To Notify** (nhận thông báo từ email)
- Ấn **Create Monitor** để hoàn thành quá trình tạo **uptime**


<h1>CÁC LỖI THƯỜNG GẶP PHẢI</h1> 

**UPDATE SOON...**
