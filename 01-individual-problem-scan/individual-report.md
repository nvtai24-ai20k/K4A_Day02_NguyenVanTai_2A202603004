# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

> ⚠️ **Bản nháp:** các số có dấu `~` là ước tính, cần kiểm lại với người trong cuộc / nguồn thật trước khi nộp.

## Thông tin cá nhân

- Họ và tên: Nguyễn Văn Tài
- Mã học viên: 2A202603004
- Vai trò / bối cảnh: Học viên chương trình AI20K (K4A)
- Công việc hằng tuần / nơi quan sát problem:
  - Dùng các dịch vụ quy mô lớn: đặt phòng khách sạn qua OTA, gọi xe công nghệ, sạc xe điện, khám bệnh, khu vui chơi
  - Mua sắm online, nhắn tin hỏi hàng với shop trên Facebook / Zalo
  - Hỗ trợ gia đình từ xa: nhắc lịch khám, thuốc, giấy tờ, thông báo trường của em
  - Làm thủ tục hành chính
  - Quan sát công việc của người quen: chủ shop, kế toán, HR, nhân viên tổng đài

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

| # | Lăng kính | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Resort / khách sạn lớn nhận booking từ nhiều OTA (Booking.com, Agoda, Trip.com…): nhân viên Reservation đọc, dịch và phân loại thủ công ghi chú "yêu cầu đặc biệt" viết tự do bằng nhiều ngôn ngữ (dị ứng, nôi em bé, đón sân bay, trang trí kỷ niệm…), rồi chuyển cho từng bộ phận | Nhân viên Reservation; bếp, Housekeeping, Concierge; khách lưu trú | ~130 yêu cầu/ngày/resort × ~10' ≈ ~22 giờ công/ngày; ~4% yêu cầu bị bỏ sót |
| 2 | Lặp lại | Tổng đài hỗ trợ tài xế của nền tảng gọi xe trả lời đi trả lời lại câu hỏi về chính sách thu nhập, thưởng theo tuần, phí phạt; chính sách thay đổi thường xuyên nên tổng đài viên phải tra văn bản | Tổng đài viên; tài xế chờ máy | ~2.000 cuộc/ngày × ~5' ≈ ~167 giờ công/ngày; ~60% là câu hỏi lặp lại |
| 3 | Pain từ người khác | Đội chất lượng dịch vụ của nền tảng gọi xe xem xét thủ công các đánh giá ≤2 sao (đọc bình luận, nghe ghi âm, xem GPS) để quyết định xử lý tài xế; tồn đọng lâu, tài xế phàn nàn bị xử lý oan | Nhân viên chất lượng dịch vụ; tài xế; khách khiếu nại | ~600 ca/ngày × ~12' ≈ ~120 giờ công/ngày (~150 giờ nếu tính phúc tra); tồn đọng 5-7 ngày |
| 4 | AI có thể tốt hơn | Hotline hỗ trợ trạm sạc xe điện công cộng: khách báo "trụ không nhận sạc", tổng đài viên hỏi theo kịch bản cứng, tra mã lỗi thủ công rồi mới hướng dẫn hoặc điều kỹ thuật | Tổng đài viên; khách đứng chờ tại trụ; kỹ thuật viên hiện trường | ~800 cuộc/ngày × ~8' ≈ ~107 giờ công/ngày; khoảng một nửa là lỗi khách tự khắc phục được |
| 5 | Tốn thời gian | Bệnh viện nhận bệnh nhân quốc tế: điều phối viên dịch và tóm tắt hồ sơ bệnh sử gửi từ nước ngoài (Anh / Hàn / Nhật) trước khi bác sĩ tiếp nhận | Điều phối viên khách quốc tế; bác sĩ; bệnh nhân chờ | ~40 hồ sơ/ngày × ~45' ≈ ~30 giờ công/ngày; bác sĩ nhận hồ sơ trễ 1-2 ngày |
| 6 | Pain từ người khác | Khu vui chơi / công viên giải trí đông khách: tìm trẻ lạc bằng cách phụ huynh mô tả tại quầy thông tin, nhân viên truyền bộ đàm từng khu | Phụ huynh; trẻ; nhân viên an ninh | ~15 ca/ngày cao điểm × ~25' tìm. Ghi nhận nhưng **không phù hợp LLM** → nên giải bằng quy trình + vòng tay QR cho trẻ (No AI) |
| 7 | Pain từ người khác + Tốn thời gian | Chủ shop online nhỏ (Facebook / Zalo / sàn TMĐT) trả lời tay câu hỏi lặp lại về giá, size, phí ship, còn hàng, rồi chép đơn vào Excel | Chủ shop 1-2 người; khách chờ phản hồi | ~50-100 tin nhắn/ngày, ~60-70% là câu hỏi lặp; lúc cao điểm khách chờ ~30'; ~1-2 đơn sai/sót mỗi tuần |
| 8 | Tốn thời gian | Kế toán doanh nghiệp nhỏ nhập tay hoá đơn điện tử (PDF / XML nhận qua email) vào phần mềm / Excel để đối chiếu | Kế toán; chủ doanh nghiệp chờ báo cáo | ~100-300 hoá đơn/tháng × ~1-2', dồn vào cuối tháng; nhập sai số tiền / mã số thuế phải sửa lại |
| 9 | Tốn thời gian + AI có thể tốt hơn | HR doanh nghiệp tuyển số lượng lớn lọc tay hàng trăm CV cho một vị trí | HR; ứng viên chờ phản hồi | ~100-300 CV/vị trí × ~2-3'/CV; ứng viên đợi ~1-2 tuần mới có phản hồi |
| 10 | Tốn thời gian + Pain từ người khác | Người dân làm thủ tục hành chính (tạm trú, sang tên xe, cấp lại giấy tờ) không rõ cần giấy tờ gì, bị trả hồ sơ, phải đi lại nhiều lần | Người đi làm phải xin nghỉ; cán bộ bộ phận một cửa | ~2-3 lần đi lại/thủ tục × ~2-3 tiếng/lần → ~1-2 ngày công |
| 11 | Lặp lại | Con cái đi làm xa theo dõi lịch uống thuốc, tái khám cho bố mẹ lớn tuổi dùng nhiều loại thuốc theo đơn giấy | Bố mẹ 60+; con cái phải gọi nhắc | ~3-5 loại thuốc, 2-3 cữ/ngày; gọi nhắc ~1 lần/ngày; ~1-2 lần/tuần quên hoặc nhầm cữ |
| 12 | Pain từ người khác + AI có thể tốt hơn | Phụ huynh theo dõi thông báo của trường qua nhiều nhóm Zalo lớp, sót lịch họp, khoản nộp tiền, đồ cần mang | Phụ huynh đi làm; giáo viên chủ nhiệm phải nhắc lại | ~3-5 nhóm Zalo/con, ~50-200 tin/ngày lẫn tin xã giao; một thông báo phải nhắc lại ~2-3 lần |

