# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Đoàn Bá Khải | 2A202602728 | Facilitator / Workflow Architect |
| 2   | Trần Ngọc Khuyến | 2A202602682 | Research Lead / Validation |
| 3   | Nguyễn Phúc Bảo | 2A202602925 | Problem Framing / Writer |
| 4   | Nguyễn Văn An | 2A202602782 | Technical Analyst / Solution Specialist |
| 5   | Nguyễn Văn Biển | 2A202602416 | Metric & Quality Reviewer |

**Candidate problem nhóm chọn (1 câu):**

Trợ giảng và Giảng viên mất nhiều giờ mỗi tuần trả lời lặp đi lặp lại các lỗi lab/môi trường phổ biến trên kênh chat, trong khi sinh viên bị nghẽn tiến độ vì phải chờ đợi giải đáp thủ công.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Khải | Đọc Official Docs ngập ngụa thuật ngữ (Kafka/RabbitMQ) | Người tự học tech sâu | Đứt đoạn luồng dữ liệu, mất 2-3 tiếng tra cứu | Bài hay nhưng phạm vi hơi hẹp cho cá nhân học backend |
| 2 | Khải | Ảo giác hiểu bài khi dùng AI tóm tắt paper AI/ML | Sinh viên làm luận văn | Tắc tịt công thức toán khi hiện thực hóa code | Nỗi đau thật, nhưng phạm vi học thuật khó kiểm chứng nhanh trong lab |
| 3 | Khải | Học từ vựng IELTS thụ động qua Flashcard | Người tự ôn IELTS | Nhớ nghĩa mặt chữ nhưng không dùng được vào bài viết/nói | Phổ biến nhưng không liên quan đến bối cảnh kỹ thuật/công nghệ của nhóm |
| 4 | Khuyến | Trợ giảng (TA) bị hỏi lặp đi lặp lại cùng một lỗi bài lab | Trợ giảng, Giảng viên | Mất 5-10 phút/lần tìm lại link hoặc gõ lại cách fix | Nỗi đau cực kỳ nhức nhối, tuần nào làm lab cả nhóm cũng chứng kiến |
| 5 | Khuyến | Chấm bài tập thực hành lập trình thủ công | Giảng viên, TA | Mất nhiều giờ tải code, cài môi trường và chạy test case | Problem lớn nhưng trường đã có hệ thống nộp bài tự động một phần |
| 6 | Khuyến | Sinh viên nộp bài lab thiếu file/sai cấu trúc thư mục | Sinh viên, TA | Đến lúc chấm bài mới phát hiện lỗi, bị trừ điểm oan | Có thể giải quyết đơn giản bằng shell script / GitHub Actions |
| 7 | Bảo | Họp nhóm đồ án bị rơi rụng các action items | Thành viên nhóm đồ án | Họp xong không ai ghi chép, quên deadline việc cần làm | Đau nhưng đã có nhiều tool Notion/Meet bot giải quyết tốt |
| 8 | Bảo | Phân chia công việc trong nhóm đồ án không đồng đều | Trưởng nhóm đồ án | Khó ước lượng khối lượng công việc, người làm nhiều người làm ít | Vấn đề con người/quản trị, khó giải quyết bằng AI |
| 9 | Bảo | Format slide báo cáo đồ án mất nhiều thời gian căn chỉnh | Sinh viên thuyết trình | Mất cả buổi tối chọn template, chỉnh font, căn lề | Vấn đề thiên về design, chưa phải bottleneck cốt lõi của kỹ thuật |
| 10 | An | Cài đặt môi trường máy ảo / Docker bị lỗi xung đột cổng | Sinh viên học môn Hệ điều hành/Mạng | Mất 2-3 tiếng debug cấu hình mạng không tương thích | Rất ức chế nhưng là bài toán con nằm trong nhóm lỗi lab |
| 11 | An | Tìm tài liệu học tập bị loãng, ngập tràn nguồn rác | Sinh viên tự học | Mất thời gian đọc lướt các bài blog sao chép không uy tín | Khó đo lường thành công một cách định lượng |
| 12 | Biển | Bỏ quên deadline bài tập do phân mảnh nhiều nền tảng | Sinh viên | Deadline rải rác trên LMS, Google Classroom, Discord | Có thể giải quyết bằng Google Calendar sync, chưa cần AI |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Hỗ trợ giải đáp & Lỗi bài lab | #4, #6, #10 | Trục trặc trong quy trình hướng dẫn thực hành và giải đáp thắc mắc bài lab | Nỗi đau trực tiếp ảnh hưởng đến cả người dạy (TA) và người học (Sinh viên) |
| B. Tự học & Tiêu hóa kiến thức sâu | #1, #2, #3, #11 | Khó khăn khi tiếp thu kiến thức học thuật, tài liệu chuyên sâu | Mang tính trải nghiệm cá nhân, khác biệt tùy vào năng lực từng người |
| C. Vận hành & Phối hợp nhóm đồ án | #7, #8, #9, #12 | Ma sát trong giao tiếp nhóm, phân chia công việc và quản lý deadline | Thiên về kỹ năng quản trị và quy trình làm việc, nhiều giải pháp non-AI đã có sẵn |
| D. Đánh giá & Chấm điểm học phần | #5 | Gánh nặng chấm bài và kiểm thử code thủ công của giảng viên | Phạm vi khá lớn, liên quan đến quyền bảo mật dữ liệu của nhà trường |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| **1. TA bị hỏi lặp đi lặp lại lỗi bài lab (#4)** | • Cả nhóm và bạn bè đều trải qua hằng tuần, bằng chứng sống động.<br>• Workflow hỏi-đáp hiện tại rất rõ ràng, đo lường được bằng số phút và số câu hỏi.<br>• Giải quyết vừa vặn trong buổi lab, so sánh Rule vs Workflow vs Agent rất tự nhiên. | Cần cơ chế cập nhật câu trả lời mới khi giảng viên thay đổi đề bài hoặc sinh viên hỏi case dị biệt. |
| **2. Đọc Official Docs ngập thuật ngữ (#1)** | • Workflow tra cứu tài liệu rõ ràng, có baseline thời gian cụ thể.<br>• Giải quyết được ma sát thực tế của sinh viên khi học công nghệ sâu. | Phạm vi hẹp cho cá nhân học chuyên sâu, khó phỏng vấn số đông sinh viên trong lớp để lấy bằng chứng. |
| **3. Họp nhóm đồ án bị rơi rụng action items (#7)** | • Sinh viên nào làm việc nhóm cũng từng gặp tình trạng họp xong để đó.<br>• Bối cảnh quen thuộc, dễ tiếp cận phỏng vấn. | Thị trường đã có quá nhiều tool (Notion AI, Otter.ai, Fireflies), khó tạo ra điểm khác biệt trong phạm vi môn học. |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **TA bị hỏi lặp lỗi lab (#4)** | 5 | 5 | 5 | 5 | 5 | 5 | 5 | **35** |
| Đọc Official Docs (#1) | 4 | 4 | 4 | 4 | 4 | 4 | 3 | 27 |
| Rơi rụng việc sau họp nhóm (#7) | 4 | 4 | 4 | 3 | 5 | 4 | 4 | 28 |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Trợ giảng / Giảng viên bị sinh viên hỏi lặp đi lặp lại về cùng một vấn đề / lỗi bài lab trên kênh chat lớp học.
```

**Vì sao chọn (4-5 câu):**

```text
Đây là bài toán có cả hai phía chịu ảnh hưởng rõ rệt và quen thuộc với tất cả thành viên trong nhóm: Trợ giảng kiệt sức vì làm "máy copy-paste", còn sinh viên bị gián đoạn tiến độ vì phải chờ đợi phản hồi. Quy trình tương tác hiện tại cực kỳ cụ thể, có thể đo lường chính xác bằng số phút chờ đợi và tỷ lệ câu hỏi trùng lặp. Đề tài có tính khả thi cao để thực hiện trong khuôn khổ buổi lab 4 tiếng mà không bị trôi dạt sang các hệ thống viễn tưởng. Đặc biệt, bài toán này mở ra không gian phân tích rất sắc bén giữa các phương án Rule (từ khóa FAQ), Workflow (tra kho Q&A theo ngưỡng) và Agent (truy hồi nhiều vòng cho câu hỏi mơ hồ), giúp nhóm thể hiện trọn vẹn năng lực tư duy bài toán trước giải pháp.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
- Bài Đọc Official Docs (#1): Dù rất sâu sắc về mặt kỹ thuật cá nhân nhưng phạm vi quá hẹp đối với số đông sinh viên; nhóm khó có thể phỏng vấn và lấy số liệu kiểm chứng từ nhiều sinh viên khác trong thời gian ngắn của buổi lab.
- Bài Rơi rụng việc sau họp nhóm đồ án (#7): Vấn đề này đã có quá nhiều công cụ thị trường giải quyết tốt (như bot tóm tắt Google Meet, Notion AI); bản chất của việc quên task chủ yếu nằm ở ý thức kỷ luật của thành viên chứ không hoàn toàn do thiếu công nghệ hỗ trợ.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Bạn An và Biển ban đầu lo ngại rằng sinh viên thường chụp ảnh màn hình lỗi rồi gửi thẳng vào chat chứ không copy text, khiến bot khó đọc được log. Sau khi tranh luận, nhóm thống nhất ranh giới (Boundary) của giải pháp: ở giai đoạn MVP trong buổi lab, hệ thống tập trung giải quyết các câu hỏi dạng text và log lỗi copy-paste; nếu sinh viên gửi ảnh, bot sẽ hướng dẫn sinh viên cách lấy text log hoặc tự động chuyển tiếp (escalate) cho TA xử lý. Cả nhóm đều đồng thuận với hướng đi này.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc log/ticket thật)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | 3 người (1 TA, 2 sinh viên) | • TA môn Lập trình: *"Đến tuần nộp đồ án, riêng lỗi cài môi trường với lỗi đường dẫn file mình phải gõ lại hoặc lục tìm link gửi lại ít nhất 20 lần một ngày, nhiều lúc đang code dở đồ án tốt nghiệp mà tin nhắn réo liên tục rất ức chế."*<br>• Sinh viên A: *"Trước deadline 2 tiếng máy em bị văng lỗi thư viện, nhắn lên Discord đợi cả tiếng anh TA mới online trả lời, suýt nữa em trễ hạn nộp."* | Sinh viên B: *"Nhiều khi em bị lỗi lạ quá thì em tự search Google hoặc quăng cho ChatGPT giải thích luôn chứ không hỏi TA vì ngại làm phiền."* | Thu hẹp phạm vi bài toán: Tập trung vào nhóm lỗi bài lab và môi trường phổ biến đã có tiền lệ, không ôm đồm việc giải quyết các lỗi logic riêng biệt của từng sinh viên. |
| Log / ticket / review (nếu có) | 45 tin nhắn channel `#hoi-dap` tuần trước | Thống kê có tới 31/45 câu hỏi (68.8%) xoay quanh đúng 4 chủ đề lặp lại: Lỗi version CUDA, lỗi thư viện thiếu module, cấu trúc nộp bài file zip và cách kết nối server trường. | Một số câu hỏi hỏi gộp 2-3 lỗi cùng một lúc trong một tin nhắn dài. | Thiết kế bot có khả năng bóc tách từng lỗi hoặc yêu cầu sinh viên làm rõ lỗi chính cần hỗ trợ; bổ sung nút "Chưa được" để sinh viên đẩy câu hỏi thành ticket khi bot không giải quyết được. |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Pain thật không nằm ở việc lớp học thiếu tài liệu hay thiếu file FAQ, mà nằm ở rào cản truy xuất (Retrieval Friction): Khi sinh viên gặp lỗi cận kề deadline, tâm lý hoảng loạn khiến họ dùng từ khóa tự do không khớp với tiêu đề FAQ, dẫn đến việc họ chọn cách nhanh nhất là hỏi thẳng lên kênh chat và đẩy toàn bộ gánh nặng tìm kiếm về phía TA.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Discord Auto-responder (Dyno / Carl-bot)** | [dyno.gg](https://dyno.gg) | Tự động trả lời khi phát hiện từ khóa trong tin nhắn | Cài đặt cực nhanh, chi phí bằng 0, phản hồi tức thì | Chỉ so khớp từ khóa cứng (Exact Match / Regex). Sinh viên diễn đạt khác đi một chữ là bot hoàn toàn tê liệt. | Không thể dùng Rule cứng; bắt buộc phải có cơ chế so khớp ngữ nghĩa (Semantic Search). |
| **Piazza / EdStem Forum** | [piazza.com](https://piazza.com) | Diễn đàn hỏi đáp học đường có tính năng gợi ý câu hỏi trùng | Lưu trữ câu hỏi theo luồng có cấu trúc, sinh viên gõ tiêu đề sẽ được gợi ý bài viết tương tự | Nằm ngoài luồng làm việc tự nhiên: Sinh viên ngại mở thêm một trang web riêng biệt khi đang quen thảo luận trên Discord/Teams. | Phải đưa giải pháp đến đúng nơi sinh viên đang sinh hoạt (in-situ on Discord/LMS), không bắt họ chuyển app. |
| **DocsBot AI / Mendable AI (RAG Docs)** | [docsbot.ai](https://docsbot.ai) | Truy hồi tài liệu (RAG) rồi sinh câu trả lời bằng LLM cho câu hỏi chưa có sẵn đáp án | Hiểu câu hỏi tự nhiên rất mượt, trả lời được cả những câu chưa ai từng hỏi, tổng hợp được từ tài liệu dài | Một lượt truy hồi duy nhất: nếu câu hỏi thiếu ngữ cảnh hoặc gộp nhiều lỗi thì truy hồi trượt, và mô hình vẫn cố sinh câu trả lời dẫn tới ảo giác | Giữ RAG nhưng buộc trích dẫn nguồn và cho phép mô hình lặp lại việc truy hồi / hỏi làm rõ thay vì trả lời bừa; không tìm ra bằng chứng thì phải im lặng và escalate. |
| **Intercom Fin / Zendesk Answer Bot** | [intercom.com/fin](https://www.intercom.com/fin) | Trả lời ticket lặp lại, ticket nào bot không xử lý được thì chuyển cho người trực | Vòng đời khép kín: câu trả lời của nhân viên được đưa ngược vào kho tri thức, tỷ lệ tự động hóa tăng dần theo thời gian | Kho tri thức có thể bị nhiễm bẩn nếu nội dung được ghi vào mà không ai hậu kiểm | Đây chính là vòng lặp nhóm cần: mọi câu TA trả lời trong ticket đều phải quay về kho Q&A, nhưng entry mới phải gắn cờ chờ TA hậu kiểm. |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Nhóm NÊN BUILD một bot hỏi đáp ngay trong kênh chat Discord/LMS với ba tầng nối tiếp: tra kho Q&A nội bộ bằng vector search cho câu lặp lại, truy hồi tài liệu môn học và docs chính thức (RAG) cho câu chưa có trong kho, và mở ticket cho TA khi không đủ bằng chứng để kết luận; mọi câu trả lời được xác nhận thành công đều được ghi ngược vào kho Q&A để tầng 1 ngày càng phủ rộng. Nhóm KHÔNG BUILD chatbot trả lời tự do không trích dẫn nguồn — mỗi câu trả lời bắt buộc chỉ ra tài liệu hoặc entry Q&A đứng sau nó, không tìm được thì escalate chứ không đoán. Nhóm cũng KHÔNG xây dựng web portal riêng vì sẽ làm tăng ma sát và lặp lại đúng thất bại của Piazza trong bối cảnh lớp học này.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png`

```text
CURRENT STATE — Trung bình 75-105 phút/câu hỏi (Chờ đợi & Trả lời thủ công lặp lại)

[1. Sinh viên chạy lab gặp lỗi: 5' - SV]
  → [2. Chụp ảnh/paste log lên Discord #hoi-dap: 2' - SV]
  → [3. Câu hỏi nằm chờ trên channel: 45-60' - Handoff chờ TA]
  → [4. TA đọc tin nhắn & nhận diện lỗi lặp lại: 3' - TA]
  → [5. TA lục tin cũ tìm link hoặc gõ lại cách sửa: 10' - TA]  <-- BOTTLENECK
  → [6. Sinh viên đọc hướng dẫn & sửa lỗi trên máy: 15' - SV]
  → [7. Báo cáo lại kết quả / hỏi tiếp: 5' - SV]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Sinh viên | Đề bài lab, code đang viết | Lỗi terminal / crash app (CUDA, ModuleNotFound, Sai đường dẫn) | 5 phút / mỗi lần gặp lỗi | Khởi phát vấn đề |
| 2 | Sinh viên | Log lỗi trên màn hình | Tin nhắn thắc mắc trên Discord channel `#hoi-dap` | 2 phút / 40-50 câu hỏi mỗi tuần | Thường kèm câu hỏi mơ hồ: "anh ơi code em không chạy" |
| 3 | Kênh Discord | Tin nhắn của sinh viên | Thông báo (notification) đến TA | 45-60 phút chờ đợi | **Handoff bị nghẽn** do độ trễ khi TA bận việc hoặc đang offline |
| 4 | Trợ giảng (TA) | Tin nhắn của sinh viên | Xác định lỗi này đã có người hỏi trước đó | 3 phút / câu hỏi | TA phải đọc và dịch ý nghĩa lỗi từ mô tả lộn xộn của sinh viên |
| 5 | Trợ giảng (TA) | Lỗi đã xác định | Đoạn text giải pháp / link câu trả lời cũ trong channel | 10 phút / câu hỏi | **BOTTLENECK CHÍNH:** Lục tìm tin cũ hoặc gõ lại các bước sửa thủ công |
| 6 | Sinh viên | Hướng dẫn của TA | Chạy lại lệnh terminal, sửa code theo hướng dẫn | 15 phút / lần sửa | Sinh viên tự thao tác trên máy cá nhân |
| 7 | Sinh viên | Kết quả sau sửa | Xác nhận đã chạy được hoặc tiếp tục hỏi | 5 phút / lần | Nếu vẫn lỗi, lặp lại quy trình từ bước 2 |

**Bottleneck chính (2-3 câu):**

```text
Điểm nghẽn nghiêm trọng nhất nằm ở bước 5 (TA mất 10 phút lục lọi tin nhắn cũ hoặc gõ lại cùng một hướng dẫn) cộng hưởng với bước 3 (sinh viên phải chờ 45-60 phút khi TA không online). Sự tắc nghẽn kép này làm sinh viên bị đóng băng tiến độ làm bài cận kề deadline, trong khi TA bị vắt kiệt thời gian và sức lực bởi hàng chục câu hỏi lặp lại giống hệt nhau vào mỗi mùa nộp lab.
```

### 5.2. Future workflow bản nhóm

Phải nhìn ra 5 thứ: bước nào máy (Rule), bước nào AI, bước nào người, boundary ở đâu, fallback khi AI sai.

```text
FUTURE STATE — 17-18 phút/câu hỏi (Bot hỏi đáp 3 tầng + vòng lặp tự bồi đắp kho Q&A)

[1. SV gửi câu hỏi/log lỗi vào #hoi-dap: 2' - Người]
  → [2. Rule kiểm tra format tin nhắn (thiếu log thì nhắc dán log): 5s - Máy (Rule)]
  → [3. TẦNG 1 — Vector search trên kho Q&A nội bộ: 10s - Máy (Workflow)]
     → [3A. Similarity >= 85%: trả lời entry đã có + trích dẫn ai đã duyệt, ngày nào: 5s - Máy]
     → [3B. Similarity < 85%: chuyển xuống tầng 2]
  → [4. TẦNG 2 — Agent truy hồi tài liệu môn + docs chính thức (RAG): 30-60s - Máy (Agent)]
     Agent lặp: tách tin nhắn gộp nhiều lỗi → hỏi lại SV nếu thiếu OS/phiên bản/log
     → viết lại truy vấn sang thuật ngữ kỹ thuật EN → truy hồi → tự đánh giá đủ bằng chứng chưa
     → [4A. Đủ bằng chứng: trả lời kèm trích dẫn tài liệu nguồn, gắn nhãn "chờ TA xác nhận": 5s]
     → [4B. Sau tối đa 3 vòng vẫn không đủ bằng chứng: chuyển xuống tầng 3]
  → [5. TẦNG 3 — Mở ticket cho TA kèm tóm tắt lỗi + những nguồn agent đã tra và vì sao
        chưa kết luận được: 15-30' - Escalation, TA trả lời trong thread]
  → [6. SV đọc giải pháp & tự chạy lệnh sửa trên máy: 15' - HUMAN BOUNDARY]
  → [7. SV bấm nút "Đã fix được" / "Chưa được": 5s - Người]
  → [8. VÒNG LẶP HỌC: cặp Q&A được xác nhận "Đã fix" (kể cả câu TA trả lời trong ticket)
        được agent chuẩn hóa và ghi vào kho Q&A với cờ `chưa kiểm duyệt`: 5s - Máy]
  → [9. TA duyệt hàng chờ hậu kiểm, entry hợp lệ được lên cờ `đã duyệt`: 10'/tuần - TA]

Boundary: Máy chỉ đọc và trả lời. Mọi thao tác chạy lệnh, sửa code trên máy sinh viên
đều do sinh viên tự làm ở bước 6 — hệ thống không có quyền truy cập máy sinh viên.

Fallback: SV bấm "Chưa được" → nhảy thẳng xuống tầng 3, đồng thời entry nghi ngờ bị đánh
dấu để TA rà lại. Nếu tầng 2 sai liên tục, tắt tầng 2 và hệ thống thoái lui về
Workflow tầng 1 + ticket, không mất khả năng phục vụ.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| **Tổng thời gian xử lý** | 75–105 phút / câu hỏi | 17 phút nếu trúng tầng 1 (20s + 15' tự sửa); 18 phút nếu qua tầng 2; 35 phút nếu phải mở ticket | Bấm giờ từ lúc gửi câu hỏi đến khi lỗi được khắc phục, tách theo tầng xử lý |
| **Số bước quy trình** | 7 bước thủ công | 9 bước nhưng chỉ 3 bước cần người (gửi hỏi, tự sửa, bấm xác nhận) | Đếm số điểm chạm (touchpoints) cần đến con người |
| **Số bước thủ công của TA** | 2 bước (bước 4 đọc & bước 5 gõ lại) | 0 bước với câu trúng tầng 1 và tầng 2; chỉ còn trả lời ticket tầng 3 + 10 phút hậu kiểm mỗi tuần | Log thống kê tỷ lệ can thiệp của TA qua bot Discord |
| **Bottleneck chính** | TA lục tìm tin cũ & SV chờ đợi (55–70 phút) | Không còn bottleneck ở khâu trả lời; chuyển thành thời gian SV tự thao tác trên máy (15 phút) | Thống kê Response Time trung bình trên kênh chat |
| **Độ phủ kho Q&A** | 0 (kiến thức nằm rải rác trong lịch sử chat, không tra cứu được) | Kho tự lớn dần mỗi tuần; tỷ lệ câu trúng ngay tầng 1 tăng dần, tỷ lệ phải mở ticket giảm dần | Đếm số entry mới được ghi và số entry TA duyệt mỗi tuần; vẽ tỷ lệ hit tầng 1 theo tuần |
| **Risk mới** | TA quá tải, sinh viên trễ deadline | Tầng 2 trả lời sai nhưng SV vô tình fix được vì lý do khác → entry sai lọt vào kho và được phục vụ mãi (nhiễm bẩn kho); sinh viên ỷ lại hỏi mà không tự đọc | Đo tỷ lệ SV bấm "Chưa được"; đếm số entry bị TA loại trong hàng chờ hậu kiểm mỗi tuần |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Trợ giảng (TA) phụ trách các buổi thực hành lab và Sinh viên các lớp kỹ thuật/AI phải hoàn thành bài tập lớn/đồ án theo deadline. |
| **Workflow** | Sinh viên gặp lỗi khi làm lab $\rightarrow$ đăng thắc mắc lên kênh chat Discord/LMS $\rightarrow$ chờ TA trực tuyến $\rightarrow$ TA tra cứu lại câu trả lời cũ $\rightarrow$ gửi hướng dẫn sửa lỗi $\rightarrow$ sinh viên áp dụng vào máy cá nhân. |
| **Bottleneck** | TA mất 5–10 phút/lần lục tìm và gõ lại cùng một hướng dẫn sửa lỗi, kết hợp với độ trễ 45–60 phút sinh viên phải chờ TA online, gây tắc nghẽn luồng hỗ trợ nghiêm trọng vào các tuần cao điểm nộp bài. |
| **Impact** | TA mất 4–6 tiếng/tuần làm công việc sao chép lặp đi lặp lại, dẫn đến kiệt sức và không còn thời gian hỗ trợ các lỗi logic phức tạp; sinh viên bị gián đoạn tiến độ thực hành, dễ nộp bài trễ hạn và chịu điểm phạt. |
| **Success Metric** | Giảm thời gian phản hồi câu hỏi lặp lại từ 60 phút xuống dưới 30 giây; giảm $\ge 70\%$ số câu hỏi TA phải gõ tay; đạt tỷ lệ $\ge 80\%$ sinh viên tự sửa lỗi thành công sau phản hồi tự động; kho Q&A tự bồi đắp để tỷ lệ câu trúng ngay tầng 1 tăng đều qua từng tuần. |
| **Boundary** | **Phạm vi làm:** Trả lời lỗi cài đặt, lỗi môi trường, lỗi cú pháp bài lab bằng kho Q&A nội bộ; nếu chưa có thì truy hồi tài liệu môn và docs chính thức để trả lời kèm trích dẫn; không đủ bằng chứng thì mở ticket cho TA; ghi ngược câu trả lời thành công vào kho.<br>**Phạm vi KHÔNG làm:** Không truy cập hay tự chạy lệnh trên máy sinh viên, không giải bài tập logic hộ sinh viên, không trả lời khi không chỉ ra được nguồn (không có nguồn thì escalate chứ không đoán). |

**Câu hỏi AI phản biện v0 (nếu có):**
- **Field nào mơ hồ:** AI chỉ ra rằng Success Metric "$\ge 80\%$ sinh viên tự sửa lỗi thành công" rất khó đo nếu sinh viên đọc xong rồi im lặng rời đi; Boundary chưa nói cách xử lý khi sinh viên gửi ảnh chụp màn hình thay vì copy text log; và nguy hiểm nhất là cơ chế ghi ngược kho Q&A chưa có chốt chặn — nếu tầng 2 trả lời sai mà sinh viên vô tình fix được vì lý do khác, entry sai sẽ vào kho rồi được tầng 1 phục vụ mãi mãi với độ tin cậy cao.
- **Tôi sửa gì:** Nhóm bổ sung nút tương tác bắt buộc ("Đã fix được" / "Chưa được") ngay dưới mỗi câu trả lời để lượng hóa; quy định MVP chỉ xử lý log dạng text, gặp ảnh thì bot hướng dẫn cách copy text terminal; và thêm cơ chế hai cấp cho kho Q&A — entry sinh từ tầng 2 vào kho với cờ `chưa kiểm duyệt` và luôn hiển thị kèm nhãn cảnh báo, chỉ lên cờ `đã duyệt` sau khi TA rà trong hàng chờ hậu kiểm hàng tuần.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [x] Thấp (có đúng/sai rõ) / [ ] Cao (nhiều cách trả lời vẫn OK) — Vì sao: Lỗi lab và môi trường kỹ thuật (CUDA, thiếu module, sai đường dẫn) có tính đúng/sai tuyệt đối; lệnh sửa lỗi đưa ra hoặc là khắc phục được, hoặc là tiếp tục báo lỗi, không có vùng mập mờ. **Lưu ý:** mơ hồ nằm ở *đầu vào và đường đi tìm đáp án*, không nằm ở đáp án — sinh viên hỏi "anh ơi code em không chạy" và hay gộp 2-3 lỗi trong một tin nhắn (bằng chứng mục 4.1), nên không biết trước phải tra bao nhiêu vòng và tra ở đâu mới đủ kết luận.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: Quy trình đi qua nhiều nguồn nối tiếp: tiếp nhận tin nhắn $\rightarrow$ trích xuất log $\rightarrow$ tra kho Q&A nội bộ $\rightarrow$ nếu trượt thì truy hồi tài liệu môn và docs chính thức $\rightarrow$ tự đánh giá bằng chứng $\rightarrow$ rẽ nhánh trả lời hoặc mở ticket $\rightarrow$ ghi ngược kết quả vào kho.

**Bài toán nhóm nằm ở ô nào:**

```text
Phần lớn khối lượng (câu lặp lại) nằm ở ô "Mơ hồ Thấp + Phức tạp Cao" → Workflow.
Một phần nhỏ (câu hỏi mơ hồ, gộp nhiều lỗi, chưa có trong kho) trôi sang ô
"đường đi không xác định trước" → cần Agent lặp truy hồi. Nhóm cắt bài toán theo đúng
hai vùng này thay vì ép cả hệ thống vào một mức.
```

**Vì sao (2-3 câu):**

```text
Đáp án kỹ thuật luôn đúng/sai rõ ràng nên không có chỗ cho AI sáng tạo tự do — đây là lý do tầng 1 và tầng 2 đều bị buộc phải trích dẫn nguồn. Nhưng số bước để đi tới đáp án thì không cố định được: có câu chỉ cần một lần tra kho, có câu phải hỏi lại sinh viên rồi tách lỗi rồi truy hồi vài vòng mới đủ bằng chứng. Vì vậy nhóm dùng Workflow cho vùng số bước biết trước và chỉ mở Agent ở vùng số bước không biết trước, thay vì trả giá token và rủi ro cho toàn bộ câu hỏi.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Dùng regex / từ khóa cứng (như Carl-bot) để tự động trả lời khi phát hiện từ khóa | Chỉ đủ khi sinh viên gõ đúng 100% từ khóa chuẩn (như `CUDA_ERROR`, `ModuleNotFoundError`) | Sinh viên dùng ngôn ngữ tự nhiên ("anh ơi code văng", "máy không nhận card") thì Rule hoàn toàn bất lực (< 20% case) | **CHỌN cho tầng 0** — tiền xử lý định dạng: thiếu log thì nhắc sinh viên dán log. Mất 5 giây, không tốn token, chặn sớm các tin nhắn không thể xử lý. |
| **Workflow** | Vector search câu hỏi trên kho Q&A nội bộ, so ngưỡng similarity 85% rồi rẽ nhánh: trúng thì trả lời entry cũ, trượt thì đẩy xuống tầng dưới | Đủ cho ~70% câu hỏi trùng lặp — đây là các câu đã có người hỏi và đã có đáp án được xác nhận | Trả lời nhầm nếu hai lỗi mô tả gần giống nhau nhưng bản chất khác; chịu chết hoàn toàn với câu chưa từng ai hỏi | **CHỌN cho tầng 1** — xương sống của hệ thống. Cố tình không dùng LLM sinh văn bản ở tầng này để giữ tốc độ, chi phí gần 0 và tuyệt đối không bịa. |
| **Agent** | LLM được cấp bộ tool **chỉ đọc**: `search_qna`, `search_docs` (tài liệu môn + docs chính thức), `ask_clarify`, `create_ticket`, `write_qna`. Agent tự lặp: tách tin nhắn gộp nhiều lỗi, hỏi lại sinh viên khi thiếu ngữ cảnh, viết lại truy vấn, tự đánh giá bằng chứng đã đủ chưa, tối đa 3 vòng | Cần khi câu hỏi trượt kho Q&A: không biết trước phải tra mấy vòng và tra ở đâu, nên không viết được thành cây quyết định cố định | Ảo giác nếu truy hồi trượt mà vẫn cố trả lời; chi phí token cao hơn tầng 1; entry sai có thể lọt vào kho qua vòng lặp ghi ngược | **CHỌN cho tầng 2-3**, với ba chốt chặn: bắt buộc trích dẫn nguồn, không đủ bằng chứng thì mở ticket chứ không đoán, và entry mới vào kho ở cờ `chưa kiểm duyệt`. **KHÔNG cấp quyền terminal hay ghi file trên máy sinh viên.** |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. **Rule có giải được 70-80% case không?** Không, Rule chỉ bắt được tối đa 15-20% trường hợp vì sinh viên diễn đạt lỗi bằng ngôn ngữ tự nhiên vô cùng phong phú.
2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?** Quy trình bắt buộc phải rẽ nhánh: Nếu độ tương đồng $\ge 85\%$ thì trả lời ngay bằng giải pháp mẫu; nếu $< 85\%$ hoặc lỗi mới thì tự động chuyển tiếp (escalate) cho TA.
3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?** Cần, nhưng chỉ ở tầng 2. Việc hỏi "câu này đã có trong kho chưa" không cần Agent — đó chỉ là so ngưỡng similarity rồi rẽ nhánh, một câu `if` là xong. Agent cần thiết ở đúng nhóm câu trượt kho Q&A: tin nhắn "code em không chạy" hoặc gộp 2-3 lỗi (bằng chứng mục 4.1) không thể viết thành cây quyết định cố định, phải để mô hình tự quyết định hỏi lại gì, tra nguồn nào, tra thêm vòng nữa hay dừng lại mở ticket.
4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?** Sinh viên phát hiện đầu tiên khi chạy lệnh không thành công, bấm nút "Chưa được" và hệ thống mở ticket cho TA trong 10-15 phút. Lớp phát hiện thứ hai là TA trong hàng chờ hậu kiểm hàng tuần, nơi các entry `chưa kiểm duyệt` bị rà lại và loại nếu sai — chốt này quan trọng vì có trường hợp câu trả lời sai nhưng sinh viên vẫn fix được vì lý do khác, nút bấm không bắt được.
5. **Có hạ được từ Agent → Workflow → Rule không?** Hạ được, và nhóm đã hạ sẵn ở 2/3 tầng. Tắt tầng 2 thì hệ thống thành Workflow thuần: tra kho Q&A, trượt thì mở ticket cho TA — vẫn phục vụ được 70% câu lặp lại. Hạ tiếp về Rule thì vẫn còn bot nhắc định dạng bài đăng. Đây cũng chính là đường thoái lui trong mục Exit/rollback.

**Mức chọn:**

```text
Hybrid — Rule (tầng 0: kiểm định dạng) + Workflow (tầng 1: tra kho Q&A theo ngưỡng)
+ Agent (tầng 2-3: truy hồi tài liệu nhiều vòng, mở ticket, ghi ngược kho Q&A)
```

**Vì sao chọn (3-4 câu):**

```text
Nhóm không chọn một mức duy nhất vì bài toán có hai vùng khác hẳn nhau về bản chất: vùng câu lặp lại đã biết trước đường đi, và vùng câu mới không biết trước phải tra mấy vòng. Ép cả hệ thống thành Workflow thì mất trắng nhóm câu hỏi khó nhất — đúng nhóm mà TA đang tốn nhiều thời gian nhất; ép cả hệ thống thành Agent thì trả giá token và rủi ro ảo giác cho cả 70% câu hỏi vốn chỉ cần tra kho là xong. Cắt theo tầng cho phép mỗi mức làm đúng việc nó giỏi, đồng thời tạo ra đường thoái lui rõ ràng khi tầng trên hỏng. Vòng lặp ghi ngược kho Q&A khiến tỷ lệ câu phải chạm tới Agent giảm dần theo thời gian, nên chi phí vận hành đi xuống chứ không đi lên.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule đơn thuần đã được thực tế chứng minh là thất bại vì sinh viên không bao giờ gõ đúng từ khóa kỹ thuật khi hoảng loạn trước deadline — hơn 80% câu hỏi sẽ bị bỏ sót. Workflow thuần giải quyết tốt câu lặp lại nhưng chịu chết với mọi câu chưa từng ai hỏi: kho Q&A ban đầu rỗng, không có tầng RAG thì mọi câu mới đều rơi hết vào ticket và TA vẫn phải gõ tay như cũ, kho cũng không có gì để tự lớn lên. Nói cách khác, bỏ Agent thì vòng lặp tự bồi đắp — giá trị cốt lõi của giải pháp — không khởi động được.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Trợ giảng (TA) phụ trách hướng dẫn thực hành và Sinh viên các lớp kỹ thuật/AI thực hiện bài tập lớn/đồ án theo deadline. |
| **Workflow** | Sinh viên gặp lỗi khi làm lab $\rightarrow$ đăng câu hỏi kèm text log lên Discord channel `#hoi-dap` $\rightarrow$ bot tra kho Q&A nội bộ, trúng thì trả lời ngay $\rightarrow$ trượt thì agent truy hồi tài liệu môn và docs chính thức để trả lời kèm trích dẫn $\rightarrow$ không đủ bằng chứng thì mở ticket cho TA $\rightarrow$ sinh viên tự chạy lệnh sửa trên máy và bấm xác nhận $\rightarrow$ cặp Q&A thành công được ghi ngược vào kho chờ TA hậu kiểm. |
| **Bottleneck** | TA mất 5–10 phút/lần lục tìm và gõ lại cùng một hướng dẫn sửa lỗi, kết hợp với độ trễ 45–60 phút sinh viên phải chờ TA online, gây tắc nghẽn luồng hỗ trợ nghiêm trọng vào các tuần cao điểm nộp bài. |
| **Impact** | TA mất 4–6 tiếng/tuần làm công việc sao chép lặp đi lặp lại, dẫn đến kiệt sức và không còn thời gian hỗ trợ các lỗi logic phức tạp; sinh viên bị gián đoạn tiến độ thực hành, dễ nộp bài trễ hạn và chịu điểm phạt. |
| **Success Metric** | Giảm thời gian phản hồi câu hỏi lặp lại từ 60 phút xuống dưới 30 giây; giảm $\ge 70\%$ số câu hỏi TA phải gõ tay; $\ge 80\%$ sinh viên tự sửa lỗi thành công sau phản hồi tự động; tỷ lệ câu trúng ngay tầng 1 tăng đều qua từng tuần nhờ vòng lặp ghi ngược kho Q&A. |
| **Boundary** (làm / không làm) | **Làm:** Trả lời lỗi cài đặt, lỗi môi trường, lỗi cú pháp bài lab từ kho Q&A nội bộ; truy hồi tài liệu môn học và docs chính thức (Python, CUDA, PyTorch) để trả lời câu chưa có trong kho, kèm trích dẫn nguồn; hỏi lại sinh viên khi thiếu ngữ cảnh; mở ticket cho TA khi không đủ bằng chứng; ghi cặp Q&A thành công vào kho ở trạng thái chờ hậu kiểm.<br>**Không làm:** Không truy cập, chạy lệnh hay sửa code trên máy sinh viên; không giải bài tập logic hộ sinh viên; không trả lời khi không chỉ ra được nguồn; không tự đưa entry lên trạng thái `đã duyệt` nếu chưa có TA rà. |
| **AI intervention point** | Can thiệp ngay sau **Bước 1** (sinh viên gửi câu hỏi) và kết thúc trước **Bước 6** (trước khi sinh viên thao tác chạy lệnh trên máy cá nhân); quay lại một lần nữa ở **Bước 8** để chuẩn hóa cặp Q&A ghi vào kho. Ranh giới cứng: AI chỉ đọc và viết vào kho Q&A của lớp, không chạm vào máy sinh viên. |
| **Mức chọn** | **Hybrid**: Rule kiểm định dạng (tầng 0) + Workflow vector search kho Q&A (tầng 1, phục vụ ~70% câu lặp lại) + Agent truy hồi nhiều vòng (tầng 2-3, cho câu trượt kho và mở ticket). Mỗi tầng chỉ nhận phần việc mà tầng dưới nó không làm nổi. |
| **Rủi ro & người thật kiểm tra** | (1) Bot đưa sai giải pháp do câu hỏi thiếu ngữ cảnh — chặn bằng cơ chế agent hỏi lại trước khi trả lời. (2) Ảo giác ở tầng 2 — chặn bằng yêu cầu trích dẫn bắt buộc, không có nguồn thì escalate. (3) **Kho Q&A bị nhiễm bẩn**: entry sai lọt vào kho vì sinh viên fix được do lý do khác rồi được tầng 1 phục vụ mãi — chặn bằng cờ `chưa kiểm duyệt` và hàng chờ TA hậu kiểm hàng tuần. Người thật kiểm tra: **Sinh viên** (chạy lệnh, bấm nút phản hồi) và **TA** (trả lời ticket, duyệt hàng chờ). |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Đã xác định rõ luồng tương tác giữa Sinh viên, Bot Discord và Trợ giảng. |
| Baseline + metric đo được chưa? | **Yes** | Baseline 45-60 phút chờ và 70% câu hỏi trùng lặp; đo bằng thời gian phản hồi và số lượng ticket can thiệp. |
| Data/input đủ dùng chưa? | **Yes** | Đã có log 45 câu hỏi tuần trước và tài liệu hướng dẫn lab các kỳ trước để mồi kho Q&A tầng 1; tầng 2 dùng tài liệu môn học đã số hóa cộng docs chính thức của Python/CUDA/PyTorch, đều truy cập công khai được. |
| AI sai, hậu quả chấp nhận được không? | **Yes** | Sinh viên mất 1-2 phút nhận ra lệnh không chạy rồi bấm "Chưa được" để mở ticket. Hậu quả nặng hơn là entry sai lọt vào kho, nhưng đã có cờ `chưa kiểm duyệt` và hàng chờ hậu kiểm chặn lại trong vòng một tuần. |
| Có người review/owner không? | **Yes** | TA của lớp là owner: trả lời ticket tầng 3 và duyệt hàng chờ entry mới (ước tính 10 phút/tuần). |
| Có cách non-AI đơn giản hơn không? | **No** | Đã thử file FAQ và ghim tin nhắn nhưng sinh viên không tự tìm kiếm được do rào cản từ khóa. |

**Decision:**

```text
[Go]
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Quyết định Go hoàn toàn dựa trên bằng chứng thực tế: 68.8% câu hỏi trên Discord là trùng lặp, gây lãng phí 4-6 tiếng/tuần của TA và làm sinh viên chờ đợi hàng giờ trước deadline. Kiến trúc Hybrid xử lý được cả hai phía của bài toán — tầng 1 dập phần lặp lại với chi phí gần 0, tầng 2-3 lo phần câu hỏi mới mà trước đây luôn rơi hết vào tay TA. Rủi ro lớn nhất là ảo giác và nhiễm bẩn kho Q&A, cả hai đều đã có chốt chặn cụ thể (bắt buộc trích dẫn, cờ chưa kiểm duyệt, hậu kiểm hàng tuần) chứ không chỉ là lời hứa. Giải pháp cũng có đường thoái lui từng tầng nên rủi ro triển khai được giới hạn.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
- Data: Mồi kho Q&A bằng 20 cặp phổ biến nhất của Bài Lab 1 (cài môi trường Python, PyTorch, CUDA); nạp tài liệu môn học và docs chính thức cho tầng 2 truy hồi.
- Chạy thử: Tích hợp bot vào 1 channel Discord thử nghiệm của lớp; chạy song song với TA trong 1 tuần nộp bài lab đầu tiên, TA vẫn trả lời như bình thường để đối chiếu.
- Đo 3 số:
  1. Thời gian phản hồi trung bình (mục tiêu: < 30 giây với câu trúng tầng 1).
  2. Tỷ lệ câu hỏi bot tự giải quyết thành công, tách riêng tầng 1 và tầng 2 (mục tiêu chung: >= 70%).
  3. Số entry mới ghi vào kho và tỷ lệ entry được TA giữ lại khi hậu kiểm (mục tiêu: >= 80%) — đây là số đo sức khỏe của vòng lặp học.
```

**Nếu Not Yet — cần validate gì trước:**

```text
(Không áp dụng vì nhóm đã chọn GO)
```

**Nếu No-Go — làm gì thay AI:**

```text
(Không áp dụng vì nhóm đã chọn GO)
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Nhóm thoái lui theo từng tầng chứ không tắt cả hệ thống:
- Tắt tầng 2 (Agent RAG) nếu trong 3 ngày đầu, tỷ lệ sinh viên bấm "Chưa được" với câu trả lời tầng 2 vượt quá 40%, hoặc TA loại quá 30% entry mới trong lần hậu kiểm đầu tiên (dấu hiệu kho Q&A đang bị nhiễm bẩn). Khi đó hệ thống chạy như Workflow thuần: tra kho Q&A, trượt thì mở ticket cho TA.
- Tắt tiếp tầng 1, quay về hỏi đáp thủ công hoàn toàn nếu ngay cả tầng 1 cũng trả lời sai trên 40%, nghĩa là phải chuẩn hóa lại bộ Vector Embeddings và ngưỡng tương đồng trước khi chạy lại.
- Trong mọi trường hợp, kho Q&A đã tích lũy vẫn giữ nguyên giá trị vì TA có thể tra tay như một file FAQ có cấu trúc.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do

