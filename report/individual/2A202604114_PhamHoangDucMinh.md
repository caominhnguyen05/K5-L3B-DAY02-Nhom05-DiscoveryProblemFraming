# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phạm Hoàng Đức Minh
- MSSV: 2A202604114
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: 05
- Link repo nhóm: https://github.com/caominhnguyen05/K5-L3B-DAY02-Nhom05-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi nhận được yêu cầu mượn sách từ sinh viên, tôi muốn biết ngay trạng thái và vị trí của sách, để phản hổi nhanh chóng mà không mất công tra cứu thủ công. | Thủ thư tại thư viện, sinh viên | Mỗi ngày có khoảng 20-30 lượt nhờ tìm hộ, mất 3-5 phút/yêu cầu tra cứu tay và đi kiểm tra kệ. |
| 2 | Tốn thời gian | Khi nhập một lô sách mới về thư viện, tôi muốn trích xuất tự động thông tin (tên, tác giả, NXB, năm XB) từ mã ISBN hoặc ảnh bìa, để gõ dữ liệu vào hệ thống nhanh và không sai sót. | Thủ thư tại thư viện | Mất 5-7 phút gõ tay cho 1 cuốn sách. Một đợt nhập 100 cuốn sách tốn trọn 1 ngày làm việc, thỉnh thoảng gõ sai chính tả. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi sinh viên nhờ tư vấn tài liệu tham khảo cho một chủ đề tiểu luận, tôi muốn quét nhanh toàn bộ mục lục và tóm tắt của các sách hiện có, để gợi ý đúng sách đang nằm trên kệ. | Thủ thư tư vấn, Sinh viên | 5-7 lượt sinh viên hỏi mỗi ngày. Mỗi lượt mất 10-15 phút lục tìm trí nhớ hoặc gõ keyword thử sai trên phần mềm cũ. |
| 4 | Pain từ người khác | Khi sinh viên đem trả một chồng sách, tôi muốn biết ngay cuốn nào đang bị trễ hạn hoặc có ghi chú rách/hỏng từ trước, để xử lý phạt ngay tại quầy mà không bắt sinh viên chờ lâu. | Thủ thư tại thư viện, sinh viên | Cuối học kỳ có hàng trăm lượt trả sách mỗi ngày. Thời gian quét mã vạch và đọc thông báo trễ hạn mất 2-3 phút/chồng sách, gây ùn ứ tại quầy. |
| 5 | Tốn thời gian | Cuối học kỳ có hàng trăm lượt trả sách mỗi ngày. Thời gian quét mã vạch và đọc thông báo trễ hạn mất 2-3 phút/chồng sách, gây ùn ứ tại quầy. | Thủ thư quản lý, Trưởng thư viện | Mất 1 đến 2 ngày làm việc  |
| 6 | Lặp lại| Khi đến hạn trả sách của hàng loạt sinh viên, tôi muốn hệ thống tự động lọc danh sách và gửi email/tin nhắn nhắc nhở, để tôi không phải xuất file Excel và gửi thông báo thủ công mỗi ngày. |Thủ thư, Sinh viên| Mỗi ngày có khoảng 50-100 sinh viên đến hạn hoặc quá hạn trả. Thủ thư tốn 45-60 phút mỗi buổi sáng để lọc dữ liệu và thao tác gửi email. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi làm đề xuất mua sắm sách cho năm học mới, tôi muốn có một báo cáo phân tích xu hướng mượn sách và những từ khóa sinh viên tìm kiếm nhưng không có kết quả, để quyết định mua đúng đầu sách đang có nhu cầu cao. | Trưởng thư viện, Cán bộ bổ sung tài liệu| Mỗi học kỳ có 1 đợt lập ngân sách. Hiện tại tốn 1-2 tuần để tải hàng chục file lịch sử mượn trả, dùng hàm Excel tổng hợp thủ công để biết thể loại nào đang hot. |
| 8 | Pain từ người khác | Khi sinh viên đọc xong và tự ý cất sách sai vị trí trên kệ, tôi muốn có một công cụ quét nhanh (ví dụ: đầu đọc RFID), để dễ dàng phát hiện cuốn sách "đi lạc" mà không phải rà soát bằng mắt từng gáy sách. | Thủ thư xếp sách, Sinh viên tìm sách sau đó | Tỷ lệ sách bị đặt sai kệ chiếm 5-10%. Mỗi ngày đều có tình trạng sinh viên báo: "Hệ thống ghi còn sách nhưng tìm trên kệ không thấy". Thủ thư phải tốn 1-2 tiếng rà soát lại các hàng kệ.|

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.