**AI đã dùng ở Phase 1:**
- Prompt đã hỏi: Bản scan đầu chỉ quanh việc học AI20K nên quá hẹp; nhờ Claude mở rộng sang đời sống, kinh doanh nhỏ, dịch vụ công. Sau đó tôi tự bổ sung các problem vận hành dịch vụ quy mô lớn (khách sạn, gọi xe, trạm sạc, bệnh viện, khu vui chơi) và nhờ Claude viết lại thành vấn đề chung, không gắn với tên công ty cụ thể.
- Ý dùng được: #1-#6 có volume lớn, tính được giờ công/ngày; #7, #10, #11 có actor gần gũi, dễ phỏng vấn. Top 3 do tôi tự chọn: #3, #4, #6.
- Ý bỏ vì không phải pain thật / quá rộng: "App AI quản lý toàn bộ sức khoẻ gia đình" (quá rộng), "AI dự báo kẹt xe, ngập nước" (cần dữ liệu hạ tầng); các bài chỉ quanh việc học (Discord, rubric) bị thay bằng bài có tác động rộng hơn.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể *(còn phải kiểm các số `~` với nguồn thật)*
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Ba card được chọn có chủ đích nằm ở ba mức khác nhau — Workflow / Rule / No AI — để thấy không phải bài nào có volume lớn cũng cần AI.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #3 Xem xét đánh giá ≤2 sao để xử lý tài xế | Volume lớn (~120-150 giờ công/ngày); tồn đọng 5-7 ngày gây hại cả hai phía: tài xế vi phạm vẫn chạy tiếp, tài xế không có lỗi bị xử lý oan; bottleneck rõ ở bước xem bằng chứng; buộc phải bàn kỹ boundary vì quyết định ảnh hưởng thu nhập người thật | Số liệu là ước tính; quyền dùng ghi âm cuộc xe cho AI; nhân viên có tin tóm tắt của AI quá mức không; tỷ lệ quyết định bị lật khi phúc tra chưa có số |
| 2 | #4 Hotline trạm sạc xe điện | ~107 giờ công/ngày, khoảng một nửa là lỗi khách tự xử lý được; mã lỗi là tập cố định, đúng/sai rõ → ví dụ cho thấy Rule có thể đủ dù ban đầu xếp vào lăng kính "AI có thể tốt hơn" | Trụ sạc có gửi mã lỗi / trạng thái về hệ thống không; khách đang sốt ruột có chịu tự thao tác theo hướng dẫn không |
| 3 | #6 Tìm trẻ lạc ở khu vui chơi | Rủi ro an toàn trẻ em cao, workflow vẽ được rõ; ví dụ rõ nhất cho kết luận No AI: bottleneck nằm ở định danh trẻ và truyền tin đồng thời, không nằm ở việc hiểu ngôn ngữ | ~15 ca/ngày, ~25'/ca là ước tính; phụ huynh có chịu cho trẻ đeo vòng không; số điện thoại trên vòng tay cũng là dữ liệu cá nhân |

