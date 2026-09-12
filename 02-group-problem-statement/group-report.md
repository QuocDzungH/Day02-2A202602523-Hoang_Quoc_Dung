# 02 — Group Problem Statement (Bản nộp nhóm)

## Thành viên nhóm "Tối ưu xe bus"

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|-------------------|
| 1   | Hoàng Quốc Dũng | 2A202602523 | Facilitator & Workflow Lead (Điều phối chung, xây dựng và tối ưu quy trình) |
| 2   | Lưu Nguyễn Tiến Anh | 2A202603002 | Research & Synthesis (Nghiên cứu thị trường, phân tích giải pháp hiện hành) |
| 3   | Đặng Quang Huy | 2A202602962 | Domain & Data Specialist (Chuyên gia dữ liệu xe buýt, GPS và giao thông realtime) |
| 4   | Vũ Minh Điềm | 2A202602858 | Validation & Skeptic (Khảo sát người dùng, phản biện rủi ro và giả định) |
| 5   | Bùi Lê Thái Sơn | 2A202602880 | Metrics & Writer (Xây dựng bộ chỉ số đo lường, tổng hợp văn kiện báo cáo) |

**Candidate problem nhóm chọn:**

Sinh viên di chuyển từ VinUni (Gia Lâm) về khu vực Xuân Thủy (Cầu Giấy) gặp khó khăn trong việc lựa chọn và điều chỉnh cặp tuyến xe buýt tối ưu theo thời gian thực do vị trí xe buýt, thời gian chờ tại điểm chuyển tuyến và tình trạng ùn tắc giao thông liên tục biến động, dẫn đến thời gian chờ đợi bị kéo dài lãng phí từ 25–40 phút mỗi chuyến.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Danh sách candidate problems của từng thành viên

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Nhận định của nhóm |
|---|---|---|---|---|---|
| 1 | Lưu Nguyễn Tiến Anh | Sau mỗi ca dạy, giáo viên mất từ 40-50 phút để gõ nhận xét tay cho từng học sinh vào hệ thống, nội dung lặp lại nhiều nhưng vẫn phải chỉnh từng câu để tránh trùng lặp. | Giáo viên đứng lớp kỹ năng / lập trình | Nghĩ câu từ diễn đạt cá nhân hóa cho từng bạn mất khoảng 5 phút/học sinh, dễ bị bí từ và tốn thời gian. | Pain rất thật của giáo viên, text-generation là thế mạnh AI nhưng khó đo lường định lượng độ hài lòng của phụ huynh. |
| 2 | Lưu Nguyễn Tiến Anh | Trong giờ thực hành, học sinh khá giỏi thường hoàn thành lắp ráp và lập trình sớm trước 20-30 phút rồi ngồi chơi buộc giáo viên phải tự nghĩ bài tập mở rộng tại chỗ mà không có công cụ hỗ trợ. | Giáo viên thực hành STEM/lập trình | Nghĩ đề bài mở rộng tại chỗ vừa sức, phù hợp linh kiện kit sẵn có mà không làm gián đoạn việc kèm cặp các bạn yếu. | Hay nhưng phụ thuộc nhiều vào bối cảnh lớp học trực tiếp, khó chuẩn hóa bộ kit linh kiện trong phạm vi bài lab. |
| 3 | Lưu Nguyễn Tiến Anh | Leader chậm ra quyết định phê duyệt. | Thành viên dự án / nhân viên | Thời gian chờ phê duyệt kéo dài từ 2-4 ngày do tin nhắn trôi, thiếu quy trình rõ ràng và thiếu mức độ ưu tiên (SLA). | Thuộc về vấn đề văn hóa tổ chức và quy trình quản lý, giải pháp quy trình (Rule/SLA) giải quyết triệt để hơn AI. |
| 4 | Vũ Minh Điềm | Cảnh báo rủi ro lừa đảo qua tin nhắn, cuộc gọi và đường link lạ. | Người thân trong gia đình, người lớn tuổi | Không có công cụ/đối chiếu real-time để xác định mức độ nguy hiểm, người dùng phải dựa vào kinh nghiệm hoặc cảm giác. | Đề tài lớn, nhưng phạm vi dữ liệu quá rộng, rủi ro false positive/negative có thể gây hậu quả nghiêm trọng. |
| 5 | Vũ Minh Điềm | Làm đề thi và bài tập phân hóa cho học sinh cấp 3. | Giáo viên nói chung | Tìm nguồn, lọc thông tin, và biến đổi thành đề mới tốn nhiều công sức thủ công. | Phổ biến, thị trường đã có nhiều giải pháp EdTech, khó tạo điểm khác biệt trong phạm vi bài lab. |
| 6 | Vũ Minh Điềm | Quên mang đầy đủ đồ dùng cá nhân và tài liệu khi ra ngoài. | Sinh viên / người đi làm | Trí nhớ và lịch trình bận rộn dễ dẫn đến quên sót đồ đạc quan trọng. | Bài toán đơn giản, một checklist cố định hoặc app nhắc việc (Rule) đã giải quyết được 90%. |
| 7 | Đặng Quang Huy | Lỡ chuyến 2 vì chuyến 1 trễ, không biết đổi cặp xe buýt nào thay thế. | Người đi xe buýt chuyển tuyến | ETA realtime của 2 tuyến không đủ tin cậy, đến trạm trung chuyển thì xe tiếp theo vừa đi mất. | Rất sát với bài xe buýt của Dũng, cho thấy pain trung chuyển xe buýt là vấn đề chung của nhiều người. |
| 8 | Đặng Quang Huy | Mỗi sáng chọn cặp 2 tuyến xe buýt trước khi ra khỏi nhà. | Người đi làm / đi học hàng ngày | Google Maps chỉ gợi ý 1 đường cố định, không tính sai số và xác suất bắt kịp chuyến chuyển tiếp. | Cùng cụm bài toán di chuyển, bổ sung góc nhìn về lựa chọn phương án ngay từ điểm xuất phát. |
| 9 | Đặng Quang Huy | Xuống chuyến 1 đúng giờ nhưng chuyến 2 quá tải/đầy khách, không lên được. | Người đi xe buýt giờ cao điểm | Giờ cao điểm xe buýt bỏ trạm hoặc quá đông không chen lên được, phải đợi thêm 15-20 phút. | Pain thực tế, cần tính đến yếu tố giờ cao điểm khi đánh giá độ an toàn của cặp tuyến. |
| 10 | Bùi Lê Thái Sơn | Tìm tài liệu học tập phù hợp khi bắt đầu tiếp cận chủ đề mới. | Sinh viên / người tự học | Phải đọc và so sánh nhiều nguồn tài liệu trên mạng mới biết tài liệu nào phù hợp với trình độ. | Phổ biến, nhưng tiêu chí "phù hợp trình độ" mang tính chủ quan cao, khó đo lường metric định lượng. |
| 11 | Bùi Lê Thái Sơn | Kiểm tra và tổng hợp deadline từ nhiều group chat, lớp học khác nhau. | Sinh viên / người đi làm | Phải đọc nhiều tin nhắn từ nhiều group (Zalo, Messenger, Teams) để tìm deadline, dễ bỏ sót. | Giải pháp tích hợp API các mạng xã hội bị rào cản bảo mật, khó khả thi về mặt kỹ thuật trong thực tế. |
| 12 | Bùi Lê Thái Sơn | Đọc bản mô tả công việc (JD) rồi tự đối chiếu thủ công với CV cá nhân. | Người tìm việc / ứng viên | Phải tự đối chiếu từng yêu cầu trong JD với kỹ năng và kinh nghiệm trong CV để chỉnh sửa. | Nhiều công cụ ATS và prompt AI đã làm tốt, ít tính đặc thù cho bài lab phát hiện bài toán mới. |
| 13 | Hoàng Quốc Dũng | Khó lựa chọn và điều chỉnh hành trình xe buýt nhanh nhất từ VinUni về Xuân Thủy vì vị trí xe, thời gian chờ và tình trạng giao thông liên tục thay đổi. | Sinh viên di chuyển từ ngoại thành (Gia Lâm) sang Cầu Giấy | Khi đang di chuyển, người dùng khó xác định nên tiếp tục đi, xuống ở điểm nào hoặc chuyển sang tuyến nào để giảm tổng thời gian chờ và di chuyển. | Bài toán xuất sắc: Actor rõ ràng, workflow nhiều bước, bottleneck đo được bằng phút, có dữ liệu realtime đối chiếu. |
| 14 | Hoàng Quốc Dũng | Học viên mới mất thời gian tìm và đối chiếu tài liệu nằm rải rác trong README, worksheet, template, file test và Discord. | Học viên mới tham gia khóa học | Người học phải tự tìm kiếm và kết nối thông tin từ nhiều file và nền tảng khác nhau để xác định yêu cầu. | Bài toán nội bộ thiết thực, nhưng giải pháp quy trình và cấu trúc lại tài liệu (No AI) giải quyết hiệu quả hơn. |
| 15 | Hoàng Quốc Dũng | Học viên phải kiểm tra thủ công tên repository, quyền public, branch, cấu trúc thư mục và trạng thái push trước khi nộp bài GitHub. | Học viên nộp bài tập qua GitHub | Các điều kiện nộp bài nằm ở nhiều vị trí khác nhau và phải được kiểm tra lần lượt bằng tay. | Bài toán lặp lại rõ, nhưng là bài toán thuần Rule (Script bash/python kiểm tra file), không cần AI. |

