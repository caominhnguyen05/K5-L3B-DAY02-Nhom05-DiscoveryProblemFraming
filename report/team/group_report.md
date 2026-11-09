# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: 05
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi muốn tìm địa điểm đi chơi trong một khu vực nhất định, người dùng muốn nhanh chóng tìm và lựa chọn địa điểm phù hợp với sở thích, ngân sách, khoảng cách và mục đích đi chơi, để giảm thời gian tìm kiếm và so sánh thông tin trên nhiều ứng dụng.
- Quyết định cuối: Go

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
|---|---|---|
| A — Tìm kiếm và lựa chọn thông tin phù hợp | #2 Tìm địa điểm đi chơi, #7 Tìm job phù hợp, #9 Tư vấn sách tham khảo | Phải tìm kiếm, lọc và so sánh nhiều lựa chọn để xác định phương án phù hợp với nhu cầu cụ thể |
| B — Tra cứu và hiểu thông tin | #1 Tra cứu trạng thái sách, #5 Tìm hiểu codebase, #6 Tra cứu mark scheme | Mất thời gian tìm đúng thông tin cần thiết trong hệ thống hoặc tài liệu có sẵn |
| C — Xác minh và nhập liệu | #4 Xác minh lưu trú, #8 Nhập thông tin sách mới | Quy trình thủ công, tốn thời gian thu thập hoặc xác minh thông tin, có thể xảy ra sai sót |
| D — Cá nhân hóa nội dung | #3 Tailor CV theo job description | Phải đọc yêu cầu cụ thể và chỉnh sửa nội dung hiện có cho phù hợp với từng trường hợp |

### 2.3. Opportunity Solution Tree rút gọn

**Outcome:** Giảm thời gian tìm kiếm và lựa chọn địa điểm đi chơi phù hợp ở khu vực lân cận từ 40–60 phút xuống dưới 15 phút/lần, đồng thời vẫn đáp ứng các tiêu chí quan trọng của người dùng.

