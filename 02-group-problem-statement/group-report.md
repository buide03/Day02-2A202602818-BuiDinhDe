# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Bùi Đình Đề | 2A202602818 |                research                                          |
| 2   | Phùng Gia Khánh | 2A20262585 |                   workflow                                   |
| 3   | Lê Hoàng Đạt | 2A202602583 |                      writer                                    |
| 4   | Lê Minh Hiếu | 2A202602848 |             writer                                             |
| 5   | Nguyễn Ngọc Minh | 2A202602653 |                   research                                 |

**Candidate problem nhóm chọn (1 câu):** Sinh viên khó tra cứu quy chế và thủ tục học vụ trong Sổ tay sinh viên PDF dài hơn 100 trang, khiến các câu hỏi lặp lại dồn về chuyên viên CTSV.


---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Ngọc Minh | Bị kéo vào họp bất ngờ giữa lúc đang làm việc tập trung | AI Engineer | Mất ~10-15 phút phục hồi context sau mỗi lần bị ngắt | Pain thật nhưng solution có thể chỉ là process fix, không cần AI |
| 2 | Nguyễn Ngọc Minh | Đọc API docs / framework docs có chỗ không hiểu phải dừng mở ChatGPT hỏi riêng | AI Engineer | Switch context 3-5 lần/tài liệu, mỗi lần 5-10 phút | Workflow rõ, AI có thể hỗ trợ inline — đáng đào sâu |
| 3 | Nguyễn Ngọc Minh | Lưu bài hay trên LinkedIn nhưng quên đã lưu, không tìm lại được khi cần | AI Engineer | Không có tổ chức trong saved list, không search được theo chủ đề | Scope nhỏ, Rule/Notion có thể đủ, không cần AI |
| 4 | Lê Minh Hiếu | Tra cứu quy chế, thủ tục học vụ từ Sổ tay sinh viên PDF dày >100 trang | Sinh viên, Chuyên viên Đào tạo / CTSV | Khó tự tìm đúng điều khoản qua Ctrl+F; dồn 50-70 email/ngày về phòng ban xử lý thủ công | Pain rộng, evidence mạnh (50-70 email/ngày), RAG phù hợp — đáng xem xét |
| 5 | Lê Minh Hiếu | Học viên hỏi lặp đi lặp lại mật khẩu Wi-Fi phòng Lab do chuỗi ký tự quá dài, phức tạp | Học viên, Trợ giảng (TA), Kỹ thuật viên Lab | Nhập tay chuỗi ký tự dài dễ sai sót; TA phải dừng việc chuyên môn để đọc/ghi bảng thủ công | Rule đủ (QR code), không cần AI |
| 6 | Lê Minh Hiếu | Đổi Gmail liên kết và cấp lại quyền truy cập GitHub Organization / repo bài Lab | Học viên, Nhân viên, IT Helpdesk / DevOps Admin | Helpdesk phải dò đối soát danh tính chéo trên Sheet và thao tác click invite tay từng tài khoản | Workflow automation đủ, không cần AI phức tạp |
| 7 | Phùng Gia Khánh | Sau khi hoàn thành lab/project, việc biến notes rời rạc thành artifact nộp có cấu trúc vẫn cần nhiều bước kiểm tra chéo | Sinh viên AI / project team | Khó map notes, evidence, research và quyết định rời rạc vào đúng section mà vẫn giữ được tính nhất quán giữa claim, metric và kết luận | Pain thật, AI có thể hỗ trợ tổng hợp — workflow cần làm rõ hơn |
| 8 | Phùng Gia Khánh | Khi đọc rubric/readme dài, người học dễ tối ưu "cho đủ form" nhưng bỏ sót logic problem → workflow → metric → boundary | Học viên làm lab | Khó kiểm tra quan hệ logic xuyên suốt giữa các section; bài có thể đủ heading nhưng problem, bottleneck, metric, boundary và solution không support lẫn nhau | Thú vị, AI có thể làm reviewer — nhưng actor hơi chung, cần thu hẹp |
| 9 | Phùng Gia Khánh | Yêu cầu bài lab nằm rải ở nhiều file, người học phải đối chiếu để biết chính xác output, rubric và trình tự làm | Học viên AI Thực Chiến | Phải tổng hợp và reconcile requirement từ nhiều tài liệu thành một checklist và execution flow thống nhất | Overlap với #8, có thể gom — bottleneck rõ hơn #8 |
| 10 | Lê Hoàng Đạt | Sinh viên phải tìm lại thông tin từ nhiều nguồn để nhớ mình đang làm gì và cần làm gì tiếp theo khi quay lại đồ án | Sinh viên năm cuối làm đồ án/khóa luận | Thông tin nằm rải rác ở chat, email, file, repository khiến việc khôi phục context mất thời gian | Pain thật, workflow rõ — gần giống #7, có thể cluster |
| 11 | Lê Hoàng Đạt | Sinh viên phải đọc và tổng hợp nhiều paper/tài liệu khác nhau để phục vụ một câu hỏi hoặc một phần của đồ án | Sinh viên năm cuối làm đồ án/khóa luận/research | Phải đọc nhiều nguồn, tự tìm evidence, ghi chú và đối chiếu thông tin giữa các paper | Evidence mạnh, AI có thể hỗ trợ tổng hợp literature — đáng xem xét |
| 12 | Lê Hoàng Đạt | Sinh viên khó đối chiếu feedback cũ với phiên bản báo cáo hiện tại để biết vấn đề nào đã được sửa và vấn đề nào còn tồn đọng | Sinh viên làm đồ án/khóa luận | Feedback qua nhiều vòng và nhiều phiên bản khiến việc mapping feedback với thay đổi hiện tại dễ bị bỏ sót | Bottleneck rõ, có thể đo được — workflow cần làm rõ hơn |
| 13 | Bùi Đình Đề | Bỏ sót chỉ định cận lâm sàng không khớp chẩn đoán | Bác sĩ điều trị, Giám định viên BHYT | Biến thể từ ngữ làm sàng và quy tắc chi trả quá đồ sộ | Domain phức tạp, impact lớn — nhưng cần hiểu sâu ngành y tế mới validate được |
| 14 | Bùi Đình Đề | Soạn thư giải trình cho từng ca bị từ chối bảo hiểm | Giám định viên BHYT, Bác sĩ điều trị | Dữ liệu phi cấu trúc (file scan) quá dài, tốn nhân lực tổng hợp | Pain rõ, lặp lại nhiều — nhưng domain y tế cần kiểm chứng kỹ trước khi dùng AI |
| 15 | Bùi Đình Đề | Tính nhầm hạn mức tiền giường khi thay đổi loại phòng | Kế toán viện phí | Tên phòng không chuẩn hóa và logic tính toán tầng phức tạp | Rule/script có thể đủ nếu chuẩn hóa dữ liệu đầu vào — không cần AI |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Tổng hợp thông tin rời rạc | #7, #9, #10, #11 | Người dùng phải gom thông tin từ nhiều nguồn (notes, file, paper, tài liệu) thành một output có cấu trúc | Pain thật, actor rõ (sinh viên làm đồ án), AI có thể hỗ trợ tổng hợp — cluster mạnh nhất |
| B — Tra cứu tài liệu dài / Q&A | #2, #4, #8 | Người dùng phải đọc tài liệu dài để tìm đúng thông tin cần, dễ bỏ sót hoặc mất mạch | #4 có evidence mạnh nhất (50-70 email/ngày); #2 và #8 cùng pattern nhưng scope nhỏ hơn |
| C — Automation quy trình lặp lại | #5, #6, #12, #15 | Các bước thủ công lặp lại nhiều lần, không cần AI phức tạp, Rule hoặc Workflow automation đủ | Nên loại sớm khỏi shortlist AI — giải bằng Rule/script hiệu quả hơn |
| D — Domain y tế / nghiệp vụ phức tạp | #13, #14 | Bài toán trong ngành y tế, cần hiểu sâu domain để validate pain và solution | Impact lớn nhưng rủi ro cao, khó validate trong lab — nhóm không có domain expert |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #4 — Tra cứu quy chế từ Sổ tay sinh viên PDF (Lê Minh Hiếu) | Actor rõ (sinh viên, chuyên viên CTSV); evidence mạnh (50-70 email/ngày); bottleneck cụ thể (Ctrl+F không đủ); có thể vẽ workflow rõ; so sánh RAG vs Rule được | Cần kiểm chứng con số 50-70 email/ngày; chưa rõ ai là actor chính — sinh viên hay chuyên viên CTSV |
| #11 — Tổng hợp paper/tài liệu cho đồ án (Lê Hoàng Đạt) | Actor rõ (sinh viên năm cuối); pain lặp lại mỗi khi research; workflow vẽ được; AI có thể hỗ trợ rõ ràng ở bước tổng hợp | Chưa có metric thời gian cụ thể; "đủ tốt" khi tổng hợp paper khó đo; scope có thể rộng |
| #7 — Biến notes rời rạc thành artifact nộp (Phùng Gia Khánh) | Pain thật với sinh viên làm lab/project; workflow có thể vẽ; AI hỗ trợ mapping notes vào section rõ | Overlap với #11 và #10; actor hơi chung; metric chất lượng artifact khó đo |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #4 — Tra cứu quy chế PDF | 5 | 4 | 5 | 4 | 5 | 5 | 4 | 32 |
| #11 — Tổng hợp paper đồ án | 4 | 4 | 3 | 3 | 4 | 4 | 4 | 26 |
| #7 — Biến notes thành artifact | 3 | 3 | 3 | 3 | 4 | 4 | 4 | 24 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#4 — Tra cứu quy chế, thủ tục học vụ từ Sổ tay sinh viên PDF dày >100 trang (Lê Minh Hiếu)
```

**Vì sao chọn (4-5 câu):**

```text
Đây là bài có evidence mạnh nhất trong nhóm với con số 50-70 email/ngày đổ về phòng ban xử lý thủ công. Actor rõ gồm cả sinh viên lẫn chuyên viên CTSV, hai phía đều chịu ảnh hưởng. Workflow hiện tại có thể vẽ được từ bước sinh viên cần tra → tìm trong PDF → không ra → gửi email. Bottleneck cụ thể ở bước tìm kiếm trong tài liệu dài và xử lý email lặp lại. Có thể so sánh Rule/RAG/Agent rõ ràng và nhóm đủ hiểu domain để validate trong thời gian lab.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
#11 — Tổng hợp paper đồ án: Pain thật nhưng thiếu metric thời gian cụ thể; "tổng hợp đủ tốt" khó đo; scope dễ bị rộng khi đào sâu.

