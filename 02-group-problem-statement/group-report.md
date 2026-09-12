# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Hoàng Quốc Dũng | 2A202602523 | Facilitator & Workflow Lead (Chủ bài toán, điều phối luồng quy trình) |
| 2   | Lưu Nguyễn Tiến Anh | 2A202603002 | Research & Synthesis (Nghiên cứu giải pháp hiện có, tổng hợp tài liệu) |
| 3   | Đặng Quang Huy | 2A202602962 | Domain & Data Specialist (Phân tích dữ liệu xe buýt, GPS realtime, API giao thông) |
| 4   | Vũ Minh Điềm | 2A202602858 | Validation & Skeptic (Kiểm chứng người dùng, đặt câu hỏi phản biện, rà soát rủi ro) |
| 5   | Bùi Lê Thái Sơn | 2A202602880 | Metrics & Writer (Xây dựng bộ chỉ số đo lường, hoàn thiện Problem Statement) |

**Candidate problem nhóm chọn (1 câu):**

Sinh viên di chuyển từ VinUni (Gia Lâm) về Xuân Thủy (Cầu Giấy) gặp khó khăn trong việc lựa chọn và điều chỉnh cặp tuyến xe buýt tối ưu theo thời gian thực do vị trí xe buýt, thời gian chờ tại điểm chuyển tuyến và tình trạng ùn tắc giao thông liên tục biến động, dẫn đến thời gian chờ đợi bị kéo dài lãng phí từ 25–40 phút mỗi chuyến.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Lưu Nguyễn Tiến Anh | Sau mỗi ca dạy, giáo viên mất từ 40-50 phút để gõ nhận xét tay cho từng học sinh vào hệ thống, nội dung lặp lại nhiều nhưng vẫn phải chỉnh từng câu để tránh trùng lặp. | Giáo viên đứng lớp dạy kỹ năng / lập trình | Nghĩ câu từ diễn đạt cá nhân hóa cho từng bạn mất khoảng 5 phút/học sinh, dễ bị bí từ và tốn thời gian. | Pain rất thật của giáo viên, text-generation là thế mạnh AI nhưng khó đo lường độ hài lòng phụ huynh. |
| 2 | Lưu Nguyễn Tiến Anh | Trong giờ thực hành, học sinh khá giỏi thường hoàn thành lắp ráp và lập trình sớm trước 20-30 phút rồi ngồi chơi buộc giáo viên phải tự nghĩ bài tập mở rộng tại chỗ mà không có công cụ hỗ trợ. | Giáo viên thực hành STEM/lập trình | Nghĩ đề bài mở rộng tại chỗ vừa sức, phù hợp linh kiện kit sẵn có và hấp dẫn học sinh mà không làm gián đoạn việc kèm cặp các bạn yếu. | Hay nhưng phụ thuộc nhiều vào bối cảnh lớp học trực tiếp, khó chuẩn hóa bộ kit linh kiện vào lab này. |
| 3 | Lưu Nguyễn Tiến Anh | Leader chậm ra quyết định phê duyệt. | Thành viên dự án / nhân viên | Thời gian chờ phê duyệt kéo dài từ 2-4 ngày do tin nhắn trôi, thiếu quy trình rõ ràng và thiếu mức độ ưu tiên (SLA). | Thuộc về vấn đề văn hóa tổ chức và quy trình quản lý, giải pháp quy trình (rule/SLA) giải quyết tốt hơn AI. |
| 4 | Vũ Minh Điềm | Cảnh báo rủi ro lừa đảo qua tin nhắn, cuộc gọi và đường link lạ. | Người thân trong gia đình, người lớn tuổi | Không có công cụ/đối chiếu real-time để xác định mức độ nguy hiểm, nên người dùng phải dựa vào kinh nghiệm hoặc cảm giác. | Vấn đề xã hội lớn, nhưng phạm vi dữ liệu quá rộng, rủi ro false positive/negative có thể gây hậu quả nghiêm trọng. |
| 5 | Vũ Minh Điềm | Làm đề thi và bài tập phân hóa cho học sinh cấp 3. | Giáo viên nói chung | Tìm nguồn, lọc thông tin, và biến đổi thành đề mới thực sự tốn thời gian và cần nhiều công sức thủ công. | Phổ biến, thị trường đã có nhiều giải pháp EdTech, khó tạo điểm khác biệt trong phạm vi bài lab. |
| 6 | Vũ Minh Điềm | Quên mang đầy đủ đồ dùng cá nhân và tài liệu khi ra ngoài. | Cá nhân sinh viên / người đi làm | Trí nhớ và lịch trình khả năng quên rất cao, đặc biệt khi có nhiều đồ đạc cần mang theo cùng lúc. | Bài toán đơn giản, một checklist cố định hoặc app nhắc việc (Rule) đã giải quyết được 90%. |
| 7 | Đặng Quang Huy | Lỡ chuyến 2 vì chuyến 1 trễ, không biết đổi cặp xe buýt nào thay thế. | Người đi xe buýt chuyển tuyến | ETA realtime của 2 tuyến không đủ tin cậy, đến trạm trung chuyển thì xe tiếp theo vừa đi mất. | Rất sát với bài xe buýt của Dũng, cho thấy pain trung chuyển xe buýt là vấn đề chung của nhiều người. |
| 8 | Đặng Quang Huy | Mỗi sáng chọn cặp 2 tuyến xe buýt trước khi ra khỏi nhà. | Người đi làm / đi học hàng ngày | Google Maps chỉ gợi ý 1 đường cố định, không tính sai số và xác suất bắt kịp chuyến chuyển tiếp. | Cùng cụm bài toán di chuyển, bổ sung góc nhìn về lựa chọn phương án ngay từ điểm xuất phát. |
| 9 | Đặng Quang Huy | Xuống chuyến 1 đúng giờ nhưng chuyến 2 quá tải/đầy khách, không lên được. | Người đi xe buýt giờ cao điểm | Giờ cao điểm xe buýt bỏ trạm hoặc quá đông không chen lên được, phải đợi thêm 15-20 phút. | Pain thực tế, cần tích hợp yếu tố giờ cao điểm vào thuật toán tính toán rủi ro khi chọn cặp tuyến. |
| 10 | Bùi Lê Thái Sơn | Tìm tài liệu học tập phù hợp khi bắt đầu tiếp cận chủ đề mới. | Sinh viên / người tự học | Phải đọc và so sánh nhiều nguồn tài liệu trên mạng mới biết tài liệu nào phù hợp với mục tiêu và trình độ hiện tại. | Pain phổ biến, nhưng tiêu chí "phù hợp trình độ" mang tính chủ quan cao, khó đo lường metric định lượng. |
| 11 | Bùi Lê Thái Sơn | Kiểm tra và tổng hợp deadline từ nhiều group chat, lớp học khác nhau. | Sinh viên / người đi làm | Phải đọc nhiều tin nhắn từ nhiều group (Zalo, Messenger, Teams) để tìm deadline, dễ mất thời gian và bỏ sót. | Giải pháp tích hợp API các mạng xã hội bị chặn bảo mật, khó khả thi về mặt kỹ thuật trong thực tế. |
| 12 | Bùi Lê Thái Sơn | Đọc bản mô tả công việc (JD) rồi tự đối chiếu thủ công với CV cá nhân. | Người tìm việc / ứng viên | Phải tự đối chiếu từng yêu cầu trong JD với kỹ năng và kinh nghiệm trong CV để chỉnh sửa. | Nhiều công cụ ATS và prompt AI đã làm tốt, ít tính đặc thù cho bài lab phát hiện bài toán mới. |
| 13 | Hoàng Quốc Dũng | Khó lựa chọn và điều chỉnh hành trình xe buýt nhanh nhất từ VinUni về Xuân Thủy vì vị trí xe, thời gian chờ và tình trạng giao thông liên tục thay đổi. | Sinh viên di chuyển từ ngoại thành (Gia Lâm) sang Cầu Giấy | Khi đang di chuyển, người dùng khó xác định nên tiếp tục đi, xuống ở điểm nào hoặc chuyển sang tuyến nào để giảm tổng thời gian chờ và di chuyển. | Problem xuất sắc: Actor rõ ràng, workflow nhiều bước, bottleneck đo được bằng phút, có dữ liệu realtime đối chiếu. |
| 14 | Hoàng Quốc Dũng | Học viên mới mất thời gian tìm và đối chiếu tài liệu nằm rải rác trong README, worksheet, template, file test và Discord. | Học viên mới tham gia khóa học | Người học phải tự tìm kiếm và kết nối thông tin từ nhiều file và nền tảng khác nhau để xác định yêu cầu và bước tiếp theo. | Bài toán nội bộ thiết thực, nhưng giải pháp quy trình/tái cấu trúc tài liệu (No AI) giải quyết hiệu quả hơn. |
| 15 | Hoàng Quốc Dũng | Học viên phải kiểm tra thủ công tên repository, quyền public, branch, cấu trúc thư mục và trạng thái push trước khi nộp bài GitHub. | Học viên nộp bài tập qua GitHub | Các điều kiện nộp bài nằm ở nhiều vị trí khác nhau và phải được kiểm tra lần lượt bằng tay. | Bài toán lặp lại rõ, nhưng là bài toán thuần Rule (Script bash/python kiểm tra file), không cần AI. |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Tối ưu di chuyển & chuyển tuyến xe buýt công cộng | #7, #8, #9, #13 | Người đi phương tiện công cộng phải kết hợp 2 tuyến trở lên (interchange), phụ thuộc vào độ trễ thực tế, tần suất xe và ùn tắc giao thông; dễ bị lỡ chuyến hoặc chờ đợi kéo dài tại trạm trung chuyển. | Chiếm 4/15 ý tưởng (nhóm có 2 thành viên Dũng và Huy cùng gặp pain thật này). Dữ liệu phong phú, tác động đo được bằng phút. |
| B. Soạn thảo & cá nhân hóa nội dung giáo dục | #1, #2, #5 | Giáo viên tốn nhiều thời gian thủ công để tạo nội dung mới (nhận xét học sinh, đề thi, bài tập mở rộng) lặp đi lặp lại nhưng vẫn cần cá nhân hóa. | Thế mạnh của xử lý ngôn ngữ tự nhiên (NLP), nhưng khó đo lường độ chuẩn xác và phụ thuộc ngữ cảnh lớp học. |
| C. Tổng hợp, tìm kiếm & đối chiếu thông tin phân tán | #10, #11, #12, #14 | Người học/làm việc bị ngập trong tài liệu nằm rải rác trên nhiều nguồn, tốn thời gian đọc, lọc và so khớp thông tin để ra quyết định. | Nhiều bài trong cụm này có thể giải quyết bằng cách cải tổ cấu trúc thông tin (Information Architecture) hoặc tool lọc thông thường. |
| D. Kiểm soát rủi ro & quy trình cá nhân / nhóm | #3, #4, #6, #15 | Thiếu cơ chế nhắc nhở, kiểm tra điều kiện hoặc đối chiếu tự động dẫn đến quên sót, chậm trễ hoặc rủi ro bị lừa đảo. | Thiên về quy trình và kiểm tra luật cứng (Rule-based / Checklist), không cần đến khả năng học hay suy luận của AI. |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **Candidate #13: Tối ưu chọn & điều chỉnh cặp tuyến xe buýt VinUni — Xuân Thủy** | 1. Actor cực kỳ rõ (sinh viên VinUni đi về Cầu Giấy quãng đường ~25km).<br>2. Bottleneck rõ ràng tại điểm chuyển tuyến (chờ 15–30 phút nếu lỡ xe).<br>3. Đo lường chính xác bằng phút; có thể kết hợp dữ liệu tĩnh và động. | Độ trễ và tính chính xác của dữ liệu GPS từ các hệ thống mở của xe buýt Hà Nội có thời điểm bị lệch 3–5 phút. |
| **Candidate #1: Soạn nhận xét học sinh sau ca dạy** | 1. Bottleneck cụ thể: mất 40–50 phút gõ tay nhận xét sau mỗi buổi.<br>2. Nhiệm vụ lặp lại đều đặn hàng tuần, giáo viên có nhu cầu thật.<br>3. Dễ áp dụng mô hình ngôn ngữ để sinh văn bản từ rubric có sẵn. | Tiêu chí "nhận xét hay và cá nhân hóa" khó đo lường định lượng; rủi ro giáo viên lạm dụng AI tạo nhận xét rập khuôn khiến phụ huynh phàn nàn. |
| **Candidate #14: Tìm và đối chiếu tài liệu khóa học rải rác** | 1. Bối cảnh gần gũi với tất cả thành viên trong nhóm đang làm lab.<br>2. Khối lượng tài liệu xác định (README, worksheet, template).<br>3. Đo được bằng thời gian tìm kiếm từ khi có thắc mắc đến khi thấy câu trả lời. | Giải pháp tốt nhất lại là tổ chức lại cây thư mục và viết file mục lục tập trung (No AI / Documentation Fix) thay vì xây AI. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Candidate #13 (Xe buýt VinUni — Xuân Thủy)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| **Candidate #1 (Nhận xét học sinh)** | 4 | 4 | 4 | 3 | 5 | 4 | 3 | **27** |
| **Candidate #14 (Tài liệu khóa học)** | 4 | 3 | 4 | 3 | 5 | 3 | 4 | **26** |

