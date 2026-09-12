# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trần Ngọc Khuyến
- Mã học viên: 2A202602682
- Nhóm: Nhóm Lab Day 02 (Đoàn Bá Khải, Trần Ngọc Khuyến, Nguyễn Phúc Bảo, Nguyễn Văn An, Nguyễn Văn Biển)
- Candidate problem nhóm chọn: Trợ giảng và Giảng viên mất nhiều giờ mỗi tuần trả lời lặp đi lặp lại các lỗi lab/môi trường phổ biến trên kênh chat, trong khi sinh viên bị nghẽn tiến độ vì phải chờ đợi giải đáp thủ công.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Quét 10 vấn đề thực tế từ bối cảnh sinh viên năm cuối làm đồ án và học lab AI; viết chi tiết 3 Problem Cards (#1 Slide đồ án, #2 So sánh paper, #3 TA hỗ trợ lỗi lab). | Đóng góp 3 bài toán sát sườn, trong đó Card #3 về giải đáp lỗi lab trở thành hạt nhân cho bài nộp của nhóm. |
| Pitch Problem Card | Ban đầu chuẩn bị pitch Card #1 (làm slide tuần), nhưng khi mở đầu thảo luận nhóm thấy nỗi đau hỗ trợ lab chạm đúng trải nghiệm chung nên đã pitch mạnh bài #4 (TA bị hỏi lặp lỗi lab). | Thuyết phục cả nhóm đồng thuận đưa bài toán này vào vòng xem xét ưu tiên cao nhất. |
| Challenge bài của bạn khác | Phản biện bài của Khải (#2 - Ảo giác tóm tắt paper) vì quá trừu tượng, khó đo lường; phản biện bài của Bảo (#7 - Rơi rụng việc họp nhóm) vì đã có nhiều công cụ thị trường làm tốt (Notion, Meet bot). | Giúp nhóm loại bỏ các bài toán khó kiểm chứng hoặc thừa thãi giải pháp, tập trung vào phạm vi vừa vặn cho buổi lab. |
| Gom trùng / cluster | Đề xuất gom các vấn đề lỗi môi trường máy ảo của An (#10), lỗi nộp bài lab của Khuyến (#6) và câu hỏi lặp lại của TA (#4) vào Cụm A (Hỗ trợ giải đáp & Lỗi bài lab). | Giúp nhóm nhìn ra bức tranh toàn cảnh về quy trình tương tác giữa Trợ giảng và Sinh viên. |
| Chọn candidate problem | Dẫn dắt việc chấm điểm ma trận (Score matrix) dựa trên 7 tiêu chí trong worksheet; bảo vệ mức điểm tối đa (35/35) cho bài toán hỗ trợ lỗi lab. | Nhóm đạt đồng thuận tuyệt đối (5/5 thành viên) chọn đề tài này thay vì tranh cãi kéo dài. |
| Validation / research | Đảm nhận vai trò **Research Lead**: phỏng vấn 1 TA và 2 sinh viên; thu thập & phân tích log 45 tin nhắn channel `#hoi-dap`; tìm hiểu 4 công cụ (Dyno, Piazza, DocsBot AI, Intercom Fin). | Cung cấp bằng chứng sống động (68.8% lỗi lặp lại), tìm ra insight "Retrieval Friction" và bài học vòng lặp học hỏi (learning loop) từ Intercom Fin. |
| Workflow nhóm | Cùng Khải và An xây dựng Future Workflow 9 bước; kiên quyết thiết kế chốt chặn Human Boundary ở bước 6 (sinh viên tự chạy lệnh) và nút phản hồi ("Đã fix" / "Chưa được"). | Đảm bảo hệ thống không can thiệp trái phép vào máy tính sinh viên và có cơ chế đo lường kết quả thực tế. |
| Problem Statement | Cùng nhóm mổ xẻ bản v0 để gọt lại Boundary: kiên quyết giới hạn bot chỉ nhận text log và trả lời có trích dẫn, cấm can thiệp vào máy sinh viên hay giải bài hộ; đồng thời sửa lại metric thành công đo bằng nút bấm thật. | Bản v1 gãy gọn, ranh giới an toàn rõ ràng, giúp nhóm không bị sa đà vào những tính năng viễn tưởng vượt quá sức của buổi lab. |
| Rule / Workflow / Agent | Lập luận lựa chọn kiến trúc Hybrid: Rule cho tầng 0 (format), Workflow cho tầng 1 (vector search kho Q&A 85%), và chỉ mở Agent cho tầng 2-3 (truy hồi nhiều vòng khi câu hỏi mơ hồ). | Ngăn chặn việc lạm dụng "Agent cho ngầu", giúp nhóm tiết kiệm chi phí token và triệt tiêu nguy cơ ảo giác lan tràn. |
| Decision | Đề xuất quyết định Go với pilot nhỏ mồi 20 cặp Q&A bài Lab 1; thiết kế phương án thoái lui (rollback) theo từng tầng nếu tầng 2 sai >40% hoặc làm bẩn kho tri thức. | Nhóm có kế hoạch triển khai khả thi, an toàn và có đường rút lui kỹ thuật rõ ràng. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc ngồi lội ngược 45 tin nhắn trong kênh #hoi-dap tuần trước để gom ra con số 68.8% lỗi trùng lặp, biến nó thành bằng chứng thuyết phục cả nhóm chọn đề tài này. Ngoài ra, chính tôi là người kiên quyết đưa vào cơ chế cờ "chưa kiểm duyệt" để chặn nguy cơ bot trả lời bậy rồi tự lưu rác vào kho Q&A của lớp.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các công việc lặp lại, tốn thời gian của sinh viên năm cuối ngành AI. | Gợi ý trúng nỗi đau label ảnh thủ công (#9) và lỗi CUDA OOM khi train model (#10). | Đưa ra các ý tưởng sáo rỗng kiểu "quản lý thời gian sinh viên", "nhắc nhở học tập" không có workflow hay metric. | Loại bỏ toàn bộ các gợi ý chung chung; chỉ giữ lại những công việc kỹ thuật có số phút đo lường thực tế. |
| Problem Card | Nhờ AI đóng vai phản biện để tìm điểm yếu dữ liệu đầu vào của Problem Card #1 và #3. | Cảnh báo việc tin nhắn cụt ngủn ("anh ơi lỗi") sẽ khiến AI hallucinate (bịa giải pháp) nếu không có context. | AI gợi ý giải pháp viễn tưởng là cài extension theo dõi toàn bộ màn hình sinh viên để lấy log tự động. | Bác bỏ gợi ý vi phạm quyền riêng tư; thay bằng quy tắc Rule kiểm tra định dạng text log bắt buộc trước khi bot tiếp nhận. |
| Workflow | Nhờ AI chuyển đổi mô tả các bước thành sơ đồ ASCII / Mermaid dạng trước và sau. | Chuyển đổi định dạng nhanh chóng, căn chỉnh thời gian trực quan cho luồng xử lý. | Tự ý gộp bước "sinh viên tự sửa lỗi" với "bot đưa giải pháp", và đề xuất bot can thiệp tự sửa file trên máy SV. | Tách độc lập bước sinh viên tự chạy lệnh (Human Boundary) và khẳng định bot chỉ được quyền đọc/trả lời chứ không chạm vào máy người dùng. |
| Research | Tìm kiếm các công cụ hỗ trợ hỏi đáp kỹ thuật và bot cộng đồng phổ biến trong giáo dục. | Liệt kê nhanh các giải pháp hiện hành: DocsBot AI, Intercom Fin, Piazza, Dyno bot Discord. | Tự bịa số liệu thống kê về độ chính xác và đưa các đường link không truy cập được. | Tự tay kiểm tra tài liệu chính thức (docs/pricing) của từng tool, loại bỏ các con số vô căn cứ và chỉ giữ lại link xác thực. |
| Problem Statement | Nhờ AI phản biện xem ranh giới làm/không làm (Boundary) và các số đo thành công của bản v0 đã đủ chặt chẽ chưa. | Cảnh báo nguy cơ kho tri thức bị nhiễm rác nếu AI trả lời ẩu mà sinh viên vô tình fix được do cách khác rồi hệ thống tự động lưu lại. | Đề xuất phức tạp hóa vấn đề: đòi tích hợp mô hình AI khác để tự động chấm điểm độ chuẩn xác của câu trả lời trước khi lưu. | Tôi nhận định máy không thể tự kiểm tra máy trong case này; tôi chốt quy trình người thật kiểm tra: gắn cờ `chưa kiểm duyệt` và bắt buộc TA phải rà tay trong hàng chờ mỗi tuần. |
| Rule / Workflow / Agent | Phân tích trade-off nếu giải quyết bài toán bằng Rule thuần túy so với Full-Agent. | Phân tích rõ nhược điểm của Rule (bị tê liệt trước từ ngữ tự nhiên) và rủi ro chi phí nếu thả nổi Agent cho 100% câu hỏi. | AI thiên vị việc xây dựng hệ thống "Multi-Agent System" phức tạp và đề xuất cấp quyền chạy lệnh bash cho agent để kiểm tra code hộ SV. | Bác bỏ hoàn toàn ý tưởng Multi-agent; hạ xuống kiến trúc Hybrid thực dụng với bộ tool chỉ đọc và cô lập Agent ở tầng xử lý câu hỏi khó. |
| Decision | *Không dùng.* | *Không dùng.* | *Không dùng.* | Nhóm tự đưa ra quyết định Go và kịch bản thoái lui dựa trên phỏng vấn thực tế và năng lực hiện có, không để AI can thiệp vào quyết định cuối. |

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
Ban đầu tôi định bảo vệ ý tưởng làm slide đồ án cá nhân, nhưng khi nghe các bạn chia sẻ thì nhận ra bài toán Trợ giảng bị quá tải lỗi lab mới là nỗi đau chung của cả lớp. Thấy bài có số đo rõ và cả nhóm đều thấm, tôi chủ động bỏ bài cũ để theo bài này. Lúc bàn giải pháp, nhóm suýt bị "ngáo Agent" khi bạn An đòi cho AI tự nhảy vào terminal để sửa code hộ sinh viên. Tôi với Khải phải cản ngay vì vừa hở bảo mật, vừa lãng phí trong khi phần lớn lỗi chỉ cần tra kho câu hỏi cũ là xong. Dấu tay rõ nhất của tôi là ngồi lọc 45 tin nhắn Discord tuần trước để ra con số 68.8% lỗi lặp lại làm bằng chứng. Khâu khó nhất khi viết Problem Statement chính là Boundary chống "bẩn" kho tri thức. Nếu AI trả lời sai mà sinh viên vô tình chạy được lệnh khác, hệ thống sẽ tự lưu rác vào kho và phục vụ mãi về sau. Vì vậy, tôi kiên quyết giữ chốt chặn: câu trả lời mới phải gắn cờ chờ TA duyệt tay mỗi tuần mới được dùng chính thức. Nếu làm lại, tôi sẽ bắt nhóm thống nhất chỉ nhận text log ngay từ đầu. Như vậy nhóm sẽ không bị phí 45 phút ngồi cãi nhau xem bot có nên đọc ảnh chụp màn hình hay không.
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