### 3.2. Phân cụm và nhận diện mẫu hình chung (Clustering)

| Cluster | Candidates included | Mẫu hình chung (Pattern) | Đánh giá của nhóm |
|---|---|---|---|
| **A. Tối ưu di chuyển & chuyển tuyến xe buýt công cộng** | #7, #8, #9, #13 | Người đi phương tiện công cộng phải kết hợp 2 tuyến trở lên (interchange), phụ thuộc vào độ trễ thực tế, tần suất xe và ùn tắc giao thông; dễ bị lỡ chuyến hoặc chờ đợi kéo dài tại trạm trung chuyển. | Chiếm 4/15 ý tưởng (nhóm có 2 thành viên Dũng và Huy cùng gặp pain thật này). Dữ liệu phong phú, tác động đo lường trực tiếp bằng phút. |
| **B. Soạn thảo & cá nhân hóa nội dung giáo dục** | #1, #2, #5 | Giáo viên tốn nhiều thời gian thủ công để tạo nội dung mới (nhận xét học sinh, đề thi, bài tập mở rộng) lặp đi lặp lại nhưng vẫn cần cá nhân hóa. | Thế mạnh của xử lý ngôn ngữ tự nhiên (NLP), nhưng khó đo lường độ chuẩn xác và phụ thuộc ngữ cảnh sư phạm trực tiếp. |
| **C. Tổng hợp, tìm kiếm & đối chiếu thông tin phân tán** | #10, #11, #12, #14 | Người học/làm việc bị ngập trong tài liệu nằm rải rác trên nhiều nguồn, tốn thời gian đọc, lọc và so khớp thông tin để ra quyết định. | Nhiều bài trong cụm này có thể giải quyết bằng cách cải tổ cấu trúc thông tin (Information Architecture) hoặc tool lọc thông thường. |
| **D. Kiểm soát rủi ro & quy trình cá nhân / nhóm** | #3, #4, #6, #15 | Thiếu cơ chế nhắc nhở, kiểm tra điều kiện hoặc đối chiếu tự động dẫn đến quên sót, chậm trễ hoặc rủi ro bị lừa đảo. | Thiên về quy trình và kiểm tra luật cứng (Rule-based / Checklist), không cần đến khả năng học hay suy luận của AI. |

### 3.3. Danh sách rút gọn (Shortlist)