**Giải thích điểm nổi bật:**
- Candidate #13 đạt điểm tối đa ở **Actor**, **Workflow**, **Pain evidence** và **Impact** vì cả Dũng và Huy đều trực tiếp trải nghiệm mỗi tuần, bấm giờ thực tế và hiểu rõ từng trạm trung chuyển (Ngã Tư Sở, Cầu Giấy, Kim Mã). So sánh giữa No AI (Google Maps), Rule (lịch trình cố định) và Workflow/Agent (tự động điều chỉnh theo GPS) rất rõ nét.
- Candidate #1 bị điểm 3 ở **Impact đo được** vì tính cá nhân hóa của lời nhận xét rất khó lượng hóa bằng số liệu khách quan, chỉ 1 thành viên trong nhóm hiểu sâu về nghiệp vụ dạy học này.
- Candidate #14 bị điểm 3 ở **Workflow** và **So sánh R/W/A** vì bản chất chỉ cần một file README chỉ mục tốt là giải quyết được bài toán, đưa AI vào là giải pháp thừa thãi (solution looking for a problem).

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Candidate #13: Tối ưu lựa chọn và điều chỉnh cặp tuyến xe buýt thời gian thực từ VinUni (Gia Lâm) về Xuân Thủy (Cầu Giấy) nhằm giảm thiểu thời gian chờ đợi và chuyển tuyến.
```

**Vì sao chọn (4-5 câu):**

Bài toán xuất phát từ nhu cầu di chuyển thực tế hàng tuần của sinh viên VinUni với quãng đường xuyên tâm dài 25km và bắt buộc phải trung chuyển qua ít nhất 2 chặng xe buýt. Vấn đề có điểm nghẽn cục bộ cực kỳ rõ ràng tại bước chuyển tiếp giữa chặng 1 và chặng 2, nơi thời gian chờ có thể tăng vọt từ 5 phút lên 25–35 phút chỉ vì chặng 1 bị kẹt xe nhẹ dẫn đến lỡ chuyến chặng 2. Tác động của bài toán đo lường được trực tiếp bằng đơn vị thời gian (phút), có thể kiểm chứng ngay bằng đồng hồ bấm giờ và dữ liệu chuyến xe. Nhóm có hai thành viên trực tiếp trải nghiệm tuyến đường này và nắm vững các cặp tuyến khả dĩ (E01, E03, 34, 27, 09B) cùng các điểm nút giao thông hay ùn tắc. Đây là bài toán mẫu mực để phân biệt ranh giới giữa tìm đường tĩnh (Rule/Google Maps) và điều phối động theo thời gian thực (Dynamic Workflow).

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

- **Candidate #1 (Nhận xét học sinh sau ca dạy):** Nhóm không chọn vì đây là bài toán nghiệp vụ riêng của 1 thành viên, các thành viên khác không có bối cảnh sư phạm để kiểm chứng. Hơn nữa, ranh giới chất lượng của nhận xét học sinh mang tính cảm tính cao, khó xác lập một Success Metric định lượng và khách quan trong buổi lab.
- **Candidate #14 (Tìm tài liệu khóa học rải rác):** Nhóm không chọn vì sau khi phân tích kỹ, điểm nghẽn nằm ở khâu thiết kế cấu trúc tài liệu của ban tổ chức. Một giải pháp Non-AI (viết lại file README, tạo trang tổng quan lục chỉ mục hoặc pin bài trên Discord) sẽ giải quyết triệt để 85% vấn đề mà không tốn chi phí xây dựng hay vận hành AI.

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
- Anh Điềm và anh Huy lo lắng: Dữ liệu vị trí xe buýt thời gian thực tại Hà Nội qua các ứng dụng như BusMap hay Tìm Buýt có thể bị chập chờn, mất tín hiệu GPS hoặc lệch 3-5 phút ở một số tuyến thường, liệu hệ thống có đưa ra quyết định sai lầm làm sinh viên đứng chờ lâu hơn không?
- Nhóm chốt: Không phụ thuộc vào một luồng dữ liệu duy nhất. Thiết kế luồng xử lý có nguyên tắc "Buffer an toàn" (chỉ gợi ý chuyển tuyến nếu khoảng cách giữa 2 xe tối thiểu 7-10 phút) và tích hợp cơ chế Fallback rõ ràng: nếu mất tín hiệu GPS realtime, hệ thống lập tức lùi về bảng giờ xuất bến tiêu chuẩn (GTFS timetable) kết hợp khuyến nghị các cặp tuyến có tần suất dày nhất trong khung giờ đó.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Phỏng vấn sâu (Interview) | 3 sinh viên VinUni thường xuyên đi xe buýt về nội thành | 1. Bạn N.M.T (sinh viên năm 2): *"Mỗi lần đi từ trường về Cầu Giấy ức chế nhất là trạm trung chuyển Ngã Tư Sở. Mình vừa bước xuống xe E01 thì thấy xe 27 vừa đóng cửa lăn bánh, thế là phải đứng chôn chân ở trạm gần 20 phút dưới trời nắng."*<br>2. Bạn H.T.K (sinh viên năm 3): *"Google Maps chỉ bảo đi tuyến nào tổng thời gian ngắn nhất lúc tìm ở trường, nhưng lúc mình đi qua cầu Vĩnh Tuy bị kẹt 10 phút là toàn bộ lộ trình Maps tính ban đầu coi như vứt đi, nó không tự nhắc mình đổi sang trạm khác."* | Bạn Đ.T.A: *"Nếu đi vào cuối tuần thì xe chạy rất đúng giờ, cứ lên xe E03 rồi sang xe 34 là xong, không thấy phiền lắm."* | Giới hạn rõ bài toán tập trung vào **khung giờ cao điểm các ngày trong tuần (16h30 – 19h00)** khi biến số giao thông và sai lệch giờ chạy xe buýt là lớn nhất. |
| Khảo sát nhanh (Survey) | 8 người (sinh viên và học viên có đi buýt liên quận) | 7/8 người (87.5%) xác nhận từng bị lỡ chuyến xe thứ hai ít nhất 2 lần/tuần khiến tổng thời gian chuyến đi tăng thêm từ 20 đến 40 phút. 6/8 người cho biết họ thường phải mở song song 2 ứng dụng (Google Maps để xem đường và BusMap/Tìm Buýt để soi xe đang ở đâu). | 1 người cho biết họ chọn xe ôm công nghệ nếu có việc gấp chứ không phụ thuộc vào xe buýt khi đã trễ giờ. | Làm rõ đối tượng phục vụ là nhóm sinh viên muốn tối ưu chi phí đi lại bằng xe buýt nhưng cần sự tin cậy và chủ động về thời gian, không so sánh với xe ôm công nghệ. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

Pain thật không nằm ở việc "không biết đường đi xe buýt", mà nằm ở **sự bất lực khi đang trên đường mà không biết bước trung chuyển tiếp theo có khớp hay không**. Người dùng thiếu một cơ chế dự báo và cảnh báo chuyển tuyến động khi xe chặng 1 bị chậm trễ so với dự kiến.

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Tìm Buýt (HanoiBus - Transerco)** | [timbus.vn](http://timbus.vn) | Tra cứu tuyến, tìm đường đi xe buýt tại Hà Nội và theo dõi xe đang chạy trên bản đồ. | Dữ liệu gốc chính thức từ Tổng công ty Vận tải Hà Nội, có biển số xe và vị trí GPS các tuyến truyền thống. | Thuật toán tìm đường tĩnh, không tính toán độ trễ liên tuyến; giao diện web/app còn giật lag, không có tính năng chủ động đẩy thông báo (push notification) khi có sự cố. | Dùng làm nguồn cung cấp dữ liệu GPS vị trí xe và danh sách điểm dừng, không dựa vào logic tìm đường của app này. |
| **BusMap (Hà Nội)** | [busmap.vn](https://busmap.vn) | Tìm lộ trình xe buýt thông minh đa phương thức, xem thời gian xe đến trạm (ETA). | Giao diện thân thiện, tính toán thời gian chờ tại từng trạm tương đối trực quan, hỗ trợ nhiều tuyến xe buýt điện VinBus. | Chỉ tính ETA tại một trạm đơn lẻ, không liên kết chuỗi hành trình (nếu xe 1 chậm thì xe 2 tại trạm đón phía trước có bị lỡ hay không vẫn không tự động tính lại). | Cần xây dựng logic "ghép cặp hành trình" (Interchange Pair Monitoring) thay vì theo dõi từng trạm độc lập. |
| **Google Maps Transit** | [maps.google.com](https://maps.google.com) | Chỉ đường công cộng toàn cầu, kết hợp dữ liệu mật độ giao thông (traffic layer). | Dữ liệu tắc đường theo thời gian thực cực kỳ chính xác nhờ nguồn dữ liệu thiết bị di động khổng lồ. | Dữ liệu vị trí xe buýt realtime tại Hà Nội trên Google Maps thường bị trễ hoặc thiếu thông tin các đợt điều chỉnh lộ trình; không gợi ý phương án nhảy cóc trạm khi đang ngồi trên xe. | Cần tận dụng lớp dữ liệu tắc đường để dự báo tốc độ di chuyển thực tế của xe buýt chặng 1. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

Nhóm **không xây dựng lại bản đồ hay ứng dụng theo dõi GPS từ đầu** (vì đã có Google Maps và BusMap làm rất tốt phần hạ tầng dữ liệu). Nhóm **chỉ tập trung xây dựng một Dynamic Re-routing & Decision Support Workflow**: lấy dữ liệu vị trí xe và tình trạng giao thông từ API, giám sát khoảng cách thời gian giữa chặng 1 và chặng 2, và đưa ra khuyến nghị chuyển tuyến kịp thời cho người dùng.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.md`