---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tốn nhiều thời gian và dễ sai sót khi nhập liệu thủ công thông tin cho các lô sách mới.| Đây là công việc mất nhiều thời gian nhất (có thể tốn cả ngày) và tạo ra rủi ro sai lệch dữ liệu hệ thống. |Chất lượng ảnh chụp bìa/mã vạch có đủ tốt để AI/OCR đọc chính xác 100% không, đặc biệt với sách cũ. |
| 2 |Khó khăn khi tư vấn tài liệu tham khảo chuyên sâu cho sinh viên dựa trên tóm tắt và mục lục. | Tốn nhiều công sức để đọc/tổng hợp thông tin, phụ thuộc quá nhiều vào trí nhớ cá nhân của thủ thư. |AI có khả năng hiểu đúng ngữ nghĩa chuyên ngành sâu trong các cuốn sách học thuật hay không. |
| 3 | AI có khả năng hiểu đúng ngữ nghĩa chuyên ngành sâu trong các cuốn sách học thuật hay không. | Gây nhàm chán, lặp lại mỗi ngày (45-60 phút) và hoàn toàn không mang lại giá trị gia tăng nào. | Hệ thống quản lý thư viện hiện tại (legacy system) có cho phép kết nối API để lấy dữ liệu tự động ra ngoài không.|

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhập một lô sách mới về thư viện, tôi muốn trích xuất tự động thông tin (tên, tác giả, NXB, năm XB, tóm tắt) từ mã ISBN hoặc ảnh bìa, để gõ dữ liệu vào hệ thống nhanh và không sai sót. |
| Actor | Thủ thư nhập liệu / Cán bộ bổ sung tài liệu. |
| Thời điểm / bối cảnh | Đầu học kỳ hoặc các đợt mua sắm bổ sung sách mới, nhận hàng trăm cuốn sách cùng lúc. |
| Quy trình hiện tại (3–7 bước) |1. Bóc thùng sách. 2. Cầm từng cuốn, tìm thông tin trên trang bìa và trang lót. 3. Gõ thủ công tên sách, tác giả, NXB, mã ISBN vào phần mềm. 4. In và dán mã vạch. 5. Xếp sách lên xe đẩy đưa ra kệ. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Gõ thủ công thông tin vào phần mềm - mất 5–7 phút cho mỗi cuốn sách.|
| Impact (nếu không giải thì sao) | Mất cả ngày hoặc nhiều ngày chỉ để nhập liệu. Chậm trễ đưa sách ra phục vụ sinh viên. Sai chính tả dẫn đến sinh viên không search ra sách.|
| Success metric (baseline → target) |Thời gian xử lý 1 cuốn sách: 5 phút → dưới 1 phút. Tỷ lệ sai sót dữ liệu: >5% → 0%. |
| Phương án không dùng AI |Thuê thêm sinh viên làm thêm (part-time) để hỗ trợ gõ máy tính nhập liệu trong các đợt cao điểm. |
| Giả thuyết về AI (nếu có) |  Sử dụng AI OCR (nhận diện hình ảnh) kết hợp LLM để đọc ảnh chụp bìa sách và tự động điền (mapping) vào các trường dữ liệu tương ứng.|
| Cảm nhận nhanh | Workflow / AI OCR |

Quy trình nháp hiện tại:

