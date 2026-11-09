# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm:
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu):
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phạm Hoàng Đức Minh | Khi nhận được yêu cầu mượn sách từ sinh viên, tôi muốn biết ngay trạng thái và vị trí của sách, để phản hồi nhanh chóng mà không mất công tra cứu thủ công. | Thủ thư tại thư viện, sinh viên | Mỗi ngày có khoảng 20–30 lượt nhờ tìm hộ, mất 3–5 phút/yêu cầu tra cứu tay và đi kiểm tra kệ. | Hệ thống hay phần mềm quản lý thư viện hiện tại đã có thông tin về trạng thái và vị trí sách chưa? Nếu đã có, tại sao thủ thư vẫn phải tra cứu thủ công? Liệu cải thiện cách tìm kiếm và hiển thị thông tin có đủ giải quyết vấn đề mà không cần AI? |
| 2 | Tào Quang Vinh | Tìm địa điểm đi chơi phù hợp ở khu vực lân cận | Cá nhân | Mất khoảng 40–60 phút tìm và so sánh thông tin trên nhiều ứng dụng. | Các ứng dụng hiện tại như Google Maps đã hỗ trợ tìm kiếm và lọc địa điểm theo vị trí, đánh giá và loại hình. Vậy những tính năng này còn thiếu điều gì khiến bạn phải mất 40–60 phút để đưa ra quyết định? |
| 3 | Nguyễn Cao Minh | Khi tìm được một job opening phù hợp với tôi, tôi muốn tailor CV nhanh (dưới 25 phút), để có thể apply được nhiều vị trí hơn | Cá nhân |Mỗi tuần apply 10–15 role, mỗi role sửa CV mất khoảng 30–60 phút | Bạn đã thử dùng AI hoặc một template CV cố định để rút ngắn thời gian chỉnh sửa chưa? Nếu có, bước nào vẫn khiến bạn mất 30–60 phút cho mỗi vị trí ứng tuyển?|
| 4 | Tào Quang Vinh | Khi cần xác minh lưu trú, công an muốn có thông tin về nơi lưu trú có đúng khai báo hay không hay hiện tại nơi lưu trú đang như nào để kiểm soát khu vực hợp lí | Công an | Gọi xác minh không nghe máy, đến tận nơi nhưng không có nhà | Có thể dùng dữ liệu đăng ký lưu trú và quy trình hẹn xác minh trước khi cần đến tận nơi không? |
| 5 | Tào Quang Vinh | Khi cần tìm hiểu nội dung mới, tôi muốn tổng hợp thông tin cần để nắm rõ hiện tại cần tìm hiểu gì cho đúng, hợp lí | Cá nhân | Tiếp nhận code 1 ngày nhưng chưa nắm hết  | Các coding agent hiện tại có thể phân tích codebase tốt và giải thích luồng trong code, vậy cần thêm tính năng gì? |
| 6 | Nguyễn Cao Minh | Khi hướng dẫn học sinh giải past paper môn Math và Computer Science, tôi muốn tìm nhanh đáp án và marking criteria của từng câu hỏi, để giải thích và chấm bài ngay mà không phải mở mark scheme riêng rồi tìm đúng câu | Cá nhân, học sinh được tutor | Mỗi buổi dạy 1.5–2 giờ, thường phải chuyển giữa question paper và mark scheme nhiều lần, mỗi lần tìm đáp án khoảng 20-40s | Có thể dùng PDF có bookmark hoặc dùng website hỗ trợ đặt question paper và mark scheme cạnh nhau để giảm thời gian mà không cần AI không? |
| 7 | Nguyễn Cao Minh | Khi tìm các job opening, tôi muốn nhanh chóng xác định những vị trí phù hợp với CV, kỹ năng và kinh nghiệm của mình, để không mất nhiều giờ tìm và đọc job description trên các website mỗi tuần | Cá nhân apply việc | Mỗi tuần tìm khoảng 10–15 vị trí để ứng tuyển, phải đọc và so sánh JD từ nhiều nguồn (3-4h mỗi tuần) | Trong 3–4 giờ mỗi tuần, bạn mất nhiều thời gian nhất để tìm tin mới, lọc yêu cầu kinh nghiệm hay đánh giá mức độ phù hợp với CV? Các job board tổng hợp chưa đáp ứng được nhu cầu gì? |
| 8 | Phạm Hoàng Đức Minh | Khi nhập một lô sách mới về thư viện, tôi muốn trích xuất tự động thông tin (tên, tác giả, NXB, năm XB) từ mã ISBN hoặc ảnh bìa, để gõ dữ liệu vào hệ thống nhanh và không sai sót. | Thủ thư tại thư viện | Mất 5-7 phút gõ tay cho 1 cuốn sách. Một đợt nhập 100 cuốn sách tốn trọn 1 ngày làm việc, thỉnh thoảng gõ sai chính tả. | Phần mềm thư viện hiện tại có hỗ trợ tra cứu thông tin theo ISBN hoặc nhập dữ liệu hàng loạt chưa? Nếu có, bước nào vẫn buộc thủ thư nhập tay và có cần AI để giải quyết không? |
| 9 | Phạm Hoàng Đức Minh | Khi sinh viên nhờ tư vấn tài liệu tham khảo cho một chủ đề tiểu luận, tôi muốn quét nhanh toàn bộ mục lục và tóm tắt của các sách hiện có, để gợi ý đúng sách đang nằm trên kệ. | Thủ thư tư vấn, Sinh viên | 5-7 lượt sinh viên hỏi mỗi ngày. Mỗi lượt mất 10-15 phút lục tìm trí nhớ hoặc gõ keyword thử sai trên phần mềm cũ. | Trong 10–15 phút tư vấn mỗi lượt, bước nào thực sự tốn thời gian nhất: tìm sách liên quan đến chủ đề, đánh giá mức độ phù hợp của nội dung hay kiểm tra sách còn trên kệ? |


### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
| ------- | ------------- | ------------- |
| A       |               |               |
| B       |               |               |
| C       |               |               |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME:
├── Opportunity A:
├── Opportunity B:
└── Opportunity C:
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
| --------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | ---: |
|           |          |              |                    |                |             |                                        |                  |      |
|           |          |              |                    |                |             |                                        |                  |      |
|           |          |              |                    |                |             |                                        |                  |      |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 |          |                                                    |                  |                        |                   |
|   2 |          |                                                    |                  |                        |                   |
|   3 |          |                                                    |                  |                        |                   |
|   4 |          |                                                    |                  |                        |                   |
|   5 |          |                                                    |                  |                        |                   |
|   6 |          |                                                    |                  |                        |                   |

_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |          |
| Câu nói đáng nhớ nhất (nguyên văn)                |          |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |          |
| Hiện đang xử lý bằng cách nào (workaround)?       |          |
| Mất bao lâu, bao lần?                             |          |
| Insight / opportunity rút ra                      |          |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
| ----- | ----------------: | ----------------- | ----------------- |
|       |                   |                   |                   |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |
|                          |      |                                |           |                       |                  |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
|    1 |       |       |        |                      |         |
|    2 |       |       |        |                      |         |
|    3 |       |       |        |                      |         |
|    4 |       |       |        |                      |         |
|    5 |       |       |        |                      |         |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước              |       |               |         |
| Tổng thời gian       |       |               |         |
| Số bước thủ công     |       |               |         |
| Bottleneck chính     |       |               |         |
| Rủi ro mới phát sinh |       |               |         |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung |
| -------------------------------------------------------------------------- | -------- |
| **Actor**                                                                  |          |
| **Quy trình**                                                              |          |
| **Bottleneck**                                                             |          |
| **Impact**                                                                 |          |
| **Success Metric** (baseline → target, cách đo)                            |          |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) |          |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- ***

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
| ------------------------- | -------------------------- | ---------- | ------ | ----- |
| **No AI** (sửa quy trình) |                            |            |        |       |
| **Rule**                  |                            |            |        |       |
| **Workflow**              |                            |            |        |       |
| **Agent**                 |                            |            |        |       |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung |
| ----------------------------------------------------------------- | -------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          |          |
| **Judgment** — con người cân nhắc, quyết định gì?                 |          |
| **Action** — hành động cuối cùng là gì, ai làm?                   |          |
| **Outcome** — đo kết quả bằng gì?                                 |          |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? |          |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   |          |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                        |
| ----------------------------------------------- | ------------------------------- |
| **Actor**                                       |                                 |
| **Quy trình**                                   |                                 |
| **Bottleneck**                                  |                                 |
| **Impact**                                      |                                 |
| **Success Metric** (baseline → target, cách đo) |                                 |
| **Boundary**                                    |                                 |
| **AI intervention point**                       |                                 |
| **Mức chọn**                                    | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra**                     |                                 |

**Thay đổi so với v0 và lý do:**

| Trường | v0  | v1  | Vì sao đổi |
| ------ | --- | --- | ---------- |
|        |     |     |            |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí | Đạt khi | Không đạt khi |
| --: | -------- | ------- | ------------- |
|   1 |          |         |               |
|   2 |          |         |               |
|   3 |          |         |               |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | ------------------ |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       |                                                       |                    |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? |                                                       |                    |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     |                                                       |                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     |                                                       |                    |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