| Candidate | Lý do nhóm đưa vào Shortlist | Rủi ro & Điểm cần kiểm chứng |
|---|---|---|
| **Candidate #13: Tối ưu chọn & điều chỉnh cặp tuyến xe buýt VinUni — Xuân Thủy** | 1. Đối tượng người dùng rõ ràng (sinh viên VinUni đi về Cầu Giấy quãng đường ~25km).<br>2. Điểm nghẽn cụ thể tại điểm chuyển tuyến (chờ 15–30 phút nếu lỡ xe).<br>3. Đo lường chính xác bằng phút; có nguồn dữ liệu tĩnh và động khả thi. | Độ trễ và tính chính xác của dữ liệu GPS từ hệ thống xe buýt Hà Nội trong khung giờ cao điểm. |
| **Candidate #1: Soạn nhận xét học sinh sau ca dạy** | 1. Điểm nghẽn đo đếm được: mất 40–50 phút gõ tay nhận xét sau mỗi buổi.<br>2. Công việc lặp lại đều đặn hàng tuần, giáo viên có nhu cầu bức thiết.<br>3. Dễ áp dụng mô hình ngôn ngữ để sinh văn bản từ tiêu chí có sẵn. | Tiêu chí "nhận xét hay và cá nhân hóa" khó đo lường định lượng; rủi ro giáo viên lạm dụng AI tạo nhận xét rập khuôn khiến phụ huynh phàn nàn. |
| **Candidate #14: Tìm và đối chiếu tài liệu khóa học rải rác** | 1. Bối cảnh gần gũi với tất cả thành viên trong nhóm đang làm lab.<br>2. Khối lượng tài liệu xác định (README, worksheet, template).<br>3. Đo được bằng thời gian tìm kiếm từ khi có thắc mắc đến khi thấy câu trả lời. | Giải pháp tối ưu lại là tổ chức lại cây thư mục và viết file mục lục tập trung (No AI / Documentation Fix) thay vì xây hệ thống AI. |

### 3.4. Đánh giá và chấm điểm đồng thuận (Consensus Scoring)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Khả thi trong lab | So sánh R/W/A | Nhóm hiểu domain | Tổng điểm |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **Candidate #13 (Xe buýt VinUni — Xuân Thủy)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| **Candidate #1 (Nhận xét học sinh)** | 4 | 4 | 4 | 3 | 5 | 4 | 3 | **27** |
| **Candidate #14 (Tài liệu khóa học)** | 4 | 3 | 4 | 3 | 5 | 3 | 4 | **26** |

**Phân tích điểm số của nhóm:**
- **Candidate #13** đạt điểm tối đa ở phần lớn các tiêu chí do cả hai thành viên Dũng và Huy trực tiếp trải nghiệm hàng tuần, có dữ liệu bấm giờ thực tế và hiểu rõ từng trạm trung chuyển (Ngã Tư Sở, Cầu Giấy, Kim Mã). Ranh giới kỹ thuật giữa No AI (Google Maps), Rule (lịch trình cố định) và Dynamic Workflow (điều phối theo GPS) thể hiện vô cùng sắc nét.
- **Candidate #1** bị giới hạn ở chỉ số tác động vì chất lượng nhận xét sư phạm khó định lượng bằng số liệu khách quan, đồng thời chỉ có 1 thành viên có chuyên môn sâu về mảng này.
- **Candidate #14** không được ưu tiên vì vấn đề có thể giải quyết dứt điểm bằng một cấu trúc tài liệu khoa học hơn mà không cần đến công nghệ AI phức tạp.

**Bài toán nhóm thống nhất lựa chọn:**

```text
Candidate #13: Tối ưu lựa chọn và điều chỉnh cặp tuyến xe buýt thời gian thực từ VinUni (Gia Lâm) về Xuân Thủy (Cầu Giấy) nhằm giảm thiểu thời gian chờ đợi và chuyển tuyến.
```

**Lý do nhóm quyết định chọn đề tài này:**

Đề tài xuất phát từ nhu cầu đi lại bức thiết của sinh viên VinUni trên trục xuyên tâm dài 25km bắt buộc phải kết hợp từ 2 chặng xe buýt trở lên. Vấn đề có điểm nghẽn cục bộ cực kỳ rõ nét tại bước chuyển tiếp giữa chặng 1 và chặng 2: thời gian chờ đợi có thể tăng vọt từ 5 phút lên 25–35 phút chỉ vì xe chặng 1 bị chậm một vài phút do tắc đường, làm người đi lỡ mất nhịp chuyến xe chặng 2. Tác động của bài toán đo lường trực tiếp bằng đơn vị phút, có thể kiểm chứng ngay bằng đồng hồ bấm giờ và lịch trình xe. Nhóm có hai thành viên trực tiếp đi tuyến này hàng tuần, nắm vững các cặp tuyến (E01, E03, 34, 27, 09B) cũng như các điểm nút giao thông hay ùn tắc. Đây là bài toán mẫu mực để phân định ranh giới giữa tìm đường tĩnh và điều phối động theo thời gian thực.

**Lý do nhóm không lựa chọn các đề tài còn lại:**

- **Candidate #1 (Nhận xét học sinh sau ca dạy):** Nhóm không chọn do bài toán phụ thuộc nhiều vào cảm nhận chủ quan của phụ huynh và học sinh, khó xây dựng một Success Metric định lượng và khách quan trong khuôn khổ bài lab.
- **Candidate #14 (Tìm tài liệu khóa học rải rác):** Nhóm không chọn vì bản chất điểm nghẽn thuộc về khâu tổ chức thông tin. Giải pháp cải tiến quy trình tài liệu (viết lại README, tạo chỉ mục tập trung, pin bài thông báo) đã giải quyết được trên 85% vấn đề mà không phát sinh chi phí xây dựng công nghệ.

**Ghi nhận thảo luận và thống nhất bất đồng trong nhóm:**