```text
CURRENT STATE — Tổng thời gian: ~95 phút (trong đó chờ đợi lãng phí: ~35 phút)

[1. Tra cứu Maps tại VinUni: 3'] 
  → [2. Đi bộ ra trạm VinBus: 5'] 
  → [3. Chờ xe E01/E03: 10'] 
  → [4. Ngồi xe chặng 1 đến trạm chuyển tiếp: 45'] 
  → [5. Xuống trạm, ngỡ ngàng thấy lỡ xe chặng 2 & Chờ xe tiếp theo: 20']  <-- BOTTLENECK NẶNG NHẤT
  → [6. Lên xe chặng 2 (34/27) về Xuân Thủy: 25'] 
  → [7. Xuống trạm & Đi bộ đến đích: 5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1. Tra cứu lộ trình ban đầu | Sinh viên | Điểm đi (VinUni), điểm đến (Xuân Thủy), giờ đi | Lộ trình cố định gợi ý trên Google Maps (VD: E01 → trạm Ngã Tư Sở → xe 27) | 3 phút / mỗi chuyến đi | Chỉ là kế hoạch lý thuyết, không tính được độ trễ khi qua cầu Vĩnh Tuy |
| 2. Đi bộ ra trạm đón | Sinh viên | Vị trí hiện tại | Có mặt tại trạm xe buýt VinUni | 5 phút | Cố định |
| 3. Chờ xe chặng 1 | Sinh viên | Thông tin giờ xe trên app | Lên được xe chặng 1 (E01 hoặc E03) | 8–12 phút | Phụ thuộc tần suất xe xuất bến tại Vinhomes Ocean Park |
| 4. Di chuyển chặng 1 | Sinh viên + Tài xế | Lộ trình xe buýt chặng 1 | Đến gần điểm chuyển tiếp dự kiến | 40–55 phút | **Rủi ro ùn tắc:** Đoạn Cổ Linh, Cầu Vĩnh Tuy, Trường Chinh thường xuyên kẹt xe giờ tan tầm |
| 5. Chuyển tuyến tại trạm trung chuyển | Sinh viên | Trực giác / tự mở lại app soi xe buýt | Lên được xe chặng 2 (xe 27, 34, 09B) | **15–25 phút** | **BOTTLENECK CHÍNH:** Xe chặng 1 bị chậm 7 phút dẫn đến trôi mất chuyến xe chặng 2, phải đứng đợi lượt xe tiếp theo trong mệt mỏi |
| 6. Di chuyển chặng 2 | Sinh viên + Tài xế | Tuyến đường trục Nguyễn Trãi/Kim Mã - Cầu Giấy | Đến trạm dừng tại đường Xuân Thủy | 20–30 phút | Mật độ xe cao, xe đông |
| 7. Đi bộ về điểm đến | Sinh viên | Điểm dừng xe buýt | Điểm đến cuối cùng (phòng trọ / trường học) | 5 phút | Kết thúc hành trình |

**Bottleneck chính (2-3 câu):**

Điểm nghẽn nghiêm trọng nhất nằm ở **Bước 5 (Thời gian chờ tại điểm chuyển tuyến)**. Do sinh viên hoàn toàn bị động trong suốt Bước 4 (không biết xe chặng 1 của mình đang bị trễ so với chuyến xe chặng 2 phía trước), họ vẫn xuống đúng trạm trung chuyển đã định sẵn trong khi xe chặng 2 vừa rời đi 1-2 phút trước, buộc phải chịu thêm một chu kỳ giãn cách chuyến mới kéo dài từ 15 đến 25 phút.

### 5.2. Future workflow bản nhóm

```text
FUTURE STATE — Tổng thời gian: ~68 phút (Thời gian chờ chuyển tuyến rút xuống: 5–8 phút)

