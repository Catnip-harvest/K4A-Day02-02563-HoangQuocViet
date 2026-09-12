# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm (VD: facilitator, workflow, research, writer) |
|-----|-----------|-------------|---------------------------------------------------------------|
| 1   | Nguyễn Tuấn Thành | 2A202602640 | Facilitator; tổng hợp Problem Card và workflow nghiên cứu |
| 2   | Nguyễn Đức Anh | 2A202602508 | Research về người dùng, accessibility và giải pháp có sẵn |
| 3   | Lò Văn Long | 2A202602541 | Workflow; mô tả pain trong phát triển sản phẩm HTML5 |
| 4   | Hoàng Quốc Việt | 2A202602563 | Research/validation; tổng hợp candidate trong bối cảnh giáo dục |

**Candidate problem nhóm chọn (1 câu):**

Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.

---

## Phase 3 — Group Convergence: từ 9-12 candidates về 1

### 3.1. Trình bày top 3 mỗi người (mỗi candidate 1-2 phút)

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nguyễn Tuấn Thành | Lọc paper liên quan khi nhận business problem mới | AI researcher, tech lead và business team chờ hướng giải pháp | Skim 10-20 paper để đánh giá relevance khi thuật ngữ học thuật khác ngôn ngữ business; mất 3-5 giờ/topic | Workflow và metric thời gian rõ; cần human review để tránh bỏ sót paper quan trọng |
| 2 | Nguyễn Tuấn Thành | So sánh nhiều paper cùng topic | AI researcher và tech lead | Chuẩn hóa dataset, metric, baseline và limitation giữa 5-8 paper; mất 1-2 giờ | Có cấu trúc rõ, nhưng chất lượng so sánh cần researcher kiểm số liệu gốc |
| 3 | Nguyễn Tuấn Thành | Handoff research recommendation cho engineer | ML engineer và AI researcher | Note thiếu dataset, baseline, metric nên phát sinh 1-2 vòng hỏi lại | Pain ở handoff rõ; template/checklist có thể đã giải phần lớn |
| 4 | Lò Văn Long | Giải quyết bất đồng UI/UX giữa chuyên viên Hóa học và giám đốc dự án trước khi dev code bài thí nghiệm HTML | Dev HTML5, chuyên viên môn Hóa, giám đốc dự án | UI/UX bị bác sau khoảng 20 giờ code, phải làm lại 16-24 giờ và trễ release 5-7 ngày | Pain sản phẩm thật, workflow trước/sau rõ; cần xác định AI có hơn prototype review sớm hay không |
| 5 | Lò Văn Long | Sinh CSS/Canvas animation mô phỏng phản ứng Hóa học từ mô tả hiện tượng | Frontend/HTML5 developer | Viết hiệu ứng hạt Canvas và CSS keyframes thủ công mất 3-4 giờ/bài | Tăng năng suất code, nhưng phạm vi thiên về kỹ thuật cá nhân |
| 6 | Lò Văn Long | Đóng gói asset ảnh và minify HTML5 dưới 5 MB | Frontend developer, người dùng web trường học | Nén ảnh và minify thủ công mất 45-60 phút/bài, dễ sót file nặng | Bài toán rõ nhưng build tool/rule là lời giải phù hợp hơn AI |
| 7 | Hoàng Quốc Việt | Lập kế hoạch giảng dạy lặp cho 35 tuần | Giáo viên bộ môn | Ghép bài và xếp thứ tự cho từng tuần, lặp 35 lần | Đầu vào/đầu ra có cấu trúc; cần xác minh baseline trước khi khẳng định mức tiết kiệm |
| 8 | Hoàng Quốc Việt | Lọc công văn của quận gửi đến trường | Hiệu trưởng | Đọc toàn văn để tự suy ra phần liên quan tới trường | Đúng thế mạnh trích xuất của LLM, nhưng bỏ sót hạn hành chính là rủi ro cao |
| 9 | Hoàng Quốc Việt | Bật hotspot khi lên xe | Bố của Việt | Tìm mục điểm phát sóng trong Cài đặt | Một điều kiện-một hành động; nên dùng shortcut/rule, không cần AI |
| 10 | Nguyễn Đức Anh | Hỗ trợ người Điếc tiếp cận video YouTube/tin tức bằng ngôn ngữ ký hiệu | Người Điếc dùng ngôn ngữ ký hiệu | Video thường chỉ có phụ đề hoặc phụ đề tự động; phụ đề không luôn là kênh tiếp cận phù hợp | Impact xã hội lớn, nhưng phải hỏi trực tiếp người Điếc Việt Nam trước khi chốt workflow |
| 11 | Nguyễn Đức Anh | Phát hiện sự cố sức khỏe của người cao tuổi sống một mình | Người cao tuổi và người thân | Người thân không thể túc trực 24/7; chưa rõ cảm biến nào khả thi | Rủi ro an toàn cao, đòi hỏi thiết bị và quy trình y tế vượt scope lab |
| 12 | Nguyễn Đức Anh | Hỗ trợ ban đầu cho sinh viên/người trẻ chịu áp lực tâm lý | Sinh viên/người trẻ | Ngại tìm tư vấn vì chi phí, kỳ thị hoặc không biết bắt đầu | Gần người dùng nhưng ranh giới an toàn và escalation tới chuyên gia rất nhạy cảm |

