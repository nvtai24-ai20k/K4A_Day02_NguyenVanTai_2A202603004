# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|:---:|-----------|:-----------:|---------------------------------------------------------------|
| 1   | Nguyễn Đức Minh | 2A202602891 | Facilitator (Điều phối thảo luận, quản lý timeline và review) |
| 2   | Phan Đức Duy | 2A202602397 | Problem Owner & Concept Lead (Đề xuất bài toán, bảo vệ concept) |
| 3   | Mai Phan Anh Tùng | 2A202602980 | Workflow Lead (Thiết kế luồng quy trình Hiện tại & Tương lai) |
| 4   | Nguyễn Thọ Đạt | 2A202602484 | Technical Lead (Phân tích kiến trúc kỹ thuật Rule vs AI) |
| 5   | Đinh Trường An | 2A202602393 | Research & Validation Lead (Thu thập phỏng vấn, khảo sát thực tế) |
| 6   | Nguyễn Văn Tài | 2A202603004 | Writer & Risk Lead (Tổng hợp báo cáo, đánh giá rủi ro & fallback) |

**Candidate problem nhóm chọn (1 câu):**  
Người bán hàng và chủ shop online nhỏ rất khó nghĩ ra một chiến lược marketing tổng thể để đưa sản phẩm mới ra thị trường (từ research xu hướng, lên concept quảng bá, tạo ảnh/content, đến triển khai trên sàn TMĐT TikTok Shop/Shopee), dẫn đến việc đăng sản phẩm thụ động không có chiến lược, tỷ lệ chuyển đổi thấp (<1%) và lãng phí ngân sách quảng cáo.

---

## Phase 3 — Group Convergence: từ 18 candidates (6 thành viên × 3) về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Phan Đức Duy | Nhận diện sâu bệnh cho người mới trồng trọt (Nông nghiệp xanh) | Nông dân nhỏ lẻ, người làm vườn tại nhà | Nhận biết bệnh trễ, tra cứu triệu chứng mất 30–60' | Kỹ thuật CV chín muồi nhưng domain nông nghiệp hẹp, nhóm khó validate sâu trong lab |
| 2 | Phan Đức Duy | Hướng dẫn thủ tục hành chính công nhiều tầng nấc | Người dân làm giấy tờ nhà đất, kinh doanh | Mất 3–5 lần đi lại, thiếu checklist giấy tờ chuẩn | Pain rất lớn của xã hội nhưng phụ thuộc dữ liệu cơ quan nhà nước, khó làm pilot |
| 3 | Phan Đức Duy | **AI Marketing Kit: Chiến lược đưa sản phẩm ra thị trường** | **Chủ shop online, seller TikTok Shop/Shopee** | **Research xu hướng thị trường, nghĩ concept và tạo visual** | **Pain cực lớn, volume thị trường khổng lồ, workflow rõ, AI giải quyết đúng thế mạnh** |
| 4 | Nguyễn Đức Minh | Thu thập & đồng bộ Deadline / Thông báo bài tập đa kênh | Sinh viên, trưởng nhóm bài tập lớn | Đọc lọc tin nhắn rác, bóc tách mốc giờ NLP từ 4 app | Rất thân thuộc, workflow cực rõ, nhưng quy mô ảnh hưởng hẹp trong phạm vi trường học |
| 5 | Nguyễn Đức Minh | Tiền kiểm tra (Pre-check) format & checklist báo cáo đồ án | Sinh viên làm đồ án, người chấm | Mất 60–90' dò từng trang đối chiếu rubric | Thực tế và logic tốt, nhưng tần suất sử dụng chỉ rộ lên vào đợt thi cuối kỳ |
| 6 | Nguyễn Đức Minh | Phân loại & gom cụm Log lỗi / Crash reports backend | Sinh viên lập trình, Backend Dev | Đọc stack trace dài, lần tìm root cause mất 30–45' | Mang tính kỹ thuật cao, chỉ phục vụ dân dev, khó phỏng vấn mở rộng |
| 7 | Mai Phan Anh Tùng | Đào tạo công thức pha chế đồ uống cho nhân viên mới | Nhân viên F&B mới, Quản lý ca | Tài liệu rời rạc, nhân viên hỏi lặp lại 3–4 lần/tuần | Pain thật nhưng giải quyết tốt bằng chuẩn hóa tài liệu nội bộ (No AI / Rule là đủ) |
| 8 | Mai Phan Anh Tùng | Đặt hàng nguyên liệu dựa trên dự báo tiêu thụ F&B | Quản lý kho, Chủ chuỗi F&B | Thiếu dữ liệu dự báo gây tồn dư hoặc thiếu nguyên liệu | Cần dữ liệu lịch sử bán hàng POS nhiều tháng, khó giả lập trong lab |
| 9 | Mai Phan Anh Tùng | Phân tích Menu Engineering (giữ/bỏ món theo margin) | Quản lý vận hành chuỗi F&B | Tổng hợp số liệu doanh số và giá vốn mất 100'/tháng | Logic tốt nhưng đã có nhiều phần mềm POS (iPOS, KiotViet) có báo cáo sẵn |
| 10 | Nguyễn Thọ Đạt | Tự động tạo Pull Request (PR) Description theo template | Intern / Junior Developer | Mất 20–25' đọc git diff để tóm tắt PR | Workflow kỹ thuật chuẩn, nhưng phạm vi người dùng hẹp, GitHub Copilot đã có sẵn |
| 11 | Nguyễn Thọ Đạt | Viết Daily Standup và Nhật ký thực tập cuối ngày | Sinh viên thực tập IT | Lục lại Jira, Git log cuối ngày mất 20' | Scope bài toán nhỏ, chỉ là tiện ích cá nhân |
| 12 | Nguyễn Thọ Đạt | Kiểm tra coding convention & try-catch trước khi merge code nhóm | Trưởng nhóm kỹ thuật đồ án sinh viên | Mất 40–60'/lần review và refactor hộ bạn | Pain rất thực tế khi làm bài tập lớn, nhưng có thể giải quyết bằng linter/CI rule |
| 13 | Đinh Trường An | Cá nhân hóa kế hoạch tập thể dục tại nhà chống bỏ cuộc | Người đi làm văn phòng bận rộn | Lười tập, không có lộ trình phù hợp, bỏ cuộc sau 2 tuần | Khó đo lường cam kết của người dùng, ranh giới AI can thiệp chưa rõ ràng |
| 14 | Đinh Trường An | Chờ khám bệnh viện công mất nửa ngày vì không biết tiến độ | Bệnh nhân ngoại trú, người già | Ngồi chờ 2–3 tiếng tại phòng khám đông đúc | Vấn đề xã hội lớn nhưng phụ thuộc hệ thống xếp hàng HIS nội bộ của bệnh viện |
| 15 | Đinh Trường An | Hỗ trợ người dân chuẩn bị hồ sơ thủ tục hành chính tránh đi lại | Người dân làm CCCD, sang tên, công chứng | Hướng dẫn trên mạng khó hiểu, chuẩn bị thiếu giấy tờ | Trùng hướng với candidate #2 của Duy, rủi ro cập nhật luật chậm |
| 16 | Nguyễn Văn Tài | Rà soát và thẩm định đánh giá tài xế ≤2 sao nền tảng gọi xe | Đội QC nền tảng gọi xe, Tài xế | Đọc comment, nghe ghi âm, đối chiếu GPS tốn 120–150h/ngày | Bài toán doanh nghiệp rất hay, nhưng dữ liệu nhạy cảm, sinh viên không truy cập được |
| 17 | Nguyễn Văn Tài | Hotline hỗ trợ xử lý sự cố trụ sạc xe điện công cộng | Tổng đài viên, Tài xế xe điện | Khách đứng chờ tại trụ, tổng đài viên tra mã lỗi thủ công | Mã lỗi là tập cố định có đúng/sai rõ, giải quyết bằng Rule/Chatbot tra cứu là đủ |
| 18 | Nguyễn Văn Tài | Tìm trẻ lạc tại khu vui chơi / công viên giải trí đông người | Phụ huynh, Nhân viên an ninh | Tìm kiếm thủ công qua mô tả và bộ đàm mất ~25'/ca | Rủi ro an toàn cao; nhóm thống nhất nên giải bằng vòng đeo tay QR định danh (No AI) |

