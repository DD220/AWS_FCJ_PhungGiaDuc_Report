---
title: "Blog 3"

weight: 1
chapter: false
pre: " <b> 3.3. </b> "
---

### AWS Transform for .NET hiện đã hỗ trợ hỏi đáp về các báo cáo đánh giá và chuyển đổi  

**Tác giả:** David Pallmann, Vijay Mandadi, Rakshith Ravi Kumar  
**Ngày đăng:** 01/07/2025  
**Danh mục:** .NET, AWS Transform  

---

## Giới thiệu

AWS Transform for .NET giúp tăng tốc quá trình hiện đại hóa quy mô lớn các dự án .NET, bao gồm chuyển đổi từ .NET Framework sang .NET đa nền tảng (cross-platform .NET), cũng như nâng cấp giữa các phiên bản .NET.  

Hôm nay, chúng tôi giới thiệu **tính năng hỏi đáp (Q&A)** mới cho phép bạn truy vấn thông tin chuyên sâu về các job chuyển đổi thông qua **giao diện chat trên web console**.

Tính năng này cho phép bạn đặt câu hỏi bằng **ngôn ngữ tự nhiên** về báo cáo đánh giá repository và báo cáo chuyển đổi. Các báo cáo này thường dài và phức tạp — đặc biệt khi làm việc với nhiều repository — nên việc có thể hỏi trực tiếp giúp bạn thao tác nhanh và hiệu quả hơn.

*(Lưu ý: Tính năng chat chỉ hỗ trợ trên web console, chưa hỗ trợ trong IDE.)*

---

## Các truy vấn Assessment (Assessment Queries)

Khi bạn thiết lập một job chuyển đổi .NET, AWS Transform sẽ tiến hành **đánh giá (assessment)** các repository đã chọn.  
Bạn có thể tải báo cáo đánh giá dưới dạng **HTML hoặc JSON** từ tab **Collaboration**.

Báo cáo đánh giá cung cấp thông tin như:

- Chủ sở hữu repository  
- Nhánh được đánh giá  
- Số lượng solution  
- Số lượng project  
- Tổng dòng code  
- Phiên bản .NET được phát hiện  
- Loại project  
- Số lượng dependency NuGet public/private  
- Mức độ phức tạp của chuyển đổi  

Khi báo cáo đã hoàn tất, tab **Worklog** sẽ hiển thị thông báo:  
**“Assessment report is now available in chat for queries.”**

Để mở chat, chọn biểu tượng hình lục giác màu tím ở góc phải phía dưới giao diện.

### Ví dụ truy vấn Assessment:

Hệ thống chat sẽ đọc báo cáo đánh giá và trả về câu trả lời tương ứng.

---

## Các truy vấn Transformation (Transformation Queries)

Khi quá trình chuyển đổi hoàn tất (cho một repository hoặc toàn bộ job), AWS Transform sẽ tạo **báo cáo chuyển đổi**.

Tab **Dashboard** hiển thị trạng thái của từng repository:

- In-progress (Đang xử lý)  
- Success (Thành công)  
- Failed (Thất bại)  

Bạn có thể tải về báo cáo hoặc truy vấn trực tiếp qua chat.

### Ví dụ truy vấn Transformation:

Ví dụ:

- Truy vấn **“What changes were made to the hello-bedrock repository?”**  
  → Chat sẽ giải thích về nâng cấp từ .NET 6 lên .NET 8, cập nhật SDK Bedrock, cải tiến project structure, các thay đổi phục vụ migration analysis...

- Truy vấn **“What packages were upgraded in the mathcore-main project?”**  
  → Phản hồi sẽ liệt kê các package nâng cấp như NUnit, FluentAssertions, Microsoft.NET.Test.Sdk...

---

## Cung cấp phản hồi (Providing Feedback)

Nếu chat không hiểu câu hỏi của bạn, bạn có thể nhận phản hồi chung.  
Cách khắc phục:

- Làm rõ câu hỏi (bạn đang hỏi về báo cáo **đánh giá** hay **chuyển đổi**)  
- Tải và xem trước các báo cáo để hiểu cấu trúc thông tin  

Bạn có thể hỗ trợ AWS cải thiện hệ thống bằng cách dùng nút 👍 / 👎 dưới mỗi câu trả lời.  
Khi bấm, bạn có thể nhập lý do đánh giá — AWS rất hoan nghênh phản hồi này.

---

## Kết luận

Bài viết đã chia sẻ cách truy vấn AWS Transform for .NET bằng ngôn ngữ tự nhiên để lấy thông tin về:

- Báo cáo đánh giá repository  
- Báo cáo chuyển đổi  

Tính năng chat mới giúp bạn **giảm thời gian đọc báo cáo**, tăng tốc quá trình phân tích và hiện đại hóa ứng dụng .NET.

---

## Về các tác giả

### **David Pallmann**  
Giám đốc sản phẩm cấp cao trong nhóm AWS Transform, phụ trách trải nghiệm dành cho lập trình viên .NET.  
Trước đây từng là kỹ sư, kiến trúc sư, tư vấn và quản lý.  
Ông từng làm việc với WCF và tạo ra **Neuron ESB** — ESB đầu tiên dựa trên .NET.  
Theo dõi trên X: **@davidpallmann**

---

### **Vijay Mandadi**  
Lãnh đạo kỹ thuật trong nhóm AWS Migrations and Modernizations với hơn 16 năm kinh nghiệm trong:

- Hệ thống phân tán  
- Điện toán đám mây  
- Ảo hóa  
- Chuyển đổi workload  
- Ngành y tế  

Trọng tâm của ông tại AWS là ứng dụng **Generative AI** và **Agentic AI** vào hiện đại hóa ứng dụng.

---

### **Rakshith Ravi Kumar**  
Kỹ sư phần mềm cấp cao tại AWS với hơn 11 năm kinh nghiệm trong:

- Phát triển ứng dụng di động  
- Hệ thống CRM  
- Giải pháp NetBackup  
- Công nghệ di chuyển lên đám mây  

Hiện ông tập trung phát triển các giải pháp tự hành (Agentic solutions) phục vụ di chuyển và hiện đại hóa workload.

---

