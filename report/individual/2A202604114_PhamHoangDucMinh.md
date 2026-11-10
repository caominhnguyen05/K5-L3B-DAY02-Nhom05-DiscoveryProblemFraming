# Báo cáo cá nhân — 2A202604114_PhamHoangDucMinh

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

- Card số: #1
- Vì sao: Đây là công việc có tần suất lặp lại rất cao mỗi ngày (20–30 lượt nhờ tìm hộ). Việc tra cứu thủ công bằng cách gõ tay, nhớ vị trí và đi bộ ra kiểm tra kệ gây mất thời gian (3–5 phút/lượt) và tạo ra sự ùn ứ tại quầy. Nó là một "pain point" rất rõ ràng, tốn thời gian và ảnh hưởng trực tiếp đến cả 2 đối tượng (actor) là thủ thư và sinh viên.
- Câu hỏi muốn nhóm phản biện: Liệu vấn đề này có thực sự "đáng" để dùng đến AI (như GenAI/Agent) không? Hay thực chất chỉ cần tối ưu hóa lại giao diện tìm kiếm (UI/UX) và tính năng lọc (Filter/Elasticsearch) của hệ thống phần mềm thư viện hiện tại là đã giải quyết được 80% vấn đề rồi?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Về mức độ cần thiết của AI (Overkill): Việc truy xuất trạng thái (còn/hết) và vị trí sách là thao tác truy vấn dữ liệu có cấu trúc (structured data). Dùng AI tạo sinh (GenAI) cho việc này là "dao mổ trâu giết gà", không khai thác được thế mạnh cốt lõi của AI.|Đồng ý | Hạ mức độ ưu tiên của giải pháp AI: Tôi nhận ra vấn đề này thiên về Rule-based/Workflow truyền thống. Tôi ghi chú thêm vào card: "Cân nhắc phương án không dùng AI (tối ưu UI/Search bar) trước khi nghĩ đến AI".


