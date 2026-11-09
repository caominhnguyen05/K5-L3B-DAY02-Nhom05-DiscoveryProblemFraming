# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Tào Quang Vinh    
- MSSV: 2A202604081
- Email trường (không bắt buộc, repo có thể để public): 
- Tên nhóm: Nhom05
- Link repo nhóm: https://github.com/caominhnguyen05/K5-L3B-DAY02-Nhom05-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 |Tốn thời gian |Khi cần tìm nơi đi chơi khu vực lân cận, tôi muốn có thông tin về khu vực xung quanh để tìm được nơi cần tới phù hợp|Cá nhân |tự search 1-2h( xui không ưng ý) |
| 2 |Lặp lại |Khi cần xác minh lưu trú, công an muốn có thông tin về nơi lưu trú có đúng khai báo hay không hay hiện tại nơi lưu trú đang như nào để kiểm soát khu vực hợp lí |công an |gọi xác minh không nghe máy, đến tận nơi nhưng không có nhà |
| 3 |Cần đọc, tổng hợp nhiều thông tin |khi cần tìm hiểu nội dung mới, tôi muốn tổng hợp thông tin cần để nắm rõ hiện tại cần tìm hiểu gì cho đúng, hợp lí |cá nhân |tiếp nhận code 1 ngày nhưng chưa nắm hết |
| 4 |pain từ người khác |khi labcoach cần thông tin về những gì tôi học, tôi muốn tổng hợp thông tin để labcoach nắm được |labcoach |mỗi ngày 30p |
| 5 |tốn thời gian | khi cần xây dựng 1 chế độ ăn uống, tôi muốn duy trì trong 1 thời gian rõ ràng và tác dụng để điều chỉnh mục tiêu hướng tới phù hợp | cá nhân | mỗi ngày tìm thực phẩm phù hợp 1h |
| 6 |lặp lại | khi xây dựng 1 ứng dụng phục vụ cá nhân, tôi muốn hàng ngày dành thời gian nhất định trong khung giờ phù hợp hàng ngày để duy trì việc xây dựng | ceo |mỗi ngày set up lịch trống 30p |
| 7 |lặp lại  |khi cần đến 1 nơi, khách hàng muốn biết thời gian nếu đặt và đến nơi sẽ được tính toán trong bao lâu để đặt xe cho phù hợp | khách hàng | đặt xe không có xế bị delay việc |
| 8 |Pain từ người khác | khi producer nhận thông tin, họ muốn nắm được artist muốn gì để làm đúng mong muốn của artist |artist |artist yêu cầu lại 6,7 lần |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- ý kiến cá nhân, xuất phát từ thực tế

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | 1|khi di chuyển tới 1 nơi mới hay ở khu vực lân cận thiếu thông tin, mất nhiều thời gian để tìm hiểu và lọc thông tin | lượng đánh giá sẽ là bot hay người |
| 2 | 2| với việc tạm trú và thay đổi khu vực sau vài tháng 1 lần của nhiều người, nắm thông tin địa bàn rất quan trọng trong việc bảo đảm an toàn khu vực| lượng người đổi nơi ở liên tục |
| 3 |3 |cần hiểu đúng, tổng hợp không bị thiếu thông tin cần nắm | thông tin có được giữ đủ không hay cái thừa cái thiếu|