[1. Khởi tạo hành trình & Thiết lập cặp tuyến tối ưu: 30s - Máy/Rule] 
  → [2. Giám sát tự động vị trí xe 1 & xe 2 realtime: Liên tục ngầm - Máy/Data Pipeline] 
  → [3. Phát hiện lệch pha & Tính toán lại điểm chuyển tuyến tối ưu: 10s - AI/Dynamic Routing] 
  → [4. Gửi thông báo chuyển hướng kịp thời cho sinh viên: 5s - Máy] 
  → [5. Sinh viên duyệt phương án & xuống trạm đề xuất mới: 1' - HUMAN BOUNDARY] 
  → [6. Bắt ngay chuyến xe chặng 2 thay thế mà không phải chờ đợi: 5-8' chờ] 
  → [7. Về đến Xuân Thủy an toàn, đúng giờ]

Fallback: Nếu mất tín hiệu GPS hoặc API dữ liệu xe bị lỗi, hệ thống tự động thông báo cho người dùng và chuyển sang chế độ "An toàn theo lịch trình" (khuyên chọn điểm trung chuyển có từ 3 tuyến thay thế trở lên như trạm Trung chuyển Cầu Giấy hoặc Ngã Tư Sở).
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian hành trình | ~95–105 phút | ~65–75 phút | Đồng hồ bấm giờ từ lúc rời trạm VinUni đến khi đặt chân xuống trạm Xuân Thủy |
| Thời gian chờ tại trạm chuyển tuyến | 18–28 phút | 5–8 phút | Bấm giờ từ lúc bước xuống xe chặng 1 đến lúc bước chân lên xe chặng 2 |
| Tỷ lệ lỡ chuyến chuyển tiếp phải chờ >15' | 65% số chuyến giờ cao điểm | Dưới 15% số chuyến | Ghi chép nhật ký 10 chuyến đi thực tế trong 2 tuần |
| Số lần phải mở app thủ công kiểm tra lại khi đang đi | 4–6 lần/chuyến | 0 lần (chỉ nhận 1 cảnh báo chủ động khi cần đổi điểm) | Đếm số thao tác bật màn hình điện thoại trong chuyến đi |
| Mức độ ức chế và bất an tâm lý | Cao (luôn lo sợ lỡ xe, muộn giờ) | Thấp (chủ động biết trước trạm cần xuống và xe sắp đón) | Khảo sát thang điểm hài lòng (1–5 sao) sau chuyến đi |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên trường Đại học VinUni (Gia Lâm) di chuyển bằng phương tiện giao thông công cộng về khu vực Xuân Thủy (Cầu Giấy) trong các buổi chiều tan học các ngày trong tuần. |
| **Workflow** | Tra cứu tuyến trên bản đồ → Bắt xe buýt chặng 1 (E01/E03) → Di chuyển qua các nút giao hay ùn tắc → Xuống trạm chuyển tiếp → Chờ và lên xe buýt chặng 2 (27/34/09B) → Về đến Xuân Thủy. |
| **Bottleneck** | Thời gian chờ đợi kéo dài từ 15–25 phút tại trạm chuyển tiếp do xe chặng 1 bị chậm vì tắc đường, khiến sinh viên không kịp đón chuyến xe chặng 2 như kế hoạch ban đầu mà không có phương án thay thế kịp thời. |
| **Impact** | Làm lãng phí từ 25–40 phút mỗi lượt đi, nâng tổng thời gian di chuyển lên gần 2 tiếng đồng hồ, gây mệt mỏi về thể chất và tăng nguy cơ trễ các lịch trình học tập/làm việc buổi tối. |
| **Success Metric** | Giảm thời gian chờ đợi tại trạm trung chuyển từ mức trung bình 20 phút xuống dưới 8 phút; giảm tổng thời gian hành trình từ ~95 phút xuống dưới 75 phút trong giờ cao điểm. |
| **Boundary** | Hệ thống chỉ giải quyết bài toán đề xuất và cảnh báo điều chỉnh điểm chuyển tuyến tối ưu cho tuyến đường VinUni – Xuân Thủy; không can thiệp vào vận hành thực tế của xe buýt và không đảm bảo việc xe buýt luôn có chỗ ngồi. |

**Câu hỏi AI phản biện v0 (nếu có):**
- **Field nào mơ hồ:** AI chỉ ra rằng Field **Success Metric** chưa nêu rõ điều kiện đo lường (đo vào khung giờ nào, điều kiện thời tiết ra sao) và Field **Boundary** chưa xác định rõ phạm vi hỗ trợ các tuyến xe buýt nào (chỉ VinBus hay cả xe buýt truyền thống của Transerco).
- **Tôi sửa gì:** Đã bổ sung phạm vi đo lường vào giờ cao điểm các ngày làm việc trong tuần (16h30–19h00); mở rộng phạm vi dữ liệu gồm cả tuyến VinBus (E01, E03, E05) và tuyến Transerco (27, 34, 09B) vì bài toán bắt buộc phải kết hợp cả hai mạng lưới xe này.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: **Thấp** (Tọa độ trạm, vị trí GPS của xe buýt, thời gian đến dự kiến, lịch trình tuyến đều là các số liệu định lượng, có tính đúng/sai rõ ràng, không phụ thuộc vào cảm xúc hay cách diễn giải chủ quan).
- Độ phức tạp: **Trung bình - Cao** (Phải xử lý đồng thời 3+ luồng dữ liệu biến động liên tục: vị trí xe chặng 1, vị trí các xe chặng 2 khả dĩ, và tình trạng tắc đường trên các phân đoạn kết nối; các bước xử lý phụ thuộc chặt chẽ vào thời gian thực).

**Bài toán nhóm nằm ở ô nào:**

```text
Ô "Độ mơ hồ Thấp — Độ phức tạp Trung bình/Cao" (Thích hợp cho Deterministic Data Pipeline kết hợp Dynamic Workflow).
```

**Vì sao (2-3 câu):**

Bài toán này không cần đến một thực thể AI có khả năng sáng tạo văn bản hay tự đưa ra quyết định mơ hồ. Cái cốt lõi là một hệ thống luồng công việc (Workflow) có khả năng liên tục đối soát điều kiện logic dựa trên dữ liệu định lượng thời gian thực để kích hoạt gợi ý chính xác khi có độ lệch ngưỡng xảy ra.

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Thiết lập các quy tắc cứng: *"Nếu đi trước 16h30, luôn đổi tại trạm Ngã Tư Sở sang xe 27; Nếu sau 17h00, luôn đổi tại trạm Kim Mã sang xe 34"*. | Chỉ đủ khi giao thông diễn ra hoàn hảo theo đúng biểu đồ giờ chuẩn (chủ nhật hoặc đêm muộn không kẹt xe). | Hoàn toàn bất lực trước các sự cố ngẫu nhiên như ùn tắc đột xuất, xe hỏng hoặc xe bỏ trạm. | **Dùng làm Fallback:** Khi mất kết nối API hoặc không có dữ liệu GPS thời gian thực. |
| **Workflow (Chọn)** | Pipeline tự động thu thập dữ liệu GPS của cả 2 chặng; liên tục tính chênh lệch thời gian đến trạm (Time Gap); nếu khoảng cách < 3 phút (nguy cơ lỡ chuyến cao), kích hoạt thuật toán đánh giá các điểm chuyển tuyến dự phòng và đẩy thông báo gợi ý đổi trạm cho sinh viên. | Đủ cho 95% các tình huống di chuyển thực tế vì quy trình có các bước xác định rõ ràng, có ngưỡng kích hoạt (trigger thresholds) và có người duyệt phương án cuối cùng. | Phụ thuộc vào chất lượng dữ liệu của API giao thông bên ngoài. | **CHỌN LÀM GIẢI PHÁP CHÍNH:** Điều phối toàn bộ luồng từ giám sát xe đến đề xuất chuyển hướng linh hoạt. |
| **Agent** | Một AI Agent hoàn toàn tự chủ, liên tục tự suy luận, tự gọi các công cụ ngoại vi (Maps API, Weather API, Xã luận giao thông trên Twitter), tự đưa ra quyết định mà không cần người dùng xác nhận. | Chỉ cần khi hệ thống phải tự đặt vé, tự đàm phán phương tiện thay thế hoặc tự động điều xe buýt đến đón sinh viên. | Quá mức phức tạp (over-engineering), chi phí tính toán cao, độ trễ phản hồi (latency) của LLM có thể làm chậm mất thời điểm vàng cần bấm chuông xuống xe. | **KHÔNG CHỌN:** Tốn kém không cần thiết và tạo rủi ro mất kiểm soát cho người dùng. |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?** Không, vì giao thông giờ cao điểm tại Hà Nội có tính biến động rất lớn; các quy tắc giờ cố định thường xuyên bị phá vỡ bởi ùn tắc tại các nút giao cầu Vĩnh Tuy và đường vành đai 2.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Quy trình bắt buộc phải rẽ nhánh phụ thuộc vào điều kiện thực tế (nếu xe 1 đến sớm → giữ nguyên lộ trình; nếu xe 1 trễ nhưng xe 2 cũng trễ → giữ nguyên; nếu xe 1 trễ mà xe 2 đúng giờ → rẽ nhánh đổi điểm chuyển tuyến hoặc đổi số hiệu xe chặng 2).
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Không cần Agent tự chủ hoàn toàn, vì không gian trạng thái của các tuyến xe buýt là hữu hạn và các nhánh rẽ hoàn toàn có thể định nghĩa tường minh bằng một Dynamic Workflow có cấu trúc.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Sinh viên là người phát hiện đầu tiên khi nhìn thấy gợi ý không hợp lý hoặc nhìn qua cửa sổ xe; họ chỉ mất 2 giây để bỏ qua thông báo và tiếp tục đi theo lộ trình cũ.
5. **Có hạ được từ Agent → Workflow → Rule không?** Hoàn toàn hạ được. Nhóm chủ động hạ từ ý tưởng Agent tự động phức tạp xuống mức **Workflow** có ngưỡng kích hoạt (Event-driven Workflow) kết hợp Rule dự phòng để đảm bảo độ tin cậy và tốc độ xử lý nhanh nhất.

**Mức chọn:**

```text
Workflow (Dynamic Event-driven Workflow with Fallback Rules)
```

**Vì sao chọn (3-4 câu):**

Mức Workflow đáp ứng chính xác sự phức tạp của bài toán mà không gây lãng phí tài nguyên như Autonomous Agent. Toàn bộ các bước từ theo dõi vị trí xe, tính toán khoảng thời gian chênh lệch (time buffer), đến kích hoạt cảnh báo đều tuân theo các logic luồng rõ ràng và có thể kiểm chứng được. Phương án này đảm bảo độ trễ xử lý cực thấp (dưới 1 giây) để thông báo kịp thời cho sinh viên trước khi xe buýt đi qua điểm rẽ, đồng thời giữ vững nguyên tắc con người luôn là người ra quyết định cuối cùng (Human-in-the-loop).

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

Mức Rule đơn thuần không thể đáp ứng được vì bài toán xe buýt liên tuyến đòi hỏi xử lý biến số thời gian thực từ hai đối tượng chuyển động độc lập (hai chiếc xe buýt ở hai vị trí khác nhau) trong điều kiện đường xá không thể đoán trước. Nếu chỉ dùng các luật tĩnh dạng "nếu giờ X thì đi xe Y", hệ thống sẽ hoàn toàn vô dụng trước những ngày trời mưa hoặc các vụ va chạm giao thông gây tắc nghẽn bất thường.

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên VinUni (Gia Lâm) di chuyển bằng xe buýt về khu vực Cầu Giấy/Xuân Thủy trong khung giờ cao điểm chiều (16h30 – 19h00) các ngày từ thứ Hai đến thứ Sáu. |
| **Workflow** | Khởi tạo chuyến đi → Lên xe chặng 1 (E01/E03) → Hệ sinh thái tự động giám sát vị trí xe 1 và xe 2 thời gian thực → Nhận thông báo điều chỉnh điểm chuyển tuyến nếu phát hiện nguy cơ lỡ xe → Xuống trạm được đề xuất tối ưu → Lên xe chặng 2 (27/34/09B/E05) → Kết thúc tại Xuân Thủy. |
| **Bottleneck** | Thời gian chờ đợi bị dồn ứ từ 15 đến 25 phút tại trạm trung chuyển do xe chặng 1 bị kẹt xe làm lỡ mất nhịp chuyến xe chặng 2, trong khi người đi không có thông tin dự báo để đổi trạm đón sớm hơn. |
| **Impact** | Gây lãng phí 25–40 phút mỗi chuyến đi, đẩy tổng thời gian hành trình lên 95–110 phút, gây mệt mỏi về thể chất, căng thẳng tâm lý và làm trễ giờ sinh hoạt/học tập cá nhân. |
| **Success Metric** | Giảm thời gian chờ đợi chuyển tuyến xuống dưới 8 phút (baseline: 20 phút); giảm tổng thời gian hành trình trung bình xuống dưới 75 phút (baseline: 95 phút); tỷ lệ bắt xe chặng 2 thành công trong vòng 7 phút đạt trên 85%. |
| **Boundary** (làm / không làm) | **LÀM:** Giám sát dữ liệu GPS thời gian thực của các cặp tuyến VinBus (E01, E03) và Transerco (27, 34, 09B, E05); tính toán Time-gap tại các trạm trung chuyển (Ngã Tư Sở, Cầu Giấy, Kim Mã, Royal City); phát cảnh báo đổi trạm trước ít nhất 5 phút.<br>**KHÔNG LÀM:** Không đặt vé xe, không can thiệp vào lộ trình lái xe của tài xế, không hỗ trợ các phương tiện ngoài xe buýt (như taxi, xe ôm), không giải quyết vấn đề xe buýt hết chỗ ngồi. |
| **AI intervention point** | Can thiệp ở **giữa Bước 4 (khi xe 1 đang di chuyển) và trước Bước 5 (trước khi đến trạm chuyển tuyến ít nhất 2 trạm dừng)**. Hệ thống phân tích độ lệch ETA để quyết định xem có cần can thiệp đổi trạm trung chuyển hay không. |
| **Mức chọn** | **Workflow** — Kết hợp Data Pipeline kiểm tra khoảng cách an toàn giữa 2 xe với Dynamic Routing logic; không dùng Agent tự chủ để tránh chi phí tính toán cao và độ trễ sinh kết quả. |
| **Rủi ro & người thật kiểm tra** | **Rủi ro:** Dữ liệu GPS của xe buýt bị mất kết nối hoặc trả về tọa độ ảo khiến hệ thống gợi ý sinh viên xuống trạm sai lầm.<br>**Người kiểm tra:** Sinh viên trên xe là người kiểm tra cuối cùng; thông báo luôn hiển thị rõ: *"Xe 27 còn cách trạm X 1.2km (khoảng 4 phút nữa tới). Bạn có muốn xuống trạm Royal City thay vì Ngã Tư Sở không?"* kèm nút bấm xác nhận. Nếu sinh viên không bấm hoặc từ chối, giữ nguyên lộ trình cũ. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor là sinh viên VinUni đi về Xuân Thủy; workflow 7 bước rõ ràng trước và sau khi tối ưu. |
| Baseline + metric đo được chưa? | **Yes** | Baseline thời gian chờ 20 phút, tổng thời gian 95 phút đo bằng đồng hồ bấm giờ; mục tiêu giảm xuống <8 phút và <75 phút. |
| Data/input đủ dùng chưa? | **Yes** | Đã có API và dữ liệu công khai từ BusMap và timbus.vn cho các tuyến E01, E03, 27, 34. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Hậu quả xấu nhất là sinh viên xuống ở trạm cũ và chờ xe bình thường như hiện tại, không gây nguy hiểm hay thiệt hại tài chính. |
| Có người review/owner không? | **Yes** | Sinh viên là người trực tiếp nhận thông báo và quyết định bấm chuông xuống xe hay tiếp tục ngồi trên xe. |
| Có cách non-AI đơn giản hơn không? | **Yes (nhưng không tối ưu)** | Cách Non-AI (nhìn bảng giờ cố định hoặc tự mở app soi bằng tay) chính là nguyên nhân gây ra bottleneck hiện tại vì con người không thể vừa đi đường vừa liên tục tính toán độ lệch của 2 xe cùng lúc. |

**Decision:**

```text
[Go]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

Dự án hội tụ đầy đủ các điều kiện tiên quyết để triển khai: bài toán có điểm nghẽn đo lường được bằng số liệu thực tế, đối tượng người dùng có nhu cầu bức thiết mỗi ngày, nguồn dữ liệu đầu vào (GPS xe buýt và luồng giao thông) đã sẵn sàng và khả thi. Việc lựa chọn giải pháp ở mức **Workflow** giúp loại bỏ hoàn toàn sự cồng kềnh của mô hình AI tạo sinh, tập trung tối đa vào tốc độ xử lý và tính chính xác của quyết định. Rủi ro sai số dữ liệu được khống chế an toàn nhờ cơ chế Human-in-the-loop và Fallback Rules vững chắc.

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data: Giới hạn trên 1 hành trình duy nhất từ VinUni về Xuân Thủy với 2 cặp tuyến chính: Cặp A (E01 chuyển sang 27 tại Ngã Tư Sở) và Cặp B (E03 chuyển sang 34 tại Kim Mã/Cầu Giấy).
- Chạy tay (Wizard of Oz / Semi-auto): Bạn Dũng đi xe buýt trên đường, bạn Huy ở nhà theo dõi màn hình định vị GPS của 2 xe qua web timbus.vn; khi thấy xe chặng 1 bị kẹt ở cầu Vĩnh Tuy làm lỡ xe 27, Huy nhắn tin báo Dũng xuống sớm tại trạm Times City để bắt xe E05 chạy thẳng về Cầu Giấy.
- Đo 3 số cụ thể:
  1. Thời gian chờ thực tế tại điểm chuyển tuyến (phút).
  2. Tổng thời gian chuyến đi từ VinUni về đến Xuân Thủy (phút).
  3. Độ chính xác của thời điểm gợi ý (báo trước điểm xuống xe bao nhiêu phút, có đủ thời gian chuẩn bị xuống xe không).
```

**Nếu Not Yet — cần validate gì trước:**

*(Không áp dụng vì nhóm chọn Go, tuy nhiên trong trường hợp cần thận trọng hơn: Cần kiểm tra độ ổn định tín hiệu GPS của tuyến xe buýt 27 và 34 liên tục trong 5 ngày làm việc để xác định tỷ lệ rớt sóng).*

**Nếu No-Go — làm gì thay AI:**

*(Không áp dụng)*

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng thử nghiệm và quay về cách tra cứu thông thường nếu:
1. Tỷ lệ dữ liệu GPS của các tuyến xe buýt bị gián đoạn hoặc mất tín hiệu vượt quá 30% tổng số chuyến thử nghiệm.
2. Gợi ý của hệ thống làm người dùng bị lỡ xe hoặc kéo dài thời gian di chuyển hơn so với việc ngồi yên trên lộ trình cũ từ 2 chuyến trở lên.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

