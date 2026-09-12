# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Bùi Đình Đề
- Mã học viên: 2A202602818
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Là nhân viên thanh toán viện phí, thanh toán khoảng 200 hồ sơ 1 ngày với nhiều hạng mục có chi trả nhiều loại bảo hiểm khác nhau.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    -Tiếp nhận hồ sơ của từng bệnh nhân, lọc các giấy tờ liên quan đến hạng mục y tế sử dụng và bảng kê chi phí.
    -Liệt kê hợp đồng của nhiều loại bảo hiểm kê ra các hạng mục bảo hiểm thanh toán.
    -Tìm và đối chiếu với bảng chi phí để thực hiện khấu trừ.
    -Gửi bản tạm kê đã khấu trừ cho các bên xác nhận.
    -Nếu có lỗi soát lại và bổ xung.
    -Hoàn tất hồ sơ thanh toán viện phí cho bệnh nhân.
    

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Lặp lại |Lặp lại thao tác đọc bảng chi phí và lọc từng nhóm. |Nhân viên thanh toán |Nhiều bộ hồ sơ phải đọc lặp đi lặp lại nhiều lần trung bình 200 bộ/ ngày |
| 2 |Lặp lại |Những hạng mục thanh toán giống nhau như cùng 1 loại thuốc, 1 loại dịch vụ cho nhiều loại bảo hiểm của nhiều bệnh nhân sử dụng dịch vụ tương tự |Nhân viên thanh toán|Có những bệnh nhân cùng 1 loại bệnh khoảng 20-30 bộ hồ sơ/ngày |
| 3 |Tốn thời gian |Đọc hiểu và tra cứu thông tin hợp đồng bảo hiểm của nhiều loại bảo hiểm khác nhau |Nhân viên thanh toán |Có nhiều bệnh nhân sử dụng trên 2 loại bảo hiểm |
| 4 |Tốn thời gian |Giải trình các hạng mục thanh toán cho bác sĩ, bệnh nhân và công ty bảo hiểm. |Nhân viên thanh toán | Mất khoảng 20–30 phút cho một hồ sơ cần giải thích; đây là ước lượng từ kinh nghiệm xử lý, chưa có log tổng hợp |
| 5 |Tốn thời gian |Xử lý những hạng mục ở trạng thái có thể bảo hiểm chi trả còn thiếu 1 số điều kiện phụ mà có thể xử lý để giảm cho người bệnh |Nhân viên thanh toán/Người bệnh |tốn thời gian khoảng trên 1 tiếng do một số thứ cần ý kiến chuyên môn |
| 6 |AI thay thế |Thao tác đọc pdf tài liệu bảo hiểm Ai có thể làm tốt |Nhân viên thanh toán |Đọc khoảng 10-15 loại bảo hiểm/ ngày |
| 7 |AI có thể tốt hơn |Sinh bản nháp giải thích hoặc email phản hồi cho các bên |Nhân viên thanh toán |Nhiều phản hồi vẫn yêu cầu giải thích hoặc bổ sung thông tin hồ sơ; tỷ lệ chính xác chưa được thống kê |
| 8 |Pain từ người khác |phàn nàn về thời gian thanh toán của bệnh nhân |Nhân viên thanh toán/Bệnh nhân |Khoảng 30% có phản hồi lâu 20 ticket hỗ trợ lên hệ thống/ ngày |
| 9 |Pain từ người khác |Áp lức của phòng kế toán khi không xử lý đủ các bộ hồ sơ trong khoảng thời gian làm việc |Nhân viên thanh toán |Ticket từ phòng kế toán 2 tiếng/ Lần |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?
    Tuần trước mất thời gian vào việc đọc và lọc các điều khoản cho hạng mục thanh toán.
    Việc trì hoãn là giải trình cho các bên.
    Hay hỏi lại : Hồ sơ của tôi xử lý còn bao lâu nữa ?
    Workflow về đọc điều khoản và so khớp điều kiện là chậm nhất.
**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 |Phát hiện cận lâm sàng thiếu chẩn đoán kèm theo|Workflow có bottleneck cụ thể ở bước đối chiếu; có thể đo thời gian rà soát và nguy cơ hồ sơ bị từ chối. |Một số điều khoản phụ không trùng nhưng chức năng tương đồng giữa bảo hiểm và bệnh viện |
| 2 |Soạn thư giải trình đối chiếu hồ sơ bị từ chối |Mất nhiều thời gian để đọc lại hồ sơ, đối chiếu lý do từ chối và soạn thư; AI có thể hỗ trợ tạo bản nháp có trích dẫn. |Tính khả thi khi có nhiều loại bảo hiểm và điều khoản chồng chéo; tỷ lệ giải trình thành công cần xác minh |
| 3 |Sinh bảng tóm tắt chi phí dễ hiểu cho người bệnh |Thu ngân mất 5–10 phút/lượt giải thích miệng các thuật ngữ thuốc/khoản trừ bảo hiểm phức tạp khiến quầy thanh toán ùn ứ và người nhà bệnh nhân bức xúc vì nghi ngờ viện phí, LLm có thể sinh văn bản giải thích nhanh cho người bệnh |Khả năng giải thích của LLM có thể tạo ra 1 số từ dễ gây hiểu lầm |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Phát hiện cận lâm sàng thiếu chẩn đoán kèm theo

