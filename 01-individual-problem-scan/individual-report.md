# 01 — Individual Scan (Phase 1)

## Scan rộng 5 Problems (Bối cảnh học tập & làm đồ án)

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---|-----------|-----------------------|--------------------|---------------|
| 1 | Tốn thời gian / Lặp lại | Sau buổi họp với mentor, ghi chú (notes) thường lộn xộn, mất nhiều thời gian để lọc ra đâu là yêu cầu cốt lõi và danh sách việc cần làm. | Các thành viên trong nhóm dự án | Mất **30–40 phút** mỗi lần họp để tổng hợp lại; hay bị sót các yêu cầu nhỏ. |
| 2 | Pain từ người khác | Các thành viên trong nhóm làm project hiểu khác nhau về yêu cầu của mentor sau khi họp, dẫn đến làm sai hướng phần việc được giao. | Cả nhóm dự án | Phải hỏi lại mentor nhiều lần hoặc bị trừ điểm/nhắc nhở khi nộp sản phẩm sai lệch ý định ban đầu. |
| 3 | Lặp lại | Việc phân chia và định nghĩa deadline, độ ưu tiên cho các task mới nhận từ mentor cứ lặp đi lặp lại thủ công mỗi tuần. | Trưởng nhóm / Người quản lý task | Mất **20–30 phút** cập nhật lên Notion/Trello hàng tuần nhưng dễ bỏ sót dependency. |
| 4 | AI có thể tốt hơn | Tìm lại quyết định hoặc yêu cầu cũ của mentor từ 3–4 tuần trước trong đống tin nhắn Zalo/Discord hoặc file note cũ rất khó khăn. | Các thành viên trong nhóm dự án | Mất **10–15 phút** lục lọi lịch sử chat mỗi khi cần kiểm tra: *"Thầy từng dặn sửa đoạn này thế nào?"* |
| 5 | Tốn thời gian | Soạn nội dung báo cáo tiến độ tuần gửi mentor dựa trên những gì đã làm và yêu cầu cũ tốn công gọt giũa câu chữ để báo cáo mạch lạc. | Sinh viên làm nghiên cứu / đồ án | Mất khoảng **30 phút** mỗi tuần để viết email hoặc slide báo cáo tiến độ ngắn gọn. |

---

# 02 — Top 3 Problem Cards + Draft Workflow (Phase 2)

## Chọn Top 3 từ danh sách trên

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|------|---------|-------------|--------------------|
| **1** | Hệ thống hóa yêu cầu từ mentor sau buổi họp | Workflow cực kỳ rõ ràng, pain rất thật, tốn thời gian cố định hằng tuần, metric thời gian đo lường dễ dàng. | Độ chính xác của AI khi bóc tách ý chuyên môn kỹ thuật phức tạp. |
| **2** | Tìm kiếm quyết định/yêu cầu cũ từ lịch sử chat | Pain rộng nhưng phụ thuộc nhiều vào quyền truy cập dữ liệu (data access) của các app chat. | Giới hạn quyền riêng tư và khả năng kết nối API chat. |
| **3** | Đồng bộ hóa hiểu biết yêu cầu giữa các thành viên | Rất có giá trị nhưng khó kiểm soát khách quan hành vi của từng cá nhân trong nhóm. | Khó chuẩn hóa hành vi phản hồi của các thành viên khác. |

---

# Problem Card #1 — Hệ thống hóa yêu cầu từ mentor

## Problem (1 câu)

Sau mỗi buổi họp với mentor, các thành viên/ nhóm trưởng mất nhiều thời gian đọc lại ghi chú thô để lọc ra danh sách yêu cầu và phân loại công việc, dễ dẫn đến sót việc hoặc hiểu sai ý.

## Actor

Thành viên nhóm dự án/ nhóm trưởng tham gia các buổi họp định kỳ với mentor để nhận feedback, định hướng và giao việc.

## Thời điểm / Bối cảnh

Ngay sau khi kết thúc buổi họp chuyên môn hằng tuần.

## Current Workflow (5 bước)

1. Ghi chép nhanh (hoặc ghi âm) ý kiến của mentor trong lúc họp.
2. Đọc lại bản ghi chú thô (hoặc nghe lại audio dài).
3. Tự lọc thủ công các ý chính, gạch đầu dòng danh sách việc phải làm.
4. Gán deadline và phân công cho các thành viên trong nhóm qua Zalo/Discord.
5. Copy thủ công các task vào bảng quản lý (Trello/Notion).

## Bottleneck

**Bước 2 và Bước 3** — Đọc lại ghi chú thô và tự cô đọng thành danh sách **action items** rõ ràng, mất khoảng **30–40 phút** và dễ bị bỏ sót các ý phụ quan trọng.

## Impact

- Tốn khoảng **35 phút/người/tuần**.
- Rủi ro thực hiện sai yêu cầu của mentor.
- Có thể làm chậm tiến độ đồ án.

## Success Metric

- Giảm thời gian hệ thống hóa yêu cầu từ **35 phút** xuống **dưới 10 phút**.
- Tỷ lệ bỏ sót action items giảm từ **2–3 ý** xuống **0 ý**.

## Non-AI Alternative

Sử dụng **Meeting Minutes Template** với các ô trống để điền ngay trong lúc họp, tuy nhiên vẫn phải tự tổng hợp thủ công sau đó.

## AI Hypothesis

AI tiếp nhận **raw notes** hoặc **transcript** từ bản ghi âm, sau đó tự động:

- Tóm tắt các yêu cầu cốt lõi.
- Sinh danh sách **Action Items**.
- Gợi ý deadline.
- Chỉ ra các rủi ro hoặc điểm cần lưu ý.

Sinh viên chỉ cần xem lại (**review**) và phê duyệt (**approve**).

## Quick Gut: **Workflow**



# Draft Workflows (Before / After)
## Draft current workflow

```text
Current State (Hiện tại — ~35 phút)

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
## Draft future workflow

```text
Future State (Sau tối ưu — ~10 phút)

[1 Cung cấp raw notes / transcript: 2']
        │
        ▼
[2 AI parse cấu trúc & draft action items: 1']
        │
        ▼
[3 Sinh viên review, chỉnh sửa & approve: 6']   ← Human boundary
        │
        ▼
[4 Export thẳng lên Notion/Trello: 1']
```

## Fallback (Phương án dự phòng)

Nếu AI phân loại sai hoặc bỏ sót các thuật ngữ chuyên ngành kỹ thuật, sinh viên sẽ trực tiếp chỉnh sửa trên bản nháp (draft) của AI hoặc bổ sung thủ công phần còn thiếu.


## Problem Cards #2 và #3 — tóm tắt

| Card | Actor | Bottleneck | Metric | Quick gut | Vì sao chưa chọn làm #1 |
|---|---|---|---|---|---|
| Tìm kiếm yêu cầu/quyết định cũ từ chat | Thành viên nhóm dự án | Lục tìm keyword rải rác trong lịch sử chat Zalo/Discord | 15 phút → dưới 2 phút | Workflow / Agent | Data access phức tạp và scope rộng |
| Đồng bộ hiểu biết yêu cầu giữa các thành viên | Thành viên trong nhóm | Các thành viên hiểu lệch ý mentor, dẫn đến làm sai hướng | Giảm tỷ lệ lệch task từ 25% xuống dưới 5% | Workflow | Khó kiểm soát và chuẩn hóa hành vi phản hồi của từng cá nhân |