```text
Đưa sách vào trước camera/webcam -> Bấm chụp -> AI quét text trên bìa và tự động điền vào form phần mềm -> Thủ thư chỉ cần liếc nhìn đối chiếu và bấm "Lưu".
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi sinh viên nhờ tư vấn tài liệu tham khảo cho một chủ đề tiểu luận, tôi muốn quét nhanh toàn bộ mục lục và tóm tắt của các sách, để gợi ý đúng sách đang nằm trên kệ. |
| Actor | Thủ thư tư vấn / Thủ thư quầy thông tin.|
| Thời điểm / bối cảnh | Giữa và cuối học kỳ, khi sinh viên bắt đầu làm tiểu luận, khóa luận và cần tìm kiếm tài liệu chuyên sâu |
| Quy trình hiện tại (3–7 bước) | 1. Lắng nghe chủ đề sinh viên cần. 2. Thủ thư tự suy nghĩ từ khóa liên quan. 3. Lên hệ thống gõ từ khóa, tìm thử các đầu sách. 4. Rút sách từ trên kệ xuống xem lướt mục lục xem có đúng ý không. 5. Đưa cho sinh viên mượn.|
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, 3 và 4 (Nghĩ từ khóa, tra cứu và đọc lướt mục lục) - mất 10–15 phút cho mỗi sinh viên.|
| Impact (nếu không giải thì sao) |Sinh viên phải chờ đợi lâu. Không tư vấn được nhiều sinh viên cùng lúc. Bỏ sót nhiều cuốn sách hay do thủ thư không nhớ hết. |
| Success metric (baseline → target) |Thời gian tìm ra sách phù hợp: 15 phút → dưới 3 phút/yêu cầu. |
| Phương án không dùng AI | Gắn tag (thẻ phân loại) thủ công thật chi tiết cho từng cuốn sách trên hệ thống (Rất tốn công sức ban đầu). |
| Giả thuyết về AI (nếu có) | Xây dựng một trợ lý AI (RAG) nội bộ đã được học trước tóm tắt/mục lục của toàn bộ sách. Thủ thư chỉ cần nhập prompt câu hỏi của sinh viên. |
| Cảm nhận nhanh | Agent / RAG |

Quy trình nháp hiện tại:

```text
Sinh viên hỏi -> Thủ thư gõ trực tiếp câu hỏi (ngôn ngữ tự nhiên) vào chatbox của hệ thống -> AI phân tích semantic search -> Trả về danh sách 3 cuốn sách phù hợp nhất kèm trích dẫn lý do tại sao phù hợp -> Thủ thư tư vấn lại cho sinh viên.
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến hạn trả sách của hàng loạt sinh viên, tôi muốn hệ thống tự động lọc danh sách và gửi email nhắc nhở, để tôi không phải làm thao tác xuất Excel và gửi thủ công mỗi ngày. |
| Actor | Thủ thư quản lý mượn/trả.|
| Thời điểm / bối cảnh | 8:00 sáng mỗi ngày làm việc.|
| Quy trình hiện tại (3–7 bước) | 1. Đăng nhập phần mềm quản lý thư viện. 2. Xuất báo cáo danh sách mượn sách. 3. Lọc Excel lấy các dòng đến hạn hoặc quá hạn ngày hôm nay. 4. Copy địa chỉ email của sinh viên. 5. Dán vào Gmail, soạn nội dung thông báo. 6. Bấm gửi đi.|
| Bottleneck (bước nào, mất bao nhiêu phút) | Lọc file Excel, copy/paste và gửi email - mất khoảng 45-60 phút mỗi buổi sáng. |
| Impact (nếu không giải thì sao) |Phí phạm thời gian làm việc quý giá của thủ thư vào các thao tác copy/paste cơ học. Đôi khi quên gửi khiến sinh viên bị phạt tiền oan. |
| Success metric (baseline → target) |Thời gian gửi email nhắc nhở mỗi ngày: 45 phút → 0 phút (hoàn toàn tự động). |
| Phương án không dùng AI | Thuê đội IT viết một đoạn script/cron job để tự động gửi email từ database (Automation thông thường).|
| Giả thuyết về AI (nếu có) |Về cơ bản không cần AI. Tuy nhiên, có thể dùng AI để sinh ra các email nhắc nhở với văn phong cá nhân hóa, thân thiện để tăng tỷ lệ phản hồi mang sách đi trả. |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
Setup hệ thống Automation: 8:00 AM hàng ngày -> Tự động query Database tìm sinh viên trễ hạn -> Render nội dung email nhắc nhở có chèn tên SV + tên sách -> Tự động trigger API gửi email mà không cần con người can thiệp.
```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch candidate #1 (thủ thư tra cứu trạng thái và vị trí sách) ở mục 2.1 báo cáo nhóm: actor là thủ thư và sinh viên, bottleneck là 20–30 lượt nhờ tìm hộ mỗi ngày, mỗi lượt 3–5 phút. | Candidate nằm ở hàng 1 của bảng pitch. Nhóm chọn bài của Vinh (tìm địa điểm đi chơi) thay vì bài của tôi. [ĐIỀN: tôi đồng ý hay không với lựa chọn đó, vì sao] |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: hệ thống quản lý thư viện hiện tại đã có thông tin trạng thái và vị trí sách chưa; nếu đã có thì vì sao thủ thư vẫn tra tay; cải thiện tìm kiếm và hiển thị có đủ giải quyết mà không cần AI không (ghi ở mục 2.1). | Tôi đã sửa gì: [ĐIỀN: sau câu hỏi này tôi đổi hoặc giữ gì trong candidate của mình, và vì sao] |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | Điền Assumption Map (mục 3.1, 5 giả định) và Interview Snapshot (mục 3.2) trong báo cáo nhóm; commit "CP04 - Group_Report" ngày 09/11. [ĐIỀN: tôi hỏi bao nhiêu người, ai, bằng cách nào] | [ĐIỀN: kết quả kiểm chứng làm nhóm giữ hay sửa problem thế nào] |
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
