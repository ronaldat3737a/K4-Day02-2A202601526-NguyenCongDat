# Group Report — Day 02

## Thành viên nhóm

| STT | Họ và tên       | Mã học viên | Vai trò trong nhóm |
| --- | --------------- | ----------- | ------------------ |
| 1   | Nguyễn Công Đạt | 2A202601526 | Leader             |
| 2   | Bùi Đức Hiếu    | 2A202601820 | Member             |
| 3   | Phạm Bá Huy     | 2A202601784 | Member             |
| 4   | Diệp Đức Lai    | 2A202601784 | Member             |
| 5   | Trần Bá Lợi     | 2A202601316 | Member             |

## 1.1. Group Convergence (Hội tụ từ 15 Candidates về 1)

Nhóm đã thu thập tất cả **15 bài toán cá nhân** và tiến hành gom nhóm (**cluster**) theo lăng kính nguyên nhân và bối cảnh.

### Bảng gom nhóm 15 đề tài (Cluster Table)

| Cluster                             | Các đề tài bao gồm (#1–#15)                                                                                                                                                                                                      | Pattern chung                                                               | Ghi chú & Đánh giá nhanh                                                                                                          |
| ----------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **A. Quản lý họp & Làm việc nhóm**  | 1. Biên bản + chia việc sau họp mentor/nhóm<br>2. FAQ / Trả lời câu hỏi lặp lại cho thành viên mới                                                                                                                               | Gom thông tin trao đổi rải rác thành các hành động cụ thể, tránh hiểu sai ý | Workflow rất rõ, dễ xác định baseline thời gian, rủi ro AI có thể kiểm soát bằng con người.                                       |
| **B. Hỗ trợ học tập & Báo cáo**     | 3. Tạo Flashcard / câu hỏi từ slide<br>4. Tìm lại thông tin cũ trong Discord<br>5. Kiểm tra bài nộp thiếu mục so với Rubric<br>6. Rà soát lỗi báo cáo trước khi nộp<br>7. Debug lỗi môi trường lập trình                         | Đọc hiểu, tổng hợp, tra cứu và đối chiếu tài liệu học thuật / kỹ thuật      | Nhiều bài có impact tốt nhưng metric chất lượng (như chất lượng câu hỏi hay độ chính xác debug) khó đo lường trong thời gian lab. |
| **C. Lối sống & Hiệu suất cá nhân** | 8. Đi lại tốn thời gian / trễ giờ (Huy #1)<br>9. Ăn uống thất thường do bận rộn (Huy #2)<br>10. Lên kế hoạch tập thể dục khi lịch dày (Hiếu #1)<br>11. Mất tập trung khi học do MXH (Hiếu #2)<br>12. Trằn trọc khó ngủ (Hiếu #3) | Hành vi cá nhân, quản lý thời gian sinh hoạt và kỷ luật bản thân            | Phụ thuộc nhiều vào yếu tố tâm lý và kỷ luật cá nhân, khó giải quyết triệt để bằng AI hoặc giải pháp công nghệ đơn thuần.         |
| **D. Định hướng & Hành chính**      | 13. Chuẩn bị hồ sơ thực tập / CV<br>14. Lập lịch trình sinh hoạt cá nhân<br>15. Tổng hợp báo cáo tiến độ tuần                                                                                                                    | Chuẩn hóa quy trình thủ tục và theo dõi cá nhân                             | Workflow ít lặp lại hằng tuần (CV) hoặc phạm vi quá rộng.                                                                         |

---

# 1. Đánh giá, sàng lọc và thống nhất đề tài nhóm

## 1.2. Shortlist & Scoring (Chấm điểm & Lựa chọn)

Nhóm lọc ra **Top 4 candidate** đại diện cho các nhóm bài toán để chấm điểm đồng thuận (thang điểm **1–5**).

### Bảng chấm điểm Shortlist

| Candidate Problem                                  | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm được trong lab | So sánh R/W/A | Nhóm hiểu domain |  Tổng  |
| -------------------------------------------------- | :------: | :---------: | :--------------: | :------------: | :----------------: | :-----------: | :--------------: | :----: |
| **1. Biên bản + chia việc sau họp (Mentor/Group)** |    5     |      5      |        5         |       5        |         5          |       5       |        5         | **35** |
| **2. Flashcard / câu hỏi từ slide**                |    5     |      5      |        4         |       4        |         5          |       4       |        4         | **31** |
| **3. Tìm lại thông tin cũ trên Discord**           |    4     |      4      |        5         |       4        |         3          |       4       |        4         | **28** |
| **4. Lộ trình di chuyển tránh tắc đường (Huy #1)** |    4     |      4      |        4         |       3        |         3          |       3       |        4         | **25** |

---

## 1.3. Quyết định của nhóm

### Candidate nhóm chọn

**Biên bản + chia việc / Hệ thống hóa yêu cầu từ mentor sau họp**

### Lý do chọn

- **Workflow cực kỳ mạch lạc:** Quy trình hiện tại gồm 5 bước rõ ràng:

  ```text
  Ghi chú thô
        ↓
  Đọc / Nghe lại
        ↓
  Lọc Action Items
        ↓
  Phân công
        ↓
  Cập nhật Trello / Notion
  ```

- **Bottleneck cụ thể:** Nghẽn nhất ở bước đọc lại ghi chú thô và tự cô đọng thành **Action Items**, mất khoảng **30–40 phút**.

- **Metric đo lường khách quan:**
  - Thời gian xử lý giảm từ **35 phút** xuống **dưới 10 phút**.
  - Tỷ lệ bỏ sót task giảm từ **2–3 ý** xuống **0 ý**.

- **Tranh luận Rule / Workflow / Agent rất rõ ràng:**
  - **Rule:** Meeting Minutes Template.
  - **Workflow:** AI parse văn bản → Human Review.
  - **Agent:** Bot tự tham gia họp và tự tạo task.

# 2. Quick Validation (Kiểm chứng nhanh)

Nhóm đã tiến hành khảo sát nhanh và phỏng vấn các nhóm làm dự án khác.

| Nguồn               | Số lượng | Tín hiệu xác nhận                                                             | Tín hiệu phản bác                                               | Nhóm sửa problem thế nào                                                                                              |
| ------------------- | -------- | ----------------------------------------------------------------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| Quick interview     | 3 nhóm   | 3/3 nhóm đều mất nhiều thời gian đọc lại note sau họp với mentor để chia việc | 1 nhóm dùng ghi âm tự động của phần mềm họp nhưng lười nghe lại | Thu hẹp problem: Không phải **ghi âm cuộc họp**, mà là **biến ghi chú thô/transcript thành action items có cấu trúc** |
| Mini poll trong lớp | 8 người  | 6/8 người từng phân công thiếu hoặc sót việc do ghi chép sót ý mentor         | Một số ít tự nhớ được các việc chính mà không cần ghi chú       | Bổ sung phương án non-AI: **Meeting Minutes Template**                                                                |

### Insight sau validation

Pain lớn nhất **không nằm ở việc ghi chép lời mentor**, mà nằm ở khâu:

- Lọc thông tin.
- Cấu trúc hóa nội dung.
- Phân quyền task.

Mục tiêu là giúp nhóm **không bỏ sót việc** hoặc **hiểu sai yêu cầu kỹ thuật**.

---

# 3. Research Giải pháp

Nhóm tìm hiểu các công cụ và mô hình đang có trên thị trường.

| Nguồn / Tool         | Link                  | Họ giải quyết phần nào?         | Điểm mạnh                        | Khoảng trống / Rủi ro                            | Bài học cho nhóm                       |
| -------------------- | --------------------- | ------------------------------- | -------------------------------- | ------------------------------------------------ | -------------------------------------- |
| Otter.ai / Fireflies | https://otter.ai      | Transcribe & summarize cuộc họp | Ghi âm và tóm tắt tự động        | Không hiểu sâu ngữ cảnh kỹ thuật riêng của dự án | AI tạo bản nháp, con người rà soát lại |
| Notion AI            | https://www.notion.so | Tóm tắt văn bản                 | Tích hợp trực tiếp với workspace | Phải copy/paste nội dung vào Notion              | Phù hợp làm bước export task cuối cùng |
| ChatGPT / Claude     | https://claude.ai     | Chuyển prompt thành task list   | Linh hoạt                        | Chưa tự động hóa toàn bộ workflow                | Dùng làm AI xử lý ở bước giữa          |

### Research Takeaway

Nhóm **không xây dựng Agent tự động hoàn toàn**, vì:

- Rủi ro AI hiểu sai ý mentor rất cao.
- Sai sót sẽ ảnh hưởng trực tiếp đến dự án.

Giải pháp hợp lý là:

> **Workflow:** AI hỗ trợ phân tích và cấu trúc dữ liệu → Con người review → Đưa vào hệ thống quản lý task.

---

# 4. Workflow Before / After

## Current State (Hiện tại — ~35 phút)

```text
[1 Ghi chú thô trong họp: 12']
        │
        ▼
[2 Đọc lại ghi chú / Nghe audio: 8']
        │
        ▼
[3 Lọc action items thủ công: 7']   ← Bottleneck
        │
        ▼
[4 Gửi nhóm qua Zalo/Discord: 2']
        │
        ▼
[5 Cập nhật Notion/Trello: 6']
```

## Future State (Sau tối ưu — ~10 phút)

```text
[1 Cung cấp raw notes / transcript: 2']
        │
        ▼
[2 AI parse cấu trúc & draft action items: 1']
        │
        ▼
[3 Nhóm review, chỉnh sửa & approve: 6']   ← Human boundary
        │
        ▼
[4 Export thẳng lên Notion/Trello: 1']
```

### Bottleneck mới

Khâu **Review & Approve** (~6 phút).

Đây là bottleneck chấp nhận được vì đóng vai trò là **điểm kiểm soát chất lượng (Human-in-the-loop)**.

---

## Before / After Impact

| Metric                 | Trước                     | Sau kỳ vọng               | Ghi chú                |
| ---------------------- | ------------------------- | ------------------------- | ---------------------- |
| Tổng thời gian xử lý   | 35 phút                   | Dưới 10 phút              | Tiết kiệm đáng kể      |
| Số bước thao tác       | 5 bước                    | 4 bước                    | Giảm thao tác thủ công |
| Tỷ lệ sót action items | 2–3 ý/tuần                | 0 ý                       | Đảm bảo tính toàn vẹn  |
| Bottleneck             | Lọc action items thủ công | Review & approve AI draft | Human boundary rõ ràng |

---

# 5. Problem Statement v0 & v1

## Problem Statement v0

**Actor**

Thành viên nhóm dự án chịu trách nhiệm hệ thống hóa yêu cầu sau buổi họp với mentor.

**Workflow**

```text
Ghi chú họp
    ↓
Đọc lại note thô
    ↓
Lọc action items thủ công
    ↓
Gửi Zalo/Discord
    ↓
Cập nhật Trello/Notion
```

**Bottleneck**

Khâu đọc lại ghi chú và tự lọc action items mất **10–15 phút**, dễ bỏ sót các ý phụ.

**Impact**

- Tốn thời gian.
- Dễ làm sai hướng dự án.

**Success Metric**

- Giảm thời gian từ **35 phút** xuống **<10 phút**.
- Giảm số ý sót xuống **0**.

**Boundary**

- AI không tự phân công công việc.
- AI không tự gửi thông báo cho mentor.
- AI chỉ xử lý raw notes được cung cấp.

---

# 6. Rule / Workflow / Agent & Final Decision

## So sánh phương án AI

| Mức      | Phương án                                          | Khi nào đủ                        | Rủi ro                              | Chọn? |
| -------- | -------------------------------------------------- | --------------------------------- | ----------------------------------- | :---: |
| Rule     | Meeting Minutes Template                           | Họp ngắn, đơn giản                | Vẫn phải tổng hợp thủ công          |   X   |
| Workflow | Raw notes → AI parse → Review → Push Notion/Trello | Phù hợp với quy trình hiện tại    | AI có thể bỏ sót thuật ngữ kỹ thuật |   V   |
| Agent    | AI nghe audio → phân loại → tự tạo task            | Khi tích hợp sâu với hệ thống họp | Quá phức tạp, rủi ro cao            |   X   |

### Mức chọn

**Workflow**

### Vì sao

- Quy trình rõ ràng.
- Có Human-in-the-loop.
- Chi phí thấp.
- Dễ triển khai trong phạm vi lab.

---

# Problem Statement v1 (Bản hoàn chỉnh)

### Actor

Thành viên nhóm dự án họp định kỳ với mentor.

### Workflow

```text
Raw notes / Transcript
          ↓
AI parse thành Action Items
          ↓
Nhóm Review & Approve
          ↓
Export lên Notion/Trello
```

### Bottleneck

Xử lý và phân loại thông tin thô sau buổi họp.

### Impact

- Tiết kiệm khoảng **35 phút/tuần**.
- Tăng độ chính xác khi thực hiện công việc.

### Success Metric

- Tổng hợp trong **dưới 10 phút**.
- Không còn tình trạng sót việc.

### Boundary

AI chỉ tạo bản nháp.

Con người chịu trách nhiệm kiểm tra và phê duyệt cuối cùng.

### AI Intervention Point

Ngay sau khi kết thúc buổi họp, đưa **raw notes** vào prompt chuẩn hóa.

### Mức chọn

**Workflow**

### Rủi ro & Người kiểm tra

- **Rủi ro:** AI hiểu sai thuật ngữ kỹ thuật.
- **Người kiểm tra:** Nhóm trưởng hoặc thành viên phụ trách.

---

# Final Decision

## Decision

**Go** với phạm vi thử nghiệm nhỏ (**Pilot**).

### Pilot nhỏ nhất

1. Lấy raw notes từ **2 buổi họp** gần nhất.
2. Đưa qua prompt chuẩn hóa.
3. AI sinh danh sách Action Items.
4. Đo:
   - Thời gian chỉnh sửa.
   - Số lượng lỗi phải sửa.

### Exit / Rollback

Nếu trong **2 tuần liên tiếp**, nhóm vẫn phải sửa **hơn 60% output** của AI thì quay về:

- Meeting Minutes Template
- Checklist thủ công

### Decision Rationale

Bài toán có:

- Actor rõ ràng.
- Workflow mạch lạc.
- Đo lường được hiệu quả.
- Có Human-in-the-loop để đảm bảo chất lượng đầu ra.
