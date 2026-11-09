# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhom9999
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): (#7, Nguyễn Công Quân) Học viên học song song ở trường, khóa tiếng Anh và khóa AI mất khoảng 25 phút mỗi ngày để kiểm tra nhiệm vụ trên nhiều nền tảng và xếp thứ tự ưu tiên, nên khoảng 4 lần/tháng phải làm gấp sát deadline.
- Quyết định cuối: Go / Not Yet / No-Go

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Vũ Quang Minh | Khi luyện nghe tiếng Anh, tôi muốn tìm được bài nghe vừa trình độ, để không phí thời gian vào bài quá khó hoặc đã nghe | Sinh viên tự luyện nghe tiếng Anh ở nhà | Xem tiêu đề video rồi nghe thử, không hợp lại chọn bài khác (lặp nhiều lần): ~25 phút trong tổng ~30 phút tìm bài mỗi buổi, 7 buổi/tuần |Bạn dựa vào tiêu chí nào để xác định một bài nghe vừa trình độ? Nếu chỉ mất 25 phút tìm bài nhưng sau đó vẫn luyện nghe được thì vấn đề này có thực sự nghiêm trọng không? (Người hỏi: Hà Huy Thái)|
| 2 | Vũ Quang Minh | Khi luyện nói, tôi muốn biết mình phát âm một từ đúng hay sai, để không mang lỗi sai vào giao tiếp thật | Sinh viên tự luyện nói tiếng Anh một mình | Nghe lại bản ghi âm để so với mẫu: bình thường ~5 phút/buổi; lần gần nhất phải nghe lại 5 lần, mất ~30 phút |Làm sao bạn xác định phát âm đúng hay sai khi nghe lại bản ghi âm? Bạn có chắc việc nghe lại nhiều lần là do thiếu công cụ đánh giá chứ không phải do chưa biết cách phát âm? (Người hỏi: Nguyễn Công Quân)|
| 3 | Vũ Quang Minh | Khi viết xong một đoạn tiếng Anh, tôi muốn biết câu nào sai ngữ pháp và vì sao, để không lặp lại lỗi | Sinh viên tự luyện viết tiếng Anh | Tự soát lỗi: 10 phút/bài mà vẫn sót ~10 lỗi (người chấm chỉ ra sau khi nộp) |Bạn thường mắc những lỗi ngữ pháp nào và tại sao không tự nhận ra được? Nếu sử dụng công cụ kiểm tra ngữ pháp, liệu bạn có hiểu nguyên nhân để tránh lặp lại lỗi không? (Người hỏi: Hà Huy Thái)|
| 4 | Hà Huy Thái | Khi chuẩn bị nộp bài thực hành, tôi muốn biết còn thiếu file hay mục nào, để tránh nộp bài chưa đầy đủ | Sinh viên làm và nộp bài thực hành | So từng yêu cầu với từng file, dễ bỏ sót (chưa đo số phút) |Những yêu cầu nộp bài có được giảng viên cung cấp rõ ràng từ đầu không? Bạn thường bỏ sót file do không đọc kỹ yêu cầu hay do có quá nhiều file và định dạng khác nhau? (Người hỏi: Vũ Quang Minh)|
| 5 | Hà Huy Thái | Khi chương trình Python báo lỗi, tôi muốn hiểu lỗi và biết cần sửa chỗ nào, để tiếp tục làm bài | Sinh viên đang học Python/AI | Đọc lỗi và tìm nguyên nhân (chưa đo số phút) |Bạn gặp khó khăn ở việc hiểu thông báo lỗi hay tìm cách sửa lỗi? Nếu có công cụ giải thích lỗi nhưng bạn vẫn không hiểu kiến thức Python nền tảng thì vấn đề có được giải quyết không? (Người hỏi: Nguyễn Công Quân)|
| 6 | Hà Huy Thái | Khi train mô hình nhiều lần, tôi muốn xem lại kết quả từng lần, để chọn cấu hình phù hợp | Người học và làm bài thực hành AI | Kết quả để ở nhiều nơi nên khó so sánh (chưa đo số phút) |Bạn dựa vào những tiêu chí nào để so sánh kết quả giữa các lần train? Việc khó theo dõi kết quả có thường xuyên ảnh hưởng đến quyết định chọn mô hình hay chỉ gây bất tiện? (Người hỏi: Vũ Quang Minh)|
| 7 | Nguyễn Công Quân | Khi bắt đầu một ngày có nhiều nhiệm vụ từ trường, khóa tiếng Anh và khóa AI, tôi muốn biết việc nào cần ưu tiên và hạn của từng việc, để không phải làm gấp sát deadline | Học viên học song song ở trường, trung tâm tiếng Anh và khóa AI | Xếp thứ tự ưu tiên: ~8 phút trong tổng ~25 phút/ngày kiểm tra nhiệm vụ (hậu quả: ~4 lần/tháng phải làm gấp sát deadline) |Bạn đang quản lý deadline bằng cách nào và tại sao cách đó chưa hiệu quả? Việc làm gấp sát deadline là do không biết thứ tự ưu tiên hay do khối lượng công việc quá nhiều và thiếu thời gian? (Người hỏi: Hà Huy Thái)|
| 8 | Nguyễn Công Quân | Khi quay lại báo cáo đang làm dở, tôi muốn biết đã làm đến đâu và bước tiếp theo, để tiếp tục ngay | Học viên chuyển qua lại giữa báo cáo ở trường, bài tiếng Anh và bài lab | Đọc lại phần đã viết: ~4 phút trong tổng ~10 phút mỗi lần quay lại, 3 lần/tuần |Tại sao bạn mất thời gian khi quay lại công việc đang làm dở? Nếu có ghi chú tiến độ và việc tiếp theo, bạn có thực sự tiếp tục nhanh hơn hay vẫn cần đọc lại toàn bộ nội dung để nhớ ngữ cảnh? (Người hỏi: Vũ Quang Minh)|
| 9 | Nguyễn Công Quân | Khi tổng hợp chi tiêu trong tháng, tôi muốn phân loại giao dịch ngân hàng, để biết tiền đã đi đâu | Người tự theo dõi chi tiêu cá nhân | Nhớ lại mục đích từng giao dịch: ~15 phút trong tổng ~30 phút mỗi lần tổng hợp, 2 lần/tháng |Bạn có thường xuyên không nhớ mục đích của các giao dịch ngân hàng không? Nếu có thể tự phân loại giao dịch bằng ghi chú ngay lúc chi tiêu thì vấn đề tổng hợp cuối tháng có còn xảy ra không? (Người hỏi: Hà Huy Thái)|

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A — Học tập và cải thiện kỹ năng | #1 Tìm bài nghe phù hợp trình độ; #2 Kiểm tra phát âm; #3 Soát lỗi ngữ pháp | Sinh viên gặp khó khăn khi tự đánh giá năng lực, phát hiện lỗi và cải thiện kỹ năng học tập mà không có người hướng dẫn trực tiếp |
| B — Hỗ trợ thực hành và quản lý kết quả học tập | #4 Kiểm tra đủ file trước khi nộp; #5 Hiểu và sửa lỗi Python; #6 Theo dõi kết quả train mô hình | Sinh viên gặp khó khăn khi xử lý, kiểm tra và theo dõi các bước trong quá trình thực hành, dẫn đến mất thời gian và dễ mắc sai sót |
| C — Quản lý công việc và thông tin cá nhân | #7 Quản lý nhiệm vụ và deadline; #8 Tiếp tục công việc đang làm dở; #9 Phân loại giao dịch chi tiêu | Người dùng gặp khó khăn trong việc tổng hợp thông tin, ghi nhớ trạng thái và đưa ra quyết định khi có nhiều dữ liệu hoặc nhiệm vụ cần xử lý |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

Outcome gắn với candidate #7 vì vấn đề có số liệu cụ thể, tần suất xảy ra và hậu quả tương đối rõ ràng.

```text
OUTCOME: Giảm tình trạng phải làm gấp sát deadline của học viên
├── Opportunity A:
│   Khó xác định nhiệm vụ nào cần ưu tiên khi có nhiều
│   công việc từ trường, trung tâm tiếng Anh và khóa AI.
│
├── Opportunity B:
│   Khó nắm bắt deadline của các nhiệm vụ khi thông tin
│   được phân tán ở nhiều nguồn khác nhau.
│
└── Opportunity C:
    Khó duy trì tiến độ và cân đối thời gian giữa nhiều
    nhiệm vụ có mức độ quan trọng và thời hạn khác nhau.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ~~Tạo chatbot nhắc nhở deadline~~
- ~~Xây dựng ứng dụng quản lý công việc~~
- ~~Tự động sắp xếp lịch học bằng AI~~
- ~~Tạo dashboard hiển thị danh sách nhiệm vụ~~
- ~~Sử dụng AI Agent để phân tích và phân chia công việc~~

Lý do: đây đều là những cách giải quyết vấn đề (solution), chưa phải nhu cầu hoặc khó khăn thực tế của người dùng (opportunity).

### 2.4. Chấm điểm shortlist (1–5)

Shortlist gồm 3 candidate: #7, #5 và #8.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #7 Quản lý nhiệm vụ và deadline | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| #5 Hiểu và sửa lỗi Python | 5 | 4 | 3 | 3 | 4 | 5 | 5 | 29 |
| #8 Tiếp tục công việc đang làm dở | 5 | 4 | 4 | 4 | 5 | 5 | 5 | 32 |

Giải thích điểm:

- **#7 – Quản lý nhiệm vụ và deadline:** có actor cụ thể, quy trình rõ ràng, mất khoảng 8 phút mỗi ngày để sắp xếp thứ tự ưu tiên và có khoảng 4 lần/tháng phải làm gấp sát deadline. Đây là candidate có bằng chứng pain tốt nhất.
- **#5 – Hiểu và sửa lỗi Python:** vấn đề khá rõ và phù hợp với AI Lab, nhưng chưa có số liệu về thời gian tìm lỗi hoặc tần suất gặp lỗi nên impact chưa được chứng minh đầy đủ.
- **#8 – Tiếp tục công việc đang làm dở:** có số liệu cụ thể là mất khoảng 10 phút mỗi lần quay lại (riêng bước đọc lại phần đã viết ~4 phút), xảy ra 3 lần/tuần. Phạm vi tương đối rõ và có thể thử nghiệm bằng nhiều phương pháp khác nhau.

**Candidate được chọn:** #7 — Quản lý nhiệm vụ và deadline từ nhiều nền tảng (Nguyễn Công Quân)

**Vì sao chọn:**

- Pain có số liệu cụ thể về thời gian và tần suất.
- Hậu quả thực tế là phải làm gấp sát deadline.
- Có nhiều hướng tiếp cận để so sánh No AI, Rule-based, Workflow và AI Agent.
- Thành viên nhóm có thể dễ dàng hiểu và kiểm chứng vấn đề trong môi trường học tập thực tế.

**Vì sao loại các candidate còn lại:**

- **#5:** chưa có số liệu về thời gian tìm lỗi hoặc tần suất gặp lỗi, nên impact chưa được chứng minh.
- **#8:** vấn đề có số liệu về thời gian và tần suất, nhưng mức độ ảnh hưởng chưa thực sự nghiêm trọng. Việc mất khoảng 10 phút mỗi lần quay lại công việc (3 lần/tuần, khoảng 30 phút/tuần) chủ yếu gây gián đoạn và mất thời gian, chưa chứng minh được hậu quả lớn hoặc ảnh hưởng rõ rệt đến kết quả học tập.

**Xử lý bất đồng (nếu có):** Không có. Cả nhóm đồng ý chọn #7.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
