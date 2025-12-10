---
title: "Blog 2"
weight: 1
chapter: false
pre: " <b> 3.2. </b> "
---

### Nghiên cứu với Tốc độ Khám phá: AWS Cloud Bursting Loại bỏ Tắc nghẽn Tính toán


Hãy tưởng tượng bạn vừa có một khám phá đầy hứa hẹn trong nghiên cứu hệ gen, có thể dẫn đến một bước đột phá trong điều trị ung thư. Kết quả sơ bộ rất thuyết phục, nhưng chạy toàn bộ phân tích sẽ tiêu tốn *ba tuần toàn bộ cụm GPU của trường đại học*. Trong khi đó, các nhà nghiên cứu khác cũng đang xếp hàng với những dự án cấp bách.  

Bạn sẽ làm gì — **chờ đợi** và đánh mất đà khám phá quan trọng, hay **thu nhỏ phân tích** và có nguy cơ bỏ lỡ insight quan trọng?

Đây là tình huống diễn ra hàng ngày tại các viện nghiên cứu.

---

## Thế tiến thoái lưỡng nan của tính toán nghiên cứu

Nhu cầu tính toán trong nghiên cứu mang tính “bùng nổ”:  
- cao điểm trong các đột phá và deadline  
- thấp điểm khi bước vào giai đoạn phân tích  

Điều này xung đột với mô hình HPC truyền thống, vốn được thiết kế theo **công suất cố định**.

Các hệ thống HPC của trường đại học thường không thể cung cấp đủ tài nguyên vì giới hạn ngân sách buộc họ chỉ đầu tư để đáp ứng **nhu cầu trung bình**, không phải nhu cầu cao điểm. Điều này đặc biệt đúng với tài nguyên GPU, bộ nhớ cao — nơi thời gian chờ có thể kéo dài **hàng ngày hoặc hàng tuần**.

---

## Tại sao phương pháp truyền thống không hiệu quả

- Hệ thống fixed-capacity không thể đáp ứng khi nhiều nhóm cùng cần tài nguyên đột xuất  
- Budget hạn chế khiến phần cứng không được nâng cấp theo tốc độ phát triển công nghệ  
- Khoảng cách hiệu suất (performance gap) ngày càng lớn do hạ tầng on-prem chậm đổi mới  
- Nghiên cứu bị chậm lại khi các dự án đột phá phải chờ đợi tài nguyên  
- Phần cứng on-prem chỉ được làm mới sau 3–5 năm, trong khi cloud cải tiến liên tục

---

## HPC Bursting hoạt động như thế nào

AWS hợp tác với **Pariveda Solutions** để xây dựng giải pháp HPC bursting cho phép mở rộng cụm HPC on-prem lên cloud mà không cần đầu tư vốn khổng lồ.

### Các thành phần chính:

- **AWS Plugin for Slurm**: tích hợp trực tiếp với Slurm  
- **Tự động provision & cleanup** tài nguyên cloud  
- **Kiểm soát ngân sách** và cơ chế bảo vệ việc sử dụng cloud  
- **Giữ nguyên workflow** – nhà nghiên cứu không phải thay đổi công cụ quen thuộc

### Quy trình:

1. Gửi job vào hệ thống HPC như bình thường  
2. Slurm quyết định có bursting lên AWS hay không  
3. Job được truyền qua **VPN Site-to-Site** hoặc **AWS Direct Connect**  
4. AWS cung cấp EC2 phù hợp  
5. Job chạy xong → EC2 được tắt để tối ưu chi phí

---

## Vượt xa năng lực: Truy cập tài nguyên tiên tiến

HPC bursting mở ra khả năng tiếp cận phần cứng mà on-prem khó có thể sở hữu:

- GPU NVIDIA thế hệ mới nhất  
- CPU Intel / AMD kiến trúc mới  
- AWS Graviton (ARM) tối ưu chi phí/hiệu năng  
- AWS Trainium & Inferentia cho AI/ML  
- FPGA  
- Máy tính lượng tử qua **Amazon Braket**

Không còn chờ hàng tuần để có GPU — mọi thứ có thể dùng **ngay lập tức**.

---

## Truy cập dữ liệu liền mạch

Dữ liệu luôn sẵn sàng cho job dù chạy on-prem hay trên cloud nhờ:

- **Amazon EFS** – mount như network drive  
- **Amazon S3** – lưu trữ object scale vô hạn  
- **Amazon FSx for Lustre** – file system song song cho HPC  
- Hoặc mount trực tiếp từ storage on-prem

---

## Tác động thực tế

Một số ví dụ hiện hữu:

- Mô hình hóa khí hậu chạy dự báo theo giờ thay vì theo tuần  
- Nhóm AI truy cập GPU mới nhất để giữ tốc độ nghiên cứu  
- Hóa học tính toán scale từ 100 → 10.000 lõi  
- Vật liệu học kết hợp HPC truyền thống và lượng tử  

---

## Lợi ích cho nhóm nghiên cứu & IT

### Đối với nhà nghiên cứu:
- Gần như **không có learning curve**  
- Script & workflow giữ nguyên  
- Xác thực giữ nguyên như on-prem  
- Không còn phải thu hẹp mục tiêu nghiên cứu  
- Không còn phải chờ tuần để có GPU

### Đối với đội IT:
- Cân bằng tải thông minh giữa on-prem và cloud  
- Giảm chi phí phần cứng chuyên dụng  
- Quản lý, giám sát tập trung  
- Mô hình chi phí dựa trên usage, không cần capex lớn

---

## Kinh tế của HPC Bursting

- Tiết kiệm **60–80% chi phí** so với mua phần cứng chuyên dụng  
- ROI thường đạt trong **6–12 tháng**  
- Chi phí vận hành phù hợp thực tế hơn so với đầu tư 3–5 năm/lần

---

## Bắt đầu triển khai

### 1. Đánh giá
- Chọn nhóm nghiên cứu thí điểm  
- Xem xét yêu cầu mạng  
- Xác định security & compliance  

### 2. Thiết lập hạ tầng
- Cấu hình kết nối an toàn  
- Tích hợp với hệ thống HPC hiện tại  
- Thiết lập monitoring & logging  

### 3. Triển khai thử nghiệm
- Chạy job thử nghiệm  
- Tối ưu workflow  
- Theo dõi chi phí và hiệu năng  

Job thường khởi chạy trong **2–3 phút**.  
Data sync chạy tự động, gần như không yêu cầu bandwidth lớn — trừ workload nặng dữ liệu sẽ hưởng lợi từ Direct Connect.

---

## Tương lai của tính toán nghiên cứu

HPC bursting đại diện cho tương lai của nghiên cứu khoa học:

- Tận dụng hạ tầng hybrid (on-prem + cloud)  
- Dễ dàng tiếp cận GPU, AI chips, quantum computing  
- Không còn giới hạn bởi phần cứng  
- Nghiên cứu dựa trên cơ hội khoa học thay vì khả năng hạ tầng  

HPC bursting loại bỏ nút thắt cổ chai tính toán, đảm bảo **đột phá khoa học không bị trì hoãn vì thiếu tài nguyên**.

---