### Problem Card #1
| Trường | Nội dung |
|---|---|
| Job Story |Khi cần tìm nơi đi chơi khu vực lân cận, tôi muốn có thông tin về khu vực xung quanh để tìm được nơi cần tới phù hợp|
| Actor | con người |
| Thời điểm / bối cảnh | bí địa điểm |
| Quy trình hiện tại (3–7 bước) |1. mở map 2. mở tiktok 3. tìm thông tin quanh khu vực 4. xem review 5. xem quãng đường 6. đến địa điểm |
| Bottleneck (bước nào, mất bao nhiêu phút) |3. tìm thông tin,40p-1h, hay bị khó chọn |
| Impact (nếu không giải thì sao) |tốn thời gian, 1 tuần dư 2,3 buổi xả stress, mất 120-180p/tuần |
| Success metric (baseline → target) |bước 2,3,4,5 giảm từ 1,2h xuống 20p, thuận tiện |
| Phương án không dùng AI |note địa điểm theo khu vực, check khu vực lân cận trên map |
| Giả thuyết về AI (nếu có) | ai gợi ý bám sát nhu cầu, check review và đưa ra list theo chấm điểm |
| Cảm nhận nhanh | workflow |

Quy trình nháp hiện tại:

```
[1 mở map 2'] → [2 mở tiktok: 2'] → [3 tìm thông tin quanh khu vực: 40']← BOTTLENECK
→ [4 xem review: 20'] → [5 xem quãng đường: 10'] 
→ [6 đến địa điểm: 5-20']

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần kiểm tra thông tin lưu trú tại một địa chỉ, công an muốn xác minh được người đang lưu trú và tình trạng thực tế tại đó để quản lý địa bàn và phát hiện trường hợp khai báo chưa chính xác. |
| Actor | Công an phụ trách quản lý địa bàn |
| Thời điểm / bối cảnh | Khi cần kiểm tra, đối chiếu thông tin khai báo lưu trú hoặc xác minh tình hình tại một nơi lưu trú. |
| Quy trình hiện tại (3–7 bước) | 1. Xác định địa chỉ cần kiểm tra. 2. Tra cứu thông tin lưu trú đã khai báo. 3. Gọi điện cho người lưu trú hoặc chủ cơ sở để xác minh. 4. Nếu không liên hệ được, đến trực tiếp địa chỉ. 5. Hỏi người có mặt hoặc kiểm tra tình hình tại nơi lưu trú. 6. Ghi nhận và đối chiếu kết quả với thông tin đã khai báo. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: người được gọi không nghe máy hoặc không có mặt khi đến kiểm tra, khiến công an phải liên hệ lại hoặc đi kiểm tra nhiều lần. Thời gian và tần suất cần xác minh thực tế. |
| Impact (nếu không giải thì sao) | Tốn thời gian và công sức xác minh; thông tin lưu trú có thể chưa được cập nhật hoặc đối chiếu kịp thời, gây khó khăn cho việc nắm tình hình và quản lý địa bàn. |
| Success metric (baseline → target) | Tỷ lệ xác minh thành công trong lần liên hệ đầu tiên: hiện tại cần đo → mục tiêu tăng. Thời gian trung bình để hoàn tất một lần xác minh: hiện tại cần đo → mục tiêu giảm. |
| Phương án không dùng AI | Chuẩn hóa thông tin liên hệ và lịch xác minh; nhắc cơ sở/người lưu trú cập nhật thông tin khi thay đổi; ghi nhận các lần liên hệ và kết quả để tránh làm lại. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ tổng hợp thông tin đã có, phát hiện trường hợp thông tin thiếu hoặc cần đối chiếu, và gợi ý thứ tự ưu tiên xác minh. Cần kiểm chứng tính chính xác và quy định về dữ liệu trước khi áp dụng. |
| Cảm nhận nhanh | Workflow |
Quy trình nháp hiện tại:

```Xác định địa chỉ cần kiểm tra
→ Tra cứu thông tin lưu trú đã khai báo
→ Gọi người lưu trú hoặc chủ cơ sở
→ Nếu không liên hệ được, đến trực tiếp
→ Ghi nhận tình hình thực tế
→ Đối chiếu và cập nhật kết quả

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi tiếp nhận một codebase hoặc dự án mới, tôi muốn tổng hợp được cấu trúc, chức năng và các luồng xử lý chính để hiểu mình cần tìm hiểu gì và có thể bắt đầu làm việc đúng hướng. |
| Actor | Cá nhân tiếp nhận codebase mới |
| Thời điểm / bối cảnh | Khi mới tham gia một dự án hoặc được giao làm việc với codebase chưa quen. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc yêu cầu hoặc tài liệu bàn giao. 2. Tìm cách chạy dự án. 3. Đọc cấu trúc thư mục và các file chính. 4. Tìm kiếm các chức năng hoặc luồng liên quan đến công việc được giao. 5. Chạy thử chương trình và kiểm tra kết quả. 6. Hỏi người đã làm trước hoặc đồng đội khi chưa hiểu. 7. Ghi chú lại những gì đã tìm hiểu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: phải đọc và lần theo nhiều file để hiểu cấu trúc, chức năng và mối liên hệ giữa các phần. Sau một ngày tiếp nhận code vẫn chưa nắm hết; thời gian đọc và tìm kiếm cụ thể cần đo thêm. |
| Impact (nếu không giải thì sao) | Mất nhiều thời gian làm quen, khó xác định nên bắt đầu từ đâu, dễ bỏ sót thông tin quan trọng hoặc hiểu sai luồng xử lý khi thực hiện công việc. |
| Success metric (baseline → target) | Thời gian để xác định được cấu trúc và luồng liên quan đến một nhiệm vụ: hiện tại cần đo → mục tiêu giảm. Có thể theo dõi thêm số câu hỏi phải hỏi đồng đội và số lần phải sửa do hiểu sai code. |
| Phương án không dùng AI | Bổ sung README và tài liệu bàn giao; tạo sơ đồ cấu trúc, hướng dẫn chạy dự án và mô tả các luồng chức năng chính; ghi chú lại những phần đã tìm hiểu. |
| Giả thuyết về AI (nếu có) | AI có thể hỗ trợ tóm tắt cấu trúc dự án, giải thích các file hoặc luồng code được chọn, và gợi ý những phần cần đọc theo nhiệm vụ. Người tiếp nhận cần kiểm tra lại câu trả lời bằng code và tài liệu thực tế. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```Nhận code và yêu cầu bàn giao
→ Đọc tài liệu có sẵn
→ Tìm cách chạy dự án
→ Đọc cấu trúc thư mục và file
→ Lần theo luồng code liên quan
→ Hỏi đồng đội khi chưa hiểu
→ Ghi chú lại nội dung đã nắm

```