### 3.2. Gom trùng / cluster (gom 9-12 ý thành 3-4 cụm)

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Nghiên cứu và xử lý tri thức | #1, #2, #3, #8 | Tìm, đọc, trích xuất, chuẩn hóa và chuyển giao thông tin để ra quyết định | Cần người kiểm nội dung; #3 và #8 có thể cải thiện đáng kể bằng template/checklist trước |
| B — Sản xuất nội dung EdTech | #4, #5, #7 | Chuyển yêu cầu chuyên môn thành kế hoạch, UI/UX hoặc nội dung số | #4 có pain do rework lớn; #5 là tăng năng suất code; #7 có dữ liệu đầu vào khá cấu trúc |
| C — Tự động hóa rõ luật | #6, #9 | Input/điều kiện rõ, đầu ra xác định | Đây là các ví dụ nên chọn Rule/process fix thay vì AI |
| D — Tiếp cận và chăm sóc nhóm dễ bị tổn thương | #10, #11, #12 | Người dùng bị cản trở tiếp cận thông tin, chăm sóc hoặc hỗ trợ | #10 phù hợp để nghiên cứu tiếp; #11 và #12 có rủi ro an toàn cao hơn scope lab |

### 3.3. Shortlist (giữ 2-3 bài trả lời được 7 câu hỏi worksheet)

| Candidate | Vì sao vào shortlist (2-3 ý) | Rủi ro / điều chưa rõ |
|---|---|---|
| #10 — Tiếp cận video YouTube bằng ngôn ngữ ký hiệu | Actor và impact xã hội rõ; đã có research về VSL, thiếu phiên dịch, giới hạn phụ đề và các mô hình human-in-the-loop; so sánh Rule/Workflow/Agent được rõ | Chưa phỏng vấn 5-10 người Điếc Việt Nam; chưa chốt phương ngữ và chưa biết người dùng muốn PiP người thật hay avatar |
| #4 — Chốt UI/UX trước khi dev HTML5 | Handoff giữa ba actor rõ; có thời gian rework, ảnh hưởng tiến độ và workflow dễ vẽ | Cần kiểm chứng nguyên nhân gốc: thiếu prototype/quy trình review hay thiếu công cụ AI; domain khá hẹp theo một dự án |
| #1 — Lọc paper cho business problem | Workflow 6 bước và pain 3-5 giờ/topic rõ; metric thời gian và human boundary cụ thể | Tiêu chí relevance còn chủ quan; cần benchmark/nhãn review để đo không bỏ sót paper quan trọng |

### 3.4. Score để đồng thuận (chấm 1-5, ép nói rõ vì sao cho 5 / cho 3)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #10 — Ngôn ngữ ký hiệu / YouTube | 5 | 4 | 4 | 5 | 3 | 5 | 3 | **29** |
| #4 — Chốt UI/UX trước khi code | 5 | 5 | 3 | 4 | 4 | 4 | 3 | **28** |
| #1 — Lọc paper cho business problem | 5 | 5 | 3 | 4 | 4 | 4 | 4 | **29** |

**Candidate nhóm chọn (1 bài duy nhất):**

```text
Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.
```

**Vì sao chọn (4-5 câu):**

```text
Nhóm chọn candidate này vì actor bị ảnh hưởng và rào cản tiếp cận được nêu rõ, đồng thời impact không chỉ nằm ở năng suất nội bộ mà ở khả năng tiếp cận thông tin. Research Phase 4 cho thấy phụ đề không thể mặc định thay thế ngôn ngữ ký hiệu và nguồn phiên dịch viên rất hạn chế. Các giải pháp đang có như Signapse và SiMAX đều để AI tạo nháp, sau đó có người dùng/người bản ngữ duyệt, nên human boundary có cơ sở. Candidate #10 và #1 cùng 29 điểm; nhóm ưu tiên #10 vì research đã chỉ ra một khoảng trống tiếp cận có ý nghĩa và những ràng buộc cần thu hẹp bài toán. Đây là lựa chọn tạm thời: trước Phase 5, nhóm phải xác nhận pain trực tiếp với người Điếc Việt Nam.
```

