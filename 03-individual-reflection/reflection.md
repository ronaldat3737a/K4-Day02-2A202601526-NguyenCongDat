# 03 — Individual Reflection

## Đóng góp của Đạt trong nhóm

| Hoạt động | Đạt đã làm gì? | Kết quả |
|-----------|----------------|----------|
| **Scan cá nhân** | Đưa ra các vấn đề thực tế quanh việc họp nhóm, chia task. | Nhóm có nhiều ý tưởng gần với việc học và làm đồ án/dự án. |
| **Pitch** | Pitch bài toán **"Tóm tắt & chia việc sau khi họp với mentor"**. | Đạt điểm cao nhất (**35/35**) và được nhóm chốt chọn. |
| **Challenge** | Phản biện các bài toán về thói quen cá nhân (dậy sớm, ngủ đúng giờ) vì AI không thể thay đổi ý thức con người. | Nhóm gạt bớt các đề tài khó giải quyết bằng công nghệ. |
| **Workflow** | Vẽ flow **Hiện tại (~45 phút)** và **Tương lai (~10 phút)** cho việc xử lý ghi chú họp. | Thống nhất được workflow trước/sau và xác định rõ bước cần con người kiểm tra (**Human Review**). |
| **Research** | Tìm hiểu các ứng dụng như **Granola, Fireflies, Fathom, Fellow.ai**. | Rút ra bài học: Không cần xây dựng Agent phức tạp, chỉ cần mô hình **AI Draft → Human Review**. |
| **Rule / Workflow / Agent** | Phân tích vì sao chọn **Workflow** thay vì để **Agent** tự động thực hiện toàn bộ. | Nhóm đạt được sự đồng thuận cao và quyết định triển khai **Pilot**. |

---

# Bảng sử dụng AI trong Reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì? |
|--------|-------------------------|-------------------|-------------------------|-------------|
| **Scan** | Nhờ AI gợi ý thêm các góc nhìn lặp đi lặp lại khi làm dự án. | Chỉ ra được một số điểm tốn thời gian mà trước đây chưa để ý. | Gợi ý lan sang các thói quen cá nhân quá rộng. | Loại bỏ các ý không thể chuẩn hóa thành quy trình phần mềm. |
| **Workflow** | Nhờ AI vẽ sơ đồ dạng Text / ASCII từ mô tả các bước. | Tiết kiệm thời gian dựng workflow. | AI có xu hướng tự động hóa toàn bộ, bỏ qua bước con người review. | Thêm lại bước **"Nhóm Review & Approve"** trước khi push task. |
| **Research** | Nhờ AI tìm các công cụ đã giải quyết bài toán meeting và ghi chú. | Biết thêm các ứng dụng như **Granola, Fireflies, Fathom, Fellow.ai**. | AI đưa ra một số số liệu tiết kiệm thời gian nhưng không có nguồn kiểm chứng. | Khảo sát nhanh **3 nhóm bạn** để lấy số liệu thực tế (**45 phút → 10 phút**). |
| **Problem Statement** | Nhờ AI rà soát Problem Statement v0 còn thiếu gì. | Gợi ý bổ sung metric cụ thể (đo bằng phút và số task bị bỏ sót). | AI thường gợi ý xây dựng Agent tự tham gia họp rồi tự giao task. | Không chọn Agent, giữ giải pháp ở mức **Workflow** để con người quyết định cuối cùng. |

---

# Bài học của Đạt

1. **Bài toán hay không cần phải quá "hoành tráng".** Chỉ cần giải quyết đúng vấn đề gặp hằng tuần, có workflow rõ ràng và đo lường được bằng số liệu thì đã mang lại giá trị. Cố xây dựng một "AI Agent toàn năng" vừa khó triển khai vừa không thực tế.

2. **Phân biệt việc của công nghệ và việc của kỷ luật.** Các bài toán như tập thể dục, ngủ sớm hay dậy đúng giờ không thể giải quyết chỉ bằng AI. AI chỉ hỗ trợ nhắc nhở hoặc lập kế hoạch, còn việc thực hiện vẫn phụ thuộc vào con người.

3. **Không phải lúc nào cũng cần Agent.** Với bài toán xử lý thông tin từ mentor, lựa chọn **Workflow + Human-in-the-loop** là phù hợp nhất vì vừa tiết kiệm thời gian vừa hạn chế rủi ro AI hiểu sai nội dung.

4. **Cần có bước người duyệt.** Việc yêu cầu con người kiểm tra lại trước khi đưa task vào hệ thống không làm giảm vai trò của AI mà chính là lớp bảo vệ cuối cùng để tránh sót việc hoặc hiểu sai kiến thức chuyên môn.

---

# Nếu làm lại

```text
Nếu được làm lại, mình sẽ khảo sát thêm khoảng 5–10 nhóm dự án khác trong trường để có bộ dữ liệu đa dạng hơn về số lượng action items thường bị bỏ sót mỗi tuần, thay vì chỉ khảo sát 3 nhóm quen. Điều này sẽ giúp các metric và kết quả đánh giá có tính đại diện và thuyết phục hơn.
```