### 3.2. Gom trùng / cluster (gom 18 ý thành 4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| **A. Hỗ trợ Kinh doanh nhỏ & Thương mại điện tử** | #3 (AI Marketing Kit), #7, #8, #9 (Vận hành F&B) | Người kinh doanh nhỏ lẻ, chủ shop tự thân thiếu kỹ năng chuyên môn và nguồn lực, phải tự làm mọi việc từ chiến lược đến thực thi | **Tiềm năng thương mại và tính cấp thiết cao nhất, người dùng sẵn sàng chi trả giải pháp** |
| **B. Tối ưu Năng suất Học tập & Làm đồ án** | #4 (Sync deadline), #5 (Pre-check đồ án), #12 (Code convention nhóm) | Sinh viên bị quá tải bởi thông tin phân tán đa kênh và checklist định dạng/review thủ công | Rất gần gũi với nhóm, workflow chặt chẽ nhưng quy mô tác động hẹp trong phạm vi sinh viên |
| **C. Tự động hóa Kỹ thuật Lập trình & Hạ tầng** | #6 (Log lỗi backend), #10 (PR description), #11 (Standup), #17 (Mã lỗi trạm sạc) | Kỹ sư/developer tốn thời gian vào các tác vụ lặp lại xung quanh việc viết code, debug và vận hành | Giải pháp kỹ thuật rõ ràng nhưng thị trường đã có nhiều công cụ lập trình cạnh tranh |
| **D. Dịch vụ Công, Y tế & Đời sống Xã hội** | #1 (Sâu bệnh cây trồng), #2, #15 (Thủ tục hành chính), #13 (Tập thể dục), #14 (Khám bệnh), #16 (QC tài xế), #18 (Tìm trẻ lạc) | Người dân và cộng đồng gặp khó khăn khi tiếp cận quy trình phức tạp ngoài đời sống | Tác động xã hội cao nhưng rào cản về dữ liệu độc quyền, trách nhiệm pháp lý lớn hoặc nên dùng No AI |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **1. AI Marketing Kit đưa sản phẩm ra thị trường (Duy)** | - Pain point sát sườn của hàng trăm nghìn seller online nhỏ lẻ.<br>- Workflow end-to-end rõ ràng từ nhập sản phẩm đến xuất bản.<br>- Tận dụng hoàn hảo năng lực AI đa phương thức (NLP phân tích trend + GenAI tạo visual). | - Chất lượng hình ảnh AI tạo ra có đủ chân thực và đáp ứng tiêu chuẩn khắt khe của sàn TMĐT không.<br>- AI có cập nhật kịp thời xu hướng thay đổi nhanh theo tuần không. |
| **2. Thu thập & đồng bộ Deadline đa kênh (Minh)** | - Workflow thẳng hàng, an toàn cao, 100% sinh viên gặp phải.<br>- Điểm nghẽn bóc tách mốc giờ tự nhiên đo lường được chính xác từng phút. | - Thị trường hẹp (chủ yếu cho sinh viên), giá trị kinh tế không đột phá bằng bài toán kinh doanh. |
| **3. Tự động tạo PR Description từ Git diff (Đạt)** | - Mạch kỹ thuật rất rõ (git diff -> LLM -> Markdown).<br>- Dễ xây dựng pilot nhanh bằng script. | - Tệp người dùng hẹp; các IDE hiện đại đã tích hợp sẵn tính năng tương tự. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **AI Marketing Kit (Duy)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34/35** |
| **Đồng bộ Deadline đa kênh (Minh)** | 5 | 5 | 4 | 4 | 5 | 5 | 4 | **32/35** |
| **Tự động tạo PR Description (Đạt)** | 5 | 4 | 4 | 4 | 5 | 4 | 4 | **30/35** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Khó nghĩ ra chiến lược marketing để đưa sản phẩm mới ra thị trường — Giải pháp AI Marketing Kit cho Seller nhỏ lẻ trên sàn TMĐT (của bạn Phan Đức Duy)
```

**Vì sao chọn (4-5 câu):**

```text
1. Bài toán đánh trúng nỗi đau 'sinh tử' của hàng trăm nghìn chủ shop online và seller nhỏ lẻ trên TikTok Shop và Shopee: không có ngân sách 10–20 triệu/tháng thuê agency nhưng không biết tự làm marketing thế nào cho bài bản.
2. Quy trình hiện tại vô cùng nặng nề (mất 3–7 ngày cho 1 sản phẩm mới), trong đó các bước nghiên cứu xu hướng và tạo visual sản phẩm chiếm phần lớn thời gian và thường dựa trên cảm tính.
3. Bài toán phát huy tối đa sức mạnh của AI: từ khả năng tổng hợp xu hướng thị trường (NLP Search) đến sáng tạo concept 'hơi thở mới' và sinh hình ảnh visual thương phẩm (GenAI Multimodal).
4. Ranh giới giữa máy và người (Human Boundary) cực kỳ rõ ràng ở 2 chốt chặn: Người dùng tự duyệt concept chiến lược và trực tiếp kiểm duyệt chất lượng hình ảnh/content trước khi bấm xuất bản.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Đối với bài Đồng bộ Deadline đa kênh (Minh): Mặc dù workflow rất chặt chẽ, dễ pilot và ít rủi ro, nhưng quy mô tác động chỉ giới hạn trong môi trường học đường, chưa mang lại giá trị gia tăng kinh tế rõ rệt như bài toán marketing thương mại.
- Đối với bài Tự động tạo PR Description (Đạt): Tệp người dùng quá đặc thù (lập trình viên), đồng thời các công cụ sẵn có như GitHub Copilot / Cursor đã hỗ trợ tính năng này rất tốt, khoảng trống thị trường cho nhóm không còn nhiều.
- Đối với các bài F&B, Nông nghiệp và Hành chính công: Đòi hỏi dữ liệu chuyên ngành sâu, thiết bị phần cứng đặc thù hoặc phụ thuộc vào cơ sở dữ liệu đóng của cơ quan nhà nước, không khả thi để kiểm chứng và xây dựng giải pháp trong buổi lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
- Tranh cãi ban đầu: Thành viên trong nhóm (bạn Minh và bạn Đạt) lo ngại rằng bước 'AI tạo ảnh quảng bá sản phẩm' rất dễ bị hallucination (ảnh không khớp với sản phẩm thật, sai tỷ lệ, sai chi tiết kỹ thuật) hoặc concept gợi ý quá chung chung.
- Cách nhóm chốt đồng thuận: Nhóm quyết định không coi AI là 'cây đũa thần tự động 100%'. Thay vào đó, thiết lập 2 Human Boundary bắt buộc: Người dùng phải chọn 1 trong 3-5 concept AI đề xuất, và nếu ảnh AI sinh ra chưa hoàn hảo thì được sử dụng làm 'Moodboard / Reference' chuyên nghiệp để chụp lại nhanh, hoặc người dùng chỉnh sửa trên tool trước khi đăng. Điều này triệt tiêu rủi ro sai sót thương hiệu.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| **Interview** | 3 người (Chủ shop online & freelancer) | - **Chị Lan (Chủ shop phụ kiện thời trang TikTok Shop):** *"Mỗi lần nhập lô kẹp tóc hay túi xách mới về, mình stress nhất là không biết viết kịch bản video với chụp ảnh thế nào cho đỡ phèn. Bỏ 500k chạy ads mà bán được 2 đơn, tự làm thì mất đứt 3-4 ngày mà view lẹt đẹt."*<br>- **Anh Tuấn (Kinh doanh đồ gia dụng Shopee):** *"Thuê agency viết bài với chụp ảnh họ báo 12 triệu/tháng cho 10 sản phẩm, shop nhỏ mới bán lấy đâu ra tiền. Tự mò Canva thì cả buổi tối mới xong 1 cái ảnh bìa."*<br>- **Bạn Trang (Freelancer kinh doanh nến thơm online):** *"Có sản phẩm tốt nhưng mù tịt về nghiên cứu thị trường, không biết Gen Z đang chuộng tone màu hay thông điệp gì để làm theo."* | Người bán có kinh nghiệm lâu năm (>3 năm) cho rằng họ đã có tệp khách quen và gu thẩm mỹ riêng, họ không cần AI gợi ý concept mà chỉ cần công cụ resize ảnh hàng loạt và viết mô tả chuẩn SEO. | Thu hẹp actor mục tiêu tập trung vào: **Chủ shop nhỏ mới kinh doanh, seller cá nhân trên TikTok Shop/Shopee, và người bán không có chuyên môn marketing**. |
| **Survey / poll** | 10 người (Sinh viên & người quen có bán hàng online) | - **8/10 người (80%)** xác nhận khâu tốn thời gian nhất là: Tìm kiếm xu hướng mới và lên ý tưởng hình ảnh (trung bình mất 3–5 ngày cho 1 đợt hàng mới).<br>- **7/10 người (70%)** thừa nhận từng đăng sản phẩm 'trơ' không có chiến lược dẫn đến không có lượt mua hoặc lãng phí tiền quảng cáo. | 2 người lo lắng nếu dùng AI đại trà thì hình ảnh các shop sẽ bị na ná nhau, mất đi tính độc bản của thương hiệu thủ công. | Bổ sung vào workflow tính năng: Cho phép người dùng tải lên hình ảnh sản phẩm gốc và tùy chọn Tone & Mood / Brand Voice riêng biệt. |
| **Review trên diễn đàn TMĐT** | ~20 bài đăng trên group 'Cộng đồng Người bán hàng TikTok Shop Việt Nam' | Hàng loạt bài viết hỏi: *"Mới mở shop nên thuê agency hay tự chạy?", "Cách tìm trend nổ đơn trên TikTok", "Xin prompt viết content bán hàng không bị bóp tương tác".* | Nhiều seller bị khóa sản phẩm do vi phạm từ khóa cấm hoặc ảnh vi phạm chính sách của sàn. | Nhóm bổ sung thêm tính năng: AI tự động quét và cảnh báo các từ khóa nhạy cảm / vi phạm chính sách sàn TMĐT trước khi đăng. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Nỗi đau thật sự của người bán không nằm ở thao tác kỹ thuật 'đăng bài lên sàn', mà nằm ở khoảng trống kỹ năng: Họ có sản phẩm tốt nhưng hoàn toàn bế tắc ở khâu chuyển đổi từ thông tin sản phẩm thô thành một concept marketing hợp xu hướng thị trường và có bộ hình ảnh visual bắt mắt để kích thích chuyển đổi.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Canva (Magic Studio)** | https://www.canva.com | Tạo ảnh, banner, xóa nền sản phẩm | Kho template đồ sộ, giao diện kéo thả trực quan, có AI sinh ảnh và text cơ bản | Không có tính năng phân tích xu hướng thị trường; người dùng vẫn phải tự nghĩ concept từ đầu; rời rạc với sàn TMĐT | Giữ giao diện trực quan, nhưng phải thêm tầng phân tích xu hướng thị trường tự động trước khi sinh ảnh |
| **ChatGPT / Claude** | https://chatgpt.com | Viết content mô tả, gợi ý concept marketing | Khả năng ngôn ngữ xuất sắc, brainstorm ý tưởng nhanh | Rời rạc với visual sản phẩm (chỉ tạo text); không có kết nối dữ liệu bán hàng thực tế của các sàn TMĐT tại Việt Nam | Cần đóng gói thành bộ kit tích hợp: Input 1 lần ra cả chiến lược, content và hình ảnh visual đồng bộ |
| **CapCut Commerce Pro** | https://commerce.capcut.com | Tạo video quảng cáo sản phẩm cho TikTok Shop | Tự động tạo video ngắn từ ảnh sản phẩm, ghép nhạc trend | Chỉ tập trung vào video TikTok, bỏ qua sàn Shopee; thiếu nghiên cứu insight khách hàng và chiến lược định vị thương hiệu | Không nên tham làm công cụ dựng video phức tạp; tập trung tối ưu bộ hình ảnh visual và nội dung chuẩn sàn TMĐT |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm nên xây dựng một Workflow khép kín 'End-to-End': Chỉ từ 1 input thông tin sản phẩm thô -> Tự động research xu hướng -> Đề xuất concept -> Sinh bộ visual & content đồng bộ chuẩn sàn. Nhóm dứt khoát KHÔNG build công cụ biên tập video phức tạp và KHÔNG tự động nạp tiền chạy ads để tránh rủi ro tài chính cho người dùng.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Workflow đính kèm theo sơ đồ nhóm đã thiết kế: `02-group-problem-statement-workflow.png`

