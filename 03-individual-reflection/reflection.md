# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Văn Tài
- Mã học viên: 2A202603004
- Nhóm: 6 thành viên — Nguyễn Đức Minh, Phan Đức Duy, Mai Phan Anh Tùng, Nguyễn Thọ Đạt, Đinh Trường An, Nguyễn Văn Tài
- Vai trò trong nhóm: Writer & Risk Lead (tổng hợp báo cáo, đánh giá rủi ro và fallback)
- Candidate problem nhóm chọn: Chủ shop online nhỏ trên TikTok Shop / Shopee khó tự xây chiến lược marketing khi đưa sản phẩm mới ra thị trường — giải pháp AI Marketing Kit (bài của Phan Đức Duy)

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 12 problems, mở rộng dần từ việc học sang đời sống rồi sang vận hành dịch vụ quy mô lớn. Tự chọn top 3 ở ba mức khác nhau: rà soát đánh giá ≤2 sao của tài xế (Workflow), hotline trạm sạc xe điện (Rule), tìm trẻ lạc ở khu vui chơi (No AI) | Góp 3/18 candidates (#16, #17, #18), là nhóm bài về dịch vụ quy mô lớn, khác với phần lớn candidates xoay quanh học tập và lập trình |
| Pitch Problem Card | Pitch 3 card. Với card tìm trẻ lạc, làm thêm file phân tích phương án GPS / cảnh báo rung / vòng RFID và bộ slide thuyết trình | Nhóm nhận xét: #16 hay nhưng dữ liệu nhạy cảm, sinh viên không truy cập được; #17 mã lỗi là tập cố định nên Rule / tra cứu là đủ; #18 thống nhất giải bằng vòng tay QR định danh (No AI) |
| Challenge bài của bạn khác | Hỏi các bài trong shortlist theo góc rủi ro: nếu AI sai thì hậu quả là gì, ai phát hiện đầu tiên. Với AI Marketing Kit, rủi ro nằm ở ảnh AI lệch với sản phẩm thật và nội dung dính từ khoá vi phạm chính sách sàn | Hai rủi ro này được đưa vào field "Rủi ro & người thật kiểm tra" của PS v1 và thành điều kiện exit |
| Gom trùng / cluster | Cùng nhóm gom 18 ý thành 4 cụm; bài trạm sạc vào cụm C (tác vụ kỹ thuật lặp lại), bài QC tài xế và tìm trẻ lạc vào cụm D (dịch vụ công, đời sống) | Cụm D được ghi rõ rào cản: dữ liệu độc quyền, trách nhiệm pháp lý lớn hoặc nên dùng No AI — khớp với kết luận ở card tìm trẻ lạc của tôi |
| Chọn candidate problem | Đồng ý loại cả 3 bài của mình khỏi shortlist; chấm điểm cùng nhóm cho 3 bài shortlist | Nhóm chọn AI Marketing Kit (34/35), hơn bài đồng bộ deadline (32/35) và tạo PR description (30/35) |
| Validation / research | Phỏng vấn và khảo sát do An phụ trách; tôi tổng hợp kết quả 3 interview, survey 10 người và khoảng 20 bài đăng trên group người bán TikTok Shop vào báo cáo | Kết quả validation giúp nhóm thu hẹp actor về chủ shop mới, seller cá nhân không có chuyên môn marketing |
| Workflow nhóm | Tùng thiết kế luồng hiện tại / tương lai; tôi viết phần fallback: concept không hợp thì yêu cầu AI đề xuất lại, ảnh không đạt thì dùng làm moodboard để tự chụp, mọi nội dung phải qua người duyệt | Future workflow có 2 human boundary rõ ở bước chọn concept và bước duyệt ảnh / content |
| Problem Statement | Tổng hợp PS v0 → v1; viết field rủi ro và boundary: AI không tự nạp tiền quảng cáo, không dựng video phức tạp, không tự đăng bài khi chưa được duyệt | PS v1 đủ 9 field, boundary có cả phần làm và không làm |
| Rule / Workflow / Agent | Góp lập luận không chọn Agent: agent tự chạy ads có thể tiêu tiền vô tội vạ hoặc tạo nội dung vi phạm dẫn tới khoá gian hàng | Nhóm chọn Workflow có người duyệt (human-in-the-loop) |
| Decision | Viết điều kiện exit / rollback: sau 5 sản phẩm mà hơn 40% ảnh AI bị chủ shop từ chối; tài khoản bị sàn cảnh báo vi phạm; chi phí token vượt 100.000đ / bộ kit | Decision Go có 3 điều kiện dừng đo được bằng số |

**Dấu tay rõ nhất của tôi trong artifact cuối:**

```text
Phần Exit / rollback và field "Rủi ro & người thật kiểm tra" trong PS v1. Ba điều kiện
dừng đều đo được bằng số, nên nhóm biết khi nào phải quay về cách làm thủ công thay vì
cứ tiếp tục vì đã lỡ chọn AI.
```

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ Claude soạn nháp bảng scan, sau đó yêu cầu mở rộng ra ngoài việc học. Tôi tự đưa thêm các bài vận hành quy mô lớn (khách sạn, gọi xe, trạm sạc, bệnh viện, khu vui chơi) kèm số ước tính và nhờ AI viết lại thành vấn đề chung, không gắn tên công ty | Viết lại nhanh, giữ đủ actor, workflow, số liệu | Bản đầu chỉ quanh việc học, quá hẹp; số liệu đều là ước tính chưa có nguồn | Yêu cầu mở rộng phạm vi; đánh dấu `~` cho mọi số ước tính |
| Problem Card | Nhờ AI viết đủ field cho 3 card, vẽ workflow trước / sau và đóng vai skeptical PM phản biện | Chỉ ra metric chỉ đo tốc độ có thể khiến nhân viên QC xem lướt hơn; nhân viên dễ tin tóm tắt của AI mà không mở bằng chứng gốc | AI đề xuất top 3 nghiêng về bài "hợp AI" (xử lý yêu cầu đặc biệt của khách sạn) | Tự chọn lại top 3 theo ba mức Workflow / Rule / No AI; thêm metric tỷ lệ quyết định bị lật khi phúc tra |
| Workflow | Với card tìm trẻ lạc, tôi đưa ra ý tưởng thêm GPS và cơ chế rung báo đi lạc, nhờ AI phản biện, viết file phân tích và làm slide | AI chỉ ra rung nên đặt ở điện thoại phụ huynh chứ không phải vòng của trẻ, rủi ro báo động giả, và gợi ý thêm phương án kiểm cặp vòng ở cổng ra | Đưa ra ngưỡng cảnh báo (~30 m, ~60 giây) và các mục tiêu pilot chưa có cơ sở | Giữ các ngưỡng ở dạng giả định cần thử với vài gia đình, không đưa vào metric chính |
| Research | (tự xác nhận: có dùng AI trong phần research nhóm không) | | | |
| Problem Statement | Nhóm nhờ AI phản biện PS v0 | Chỉ ra Success Metric ban đầu chỉ ghi "tăng doanh số, làm nhanh hơn", thiếu baseline; Boundary chưa rõ cách xử lý ảnh sản phẩm thật | AI chỉ đặt câu hỏi, không biết số liệu thật của các shop | Bổ sung baseline 3–7 ngày → dưới 2 giờ, chuyển đổi <1% → 2–3%; boundary ghi rõ AI không đụng tới tiền quảng cáo |
| Rule / Workflow / Agent | (tự xác nhận) | | | |
| Decision | (tự xác nhận) | | | |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Cả 3 bài tôi mang vào nhóm đều không vào được shortlist, và lý do của từng bài dạy tôi
một điều khác nhau. Bài rà soát đánh giá tài xế là bài tôi thích nhất, nhưng nhóm chỉ ra
đúng chỗ yếu: dữ liệu ghi âm, GPS là của doanh nghiệp, sinh viên không có cách nào chạm
vào để validate. Tôi nhận ra một bài hay trên giấy chưa chắc làm được trong lab nếu không
kiểm chứng được. Bài trạm sạc và bài tìm trẻ lạc thì chính tôi cũng đã kết luận là Rule
và No AI, nên việc nhóm không chọn là hợp lý. Làm sâu bài tìm trẻ lạc giúp tôi hiểu thêm
GPS hay cảnh báo rung vẫn chỉ là cảm biến cộng ngưỡng, không biến bài toán thành bài toán
AI. Nghe 18 candidates của cả nhóm, tôi thấy nhiều bài xoay quanh học tập và lập trình,
còn bài AI Marketing Kit của Duy có pain thật và người sẵn sàng trả tiền, nên tôi đồng ý
chọn. Với vai trò Risk Lead, phần khó nhất là metric: tỷ lệ chuyển đổi từ dưới 1% lên
2–3% phụ thuộc cả giá, ads, mùa vụ, rất khó chứng minh là nhờ bộ kit, nên pilot phải đo
thêm thời gian làm và CTR. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở hai điểm. Một là
bước "AI research xu hướng trong 5 phút": chính bảng research của nhóm ghi ChatGPT / Claude
không kết nối dữ liệu sàn TMĐT Việt Nam, vậy dữ liệu xu hướng lấy từ đâu. Hai là cách viết
"triệt tiêu hoàn toàn rủi ro ảo giác" — người duyệt chỉ giảm rủi ro chứ không xoá được,
nên báo cáo nên viết đúng mức hơn.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