### Card muốn pitch nhất

- Card số:1
- Vì sao: Tôi thường mất khoảng 40 phút đến 1 giờ để tìm và so sánh địa điểm đi chơi quanh khu vực. Việc phải tìm thông tin trên nhiều ứng dụng khiến tôi mất thời gian và khó chọn được nơi phù hợp, trong khi thời gian đi chơi, thư giãn trong tuần có hạn.
- Câu hỏi muốn nhóm phản biện: Vấn đề nằm chủ yếu ở việc tìm địa điểm, đọc review hay so sánh quãng đường? Các bước và thời gian đã phản ánh đúng trải nghiệm thực tế chưa? Có cách nào cải thiện bằng danh sách địa điểm hoặc bộ lọc trên map mà không cần AI không?


### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|

| “Bí địa điểm” chưa nêu rõ bối cảnh, còn thiếu nhu cầu như loại địa điểm, ngân sách hoặc thời gian di chuyển. | Đồng ý | Làm rõ các tiêu chí cần tìm, ví dụ loại địa điểm, khoảng cách và thời gian có thể đi. |

| Impact “1 tuần dư 2,3 buổi xả stress, mất 120–180p/tuần” chưa rõ 120–180 phút là thời gian tìm địa điểm hay tổng thời gian bị ảnh hưởng. | Đồng ý | Làm rõ cách tính: nếu mỗi lần tìm mất 40–60 phút và xảy ra 2 lần/tuần thì thời gian tìm là khoảng 80–120 phút/tuần. |
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