```text
CURRENT STATE — 3-7 ngày (cho 1 sản phẩm)

[1 Có sản phẩm: sẵn] 
→ [2 Research xu hướng thủ công: 120-240']  <-- BOTTLENECK CHÍNH
→ [3 Nghĩ concept marketing (cảm tính): 60-120'] 
→ [4 Tạo ảnh quảng bá / thuê chụp: 120-240'] 
→ [5 Viết content, mô tả sản phẩm: 60-120'] 
→ [6 Đăng lên sàn TMĐT + chạy ads: 60-120'] 
→ [7 Hiệu quả thấp (tỷ lệ chuyển đổi <1%) → quay lại bước 3 thử hướng khác]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1. Có sản phẩm | Chủ shop | Hàng hóa thực tế, thông số kỹ thuật | Ý định đưa sản phẩm lên sàn bán | Có sẵn | Bước chuẩn bị ban đầu |
| 2. Research xu hướng thủ công | Chủ shop | TikTok, Shopee, Google Trends, đối thủ | Ghi chú nháp về xu hướng, hashtag | 120–240 phút / sản phẩm | **BOTTLENECK CHÍNH:** Mất nhiều thời gian lướt xem thủ công, dữ liệu rời rạc, dễ bị quá tải thông tin |
| 3. Nghĩ concept marketing | Chủ shop | Ghi chú xu hướng + cảm tính cá nhân | 1 ý tưởng/góc tiếp cận quảng bá | 60–120 phút | Thường bế tắc ý tưởng ("blank page"), ý tưởng thiếu 'hơi thở mới', trùng lặp đối thủ |
| 4. Tạo ảnh quảng bá | Chủ shop / Thuê ngoài | Ảnh chụp thô bằng điện thoại, Canva | Bộ 3–5 ảnh sản phẩm hoàn chỉnh | 120–240 phút (hoặc 2–3 ngày nếu thuê) | Khó tự chụp đẹp, thuê photographer thì đắt (1–2 triệu/bộ), dùng Canva thì mất thời gian chỉnh sửa |
| 5. Viết content & mô tả | Chủ shop | Concept đã chọn | Tiêu đề SEO, mô tả sản phẩm, bài post | 60–120 phút | Văn phong khô cứng, thiếu tính thuyết phục, dễ dính từ khóa cấm của sàn |
| 6. Đăng sàn & chạy ads | Chủ shop | Bộ ảnh + Content + Giá | Sản phẩm live trên sàn, set chiến dịch | 60–120 phút | Thao tác thủ công trên từng nền tảng (TikTok Shop, Shopee) |
| 7. Đánh giá & làm lại | Chủ shop | Doanh số, lượt click, chỉ số chuyển đổi | Quyết định giữ hay bỏ | Sau 3–7 ngày theo dõi | Tỷ lệ chuyển đổi thường dưới 1%, không có doanh thu dẫn đến chán nản, quay lại bước 3 |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn nghiêm trọng nhất nằm ở chuỗi Bước 2 đến Bước 4 (Nghiên cứu thị trường -> Nghĩ concept marketing -> Tạo hình ảnh visual). Quá trình này ngốn từ 5 đến 10 giờ làm việc thủ công nhưng kết quả hoàn toàn phụ thuộc vào cảm tính, khiến sản phẩm đăng lên bị 'chìm' giữa hàng nghìn đối thủ và lãng phí ngân sách quảng cáo ban đầu.
```

