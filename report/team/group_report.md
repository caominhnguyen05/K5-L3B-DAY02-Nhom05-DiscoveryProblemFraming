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
| Mất bao lâu, bao lần?                             |     Tốn cả tiếng đồng hồ để sàng lọc thông tin giả/thật trước mỗi buổi hẹn quan trọng.
     |
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