---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch candidate #1 (thủ thư tra cứu trạng thái và vị trí sách) ở mục 2.1 báo cáo nhóm: actor là thủ thư và sinh viên, bottleneck là 20–30 lượt nhờ tìm hộ mỗi ngày, mỗi lượt 3–5 phút. | Candidate nằm ở hàng 1 của bảng pitch. Nhóm chọn bài của Vinh (tìm địa điểm đi chơi) thay vì bài của tôi. Tôi hoàn toàn đồng ý với lựa chọn này. Vì bài toán tìm địa điểm của Vinh sát với nhu cầu thực tế của mọi thành viên, dễ dàng tìm đối tượng phỏng vấn ngay lập tức. Đồng thời, "đất" để ứng dụng AI (phân tích review, tổng hợp vibe) rõ nét và tiềm năng hơn hệ thống quản lý nội bộ của thư viện. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt (cho bài của Vinh): "Việc người dùng tốn 40-60 phút lướt tìm quán có thực sự là 'nỗi đau' (pain point) không, hay đó vốn dĩ là sở thích lướt mạng xem ảnh đẹp của họ? Làm sao phân biệt được?"  | Giúp nhóm nhận ra cần thu hẹp đối tượng (actor). Nhóm quyết định tập trung vào những người "cần chốt địa điểm cho nhóm đông người hoặc có mục đích rõ ràng (hẹn hò, làm việc)" thay vì những người chỉ tìm kiếm vô định để giải trí.|
| Nhận phản biện | Câu hỏi tôi nhận được: hệ thống quản lý thư viện hiện tại đã có thông tin trạng thái và vị trí sách chưa; nếu đã có thì vì sao thủ thư vẫn tra tay; cải thiện tìm kiếm và hiển thị có đủ giải quyết mà không cần AI không (ghi ở mục 2.1). | Tôi quyết định đổi/hạ mức độ ưu tiên của candidate này xuống (không chọn làm ý tưởng trọng tâm để pitch tiếp). |
| Gom cluster / cây OST | Tham gia cùng nhóm phân loại các ý tưởng và pain point trong đề tài "Tìm địa điểm" của Vinh. Tôi đề xuất chia làm 2 cụm: "Thiếu thông tin tĩnh" (địa chỉ, giá cả) và "Thiếu thông tin động" (độ đông đúc, vibe, review thật).| Giúp nhóm hình thành cây OST (Opportunity Solution Tree) rõ ràng. Xác định được Opportunity lớn nhất nằm ở cụm "Thiếu thông tin động và niềm tin vào review", bỏ qua mảng "thông tin tĩnh" vì Google Maps đã làm quá tốt.|
| Chọn candidate problem |Cùng nhóm thảo luận và biểu quyết chọn nhánh rễ sâu nhất: "Sự khủng hoảng niềm tin vào review ảo và hình ảnh chỉnh sửa quá đà trên các nền tảng mạng xã hội". | Chốt được hướng đi lõi cho CP4, giúp cả nhóm đồng nhất tư tưởng không tập trung làm "một cái Google Maps thứ 2" mà làm "công cụ xác thực sự thật"|
| Kiểm chứng / research | Điền Assumption Map (mục 3.1, 5 giả định) và Interview Snapshot (mục 3.2) trong báo cáo nhóm; commit "CP04 - Group_Report" ngày 09/11. Kiểm chứng: Tôi phụ trách phỏng vấn sâu (1-1) trực tiếp 01 bạn nam (sinh viên năm 3, hay làm leader đi chơi) và gửi khảo sát nhanh qua tin nhắn cho 1 nhóm bạn. |Kết quả kiểm chứng làm nhóm sửa problem: Nhóm nhận ra người dùng không hề thiếu công cụ, họ sẵn sàng nhảy qua 3-4 app (Maps -> TikTok -> FB). Nhóm sửa Problem Statement: chuyển trọng tâm từ "Thiếu bộ lọc địa điểm" sang "Thiếu công cụ xác thực chéo (cross-check) nhanh chóng về không gian (vibe) và tình trạng thực tế".
| Quy trình nhóm | Cùng nhóm vẽ lại quy trình hiện tại (As-is Workflow) của người dùng: (1) Khám phá trên Maps -> (2) Lên TikTok xem clip thực tế -> (3) Đọc comment bóc phốt -> (4) Nhắn tin Fanpage hỏi bàn. | Xác định được Bottleneck (điểm nghẽn) lớn nhất gây mất thời gian là bước (2) và (3): Phải cày hàng tá video và comment để tự lọc ra thông tin thật-giả. |
| Problem Statement | Trực tiếp chấp bút, tổng hợp ý của các thành viên để viết lại câu Problem Statement cuối cùng sau khi kiểm chứng sao cho ngắn gọn, súc tích. | Đảm bảo báo cáo nhóm có một Problem Statement rõ ràng, đầy đủ ngữ cảnh (Context), đối tượng (Actor), và nguyên nhân sâu xa (Root cause). |
| Mức can thiệp AI | Đề xuất giải pháp AI: Dùng AI Agent tự động cào (crawl) các video TikTok/Reels mới nhất được tag tại quán đó, dùng Vision/LLM để đánh giá "vibe" và trích xuất summary cho người dùng. | Nhóm ghi nhận đây là một ý tưởng (Hypothesis) rất khả thi và có tính đột phá (Wow factor) để đưa vào giai đoạn Ideation (lên ý tưởng giải pháp) ở buổi sau. |
| Quyết định | Kiểm tra chéo (review) toàn bộ file Markdown báo cáo nhóm cuối ngày, rà soát lỗi chính tả và tính logic giữa các phần CP1 -> CP4 trước khi nộp. | Đảm bảo báo cáo nhóm chỉn chu, logic xuyên suốt từ lúc nhận bài của Vinh cho đến khi chốt được định nghĩa vấn đề cuối cùng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhập bối cảnh "thủ thư thư viện đại học" và yêu cầu AI liệt kê các pain point phổ biến theo các lăng kính (lặp lại, tốn thời gian).|Gợi ý rất nhanh cấu trúc phân loại vấn đề và đưa ra được các ý tưởng cơ bản (nhập liệu, xếp sách, nhắc trả sách). | Các vấn đề AI đưa ra quá chung chung, mang tính lý thuyết sách vở (ví dụ: "thủ thư mệt mỏi vì khiêng sách nặng") chứ không sát với quy trình phần mềm ở Việt Nam.|Tôi bỏ các ý vật lý (khiêng vác) và tự viết lại các pain point tập trung vào quy trình xử lý luồng dữ liệu (ví dụ: gõ tay mã ISBN, tìm mục lục thủ công). |
| CP2 Problem Card | Đưa bản nháp Problem Card #2 (Tư vấn tài liệu chuyên sâu) cho AI (Claude/ChatGPT) đóng vai "Product Manager khó tính" để phản biện.| Chỉ ra ngay lỗ hổng về tính khả thi của dữ liệu (Data Readiness) và nhắc nhở rủi ro AI bịa thông tin (Hallucination).| AI gợi ý Success Metric quá viển vông (ví dụ: "Giảm 100% thời gian tìm kiếm", "Độ chính xác 100%").| Tôi điều chỉnh lại Success Metric thực tế hơn (giảm xuống dưới 3 phút/lượt) và thêm điều kiện thu hẹp phạm vi (chỉ áp dụng cho E-book ở Phase 1).|
| CP4 Research | Nhờ AI soạn danh sách câu hỏi phỏng vấn sâu (In-depth Interview) cho đề tài nhóm: "Tìm địa điểm đi chơi".| Lên được cấu trúc phỏng vấn tốt (Mở đầu -> Khơi gợi tình huống -> Đào sâu workaround -> Đóng).| AI mặc định nguyên nhân tốn 40-60 phút là do "app thiếu bộ lọc (filter)", nên các câu hỏi toàn xoay quanh việc hỏi người dùng thích filter gì.|Tôi xóa các câu hỏi về filter. Tự thêm các câu hỏi xoáy sâu vào hành vi "check chéo" qua TikTok/Facebook để tìm hiểu về "khủng hoảng niềm tin" đối với review ảo. |
| CP5 Quy trình | Yêu cầu AI vẽ As-is Workflow (quy trình hiện tại) từ lúc nảy sinh nhu cầu đến lúc chốt quán cafe.|Phân chia các bước (Khám phá -> Cân nhắc -> Quyết định) rất gọn gàng, rành mạch. | AI vẽ quy trình theo đường thẳng (Linear) và mặc định người dùng chỉ dùng 1 app duy nhất (Google Maps) từ đầu đến cuối.| Tôi tự vẽ lại quy trình dạng vòng lặp (Loop) và thêm rẽ nhánh đa nền tảng: bộc lộ rõ bước người dùng phải nhảy sang app khác (TikTok, FB) để xác thực "vibe".|
| CP5–6 Problem Statement | Cung cấp các insight sau phỏng vấn và nhờ AI viết lại 3 version Problem Statement sao cho súc tích, chuẩn format.|Giúp câu văn mượt mà, chuyên nghiệp hơn, gom các ý dài dòng thành các cụm từ đắt giá. | Bản tóm tắt của AI làm mất đi các key word quan trọng nhất mang tính địa phương / gen Z như "check vibe", "sợ seeding".| Tôi trộn version của AI với keyword gốc của nhóm để ra câu chốt: nhấn mạnh vào "xác thực chéo không gian (vibe) thực tế" do "mất niềm tin vào review ảo".|
| CP6 Mức can thiệp / quyết định |Đưa Problem Statement cuối cùng cho AI để brainstorm ý tưởng giải pháp (Ideation) và đánh giá mức độ cần thiết của GenAI. | Đề xuất được ý tưởng dùng Vision AI để phân tích video/hình ảnh thực tế và trích xuất tóm tắt không khí (vibe summary).| AI tham vọng khuyên nhóm nên xây dựng một mạng xã hội review địa điểm mới toanh hoặc một app bản đồ mới tích hợp AI (quá sức và phi thực tế).| Tôi bác bỏ ý tưởng làm app bản đồ mới. Quyết định định hướng sản phẩm chỉ là một "AI Agent Aggregator" (Công cụ tổng hợp) gắn dưới dạng Plugin hoặc Mini-app chuyên đi cào dữ liệu để xác thực.|

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Khi nghe các vấn đề từ các bạn, tôi nhận ra một vấn đề tốt phải có độ đồng cảm cao. Đề tài "Thủ thư" của tôi lúc đầu tuy có ý nghĩa về mặt tối ưu hệ thống, nhưng lại quá ngách và thiếu cảm xúc. Trong khi đó, vấn đề "Tìm địa điểm đi chơi" của Vinh vừa được nêu ra là cả nhóm đều đồng ý. Tôi học được rằng, việc chọn đúng bài toán có "pain point" chạm đến số đông trong cuộc sống hàng ngày sẽ giúp quá trình tìm kiếm mẫu phỏng vấn và khai thác insight sau này dễ thở, chân thực hơn rất nhiều.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, Khi vừa chốt đề tài, một vài thành viên đã vội vã đề xuất: "Hay mình làm một cái app bản đồ mới tích hợp video giống hệt TikTok?". Thật may là khi bắt tay vào vẽ As-is Workflow (quy trình hiện tại), nhóm nhận ra người dùng vốn dĩ không cần một bản đồ mới vì Google Maps đã làm quá tốt việc dẫn đường, cái họ cần là công cụ để "xác thực" không gian. Nhóm lập tức phanh lại, quay về bám sát vào bước bottleneck (điểm nghẽn xác thực thông tin) trong quy trình để đào sâu vấn đề, từ chối việc thảo luận tiếp về các tính năng của app.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã thay đổi định kiến hoàn toàn ở phần bảo vệ Problem Card #1 của mình (Thủ thư tra cứu vị trí sách). Lúc đầu tôi đinh ninh đây là "đất diễn" tuyệt vời cho AI. Nhưng khi bị nhóm phản biện rằng: "Nếu hệ thống cơ sở dữ liệu đã có sẵn tình trạng sách, tại sao không làm bộ lọc tìm kiếm thông thường cho tốt mà phải nhồi nhét AI vào?", tôi đã khựng lại. Ngẫm lại, tôi nhận ra mình đã cố tình cường điệu hóa vấn đề để có cớ dùng AI, chứ thực tế bài toán đó giải quyết bằng phần mềm truyền thống sẽ rẻ và nhanh hơn. Tôi lập tức đồng ý hạ độ ưu tiên của card cá nhân mình xuống và dồn phiếu vote cho bài của Vinh.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Cực kỳ bất ngờ. Trước khi phỏng vấn, tôi mang một giả định rằng người dùng tốn 40-60 phút tìm địa điểm vì họ "lười" và hệ thống filter của các app hiện tại quá rườm rà. Nhưng thực tế phỏng vấn chỉ ra điều ngược lại: người dùng rất "siêng năng". Họ sẵn sàng mở song song 3-4 nền tảng (Maps, Instagram, TikTok, Facebook) chỉ để kiểm tra chéo một quán cafe. Điều làm tôi bất ngờ nhất là: họ hoàn toàn không còn tin vào các bài review 5 sao hay hình ảnh lung linh do quán tự đăng nữa, họ khao khát các video quay thực tế từ cộng đồng để thẩm định.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Khó nhất là việc "kìm nén" để không vô tình nhét giải pháp vào câu phát biểu vấn đề. Rất nhiều lần tôi vô thức nháp ra những câu như: "Người dùng cần một ứng dụng AI tổng hợp video để xem vibe quán...". Phải sửa đi sửa lại, gọt giũa từ ngữ nhiều lần mới ra được câu thuần túy miêu tả nỗi đau hiện tại: "Người dùng mất nhiều thời gian xác thực chéo thông tin... do mất niềm tin vào review ảo". Việc phân biệt rạch ròi giữa "Cái người dùng đang vật lộn" và "Cái mình tính làm" thực sự tốn rất nhiều chất xám.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ phản biện nhóm mạnh mẽ hơn ở phần xác định Đối tượng. Ban đầu nhóm khá tham lam khi muốn khoanh vùng "tất cả những người đi chơi cuối tuần". Tôi sẽ ép nhóm thu hẹp ngay từ đầu xuống tệp "Người chịu trách nhiệm tìm chỗ cho nhóm đông người", vì đây mới là tệp cảm nhận nỗi đau sâu sắc nhất (chịu áp lực chọn sai quán sẽ bị bạn bè chê trách). Thu hẹp đối tượng sớm sẽ giúp các câu hỏi phỏng vấn sâu sắc, đi thẳng vào trọng tâm hơn thay vì dàn trải.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Vấn đề cốt lõi (Problem) là người dùng mất niềm tin vào review tĩnh, khiến họ tốn quá nhiều thời gian để xác thực chéo nhằm tìm không gian và tình trạng chỗ ngồi thực tế. Quy trình hiện tại (Workflow) của họ bị nghẽn nghiêm trọng ở bước phải thoát app bản đồ, lặn lội lên TikTok/Facebook đọc bình luận để tự đối chiếu độ chân thực. Mục tiêu của giải pháp là phải triệt tiêu thao tác nhảy app này, giảm thời gian chốt địa điểm từ 45 phút xuống dưới 5 phút. Ranh giới hệ thống được xác định rõ là chỉ xử lý dữ liệu cho các địa điểm có digital footprint (có video check-in cộng đồng), không áp dụng cho quán vỉa hè không ai biết tới. Từ đó, mức can thiệp AI lý tưởng là dùng một Agent Aggregator (Vision + LLM) để tự động quét, đọc hiểu và tóm tắt từ các nền tảng mạng xã hội khác. Quyết định cuối cùng là xây dựng một công cụ đối chiếu thông tin (dạng plugin/mini-app) bám vào hành vi hiện hành, chứ tuyệt đối không đi làm lại một chiếc bản đồ Google Maps thứ hai.

---

## 7. Tài liệu tham khảo

-