### 5.2. Future workflow bản nhóm

Sơ đồ Future State với sự tham gia của AI và ranh giới con người kiểm duyệt (Human Boundary):

```text
FUTURE STATE — 1-2 giờ (AI Marketing Kit)

[1 Nhập thông tin SP (brand, ảnh, giá, chất liệu): 10' - Người] 
→ [2 AI research thị trường + xu hướng: 5' - AI Step] 
→ [3 AI đề xuất 3-5 concept marketing "hơi thở mới": 5' - AI Step] 
→ [4 Người dùng chọn hướng phù hợp: 15' - HUMAN BOUNDARY 1] 
→ [5 AI tạo ảnh quảng bá + viết content chuẩn sàn: 10' - AI Step] 
→ [6 Người dùng review + chỉnh sửa: 20-30' - HUMAN BOUNDARY 2] 
→ [7 AI hỗ trợ format chuẩn & đăng lên TikTok Shop/Shopee: 10' - Máy/API]

Fallback: Nếu AI concept không phù hợp -> yêu cầu AI đề xuất lại với điều kiện khác. Nếu ảnh AI tạo không đạt -> dùng làm moodboard reference để tự chụp/chỉnh sửa. Mọi nội dung bắt buộc qua người duyệt trước khi live.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| **Tổng thời gian hoàn thiện** | 3–7 ngày / sản phẩm | **Dưới 2 giờ** / sản phẩm | Bấm giờ từ lúc nhập thông tin đến khi sản phẩm sẵn sàng đăng sàn |
| **Số bước thực hiện** | 7 bước rời rạc | 7 bước tích hợp trong 1 nền tảng | Đếm số lượng màn hình/công cụ người dùng phải tương tác |
| **Số bước thủ công nặng nhọc** | 5 bước (research, concept, chụp ảnh, viết bài, đăng bài) | **0 bước** (chỉ còn 2 bước duyệt: chọn concept & chỉnh sửa) | Đếm số tác vụ phải tự làm bằng tay không có AI hỗ trợ |
| **Chi phí triển khai marketing** | 5–20 triệu/tháng (thuê agency) hoặc 0đ nhưng mất 50 giờ công | **Dưới 500.000đ/tháng** (chi phí API token AI) | Tính toán hóa đơn dịch vụ hoặc chi phí tài nguyên |
| **Tỷ lệ chuyển đổi đơn hàng** | Dưới 1.0% | **2.0% – 3.0%** | Theo dõi trên Dashboard Analytics của Shopee / TikTok Shop |
| **Risk mới phát sinh** | Lãng phí tiền ads, trễ tiến độ | Ảnh AI có thể khác lệch sản phẩm thật nếu không kiểm soát | Tỷ lệ người dùng phải tự chỉnh sửa lại ảnh ở Bước 6 |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Chủ shop online nhỏ, cá nhân kinh doanh trên sàn TMĐT (TikTok Shop, Shopee) và người khởi nghiệp tự thân tại Việt Nam không có ngân sách thuê agency chuyên nghiệp. |
| **Workflow** | Quy trình đưa sản phẩm mới ra thị trường gồm: nghiên cứu xu hướng thị trường $\rightarrow$ xây dựng ý tưởng concept quảng bá $\rightarrow$ tạo hình ảnh sản phẩm $\rightarrow$ viết bài mô tả chuẩn SEO $\rightarrow$ đăng bán và chạy quảng cáo trên sàn TMĐT. |
| **Bottleneck** | Bước nghiên cứu thị trường, sáng tạo concept và sản xuất hình ảnh visual tốn 5–10 giờ thủ công, bế tắc ý tưởng và thiếu dữ liệu định hướng. |
| **Impact** | Mất 3–7 ngày cho một sản phẩm mới; 70% người bán đăng bài không có chiến lược dẫn đến tỷ lệ chuyển đổi dưới 1% và lãng phí 2–5 triệu đồng tiền quảng cáo không hiệu quả mỗi tháng. |
| **Success Metric** | Rút ngắn thời gian hoàn thiện chiến lược marketing từ 3–7 ngày xuống dưới 2 giờ/sản phẩm; tăng tỷ lệ chuyển đổi đơn hàng từ <1% lên 2–3%; giảm chi phí chuẩn bị tài sản marketing ít nhất 70%. |
| **Boundary** | **Làm:** Nghiên cứu xu hướng, đề xuất concept, sinh bộ ảnh visual sản phẩm và bài viết chuẩn SEO cho sàn TMĐT.<br>**Không làm:** Dựng video chuyên nghiệp phức tạp, tự động nạp tiền ngân sách quảng cáo, và tự ý xuất bản bài đăng mà không qua người duyệt. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Field *Success Metric* ban đầu chỉ ghi "tăng doanh số và làm nhanh hơn", chưa có con số baseline hiện tại và mục tiêu sau cải thiện. Field *Boundary* chưa làm rõ ranh giới xử lý hình ảnh sản phẩm thật.
- Tôi sửa gì: Bổ sung số liệu baseline cụ thể (từ 3–7 ngày xuống <2 giờ, chuyển đổi từ <1% lên 2–3%) và xác định rõ Boundary: AI không can thiệp vào ví tiền quảng cáo của khách hàng.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp / [x] **Cao (nhiều cách trả lời vẫn OK)** — Vì sao: Lĩnh vực sáng tạo marketing không có một đáp án duy nhất đúng hoặc sai; cùng một sản phẩm có thể tiếp cận theo hướng hài hước, sang trọng, câu chuyện cảm xúc hoặc đánh vào công năng.
- Độ phức tạp: [ ] Thấp / [x] **Cao (3+ bước/nguồn, phụ thuộc nhau)** — Vì sao: Quy trình đòi hỏi kết hợp dữ liệu xu hướng thị trường, bối cảnh ngành hàng, xử lý ngôn ngữ tự nhiên (viết copy) và sinh hình ảnh đa phương thức (image generation) qua nhiều bước liên hoàn.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô: ĐỘ MƠ HỒ CAO — ĐỘ PHỨC TẠP CAO (Góc trên bên phải của ma trận độ phù hợp)
```

