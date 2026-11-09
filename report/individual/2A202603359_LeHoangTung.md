# Báo cáo cá nhân — Le Hoang Tung (2A202603359)

> **Bài mẫu.** Các mốc thời gian, trải nghiệm và lời kể do AI xây dựng để minh họa cách làm bài; Le Hoang Tung chưa xác nhận chúng là dữ liệu thực tế.

## 1. Thông tin học viên

- Họ tên: Le Hoang Tung
- MSSV: 2A202603359
- Lớp: L3A
- Tên nhóm: OnlyM
- Link repo nhóm: https://github.com/tunglh04/K5-L3A-DAY02-OnlyM-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu trong bài mẫu |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi nhận một lab có nhiều tài liệu hướng dẫn, tôi muốn gom đủ yêu cầu và nơi ghi bài, để bắt đầu đúng thứ tự mà không bỏ sót. | Học viên | Lần làm lab gần nhất: 42 phút lập kế hoạch; nhận ra muộn 2 trường bắt buộc. |
| 2 | Lặp lại | Khi rà bài trước mỗi hạn nộp, tôi muốn thấy tiêu chí nào đã có bằng chứng, để không đọc lại rubric từ đầu. | Học viên, người chấm | Hai lần rà gần nhất: 24 và 28 phút; một lần vẫn thiếu phần boundary. |
| 3 | Tốn thời gian | Khi có nhiều mốc bài tập trong tuần, tôi muốn biết việc nào phải làm trước, để tránh bắt đầu quá sát hạn. | Học viên | Tuần trước mất 12 phút sắp lịch; 2 việc bắt đầu trong 24 giờ cuối. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi viết bảng research, tôi muốn kiểm được claim nào được nguồn nào hỗ trợ, để không trích nhầm hoặc dùng link chết. | Người phụ trách research | Lần gần nhất: 31 phút cho 3 nguồn; phải thay 1 link không mở được. |
| 5 | Pain từ người khác | Khi một bạn học hỏi lại quyết định cũ về phạm vi bài, tôi muốn tìm được ghi chú gốc, để không tranh luận lại từ đầu. | Bạn học và người ghi chú | Ba lần hỏi trong một tuần; mỗi lần tìm lại mất khoảng 18 phút. |

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Gom yêu cầu lab từ nhiều file (#1) | Có actor, lần xảy ra, 42 phút và hai chỗ bỏ sót | Bạn học khác có gặp tương tự không? |
| 2 | Rà rubric trước hạn (#2) | Lặp lại, có thời gian và lỗi cụ thể | Có phải chỉ là bước cuối của #1? |
| 3 | Kiểm claim và nguồn research (#4) | Bước nghẽn rõ, đo được thời gian | Lỗi link có đủ thường xuyên để đáng giải? |

### Problem Card #1 — Gom yêu cầu lab

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận một lab có nhiều tài liệu, tôi muốn gom đủ yêu cầu và nơi ghi bài, để bắt đầu đúng thứ tự mà không bỏ sót. |
| Actor | Học viên tự tổ chức bài Day 02 |
| Thời điểm / bối cảnh | Lúc mới nhận repo, trước khi viết báo cáo |
| Quy trình hiện tại | 1. Mở repo; 2. Đọc hướng dẫn chính; 3. Đối chiếu rubric và submission; 4. Ghi thứ tự làm; 5. Rà lại danh sách |
| Bottleneck | Bước 3, đối chiếu yêu cầu giữa các file: 17 phút/lần |
| Impact | Tổng 42 phút lập kế hoạch; nhận ra muộn 2 trường phải điền |
| Success metric | Từ 42 xuống tối đa 22 phút/lượt; không còn yêu cầu bị bỏ sót ở lần rà đầu |
| Phương án không dùng AI | Checklist CP × tiêu chí × file đích, mỗi mục có link nguồn |
| Giả thuyết về AI | AI trích yêu cầu, nhưng học viên phải kiểm từng dòng với tài liệu gốc |
| Cảm nhận nhanh | No AI |

```text
[Mở repo: 3'] → [Đọc hướng dẫn: 12'] → [Đối chiếu yêu cầu: 17'] ← BOTTLENECK
→ [Ghi thứ tự làm: 6'] → [Rà lại: 4'] = 42 phút
```

### Problem Card #2 — Rà rubric

| Trường | Nội dung |
|---|---|
| Job Story | Khi chuẩn bị nộp, tôi muốn nối từng tiêu chí với bằng chứng trong báo cáo, để sửa đúng chỗ còn thiếu. |
| Actor | Học viên chịu trách nhiệm nộp repo |
| Thời điểm / bối cảnh | Sau khi viết xong, trước hạn nộp |
| Quy trình hiện tại | 1. Mở rubric; 2. Đọc 11 tiêu chí; 3. Tìm bằng chứng trong báo cáo; 4. Ghi lỗi; 5. Sửa |
| Bottleneck | Bước 3, dò vị trí bằng chứng: 13 phút/lượt |
| Impact | Trung bình hai lượt là 26 phút; một lượt vẫn bỏ sót boundary |
| Success metric | 26 → tối đa 12 phút/lượt, 11/11 tiêu chí có vị trí bằng chứng |
| Phương án không dùng AI | Ma trận tiêu chí × đường dẫn trong Markdown |
| Giả thuyết về AI | AI kiểm cấu trúc, nhưng không thể xác nhận phỏng vấn thật |
| Cảm nhận nhanh | No AI hoặc Rule |

```text
[Mở rubric: 3'] → [Đọc tiêu chí: 6'] → [Dò bằng chứng: 13'] ← BOTTLENECK
→ [Ghi lỗi: 2'] → [Sửa: 2'] = 26 phút
```

### Problem Card #3 — Kiểm research

| Trường | Nội dung |
|---|---|
| Job Story | Khi viết research, tôi muốn biết từng claim có đúng với nguồn gốc, để bảng so sánh đáng tin. |
| Actor | Học viên phụ trách research |
| Thời điểm / bối cảnh | CP4, sau khi đã chọn candidate |
| Quy trình hiện tại | 1. Tìm 3 nguồn; 2. Mở từng link; 3. So claim với nguồn; 4. Ghi bảng |
| Bottleneck | Bước 2, đọc và kiểm nguồn: 12 phút/lượt |
| Impact | 31 phút; phải thay một link không mở được |
| Success metric | 31 → tối đa 18 phút/lượt; 0 link chết; 100% claim quan trọng có nguồn |
| Phương án không dùng AI | Danh sách nguồn chính thức và mẫu ghi claim → đoạn hỗ trợ |
| Giả thuyết về AI | AI gợi nguồn và so sánh, người làm tự mở và kiểm link |
| Cảm nhận nhanh | Workflow nếu số nguồn tăng nhiều; hiện tại No AI |

```text
[Tìm nguồn: 8'] → [Mở và đọc: 12'] ← BOTTLENECK
→ [So claim: 7'] → [Ghi bảng: 4'] = 31 phút
```

**Card muốn pitch:** #1. Nó xảy ra đầu quy trình, ảnh hưởng cả việc viết và rà bài. **Câu hỏi muốn được phản biện:** “Hai mục bỏ sót đến từ tài liệu rải rác hay từ thói quen không ghi checklist?”

### AI phản biện card

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| 42 phút có thể gồm cả đọc hiểu, không chỉ đối chiếu. | Có | Tách thành 5 bước; chỉ gán 17 phút cho bước đối chiếu. |
| Hai trường bỏ sót chưa chứng minh người khác cũng gặp. | Có | Đưa giả định này vào CP4 và hỏi người ngoài nhóm. |
| Target 22 phút có thể khiến bỏ sót nhiều hơn. | Có | Đo đồng thời thời gian và số yêu cầu thiếu. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Hoạt động trong bài mẫu | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày 3 card và chọn #1 để đào sâu | Chuyển trọng tâm sang bước đối chiếu yêu cầu |
| Phản biện bài khác | Nhóm một người; tự đặt câu hỏi “#1 và #2 có trùng pain không?” | Gộp #2 thành bước kiểm cuối của #1 |
| Nhận phản biện | Người được hỏi B nói họ không bỏ sót vì có checklist sẵn | Thu hẹp problem vào người chưa có hệ thống đối chiếu |
| Gom cluster / cây OST | Gom các vấn đề theo hiểu yêu cầu, kiểm bằng chứng, truy nguồn | Giữ opportunity tách khỏi solution |
| Chọn candidate | Chọn #1 dù #2 dễ đo hơn | Chọn pain xảy ra sớm trong quy trình |
| Kiểm chứng / research | Tổng hợp 3 snapshot và kiểm 3 trang nguồn chính thức | Có cả tín hiệu xác nhận và phản bác |
| Quy trình nhóm | Tách 42 phút thành 5 bước; thiết kế quy trình checklist 21 phút | Bottleneck và fallback rõ |
| Problem Statement | Ghi baseline, target và cách đo | Có v0 và v1 |
| Mức can thiệp AI | So No AI, Rule, Workflow, Agent | Chọn No AI cho pilot |
| Quyết định | Chấm 4 rủi ro và ngưỡng dừng | Go cho pilot checklist nhỏ |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi thêm góc nhìn sau khi có 3 ý | Mở ra vấn đề kiểm nguồn và tìm lại ghi chú | Gợi “AI làm toàn bộ lab” như một solution | Bỏ ý đó, giữ Job Story về pain |
| CP2 Problem Card | Đóng vai PM hoài nghi | Chỉ ra 42 phút cần tách bước | Tưởng mọi thời gian là bottleneck | Ghi rõ 17 phút ở bước đối chiếu |
| CP4 Research | Tìm trang chính thức của công cụ | Rút nhanh 3 phương án so sánh | Có thể suy tính năng là bằng chứng nhu cầu | Tự mở link và chỉ ghi claim nguồn hỗ trợ |
| CP5 Quy trình | Chuyển mô tả sang sơ đồ chữ | Dễ nhìn handoff và số phút | Có thể bỏ bước rà của người học | Giữ bước kiểm nguồn và fallback |
| CP5–6 Problem Statement | Phản biện metric và boundary | Nhắc đo số bỏ sót cùng thời gian | Gợi target quá tham vọng khi chưa cân nhắc chất lượng | Chọn 22 phút kèm 0 mục bỏ sót |
| CP6 Quyết định | So bốn mức can thiệp | Giúp thấy checklist đủ cho pilot | Ban đầu ưu tiên Workflow vì có nhiều file | Chọn No AI dựa trên quy trình và tín hiệu từ B |

---

## 6. Reflection (CP7)

**6.1.** Vì làm một mình nên mình không có buổi nghe nhóm pitch. Khi xem lại ba card, mình suýt chọn bài kiểm nguồn vì lần gần nhất mất tới 31 phút. Nhưng nó chỉ xuất hiện ở một checkpoint, còn việc gom yêu cầu diễn ra ngay từ đầu và ảnh hưởng đến cả lúc rà bài. Mình cũng nhận ra "đọc đề" và "rà rubric" thực ra là hai đoạn của cùng một việc.

**6.2.** Lúc đầu mình nghĩ cứ đưa cả repo cho AI đọc rồi nhờ liệt kê việc là nhanh nhất. Đến khi vẽ từng bước mới thấy chỗ tốn thời gian là đối chiếu yêu cầu với đúng file nộp, và việc này làm bằng bảng kiểm có link là đủ. Mình vẫn dùng AI, nhưng để hỏi ngược lại xem mình đang đo sai chỗ nào.

**6.3.** Câu trả lời của B làm mình đổi ý nhiều nhất. Bạn ấy luôn mở rubric trước rồi tự lập checklist, nên chỉ mất 18 phút và không sót mục nào. Trước đó mình viết actor là "mọi học viên", sau đó sửa thành những người chưa có cách đối chiếu yêu cầu ổn định. Bài toán hẹp hơn nhưng khớp với dữ liệu trong case hơn.

**6.4.** Mình đã đoán A và C sẽ sót yêu cầu, nên không bất ngờ. Điều bất ngờ là B đọc cùng loại tài liệu mà vẫn làm gọn như vậy. Nhờ đó mình nhìn vào cách người học tự xoay xở, thay vì mặc định file nhiều thì cần công cụ mới.

**6.5.** Success metric là phần mình mất nhiều thời gian nhất. Nếu chỉ đặt mục tiêu giảm từ 42 xuống 22 phút thì rất dễ "đạt" bằng cách đọc lướt và bỏ qua yêu cầu khó, nên mình thêm điều kiện không còn mục nào bị phát hiện muộn. Mình cũng ghi rõ người học vẫn phải mở nguồn để kiểm, vì dấu tick trên checklist không chứng minh bài đã đủ.

**6.6.** Nếu làm lại, mình sẽ bấm giờ ngay lúc mở repo thay vì nhớ lại sau, ghi tên chính xác hai mục bị phát hiện muộn, và phỏng vấn thêm một người không gặp khó khăn để xem họ làm khác gì. Mình cũng sẽ tự hỏi sớm hơn: "Nếu không có AI thì mình giải quyết phần nào trước?" Có thể câu này đã đưa mình tới checklist nhanh hơn.

**6.7. Hiểu bài:** Vấn đề là học viên chưa có cách đối chiếu yêu cầu giữa nhiều file, nên mất thời gian và dễ sót mục. Quy trình hiện tại gồm mở repo, đọc hướng dẫn, đối chiếu, ghi việc, rà lại; riêng bước đối chiếu chiếm 17 trong 42 phút. Metric gồm thời gian lập kế hoạch (tối đa 22 phút) và số yêu cầu thiếu (0). Boundary: checklist không tự xác nhận bằng chứng hay nộp bài, học viên phải kiểm nguồn và tự quyết định. Mình chọn No AI vì yêu cầu có thể chuyển thành bảng kiểm có link, và chọn Go cho một pilot nhỏ. Nếu sau hai lượt mà thời gian vẫn trên 30 phút hoặc vẫn sót yêu cầu thì dừng.

---

## 7. Tài liệu tham khảo