```text
OUTCOME: Giảm thời gian tìm và chọn địa điểm đi chơi trong một khu vực từ 40–60 phút xuống dưới 15 phút/lần.

- Opportunity A: Thông tin phân tán
Thông tin địa điểm nằm rải rác trên nhiều nền tảng (Google Maps, TikTok, Instagram, v.v.), khiến người dùng mất thời gian tìm kiếm và đối chiếu.
- Opportunity B: Khó đánh giá mức độ phù hợp
Người dùng khó xác định địa điểm nào phù hợp nhất với sở thích, ngân sách, khoảng cách và mục đích đi chơi.
- Opportunity C: Khó đưa ra quyết định
Có quá nhiều lựa chọn và đánh giá khác nhau, khiến người dùng mất thời gian so sánh và lựa chọn địa điểm cuối cùng.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- Xây dựng chatbot AI gợi ý địa điểm đi chơi dựa trên sở thích. → Đây là giải pháp, không phải nhu cầu của người dùng.
- Tạo ứng dụng tổng hợp địa điểm từ Google Maps và các nền tảng review. → Đây là tính năng, trong khi vấn đề thực sự là thông tin phân tán và khó so sánh.
- Dùng AI Agent tự động lên lịch trình đi chơi. → Đây là hướng giải pháp quá rộng, chưa có bằng chứng người dùng cần tự động hóa toàn bộ lịch trình.


### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #1 — Tra cứu trạng thái và vị trí sách | 5 | 5 | 4 | 5 | 4 | 3 | 3 | **29** |
| #2 — Tìm địa điểm đi chơi phù hợp | 5 | 5 | 3 | 5 | 5 | 5 | 5 | **33** |
| #3 — Tailor CV theo job description | 5 | 5 | 4 | 5 | 5 | 4 | 4 | **32** |

**Candidate được chọn:** Tìm địa điểm đi chơi phù hợp ở khu vực lân cận.

**Vì sao chọn:**
- Problem gần gũi, dễ tiếp cận người dùng để phỏng vấn và kiểm chứng nhu cầu.
- Có bottleneck rõ ràng: mất khoảng 40–60 phút/lần để tìm kiếm, đọc review và so sánh địa điểm từ nhiều nền tảng như Google Maps, TikTok, Instagram.
- Có thể đo lường hiệu quả bằng thời gian tìm kiếm (mục tiêu dưới 15 phút/lần) và mức độ hài lòng với địa điểm được chọn.
- Nhóm quen thuộc với domain và có thể so sánh nhiều phương án từ cải thiện quy trình tìm kiếm, sử dụng bộ lọc đến workflow hoặc AI hỗ trợ.

**Vì sao loại các candidate còn lại:**
- **#1 — Tra cứu trạng thái và vị trí sách:** Có quy trình rõ và tần suất cao, nhưng cần tiếp cận dữ liệu, phần mềm quản lý thư viện và thủ thư thực tế để kiểm chứng. Ngoài ra, nếu hệ thống đã có thông tin đầy đủ thì cải thiện chức năng tìm kiếm có thể giải quyết phần lớn vấn đề mà không cần AI.
- **#3 — Tailor CV:** Có pain thực tế (30–60 phút/role, 10–15 role/tuần), nhưng các công cụ AI hiện tại đã hỗ trợ chỉnh sửa CV theo JD. Nhóm cần xác định rõ bước nào vẫn chưa được giải quyết và khó khăn trong việc đánh giá chất lượng CV sau khi chỉnh sửa.


---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | -------- | -------------------------------------------------- | ---------------: | ---------------------: | ----------------- |
|   1 |     Ngoài Vinh, nhiều người cũng mất từ 30 phút mỗi lần chọn nơi đi chơi, và gặp việc này ít nhất 1 lần/tuần     |          Value                                          |         5         |             1           |              Có     |
|   2 |   Công cụ có sẵn (bản đồ, TikTok, chatbot AI) chưa giải đủ bài này       |              Value                                      |      5            |            1            |            Có       |
|   3 |      Người dùng tin và đi theo danh sách gợi ý ngắn của AI, thay vì tự đọc review    |          Usability                                          |         4         |               1         |          Sau         |
|   4 |      Có đủ dữ liệu đúng và còn mới (giờ mở cửa, giá, review, khoảng cách) để gợi ý không dẫn người dùng đi uổng công    |            Feasibility                                        |     4             |       2                 |              Sau     |
|   5 |      Chi phí và quyền dùng dữ liệu (vị trí người dùng, nội dung bản đồ/TikTok) không chặn bản pilot    |              Viability                                      |         3         |               1         |          Sau         |


_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

Buổi 1:
| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |   Nam sinh viên năm 3, người thường xuyên phải "lên kèo" và tìm địa điểm cho nhóm bạn thân.       |
| Câu nói đáng nhớ nhất (nguyên văn)                |    "Trên Google Maps có cả ngàn quán, nhưng map không cho mình biết quán nào hiện tại đang còn chỗ trống, hay không gian có đủ yên tĩnh để nhóm 5 người ngồi nói chuyện không."      |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |    Tối thứ 7 tuần trước hẹn nhóm đi cafe. Quán đầu tiên đến nơi thì hết bàn, quán thứ hai thì nhạc quá to không nói chuyện được. Phải chạy xe lòng vòng tìm quán rảnh mất gần 45 phút mới có chỗ ngồi.      |
| Hiện đang xử lý bằng cách nào (workaround)?       |     Lên Google Maps tìm quán có rating cao, sau đó copy tên quán lên TikTok hoặc Instagram để xem video quay không gian thực tế, rồi lên Facebook nhắn tin cho fanpage quán hỏi xem giờ này còn bàn cho 5 người không.     |
| Mất bao lâu, bao lần?                             |     Tốn khoảng 40–60 phút cho mỗi lần đi chơi. Tuần nào cũng gặp (1-2 lần/tuần).     |
| Insight / opportunity rút ra                      |    Insight: Người dùng thiếu thông tin thực tế và cập nhật về tình trạng của địa điểm mà Maps không cung cấp được. Opportunity: Tích hợp tính năng cập nhật tình trạng quán theo thời gian thực hoặc video review không gian thực tế ngắn.      |

Buổi 2:
| Trường                                            | Nội dung |
| ------------------------------------------------- | -------- |
| Người được hỏi (vai trò, không ghi tên thật)      |    Nữ nhân viên văn phòng 25 tuổi, thích tìm các không gian có đặc thù để thư giãn cuối tuần.      |
| Câu nói đáng nhớ nhất (nguyên văn)                |  Đánh giá 4.5 sao trên mạng nhiều khi là do quán tặng nước để khách review. Nhìn ảnh chụp góc nào cũng đẹp, đến nơi thì ngột ngạt không hợp gu mình chút nào.        |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |     Muốn tìm một quán cafe yên tĩnh để đọc sách tối thứ 6. Lọc trên app thấy một quán ghi là "yên tĩnh, chill", nhưng đến nơi thì hôm đó quán lại tổ chức sự kiện nhạc hát hò rất ồn, đành phải bỏ về.     |
| Hiện đang xử lý bằng cách nào (workaround)?       |     Phải đọc thật kĩ từng bình luận 1 sao, 2 sao trên Google Maps. Sau đó vào các hội nhóm review ẩm thực/cafe trên Facebook đọc comment dạo để xem quán có bị "seeding" hay không rồi mới dám chốt.     |
| Mất bao lâu, bao lần?                             |     Tốn cả tiếng đồng hồ để sàng lọc thông tin giả/thật trước mỗi buổi hẹn quan trọng.|
| Insight / opportunity rút ra                      |    Insight: Có sự khủng hoảng niềm tin vào hệ thống rating/review tĩnh. Hình ảnh chỉnh sửa và filter "loại hình" trên app không đủ để diễn tả chính xác hoặc sự kiện đang diễn ra trong ngày của quán. Opportunity: Hệ thống đánh giá dựa trên các tag cảm xúc được update linh hoạt theo khung giờ/ngày, kết hợp xác thực review chống seeding.      |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
| ----- | ----------------: | ----------------- | ----------------- |
|   Phỏng vấn sâu (1-1)    |          02 người (1 nam SV, 1 nữ NVVP)         |        Người dùng thực sự mất 40–60 phút để ra quyết định chọn địa điểm.  Các tính năng filter, rating của Google Maps hiện tại không đủ để họ chốt địa điểm.            |           Vấn đề không nằm ở việc "thiếu bộ lọc", mà nằm ở việc "thiếu thông tin thực tế/real-time". Người dùng không lười tìm kiếm, họ sẵn sàng tốn công đổi qua lại 3-4 app (Maps, TikTok, Facebook) chỉ để xác thực xem quán có hợp vibe không và có chỗ không.        |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
| ------------------------ | ---- | ------------------------------ | --------- | --------------------- | ---------------- |
|          Google Maps                |   google.com/maps   |         Khám phá (Discovery) - Tìm kiếm các địa điểm xung quanh, xem khoảng cách và thông tin cơ bản.                       |     Cơ sở dữ liệu địa điểm khổng lồ, chỉ đường chính xác, phân loại cơ bản (nhà hàng, cafe) rõ ràng.      |      Thiếu thông tin cập nhật theo thời gian thực (hiện tại có đông không, còn bàn không). Review và ảnh tĩnh dễ bị "làm đẹp" (seeding).|          Tận dụng tốt bản đồ vị trí là cần thiết, nhưng phải có thêm "lớp" dữ liệu thời gian thực (real-time data) để tạo sự khác biệt.        |
|       TikTok / Facebook Reels                   |  tiktok.com / facebook.com    |          Chốt hạ (Decision) - Nhắn tin trực tiếp cho quán để hỏi xem giờ này còn đủ bàn cho nhóm người không.                      |     Lấy được thông tin chính xác nhất về tình trạng chỗ ngồi ngay lúc đó.      |          Mất thời gian chờ đợi phản hồi từ admin. Quá trình thủ công, phải lặp lại với từng quán nếu quán trước đó báo hết bàn.             |      Cần một cơ chế hiển thị trạng thái "Độ đông đúc / Tình trạng bàn" (Capacity status) tự động hoặc do người dùng đang ở đó báo cáo (crowd-sourced) để giảm ma sát.            |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):


```HIỆN TẠI — 6 bước, 90 phút, 6/6 bước thủ công
[1 mở map 2'] → [2 mở tiktok,ig: 5'] → [3 tìm thông tin quanh khu vực: 40']← BOTTLENECK
→ [4 xem review: 20'] → [5 xem quãng đường: 10'] → [6 đến địa điểm: 5-20']


TƯƠNG LAI — 4 bước, mục tiêu dự kiến khoảng 25 phút, 2/4 bước chủ yếu do người dùng thực hiện

[1 Nhập khu vực, loại địa điểm và tiêu chí phù hợp đối tượng vào công cụ tìm kiếm: 5']
→ [2 Lọc và tạo danh sách địa điểm phù hợp: 5'] ← RULE / WORKFLOW
→ [3 Check review và lựa chọn: 10'] ← CON NGƯỜI
→ [4 So sánh quãng đường và chọn địa điểm: 3'] ← CON NGƯỜI

BOUNDARY: Công cụ chỉ gợi ý dựa trên tiêu chí đã nhập và thông tin có nguồn để kiểm tra. Không coi điểm đánh giá hoặc review là bảo đảm địa điểm phù hợp, còn mở cửa hay còn chính xác; người dùng tự kiểm tra thông tin quan trọng trước khi chọn.

PHƯƠNG ÁN QUAY VỀ: Nếu danh sách gợi ý không phù hợp hoặc thông tin thiếu/sai, quay lại tìm trên map, đọc review và tự so sánh như quy trình hiện tại.

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
| ---: | ----- | ----- | ------ | -------------------- | ------- |
| 1 | cá nhân | Muốn đi chơi nhưng chưa chọn được nơi | Mở map và xác định khu vực cần tìm | Khoảng 2 phút/lần tìm | Bắt đầu khi bí địa điểm |
| 2 | cá nhân | Khu vực muốn tìm | Mở TikTok và tìm địa điểm quanh khu vực | Khoảng 2 phút mở ứng dụng; 40–60 phút tìm thông tin | Bước tốn thời gian nhất |
| 3 | cá nhân | Các địa điểm tìm được | Xem và so sánh review | Khoảng 20 phút | Cần xác minh có trùng với thời gian tìm ở bước 2 không |
| 4 | cá nhân | Địa điểm đang cân nhắc | Kiểm tra quãng đường trên map | Khoảng 10 phút | Dùng để cân nhắc mức độ thuận tiện |
| 5 | cá nhân | Địa điểm đã chọn | Đến địa điểm | Khoảng 5–20 phút di chuyển | Không tính vào thời gian tìm và chọn |

**Bottleneck chính:**
 2 | cá nhân | Khu vực muốn tìm | Mở TikTok và tìm địa điểm quanh khu vực | Khoảng 2 phút mở ứng dụng; 40–60 phút tìm thông tin | Bước tốn thời gian nhất |

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```
[1. Người dùng nhập khu vực, loại địa điểm, ngân sách và tiêu chí]
→ CON NGƯỜI cung cấp nhu cầu

[2. Lọc địa điểm theo khoảng cách, loại hình, ngân sách hoặc tiêu chí rõ ràng]
→ RULE áp dụng bộ lọc; hiển thị danh sách địa điểm

[3. Tóm tắt review của các địa điểm trong danh sách, nêu điểm khen/chê và nguồn]
→ AI trao đổi, hỗ trợ tổng hợp thông tin để người dùng dễ so sánh

[4. Người dùng mở nguồn, kiểm tra review, giá và thông tin cần thiết]
→ CON NGƯỜI xác minh thông tin và đánh giá mức độ phù hợp

[5. Người dùng so sánh quãng đường và chọn địa điểm]
→ RULE hiển thị khoảng cách/thời gian di chuyển; CON NGƯỜI quyết định

BOUNDARY:
AI chỉ tóm tắt thông tin review có nguồn để đối chiếu. AI không tự tạo review,
không đảm bảo thông tin còn mới, không quyết định thay người dùng và không tự
đặt chỗ hoặc thực hiện hành động bên ngoài ứng dụng.

PHƯƠNG ÁN QUAY VỀ:
Nếu AI tóm tắt thiếu nguồn, sai hoặc không phù hợp, người dùng bỏ phần tóm tắt,
mở review gốc và tự tìm/lọc địa điểm trên map như quy trình hiện tại.

```

### 4.3. Before / after

| Chỉ số               | Trước | Sau (kỳ vọng) | Ghi chú |
| -------------------- | ----: | ------------: | ------- |
| Số bước              |     6  |       4        |         |
| Tổng thời gian       |   90p    |      25p         |   target chính : dưới 30p      |
| Số bước thủ công     |    6/6   |        2/4       |    cá nhân vẫn chốt     |
| Bottleneck chính     |    tìm kiếm   |   cá nhân chốt        |    ai tổng hợp     |
| Rủi ro mới phát sinh |       |       ai đưa thiếu,         |    cá nhân check bài share gốc     |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Cá nhân muốn tìm địa điểm đi chơi, học tập khu vực cần tìm |
| **Quy trình** | Xác định khu vực và nhu cầu → tìm địa điểm trên map/TikTok → đọc, so sánh review → kiểm tra quãng đường → chọn địa điểm |
| **Bottleneck** | Mất khoảng 40–60 phút tìm thông tin quanh khu vực và khó chọn giữa các địa điểm; cần xác minh xem thời gian này có bao gồm việc đọc review không |
| **Impact** | Thời gian rảnh bị giảm do phải tìm kiếm và so sánh trên nhiều ứng dụng. Nếu việc này xảy ra hai lần mỗi tuần, riêng bước tìm thông tin có thể chiếm khoảng 80–120 phút/tuần; tần suất cần xác nhận |
| **Success Metric** (baseline → target, cách đo) | Thời gian từ lúc bắt đầu tìm đến khi chọn được địa điểm: baseline ước tính 74–94 phút → mục tiêu thử nghiệm 20 phút. Đo thời gian cho mỗi lần tìm; không tính thời gian di chuyển |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI chỉ hỗ trợ gợi ý địa điểm và tóm tắt review có nguồn. Không tự bịa hoặc khẳng định review, giá hay giờ mở cửa chính xác; không quyết định thay người dùng. Người dùng kiểm tra chi tiết và tự chọn. Nếu thông tin thiếu, sai hoặc không phù hợp, bỏ gợi ý và tìm lại |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:
"so với gemini thì cái này có gì hơn, gemini vẫn ok mà?"- gemini có thể làm, nhưng nó không tối ưu. gemini rộng hơn so với việc thu hẹp lại 1 vấn đề và giải quyết tốt vấn đề đó. đó là lí do vì sao xây dựng 1 mục đích riêng.




## 6. Mức can thiệp AI (CP6)

6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: Độ mơ hồ thấp × Độ phức tạp thấp

Vì sao: Khi chọn theo các tiêu chí, ai sẽ hỗ trợ rule xử lí các review, đánh giá rate, nhu cầu ăn nhẹ hay nặng phù hợp. khi các phương tiện tra cứu hiện nay đánh giá theo tổng thể, không chia đúng rule thì ở đây sẽ có thể check review theo những người có % trùng hợp ý đánh giá, sẽ có độ tương đồng hiểu nhau. rule càng chi tiết, rate càng nhiều thì càng tương đồng nhau. tăng % chính xác trong việc đưa ra gợi ý.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Lưu địa điểm theo khu vực; dùng map và bộ lọc có sẵn; tự đọc review và so sánh. | Người dùng chủ yếu cần tổ chức danh sách hoặc chưa cần tổng hợp review. | Vẫn phải tự đọc nhiều review và so sánh thủ công. | Có thể thử trước để làm baseline. |
| **Rule** | Lọc theo khu vực, khoảng cách, loại địa điểm, ngân sách hoặc điểm đánh giá. | Tiêu chí chọn rõ ràng và dữ liệu có sẵn, cập nhật. | Không hiểu tốt nhu cầu diễn đạt tự nhiên hoặc tóm tắt được nội dung review. | Dùng cho bước lọc. |
| **Workflow** | Nhập tiêu chí → lọc bằng Rule → AI tóm tắt review có nguồn → người dùng kiểm tra và tự chọn. | Quy trình tìm kiếm lặp lại, người dùng thấy việc đọc/tổng hợp review tốn thời gian và bản tóm tắt giúp họ quyết định nhanh hơn. | AI có thể tóm tắt sai, bỏ sót ý kiến trái chiều hoặc dựa trên review cũ; cần cho xem nguồn và có cách quay lại đọc review gốc. | **Chọn thử nghiệm** |
| **Agent** | AI tự tìm, so sánh nhiều nguồn và chủ động chọn địa điểm hoặc thực hiện đặt chỗ. | Chỉ cân nhắc nếu có nhu cầu giao trọn việc và có dữ liệu, quyền hạn cùng cơ chế kiểm soát phù hợp. | Khó kiểm soát lựa chọn; có thể dùng thông tin cũ hoặc hành động sai ý người dùng. | Không chọn ở giai đoạn này. |

**Mức chọn:** Workflow có AI hỗ trợ tóm tắt review; Rule xử lý bộ lọc rõ ràng; người dùng kiểm tra và quyết định.
**Vì sao không chọn mức đơn giản hơn:** Rule có thể lọc theo tiêu chí rõ ràng nhưng không tổng hợp được nội dung review dạng văn bản. Workflow chỉ đáng chọn nếu thử nghiệm xác nhận việc tóm tắt review thực sự giảm thời gian mà vẫn giúp người dùng chọn đúng hơn. Nếu không cải thiện so với tự đọc review hoặc dùng map, nhóm nên quay về No AI/Rule.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Tóm tắt review của các địa điểm tìm được, nêu điểm được khen/chê và lý do địa điểm có thể phù hợp với tiêu chí người dùng. Kèm nguồn để đối chiếu. |
| **Judgment** — con người cân nhắc, quyết định gì? | Người dùng đánh giá các tiêu chí cá nhân như không gian, giá, độ đông và độ phù hợp; kiểm tra review gốc và chọn địa điểm. |
| **Action** — hành động cuối cùng là gì, ai làm? | Người dùng chọn địa điểm rồi đi theo dẫn đường. AI không tự đặt chỗ hoặc thực hiện hành động thay người dùng. |
| **Outcome** — đo kết quả bằng gì? | Thời gian từ lúc bắt đầu tìm đến lúc chọn được địa điểm; mục tiêu thử nghiệm là giảm từ baseline ước tính 74–94 phút xuống khoảng 20 phút. Đo thêm mức độ hài lòng, xem gợi ý phù hợp không và độ tương đồng của phần tóm tắt. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Khu vực, loại địa điểm và tiêu chí người dùng nhập; thông tin địa điểm và review có nguồn. Vị trí/quãng đường có thể lấy từ bản đồ; khả năng truy cập review và độ mới của dữ liệu cần kiểm tra. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Hỏi người dùng bản tóm tắt có phù hợp và đúng với review gốc không; ghi nhận họ có chọn địa điểm được gợi ý không. Chỉ thu thập phản hồi cần thiết và xin phép nếu lưu dữ liệu cá nhân. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Người dùng muốn AI gợi ý địa điểm và tóm tắt review để so sánh; họ vẫn tự kiểm tra thông tin và quyết định nơi đi. Hiện chưa có bằng chứng cho thấy họ muốn giao toàn bộ việc chọn địa điểm cho AI.

- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Báo nhầm địa điểm không phù hợp hoặc dùng thông tin cũ có thể khiến người dùng mất thời gian, thậm chí đi đến nơi không đáp ứng nhu cầu; bỏ sót một địa điểm tốt thường ít rủi ro hơn vì người dùng vẫn có thể tìm thủ công. Vì vậy, AI cần nêu nguồn review, không khẳng định thông tin chưa xác minh, để người dùng kiểm tra review gốc và tự quyết định.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Cá nhân muốn tìm địa điểm phù hợp mục đích tại khu vực cần tìm. |
| **Quy trình** | Nhập khu vực và tiêu chí → lọc địa điểm bằng map/bộ lọc → tìm và xem review trên các nguồn → kiểm tra quãng đường → tự chọn địa điểm. |
| **Bottleneck** | Mất khoảng 40 phút tìm thông tin quanh khu vực và khoảng 20 phút xem review; người dùng khó tổng hợp và so sánh lựa chọn. Cần xác nhận các khoảng thời gian này có bị tính trùng không. |
| **Impact** | Tốn thời gian rảnh và khó chọn được địa điểm phù hợp. Tần suất “2,3 lần mỗi tuần” mới là ước tính, cần kiểm chứng. |
| **Success Metric** (baseline → target, cách đo) | Thời gian từ lúc bắt đầu tìm đến khi chọn địa điểm: baseline ước tính 74–94 phút → mục tiêu thử nghiệm khoảng 20 phút. Đo bằng thời gian thực tế mỗi lần tìm; không tính thời gian di chuyển và tránh tính trùng thời gian đọc review. |
| **Boundary** | AI chỉ tóm tắt review có nguồn được cung cấp/truy cập; không tự tạo review, không khẳng định thông tin giá/giờ mở cửa còn chính xác, không đặt chỗ hoặc quyết định thay người dùng. |
| **AI intervention point** | Tóm tắt điểm được khen/chê trong review và nêu nguồn để người dùng mở kiểm tra. Lọc theo tiêu chí rõ ràng như khu vực, loại địa điểm hoặc khoảng cách dùng Rule. |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | AI có thể bỏ sót ý kiến trái chiều, diễn giải sai hoặc dựa trên review cũ. Người dùng mở review gốc và tự xác minh thông tin quan trọng trước khi chọn; nếu bản tóm tắt không đáng tin thì quay lại tìm thủ công trên map/review. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| AI can thiệp ở đâu | AI gợi ý địa điểm theo nhu cầu, kiểm tra review và đưa ra danh sách chấm điểm. | Rule lọc địa điểm theo tiêu chí rõ ràng; AI chỉ tóm tắt review có nguồn; người dùng tự kiểm tra và chọn. | Giới hạn vai trò AI để giảm rủi ro gợi ý thiếu căn cứ và tận dụng bộ lọc có sẵn. |
| Boundary | Chưa nêu rõ giới hạn và cách xử lý khi AI sai. | AI không tự tạo review hay quyết định thay; người dùng kiểm tra nguồn và có thể quay về cách tìm thủ công. | Cần giữ quyền quyết định cho người dùng và có cách dự phòng khi thông tin sai/thiếu. |
| Success Metric | Mục tiêu giảm thời gian còn khoảng 20 phút. | Giữ 20 phút là mục tiêu thử nghiệm; đo thời gian từ lúc bắt đầu tìm đến lúc chọn, không tính di chuyển và tránh tính trùng. | Baseline và target chưa được kiểm chứng nên cần nêu rõ cách đo và tính chất ước tính. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Độ trung thực với review nguồn | Tóm tắt đúng ý chính, có thể đối chiếu với review được dẫn nguồn. | Bịa chi tiết, gán sai ý kiến hoặc không có nguồn kiểm tra. |
| 2 | Bao quát ý kiến trái chiều | Nêu được cả điểm thường được khen và điểm bị chê nếu có trong nguồn. | Chỉ nêu mặt tích cực hoặc bỏ qua nhận xét quan trọng trái chiều. |
| 3 | Liên quan đến tiêu chí người dùng | Tóm tắt những điểm liên quan đến nhu cầu đã nhập, như giá, không gian hoặc độ yên tĩnh. | Đưa thông tin chung chung, không giúp so sánh theo tiêu chí đã nhập. |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Trung bình | Cả 2 người được phỏng vấn đều mất khoảng 40–60 phút tìm và đánh giá địa điểm. Các bộ lọc và rating hiện tại chưa đủ để họ đưa ra quyết định. Tuy nhiên, mẫu phỏng vấn mới có 2 người, chưa chứng minh nhu cầu phổ biến hoặc người dùng sẽ sử dụng công cụ mới thường xuyên. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Quy trình sử dụng tương đối đơn giản: nhập khu vực và tiêu chí → xem danh sách → đọc tóm tắt review → tự chọn. Người dùng vẫn có thể mở review gốc để kiểm tra. Tuy nhiên, cần thử nghiệm xem họ có hiểu và tin tưởng thông tin tóm tắt hay không. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Trung bình | Có thể xây dựng pilot bằng cách lọc địa điểm theo tiêu chí và dùng AI tóm tắt review từ dữ liệu được cung cấp. Tuy nhiên, chưa xác minh được khả năng truy cập dữ liệu qua API, độ mới của review và thông tin về giá, giờ mở cửa, tình trạng còn bàn. |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | Pilot có thể giới hạn số địa điểm và lượt xử lý để kiểm soát chi phí. Tuy nhiên, cần kiểm tra điều khoản sử dụng dữ liệu từ các nền tảng, quyền riêng tư về vị trí người dùng và chi phí API khi mở rộng. Nhóm chịu trách nhiệm vận hành trong giai đoạn thử nghiệm. |

### 8.2. Kết luận

**Quyết định:** Go — pilot phạm vi nhỏ.

**Lý do:**

- Có tín hiệu về nhu cầu thực tế: cả 2 người được phỏng vấn đều gặp khó khăn khi tìm địa điểm phù hợp và phải sử dụng nhiều ứng dụng để xác thực thông tin.
- Problem có thể đo lường bằng thời gian từ lúc bắt đầu tìm đến khi chọn được địa điểm, kết hợp với mức độ hài lòng và độ chính xác của thông tin.
- Có thể thử nghiệm giải pháp với phạm vi nhỏ, kết hợp Rule để lọc địa điểm, AI để tóm tắt review và con người để kiểm tra, quyết định.
- Chưa cần xây dựng AI Agent tự động tìm kiếm hay đặt chỗ. Việc giới hạn quyền của AI giúp giảm chi phí và rủi ro.
- Các rủi ro hiện tại có thể tiếp tục kiểm chứng thông qua pilot trước khi quyết định mở rộng sản phẩm.

**Nếu Go — pilot nhỏ nhất:**

Thử nghiệm trong 2 tuần với khoảng 15-20 người dùng có nhu cầu tìm quán cafe hoặc địa điểm gặp gỡ bạn bè.

1. Giới hạn phạm vi ở một khu vực cụ thể và một số loại địa điểm phổ biến như quán cafe, địa điểm học tập hoặc gặp gỡ bạn bè.
2. Cho người dùng nhập khu vực, ngân sách, khoảng cách và yêu cầu về không gian (yên tĩnh, phù hợp nhóm đông người, v.v.).
3. Dùng Rule lọc danh sách địa điểm từ dữ liệu được phép sử dụng. AI tóm tắt ưu điểm, nhược điểm từ review có nguồn để người dùng so sánh.
4. Người dùng kiểm tra lại review gốc, thông tin quan trọng và tự chọn địa điểm. Với thông tin còn bàn hoặc mức độ đông đúc chưa được xác minh, công cụ phải thông báo rõ là chưa có dữ liệu.
5. Đo thời gian tìm kiếm, ghi nhận mức độ hài lòng và các trường hợp AI tóm tắt sai, thiếu thông tin hoặc không có nguồn.

**Nếu Not Yet — cần kiểm chứng gì trước:** Phỏng vấn người từng tìm địa điểm gần đây về lần tìm cụ thể gần nhất; xác minh thời gian và bước gây tốn công; thử so sánh cách dùng bộ lọc/danh sách lưu với cách có AI tóm tắt; kiểm tra nguồn dữ liệu review, độ mới và điều kiện sử dụng.

**Nếu No-Go — nên làm gì thay AI:** Cải thiện quy trình không AI: lưu địa điểm theo khu vực, dùng bộ lọc hiện có, chuẩn hóa tiêu chí so sánh và ghi chú review/địa điểm.

**Ngưỡng dừng:**
- Dừng nếu sau 2 tuần, thời gian trung bình từ lúc bắt đầu tìm đến lúc chọn được địa điểm vẫn trên 45 phút, hoặc dưới 50% lượt dùng đạt mục tiêu dưới 30 phút.
- Dừng nếu trên 10–15% bản tóm tắt chứa thông tin sai, bịa hoặc không truy được về review gốc, hoặc có từ 2 trường hợp người dùng đến nơi thấy thông tin quan trọng sai so với công cụ khẳng định.
---

## 9. Hạn chế và hướng tiếp theo

**Hạn chế:**

- **Mẫu kiểm chứng còn nhỏ:** Cần phỏng vấn thêm nhiều nhóm người, nhiều độ tuổi khác nhau để kết luận vấn đề phổ biến với nhiều nhóm người dùng khác nhau.
- **Rủi ro về độ tin cậy:** Review có thể bị seeding, lỗi thời hoặc không phản ánh đúng trải nghiệm thực tế. AI có thể tóm tắt sai hoặc bỏ sót những đánh giá tiêu cực quan trọng.
- **Phụ thuộc nguồn dữ liệu bên ngoài:** Khả năng truy cập thông tin địa điểm, quyền sử dụng review và chi phí API chưa được xác minh đầy đủ.

**Hướng tiếp theo:**

1. Phỏng vấn thêm người dùng và quan sát trực tiếp quá trình tìm địa điểm để xác định bottleneck thực sự.
2. Đo thời gian thực hiện từng bước: tìm địa điểm, đọc review, so sánh lựa chọn và ra quyết định.
3. Thử nghiệm đối chứng giữa cách tìm hiện tại (Google Maps/TikTok), chatbot AI có sẵn và workflow đề xuất của nhóm.
4. Xây dựng pilot nhỏ, tập trung vào một khu vực và một loại địa điểm để kiểm chứng khả năng giảm thời gian tìm kiếm.
5. Đánh giá chất lượng bản tóm tắt AI theo độ chính xác, khả năng truy xuất nguồn và mức độ phù hợp với tiêu chí người dùng.