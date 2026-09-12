# 03 — Individual Reflection

## Thông tin cá nhân

- Họ và tên: Hoàng Quốc Dũng
- Mã học viên: 2A202602523
- Nhóm: Tối ưu xe bus
- Candidate problem nhóm chọn: Tối ưu lựa chọn và điều chỉnh cặp tuyến xe buýt thời gian thực (ví dụ từ VinUni (Gia Lâm) về Xuân Thủy (Cầu Giấy)) nhằm giảm thiểu thời gian chờ đợi và chuyển tuyến.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự rà soát lại 10 vấn đề từ cuộc sống sinh viên và học tập cá nhân, đo đếm số liệu thực tế về thời gian di chuyển buýt. | Đóng góp 3 bài toán chất lượng cao vào danh sách 15 candidates của cả nhóm. |
| Pitch Problem Card | Đứng ra pitch chi tiết Problem Card #1 về hành trình xe buýt VinUni — Xuân Thủy trong 2 phút, nêu rõ con số lãng phí 25–40 phút tại điểm chuyển tuyến. | Thuyết phục cả nhóm nhận thấy đây là bài toán có pain cực kỳ nhức nhối, đo đếm được rõ ràng bằng phút. |
| Challenge bài của bạn khác | Đặt câu hỏi phản biện bài viết nhận xét học sinh của Tiến Anh (về tính đo lường chất lượng lời khen) và bài tìm tài liệu của Sơn (về việc giải pháp No-AI tái cấu trúc file đã đủ tốt chưa). | Giúp nhóm nhận diện rõ ranh giới giữa vấn đề cần AI và vấn đề chỉ cần cải tiến quy trình hoặc công cụ thông thường. |
| Gom trùng / cluster | Đề xuất gộp 4 bài toán di chuyển của tôi và Huy thành Cụm A (Tối ưu di chuyển & xe buýt đa chặng). | Giúp nhóm nhanh chóng quy tụ từ 15 ý tưởng phân tán thành 4 cụm chủ đề mạch lạc. |
| Chọn candidate problem | Cung cấp dữ liệu thực tế về các trạm chuyển tuyến (Ngã Tư Sở, Kim Mã) để nhóm chấm điểm 34/35 cho Candidate #13. | Nhóm đạt được sự đồng thuận tuyệt đối (consensus) để chọn bài toán xe buýt làm đề tài chung. |
| Validation / research | Cùng Huy khảo sát 8 bạn sinh viên và tra cứu các ứng dụng hiện hành (BusMap, timbus.vn, Google Maps). | Xác thực được insight quan trọng: người dùng không thiếu bản đồ tĩnh, mà thiếu cơ chế cảnh báo điều chỉnh tuyến động. |
| Workflow nhóm | Vẽ luồng Current State (95 phút) và Future State (68 phút), chỉ rõ điểm nghẽn ở Bước 5 và ranh giới con người ở Bước 5 mới. | Toàn nhóm có cùng một bức tranh trực quan về sự can thiệp của hệ thống vào quy trình di chuyển. |
| Problem Statement | Viết bản thảo Problem Statement v0, sau đó tiếp thu phản biện của Điềm để siết chặt khung giờ cao điểm và phạm vi tuyến ở v1. | Problem Statement đạt chuẩn khắt khe: có baseline cụ thể, có boundary rõ ràng và có điểm can thiệp chính xác. |
| Rule / Workflow / Agent | Tranh luận trực tiếp với nhóm để bảo vệ quan điểm: bài này chỉ nên dừng ở mức **Workflow**, không nhảy lên làm Agent tự chủ. | Nhóm tránh được cái bẫy "làm Agent cho ngầu", tiết kiệm chi phí tính toán và kiểm soát được rủi ro sai số dữ liệu. |
| Decision | Thiết kế kịch bản thử nghiệm nhỏ (Pilot Wizard of Oz) giữa tôi (đi trên đường) và Huy (theo dõi màn hình GPS). | Đưa ra quyết định Go thuyết phục, có phương án kiểm chứng thực tế và có tiêu chí rollback cụ thể. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

