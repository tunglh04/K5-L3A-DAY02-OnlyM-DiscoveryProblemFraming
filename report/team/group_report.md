# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> **Bài mẫu.** Các mốc thời gian, phỏng vấn, câu nói và quyết định do AI xây dựng để minh họa cách làm bài; nhóm OnlyM chưa xác nhận chúng là dữ liệu thực tế. Thông tin về công cụ đã được đối chiếu với nguồn chính thức.

## 1. Thông tin nhóm

- Tên nhóm: OnlyM
- Thành viên: Le Hoang Tung (2A202603359); xem [TEAM.md](../../TEAM.md).
- Candidate chọn: Học viên chưa có cách đối chiếu yêu cầu từ nhiều file hướng dẫn nên tốn thời gian lập kế hoạch và có thể bỏ sót mục.
- Quyết định cuối trong tình huống: **Go** cho pilot checklist có link nguồn, **No AI**.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch và tự phản biện

Nhóm một người trình bày ba card; các câu hỏi dưới đây là câu hỏi tự phản biện của bài mẫu.

| # | Candidate | Actor | Bottleneck | Câu hỏi phản biện và điều chỉnh |
|---:|---|---|---|---|
| 1 | Gom yêu cầu lab | Học viên Day 02 | Đối chiếu nhiều file, 17 phút | “42 phút có phải đều do đối chiếu?” → tách 5 bước, chỉ 17 phút ở bước này. |
| 2 | Rà rubric | Học viên trước khi nộp | Dò bằng chứng, 13 phút | “Có trùng #1?” → xem là bước rà cuối trong cùng quy trình. |
| 3 | Kiểm claim research | Người làm CP4 | Mở và đọc nguồn, 12 phút | “Link lỗi có lặp lại?” → cần thêm dữ liệu trước khi ưu tiên. |

### 2.2. Cluster