### 2.2. Problem Cards chi tiết

---

#### Problem Card #1 — Xem xét đánh giá thấp để xử lý tài xế

```text
Problem 1 câu:
Ở nền tảng gọi xe lớn, đội chất lượng dịch vụ xem xét thủ công từng đánh giá ≤2 sao
(đọc bình luận, nghe ghi âm, xem GPS) để quyết định có xử lý tài xế hay không; ~12'/ca
nên tồn đọng 5-7 ngày, và tài xế phàn nàn bị xử lý oan.

Actor:
Nhân viên đội chất lượng dịch vụ. Người chịu ảnh hưởng phụ: tài xế (bị trừ điểm, tạm
khoá, ảnh hưởng thu nhập) và khách khiếu nại (chờ phản hồi).

Thời điểm / bối cảnh:
Hằng ngày, ~600 ca/ngày; dồn nhiều sau cuối tuần và dịp lễ.

Current workflow 3-7 bước:
1. Hệ thống đẩy đánh giá ≤2 sao vào hàng đợi — tự động
2. Đọc bình luận của khách, xác định loại vấn đề (thái độ, đi sai đường, xe bẩn,
   an toàn…) — ~2'
3. Nghe ghi âm (nếu có), xem GPS lộ trình, lịch sử tài xế — ~7'
4. Đối chiếu quy chế, ra quyết định (nhắc nhở / trừ điểm / tạm khoá / không xử lý) — ~2'
5. Ghi hồ sơ, thông báo tài xế — ~1'
6. Tài xế khiếu nại → phúc tra lại từ đầu — thêm ~30 giờ công/ngày

Bottleneck:
Bước 3. Mọi ca đều phải xem thủ công toàn bộ bằng chứng, kể cả ca rõ ràng không phải lỗi
tài xế (khách chấm 1 sao vì giá cao, vì kẹt xe). Quá tải nên xem lướt → quyết định sai
→ phát sinh phúc tra.

Impact:
~600 × ~12' ≈ ~120 giờ công/ngày (~150 giờ tính cả phúc tra). Tồn đọng 5-7 ngày: tài xế
vi phạm nghiêm trọng vẫn tiếp tục chạy, tài xế không có lỗi bị ảnh hưởng thu nhập, khách
không nhận được phản hồi.

Success metric:
- Thời gian tồn đọng: 5-7 ngày → ≤48 giờ.
- Thời gian xử lý trung bình / ca: ~12' → ~6'.
- Tỷ lệ quyết định bị lật khi phúc tra: không tăng, mục tiêu giảm (baseline: đếm trong
  1 tháng) — metric chất lượng đi kèm để tránh "nhanh hơn nhưng oan hơn".
- 100% ca liên quan tới an toàn được người xem trong 24 giờ.

Non-AI alternative:
- Khách chọn lý do từ danh mục khi đánh giá → Rule chuyển ca không thuộc lỗi tài xế
  (giá, app lỗi, kẹt xe) xuống hàng đợi ưu tiên thấp.
- Hàng đợi ưu tiên theo mức độ: an toàn trước, thái độ sau.
- Quy tắc chỉ xem xét xử lý khi tài xế có ≥N đánh giá thấp trong 30 ngày, trừ ca an toàn.

AI hypothesis:
AI tóm tắt bằng chứng cho mỗi ca: phân loại bình luận, đánh dấu đoạn ghi âm có lời lẽ bất
thường kèm mốc thời gian, đánh dấu GPS lệch tuyến, đề xuất mức ưu tiên. Quyết định xử lý
tài xế luôn do người; AI không đề xuất mức phạt.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1:**

```text
CURRENT STATE — ~12'/ca (~120-150 giờ công/ngày), tồn đọng 5-7 ngày

