# BÀI TẬP: ĐỌC LẠI BURNDOWN CHART SPRINT ĐẶT XE GHÉP

## Phần 1 - Phân tích

Bảng phân tích 4 nhận định về Burndown Chart Sprint 1:

| Nhận định | Đúng/Sai | Dẫn chứng số liệu (so với đường lý tưởng tại ngày cụ thể) | Cách hiểu đúng |
|---|---|---|---|
| N1. Trục dọc của biểu đồ thể hiện số giờ làm việc mà đội đã dùng. | Sai | Quy tắc nghiệp vụ số 3 nêu rõ: "Trục Y: khối lượng công việc còn lại (Story Points)". | Trục dọc của biểu đồ Burndown thể hiện khối lượng công việc còn lại (Remaining Work) tính bằng Story Points, không phải số giờ làm việc đã dùng. |
| N2. Đường lý tưởng giảm đều 4 điểm mỗi ngày và chạm 0 vào ngày 10. | Đúng | Tổng khối lượng cam kết là 40 Story Points trong 10 ngày Sprint. Đường lý tưởng giảm đều 40 / 10 = 4 Story Points mỗi ngày, đạt 0 vào ngày cuối Sprint (ngày 10). | Nhận định này hoàn toàn chính xác theo quy ước của Burndown Chart lý tưởng. |
| N3. Từ ngày 2 đến ngày 5, đường thực tế đi ngang, chứng tỏ đội đang làm việc rất ổn định. | Sai | Thực tế: Ngày 2 (36 SP), Ngày 3 (36 SP), Ngày 4 (36 SP), Ngày 5 (36 SP). Đường lý tưởng tại các ngày này lần lượt là 32, 28, 24, 20 SP. | Đường thực tế đi ngang trong nhiều ngày liên tiếp (từ ngày 2 đến ngày 5) cho thấy không có Story Point nào được hoàn thành và đánh dấu "Done". Đây là dấu hiệu đội đang bị trì trệ, gặp khó khăn hoặc bị chặn, chứ không phải là đang làm việc ổn định hay hiệu quả. |
| N4. Suốt Sprint, đường thực tế luôn nằm dưới đường lý tưởng nên đội đang nhanh hơn kế hoạch. | Sai | Tại Ngày 5: Đường thực tế là 36 SP, đường lý tưởng là 20 SP. Tại Ngày 10 (kết thúc Sprint): Đường thực tế là 20 SP, đường lý tưởng là 0 SP. | Đường thực tế luôn nằm *trên* đường lý tưởng (ngoại trừ ngày 0) và kết thúc Sprint với 20 Story Points còn lại thay vì 0, chứng tỏ đội đang *chậm hơn* kế hoạch và có nguy cơ cao không đạt được Sprint Goal. |

## Phần 2 - Vá lỗi

Đối với các nhận định sai, dưới đây là các hiện tượng và hành động cần làm:

1.  **Hiện tượng**: Nhận định N1 sai về ý nghĩa trục dọc của Burndown Chart.
    *   **Hành động**: Scrum Master cần đào tạo lại cho thành viên mới và toàn đội về cách đọc và ý nghĩa chuẩn của Burndown Chart, nhấn mạnh trục Y biểu thị khối lượng công việc còn lại tính bằng Story Points. 
    *   **Ai chịu trách nhiệm**: Scrum Master.
    *   **Thực hiện vào lúc nào**: Ngay trong buổi Daily Scrum hoặc Sprint Retrospective đầu tiên sau khi nhận báo cáo, hoặc trong một buổi đào tạo ngắn gọn. 

2.  **Hiện tượng**: Nhận định N3 sai khi hiểu đường thực tế đi ngang là ổn định, trong khi đây là dấu hiệu trì trệ.
    *   **Hành động**: Các Developers cần thảo luận trong Daily Scrum để xác định nguyên nhân cụ thể khiến công việc không được hoàn thành (ví dụ: bị chặn, gặp vấn đề kỹ thuật phức tạp, định nghĩa "Done" chưa rõ ràng), đề xuất giải pháp và điều chỉnh lại kế hoạch Sprint. Scrum Master cần hỗ trợ đội gỡ bỏ các vật cản kịp thời.
    *   **Ai chịu trách nhiệm**: Developers (tìm nguyên nhân và giải pháp), Scrum Master (gỡ bỏ vật cản).
    *   **Thực hiện vào lúc nào**: Ngay lập tức từ Ngày 3 hoặc Ngày 4, khi quan sát thấy đường thực tế vẫn đi ngang, trong buổi Daily Scrum để kịp thời điều chỉnh kế hoạch Sprint.

3.  **Hiện tượng**: Nhận định N4 sai khi cho rằng đội nhanh hơn kế hoạch, trong khi thực tế đường Burndown cho thấy đội đang chậm và có nguy cơ không đạt Sprint Goal.
    *   **Hành động**: Các Developers cần rà soát lại các User Story chưa hoàn thành, đánh giá lại khả năng hoàn thành trong thời gian còn lại, và tập trung vào các Story có giá trị cao nhất. Product Owner cần được thông báo về tình hình rủi ro không đạt Sprint Goal để có thể cân nhắc các điều chỉnh cần thiết (mặc dù thay đổi phạm vi Sprint giữa chừng không được khuyến khích). Scrum Master cần theo dõi sát sao tiến độ và hỗ trợ đội trong việc điều chỉnh kế hoạch.
    *   **Ai chịu trách nhiệm**: Developers (điều chỉnh kế hoạch và tập trung công việc), Product Owner (xem xét phạm vi Sprint nếu cần), Scrum Master (hỗ trợ và theo dõi).
    *   **Thực hiện vào lúc nào**: Liên tục trong các buổi Daily Scrum từ giữa Sprint (ví dụ: từ Ngày 5 hoặc Ngày 6) khi khoảng cách giữa đường thực tế và đường lý tưởng đã rõ ràng và không có dấu hiệu cải thiện, để có thể đưa ra các điều chỉnh chiến lược kịp thời trước khi Sprint kết thúc.