| Cluster | Candidate | Pattern chung |
|---|---|---|
| A — Đối chiếu yêu cầu | Scan #1, #2 | Nối yêu cầu với nơi ghi và bằng chứng |
| B — Truy nguồn | Scan #4, #5 | Tìm và kiểm thông tin gốc |
| C — Lập kế hoạch | Scan #3 | Chọn thứ tự và thời điểm làm |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Học viên lập kế hoạch lab trong ≤22 phút và không bỏ sót yêu cầu ở lần rà đầu
├── Opportunity A: Yêu cầu nằm ở nhiều file, khó nối với đúng nơi ghi
├── Opportunity B: Tiêu chí chấm khó nối với bằng chứng đã viết
└── Opportunity C: Người học khó nhận ra sớm phần chưa đủ nguồn
```

Loại khỏi tầng opportunity ý “chatbot đọc repo” và “dashboard tiến độ”: cả hai là solution.

### 2.4. Chấm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh 4 mức | Hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Gom yêu cầu lab | 5 | 5 | 4 | 5 | 5 | 5 | 5 | **34** |
| Rà rubric | 5 | 5 | 3 | 4 | 5 | 4 | 5 | 31 |
| Kiểm claim research | 5 | 4 | 3 | 4 | 5 | 4 | 4 | 29 |

**Chọn gom yêu cầu lab:** xảy ra trước khi viết bài; lỗi ở đây có thể kéo sang các bước sau. **Loại rà rubric** khỏi shortlist độc lập vì nó là phần cuối của cùng quy trình. **Loại kiểm claim research** vì chỉ xảy ra ở một checkpoint và hiện có ít bằng chứng về tần suất lỗi. **Xử lý bất đồng:** nhóm một người nên không có bất đồng giữa thành viên; câu hỏi tự phản biện được ghi trong bảng pitch.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

Thang bằng chứng 1 = chưa có, 5 = nhiều nguồn độc lập. Bảng điểm minh họa cách chấm sau ba cuộc phỏng vấn trong bài mẫu.

| # | Giả định | Loại | Quan trọng | Bằng chứng | Kiểm trước? |
|---:|---|---|---:|---:|---|
| 1 | Người chưa có checklist mất trên 30 phút để lập kế hoạch lab | Value | 5 | 4 | Đã kiểm |
| 2 | Yêu cầu rải file dẫn tới bỏ sót mục | Value | 5 | 3 | Đã kiểm |
| 3 | Checklist có link nguồn giảm thời gian mà không tăng bỏ sót | Usability | 5 | 2 | Pilot |
| 4 | Yêu cầu đủ rõ để chuyển thành ô kiểm | Feasibility | 4 | 4 | Đã kiểm tài liệu |
| 5 | Học viên chịu dùng và cập nhật checklist khi đề đổi | Viability | 3 | 2 | Pilot |
| 6 | Không cần gửi tài liệu nội bộ cho dịch vụ ngoài | Viability | 4 | 4 | Đã kiểm với phương án No AI |

### 3.2. Kiểm chứng

Ba snapshot trong bài mẫu dùng câu hỏi về **lần làm lab gần nhất** và các bước đã làm, không dùng câu hỏi “bạn có muốn dùng công cụ này không?”. Xem [A](../assets/cp4-interview-snapshot-1.md), [B](../assets/cp4-interview-snapshot-2.md), [C](../assets/cp4-interview-snapshot-3.md).

| Người được hỏi | Lần gần nhất | Thời gian lập kế hoạch | Workaround | Yêu cầu phát hiện muộn | Tín hiệu |
|---|---|---:|---|---:|---|
| A — học viên làm lab có nhiều file | Tuần trước | 36 phút | Ghi việc vào giấy sau khi đọc từng file | 1 | Xác nhận |
| B — học viên hay lập checklist | Tuần trước | 18 phút | Dùng checklist có link tới đề | 0 | **Phản bác**: nhiều file không nhất thiết gây pain |
| C — học viên làm lab trên GitHub | Hai tuần trước | 51 phút | Đọc lại hướng dẫn khi chuẩn bị nộp | 2 | Xác nhận |

**Tổng hợp:** 2/3 người phát hiện muộn ít nhất một yêu cầu; trung vị thời gian là 36 phút. Người không gặp lỗi đã dùng checklist. Số mẫu nhỏ, chỉ cho hướng thử nghiệm; chưa đại diện cho toàn lớp.

**Sửa problem sau kiểm chứng:** thu hẹp actor từ “mọi học viên” thành “học viên chưa có cách đối chiếu yêu cầu nhất quán”. Tín hiệu từ B cho thấy cách làm đơn giản có thể đã đủ; nhóm đổi hướng từ ý tưởng AI đọc tài liệu sang pilot checklist có link nguồn.

### 3.3. Research giải pháp đã có

Các link dưới đây đã được mở và kiểm trên trang chính thức ngày 09/11/2026.

| Công cụ / pattern | Link | Giải bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học |
|---|---|---|---|---|---|
| Checklist Markdown trong GitHub | [GitHub Docs: tasklists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists) | Theo dõi yêu cầu và trạng thái | Checkbox hoạt động ngay trong Markdown | Người lập có thể bỏ sót yêu cầu, checklist có thể cũ | Thử trước trong repo hiện có |
| GitHub Issues/sub-issues | [GitHub Docs: About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/learning-about-issues/about-issues) | Chia việc và theo dõi phụ thuộc | Có phân cấp và trạng thái riêng | Hơi nặng cho một lab ngắn, nhóm một người | Chỉ dùng nếu checklist quá dài |
| Gemini Notebook | [Google Help: Add sources](https://support.google.com/gemininotebook/answer/16215270) | Hỏi đáp trên nhiều tài liệu | Nhận Markdown/PDF và cho chọn nguồn | Câu trả lời sinh ra cần kiểm với đề gốc; phải nhập nguồn | Chưa cần cho bài có yêu cầu xác định |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
[Mở repo: 3'] → [Đọc hướng dẫn: 12'] → [Đối chiếu yêu cầu: 17'] ← BOTTLENECK
→ [Ghi thứ tự làm: 6'] → [Rà lại: 4'] = 42 phút/lượt
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Học viên | Link repo | Bộ file đã mở | 3 phút/lab | Nhận tài liệu |
| 2 | Học viên | README, RULES, CHECKPOINTS, worksheet | Hiểu các CP | 12 phút/lab | Đọc tuần tự |
| 3 | Học viên | RUBRIC, SUBMISSION, ghi chú bước 2 | Danh sách điều kiện cần nộp | **17 phút/lab** | Bottleneck: yêu cầu nằm nhiều chỗ |
| 4 | Học viên | Danh sách yêu cầu | Thứ tự làm và file đích | 6 phút/lab | Ghi bằng tay |
| 5 | Học viên | Kế hoạch, tài liệu gốc | Bản rà đầu | 4 phút/lab | Hai mục vẫn nhận ra muộn |

### 4.2. Quy trình tương lai — pilot No AI

```text
[Mở repo: 3'] → [Mở checklist có link nguồn: 4'] ← NO AI
→ [Ghi thứ tự làm: 6'] → [Học viên đối chiếu từng mục với nguồn gốc: 8']
= 21 phút/lượt
```

- **Checklist thử:** [cp6-submission-checklist.md](../assets/cp6-submission-checklist.md).
- **Con người kiểm:** học viên mở từng link nguồn, quyết định mục nào đạt, và sửa khi đề thay đổi.
- **Boundary:** checklist không tự xác nhận phỏng vấn, số liệu hoặc reflection là thật; không tự nộp LMS.
- **Phương án quay về:** nếu checklist thiếu/cũ, dùng RUBRIC và SUBMISSION gốc, sửa checklist trước khi dùng tiếp.

### 4.3. Before / after

| Chỉ số | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Số bước | 5 | 4 | Đếm bước trong hai luồng |
| Tổng thời gian | 42 phút | ≤22 phút; luồng dự kiến 21 phút | Bấm giờ hai lượt pilot |
| Bước thủ công | 5 | 4 | Checklist không tự tick |
| Bước nghẽn | Đối chiếu 17 phút | Tra checklist 4 phút + kiểm nguồn 8 phút | Ghi thời gian riêng từng bước |
| Yêu cầu phát hiện muộn | 2 | 0 | Rà toàn bộ rubric sau khi lập kế hoạch |
| Rủi ro mới | Không có checklist để lệ thuộc | Checklist cũ hoặc thiếu mục | Đối chiếu phiên bản đề và link nguồn |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên làm lab trong repo và chưa có cách đối chiếu yêu cầu nhất quán |
| **Quy trình** | Mở repo → đọc nhiều tài liệu → đối chiếu yêu cầu → ghi kế hoạch → rà lại |
| **Bottleneck** | Bước đối chiếu yêu cầu từ nhiều file: 17/42 phút trong kịch bản |
| **Impact** | Mất 42 phút và phát hiện muộn 2 trường bắt buộc; 2/3 người trong mẫu phỏng vấn cũng phát hiện muộn ít nhất một mục |
| **Success Metric** | Baseline: 42 phút và 2 mục muộn ở lượt cá nhân; target: ≤22 phút và 0 mục muộn trong 2 lượt pilot; bấm giờ từng bước và đối chiếu rubric sau mỗi lượt |
| **Boundary** | Không thay thế việc tự xác nhận bằng chứng, kết quả phỏng vấn và quyết định nộp; học viên kiểm mọi mục với nguồn gốc |

**Phản biện từ AI:** Target thời gian có thể làm tăng bỏ sót. Nhóm giữ đồng thời hai metric: thời gian và số mục phát hiện muộn; pilot chỉ đạt nếu cả hai đạt.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Ô **mơ hồ thấp × phức tạp thấp đến trung bình**. Yêu cầu có đúng/sai rõ và nằm trong số tài liệu xác định; việc ghép nguồn có vài bước nhưng không cần AI tự quyết quy trình.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Checklist có link nguồn, học viên tự tick | Yêu cầu ổn định và người học tự kiểm được | Checklist thiếu/cũ | **Có** |
| **Rule** | Script kiểm tên file, header, link | Lỗi chủ yếu là cấu trúc lặp lại | Nội dung rỗng vẫn có thể qua kiểm | Chưa cần cho pilot |
| **Workflow** | AI trích yêu cầu, người học duyệt | Nguồn dài và thay đổi thường xuyên | Trích sai, tốn công eval | Không |
| **Agent** | AI tự đọc, sửa và quyết định bước tiếp | Có nhiều ngoại lệ không dự đoán được | Sửa nhầm, vượt boundary | Không |

**Vì sao chọn mức đơn giản nhất:** B cho thấy checklist đã đủ để không bỏ sót và chỉ mất 18 phút. Không có bằng chứng Rule, Workflow hay Agent tạo thêm giá trị ở quy mô một lab. AI Canvas và câu hỏi PAIR về lỗi dự đoán không áp dụng vì phương án được chọn không dùng AI.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Học viên làm lab trong repo và chưa có cách đối chiếu yêu cầu nhất quán |
| **Quy trình** | Đọc tài liệu → dùng checklist có link nguồn → ghi kế hoạch → người học rà từng yêu cầu |
| **Bottleneck** | Đối chiếu yêu cầu: 17 phút trong baseline của bài mẫu |
| **Impact** | 42 phút và 2 mục phát hiện muộn ở lượt cá nhân |
| **Success Metric** | 42 → ≤22 phút; 2 → 0 mục muộn; bấm giờ và rà lại với RUBRIC/SUBMISSION sau mỗi lượt trong 2 lượt pilot |
| **Boundary** | Checklist không tự xác nhận dữ liệu hay tick thay người; học viên kiểm nguồn và tự nộp |
| **AI intervention point** | Không có; yêu cầu đủ xác định để kiểm bằng checklist |
| **Mức chọn** | No AI |
| **Rủi ro & người kiểm tra** | Checklist thiếu/cũ; Le Hoang Tung rà với đề gốc sau mỗi lần dùng |

**Thay đổi so với v0:** v0 mô tả pain chưa gắn một cách xử lý. v1 thêm cách thử checklist và nêu rõ mức can thiệp.

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | Đọc, đối chiếu thủ công | Tra checklist có link rồi kiểm nguồn | B cho thấy workaround này hữu ích |
| Boundary | Người học xác nhận bằng chứng | Thêm cấm tick thay người | Tránh “đủ ô” nhưng thiếu nội dung |
| Mức can thiệp | Chưa chọn | No AI | Yêu cầu xác định; chưa cần tạo nội dung |

**Tiêu chí đánh giá checklist:**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đủ yêu cầu | 11/11 tiêu chí rubric và mọi mục bắt buộc trong submission được đối chiếu | Thiếu một mục |
| 2 | Truy vết | Mỗi mục có link đúng tới tài liệu gốc và bằng chứng | Link chết hoặc sai đích |
| 3 | Thời gian | Lập kế hoạch và rà trong ≤22 phút | Trên 22 phút |
| 4 | Chất lượng | 0 yêu cầu phát hiện muộn sau lượt rà độc lập | Có ít nhất 1 yêu cầu phát hiện muộn |
| 5 | Kiểm soát | Học viên tự tick, mở nguồn và sửa checklist khi đề đổi | Checklist tự được coi là bằng chứng đạt |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Mức | Lý do / bằng chứng |
|---|---|---|
| **Value** | Trung bình | 2/3 người trong mẫu gặp bỏ sót; B không gặp nhờ checklist; mẫu chỉ ba người |
| **Usability** | Thấp | Checkbox và link nằm ngay trong repo; học viên vẫn mở nguồn gốc |
| **Feasibility** | Thấp | Markdown và tài liệu gốc đã có; [bảng kiểm thử](../assets/cp6-submission-checklist.md) đã được lập |
| **Viability** | Trung bình | Cần cập nhật khi đề đổi; không có chi phí dịch vụ nhưng học viên phải chịu trách nhiệm rà |

### 8.2. Kết luận

**Quyết định: Go cho pilot No AI quy mô nhỏ.** Dùng checklist trong hai lượt lập kế hoạch/rà bài, không xây công cụ mới và không tự động nộp.

**Ngưỡng dừng:** Nếu sau hai lượt, một lượt vẫn trên 30 phút **hoặc** phát hiện muộn ít nhất một yêu cầu, dừng dùng checklist như nguồn tin cậy; quay về rà trực tiếp RUBRIC và SUBMISSION, sửa checklist trước khi thử tiếp.

**Bước tiếp theo:** bấm giờ bốn bước trong quy trình mới, ghi số mục phát hiện muộn, so với baseline 42 phút và 2 mục, rồi quyết định giữ hoặc sửa checklist.

---

## 9. Hạn chế và hướng tiếp theo

- Mẫu ba người trong bài chưa đại diện cho toàn lớp.
- Tính năng của công cụ từ trang chính thức không chứng minh nhu cầu người dùng; quyết định dựa thêm vào hành vi trong snapshot.
- Nếu checklist không đạt cả thời gian và chất lượng, thử sửa cách viết checklist trước khi tăng mức can thiệp.

## 10. Tài liệu tham khảo

- [README](../../README.md), [RULES](../../RULES.md), [CHECKPOINTS](../../CHECKPOINTS.md), [RUBRIC](../../RUBRIC.md), [SUBMISSION](../../SUBMISSION.md), [worksheet](../../docs/01-worksheet.md).
- [GitHub Docs — About tasklists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists).
- [GitHub Docs — About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/learning-about-issues/about-issues).
- [Google Help — Add or discover new sources for your notebook](https://support.google.com/gemininotebook/answer/16215270).