**Vì sao (2-3 câu):**

```text
Bài toán đòi hỏi cả năng lực sáng tạo đa dạng (mơ hồ) lẫn sự phối hợp của chuỗi công cụ đa phương thức từ tìm kiếm dữ liệu, sinh văn bản đến tạo ảnh (phức tạp). Các giải pháp lập trình quy tắc tĩnh (Rule) hoàn toàn bất lực ở bài toán này, bắt buộc phải có sự tham gia của mô hình AI tạo sinh (GenAI).
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng template có sẵn trên Canva / Excel / Shopee Form | Khi sản phẩm không cần cạnh tranh, chỉ cần điền thông tin cơ bản | Nội dung rập khuôn, ảnh đơn điệu, không có tính cá nhân hóa theo xu hướng | **Chỉ dùng cho Bước 1 & 7:** Kiểm tra định dạng đầu vào và cấu trúc API đăng bài |
| **Workflow** | **AI Marketing Kit tuần tự có chốt chặn con người (Human-in-the-loop):** Nhập data -> AI research trend -> AI tạo concept -> Người duyệt -> AI tạo visual/text -> Người duyệt -> Xuất bản | **ĐỦ VÀ TỐI ƯU NHẤT:** Khi cần tự động hóa chuỗi quy trình sáng tạo nhưng vẫn đảm bảo sự kiểm soát chất lượng tuyệt đối của người bán | Rủi ro xảy ra khi AI sinh hình ảnh không chuẩn với chất liệu thật, được giải quyết bằng bước Human Review | **CHỌN TOÀN BỘ GIẢI PHÁP CHÍNH** |
| **Agent** | Autonomous Marketing Agent: AI tự động lướt web, tự chọn sản phẩm bán chạy, tự quyết định concept, tự tạo ảnh và tự bấm chạy ads trên TikTok Shop | Chỉ phù hợp khi các hệ thống TMĐT cho phép tự động hóa hoàn toàn và doanh nghiệp chấp nhận rủi ro tài chính cao | Agent có thể hiểu sai đối tượng, tự động tiêu tiền quảng cáo vô tội vạ, hoặc tạo nội dung vi phạm chính sách dẫn đến bị khóa gian hàng | **KHÔNG CHỌN** (quá rủi ro và không cần thiết cho quy mô seller nhỏ) |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?**  
   $\rightarrow$ *Không. Rule chỉ tạo ra được các biểu mẫu tĩnh, hoàn toàn không thể phân tích ngôn ngữ xu hướng thị trường hay sáng tạo concept và hình ảnh cho từng sản phẩm mới.*
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?**  
   $\rightarrow$ *Quy trình đi thẳng theo đường ống (Pipeline): Input $\rightarrow$ Trend $\rightarrow$ Concept $\rightarrow$ Visual/Text $\rightarrow$ Publish; có nhánh quay đầu ngắn ở các điểm duyệt nếu người dùng yêu cầu làm lại.*
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?**  
   $\rightarrow$ *Không cần thiết phải dùng Autonomous Agent tự trị hoàn toàn. Một hệ thống Workflow định sẵn các bước kết hợp gọi mô hình AI chuyên biệt (LLM + Image Diffusion) là đã giải quyết trọn vẹn bài toán.*
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?**  
   $\rightarrow$ *Chính chủ shop sẽ phát hiện ngay tại Bước 4 (chọn concept) và Bước 6 (duyệt visual/content); chỉ mất 2–5 phút để bấm yêu cầu tạo lại hoặc tự chỉnh sửa trực tiếp.*
5. **Có hạ được từ Agent → Workflow → Rule không?**  
   $\rightarrow$ *Có. Nhóm đã chủ động hạ từ mô hình 'Autonomous Agent' xuống 'AI Workflow có con người kiểm soát' để đảm bảo an toàn tuyệt đối về mặt thương hiệu và chi phí cho người dùng.*

**Mức chọn:**

```text
WORKFLOW (AI-Powered Workflow with Human-in-the-loop)
```

**Vì sao chọn (3-4 câu):**

```text
1. Mô hình Workflow giúp xâu chuỗi nhịp nhàng các năng lực AI đa dạng (tìm kiếm trend, viết content, tạo visual) theo đúng trình tự nghiệp vụ chuẩn của một chiến dịch marketing.
2. Thiết lập được 2 chốt chặn con người (Human Boundary) cực kỳ vững chắc, loại bỏ hoàn toàn nguy cơ AI bị ảo giác hay sinh ảnh sai lệch thực tế.
3. Chi phí triển khai và độ phức tạp kỹ thuật thấp hơn rất nhiều so với Autonomous Agent, đảm bảo tính khả thi để triển khai và kiểm chứng ngay.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Mức Rule (No AI) không thể giải quyết được bài toán vì marketing đòi hỏi sự thấu hiểu ngữ cảnh thị trường, cảm xúc khách hàng và khả năng sáng tạo hình ảnh mà các câu lệnh if-else hoặc template tĩnh không bao giờ làm được.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Chủ shop online nhỏ, cá nhân kinh doanh trên sàn TMĐT (TikTok Shop, Shopee) và người khởi nghiệp tự thân tại Việt Nam không có ngân sách thuê agency chuyên nghiệp. |
| **Workflow** | Quy trình đưa sản phẩm mới ra thị trường gồm: nhập thông số sản phẩm $\rightarrow$ AI nghiên cứu xu hướng thị trường $\rightarrow$ AI gợi ý 3–5 concept $\rightarrow$ người dùng chọn concept $\rightarrow$ AI sinh trọn bộ visual và bài viết chuẩn SEO $\rightarrow$ người dùng duyệt và chỉnh sửa $\rightarrow$ xuất bản lên sàn TMĐT. |
| **Bottleneck** | Bước nghiên cứu thị trường, sáng tạo concept và sản xuất hình ảnh visual tốn 5–10 giờ thủ công, bế tắc ý tưởng và thiếu dữ liệu định hướng. |
| **Impact** | Mất 3–7 ngày cho một sản phẩm mới; 70% người bán đăng bài không có chiến lược dẫn đến tỷ lệ chuyển đổi dưới 1% và lãng phí 2–5 triệu đồng tiền quảng cáo không hiệu quả mỗi tháng. |
| **Success Metric** | Rút ngắn thời gian hoàn thiện bộ tài sản marketing từ 3–7 ngày xuống **dưới 2 giờ / sản phẩm**; tăng tỷ lệ chuyển đổi đơn hàng từ <1% lên **2.0% – 3.0%**; giảm chi phí sản xuất tư liệu marketing ít nhất **70%**. |
| **Boundary** (làm / không làm) | **Làm:** Nghiên cứu xu hướng, đề xuất 3-5 concept tiếp cận, sinh bộ ảnh visual sản phẩm và bài viết chuẩn SEO cho sàn TMĐT.<br>**Không làm:** Dựng video phức tạp, tự động nạp tiền ngân sách quảng cáo, và tự ý xuất bản bài đăng mà không qua người duyệt. |
| **AI intervention point** | Can thiệp ở 3 điểm cốt lõi: (1) Sau khi nhận thông tin sản phẩm thô $\rightarrow$ trước khi chọn concept (AI Research Trend); (2) Sau khi có concept $\rightarrow$ trước khi người duyệt visual (AI Generate Visual & Content); (3) Sau khi người duyệt $\rightarrow$ trước khi đăng bài (AI Format chuẩn sàn). |
| **Mức chọn** | **Workflow:** Vì quy trình có thứ tự rõ ràng, cần kết hợp đa mô hình AI (Text + Image) và bắt buộc phải có chốt chặn con người kiểm duyệt chất lượng. |
| **Rủi ro & người thật kiểm tra** | **Rủi ro lớn nhất:** Hình ảnh AI tạo ra bị sai lệch màu sắc/chất liệu so với sản phẩm thực tế, hoặc content chứa từ khóa vi phạm chính sách sàn.<br>**Người thật kiểm tra:** Chủ shop trực tiếp rà soát và bấm duyệt tại Bước 4 và Bước 6 bằng giao diện checklist trực quan; nếu ảnh chưa đạt, hệ thống tự động chuyển sang chế độ gợi ý góc chụp (Moodboard). |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|:---:|---|
| Actor + workflow rõ chưa? | **Yes** | Actor là seller online nhỏ lẻ trên TikTok Shop/Shopee; workflow gồm 7 bước rõ ràng từ nhập sản phẩm đến xuất bản. |
| Baseline + metric đo được chưa? | **Yes** | Baseline: mất 3–7 ngày, chuyển đổi <1%; Mục tiêu: dưới 2 giờ, chuyển đổi 2–3%, đo bằng đồng hồ và dashboard sàn. |
| Data/input đủ dùng chưa? | **Yes** | Input chỉ cần ảnh chụp sản phẩm thô bằng điện thoại và thông số cơ bản do chính chủ shop cung cấp. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Chấp nhận được vì mọi nội dung đều qua khâu Human Review ở Bước 4 và Bước 6 trước khi đăng lên sàn. |
| Có người review/owner không? | **Yes** | Chính chủ shop là người sở hữu sản phẩm và chịu trách nhiệm duyệt cuối cùng. |
| Có cách non-AI đơn giản hơn không? | **Yes (Đã loại)** | Cách non-AI là dùng template Canva/Shopee nhưng không giải quyết được tính cá nhân hóa và xu hướng thị trường. |

