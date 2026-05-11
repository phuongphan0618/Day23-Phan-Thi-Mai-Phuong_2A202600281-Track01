# Bài 2 — Nghiên Cứu Case Thành Công/Thất Bại

### Bảng so sánh case study

| Trường | Case thành công: Morgan Stanley | Case thất bại/cảnh báo: JPMorgan Dashboard |
|--------|----------------------------------|-------------------------------------------|
| **Case** | Morgan Stanley Wealth Management AI Deployment | JPMorgan "Bossware" Surveillance Dashboard |
| **Nguồn dữ liệu** | OpenAI case study (2024), Morgan Stanley Internal Reports | Business Insider, Fortune, Financial Times (2024-2026) |
| **AI được dùng trong quy trình (workflow) nào?** | AI @ Morgan Stanley Assistant (chatbot nội bộ) + AI Debrief (tóm tắt cuộc họp). Giúp cố vấn truy cập 100.000 tài liệu nội bộ nhanh hơn, tóm tắt báo cáo, tăng tương tác khách hàng. | "Bossware" theo dõi giờ làm, keystrokes, video calls, meetings của nhân viên. Giám sát nhân viên có "có mặt" tại máy tính, so sánh giờ tự khai với dữ liệu IT. |
| **Họ đo chỉ số (metric) gì?** | - 98% đội ngũ cố vấn sử dụng AI hàng ngày<br>- 20% → 80% tỷ lệ truy cập tài liệu<br>- Thời gian tìm tài liệu: 20 phút → vài giây | - Số giờ làm việc tích cực (self-reported vs IT data)<br>- Tần suất mở ứng dụng AI<br>- Keystrokes, video calls, meetings/tuần |
| **Chỉ số chứng minh được gì?** | - AI giúp chuyên gia tra cứu 100.000 tài liệu hiệu quả (80% adoption)<br>- "Friction giữa kiến thức và giao tiếp về 0" – Jeff McMillan, Head of Firmwide AI<br>- Follow-up từ vài ngày → vài giờ | - Nhân viên có đang ngồi tại máy tính hay không<br>- AI theo dõi dữ liệu thô ở quy mô 65.000 kỹ sư<br>- Banker tự khai giờ so với footprint điện tử |
| **Chỉ số chưa chứng minh được?** | - Chưa chứng minh khách hàng chốt hợp đồng nhiều hơn do AI (chưa có data conversion rate/AUM growth)<br>- Chưa đo chất lượng lời khuyên tài chính thực sự | - Không chứng minh chất lượng công việc<br>- Nhân viên có thể "spam email" hoặc treo máy để làm đẹp chỉ số (Vanity Metrics)<br>- Không đo năng suất thực, chỉ đo "activity" |
| **Thiếu chỉ số nào?** | - Confidence Score: Sự tự tin của cố vấn khi dùng AI<br>- Client Conversion Rate: Tỷ lệ chuyển đổi khách hàng sau khi dùng AI<br>- Trust in AI: 93% cố vấn muốn giữ quyền kiểm soát quyết định | - Employee Morale/Motivation: Phản ứng tinh thần của nhân viên<br>- Quality of Work: Chất lượng phân tích, độ chính xác<br>- Trust & Creativity: Bị giám sát quá mức gây Resentment (chống đối), giảm động lực |
| **Kết quả thực tế** | - 74% cố vấn xác nhận AI hỗ trợ tốt công việc<br>- 39% cần peer-test evidence để tin tưởng hoàn toàn<br>- Tốc độ phản hồi khách hàng cải thiện rõ rệt | - "Big Brother bank" – Ariel Zilber (NY Post)<br>- Resentment: Nhân viên lo lắng bị giám sát kiểu Orwell's 1984<br>- 10% back-office bị thay thế bởi AI |
| **Bài học cho dashboard của nhóm** | Tập trung vào **Trust Architecture** và **Expert Feedback Loop**. Đo giá trị gia tăng cho người dùng cuối. | Tránh bẫy **Activity-based metrics**. Giám sát quá mức sẽ tạo ra con số ảo (Vanity Metrics) và làm giảm Motivation. |

---

### Câu chốt của nhóm (Synthesis)
Tránh bẫy **"Activity-based metrics"** (đo hoạt động) của JPMorgan. Dashboard của nhóm phải tập trung đo **"Outcome-based metrics"** (giá trị đầu ra) và **Trust** (sự tin tưởng). 

Việc giám sát quá mức (Bossware) không chỉ giết chết sự sáng tạo mà còn tạo ra rủi ro **"Resentment"** (chống đối), khiến nhân viên tối ưu các con số ảo thay vì tập trung vào năng suất thực tế. Nhóm sẽ áp dụng cơ chế **"Expert feedback loop"** như Morgan Stanley để AI thực sự là trợ lý thay vì là công cụ giám sát.