Problem 1 câu:Thu ngân mất 15 phút lật tìm từng trang bệnh án để rà soát xem các chỉ định cận lâm sàng đắt tiền có đủ mã bệnh ICD tương ứng hay không, nếu sót sẽ bị bảo hiểm xuất toán toàn bộ chi phí.

Actor: Nhân viên thanh toán,Nhân viên xử lý hồ sơ.

Thời điểm / bối cảnh: Trước khi gửi hồ sơ yêu cầu bảo lãnh (Claim) sang cổng tiếp nhận của công ty bảo hiểm.

Current workflow 3-7 bước:
1. Mở file PDF bệnh án và bảng kê chi phí
2. Đọc lướt tìm các xét nghiệm đắt tiền (MRI, CT, chỉ số miễn dịch)
3. Lật ngược lại trang đầu để đọc chẩn đoán chính và chẩn đoán phụ
4. Tra cứu quy tắc thanh toán BHYT/BHTM xem xét nghiệm đó cần mã ICD nào
5. Đánh giá tính tương thích giữa xét nghiệm và chẩn đoán
6. Nếu thiếu: Gọi điện cho bác sĩ điều trị yêu cầu bổ sung chẩn đoán phụ
7. Gửi hồ sơ đi sau khi đã khớp

Bottleneck:Bước 4 & 5 — So sánh ngữ nghĩa giữa tên xét nghiệm chuyên sâu và chẩn đoán lâm sàng mất 8–10 phút, phụ thuộc hoàn toàn vào trí nhớ hoặc kinh nghiệm tra cứu của nhân viên.

Impact:Mất 15 phút/hồ sơ phức tạp. Tỷ lệ hồ sơ bị từ chối được ước tính khoảng 5–8% từ kinh nghiệm xử lý, nhưng cần đối chiếu log để xác nhận tác động doanh thu.

Success metric:Giảm thời gian rà soát hồ sơ từ 15 phút xuống dưới 2 phút; tỷ lệ hồ sơ bị bảo hiểm từ chối do thiếu mã chẩn đoán giảm về dưới 1%.

Non-AI alternative:Bảng tra cứu Excel tĩnh hoặc quy tắc cứng (Rule-based checklist). Tuy nhiên bác sĩ ghi chẩn đoán bằng nhiều biến thể từ ngữ khác nhau khiến việc đối chiếu từ khóa thô bị sót rất nhiều.

AI hypothesis:RAG + LLM đọc hiểu ngữ nghĩa lâm sàng, tự động đối chiếu danh mục cận lâm sàng với quy chuẩn chi trả và gắn cờ cảnh báo đỏ ngay lập tức nếu phát hiện thiếu cơ sở bệnh học.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow trước; Agent chỉ là phương án mở rộng nếu sau này phải phối hợp nhiều nguồn và nhiều nhánh xử lý
[ ] Agent
[ ] Chưa biết

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

CURRENT STATE — 15 phút