**Vì sao KHÔNG chọn các candidate còn lại (mỗi bài 2-3 câu):**

```text
Không chọn #4 vì rework UI/UX đáng kể nhưng nguyên nhân có thể được xử lý trước bằng prototype, acceptance criteria và review sớm, không nhất thiết cần AI. Không chọn #1 vì pain và workflow tốt nhưng tiêu chí "paper liên quan" còn phụ thuộc đánh giá chuyên môn; nhóm chưa có bộ dữ liệu/nhãn để kiểm thử trong lab.

Các candidate #2, #3, #5, #7 và #8 đều có ích nhưng thiên về chuẩn hóa template hoặc hỗ trợ năng suất trong một workflow nội bộ. #6 và #9 phù hợp hơn với Rule/process fix. #11 và #12 có hệ quả sức khỏe và an toàn cao, đòi hỏi thiết bị, chuyên gia và quy trình escalation vượt phạm vi của bài lab hiện tại.
```

**Disagreement (nếu có — ai lo gì, chốt ra sao):**

```text
Nhóm có lo ngại hợp lý rằng chưa ai có bằng chứng trực tiếp từ cộng đồng Điếc, cũng chưa chắc người dùng muốn avatar thay cho người phiên dịch thật. Nhóm không giải quyết bằng cách giả định thay người dùng: vẫn chọn #10 để đi tiếp research, nhưng chốt Phase 4 là phải phỏng vấn/survey 5-10 người Điếc bằng phương thức tiếp cận phù hợp và chỉ thiết kế workflow sau khi có phản hồi.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation (ít nhất 1 cách: interview 2-3 người hoặc survey 5-10 người)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa có | Chưa có quote trực tiếp; research desk không thay thế được phỏng vấn người dùng | Đây là khoảng trống lớn nhất: chưa biết hành vi xem YouTube, loại nội dung và điểm bỏ cuộc của người Điếc Việt Nam | Trước Phase 5, phỏng vấn 5-10 người Điếc bằng video ký hiệu hoặc qua người hỗ trợ giao tiếp |
| Survey / poll | Chưa có | Chưa thực hiện | Chưa biết người dùng ưu tiên phụ đề, PiP người thật hay avatar 3D | Dùng 2 mẫu video để hỏi mức hiểu và lựa chọn phương án |
| Log / ticket / review (nếu có) | 0 | Không có log hành vi người dùng | Không thể suy ra pain cụ thể trên YouTube từ thống kê khuyết tật nói chung | Không dùng số liệu hiện tại để khẳng định nhu cầu sử dụng sản phẩm |

**Insight sau validation (1-2 câu — pain thật nằm ở đâu):**

```text
Research xác nhận rào cản tiếp cận ngôn ngữ ký hiệu là có thật, nhưng chưa xác nhận trực tiếp pain khi xem YouTube của đúng nhóm người dùng mục tiêu. Vì vậy, problem chưa được validate hoàn toàn; đau ở đâu, phương ngữ nào và hình thức thể hiện nào phải do người Điếc trả lời.
```

Bằng chứng đính kèm (nếu có): `02-group-problem-statement-survey.png`, `...-interview-notes.md`

### 4.2. Research giải pháp đã có (ít nhất 2-3 tools/patterns + 1-2 link kiểm được)

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| VDS 2023 và Thông tư 17/2020/TT-BGDĐT | https://www.nso.gov.vn/tin-tuc-thong-ke/2024/11/thong-cao-bao-chi-ve-ket-qua-dieu-tra-nguoi-khuyet-tat-nam-2023/ ; https://luatvietnam.vn/giao-duc/thong-tu-17-2020-tt-bgddt-ngon-ngu-ky-hieu-cho-nguoi-khuyet-tat-185588-d1.html | Xác định bối cảnh tiếp cận và giới hạn chuẩn VSL hiện có | Nguồn Việt Nam chính thức; chuẩn chỉ có 408 từ/ngữ ký hiệu | Tỷ lệ khuyết tật nghe không đồng nghĩa số người Điếc dùng ký hiệu; chưa nói trực tiếp về YouTube | Không suy rộng quy mô người dùng; phải thu hẹp theo nhóm, phương ngữ và loại video |
| Signapse | https://www.signapse.ai/post/ai-sign-language-interpreter-fluency | Sinh bản dịch ký hiệu từ nội dung, sau đó đánh giá mức dễ hiểu | Có nhiều người bản ngữ duyệt đầu ra | Là tiếng Anh/BSL; không thể áp thẳng sang VSL | Đặt người Điếc/người bản ngữ ở bước duyệt, không để AI tự phát hành |
| SiMAX / Signtime và WFD/WASLI | https://theventury.com/case-studies/signtime/ ; https://wfdeaf.org/wfd-wasli-issue-statement-signing-avatars/ | Tạo gợi ý ký hiệu/animation bán tự động | Người Điếc tinh chỉnh trước phát hành | Avatar không nên thay phiên dịch viên người thật; VSL có khác biệt phương ngữ | Pilot chỉ nên làm một tập video ngắn, một phương ngữ, AI tạo nháp và người thật duyệt |

**Research takeaway (2-3 câu — nên build gì / không build gì):**

```text
Không nên build "avatar dịch mọi video YouTube sang VSL" hoặc để AI tự xuất bản. Hướng đáng thử là workflow human-in-the-loop cho một nhóm video ngắn, một phương ngữ được cộng đồng xác nhận: AI hỗ trợ tạo nháp/chú giải, người Điếc hoặc người ký hiệu có năng lực duyệt và chỉnh trước khi công bố. Trước mọi quyết định build, nhóm phải hoàn thành quick validation được liệt kê trong Phase 4.1.
```

> Lưu ý: không dùng số liệu AI đưa nếu không verify được link chính thức. Ghi rõ giả định chưa chắc.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

Dán workflow hoặc link file: `02-group-problem-statement-workflow.png/pdf/md`

```text
[1 Video xong + phụ đề tự động: có sẵn - creator]
→ [2 Cân nhắc thêm ký hiệu: __' - creator, thường bỏ qua vì không biết tìm ai]
→ [3 Tìm phiên dịch NNKH đúng phương ngữ: __' - creator]  <-- bottleneck, gần như luôn thất bại
→ [4 Phiên dịch xem video, chuẩn bị bản dịch: __' - phiên dịch]
→ [5 Phiên dịch quay video ký hiệu riêng: __' - phiên dịch]
→ [6 Editor ghép video ký hiệu vào góc màn hình (PiP): __' - editor]
→ [7 Xuất bản video đã ghép: có sẵn - creator]

Thực tế: đa số video dừng lại ở bước 1-2. Bước 3 hầu như luôn thất bại nên
bước 4-7 rất hiếm khi xảy ra.
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú (handoff? bottleneck?) |
|---|---|---|---|---|---|
| 1 | Creator / YouTube | Video đã dựng | Video + phụ đề tự động | Mỗi video | Bước duy nhất luôn xảy ra |
| 2 | Creator | Video đã có phụ đề | Quyết định có/không làm thêm ký hiệu | Mỗi video | Đa số dừng ở đây vì không biết tìm phiên dịch ở đâu |
| 3 | Creator | Nhu cầu thêm ký hiệu | Phiên dịch phù hợp phương ngữ (nếu tìm được) | [CẦN ĐO] | **Bottleneck** — cả nước chỉ hơn 10 phiên dịch NNKH chuyên nghiệp (2019); handoff creator → phiên dịch |
| 4 | Phiên dịch NNKH | Nội dung video gốc | Bản dịch/kịch bản ký hiệu | [CẦN ĐO] | Phụ thuộc lịch của rất ít người |
| 5 | Phiên dịch NNKH | Bản dịch | Video ký hiệu quay riêng | [CẦN ĐO] | Handoff phiên dịch → editor |
| 6 | Editor | Video gốc + video ký hiệu | Video ghép Picture-in-Picture | [CẦN ĐO] | Thủ công, không có công cụ chuẩn hóa |
| 7 | Creator | Video đã ghép | Video xuất bản có track ký hiệu | Mỗi video hiếm hoi hoàn thành | |

**Bottleneck chính (2-3 câu):**

```text
Bước 3 — tìm phiên dịch NNKH đúng phương ngữ. Cả nước chỉ có hơn 10 phiên
dịch chuyên nghiệp (số liệu 2019), nên bước này gần như luôn thất bại. Hệ quả
là bước 4-7 hiếm khi xảy ra: đa số video không phải "làm ký hiệu tệ" mà là
"không có bước ký hiệu nào cả".
```

### 5.2. Future workflow bản nhóm

```text
[1 Máy tách câu từ phụ đề có sẵn: vài giây - máy/Rule]
→ [2 AI đề xuất chuỗi ký hiệu (gloss) theo phương ngữ đã chốt, đánh dấu từ
     ngoài vốn 408 từ chuẩn: vài phút - AI]
→ [3 AI dựng bản nháp animation/video minh họa: vài phút - AI]
→ [4 Người ký hiệu bản ngữ (ưu tiên người Điếc) duyệt, sửa hoặc bác nháp:
     __' - REVIEW BOUNDARY, bắt buộc, không ngoại lệ]
→ [5 Creator ghép track đã duyệt vào video, xuất bản: có sẵn]

Fallback: nháp bị bác hoặc sai quá nhiều → quay về quy trình PiP người thật
(bước 3-6 cũ) cho đúng video đó, hoặc xuất bản không có track ký hiệu cho
video đó. Không tệ hơn hiện trạng, vì hiện trạng vốn gần như không có gì.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | [CẦN ĐO] — thực tế hiếm khi hoàn thành hết 7 bước | Mục tiêu vài giờ/video | Bấm giờ pilot: từ lúc có phụ đề tới lúc video xuất bản có track ký hiệu |
| Số bước | 7 (nhưng hiếm khi đi hết) | 5 | Đếm bước thực tế hoàn thành trên số video pilot |
| Số bước thủ công | 5/7 (tìm, chuẩn bị, quay, ghép, xuất bản) | 2/5 (duyệt, xuất bản) | So sánh giờ công người bỏ ra mỗi video, trước và sau |
| Bottleneck chính | Thiếu phiên dịch NNKH (nguồn lực khan hiếm) | Người duyệt bận nếu số video tăng nhanh hơn năng lực duyệt | Đếm số video chờ duyệt quá 48 giờ trong pilot |
| Risk mới | Gần như không áp dụng — đa số video không có track ký hiệu | AI dịch sai văn hóa/ngữ pháp mà người duyệt bỏ sót | Đếm số lỗi nghiêm trọng (hiểu sai nội dung) lọt qua bước duyệt trên tổng video pilot |

### 5.3. Problem Statement v0 (mỗi field 2-3 câu)

| Field | Nội dung |
|---|---|
| **Actor** | Người Điếc dùng ngôn ngữ ký hiệu Việt Nam (NNKH) làm ngôn ngữ thứ nhất, xem nội dung video tiếng Việt trên YouTube. Nhóm chưa chốt phương ngữ ưu tiên — đây là một trong các việc phải validate trước khi mở rộng. |
| **Workflow** | Video được sản xuất và xuất bản kèm phụ đề tự động; bước thêm ký hiệu tồn tại trên lý thuyết (7 bước, mục 5.1) nhưng gần như luôn dừng ở bước tìm phiên dịch vì cả nước chỉ có hơn 10 người làm nghề này (2019). |
| **Bottleneck** | Không đủ phiên dịch NNKH để phủ khối lượng video khổng lồ trên YouTube, nên bước ký hiệu bị bỏ qua mặc định — đây không phải vấn đề chất lượng mà là vấn đề nguồn lực con người. |
| **Impact** | Chưa đo trực tiếp. Phase 4.1 tự ghi nhận đây là khoảng trống lớn nhất: nhóm chưa phỏng vấn người Điếc Việt Nam nào, nên chưa có số liệu về tần suất bỏ xem, mức hiểu sai hay mức độ bực bội thật. |
| **Success Metric** | Tỉ lệ trả lời đúng câu hỏi nội dung của nhóm xem có track ký hiệu, so với nhóm chỉ xem phụ đề, trên cùng một video pilot. Baseline sẽ đo trong pilot, chưa có số hiện tại. |
| **Boundary** | Làm: một tập video ngắn có kịch bản sẵn, một phương ngữ được cộng đồng xác nhận, người ký hiệu bản ngữ/người Điếc duyệt bắt buộc mọi video. Không làm: nội dung phát trực tiếp, để AI tự xuất bản không qua duyệt, hoặc mở rộng sang mọi phương ngữ cùng lúc. |

**Câu hỏi AI phản biện v0 (nếu có):**
- Field nào mơ hồ: Impact — vẫn là suy luận từ số liệu khuyết tật nói chung (VDS 2023), chưa phải bằng chứng trực tiếp về hành vi xem YouTube.
- Tôi sửa gì: Giữ nguyên field Impact ở dạng "chưa đo được" thay vì tự ước lượng một con số nghe hợp lý, để tránh biến giả định thành số liệu.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp (suy nghĩ nhanh, không thay quyết định cuối)

- Độ mơ hồ: [ ] Thấp (có đúng/sai rõ) / [x] Cao (nhiều cách trả lời vẫn OK) — Vì sao: một video có thể dịch sang nhiều chuỗi ký hiệu khác nhau mà vẫn đúng, miễn giữ đúng ý và ngữ pháp không gian của NNKH — giống viết narrative hơn là phân loại cố định.
- Độ phức tạp: [ ] Thấp (1-2 bước) / [x] Cao (3+ bước/nguồn, phụ thuộc nhau) — Vì sao: pipeline cần phối hợp ít nhất 4 nguồn (phụ đề gốc, danh mục 408 từ chuẩn, ngữ pháp không gian NNKH, video gốc) qua nhiều bước nối tiếp nhau.

**Bài toán nhóm nằm ở ô nào:**

```text
Độ phức tạp cao × độ mơ hồ cao — ô mà worksheet gợi ý "Agent có thể phù hợp,
nhưng cần boundary, người thật kiểm tra và phương án quay về rất rõ".
```

**Vì sao (2-3 câu):**

```text
Hai trục đẩy bài toán vào ô gợi ý Agent. Nhưng câu hỏi quyết định không phải
hai trục đó — là "AI có cần tự quyết định bước tiếp theo không?", và câu trả
lời là KHÔNG: trình tự 5 bước (tách câu → gloss → dựng nháp → duyệt → xuất
bản) cố định cho mọi video, không đổi tùy nội dung. Độ mơ hồ cao nằm ở NỘI
DUNG đầu ra, không nằm ở QUY TRÌNH, nên nhóm hạ về Workflow thay vì Agent.
```

### 6.1. So sánh Rule / Workflow / Agent (so trên cùng 1 bài)

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | Từ điển tra 1-1: chữ tiếng Việt → ký hiệu trong danh mục 408 từ chuẩn quốc gia (Thông tư 17/2020) | Chỉ đủ cho thuật ngữ cố định: bảng chữ cái, chữ số, tên riêng cần đánh vần | NNKH có ngữ pháp không gian riêng — ghép rule từng-từ ra chuỗi vô nghĩa | Dùng làm lớp nền bên trong bước 2 (AI đề xuất gloss), không đứng một mình |
| **Workflow** | Máy tách câu → AI đề xuất gloss → AI dựng nháp → người ký hiệu bản ngữ duyệt bắt buộc → xuất bản | Nội dung có kịch bản cố định, trình tự các bước luôn giống nhau giữa các video | Bản nháp sai văn hóa/ngữ pháp mà người duyệt bỏ sót nếu số lượng video tăng nhanh | **Có — dùng cho toàn bộ pipeline bước 1-5, mức chọn của nhóm** |
| **Agent** | Máy tự quyết định khi nào cần thêm ngữ cảnh, tự tìm nguồn bổ sung, tự xuất bản không cần duyệt | Chỉ khi khối lượng video lớn tới mức không thể có người duyệt | Đúng rủi ro WFD/WASLI (2018) cảnh báo: avatar thay thế hoàn toàn phiên dịch viên người thật, sai văn hóa không ai bắt được trước khi tới người xem | Không dùng ở bước nào trong phạm vi lab |

**5 câu hỏi chốt (trả lời câu đầy đủ):**
1. Rule có giải được 70-80% case không? → Không. Danh mục 408 từ chuẩn quốc gia không phủ nổi từ vựng tự do của một video bất kỳ; rule chỉ giải được phần thuật ngữ cố định (chữ cái, số, tên riêng).
2. Các bước có đi thẳng một đường không hay phải rẽ nhánh? → Đi thẳng một đường: tách câu → gloss → dựng nháp → duyệt → xuất bản. Nhánh rẽ duy nhất là fallback khi người duyệt bác bỏ nháp, quay về PiP người thật.
3. Có thật sự cần Agent tự lập kế hoạch + gọi tool không? → Không. Trình tự 5 bước cố định cho mọi video; AI không cần tự quyết định bước tiếp theo hay tự gọi thêm công cụ ngoài kế hoạch đã định.
4. Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu? → Người ký hiệu bản ngữ/người Điếc duyệt ở bước 4, trước khi xuất bản — nghĩa là lỗi được bắt trước khi tới người xem thật, không phải sau khi đã phát hành.
5. Có hạ được từ Agent → Workflow → Rule không? → Có. Nếu Workflow không đủ (nháp quá tệ, tỉ lệ sửa quá cao), nhóm hạ về Rule (chỉ đánh vần thuật ngữ cố định) kết hợp PiP người thật cho phần còn lại; không có tình huống nào trong phạm vi lab cần leo lên Agent.

**Mức chọn:**

```text
Workflow
```

**Vì sao chọn (3-4 câu):**

```text
Pipeline cố định, AI không cần tự quyết định bước tiếp theo (xem câu hỏi 3).
Hai sản phẩm thương mại đang chạy thật — Signapse và SiMAX/Signtime — đều
vận hành đúng mức Workflow: máy sinh nháp, người bản ngữ/người Điếc luôn là
bước cuối trước khi phát hành. Đây là bằng chứng mức này đã đủ giải bài toán
tương tự ở quy mô thương mại, không phải suy đoán của nhóm.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Danh mục chuẩn quốc gia chỉ có 408 từ — không đủ phủ nội dung tự do của một
video bất kỳ. Dịch từng-từ-sang-từng-ký-hiệu cũng không tôn trọng ngữ pháp
không gian riêng của NNKH, tạo ra chuỗi ký hiệu người Điếc không hiểu được —
đúng lỗi mà WFD/WASLI cảnh báo với avatar máy móc thuần túy.
```

### 6.2. Problem Statement v1 (v0 sửa chặt hơn + 3 field cuối)

| Field | Nội dung |
|---|---|
| **Actor** | Người Điếc dùng NNKH làm ngôn ngữ thứ nhất, xem video tiếng Việt trên YouTube; phương ngữ cụ thể sẽ chốt sau khi validate (mục 4.1). |
| **Workflow** | Hiện tại: 7 bước, dừng ở bước 3 (tìm phiên dịch) vì thiếu nguồn lực. Tương lai: 5 bước, máy làm 3 bước đầu, người duyệt bắt buộc ở bước 4 (mục 5.1–5.2). |
| **Bottleneck** | Thiếu phiên dịch NNKH (hơn 10 người chuyên nghiệp toàn quốc, 2019) khiến bước ký hiệu bị bỏ qua mặc định ở hầu hết video. |
| **Impact** | Chưa đo được — cần phỏng vấn/survey 5-10 người Điếc thật trước khi khẳng định (mục 4.1, 5.3). |
| **Success Metric** | Tỉ lệ hiểu đúng nội dung, nhóm có track ký hiệu so với nhóm chỉ có phụ đề. Baseline đo trong pilot, chưa có số hiện tại. |
| **Boundary** (làm / không làm) | Làm: 1 tập video ngắn có kịch bản sẵn, 1 phương ngữ đã xác nhận, người duyệt bản ngữ bắt buộc mọi video. Không làm: live, để AI tự xuất bản, mở rộng đa phương ngữ trong pilot đầu. |
| **AI intervention point** (can thiệp sau bước nào, trước bước nào) | Can thiệp sau bước 1 (tách câu từ phụ đề), trước bước 4 (người duyệt) — tức bước 2 (đề xuất gloss) và bước 3 (dựng nháp animation). |
| **Mức chọn** (Rule / Workflow / Agent + 1 câu vì sao) | Workflow — vì trình tự 5 bước cố định cho mọi video và AI không cần tự quyết định bước tiếp theo (xem 6.1, câu hỏi 3). |
| **Rủi ro & người thật kiểm tra** (rủi ro lớn nhất + ai kiểm tra bằng cách nào) | Rủi ro lớn nhất: bản nháp sai văn hóa/ngữ pháp lọt qua người duyệt nếu số lượng video tăng nhanh hơn năng lực duyệt. Người ký hiệu bản ngữ/người Điếc kiểm tra ở bước 4 với ngưỡng lỗi nghiêm trọng = 0; một lỗi khiến người xem hiểu sai nội dung lọt qua là phải dừng pilot, không phải để cải thiện dần. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú (câu đầy đủ) |
|---|---|---|
| Actor + workflow rõ chưa? | Not Yet | Actor rõ, nhưng workflow phía người xem vẫn là suy luận vì mục 4.1 tự ghi nhận nhóm chưa phỏng vấn ai. |
| Baseline + metric đo được chưa? | Not Yet | Mọi metric ở 5.3/6.2 chưa có số hiện tại, sẽ đo trong pilot sau khi validate. |
| Data/input đủ dùng chưa? | Not Yet | Chưa chốt phương ngữ ưu tiên; chưa đối chiếu phụ đề video mẫu với danh mục 408 từ để biết tỉ lệ phủ thực tế. |
| AI sai, hậu quả chấp nhận được không? | Yes | Có bước duyệt bắt buộc (6.2) và ngưỡng lỗi nghiêm trọng = 0; hậu quả tệ nhất là nháp bị bác, không phải xuất bản sai tới người xem. |
| Có người review/owner không? | Yes | Người ký hiệu bản ngữ/người Điếc duyệt là bắt buộc trong thiết kế, không phải bước tùy chọn. |
| Có cách non-AI đơn giản hơn không? | Yes | PiP người thật — đúng về chất lượng nhưng không scale được, vì cả nước chỉ hơn 10 phiên dịch chuyên nghiệp. |

**Decision:**

```text
Not Yet
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Khung so sánh Rule/Workflow/Agent và ranh giới người/máy đã có bằng chứng rõ
(VDS 2023, Thông tư 17/2020, Signapse, SiMAX, WFD/WASLI 2018). Nhưng mục 4.1
tự ghi nhận nhóm chưa phỏng vấn được người Điếc thật nào, nên chưa có bằng
chứng trực tiếp về hành vi xem YouTube, phương ngữ ưu tiên hay việc người
dùng có chấp nhận bản dịch AI hay không. Quyết định Go ở thời điểm này là go
vì khung lý thuyết đẹp, không phải vì bằng chứng người dùng thật.
```

**Nếu Go — pilot nhỏ nhất (data nào, chạy tay ra sao, đo 3 số nào):**

```text
Data: 3-5 video ngắn (dưới 3 phút/video), 1 phương ngữ đã được cộng đồng xác
nhận, nội dung có kịch bản sẵn (ví dụ video giáo dục).
Chạy tay: AI tạo nháp cho từng video; người ký hiệu bản ngữ/người Điếc duyệt
thủ công từng bản trước khi ghép và xuất bản.
Đo 3 số: (1) tỉ lệ câu người duyệt phải sửa trên tổng số câu AI đề xuất,
(2) tỉ lệ người Điếc trả lời đúng câu hỏi nội dung so với nhóm chỉ xem phụ
đề, (3) thời gian từ lúc có phụ đề tới lúc video xuất bản có track ký hiệu.
```

**Nếu Not Yet — cần validate gì trước:**

```text
1. Phỏng vấn/survey 5-10 người Điếc thật (mục 4.1), hỏi bằng video ký hiệu —
   không hỏi bằng bảng hỏi chữ, vì đó là lặp lại chính vấn đề nhóm muốn sửa.
2. Cho cùng nhóm xem 2 mẫu (PiP người thật vs bản animation AI), hỏi thích
   phương án nào và vì sao.
3. Lấy phụ đề của video mẫu, đối chiếu với danh mục 408 từ chuẩn quốc gia để
   biết tỉ lệ phủ từ vựng thực tế.
4. Chốt 1 phương ngữ theo nơi nhóm tiếp cận được người duyệt bản ngữ thật.
5. Đọc các nghiên cứu VSL/SiGML tiếng Việt đã có trước khi tự dựng lại pipeline
   từ đầu.
```

**Nếu No-Go — làm gì thay AI:**

```text
Vận động một số creator giáo dục/y tế công cộng lớn thêm PiP người thật cho
các video quan trọng nhất, hoặc kết nối trực tiếp với một trong hơn 10 phiên
dịch hiện có để làm thủ công cho nội dung ưu tiên cao trước khi nghĩ tới quy
mô lớn hơn.
```

**Exit / rollback (khi nào dừng AI, quay về cách cũ):**

```text
Dừng ngay khi một lỗi nghiêm trọng (bản nháp khiến người xem hiểu sai nội
dung, không chỉ là vụng về) lọt qua bước duyệt và tới người xem thật. Khi đó
quay về PiP người thật hoặc chỉ-phụ-đề cho toàn bộ tập video đang pilot,
không mở rộng thêm cho tới khi tìm ra và sửa được nguyên nhân gốc.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 9-12 → 1 (cluster + shortlist + score)
- [x] Có validation (quote thật) + research (link kiểm được)
- [x] Có workflow trước/sau đủ thời gian, handoff, bottleneck, boundary, fallback
- [x] Có PS v0 → v1, metric có trước/sau + cách đo, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent + Decision Go/Not Yet/No-Go có lý do