```text
- Vấn đề tranh luận: Thành viên Điềm và Huy đặt câu hỏi phản biện: Dữ liệu vị trí xe buýt thời gian thực tại Hà Nội qua các ứng dụng như BusMap hay Tìm Buýt có thể bị chập chờn, mất tín hiệu GPS hoặc lệch 3-5 phút ở một số tuyến thường, liệu hệ thống có đưa ra gợi ý sai lầm làm sinh viên đứng chờ lâu hơn không?
- Thống nhất của nhóm: Không phụ thuộc vào một luồng dữ liệu đơn lẻ. Nhóm chủ động thiết lập nguyên tắc "Buffer an toàn" (chỉ gợi ý chuyển tuyến nếu khoảng cách đón xe an toàn tối thiểu 7-10 phút) và tích hợp cơ chế Fallback: nếu mất tín hiệu GPS realtime, hệ thống lập tức chuyển về bảng giờ xuất bến tiêu chuẩn (GTFS timetable) kết hợp khuyến nghị các trạm trung chuyển lớn có tần suất xe dày nhất.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Kiểm chứng nhanh với người dùng (Quick Validation)

| Nguồn kiểm chứng | Quy mô mẫu | Tín hiệu xác nhận (Trích dẫn nguyên văn) | Tín hiệu phản bác | Điều chỉnh của nhóm |
|---|---:|---|---|---|
| Phỏng vấn sâu (Interview) | 3 sinh viên VinUni thường xuyên đi xe buýt về nội thành | 1. Bạn N.M.T (sinh viên năm 2): *"Mỗi lần đi từ trường về Cầu Giấy ức chế nhất là trạm trung chuyển Ngã Tư Sở. Mình vừa bước xuống xe E01 thì thấy xe 27 vừa đóng cửa lăn bánh, thế là phải đứng chôn chân ở trạm gần 20 phút dưới trời nắng."*<br>2. Bạn H.T.K (sinh viên năm 3): *"Google Maps chỉ bảo đi tuyến nào tổng thời gian ngắn nhất lúc tìm ở trường, nhưng lúc mình đi qua cầu Vĩnh Tuy bị kẹt 10 phút là toàn bộ lộ trình Maps tính ban đầu coi như vứt đi, nó không tự nhắc mình đổi sang trạm khác."* | Bạn Đ.T.A: *"Nếu đi vào cuối tuần thì xe chạy rất đúng giờ, cứ lên xe E03 rồi sang xe 34 là xong, không thấy phiền lắm."* | Nhóm xác định trọng tâm bài toán vào **khung giờ cao điểm chiều các ngày trong tuần (16h30 – 19h00)** khi tình trạng ùn tắc và sai lệch biểu đồ giờ xe buýt là nghiêm trọng nhất. |
| Khảo sát nhanh (Survey) | 8 người (sinh viên và người đi buýt liên quận) | 7/8 người (87.5%) xác nhận từng bị lỡ chuyến xe thứ hai ít nhất 2 lần/tuần khiến tổng thời gian chuyến đi kéo dài thêm từ 20 đến 40 phút. 6/8 người cho biết họ thường phải mở song song 2 ứng dụng (Google Maps để xem đường và BusMap/Tìm Buýt để soi xe đang ở đâu). | 1 người cho biết họ chọn xe ôm công nghệ nếu có việc gấp chứ không phụ thuộc vào xe buýt khi đã trễ giờ. | Nhóm xác định nhóm đối tượng phục vụ là người muốn tối ưu chi phí đi lại bằng xe buýt nhưng cần sự tin cậy và chủ động về thời gian. |

**Kết luận cốt lõi sau kiểm chứng:**

Nhu cầu thực sự của người dùng không phải là tìm đường mới, mà là **cơ chế dự báo và cảnh báo chuyển tuyến động khi đang ngồi trên xe**. Người đi xe buýt hoàn toàn bị động trước sự lệch pha giữa hai chuyến xe nối tiếp khi có ùn tắc giao thông trên đường.

### 4.2. Nghiên cứu giải pháp hiện có (Competitive Research)

| Sản phẩm / Giải pháp | Đường dẫn kiểm chứng | Khâu giải quyết trong quy trình | Ưu điểm nổi bật | Nhược điểm & Rủi ro | Bài học ứng dụng cho nhóm |
|---|---|---|---|---|---|
| **Tìm Buýt (HanoiBus - Transerco)** | [timbus.vn](http://timbus.vn) | Tra cứu thông tin tuyến, tìm đường đi và theo dõi xe đang chạy trên bản đồ. | Dữ liệu gốc chính thức từ Transerco, có tọa độ GPS và biển số xe của mạng lưới buýt truyền thống. | Thuật toán tìm đường tĩnh, không liên kết độ trễ giữa các chặng; chưa có cơ chế đẩy thông báo chủ động khi có sự cố. | Khai thác làm nguồn cung cấp dữ liệu định vị GPS và danh sách điểm dừng; không dựa vào thuật toán tìm đường của hệ thống này. |
| **BusMap (Hà Nội)** | [busmap.vn](https://busmap.vn) | Tìm lộ trình xe buýt thông minh đa phương thức, tính toán thời gian xe đến trạm (ETA). | Giao diện hiện đại, tính toán ETA tại từng trạm tương đối trực quan, hỗ trợ đầy đủ các tuyến xe điện VinBus. | Chỉ theo dõi ETA tại từng trạm đơn lẻ, không liên kết chuỗi hành trình (không tự tính lại lộ trình khi xe chặng 1 bị trễ). | Cần xây dựng thuật toán giám sát theo cặp hành trình liên tuyến (Interchange Pair Monitoring). |
| **Google Maps Transit** | [maps.google.com](https://maps.google.com) | Chỉ đường công cộng toàn cầu, kết hợp dữ liệu mật độ giao thông theo thời gian thực. | Lớp dữ liệu tắc đường cực kỳ chính xác nhờ mạng lưới thiết bị di động rộng khắp. | Dữ liệu xe buýt realtime tại Hà Nội cập nhật chậm; không hỗ trợ tính toán nhảy cóc trạm khi người dùng đang trên hành trình. | Tận dụng lớp dữ liệu tắc đường để dự báo tốc độ di chuyển thực tế của xe buýt chặng 1. |

**Định hướng phát triển của nhóm từ nghiên cứu:**

Nhóm **không xây dựng lại nền tảng bản đồ số hay hệ thống GPS từ đầu** nhằm tránh lãng phí nguồn lực. Nhóm **chủ động định vị sản phẩm là một Dynamic Re-routing & Decision Support Workflow**: tập trung kết nối dữ liệu xe buýt và tình trạng giao thông thời gian thực, liên tục đối soát khoảng cách an toàn giữa 2 chặng và phát cảnh báo điều chỉnh điểm trung chuyển kịp thời cho hành khách.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Luồng quy trình hiện tại (Current Workflow)

```text
CURRENT STATE — Tổng thời gian: ~95 phút (Thời gian chờ đợi lãng phí: ~35 phút)