[1 Mở file PDF bệnh án: 1']
→ [2 Tìm xét nghiệm đắt tiền: 2']
→ [3 Lật xem chẩn đoán ICD: 2']
→ [4 Tra cứu cẩm nang quy tắc: 4']
→ [5 Đánh giá độ tương thích: 4']  <-- bottleneck
→ [6 Liên hệ bác sĩ bổ sung (nếu thiếu): 15-30' (async)]
→ [7 Gửi hồ sơ: 2']


FUTURE STATE — 2 phút

[1 Upload hồ sơ bệnh án: 10s]
→ [2 AI scan cận lâm sàng & đối chiếu quy tắc bảo hiểm: 20s]
→ [3 AI hiển thị cảnh báo mục có rủi ro xuất toán: 10s]
→ [4 Thu ngân xác nhận cảnh báo & gửi yêu cầu sửa cho bác sĩ: 1']  <-- human boundary
→ [5 Bấm duyệt & gửi hồ sơ: 20s]

Fallback: AI không chắc chắn (confidence < 80%) → Đánh dấu "Cần kiểm tra thủ công".

```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Soạn thư giải trình đối chiếu hồ sơ bị từ chối

Problem 1 câu:Thu ngân/kế toán bảo hiểm mất 30–45 phút cho mỗi ca bị từ chối chi trả để lục lại bệnh án và soạn công văn giải trình y khoa gửi cho bên bảo hiểm.

Actor:Kế toán công nợ bảo hiểm / Thu ngân phụ trách khiếu nại

Thời điểm / bối cảnh:Khi nhận được email/thông báo từ chối thanh toán (Rejection Letter) từ công ty bảo hiểm hoặc cổng BHYT.

Current workflow 3-7 bước:
1. Đọc thư từ chối để xác định khoản mục bị gạt bỏ và mã lý do
2. Mở lại tệp hồ sơ bệnh án cũ của bệnh nhân (thường 20-50 trang)
3. Tìm kiếm các bằng chứng lâm sàng (chỉ số xét nghiệm, biên bản hội chẩn)
4. Mở mẫu văn bản giải trình (Word)
5. Soạn nội dung giải trình: viện dẫn số bệnh án, ngày làm xét nghiệm, lý do y khoa
6. Rà soát văn phong, đối chiếu điều khoản hợp đồng
7. Xuất PDF và gửi email khiếu nại lại cho bên bảo hiểm

Bottleneck:Bước 3 & 5 — Đọc quét tệp bệnh án đồ sộ để trích xuất đúng chỉ số chứng minh bệnh và soạn đoạn văn tranh biện hành chính mất 25–30 phút.

Impact:30–45 phút/công văn. Ước tính mỗi tuần có 10–15 ca tranh chấp, tương đương 6–10 giờ làm việc; thời gian phúc khảo thường kéo dài 30–60 ngày và cần xác nhận bằng dữ liệu thực tế.

Success metric:Trong pilot, đo thời gian soạn thảo từ baseline khoảng 40 phút và kiểm tra mục tiêu dưới 5 phút; theo dõi riêng tỷ lệ giải trình thành công thay vì giả định trước mức tăng 20%.

Non-AI alternative:Mẫu biểu Word có sẵn (Template). Chỉ giải quyết được khung văn bản, toàn bộ số liệu chi tiết và lập luận y khoa vẫn phải gõ tay hoàn toàn.

AI hypothesis:LLM kết hợp trích xuất tài liệu (RAG) đối chiếu lý do từ chối với bệnh án, tự động trích dẫn số trang/chỉ số xét nghiệm và soạn sẵn bản thảo giải trình hoàn chỉnh theo 1 quy tắc đặt ra.

Quick gut:
Drafting & Information Retrieval.

**Draft workflow Card #2:**

CURRENT STATE — 40 phút

[1 Đọc thư từ chối: 3']
→ [2 Mở bệnh án cũ: 2']
→ [3 Đọc quét tìm bằng chứng: 15']  <-- bottleneck
→ [4 Mở template Word: 2']
→ [5 Soạn lập luận & trích số liệu: 13']  <-- bottleneck
→ [6 Review văn bản: 3']
→ [7 Xuất PDF & gửi mail: 2']

FUTURE STATE — 4.5 phút

[1 Upload thư từ chối + bệnh án: 20s]
→ [2 AI định vị bằng chứng & draft thư giải trình: 40s]
→ [3 Thu ngân review lập luận, kiểm tra số liệu trích dẫn: 3']  <-- human boundary
→ [4 Xuất file & gửi khiếu nại: 30s]

Fallback: Bệnh án quá mờ không đọc được → AI chỉ ra trang cần thu ngân tự đọc lại.



File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 —Sinh bảng tóm tắt chi phí dễ hiểu cho người bệnh

Problem 1 câu:Thu ngân mất 5–10 phút/lượt giải thích miệng các thuật ngữ thuốc/khoản trừ bảo hiểm phức tạp khiến quầy thanh toán ùn ứ và người nhà bệnh nhân bức xúc vì nghi ngờ viện phí.

Actor: Thu ngân quầy thanh toán xuất viện, Bệnh nhân / Người nhà bệnh nhân.

Thời điểm / bối cảnh: Lúc bệnh nhân nhận bảng kê chi phí chi tiết để nộp tiền ra viện.

Current workflow 3-7 bước:
1. In bảng kê chi tiết từ HIS (dài 3-5 trang với hàng chục mã kỹ thuật, tên thuốc Latin)
2. Đưa bảng kê cho người nhà và đọc tổng số tiền cần thanh toán
3. Người nhà thắc mắc: "Tại sao thuốc này không được bảo hiểm trả?"
4. Thu ngân cầm lại giấy, dùng bút mực khoanh tròn và giải thích từng dòng
5. Giải thích tiếp các thuật ngữ chuyên môn hoặc lý do thuốc ngoài danh mục
6. Người nhà hiểu và đồng ý nộp tiền
7. Thực hiện thu tiền và in hóa đơn GTGT

Bottleneck:Bước 4 & 5 — Trả lời các câu hỏi lặp đi lặp lại về cùng các loại thuốc/khoản loại trừ bằng lời nói mất từ 5 đến 8 phút cho mỗi người bệnh.

Impact:Mất 8 phút/giao dịch. Dồn ứ hàng dài 15–20 người tại sảnh thanh toán vào giờ trưa; tạo áp lực tâm lý nặng nề cho thu ngân và làm giảm mạnh chỉ số hài lòng của người bệnh.

Success metric:Giảm thời gian giải thích tại quầy từ 8 phút xuống dưới 2 phút/lượt; giảm 70% số lượng câu hỏi thắc mắc về các khoản bảo hiểm không chi trả.

Non-AI alternative:Tờ rơi giải thích chung hoặc bảng thông báo treo tường. Người bệnh không đọc vì họ chỉ quan tâm trực tiếp đến các khoản tiền cụ thể in trên hóa đơn của chính họ.

AI hypothesis:AI tự động chuyển đổi các dòng viện phí bị từ chối thành ngôn ngữ đời thường kèm lý do ngắn gọn 1 câu, xuất thành phiếu tóm tắt 1 trang trực quan kẹp cùng hóa đơn.

Quick gut:
Content Transformation & Patient Communication



**Draft workflow Card #3:**

CURRENT STATE — 8 phút

[1 In bảng kê chi tiết: 30s]
→ [2 Báo tổng tiền: 30s]
→ [3 Tiếp nhận thắc mắc từ người bệnh: 1']
→ [4 Cầm giấy dò tìm khoản mục: 2']  <-- bottleneck
→ [5 Giải thích thuật ngữ & lý do trừ: 3']  <-- bottleneck
→ [6 Người bệnh đồng ý: 30s]
→ [7 Thu tiền & xuất hóa đơn: 30s]

FUTURE STATE — 2 phút

[1 Hệ thống tự sinh phiếu tóm tắt trực quan 1 trang: 10s]
→ [2 Thu ngân đưa phiếu tóm tắt giải thích sẵn các khoản trừ: 30s]
→ [3 Người bệnh tự đọc & nắm rõ số tiền tự trả: 45s]  <-- human boundary
→ [4 Thu tiền & hoàn tất thủ tục: 35s]

Fallback: Người bệnh vẫn thắc mắc trường hợp đặc thù → Thu ngân giải thích miệng bổ sung.

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

Problem Card #2 — Soạn thư giải trình đối chiếu hồ sơ viện phí bị bảo hiểm từ chối (Claim Dispute & Appeal Drafting)

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

Tôi chọn bài toán này vì workflow hiện tại bị nghẽn ở khâu đọc quét thủ công 20–50 trang bệnh án và soạn văn bản đối chiếu với lý do từ chối của bảo hiểm.
Mục tiêu pilot là kiểm tra liệu bản nháp có thể giảm thời gian soạn từ khoảng 40 phút xuống dưới 5 phút hay không, trong khi người phụ trách vẫn kiểm tra toàn bộ trích dẫn trước khi gửi.
Tác động tiềm năng là giảm thời gian xử lý công nợ bị treo 30–60 ngày; tỷ lệ giải trình thành công cần được đo bằng dữ liệu thực tế thay vì coi mức tăng 20% là kết quả chắc chắn.

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**
1. Bệnh án scan thực tế thường có chữ viết tay của bác sĩ rất xấu hoặc bị mờ nhòe, nếu OCR/Vision model đọc sai chỉ số y khoa thì cơ chế fallback nào để ngăn chặn AI "bịa" ra bằng chứng (hallucination) trong công văn gửi bảo hiểm?
2. Phía các hãng bảo hiểm có quy chuẩn chấp nhận một văn bản giải trình do AI hỗ trợ soạn thảo hay không, và ranh giới trách nhiệm pháp lý của kế toán/thu ngân khi bấm duyệt gửi đi là gì?

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
    Nguy cơ Hallucination biến thành gian lận bảo hiểm.
    Vấn đề "GIGO" từ dữ liệu đầu vào
- Tôi sửa gì:
    Không giải quyết mọi ca từ chối: Chỉ tập trung vào 1 nhóm lý do từ chối phổ biến nhất và dữ liệu rõ ràng nhất.
    Giao diện dạng Split-Screen (Màn hình đôi): Nửa bên trái là file PDF bệnh án gốc với các chỉ số được tô sáng (highlighted), nửa bên phải là thư giải trình do AI sinh

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