[1 Đánh giá ≤2 sao vào hàng đợi: tự động]
→ [2 Đọc bình luận, phân loại: 2']
→ [3 Nghe ghi âm, xem GPS, lịch sử tài xế: 7']   <-- bottleneck
→ [4 Đối chiếu quy chế, quyết định: 2']
→ [5 Ghi hồ sơ, báo tài xế: 1']
→ [6 Phúc tra khi tài xế khiếu nại: làm lại từ đầu]

FUTURE STATE — ~6'/ca

[1 Hàng đợi: ưu tiên ca an toàn, ca không thuộc lỗi tài xế xuống ưu tiên thấp: tức thì]  -- Rule
→ [2 AI tóm tắt bằng chứng: bình luận, đoạn ghi âm đáng chú ý + mốc thời gian,
     GPS lệch tuyến: tức thì]                                                         -- Workflow step
→ [3 Nhân viên đọc tóm tắt + bắt buộc mở đoạn bằng chứng gốc được đánh dấu: 4']        <-- human boundary
→ [4 Nhân viên quyết định theo quy chế: 1']                                           <-- human boundary
→ [5 Ghi hồ sơ kèm bằng chứng gốc, báo tài xế: 1']

Fallback:
- Tóm tắt của AI thiếu / sai → nhân viên xem toàn bộ bằng chứng gốc như cũ.
- Ca liên quan an toàn (quấy rối, đe doạ, tai nạn) → nhân viên nghe toàn bộ ghi âm,
  không dựa vào tóm tắt.
- Mọi quyết định tạm khoá tài khoản phải có người thứ hai duyệt.
- Phúc tra luôn do người khác với người ra quyết định ban đầu, không dùng lại tóm tắt AI.
```

---

#### Problem Card #2 — Hotline trạm sạc xe điện công cộng

```text
Problem 1 câu:
Hotline hỗ trợ trạm sạc công cộng nhận ~800 cuộc/ngày báo "trụ không nhận sạc"; tổng đài
viên hỏi theo kịch bản cứng và tra mã lỗi thủ công ~8'/cuộc, trong khi khoảng một nửa là
lỗi khách tự khắc phục được (cắm chưa chặt, chưa kích hoạt phiên sạc trên app, chọn sai
cổng).

Actor:
Tổng đài viên hotline trạm sạc. Người chịu ảnh hưởng phụ: khách đang đứng chờ tại trụ,
kỹ thuật viên hiện trường bị điều đi không cần thiết.

Thời điểm / bối cảnh:
Mọi giờ trong ngày, nhiều nhất giờ cao điểm và dịp lễ. Khách đang ở trụ, sốt ruột, có
thể sắp hết pin.

Current workflow 3-7 bước:
1. Khách gọi hotline, chờ kết nối — ~2'
2. Tổng đài viên hỏi theo kịch bản: vị trí trạm, mã trụ, dòng xe, hiện tượng — ~2'
3. Nhờ khách đọc mã lỗi trên màn hình trụ, tra tài liệu mã lỗi — ~2'
4. Hướng dẫn khách thao tác lại, hoặc tạo phiếu điều kỹ thuật — ~2'
5. Kỹ thuật viên tới xử lý (nếu cần) — ~30-60'

Bottleneck:
Bước 2-3. Thông tin trụ và mã lỗi (nếu trụ có kết nối giám sát) đã nằm trong hệ thống,
nhưng tổng đài viên vẫn phải hỏi khách và tra tay. Cùng một nhóm lỗi đơn giản lặp đi
lặp lại hàng trăm lần mỗi ngày.

Impact:
~800 × ~8' ≈ ~107 giờ công/ngày. Khoảng một nửa là lỗi khách tự xử lý được. Khách mất
~8-10' đứng chờ tại trụ; một phần phiếu điều kỹ thuật tới nơi không có lỗi phần cứng.

Success metric:
- Tỷ lệ khách tự xử lý lỗi đơn giản không cần gọi: ~0% → ≥40%.
- Thời gian xử lý các cuộc gọi còn lại: ~8' → ~4'.
- Số phiếu điều kỹ thuật tới nơi không có lỗi phần cứng: giảm (baseline: đếm phiếu
  1 tháng).

Non-AI alternative:
- Mã QR dán trên trụ → mở hướng dẫn xử lý theo từng mã lỗi (cây quyết định).
- Màn hình tổng đài tự hiện mã trụ, trạng thái, mã lỗi gần nhất theo số điện thoại
  hoặc phiên sạc của khách.
- Kịch bản tổng đài sắp xếp lại theo mã lỗi thay vì hỏi tuần tự.

AI hypothesis:
Chatbot / voicebot hỏi triệu chứng bằng ngôn ngữ tự nhiên. Nhưng mã lỗi là tập cố định,
đúng/sai rõ → Rule nhiều khả năng đủ cho phần lớn case; AI chỉ đáng thử cho mô tả mơ hồ
không có mã lỗi.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~8'/cuộc (~107 giờ công/ngày)

[1 Gọi, chờ kết nối: 2']
→ [2 Hỏi kịch bản: vị trí, mã trụ, hiện tượng: 2']
→ [3 Hỏi mã lỗi, tra tài liệu: 2']        <-- bottleneck
→ [4 Hướng dẫn / tạo phiếu kỹ thuật: 2']
→ [5 Kỹ thuật viên tới xử lý: 30-60']

FUTURE STATE — ~2' nếu khách tự xử lý, ~4' nếu vẫn phải gọi

[1 Khách quét QR trên trụ → lấy mã trụ + mã lỗi: tức thì]         -- Rule
→ [2 Hiện hướng dẫn theo cây quyết định mã lỗi: ~2']              -- Rule
→ [3 Chưa được → gọi hotline; màn hình tổng đài hiện sẵn mã trụ,
     mã lỗi, các bước khách đã thử: ~4']
→ [4 Tổng đài viên quyết định hướng dẫn thêm hay điều kỹ thuật]    <-- human boundary

Fallback:
- Trụ mất kết nối / không có mã lỗi → quay về kịch bản hỏi đáp như cũ.
- Dấu hiệu nguy hiểm về điện (chập, mùi khét, nóng bất thường) → hướng dẫn dừng sạc và
  điều kỹ thuật ngay, không đi qua cây tự xử lý.
```

---

#### Problem Card #3 — Tìm trẻ lạc ở khu vui chơi đông khách

```text
Problem 1 câu:
Ở khu vui chơi / công viên giải trí đông khách, khi trẻ bị lạc, phụ huynh phải tìm tới
quầy thông tin mô tả trẻ bằng lời, nhân viên truyền bộ đàm lần lượt từng khu; mỗi ca mất
~25' mới tìm được, trong lúc đó trẻ có thể đi tới khu nguy hiểm (hồ nước, cổng ra).

Actor:
Nhân viên quầy thông tin và nhân viên an ninh của khu vui chơi. Người chịu ảnh hưởng
phụ: phụ huynh và trẻ.

Thời điểm / bối cảnh:
Cuối tuần, dịp lễ, mùa hè; ~15 ca/ngày vào ngày cao điểm.

Current workflow 3-7 bước:
1. Phụ huynh phát hiện mất con, tự tìm quanh khu vực — ~5-10'
2. Hỏi đường, tìm tới quầy thông tin — ~3-5'
3. Mô tả trẻ (tuổi, quần áo, đặc điểm), nhân viên ghi tay — ~3'
4. Truyền mô tả qua bộ đàm lần lượt từng khu, nhân viên các khu tìm theo mô tả — ~15'
5. Tìm thấy → đưa trẻ về quầy, xác minh đúng phụ huynh — ~5'

Bottleneck:
Bước 4, và nó có hai chiều:
- Chiều phụ huynh → trẻ: mô tả bằng lời qua bộ đàm dễ sai lệch ("áo đỏ, khoảng 5 tuổi"
  khớp với rất nhiều trẻ) và truyền tuần tự từng khu thay vì đồng thời.
- Chiều trẻ → phụ huynh: nhân viên thấy trẻ đi một mình nhưng trẻ nhỏ không nhớ số điện
  thoại bố mẹ, nên không liên lạc được ngay.
Cả hai đều là vấn đề định danh + truyền tin, không phải vấn đề hiểu ngôn ngữ.

Impact:
~15 ca × ~25' ≈ ~6 giờ công/ngày, thực tế nhiều hơn vì nhiều nhân viên cùng tìm một ca.
Giờ công không phải tác động chính: rủi ro an toàn của trẻ trong ~25' đó, phụ huynh hoảng
loạn, và uy tín của khu vui chơi nếu có sự cố.

Success metric:
- Thời gian từ lúc báo lạc tới lúc đoàn tụ: ~25' → dưới 10'.
- Tỷ lệ trẻ dưới ~10 tuổi đeo vòng định danh khi qua cổng: → ≥90%.
- 0 ca trẻ ra khỏi cổng mà không đi cùng người lớn đã đăng ký.
Cách đo: ghi nhận thời gian báo / đoàn tụ trong sổ an ninh, đếm vòng phát tại cổng.

Non-AI alternative (đây chính là phương án chọn):
- Vòng tay QR / in số điện thoại phụ huynh phát tại cổng cho trẻ nhỏ → ai thấy trẻ đi
  một mình quét là gọi được phụ huynh.
- Phụ huynh chụp ảnh trẻ tại cổng (quần áo hôm đó) để đưa cho nhân viên thay vì mô tả
  bằng lời.
- Quy trình mã khẩn tìm trẻ lạc: báo bất kỳ nhân viên nào (không cần tới quầy) → gửi ảnh
  + mô tả đồng thời tới mọi khu qua nhóm liên lạc nội bộ → cổng ra kiểm soát ngay.
- Điểm hẹn "trẻ lạc" cố định ở mỗi khu, có biển hiệu rõ.

AI hypothesis (và vì sao không chọn):
Camera AI nhận diện khuôn mặt / quần áo để tìm trẻ trong đám đông. Không chọn vì: cần hạ
tầng camera phủ khắp khu; xử lý dữ liệu sinh trắc học của trẻ em rất nhạy cảm về pháp lý;
nhận diện sai trong đám đông gây báo động giả. LLM cũng không giải được bottleneck vì vấn
đề nằm ở định danh và truyền tin đồng thời.

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~25' từ lúc báo quầy (chưa tính ~10' phụ huynh tự tìm)

[1 Phụ huynh tự tìm quanh khu: 5-10']
→ [2 Tìm tới quầy thông tin: 3-5']
→ [3 Mô tả trẻ, nhân viên ghi tay: 3']
→ [4 Truyền bộ đàm lần lượt từng khu, tìm theo mô tả: 15']   <-- bottleneck
→ [5 Đưa trẻ về quầy, xác minh phụ huynh: 5']

FUTURE STATE — dưới 10'

Nhánh A — có người thấy trẻ đi một mình:
[1 Quét vòng tay QR trên tay trẻ: tức thì]                      -- process fix
→ [2 Gọi thẳng số điện thoại phụ huynh: 1']
→ [3 Giữ trẻ tại điểm hẹn gần nhất, xác minh phụ huynh
     bằng vòng tay đôi / ảnh chụp tại cổng: 5']                 <-- human boundary

Nhánh B — phụ huynh báo mất con:
[1 Báo nhân viên gần nhất, không cần tới quầy: 1']
→ [2 Kích hoạt mã khẩn: gửi ảnh chụp tại cổng + mô tả đồng thời
     tới mọi khu, cổng ra kiểm soát: 1']                        -- process fix
→ [3 Các khu tìm song song: ~5']
→ [4 Xác minh phụ huynh bằng vòng tay đôi / ảnh: 2']            <-- human boundary

Fallback:
- Trẻ không đeo vòng / làm mất vòng → chạy nhánh B.
- Quá 15' chưa tìm thấy → xem camera cổng ra và báo cơ quan chức năng theo quy trình
  an ninh.
```

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Xem xét đánh giá thấp để xử lý tài xế
```

**Vì sao:**

```text
Đội chất lượng dịch vụ mất ~120-150 giờ công/ngày cho ~600 đánh giá ≤2 sao, bottleneck
nằm gọn ở bước nghe ghi âm + xem GPS (~7'/ca), và tồn đọng 5-7 ngày gây hại cả hai phía:
tài xế vi phạm vẫn chạy, tài xế không có lỗi bị xử lý oan. Bài tách được ba lớp rõ: Rule
sắp ưu tiên hàng đợi, AI tóm tắt bằng chứng, con người ra quyết định — nên so sánh Rule
/ Workflow / Agent được ngay, và buộc phải bàn boundary vì quyết định chạm tới thu nhập
của người thật.
```

**Câu hỏi tôi muốn nhóm challenge:**

```text
1. Nếu Rule đã chuyển các ca "không phải lỗi tài xế" xuống ưu tiên thấp, hàng đợi thật sự
   còn bao nhiêu ca — phần còn lại có đủ lớn để đáng dùng AI không?
2. Nếu tóm tắt của AI bỏ sót một câu đe doạ trong ghi âm thì sao? Bắt nhân viên nghe
   toàn bộ ghi âm với ca an toàn thì còn tiết kiệm được bao nhiêu thời gian?
```

**AI phản biện Card #1 (vai skeptical PM):**
- Điểm yếu AI chỉ ra:
  - ~600 ca/ngày, ~12'/ca, tồn đọng 5-7 ngày đều là ước tính, chưa kiểm với người làm thật.
  - Metric chỉ đo tốc độ có thể khuyến khích xem lướt hơn → cần metric chất lượng đi kèm.
  - Nhân viên dễ tin tóm tắt của AI mà không mở bằng chứng gốc → số ca xử lý oan có thể tăng thay vì giảm.
  - Ghi âm cuộc xe là dữ liệu cá nhân nhạy cảm → dùng AI xử lý cần chính sách rõ, có thể nằm ngoài tầm quyết định của đội vận hành.
- Tôi sửa gì:
  - Thêm "tỷ lệ quyết định bị lật khi phúc tra" làm metric chất lượng song song với thời gian tồn đọng.
  - Bắt buộc nhân viên mở đoạn bằng chứng gốc trước khi quyết định; ca an toàn nghe toàn bộ ghi âm.
  - Tạm khoá tài khoản cần người thứ hai duyệt; phúc tra không dùng lại tóm tắt AI.
  - Ghi vào "Điều còn chưa chắc": quyền dùng ghi âm cho AI.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
