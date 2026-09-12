# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trần Ngọc Khuyến
- Mã học viên: 2A202602682
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): sinh viên năm 4 đang tham gia khóa AI thực chiến của VinUni 
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    - Đọc và phân tích các paper để đưa ra ý tưởng chính cho đồ án tốt nghiệp
    - Code thực nghiệm mô hình Deep Learning (PyTorch) trên Google Colab / server GPU
    - Tham gia các buổi lab thực hành AI thực chiến và làm bài tập nộp GitHub Classroom
    - Họp nhóm đồ án hàng tuần, tổng hợp tiến độ và báo cáo cho Giảng viên hướng dẫn

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Đọc và so sánh các phương pháp từ 5-7 research papers để viết Related Work cho khóa luận. | Sinh viên năm 4 | Mất 4-6 tiếng/papers, đọc xong dễ quên điểm khác biệt cốt lõi giữa các baseline. |
| 2 | Lặp lại | Tóm tắt lý thuyết, code snippet và công thức sau mỗi buổi học/lab vào Notion cá nhân. | Sinh viên | 4-6 buổi/tuần, mỗi buổi mất 1-2 tiếng để lọc nội dung và ghi chép lại. |
| 3 | Pain từ người khác |  Trợ giảng / Giảng viên bị sinh viên hỏi lặp đi lặp lại về cùng một vấn đề. | TA, giảng viên, sinh viên | TA nhận 20-30 tin nhắn cùng 1 câu hỏi trên Discord mỗi đầu buổi lab, mất 30p - 1 tiếng trả lời lặp lại. |
| 4 | Lặp lại | Chuyển đổi báo cáo tiến độ đồ án nhóm hàng tuần từ docs + Git commit log thành slide báo cáo giảng viên hướng dẫn. | Thành viên nhóm | Mỗi tuần mất 30p-1h để gom thông tin và 2-4h để làm thành slide. |
| 5 | Pain từ người khác | Bạn cùng nhóm viết commit message cụt ngủn ("fix", "update"), không viết docstrings khiến người merge code phải hỏi đi hỏi lại. | Người merge code, cả nhóm | Tốn thêm 30p mỗi buổi họp để nghe giải thích rõ từng phần commit. |
| 6 | AI có thể tốt hơn | Review và tự chấm bài tập code trước khi nộp theo bảng rubric tiêu chí (format, clean code, comment, edge case). | Sinh viên | Trước khi nộp dùng AI để review lại bài tập, nếu phát hiện chỗ sai thì sửa chữa kịp thời. |
| 7 | Tốn thời gian | Tìm kiếm lại một quyết định thiết kế kiến trúc mô hình trong tin nhắn nhóm. | Nhóm trưởng, thành viên | Mất 15-20p search lại tin nhắn trong nhóm |
| 8 | AI có thể tốt hơn | So sánh, tư duy trade-off giữa các thay đổi công nghệ/mô hình AI. | Sinh viên | 1-2 lần/tháng khi đổi tech stack; mất 3-4 tiếng đọc benchmark & trade-off; dùng AI brainstorm và phản biện nhiều vòng để tìm phương án tối ưu. |
| 9 | Lặp lại | Label các class trong dataset ảnh để chuẩn bị dữ liệu cho đồ án tốt nghiệp. | Thành viên trong nhóm | Dataset 1.500 ảnh, 4 thành viên mất 2 tuần, mỗi ảnh mất 2-3 phút check từng object và kéo thả bounding box cho khớp. |
| 10 | AI có thể tốt hơn | Giải thích lỗi Runtime / CUDA Out-of-Memory (OOM) khi train PyTorch. | Sinh viên | Xảy ra 3-5 lần/tuần khi train trên Colab; mất 30-60 phút mò tensor shape và VRAM allocation để tìm đúng lỗi tràn bộ nhớ. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Gợi ý các công việc lặp lại, tốn thời gian hoặc hay gặp lỗi của sinh viên năm cuối làm đồ án tốt nghiệp ngành AI".
- Ý dùng được: Nhớ ra vấn đề label dataset ảnh thủ công (#9) và lỗi CUDA OOM khi train model (#10).
- Ý bỏ vì không phải pain thật: Ý tưởng "AI gợi ý cách quản lý thời gian sinh viên" vì quá chung chung, không có workflow và metric cụ thể.

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
| 1 | #4: Chuyển đổi báo cáo tiến độ đồ án nhóm hàng tuần từ docs + Git commit log thành slide báo cáo giảng viên hướng dẫn. | - Workflow lặp lại hàng tuần rất rõ ràng (30p gom + 2-4h làm slide).<br>- Dữ liệu đầu vào cụ thể (Git commits, docs) và đầu ra rõ ràng (slide).<br>- Tác động trực tiếp đến đánh giá của GVHD. | Chất lượng tóm tắt kỹ thuật của AI có đủ sâu để GVHD hiểu ngữ cảnh không. |
| 2 | #1: Đọc và so sánh các phương pháp từ 5-7 research papers để viết Related Work cho khóa luận. | - Pain thực tế lớn nhất của sinh viên năm 4 (4-6h/paper).<br>- Thế mạnh cốt lõi của LLM là đọc hiểu và tổng hợp văn bản dài.<br>- Dễ đo lường thời gian tiết kiệm. | Khả năng AI trích xuất sai số liệu trong các bảng benchmark phức tạp của file PDF. |
| 3 | #3: Trợ giảng / Giảng viên bị sinh viên hỏi lặp đi lặp lại về cùng một vấn đề/lỗi lab. | - Số lượng câu hỏi lặp lại lớn (20-30 tin/buổi lab, tốn 30p-1h).<br>- Metric đo lường cực rõ (thời gian phản hồi và số ticket giảm).<br>- Rất sát bối cảnh lớp học AI thực chiến. | Sinh viên hay chụp ảnh màn hình mờ hoặc không gửi mã lỗi traceback đầy đủ. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tổng hợp báo cáo tiến độ đồ án tuần từ Git + Docs thành Slide]

```text
Problem 1 câu:
Thành viên phụ trách mất từ 2.5 - 5 tiếng mỗi cuối tuần để gom Git commit log và ghi chép rời rạc của 4 thành viên, biên tập thành nội dung có cấu trúc và thiết kế slide báo cáo cho Giảng viên hướng dẫn.

Actor:
Trưởng nhóm hoặc thành viên phụ trách tổng hợp tiến độ đồ án tốt nghiệp (sinh viên năm 4).

Thời điểm / bối cảnh:
Tối Chủ nhật hàng tuần, trước buổi họp tiến độ định kỳ sáng thứ Hai với Giảng viên hướng dẫn.

Current workflow 3-7 bước:
1. Mở GitHub xem commit log và pull request trong tuần của cả nhóm (20')
2. Đọc file docs/trello ghi chú công việc cá nhân của các thành viên (30')
3. Nhắn tin hỏi lại các bạn về những task ghi chưa rõ hoặc kết quả thí nghiệm chưa có số (30')
4. Tổng hợp nội dung thành 4 phần: Đã làm, Kết quả số liệu, Khó khăn/Blocker, Kế hoạch tuần tới (45')
5. Tạo slide Google Slides/PowerPoint và căn chỉnh format chữ, ảnh đồ thị (90')
6. Gửi nhóm duyệt trước khi đem đi báo cáo (15')

Bottleneck:
Bước 4 & 5 — Biên tập các commit kỹ thuật khô khan thành một câu chuyện tiến độ mạch lạc và mất quá nhiều thời gian căn chỉnh layout slide thủ công.

Impact:
Tốn từ 2.5 - 5 tiếng/tuần cho 1 người (tổng cộng 30-40 tiếng cả học kỳ). Slide làm vội dễ thiếu số liệu thực nghiệm, khiến thầy cô nhắc nhở và làm giảm chất lượng buổi hướng dẫn.

Success metric:
- Giảm tổng thời gian làm báo cáo tuần từ 230 phút xuống dưới 45 phút.
- 100% các kết quả thực nghiệm và khó khăn kỹ thuật được phản ánh chính xác, không bị GVHD nhắc nhở thiếu số liệu.

Non-AI alternative:
Tạo template slide cố định sẵn và yêu cầu mỗi thành viên tự điền slide của mình vào tối thứ Bảy. (Nhược điểm: Nội dung rời rạc, không có bức tranh tổng thể, vẫn mất công format lại).

AI hypothesis:
Dùng AI đọc Git commit log + ghi chú thô của các thành viên, tự động phân loại theo mảng công việc, draft sẵn nội dung báo cáo theo chuẩn cấu trúc và chuyển thành định dạng slide.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 230 phút

[1 Gom Git log: 20'] → [2 Đọc docs: 30'] → [3 Hỏi lại thành viên: 30'] → [4 Tổng hợp nội dung: 45'] (bottleneck) → [5 Căn chỉnh slide: 90'] (bottleneck) → [6 Gửi duyệt: 15']

FUTURE STATE — 40 phút

[1 Script kéo Git log + Form cập nhật: 2'] → [2 AI cấu trúc dữ liệu: 2'] → [3 AI draft Markdown: 3'] → [4 Trưởng nhóm review: 20'] <-- human boundary → [5 Render slide qua Marp: 3'] → [6 Cả nhóm duyệt: 10']

Fallback: nếu AI sai thì trưởng nhóm dùng bản cập nhật thô và tự điền vào template slide có sẵn.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Trích xuất & Lập bảng so sánh Benchmark từ Research Papers]

```text
Problem 1 câu:
Sinh viên năm 4 mất từ 4-6 tiếng cho mỗi bài báo khoa học để đọc, chắt lọc công thức kiến trúc mô hình và chép thủ công các kết quả benchmark vào bảng so sánh Related Work của khóa luận.

Actor:
Sinh viên năm 4 ngành AI/CNTT đang làm đồ án tốt nghiệp hoặc nghiên cứu khoa học.

Thời điểm / bối cảnh:
Giai đoạn 4-6 tuần đầu làm đồ án (nghiên cứu tổng quan tài liệu) và trước mỗi đợt nộp báo cáo chương lý thuyết.

Current workflow 3-7 bước:
1. Tải paper PDF từ ArXiv / IEEE / Google Scholar (5')
2. Đọc Abstract, Intro và Conclusion để nắm đóng góp chính (30')
3. Đọc phần Methodology để nắm kiến trúc model và hàm loss (45')
4. Cuộn xuống phần Experiments tìm các bảng kết quả benchmark (30')
5. Đọc hiểu bảng và chép tay các metric (F1, Accuracy, Latency) vào file Notion/Excel (45')
6. Viết 1-2 đoạn văn so sánh ưu/nhược điểm so với đề tài của mình (45')

Bottleneck:
Bước 5 — Đọc và bóc tách các bảng kết quả phức tạp từ PDF sang bảng Excel, rất dễ nhầm cột/dòng hoặc sai điều kiện thí nghiệm.

Impact:
Một đồ án cần khảo sát 15-20 papers, tốn khoảng 80-100 tiếng của sinh viên chỉ để đọc và nhặt số liệu, làm chậm tiến độ bắt tay vào code thực nghiệm.

Success metric:
- Giảm thời gian trích xuất thông tin chính từ 200 phút xuống dưới 30 phút/paper.
- Độ chính xác trích xuất thông số (metric, dataset, baseline) đạt >= 95% sau khi người dùng kiểm tra.

Non-AI alternative:
Tạo bảng Excel mẫu với các cột cố định; dùng highlight màu trong phần mềm đọc PDF. (Nhược điểm: Vẫn phải đọc quét mắt và gõ tay từng số).

AI hypothesis:
Dùng LLM Document Understanding đọc file PDF paper, tự động trích xuất các trường: [Tác giả, Năm, Dataset, Kiến trúc, Metric chính, Điểm yếu] thành bảng Markdown chuẩn.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 200 phút

[1 Tải PDF: 5'] → [2 Đọc tổng quan: 30'] → [3 Đọc kiến trúc: 45'] → [4 Tìm bảng: 30'] → [5 Chép số vào Excel: 45'] <-- bottleneck → [6 Viết tóm tắt: 45']

FUTURE STATE — 25 phút

[1 Upload PDF: 1'] → [2 Rule tách trang kết quả: 1'] → [3 AI trích xuất bảng ra Markdown: 3'] → [4 SV đối chiếu kiểm tra số liệu: 10'] <-- human boundary → [5 AI draft nhận xét: 2'] → [6 SV lưu vào đồ án: 8']

Fallback: nếu AI đọc sai số liệu bảng thì hiển thị song song 2 màn hình để sinh viên tự gõ tay vào form.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Trợ giảng giải đáp các lỗi môi trường & code lặp lại cho lớp Lab]

```text
Problem 1 câu:
Trợ giảng (TA) bị quá tải khi phải trả lời 20-30 tin nhắn mỗi buổi lab về cùng một nhóm lỗi thiết lập môi trường (CUDA, version package, Git) khiến thời gian hỗ trợ các lỗi thuật toán chuyên sâu bị co hẹp.

Actor:
Trợ giảng (TA) và sinh viên tham gia các buổi lab thực hành AI thực chiến.

Thời điểm / bối cảnh:
30-60 phút đầu của mỗi buổi thực hành lab hoặc các ngày sát hạn nộp bài tập.

Current workflow 3-7 bước:
1. Sinh viên gặp lỗi, chụp ảnh màn hình hoặc copy dòng lỗi gửi lên Discord lớp (2')
2. TA nhận thông báo, đọc tin nhắn và xem xét ngữ cảnh bài lab (3')
3. TA nhận ra đây là lỗi quen thuộc, lục lại tin nhắn cũ hoặc file cẩm nang để tìm link/câu lệnh sửa (5')
4. TA gõ lại câu hướng dẫn kèm câu lệnh và gửi cho sinh viên (5')
5. Sinh viên làm theo và phản hồi lại (5')

Bottleneck:
Bước 3 & 4 — TA phải lặp đi lặp lại việc tra cứu cẩm nang và gõ lại cùng một hướng dẫn hàng chục lần cho nhiều sinh viên khác nhau.

Impact:
TA mất 30-60 phút mỗi buổi chỉ để gõ lại những hướng dẫn cơ bản; sinh viên phải chờ đợi 10-15 phút mới được giải đáp, gây gián đoạn mạch thực hành.

Success metric:
- Giảm thời gian chờ phản hồi của sinh viên từ 15 phút xuống dưới 2 phút.
- Giảm 70% số lượng câu hỏi lặp lại mà TA phải trực tiếp gõ trả lời.

Non-AI alternative:
Tạo 1 trang web/file FAQ tổng hợp các lỗi thường gặp và ghim lên đầu kênh Discord. (Nhược điểm: Sinh viên lười đọc FAQ, vẫn thích tag TA hỏi trực tiếp).

AI hypothesis:
Một bot lắng nghe trên kênh hỗ trợ, khi sinh viên đăng lỗi, bot dùng RAG tra cứu trực tiếp tài liệu lab để draft câu trả lời mẫu; TA chỉ cần bấm duyệt reaction để bot gửi đi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 20 phút (lặp lại 20-30 lần/buổi)

[1 SV gửi lỗi: 2'] → [2 TA đọc lỗi: 3'] → [3 TA tra cứu giải pháp: 5'] <-- bottleneck → [4 TA gõ hướng dẫn: 5'] → [5 SV làm theo: 5']

FUTURE STATE — 4 phút

[1 SV gửi lỗi lên Discord: 1'] → [2 Rule phân loại lỗi: 30s] → [3 AI đọc traceback + tra cứu tài liệu lab: 1'] → [4 TA duyệt câu trả lời: 30s] <-- human boundary → [5 Bot gửi trả lời SV: tức thì]

Fallback: nếu AI không chắc chắn (>80%) thì bot gắn tag TA để vào hỗ trợ thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Chuyển đổi báo cáo tiến độ đồ án nhóm hàng tuần từ docs + Git commit log thành slide báo cáo giảng viên hướng dẫn.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là nỗi đau có thật mà cả 4 thành viên trong nhóm đang gặp phải hàng tuần, tốn 2.5 - 4 tiếng mỗi Chủ nhật chỉ để làm slide. Workflow tuyến tính rất rõ ràng, dữ liệu đầu vào (Git log + docs) và đầu ra (slide) đều đo lường được bằng số phút cụ thể. Tối ưu được bài toán này giúp nhóm tiết kiệm hàng chục giờ quý báu để tập trung vào cải tiến mô hình và viết luận văn.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm sao để AI hiểu được ngữ cảnh kỹ thuật sâu của từng commit để viết thành insight thực chất, thay vì chỉ tóm tắt lại các câu commit cụt ngủn của các thành viên?
2. Nếu các thành viên không commit code đều đặn trong tuần thì dữ liệu đầu vào cho AI sẽ bị rỗng, nhóm giải quyết bước này thế nào?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI cảnh báo rằng nếu commit message quá ngắn ("fix", "update"), AI sẽ hallucinate (bịa ra tiến độ).
- Tôi sửa gì: Bổ sung thêm một Google Form cập nhật nhanh 3 câu hỏi (Làm gì, Kết quả đo lường gì, Khó khăn gì) để kết hợp với Git log tạo đầu vào trung thực cho AI.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