**Decision:**

```text
GO (Triển khai thử nghiệm Pilot)
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
1. Nhu cầu thị trường đã được kiểm chứng rõ ràng qua phỏng vấn và khảo sát thực tế: 80% người bán nhỏ lẻ gặp bế tắc và tốn 3–7 ngày cho khâu concept và visual.
2. Công nghệ GenAI hiện tại (các mô hình LLM tiên tiến và Image Generation/Inpainting) đã hoàn toàn đủ độ chín để tạo ra text chuẩn SEO và hình ảnh thương phẩm chất lượng cao.
3. Bài toán giải quyết trực tiếp giá trị kinh tế: Tiết kiệm hàng chục giờ làm việc, giảm 70% chi phí và nâng cao tỷ lệ chuyển đổi bán hàng thực tế.
4. Thiết kế Workflow có Human Boundary giúp triệt tiêu hoàn toàn rủi ro ảo giác và bảo vệ an toàn thương hiệu cho người bán.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Pilot nhỏ nhất: Thử nghiệm thực tế trên 3 sản phẩm mới của 1 shop thời trang/phụ kiện quen thuộc của thành viên nhóm.
- Cách chạy: Chạy tay từng bước trong quy trình (Dùng Claude/GPT để research trend và viết content; dùng Midjourney/Stable Diffusion để ghép sản phẩm vào bối cảnh thương phẩm; đưa cho chủ shop review và duyệt bài).
- Đo 3 số cụ thể:
  1. Thời gian từ lúc nhận ảnh sản phẩm thô đến khi ra bộ kit hoàn chỉnh (Mục tiêu: < 90 phút).
  2. Điểm đánh giá độ hài lòng của chủ shop về tính ứng dụng của bộ kit (Mục tiêu: ≥ 8/10 điểm).
  3. Tỷ lệ nhấp chuột (CTR) của bài đăng thử nghiệm trên sàn TMĐT (Mục tiêu: CTR ≥ 2.5%).
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã quyết định Go. Tuy nhiên nếu cần mở rộng thêm tính năng tự động đăng bài qua API sàn TMĐT, nhóm sẽ cần validate thêm chính sách cấp quyền Developer Partner của TikTok Shop và Shopee).
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng).
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng thử nghiệm và quay về quy trình chụp ảnh/thiết kế thủ công khi:
1. Sau 5 sản phẩm thử nghiệm, tỷ lệ hình ảnh AI tạo ra bị chủ shop từ chối chỉnh sửa vượt quá 40% (AI sinh ảnh không đạt chất lượng thương phẩm).
2. Tài khoản bán hàng nhận cảnh báo vi phạm chính sách nội dung từ sàn TMĐT liên quan đến thông tin sản phẩm do AI sinh ra.
3. Chi phí vận hành token API vượt quá 100.000đ cho một bộ kit sản phẩm, làm mất lợi thế cạnh tranh về chi phí cho shop nhỏ.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 18 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