#7 — Biến notes thành artifact: Overlap nhiều với #11 và #10; actor chưa đủ cụ thể; metric chất lượng artifact khó thống nhất trong lab.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Chưa có disagreement lớn. Nhóm đồng thuận #4 có evidence mạnh nhất và workflow dễ validate nhất trong thời gian lab.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 0 | Chưa thực hiện được trong thời gian lab | — | — |
| Survey / poll | 0 | Chưa thực hiện được trong thời gian lab | — | — |
| Log / ticket / review (nếu có) | 0 | Không có quyền truy cập log email CTSV | — | — |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Nhóm chưa validate được với người thật do giới hạn thời gian lab. Pain được suy luận từ trải nghiệm cá nhân của thành viên nhóm (Lê Minh Hiếu) và pattern chung quan sát được trong môi trường học tập. Con số 50-70 email/ngày là giả định của nhóm, chưa xác nhận — đây là rủi ro chính của bài và là lý do nhóm chọn "Not Yet" thay vì "Go".
```

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| REBot — CatRAG tại Đại học Cần Thơ | https://arxiv.org/html/2510.01800v1 | Chatbot RAG trả lời câu hỏi về quy chế, thủ tục từ student handbook và PDF tài liệu chính thức | Đúng context bài toán — cùng là trường đại học Việt Nam, cùng vấn đề sinh viên khó tìm thông tin trong tài liệu dài | Cần semantic enrichment và graph routing mới đạt độ chính xác cao; vẫn có hallucination risk | Không nên dùng RAG đơn giản — cần chunking tốt và fallback rõ khi AI không tìm được đoạn liên quan |
| HUST Regulations Bot | https://github.com/mizuwonomu/hust-regulations-bot | RAG chatbot giúp sinh viên HUST tra cứu quy chế đào tạo bằng ngôn ngữ tự nhiên | Đã build trên tài liệu tiếng Việt, cùng bối cảnh trường kỹ thuật Việt Nam | Chưa rõ độ chính xác; không có metric đo số email giảm được | Có thể dùng làm reference architecture; cần đo được metric trước/sau khi deploy |
| Georgia State University — Chatbot "Pounce" | https://www.eesel.ai/blog/ai-chatbot-for-education | Xử lý 50.000+ tin nhắn sinh viên, dưới 1% cần chuyển cho nhân viên; giảm summer melt 21.4% | Evidence mạnh về giảm workload thủ công; có metric rõ | Scale lớn, cần đầu tư hạ tầng; context khác (Mỹ) | Pattern tốt: AI xử lý câu hỏi lặp lại, escalate câu phức tạp cho người thật — áp dụng được cho CTSV |
| Các trường đại học triển khai chatbot hỗ trợ sinh viên | https://www.lowcode.agency/blog/how-to-build-an-ai-chatbot-for-student-support-and-course-queries | Giảm 40-60% volume email hành chính sau khi deploy chatbot | Nhiều case study xác nhận pattern này hoạt động | Số liệu từ vendor blog, cần kiểm chứng thêm từ nguồn học thuật | Dùng làm baseline kỳ vọng — nếu nhóm deploy pilot, target giảm 40% email là hợp lý |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Bài toán này đã có nhiều precedent ở Việt Nam và quốc tế — không cần build từ đầu. Pattern phù hợp nhất là RAG Workflow: chunk PDF quy chế, embed, cho sinh viên query bằng ngôn ngữ tự nhiên, AI trả lời kèm trích dẫn đoạn nguồn, chuyên viên CTSV vẫn xử lý câu phức tạp. Không nên build Agent tự quyết định vì câu trả lời sai về quy chế có thể gây hậu quả thật cho sinh viên — cần người thật review các trường hợp edge case.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
LUỒNG 1 — Sinh viên tự tra (phổ biến hơn)

[1 Nảy sinh câu hỏi về quy chế/thủ tục]
→ [2 Thử Ctrl+F trong PDF sổ tay >100 trang: 5-15']
→ [3 Không ra hoặc không chắc → hỏi Google / AI / bạn: 5-10']
→ [4a Tìm được đáp án → xong]
→ [4b Vẫn không chắc → lên website CTSV hoặc gửi email]

LUỒNG 2 — Sinh viên gửi email CTSV

[1 Sinh viên gửi email hỏi]
→ [2 Email vào hàng đợi CTSV (~50-70 email/ngày — giả định của nhóm, chưa xác nhận với CTSV)]
→ [3 Chuyên viên tra tài liệu, soạn trả lời thủ công]  <-- bottleneck
→ [4 Gửi email trả lời sinh viên]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Sinh viên | Câu hỏi về quy chế, thủ tục | — | Không cố định | Phát sinh khi làm thủ tục, đăng ký, thi cử |
| 2 | Sinh viên | PDF sổ tay >100 trang | Đáp án (nếu tìm được) | 5-15 phút/lần | Ctrl+F kém hiệu quả vì từ ngữ không khớp chính xác |
| 3 | Sinh viên | Câu hỏi | Đáp án từ Google/AI/bạn | 5-10 phút/lần | Độ chính xác không đảm bảo, dễ nhầm phiên bản quy chế |
| 4 | Sinh viên | — | Email hỏi CTSV | — | Xảy ra khi bước 2-3 thất bại |
| 5 | Chuyên viên CTSV | Email sinh viên | Email trả lời | Giả định của nhóm: 5-10 phút/email, ~50-70 email/ngày — cần xác nhận với CTSV | Lặp lại nhiều câu hỏi giống nhau mỗi ngày |

**Bottleneck chính:**

```text
Hai bottleneck song song:
1. Phía sinh viên: Ctrl+F trong PDF dài không hiệu quả vì từ ngữ câu hỏi không khớp chính xác với từ ngữ trong văn bản quy chế.
2. Phía CTSV: Xử lý thủ công ~50-70 email/ngày (giả định chưa xác nhận), nhiều câu hỏi lặp lại, tốn nhân lực cho việc không cần judgment cao.
```

### 5.2. Future workflow bản nhóm

```text
FUTURE STATE — RAG Workflow

