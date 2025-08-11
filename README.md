# 🚀 LOIC - Low Orbit Ion Cannon 🚀

![Ảnh Về Công Cụ DOS Loic](https://github.com/vanmanhgaming2k9/Loic-DDOS/blob/main/Loic.png)

---

## 🔥 Giới thiệu chung

**LOIC (Low Orbit Ion Cannon)** là một công cụ mã nguồn mở được phát triển để thực hiện các cuộc tấn công từ chối dịch vụ phân tán (DDoS - Distributed Denial of Service). Nó được thiết kế để gửi lượng lớn các yêu cầu (request) đến một máy chủ hoặc địa chỉ IP mục tiêu, nhằm làm quá tải hệ thống và khiến dịch vụ bị gián đoạn hoặc ngưng hoạt động.

Công cụ này thường được sử dụng trong các thử nghiệm bảo mật hoặc nghiên cứu, tuy nhiên nó cũng rất dễ bị lợi dụng cho các mục đích tấn công mạng phi pháp.

---

## ⚙️ Cách thức hoạt động

- LOIC gửi hàng ngàn yêu cầu TCP, UDP hoặc HTTP đến mục tiêu với tốc độ rất cao.
- Khi lượng truy cập tăng đột biến, máy chủ mục tiêu sẽ bị quá tải và không thể xử lý hết các yêu cầu, dẫn đến tình trạng nghẽn mạng hoặc sập hệ thống.
- Công cụ này có thể chạy từ một hoặc nhiều máy tính (thường gọi là "botnet") để tạo thành một cuộc tấn công DDoS phân tán.

---

## ✋ Cách phòng chống tấn công từ LOIC

Để bảo vệ hệ thống trước các cuộc tấn công LOIC, bạn có thể áp dụng các biện pháp sau:

1. **Sử dụng tường lửa (Firewall)**  
   - Giới hạn số lượng kết nối đồng thời từ một IP nhất định.
   - Chặn các gói dữ liệu nghi ngờ hoặc không hợp lệ.

2. **Triển khai hệ thống phát hiện và ngăn chặn xâm nhập (IDS/IPS)**  
   - Theo dõi và phát hiện lưu lượng bất thường.
   - Tự động chặn IP hoặc dải IP tấn công.

3. **Sử dụng dịch vụ chống DDoS chuyên nghiệp**  
   - Các nhà cung cấp như Cloudflare, AWS Shield, Akamai... cung cấp các giải pháp chống DDoS hiệu quả.
   
4. **Giới hạn băng thông và tốc độ truy cập (Rate Limiting)**  
   - Giới hạn số lượng yêu cầu từ một địa chỉ IP trong một khoảng thời gian.

5. **Cập nhật phần mềm, hệ điều hành thường xuyên**  
   - Vá các lỗ hổng bảo mật giúp giảm nguy cơ bị tấn công.

---

## ⚠️ Từ chối trách nhiệm (Disclaimer)

⚠️ Công cụ này được phát hành chỉ nhằm mục đích nghiên cứu và kiểm thử bảo mật. Việc sử dụng LOIC để tấn công vào hệ thống hoặc mạng mà bạn không có quyền là **bất hợp pháp** và có thể dẫn đến hậu quả pháp lý nghiêm trọng.

**Chủ sở hữu và người phát triển không chịu trách nhiệm về bất kỳ thiệt hại hoặc hậu quả pháp lý nào phát sinh từ việc sử dụng công cụ này.**

---

## 📋 Hướng dẫn sử dụng

1. Tải file LOIC về máy tính của bạn.  
2. **Tắt phần mềm diệt virus và các tường lửa cá nhân** trên máy tính vì LOIC thường bị chặn do hoạt động bất thường.  
3. Mở phần mềm LOIC bằng quyền quản trị (Run as Administrator) để đảm bảo hoạt động ổn định.  
4. Nhập địa chỉ IP hoặc tên miền của mục tiêu muốn kiểm thử.  
5. Chọn loại tấn công (HTTP, TCP, UDP) và thiết lập các tham số nếu cần.  
6. Nhấn nút **Start** để bắt đầu tấn công.  
7. Để dừng tấn công, nhấn nút **Stop** hoặc đóng phần mềm.

> **Lưu ý:**  
> - Chỉ sử dụng công cụ trên các hệ thống mà bạn được phép kiểm thử.  
> - Hành động tấn công trái phép có thể vi phạm pháp luật và dẫn đến hậu quả nghiêm trọng.

---

## 🔗 Tham khảo

- [LOIC trên GitHub](git@github.com:vanmanhgaming2k9/Loic-DDOS.git)  
- [Tấn công từ chối dịch vụ (DDoS) - Wikipedia](https://en.wikipedia.org/wiki/Denial-of-service_attack)  
- [Hướng dẫn chống DDoS cơ bản](https://www.cloudflare.com/learning/ddos/what-is-a-ddos-attack/)

---

✍️ *Document created by [Your Name]*
