# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Bùi Đình Đề
- Mã học viên: 2A202602818
- Nhóm: Nhóm 02
- Candidate problem nhóm chọn: Tra cứu quy chế, thủ tục học vụ từ Sổ tay sinh viên PDF dài hơn 100 trang

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi scan 9 vấn đề trong công việc thanh toán viện phí, tập trung vào đọc hồ sơ, đối chiếu bảo hiểm và giải trình. | Cung cấp các candidate có actor, workflow và số đo cụ thể; nổi bật là phát hiện cận lâm sàng thiếu chẩn đoán và soạn thư giải trình. |
| Pitch Problem Card | Tôi pitch bài toán soạn thư giải trình cho ca bị bảo hiểm từ chối, với thời gian xử lý ước tính 30–45 phút mỗi ca và khoảng 10–15 ca mỗi tuần. | Bài toán được đưa vào danh sách candidate để nhóm so sánh với các vấn đề khác; các số liệu được ghi là ước tính cần xác minh. |
| Challenge bài của bạn khác | Tôi đặt câu hỏi về độ tin cậy của số liệu 50–70 email CTSV/ngày và rủi ro khi AI trả lời sai quy chế. | Nhóm ghi rõ đây là giả định chưa xác nhận và chọn Not Yet thay vì kết luận Go quá sớm. |
| Gom trùng / cluster | Tôi góp ý nhận diện các bài toán có cùng pattern tổng hợp thông tin, tra cứu tài liệu và automation. | Nhóm gom được các candidate thành bốn cluster và loại những bài chỉ cần Rule hoặc process fix. |
| Chọn candidate problem | Tôi đồng ý chọn bài tra cứu quy chế vì workflow rõ, có tài liệu nguồn và dễ thử nghiệm hơn bài toán y tế. | Nhóm thu hẹp scope từ các ý tưởng rộng về một quy trình RAG có escalation. |
| Validation / research | Tôi tham gia rà soát các precedent RAG/chatbot giáo dục và các điểm mạnh, khoảng trống, rủi ro của từng hướng. | Nhóm có cơ sở chọn Workflow thay vì Agent, đồng thời ghi nhận validation người thật chưa thực hiện được. |
| Workflow nhóm | Tôi góp ý phân biệt bước sinh viên tự tra cứu với bước gửi email cho CTSV và làm rõ fallback khi AI không chắc chắn. | Workflow trước/sau thể hiện bottleneck, AI boundary và đường chuyển sang người thật. |
| Problem Statement | Tôi góp ý chốt metric, boundary và cách ghi nhãn các số liệu chưa xác nhận. | Problem Statement v1 không cho AI tự quyết ngoại lệ và gắn rõ CTSV là người review. |
| Rule / Workflow / Agent | Tôi cùng nhóm so sánh FAQ tĩnh, RAG pipeline và Agent tự gọi nhiều nguồn. | Nhóm chọn Workflow vì luồng nhận câu hỏi → retrieve → trả lời có nguồn → escalate là tuyến tính. |
| Decision | Tôi ủng hộ quyết định Not Yet vì baseline và quy trình review chưa đủ bằng chứng. | Decision giữ được tính thận trọng, kèm ba việc cần validate trước pilot. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text