Dấu tay rõ nhất của tôi là việc khởi xướng bài toán xe buýt VinUni — Xuân Thủy, trực tiếp thiết kế luồng Before/After Workflow với điểm nghẽn chuyển tuyến (Bước 5), và kiên quyết định hướng nhóm lựa chọn mức độ giải pháp là **Workflow** thay vì bị cuốn theo việc xây dựng AI Agent tự chủ quá phức tạp.

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Brainstorm thêm góc nhìn về các vấn đề tốn thời gian quanh đời sống sinh viên. | Gợi ý được từ khóa "Interchange delay" (độ trễ tại điểm chuyển tuyến) giúp tôi định hình rõ hơn pain point. | Gợi ý những ý tưởng rất viển vông, phi thực tế như "AI gợi ý trang phục sinh viên theo thời tiết". | Gạt bỏ toàn bộ các gợi ý hời hợt, chỉ giữ lại các vấn đề bản thân thực sự trải qua và có số liệu bấm giờ thật. |
| Problem Card | Đóng vai một Product Manager khó tính để phản biện Problem Card #1. | Chỉ ra rằng tôi chưa làm rõ rủi ro khi hệ thống phụ thuộc hoàn toàn vào API dữ liệu bên ngoài. | Nhận xét máy móc rằng đề tài "quá hẹp vì chỉ phục vụ một tuyến đường đơn lẻ". | Tôi phản biện lại: Tuyến đường này là bài toán đại diện (representative case) cho toàn bộ mô hình xe buýt liên tuyến xuyên tâm, hoàn toàn có thể mở rộng sau khi pilot thành công. |
| Workflow | Nhờ AI format lại sơ đồ khối sang dạng Mermaid và text-based pipeline. | Giúp cấu trúc hóa các bước thành chuỗi tuần tự rất gọn gàng và dễ nhìn. | AI tự tiện thêm bước "AI tự động thanh toán vé xe buýt điện tử" vào workflow tương lai. | Xóa bỏ ngay bước này vì xe buýt Hà Nội hiện tại dùng vé giấy hoặc thẻ từ riêng biệt, việc AI tự thanh toán là bất khả thi và vi phạm boundary. |
| Research | Tìm kiếm các giải pháp hoặc bài báo nghiên cứu về "Dynamic bus re-routing algorithm". | Cung cấp tổng quan về các thuật toán tìm đường động dựa trên trọng số đồ thị biến đổi. | AI trích dẫn một số con số thống kê về độ chính xác của GPS xe buýt Hà Nội nhưng không đưa được nguồn dẫn chứng xác thực. | Tự mình truy cập trang chủ timbus.vn và tải app BusMap về điện thoại để kiểm tra trực tiếp tính năng thực tế. |
| Problem Statement | Nhờ AI rà soát xem giữa v0 và v1 có câu từ nào còn mơ hồ, chung chung không. | Phát hiện ra từ "nhanh hơn" ở phần metric chưa có mốc thời gian (baseline) để so sánh. | AI đề xuất đặt mục tiêu "giảm 80% thời gian di chuyển" — một con số phi thực tế đối với giao thông công cộng. | Tự sửa lại mục tiêu khả thi: giảm thời gian chờ chuyển tuyến từ 20 phút xuống dưới 8 phút dựa trên tần suất xe thực tế. |
| Rule / Workflow / Agent | Hỏi AI ưu/nhược điểm khi dùng Autonomous Agent trong bài toán giao thông công cộng. | Liệt kê đầy đủ các rủi ro về chi phí vận hành token và độ trễ phản hồi (latency). | AI vẫn thiên vị và cố lái nhóm chọn mô hình "Multi-Agent System" để phân tích đa nguồn tin tức. | Bác bỏ hoàn toàn gợi ý Multi-Agent của AI; cùng nhóm thống nhất chốt giải pháp dừng lại ở mức **Workflow** có điều kiện logic. |
| Decision | Gợi ý các tiêu chí để thiết lập kịch bản Rollback / Exit an toàn. | Gợi ý tiêu chuẩn về ngưỡng lỗi dữ liệu (data failure threshold) rất hữu ích. | Đưa ra các bước thử nghiệm phức tạp đòi hỏi phải code backend hoàn chỉnh. | Tự thiết kế phương pháp kiểm thử bán tự động (Wizard of Oz) bằng tay giữa 2 người bạn để xác thực bài toán mà không tốn công lập trình trước. |

---

## 3. Reflection câu hỏi mở

Sau buổi lab Day 02 tôi thấy cách nhìn về một vấn đề của mình đã thay đổi khá nhiều. Khi nghe top 3 problems của các bạn trong nhóm tôi nhận ra có nhiều vấn đề nghe qua thì tưởng cần dùng AI nhưng thực ra chỉ cần sửa lại quy trình hoặc dùng một script đơn giản là được. Ví dụ như việc kiểm tra repo GitHub hay tìm tài liệu học tập nếu có checklist rõ ràng thì cũng giải quyết được phần lớn rồi. Đến Phase 6 nhóm tôi cũng có lúc nghĩ đến việc dùng Agent để hệ thống tự suy luận và đưa ra quyết định vì nghe có vẻ hiện đại hơn. Nhưng sau khi thảo luận thì tôi cùng anh Huy và anh Điềm nhận thấy bài toán xe buýt cần phản hồi nhanh để người dùng còn kịp xuống trạm, nên Workflow kết hợp với Rule dự phòng sẽ hợp lý hơn. Phần khó nhất đối với tôi khi viết Problem Statement là xác định Boundary tức là hệ thống sẽ làm gì và không làm gì. Ban đầu tôi muốn hệ thống dự báo cả việc xe buýt còn chỗ trống hay không nhưng nhóm challenge rằng hiện tại chưa có dữ liệu đủ tin cậy để làm việc đó. Vì vậy tôi bỏ tính năng này để phạm vi bài toán thực tế hơn và không bị quá rộng. Đóng góp chính của tôi là đưa ra vấn đề di chuyển từ VinUni về Xuân Thủy, xây dựng workflow trước và sau  đồng thời cùng nhóm xác định bottleneck ở bước chuyển tuyến. Nếu được làm lại tôi sẽ challenge nhóm sớm hơn ở những vấn đề còn chung chung hoặc chưa có số liệu để đỡ mất thời gian trong bước hội tụ.


---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards (đã có 10 problems scan + 3 Problem Cards chi tiết)
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

