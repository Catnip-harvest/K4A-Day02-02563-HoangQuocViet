# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.
>
> ⚠️ Bản dưới đây là draft dựng từ nhật ký thật của phiên làm việc (artifact đã
> nộp + hội thoại với AI) để Việt có sẵn khung mà điền nhanh — **không phải bản
> để nộp nguyên văn.** Trước khi nộp, đọc lại và sửa bằng đúng cảm nhận thật
> của Việt, đặc biệt mục 3 (đoạn văn mở), vì đó là phần chấm điểm sự trung thực
> cá nhân, không phải phần AI viết hộ được.

## Thông tin cá nhân

- Họ và tên: Hoàng Quốc Việt
- Mã học viên: 02563
- Nhóm: Zone E, Nhóm 4
- Candidate problem nhóm chọn: Người Điếc dùng ngôn ngữ ký hiệu gặp khó khi tiếp cận video tiếng Việt trên YouTube vì phụ đề không luôn phù hợp và video hiếm khi có phiên dịch ngôn ngữ ký hiệu.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự viết 6 problem quan sát thật (kế hoạch 35 tuần, lọc công văn, hotspot xe, quy trình fork/rename lặp mỗi buổi lab, đọc ngược ticket cũ ở BLI) kèm số đo, tách rõ khỏi 6 dòng ứng viên chưa xác nhận | Repo cá nhân có bảng scan 12 dòng, không lẫn "quan sát thật" với "chưa xác nhận" |
| Pitch Problem Card | Viết đủ 3 Problem Card (kế hoạch 35 tuần / lọc công văn / hotspot xe) với workflow trước-sau, bottleneck, metric, non-AI alternative | 3 candidate này trở thành #7-9 trong bảng trình bày Phase 3.1 của nhóm |
| Challenge bài của bạn khác | Trước khi nhóm chốt candidate #10 (Đức Anh đề xuất), tôi tìm nguồn số liệu chính thức thay vì chỉ nghe impact "nghe hợp lý": Điều tra người khuyết tật 2023, Thông tư 17/2020, tuyên bố WFD/WASLI 2018 | Phát hiện 3 ràng buộc thật (chuẩn quốc gia chỉ 408 từ, 3 phương ngữ chỉ giống nhau hơn 50%, cộng đồng Điếc quốc tế cảnh báo avatar) — buộc nhóm thu hẹp phạm vi thay vì nhận "dịch mọi video" |
| Gom trùng / cluster | Đề xuất xếp #7, #8 vào cluster "nghiên cứu và xử lý tri thức", #9 vào cluster "tự động hóa rõ luật" | Phản ánh đúng trong bảng 3.2 của nhóm |
| Chọn candidate problem | Đồng ý chọn #10 dù #1 và #10 cùng 29 điểm, vì impact của #10 rộng hơn phạm vi một tổ chức/gia đình | Ghi trong mục "Vì sao chọn" Phase 3.4 |
| Validation / research | Tự mở và đọc từng nguồn trước khi đưa vào bảng — không lấy số qua tóm tắt trung gian | Toàn bộ dòng Phase 4.2 là nguồn đã kiểm, có link |
| Workflow nhóm | Dựng workflow hiện tại 7 bước (từ lúc video có phụ đề tới lúc hiếm khi có track ký hiệu) và workflow tương lai 5 bước với ranh giới người duyệt ở bước 4 | Phase 5.1-5.2 |
| Problem Statement | Viết v0 và v1; cố tình giữ field Impact ở dạng "chưa đo được" thay vì đoán một con số nghe hợp lý | Phase 5.3, 6.2 |
| Rule / Workflow / Agent | Dùng 3 câu hỏi tự kiểm của ma trận 6.0 để giải thích vì sao chọn Workflow dù độ phức tạp/mơ hồ đều cao (gợi ý Agent) | Phase 6.0-6.1 |
| Decision | Giữ quyết định "Not Yet" thay vì "Go", vì Phase 4.1 tự ghi nhận nhóm chưa phỏng vấn người Điếc thật nào | Phase 6.3 |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Rõ nhất là câu hỏi thứ ba trong ma trận 6.0 — "AI có tự quyết định bước tiếp
theo không?" — đây là lý do thật khiến nhóm giữ Workflow thay vì nhảy lên
Agent, dù hai trục còn lại (độ phức tạp, độ mơ hồ) đều gợi ý ngược lại.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Sau khi tự viết 4 dòng đầu, đưa bối cảnh "SWE intern BLI + học viên K4A" và xin gợi ý thêm theo 4 lăng kính | Gợi ý "quy trình fork/rename lặp mỗi buổi lab" đúng và xảy ra ngay trong buổi này (đặt sai mã học viên, phải làm lại) | Đưa liền 6 dòng một lúc mà không hỏi tôi đã tự nghĩ đủ chưa — dễ khiến tôi lười tự scan trước | Giữ #1-4 là của mình trước; đánh dấu rõ #5 trở lên là "ứng viên" chưa xác nhận, không gộp chung như một khối |
| Problem Card | Xin AI tự hỏi ngược "non-AI alternative đã đủ chưa" cho Card #1 | Câu hỏi ép tôi viết rõ file Excel mẫu giải quyết được phần nào, chưa giải được phần nào | Không sai, nhưng nếu tôi không để ý thì dễ để AI tự trả lời luôn câu hỏi đó thay vì để ngỏ | Biến câu hỏi thành câu challenge cho nhóm, không để AI tự chốt hộ |
| Workflow | Dùng AI dựng bảng current/future state theo đúng field worksheet yêu cầu | Đúng cấu trúc, nhanh | AI tự điền "10 phút" cho hai bước ("mở phân phối CT", "mở kho học liệu") ở Card #1 như số minh họa, dù chưa ai bấm giờ thật — một kiểu bịa số nhỏ dù cả bài đang cố tránh đúng lỗi này | Tự soát lại, đổi cả hai về `[cần đo]` — giữ nguyên tắc không có số nào trong bài mà chưa kiểm được nguồn hoặc chưa đo thật |
| Research | Dùng AI tìm và tóm tắt nguồn (VDS 2023, Thông tư 17/2020, WFD/WASLI, Signapse, SiMAX) | Đọc nhanh nhiều nguồn tiếng Anh và tiếng Việt cùng lúc | Lần đầu dùng số "2,5 triệu người khuyết tật nghe nói (2016)" lấy qua một bài báo trung gian, thay vì mở thẳng báo cáo gốc | Sau khi có link Cục Thống kê (VDS 2023), yêu cầu bỏ số cũ, thay bằng 2,21% (khuyết tật nghe, 16+), 30,8% (học vấn) và 33,6% (internet) lấy trực tiếp từ nguồn gốc |
| Problem Statement | Dùng AI cấu trúc 6 field theo mẫu, giữ nhất quán giữa v0 và v1 | Cấu trúc rõ, không thiếu field | Không có sai rõ trong phase này | Không cần sửa, nhưng tôi tự kiểm lại: field Impact vẫn phải ghi "chưa đo được" chứ không được làm đẹp bằng một con số nghe hợp lý |
| Rule / Workflow / Agent | Dùng AI chạy qua 3 câu hỏi tự kiểm của ma trận 6.0 | Câu hỏi thứ ba là lập luận sắc nhất — tránh chọn nhầm Agent chỉ vì độ phức tạp/mơ hồ cao | Không có | Tự kiểm lại bằng cách hỏi thêm: "nếu mai thêm 1 phương ngữ, quy trình 5 bước có đổi không?" — không đổi, nên vẫn đúng là Workflow |
| Decision | Dùng AI chạy checklist 6.3 (6 câu Yes/Not Yet/No) | Ép nhìn thẳng vào việc chưa phỏng vấn ai, không né tránh bằng cách viết chung chung | Không có — Not Yet khớp ngay với bằng chứng đang có | Đối chiếu lại: chừng nào dòng "Baseline + metric đo được chưa?" còn là Not Yet thì không được chọn Go, dù các dòng khác đã sẵn sàng |

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
Khi nghe candidate #10 của Đức Anh, phản ứng đầu tiên của tôi là thấy đề tài
hay hơn hẳn ba bài của mình — nhưng chính vì thấy nó hay nên tôi phải tự hỏi
liệu nhóm có đang chọn vì "cảm thấy AI ở đây ngầu" chứ không phải vì bằng
chứng. Đó là lý do tôi đi tìm nguồn trước khi đồng ý: Điều tra người khuyết
tật 2023, Thông tư 17/2020 và tuyên bố của WFD/WASLI. Ba nguồn đó đổi hẳn
cách nhóm nhìn bài toán — từ "làm avatar dịch mọi video" xuống "một pipeline
có người duyệt bắt buộc, phạm vi rất hẹp". Nếu không tự đi kiểm, tôi nghĩ
nhóm rất dễ rơi vào đúng cái bẫy solution-first mà worksheet cảnh báo. Phần
khó nhất với tôi không phải là chọn Rule/Workflow/Agent — ba câu hỏi tự kiểm
ở ma trận 6.0 làm việc đó khá rõ ràng. Khó nhất là Impact: viết "chưa đo
được" nghe yếu hơn hẳn một con số cụ thể, và có lúc tôi bị cám dỗ muốn ước
lượng một con số nghe hợp lý cho bài đỡ trống. Tôi không làm vậy, vì chính
Phase 4.1 của nhóm đã tự thừa nhận chưa phỏng vấn ai — viết một con số lúc
đó là tự lừa chính nhóm mình, không phải lừa AI. Dấu tay rõ nhất của tôi
trong bài không phải một đoạn văn, mà là quyết định giữ "Not Yet" ở Phase 6.3
thay vì để nhóm chọn "Go" chỉ vì khung Rule/Workflow/Agent đã dựng xong và
nghe gọn gàng. Nếu làm lại, tôi sẽ challenge sớm hơn: ngay từ Phase 3, thay
vì đợi tới Phase 4 mới đi tìm nguồn, tôi nên hỏi thẳng "ai trong nhóm đã nói
chuyện với một người Điếc chưa" trước khi chấm điểm đồng thuận ở 3.4.
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
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì — **đọc lại mục 3 và sửa bằng lời thật của Việt trước khi bỏ dấu tick này**
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