[1 Sinh viên nhập câu hỏi tự nhiên vào chatbot]
→ [2 RAG tìm đoạn liên quan trong PDF quy chế: < 3'']
→ [3 AI trả lời kèm trích dẫn đoạn nguồn + số trang: < 5'']  <-- AI boundary
→ [4a Sinh viên hiểu và xong]
→ [4b Câu phức tạp / AI không chắc → escalate tự động sang CTSV kèm context]

Fallback: AI không tìm được đoạn liên quan hoặc độ tin cậy thấp → thông báo rõ và chuyển sang CTSV.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Thời gian sinh viên tìm được câu trả lời | 10-25 phút | Dưới 1 phút | Bấm giờ từ lúc đặt câu hỏi đến lúc có đáp án |
| Số email CTSV/ngày | ~50-70 (giả định) | Giảm 40-60% | Đếm email trước/sau khi deploy pilot |
| Số bước sinh viên phải thực hiện | 3-4 bước | 1 bước | Đếm bước trong workflow |
| Risk mới | Không có | Hallucination — AI trả lời sai quy chế | Review sample output hàng tuần |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên cần tra cứu quy chế/thủ tục học vụ và chuyên viên CTSV xử lý email hỏi đáp hàng ngày. |
| **Workflow** | Sinh viên tìm thông tin bằng Ctrl+F trong PDF >100 trang hoặc hỏi Google/AI/bạn; khi không tìm được thì gửi email CTSV; chuyên viên xử lý thủ công từng email. |
| **Bottleneck** | Ctrl+F không khớp từ ngữ tự nhiên nên sinh viên không tìm được dù thông tin có trong tài liệu; chuyên viên CTSV lặp lại xử lý cùng câu hỏi nhiều lần mỗi ngày. |
| **Impact** | Sinh viên mất 10-25 phút cho câu hỏi đơn giản; CTSV tốn nhân lực cho việc lặp lại thay vì tập trung vào case phức tạp hơn. |
| **Success Metric** | Giảm thời gian tìm câu trả lời của sinh viên từ 10-25 phút xuống dưới 1 phút; giảm 40% volume email đơn giản vào CTSV. |
| **Boundary** | Chỉ trả lời câu hỏi có trong tài liệu quy chế chính thức; không tự quyết định ngoại lệ; câu phức tạp hoặc độ tin cậy thấp escalate sang người thật. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Metric "40% volume email" dựa trên con số 50-70 email/ngày chưa xác nhận — cần validate trước khi chốt
- Tôi sửa gì: Ghi rõ "(giả định chưa xác nhận)" ở mọi chỗ dùng con số này cho đến khi nhóm validate xong 4.1

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Câu hỏi về quy chế có thể diễn đạt nhiều cách, câu trả lời đúng cần hiểu ngữ cảnh và ý định của sinh viên, không phải keyword matching đơn thuần
- Độ phức tạp: [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Cần retrieve đúng đoạn từ PDF dài, hiểu câu hỏi tự nhiên, tổng hợp câu trả lời, kèm trích dẫn nguồn, và escalate khi không chắc

**Bài toán nhóm nằm ở ô nào:**

```text
Độ mơ hồ cao + Độ phức tạp cao → Agent có thể phù hợp, nhưng cần boundary, người thật kiểm tra và phương án quay về rõ. Tuy nhiên xét kỹ thì workflow khá tuyến tính (hỏi → retrieve → trả lời → escalate nếu không chắc), chưa cần Agent tự lập kế hoạch động.
```

**Vì sao (2-3 câu):**

```text
Workflow đi theo một đường cố định: nhận câu hỏi → tìm trong PDF → trả lời kèm nguồn → escalate nếu không chắc. Không có bước nào AI cần tự quyết định bước tiếp theo khác nhau tùy tình huống. Vì vậy Workflow phù hợp hơn Agent dù độ mơ hồ cao.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | FAQ tĩnh: danh sách câu hỏi thường gặp + câu trả lời cố định | Đủ nếu chỉ có 20-30 câu hỏi lặp lại nhất, sinh viên chịu tìm trong list | Không xử lý được câu hỏi mới hoặc diễn đạt khác; tốn công maintain khi quy chế thay đổi | Dùng cho bước pre-filter câu hỏi phổ biến nhất |
| **Workflow** | RAG pipeline: nhận câu hỏi tự nhiên → retrieve đoạn liên quan trong PDF → AI tổng hợp trả lời kèm trích dẫn → escalate nếu độ tin cậy thấp | Đủ vì workflow tuyến tính, AI chỉ hỗ trợ bước retrieve + tổng hợp, người thật vẫn xử lý edge case | Hallucination nếu chunk kém; trả lời sai quy chế có thể gây hậu quả thật cho sinh viên | **Chọn** |
| **Agent** | Agent tự quyết định: tìm nhiều nguồn, so sánh phiên bản quy chế, tự escalate, tự gửi email | Cần nếu workflow có nhiều nhánh phức tạp, nhiều nguồn dữ liệu khác nhau cần kết hợp | Quá rộng cho scope hiện tại; rủi ro cao khi AI tự quyết trong domain có hậu quả thật | Không chọn ở giai đoạn này |

**5 câu hỏi chốt:**
1. Rule có giải được 70-80% case không? Có thể — nếu nhóm thống kê được top 20-30 câu hỏi lặp lại. Nhưng không scale và khó maintain khi quy chế cập nhật.
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? Phần lớn tuyến tính — nhận câu hỏi → retrieve → trả lời hoặc escalate. Không cần Agent.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? Không — chỉ cần retrieve và tổng hợp từ một nguồn PDF cố định.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? Sinh viên phát hiện nếu câu trả lời vô lý; chuyên viên CTSV phát hiện khi nhận escalation. Cần review sample output định kỳ.
5. Có hạ được từ Agent → Workflow → Rule không? Có — Workflow là lựa chọn phù hợp, Rule dùng bổ sung cho top câu hỏi phổ biến nhất.

**Mức chọn:**

```text
Workflow (RAG pipeline với escalation)
```

**Vì sao chọn (3-4 câu):**

```text
Workflow phù hợp vì pipeline tuyến tính và rõ ràng: retrieve → tổng hợp → trả lời kèm nguồn → escalate nếu không chắc. AI chỉ hỗ trợ bước tìm kiếm và tổng hợp ngôn ngữ, không tự quyết định ngoài phạm vi đó. Người thật (CTSV) vẫn xử lý câu phức tạp nên rủi ro kiểm soát được. Có nhiều precedent thành công ở các trường đại học Việt Nam (HUST, CTU) với cùng pattern này.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule không đủ vì câu hỏi sinh viên diễn đạt rất đa dạng, không thể cover bằng keyword matching. Khi quy chế cập nhật, FAQ tĩnh tốn công maintain và dễ lỗi thời. RAG tự động cập nhật khi PDF nguồn thay đổi.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên cần tra cứu quy chế/thủ tục học vụ; chuyên viên CTSV xử lý email hỏi đáp hàng ngày. |
| **Workflow** | Sinh viên tìm bằng Ctrl+F trong PDF >100 trang hoặc hỏi Google/AI/bạn; khi không ra thì gửi email CTSV; chuyên viên tra tài liệu và soạn trả lời thủ công từng email. |
| **Bottleneck** | Ctrl+F không khớp từ ngữ tự nhiên nên sinh viên không tìm được dù thông tin có trong tài liệu; chuyên viên CTSV lặp lại xử lý cùng câu hỏi nhiều lần mỗi ngày. |
| **Impact** | Sinh viên mất 10-25 phút cho câu hỏi có thể trả lời trong vài giây; CTSV tốn nhân lực cho việc lặp lại thay vì tập trung vào case cần judgment. |
| **Success Metric** | Giảm thời gian tìm câu trả lời của sinh viên từ 10-25 phút xuống dưới 1 phút; giảm ít nhất 40% volume email đơn giản vào CTSV (đo bằng đếm email trước/sau pilot 2 tuần). |
| **Boundary** (làm / không làm) | Làm: trả lời câu hỏi có trong tài liệu quy chế chính thức, kèm trích dẫn số trang. Không làm: tự quyết định ngoại lệ, xử lý hồ sơ, thay thế CTSV trong case phức tạp. |
| **AI intervention point** | Sau khi sinh viên nhập câu hỏi tự nhiên, trước khi câu hỏi đến CTSV — AI retrieve đoạn liên quan và tổng hợp câu trả lời. |
| **Mức chọn** | Workflow — RAG pipeline tuyến tính, AI hỗ trợ retrieve và tổng hợp, CTSV xử lý escalation. |
| **Rủi ro & người thật kiểm tra** | Rủi ro: AI trả lời sai quy chế → sinh viên làm sai thủ tục. Người thật kiểm tra: CTSV review sample output hàng tuần; AI tự động escalate khi độ tin cậy thấp. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Hai actor rõ: sinh viên và chuyên viên CTSV; workflow có thể vẽ được |
| Baseline + metric đo được chưa? | Not Yet | Thời gian sinh viên tìm câu trả lời cần đo thật; số email/ngày của CTSV chưa xác nhận |
| Data/input đủ dùng chưa? | Yes | PDF sổ tay sinh viên là nguồn dữ liệu có sẵn và rõ ràng |
| AI sai, hậu quả chấp nhận được không? | Not Yet | Trả lời sai quy chế có thể khiến sinh viên làm sai thủ tục — cần review rõ trước khi deploy |
| Có người review/owner không? | Yes | Chuyên viên CTSV là owner tự nhiên, xử lý escalation và review định kỳ |
| Có cách non-AI đơn giản hơn không? | Yes | FAQ tĩnh + website tìm kiếm tốt hơn — nhưng không scale và khó maintain |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Hướng đi đúng và có nhiều precedent thành công, nhưng còn 2 điều cần xác nhận trước khi Go. Thứ nhất, baseline metric (số email/ngày của CTSV, thời gian sinh viên tìm câu trả lời) chưa được đo thật — không có baseline thì không biết pilot có cải thiện không. Thứ hai, rủi ro AI trả lời sai quy chế cần có quy trình review rõ ràng trước khi để sinh viên dùng thật.
```

**Nếu Not Yet — cần validate gì trước:**

```text
1. Hỏi chuyên viên CTSV: số email/ngày thực tế là bao nhiêu, câu hỏi nào lặp lại nhiều nhất.
2. Bấm giờ 5-10 sinh viên tìm câu trả lời trong PDF để có baseline thời gian.
3. Xác định quy trình review: ai kiểm tra output AI, bao lâu 1 lần, escalation threshold là gì.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nếu tỉ lệ câu trả lời sai vượt 5% trong 2 tuần pilot → dừng và review lại chunking + prompt. Nếu sinh viên vẫn gửi email CTSV với tỉ lệ tương đương sau 4 tuần → hạ về FAQ tĩnh + cải thiện website tìm kiếm.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [ ] Có validation (quote thật) + research (link kiểm được) — validation chưa có quote thật; research có link kiểm được
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