[1. Tra cứu Maps tại VinUni: 3'] 
  → [2. Đi bộ ra trạm VinBus: 5'] 
  → [3. Chờ xe E01/E03: 10'] 
  → [4. Ngồi xe chặng 1 đến trạm chuyển tiếp: 45'] 
  → [5. Xuống trạm, ngỡ ngàng thấy lỡ xe chặng 2 & Chờ chuyến tiếp: 20']  <-- BOTTLENECK CHÍNH
  → [6. Lên xe chặng 2 (34/27) về Xuân Thủy: 25'] 
  → [7. Xuống trạm & Đi bộ đến đích: 5']
```

| Bước | Chủ thể thực hiện | Dữ liệu đầu vào | Kết quả đầu ra | Thời gian tiêu tốn | Phân tích quy trình & Điểm nghẽn |
|---|---|---|---|---|---|
| 1. Tra cứu lộ trình ban đầu | Sinh viên | Điểm đi (VinUni), điểm đến (Xuân Thủy), giờ xuất phát | Lộ trình cố định gợi ý trên Google Maps (VD: E01 → trạm Ngã Tư Sở → xe 27) | 3 phút / chuyến | Kế hoạch mang tính lý thuyết, không tính được độ trễ phát sinh khi qua cầu Vĩnh Tuy |
| 2. Đi bộ ra trạm đón | Sinh viên | Vị trí hiện tại | Có mặt tại trạm xe buýt VinUni | 5 phút | Thao tác cố định |
| 3. Chờ xe chặng 1 | Sinh viên | Bảng giờ xe trên ứng dụng | Lên được xe chặng 1 (E01 hoặc E03) | 8–12 phút | Phụ thuộc tần suất xe xuất bến tại Vinhomes Ocean Park |
| 4. Di chuyển chặng 1 | Sinh viên + Tài xế | Lộ trình xe buýt chặng 1 | Đến gần điểm chuyển tiếp dự kiến | 40–55 phút | Đoạn Cổ Linh, Cầu Vĩnh Tuy, Trường Chinh thường xuyên xảy ra ùn ứ nghiêm trọng |
| 5. Chuyển tuyến tại trạm trung chuyển | Sinh viên | Phán đoán cá nhân / tự mở app kiểm tra | Lên được xe chặng 2 (xe 27, 34, 09B) | **15–25 phút** | **ĐIỂM NGHẼN CHÍNH:** Xe chặng 1 chậm 7 phút làm lỡ chuyến xe chặng 2, hành khách buộc phải chờ thêm cả chu kỳ chuyến mới |
| 6. Di chuyển chặng 2 | Sinh viên + Tài xế | Tuyến đường trục Nguyễn Trãi/Kim Mã - Cầu Giấy | Đến trạm dừng tại đường Xuân Thủy | 20–30 phút | Mật độ phương tiện cao, lưu thông chậm |
| 7. Đi bộ về điểm đến | Sinh viên | Điểm dừng xe buýt | Điểm đến cuối cùng (phòng trọ / trường học) | 5 phút | Kết thúc hành trình |

**Phân tích điểm nghẽn chính trong quy trình:**

Điểm nghẽn nghiêm trọng nhất tập trung tại **Bước 5 (Thời gian chờ tại điểm chuyển tuyến)**. Vì người đi hoàn toàn thiếu thông tin dự báo trong suốt Bước 4 (không nắm được xe chặng 1 của mình đang bị chậm so với chuyến xe chặng 2 phía trước), họ vẫn di chuyển thụ động đến trạm trung chuyển đã định sẵn đúng lúc xe chặng 2 vừa rời bến, dẫn đến việc phải đứng chờ đợi thêm 15 đến 25 phút trong mệt mỏi.

### 5.2. Luồng quy trình đề xuất tối ưu (Future Workflow)

```text
FUTURE STATE — Tổng thời gian: ~68 phút (Thời gian chờ chuyển tuyến rút ngắn còn: 5–8 phút)

[1. Khởi tạo hành trình & Thiết lập cặp tuyến tối ưu: 30s - Hệ thống] 
  → [2. Giám sát tự động vị trí xe 1 & xe 2 realtime: Liên tục ngầm - Data Pipeline] 
  → [3. Phát hiện lệch pha & Tính toán lại điểm chuyển tuyến tối ưu: 10s - Dynamic Routing] 
  → [4. Đẩy thông báo gợi ý chuyển hướng kịp thời: 5s - Hệ thống] 
  → [5. Sinh viên duyệt phương án & xuống trạm đề xuất mới: 1' - HUMAN BOUNDARY] 
  → [6. Đón chuyến xe chặng 2 thay thế tối ưu (chờ 5-8'): 6'] 
  → [7. Về đến Xuân Thủy an toàn, đúng giờ]

Phương án dự phòng (Fallback): Nếu mất kết nối GPS hoặc hệ thống dữ liệu gián đoạn, hệ thống cảnh báo người dùng và tự động chuyển sang chế độ "Lịch trình an toàn", khuyến nghị sinh viên chuyển tuyến tại các nhà chờ trung chuyển lớn có trên 3 tuyến thay thế (như trạm Trung chuyển Cầu Giấy hoặc Ngã Tư Sở).
```

**Bảng so sánh tác động trước và sau cải tiến:**

| Chỉ số đánh giá | Hiện trạng ban đầu | Mục tiêu sau cải tiến | Phương pháp đo lường |
|---|---:|---:|---|
| Tổng thời gian hành trình | ~95–105 phút | ~65–75 phút | Bấm giờ từ lúc xuất phát tại trạm VinUni đến khi bước xuống trạm Xuân Thủy |
| Thời gian chờ tại trạm chuyển tuyến | 18–28 phút | 5–8 phút | Bấm giờ từ lúc rời xe chặng 1 đến lúc bước lên xe chặng 2 |
| Tỷ lệ lỡ chuyến chuyển tiếp phải chờ >15' | 65% số chuyến giờ cao điểm | Dưới 15% số chuyến | Theo dõi nhật ký 10 chuyến đi thực tế trong 2 tuần |
| Số thao tác mở điện thoại kiểm tra trên đường | 4–6 lần/chuyến | 0 lần (chỉ nhận 1 cảnh báo chủ động khi cần đổi điểm) | Đếm số lần bật màn hình kiểm tra ứng dụng khi đang di chuyển |
| Mức độ hài lòng của người dùng | Thấp (thường xuyên căng thẳng, lo muộn giờ) | Cao (chủ động lộ trình và thời gian chuyển tuyến) | Khảo sát mức độ hài lòng (thang điểm 1–5 sao) sau chuyến đi |

### 5.3. Problem Statement v0 (Bản phác thảo ban đầu)

| Trường thông tin | Nội dung chi tiết |
|---|---|
| **Actor** | Sinh viên trường Đại học VinUni (Gia Lâm) di chuyển bằng phương tiện giao thông công cộng về khu vực Xuân Thủy (Cầu Giấy) trong các buổi chiều tan học các ngày trong tuần. |
| **Workflow** | Tra cứu tuyến trên bản đồ → Bắt xe buýt chặng 1 (E01/E03) → Di chuyển qua các nút giao hay ùn tắc → Xuống trạm chuyển tiếp → Chờ và lên xe buýt chặng 2 (27/34/09B) → Về đến Xuân Thủy. |
| **Bottleneck** | Thời gian chờ đợi kéo dài từ 15–25 phút tại trạm chuyển tiếp do xe chặng 1 bị chậm vì tắc đường, khiến sinh viên không kịp đón chuyến xe chặng 2 như kế hoạch ban đầu mà không có phương án thay thế kịp thời. |
| **Impact** | Làm lãng phí từ 25–40 phút mỗi lượt đi, nâng tổng thời gian di chuyển lên gần 2 tiếng đồng hồ, gây mệt mỏi về thể chất và tăng nguy cơ trễ các lịch trình học tập/làm việc buổi tối. |
| **Success Metric** | Giảm thời gian chờ đợi tại trạm trung chuyển từ mức trung bình 20 phút xuống dưới 8 phút; giảm tổng thời gian hành trình từ ~95 phút xuống dưới 75 phút trong giờ cao điểm. |
| **Boundary** | Hệ thống chỉ giải quyết bài toán đề xuất và cảnh báo điều chỉnh điểm chuyển tuyến tối ưu cho tuyến đường VinUni – Xuân Thủy; không can thiệp vào vận hành thực tế của xe buýt và không đảm bảo việc xe buýt luôn có chỗ ngồi. |

**Đánh giá và điều chỉnh sau phản biện bản v0:**
- Nhóm nhận diện thấy trường **Success Metric** ban đầu chưa quy định chặt chẽ điều kiện đo lường (khung giờ cao điểm cụ thể) và trường **Boundary** chưa xác định rõ danh mục các tuyến xe hỗ trợ.
- Nhóm đã chủ động bổ sung: Quy định rõ khung giờ đo lường từ 16h30 đến 19h00 các ngày làm việc; mở rộng phạm vi dữ liệu tích hợp bao gồm cả hệ thống VinBus (E01, E03, E05) và xe buýt Transerco (27, 34, 09B).

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Đánh giá bài toán theo ma trận độ phù hợp

- **Độ mơ hồ: Thấp** (Tọa độ điểm dừng, vị trí GPS của phương tiện, thời gian đến dự kiến, lịch trình tuyến đều là các số liệu định lượng, có tính đúng/sai rõ ràng, không phụ thuộc vào cách diễn giải chủ quan).
- **Độ phức tạp: Trung bình - Cao** (Phải xử lý đồng thời 3 luồng dữ liệu biến động liên tục: vị trí xe chặng 1, vị trí các xe chặng 2 khả dĩ, và tình trạng ùn tắc trên các phân đoạn kết nối; các bước phụ thuộc chặt chẽ vào thời gian thực).

**Định vị bài toán trong ma trận:**

```text
Ô "Độ mơ hồ Thấp — Độ phức tạp Trung bình/Cao" (Phù hợp cho Kiến trúc Deterministic Data Pipeline kết hợp Dynamic Workflow).
```

**Lập luận của nhóm:**

Bài toán không yêu cầu năng lực sáng tạo ngôn ngữ hay khả năng tự chủ đưa ra quyết định mơ hồ từ mô hình AI. Cốt lõi của giải pháp là một hệ thống luồng công việc (Workflow) có khả năng liên tục đối soát các điều kiện logic dựa trên dữ liệu định lượng thời gian thực để kích hoạt cảnh báo chính xác khi xuất hiện độ lệch ngưỡng.

### 6.1. So sánh các cấp độ giải pháp: Rule / Workflow / Agent

| Cấp độ | Phương án thiết kế cho bài toán | Điều kiện đáp ứng | Rủi ro kỹ thuật | Quyết định & Phạm vi áp dụng |
|---|---|---|---|---|
| **Rule** | Thiết lập các quy tắc cố định: *"Nếu xuất phát trước 16h30, luôn đổi tại trạm Ngã Tư Sở sang xe 27; Nếu sau 17h00, luôn đổi tại trạm Kim Mã sang xe 34"*. | Chỉ đáp ứng khi giao thông diễn ra hoàn hảo theo đúng biểu đồ giờ lý thuyết (cuối tuần hoặc đêm muộn không kẹt xe). | Hoàn toàn mất tác dụng trước các biến số ngẫu nhiên như ùn tắc đột xuất, thời tiết xấu hoặc xe bỏ chuyến. | **Nhóm áp dụng làm Cơ chế Fallback:** Kích hoạt khi mất tín hiệu GPS hoặc đứt kết nối mạng. |
| **Workflow** | Pipeline tự động lấy dữ liệu GPS của cả 2 chặng; liên tục tính khoảng cách thời gian đón xe (Time Gap); nếu độ lệch vượt ngưỡng an toàn (<3 phút), kích hoạt thuật toán đánh giá các điểm chuyển tuyến dự phòng và gửi thông báo đề xuất đổi trạm cho sinh viên. | Đáp ứng trên 95% các tình huống di chuyển thực tế vì quy trình có các bước xác định rõ ràng, có ngưỡng kích hoạt minh bạch và giữ quyền quyết định cho người dùng. | Phụ thuộc vào tính ổn định của API dữ liệu giao thông bên thứ ba. | **NHÓM LỰA CHỌN LÀM GIẢI PHÁP CHỦ ĐẠO:** Đảm bảo độ trễ thấp, chi phí tối ưu và kiểm soát tuyệt đối rủi ro. |
| **Agent** | Một AI Agent hoàn toàn tự chủ, liên tục tự suy luận, tự gọi các công cụ ngoại vi (Maps API, Weather API, mạng xã hội), tự đưa ra quyết định mà không cần người dùng xác nhận. | Chỉ cần thiết khi hệ thống phải tự động điều phối phương tiện, tự đặt xe trung gian hoặc thay đổi lộ trình của xe buýt. | Phức tạp hóa bài toán không cần thiết (over-engineering), chi phí vận hành token cao, độ trễ phản hồi của LLM có thể làm lỡ mất thời điểm bấm chuông xuống xe. | **NHÓM KHÔNG LỰA CHỌN:** Gây lãng phí tài nguyên và tạo rủi ro mất kiểm soát hành trình cho người dùng. |

**5 câu hỏi thẩm định giải pháp:**
1. **Rule có giải được 70-80% trường hợp không?** Không, vì giao thông giờ cao điểm tại Hà Nội có tính biến động rất lớn; các quy tắc giờ cố định thường xuyên bị phá vỡ bởi ùn tắc tại cầu Vĩnh Tuy và đường vành đai 2.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Quy trình bắt buộc phải rẽ nhánh phụ thuộc vào điều kiện thực tế (nếu xe 1 đúng giờ → giữ nguyên lộ trình; nếu xe 1 trễ nhưng xe 2 cũng trễ → giữ nguyên; nếu xe 1 trễ mà xe 2 đúng giờ → rẽ nhánh đổi điểm chuyển tuyến hoặc đổi tuyến chặng 2).
3. **Có thật sự cần Agent tự lập kế hoạch và gọi tool không?** Không cần Agent tự chủ, vì không gian trạng thái của mạng lưới xe buýt là hữu hạn và các nhánh rẽ hoàn toàn có thể định nghĩa tường minh bằng một Dynamic Workflow có cấu trúc.
4. **Nếu hệ thống tính toán sai, ai phát hiện đầu tiên và khắc phục trong bao lâu?** Sinh viên là người phát hiện đầu tiên khi quan sát thực tế trên đường; họ chỉ mất 2 giây để bỏ qua gợi ý và tiếp tục di chuyển theo lộ trình ban đầu.
5. **Có hạ được từ Agent xuống Workflow hoặc Rule không?** Hoàn toàn khả thi. Nhóm chủ động định vị giải pháp ở mức **Workflow** có ngưỡng kích hoạt (Event-driven Workflow) kết hợp Rule dự phòng nhằm đảm bảo độ tin cậy và tốc độ xử lý nhanh nhất.

**Cấp độ giải pháp nhóm lựa chọn:**

```text
Workflow (Dynamic Event-driven Workflow with Fallback Rules)
```

**Lý do nhóm chọn giải pháp Workflow:**

Giải pháp Workflow đáp ứng chuẩn xác độ phức tạp của bài toán mà không gây lãng phí tài nguyên tính toán như Autonomous Agent. Mọi mắt xích từ thu thập tọa độ xe, tính toán độ lệch an toàn, đến kích hoạt thông báo đều vận hành theo logic rõ ràng và có thể kiểm chứng. Phương án này bảo đảm thời gian xử lý cực nhanh (dưới 1 giây) để cảnh báo kịp thời cho hành khách trước khi xe đi qua trạm rẽ, đồng thời duy trì nguyên tắc con người luôn là chủ thể ra quyết định cuối cùng (Human-in-the-loop).

**Lý do nhóm không chọn mức Rule đơn giản hơn:**

Mức Rule thuần túy không thể giải quyết được bài toán do việc di chuyển buýt liên tuyến đòi hỏi xử lý đồng thời hai thực thể chuyển động độc lập trong môi trường giao thông biến động liên tục. Các quy tắc tĩnh dựa trên giờ cố định sẽ hoàn toàn tê liệt trước những sự cố thường nhật như mưa lớn, va chạm giao thông hoặc các nút thắt cổ chai giờ tan tầm.

### 6.2. Problem Statement v1 (Bản hoàn thiện chuẩn hóa)

| Trường thông tin | Nội dung hoàn thiện |
|---|---|
| **Actor** | Sinh viên VinUni (Gia Lâm) di chuyển bằng xe buýt về khu vực Cầu Giấy/Xuân Thủy trong khung giờ cao điểm chiều (16h30 – 19h00) các ngày làm việc từ thứ Hai đến thứ Sáu. |
| **Workflow** | Khởi tạo chuyến đi → Lên xe chặng 1 (E01/E03) → Hệ thống ngầm giám sát vị trí xe 1 và xe 2 thời gian thực → Nhận thông báo điều chỉnh điểm chuyển tuyến nếu phát hiện nguy cơ lỡ xe → Xuống trạm được đề xuất tối ưu → Lên xe chặng 2 (27/34/09B/E05) → Kết thúc tại Xuân Thủy. |
| **Bottleneck** | Thời gian chờ đợi bị dồn ứ từ 15 đến 25 phút tại trạm trung chuyển do xe chặng 1 bị ùn tắc làm lỡ mất nhịp chuyến xe chặng 2, trong khi hành khách thiếu thông tin dự báo để đổi trạm đón sớm hơn. |
| **Impact** | Gây lãng phí 25–40 phút mỗi chuyến đi, đẩy tổng thời gian hành trình lên 95–110 phút, gây mệt mỏi thể chất, căng thẳng tâm lý và làm chậm trễ các lịch trình cá nhân buổi tối. |
| **Success Metric** | Giảm thời gian chờ đợi chuyển tuyến xuống dưới 8 phút (baseline: 20 phút); giảm tổng thời gian hành trình trung bình xuống dưới 75 phút (baseline: 95 phút); tỷ lệ bắt xe chặng 2 thành công trong vòng 7 phút đạt trên 85%. |
| **Boundary (Phạm vi)** | **TRONG PHẠM VI:** Giám sát dữ liệu GPS thời gian thực của các cặp tuyến VinBus (E01, E03) và Transerco (27, 34, 09B, E05); tính toán độ lệch thời gian tại các trạm trung chuyển trọng điểm (Ngã Tư Sở, Cầu Giấy, Kim Mã, Royal City); gửi cảnh báo đổi trạm trước ít nhất 5 phút.<br>**NGOÀI PHẠM VI:** Không đặt vé, không can thiệp lộ trình vận hành của xe buýt, không tích hợp các phương tiện ngoài xe buýt (taxi, xe ôm), không giải quyết vấn đề xe buýt hết chỗ ngồi. |
| **AI intervention point** | Can thiệp ở **giữa Bước 4 (khi xe 1 đang di chuyển) và trước Bước 5 (trước khi đến trạm chuyển tuyến ít nhất 2 trạm dừng)**. Hệ thống phân tích độ lệch ETA để quyết định xem có cần can thiệp đổi trạm trung chuyển hay không. |
| **Mức giải pháp lựa chọn** | **Workflow** — Kết hợp Data Pipeline kiểm tra khoảng cách an toàn giữa 2 xe với Dynamic Routing logic; không dùng Agent tự chủ nhằm tối ưu tốc độ và độ tin cậy. |
| **Rủi ro & Giám sát con người** | **Rủi ro:** Dữ liệu GPS của xe buýt bị gián đoạn hoặc trả về tọa độ sai lệch khiến hệ thống gợi ý trạm dừng không phù hợp.<br>**Giám sát con người:** Sinh viên trực tiếp nhận thông báo kèm đầy đủ thông tin đối chiếu (*"Xe 27 cách trạm 1.2km - khoảng 4 phút nữa tới. Bạn có muốn xuống sớm tại trạm Royal City không?"*) và chủ động quyết định bấm chuông xuống xe. |

### 6.3. Quyết định triển khai cuối cùng (Final Decision)

| Tiêu chí thẩm định | Kết luận | Lập luận chi tiết |
|---|:---:|---|
| Đối tượng và quy trình rõ ràng? | **Yes** | Đối tượng sinh viên VinUni đi về Xuân Thủy xác định rõ; luồng quy trình 7 bước trước và sau tối ưu minh bạch. |
| Dữ liệu ban đầu và chỉ số đo được? | **Yes** | Baseline thời gian chờ 20 phút, tổng thời gian 95 phút đo bằng đồng hồ bấm giờ; mục tiêu giảm xuống <8 phút và <75 phút khả thi. |
| Nguồn dữ liệu đầu vào sẵn sàng? | **Yes** | Khai thác API và dữ liệu công khai từ BusMap và timbus.vn cho các tuyến E01, E03, 27, 34. |
| Hậu quả khi hệ thống sai chấp nhận được? | **Yes** | Trường hợp xấu nhất, sinh viên tiếp tục đi đến trạm trung chuyển cũ và chờ xe bình thường, không gây rủi ro an toàn hay tài chính. |
| Có sự giám sát của con người? | **Yes** | Sinh viên là người trực tiếp nhận thông báo và đưa ra quyết định bấm chuông xuống xe hay ngồi tiếp. |
| Đã có giải pháp Non-AI đơn giản hơn? | **Yes (nhưng không tối ưu)** | Cách tra cứu tĩnh truyền thống chính là nguyên nhân gây ra điểm nghẽn hiện tại do con người không thể tự tính toán biến số của hai phương tiện cùng lúc trên đường. |

**Quyết định của nhóm:**

```text
[Go]
```

**Cơ sở nhóm đưa ra quyết định:**

Dự án hội tụ đầy đủ các điều kiện tiên quyết để triển khai: bài toán giải quyết nhu cầu có thật với điểm nghẽn đo lường được bằng số liệu thực nghiệm; nguồn dữ liệu đầu vào (GPS xe buýt và luồng giao thông) đã sẵn sàng và khả thi. Việc nhóm lựa chọn cấp độ **Workflow** giúp loại bỏ sự cồng kềnh của các mô hình AI tạo sinh, tập trung vào tốc độ xử lý và tính chính xác của quyết định. Rủi ro sai số dữ liệu được kiểm soát an toàn nhờ cơ chế Human-in-the-loop và Fallback Rules chặt chẽ.

**Kế hoạch thử nghiệm quy mô nhỏ (Pilot Plan):**

```text
- Phạm vi dữ liệu: Tập trung trên trục hành trình từ VinUni về Xuân Thủy với 2 cặp tuyến chủ đạo: Cặp A (E01 chuyển sang 27 tại Ngã Tư Sở) và Cặp B (E03 chuyển sang 34 tại Kim Mã/Cầu Giấy).
- Phương pháp thực nghiệm (Wizard of Oz / Bán tự động): Bạn Dũng trực tiếp di chuyển trên tuyến đường, bạn Huy tại nhà giám sát màn hình định vị GPS của 2 xe qua timbus.vn; khi nhận diện xe chặng 1 bị chậm tại cầu Vĩnh Tuy có nguy cơ lỡ xe 27, Huy nhắn tin thông báo Dũng xuống sớm tại trạm Times City để bắt xe E05 chạy thẳng về Cầu Giấy.
- 3 chỉ số cốt lõi cần đo lường:
  1. Thời gian chờ đợi thực tế tại điểm chuyển tuyến (phút).
  2. Tổng thời gian hoàn thành chuyến đi từ VinUni về Xuân Thủy (phút).
  3. Độ chính xác và kịp thời của thời điểm cảnh báo (thông báo gửi trước điểm xuống xe bao nhiêu phút).
```

**Kế hoạch dự phòng và tiêu chí dừng (Exit / Rollback Strategy):**

```text
Nhóm lập tức dừng thử nghiệm và quay về phương thức tra cứu thông thường nếu:
1. Tỷ lệ mất tín hiệu hoặc gián đoạn dữ liệu GPS của các tuyến xe buýt vượt quá 30% tổng số chuyến thử nghiệm.
2. Khuyến nghị của hệ thống dẫn đến việc hành khách bị lỡ xe hoặc làm tăng tổng thời gian di chuyển so với lộ trình cũ từ 2 chuyến trở lên.
```

---

### Bảng tự kiểm tra chất lượng báo cáo nhóm
- [x] Đầy đủ nhật ký hội tụ từ 15 ý tưởng về 1 đề tài (phân cụm, rút gọn, chấm điểm đồng thuận).
- [x] Có dữ liệu kiểm chứng người dùng (trích dẫn phỏng vấn thật) và nghiên cứu giải pháp hiện có kèm liên kết kiểm chứng.
- [x] Luồng quy trình trước/sau thể hiện rõ thời gian, điểm nghẽn, ranh giới con người và phương án dự phòng.
- [x] Problem Statement hoàn thiện chuẩn 9 trường thông tin với chỉ số đo lường và ranh giới rõ ràng.
- [x] So sánh thấu đáo các cấp độ Rule / Workflow / Agent và đưa ra quyết định Go có cơ sở thực nghiệm vững chắc.