Tôi đóng góp góc nhìn kiểm soát rủi ro và nghiên cứu precedent: không coi việc có thể dùng LLM là đủ để Go,
mà yêu cầu nguồn trích dẫn, escalation và người chịu trách nhiệm review. Dấu tay rõ nhất là việc nhóm ghi
con số 50–70 email/ngày là giả định chưa xác nhận và chuyển decision cuối thành Not Yet.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý thêm các góc nhìn để mở rộng danh sách vấn đề. | Giúp tôi không chỉ nhìn vào lỗi nghiệp vụ mà còn nghĩ đến việc lặp lại, tốn thời gian và pain của người khác. | Một số gợi ý có xu hướng nhảy ngay sang chatbot hoặc Agent, chưa có bằng chứng pain. | Tôi giữ lại những vấn đề có actor, workflow và số đo; bỏ ý tưởng chỉ bắt đầu từ solution. |
| Problem Card | Gợi ý câu hỏi phản biện cho bài toán soạn thư giải trình và rà lại fallback. | Giúp tôi nhận ra OCR sai có thể biến thành hallucination trong văn bản gửi bảo hiểm. | AI không thể tự xác nhận quy định bảo hiểm hay trách nhiệm pháp lý trong domain y tế. | Tôi giới hạn phạm vi vào nhóm ca có dữ liệu rõ và yêu cầu người thật kiểm tra trước khi gửi. |
| Workflow | Hỗ trợ kiểm tra cách diễn đạt workflow trước/sau. | Giúp làm rõ bottleneck và vị trí human boundary. | AI dễ mô tả luồng quá lý tưởng, bỏ qua dữ liệu thiếu hoặc không đọc được. | Tôi bổ sung fallback và chuyển các ca không chắc chắn về người phụ trách. |
| Research | Gợi ý các pattern RAG/chatbot giáo dục để tìm nguồn tham khảo. | Giúp nhóm nhanh chóng so sánh Rule, Workflow và Agent. | Một số claim về hiệu quả có thể đến từ nguồn vendor hoặc chưa đủ context. | Tôi không dùng precedent thay cho validation; nhóm ghi rõ số liệu CTSV là giả định chưa xác nhận. |
| Problem Statement | Rà xem actor, metric và boundary có mâu thuẫn không. | Giúp phát hiện metric 40% và 50–70 email/ngày chưa có baseline thật. | AI có thể khiến câu chữ nghe chắc chắn hơn bằng chứng hiện có. | Tôi yêu cầu ghi rõ giả định, cách đo trong pilot và điều kiện escalation. |
| Rule / Workflow / Agent | Liệt kê ưu, nhược điểm của FAQ, RAG pipeline và Agent. | Giúp so sánh ba mức trên cùng một bài toán thay vì mặc định chọn Agent. | AI thường đánh giá Agent là mạnh hơn dù workflow thực tế tuyến tính. | Tôi dựa vào số nhánh và nhu cầu tự quyết định bước tiếp theo để chọn Workflow. |
| Decision | Rà các điều kiện Go/Not Yet/No-Go. | Giúp nhóm không bỏ sót data owner, rủi ro và rollback. | AI không thể thay nhóm quyết định mức rủi ro chấp nhận được cho quy chế học vụ. | Tôi giữ quyết định Not Yet và nêu ba kiểm chứng bắt buộc trước pilot. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text

Khi nghe top 3 problems của các bạn, tôi học được rằng một problem nghe rất hữu ích
chưa chắc là bài phù hợp nhất để làm trong lab. Các bài về automation mật khẩu hoặc cấp
quyền GitHub có thể giải bằng Rule, còn bài đọc tài liệu và tổng hợp thông tin mới cần
xem xét AI ở đúng một bước. Ban đầu tôi nghiêng về các bài toán thanh toán viện phí vì
đó là domain tôi hiểu, nhưng sau khi nghe challenge về dữ liệu và trách nhiệm pháp lý,
tôi đồng ý không chọn bài y tế làm candidate của nhóm. Tôi đóng góp thật sự vào artifact
cuối ở phần research, nhận diện rủi ro và làm rõ rằng 50–70 email CTSV/ngày chỉ là giả
định. Điều khó nhất khi viết Problem Statement là tách pain quan sát được khỏi metric
chưa đo, đồng thời đặt boundary để chatbot không biến thành người quyết định thủ tục.
Nhóm có lúc dễ bị solution-first khi gọi tên RAG hoặc Agent trước khi có validation,
nhưng workflow tuyến tính giúp chúng tôi hạ lựa chọn từ Agent xuống Workflow. Tôi thấy
AI hữu ích để gợi ý phản biện và cấu trúc so sánh, nhưng AI không thể xác nhận thay
người thật các con số hay mức độ an toàn của câu trả lời quy chế. Nếu làm lại, tôi sẽ
challenge nhóm sớm hơn về việc phỏng vấn CTSV và bấm giờ sinh viên, thay vì chỉ ghi nhận
đây là việc cần làm ở cuối. Bài học quan trọng nhất của tôi là phải nối được problem,
workflow, metric, boundary và owner review trước khi nói một giải pháp AI là khả thi. Khi nhìn lại
phần scan của mình, tôi cũng thấy các con số như 5–8% hồ sơ bị từ chối hay 10–15 ca tranh chấp
chỉ nên được xem là ước lượng ban đầu cho đến khi có log xác nhận.
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
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
