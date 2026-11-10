# Team


## Thông tin nhóm

- Tên nhóm: 05
- Candidate problem nhóm chọn (1 câu): Khi muốn tìm địa điểm đi chơi trong một khu vực nhất định, người dùng muốn nhanh chóng tìm và lựa chọn địa điểm phù hợp với sở thích, ngân sách, khoảng cách và mục đích đi chơi, để giảm thời gian tìm kiếm và so sánh thông tin trên nhiều ứng dụng.
- Quyết định cuối (Go / Not Yet / No-Go): Go

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Cao Minh | 2A202604099 | Trưởng nhóm| https://github.com/caominhnguyen05 |
| 2 | Phạm Hoàng Đức Minh | 2A202604114 | đóng góp việc| https://github.com/PH31M|
| 3 |Tào Quang Vinh |2A202604081 |đóng góp việc |https://github.com/qvinhh2312 |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Cao Minh | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Phạm Hoàng Đức Minh | | Assumption map, snapshot hoặc survey |
| CP4 — Research | Phạm Hoàng Đức Minh | | Bảng research có link |
| CP5 — Quy trình trước/sau |Tào Quang Vinh | | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 |Tào Quang Vinh | | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Tào Quang Vinh| | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định |Tào Quang Vinh | Nguyễn Cao Minh | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### Tào Quang Vinh-2A202604081
**Phần việc phụ trách:**

- đóng góp ý kiến
- làm cp5,cp6

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Mô tả các bước tìm địa điểm qua map, TikTok, review và kiểm tra quãng đường; xác định bước tìm thông tin là bottleneck ước tính 40–60 phút.
- Đề xuất luồng tương lai: dùng bộ lọc cho tiêu chí rõ ràng, AI hỗ trợ tóm tắt review có nguồn, người dùng kiểm tra thông tin và tự quyết định.
- Bổ sung boundary, phương án quay lại tìm thủ công nếu gợi ý sai/thiếu, và Problem Statement v0 cho candidate.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: mục 2.1 (pitch và câu hỏi phản biện), mục 4.1–4.3 (quy trình trước/sau), mục 5 (Problem Statement v0), mục 6,7
- Commit `e0f16f8` (`cp5`) cập nhật quy trình trước/sau và Problem Statement v0 trong báo cáo nhóm.

**Điều mình học được từ phần nhóm:**

-nhiều góc nhìn rộng hơn

### PhamHoangDucMinh-2A202604114

**Phần việc phụ trách:**

- làm CP4 
- đóng góp ý kiến 

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Mục 3.1: lập Assumption Map gồm 5 giả định (Value, Usability, Feasibility, Viability), chấm mức quan trọng và mức bằng chứng; chọn kiểm chứng trước 2 giả định Value có quan trọng 5 nhưng bằng chứng mới 1 (giả định #1 và #2).
- Mục 3.2: ghi 2 Interview Snapshot (1 sinh viên nam, 1 nhân viên văn phòng nữ) và bảng Tổng hợp. Tín hiệu xác nhận: mất 40–60 phút mỗi lần chọn địa điểm. Tín hiệu phản bác: vấn đề nằm ở thiếu thông tin thực tế/real-time chứ không phải thiếu bộ lọc.
- Mục 3.3: research Google Maps và TikTok/Facebook Reels, chỉ ra khoảng trống (thiếu dữ liệu thời gian thực) và bài học cho nhóm.
- Mục 2.1: pitch candidate #1 (thủ thư tra cứu trạng thái và vị trí sách) và nhận câu hỏi phản biện.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: mục 2.1 (hàng 1), mục 3.1, 3.2, 3.3.
- Commit `fd11c6a` ("CP04 - Group_Report", 09/11 20:58) cập nhật Assumption Map, Interview Snapshot và bảng research.

**Điều mình học được từ phần nhóm:**

-Tư duy "Problem-First": Tập trung giải quyết điểm nghẽn của người dùng thay vì vội vàng "chốt" giải pháp.
-Không phải vấn đề nào cũng cần AI Agent; đôi khi chỉ cần kết hợp Rule, Workflow và con người kiểm tra là đủ để giải quyết vấn đề hiệu quả.


### NguyenCaoMinh-2A202604099

**Phần việc phụ trách:**

- Phụ trách CP3 (Hội tụ nhóm): gom cluster, xây dựng Opportunity Solution Tree (OST) và chấm điểm shortlist.
- Hỗ trợ CP6 (Quyết định): đánh giá rủi ro và thống nhất quyết định Go/Not Yet/No-Go.
- Phụ trách mục 9 trong CP6: Hạn chế và hướng tiếp theo
- Đóng góp ý kiến và phản biện các candidate problem trong quá trình thảo luận nhóm.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Mục 2.1:** Pitch các candidate về tailor CV, tra cứu mark scheme Cambridge và tìm việc phù hợp với CV. Đặt câu hỏi phản biện cho các candidate khác nhằm xác định bottleneck thực sự và xem xét khả năng giải quyết bằng công cụ hiện có.
- **Mục 2.2:** Gom 9 candidate thành 4 cluster dựa trên các pattern chung: tìm kiếm và lựa chọn thông tin, tra cứu thông tin, xác minh và nhập liệu, cá nhân hóa nội dung.
- **Mục 2.3:** Xây dựng Opportunity Solution Tree cho problem tìm địa điểm đi chơi, xác định 3 opportunity chính: thông tin phân tán trên nhiều ứng dụng, khó đánh giá mức độ phù hợp và khó đưa ra quyết định.
- **Mục 2.4:** Lập bảng chấm điểm 3 candidate shortlist theo 7 tiêu chí, hỗ trợ nhóm lựa chọn problem tìm địa điểm đi chơi phù hợp.
- **Mục 8:** Hỗ trợ đánh giá 4 rủi ro Value, Usability, Feasibility và Viability; rà soát sự đồng bộ giữa Problem Statement và quyết định cuối cùng. Đề xuất giới hạn phạm vi Go ở pilot nhỏ thay vì xây dựng AI Agent phức tạp.

- **Mục 9:** Tổng hợp các hạn chế của giải pháp và đề xuất hướng tiếp theo.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md`: mục 2.1, 2.2 (Cluster), 2.3, 2.4, 8, 9.
- Commit: `75677cc`, `3f79c47`, `7615147`.

**Điều mình học được từ phần nhóm:**

- Tôi học được cách phân biệt giữa problem và solution, xác định bottleneck cụ thể trước khi nghĩ đến việc ứng dụng AI. Tôi cũng nhận ra rằng không phải vấn đề nào cũng cần AI Agent; đôi khi chỉ cần kết hợp Rule, Workflow và con người kiểm tra là đủ để giải quyết vấn đề hiệu quả.

