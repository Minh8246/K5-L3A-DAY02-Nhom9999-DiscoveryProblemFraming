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
| 1 |Thông tin nhiệm vụ phân tán khiến học viên mất thời gian kiểm tra và dễ bỏ sót hoặc phát hiện muộn deadline.|Value|5|2|Có|
| 2 |Khó xác định thứ tự ưu tiên góp phần khiến học viên làm gấp sát deadline, bên cạnh thiếu thời gian và trì hoãn.|Value|5|2|Có|
| 3 |Vấn đề xuất hiện ở nhiều học viên học song song các chương trình, không chỉ người đưa ra candidate #7.|Value|5|1|Có|
| 4 |Người học có thể duy trì cập nhật và điều chỉnh danh sách nhiệm vụ tập trung mà không thấy quá phiền.|Usability|4|1|Sau khi có thử nghiệm|
| 5 |Nhóm có thể lấy được tên nhiệm vụ, deadline và nguồn giao bài đủ chính xác từ dữ liệu người học cung cấp trong phạm vi lab.|Feasibility|5|1|Có|
| 6 |Thời gian tiết kiệm lớn hơn thời gian nhập liệu, kiểm tra và sửa thông tin của giải pháp.|Viability|4|1|Sau khi có thử nghiệm|

Giả định nhóm kiểm chứng trong buổi này: #1, #2 và #3.

Mục tiêu là phân biệt ba nguyên nhân: thông tin phân tán, khó xếp ưu tiên và thiếu thời gian. Nhóm chưa mặc định rằng cần xây ứng dụng mới hoặc sử dụng AI Agent.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn trực tiếp ba học viên học song song nhiều chương trình vào ngày 09/11/2026, tập trung vào lần gần nhất phải làm gấp, cách quản lý hiện tại và nguyên nhân bắt đầu muộn.

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Học viên A (không thuộc nhóm), học song song ở trường, trung tâm tiếng Anh và khóa AI; cùng bối cảnh với candidate #7. Phỏng vấn trực tiếp ngày 09/11/2026.|
| Câu nói đáng nhớ nhất (nguyên văn) |"Mình phải mở từng chỗ để xem có bài gì, nhưng xem xong vẫn phân vân nên làm bài nào trước."|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |Học viên ưu tiên báo cáo ở trường mà chưa kiểm tra lại hạn bài lab AI. Đến tối trước hạn nộp mới nhận ra bài lab còn nhiều phần chưa làm và phải hoàn thành gấp.|
| Hiện đang xử lý bằng cách nào (workaround)? |Mở từng nền tảng, xem lại thông báo, ghi một số việc vào ghi chú điện thoại và tự chọn việc cần làm trước. Danh sách chưa được cập nhật đều.|
| Mất bao lâu, bao lần? |Khoảng 25 phút/ngày, trong đó 8 phút xếp ưu tiên; khoảng 4 lần/tháng làm gấp.|
| Insight / opportunity rút ra |Cần giảm công sức kiểm tra nhiều nguồn và giúp người học nắm đồng thời hạn nộp, phần việc còn lại trước khi chọn ưu tiên.|

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Học viên B, đang học đại học và một khóa tiếng Anh. Phỏng vấn trực tiếp ngày 09/11/2026.|
| Câu nói đáng nhớ nhất (nguyên văn) |"Mình nhớ hạn nộp, nhưng cứ chọn bài dễ làm trước, đến lúc làm bài lớn mới biết không đủ thời gian."|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |Học viên hoàn thành nhiều bài tập ngắn trước rồi mới bắt đầu bài thuyết trình. Dù biết deadline, học viên đánh giá thấp thời gian chuẩn bị và phải làm gấp vào tối cuối.|
| Hiện đang xử lý bằng cách nào (workaround)? |Ghi deadline vào lịch điện thoại nhưng chưa ghi thời lượng dự kiến hoặc chia nhỏ bài lớn.|
| Mất bao lâu, bao lần? |Khoảng 15 phút/ngày kiểm tra và chọn việc, trong đó khoảng 5 phút xếp ưu tiên; khoảng 2 lần/tháng làm gấp.|
| Insight / opportunity rút ra |Nhớ deadline chưa đủ. Người học còn cần nhận biết khối lượng còn lại và thời điểm nên bắt đầu nhiệm vụ lớn.|

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) |Học viên C, đang học đại học và khóa AI, đồng thời có công việc bán thời gian. Phỏng vấn trực tiếp ngày 09/11/2026.|
| Câu nói đáng nhớ nhất (nguyên văn) |"Mình có danh sách và biết bài nào cần làm trước, nhưng hôm đi làm về thì không còn đủ thời gian."|
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? |Ca làm thêm kéo dài khiến học viên không thực hiện được kế hoạch làm bài đã đặt ra. Học viên phải dồn phần còn lại vào ngày sát hạn.|
| Hiện đang xử lý bằng cách nào (workaround)? |Dùng danh sách nhiệm vụ tập trung, ghi deadline và chọn trước công việc cho ngày hôm sau.|
| Mất bao lâu, bao lần? |Khoảng 5–10 phút/ngày kiểm tra và điều chỉnh kế hoạch; khoảng 3 lần/tháng làm gấp, chủ yếu do thời gian rảnh bị thu hẹp.|
| Insight / opportunity rút ra |Quản lý thông tin và ưu tiên không giải quyết được toàn bộ tình trạng làm gấp. Cần nhận diện trường hợp khối lượng công việc vượt thời gian có thể dành cho học tập.|

Tổng hợp: Hai trong ba tình huống (A và B) minh họa khó khăn trong việc tổng hợp nhiệm vụ, lựa chọn ưu tiên hoặc ước lượng thời gian thực hiện. Tình huống C đưa ra tín hiệu phản bác: người học vẫn có thể làm gấp dù đã biết deadline và thứ tự ưu tiên, do thời gian học bị hạn chế bởi công việc khác. Vì vậy, nhóm cần kiểm tra đồng thời yếu tố thông tin phân tán, cách lựa chọn ưu tiên và quỹ thời gian thực tế, thay vì mặc định việc làm gấp chỉ do quản lý deadline chưa hiệu quả.

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
|Mô tả candidate #7 trong CP3|1 người tự báo cáo|Có ước lượng thời gian kiểm tra, xếp ưu tiên và tần suất làm gấp.|Chưa có log hoặc tình huống cụ thể để xác định nguyên nhân.|
|Snapshot A |1 tình huống|Minh họa khả năng thông tin phân tán và khó chọn ưu tiên cùng góp phần gây làm gấp.|Việc không cập nhật ghi chú cũng có thể liên quan đến thói quen sử dụng.|
|Snapshot B |1 tình huống|Minh họa khó khăn chọn ưu tiên và ước lượng công sức dù đã biết deadline.|Không ủng hộ giả định rằng bỏ sót deadline luôn là nguyên nhân chính.|
|Snapshot C |1 tình huống|Minh họa nhu cầu cân đối nhiệm vụ với thời gian rảnh.|Cho thấy vẫn có thể làm gấp dù đã có danh sách và biết thứ tự ưu tiên.|

**Nhóm đã sửa problem thế nào sau kiểm chứng: không quy toàn bộ tình trạng làm gấp cho việc kiểm tra nhiều nền tảng: Học viên học song song ở trường, trung tâm tiếng Anh và khóa AI gặp khó khăn khi tổng hợp nhiệm vụ và lựa chọn việc cần làm trước dựa trên deadline, khối lượng còn lại và thời gian rảnh. Candidate #7 tự báo cáo dành khoảng 25 phút/ngày cho kiểm tra và xếp ưu tiên, trong đó 8 phút cho xếp ưu tiên, đồng thời khoảng 4 lần/tháng phải làm gấp sát deadline. Cần xác định mức đóng góp của khó khăn quản lý thông tin so với thiếu thời gian và trì hoãn.**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Todoist — Quick Add + Calendar integration** | [Quick Add — Todoist Help](https://www.todoist.com/help/todoist/features/use-task-quick-add-in-todoist-va4Lhpzz); [Calendar integration — Todoist Help](https://www.todoist.com/help/todoist/integrations/use-the-calendar-integration-rCqwLCt3G) | Tập trung nhiệm vụ vào một inbox; gắn deadline, priority, label, reminder; xem nhiệm vụ cùng lịch Google/Outlook. | Quick Add nhận ngày, deadline và priority từ nội dung nhập; có phím tắt để ghi nhanh khi đang ở ứng dụng khác. Đây là mức can thiệp đơn giản, dễ pilot. | Người dùng vẫn phải tự nhận biết và nhập nhiệm vụ từ Zalo, Discord, Cohort hoặc web khóa học. Calendar integration không biến sự kiện lịch bên ngoài thành task; việc kết nối lịch cũng cần cấp quyền. | Thử trước một “single source of truth” và quy tắc nhập task thủ công; đo xem riêng thay đổi quy trình có giảm thời gian và số lần làm gấp hay không trước khi thêm AI. |
| **Zapier — Discord → Todoist** | [Discord + Todoist integration — Zapier](https://zapier.com/apps/discord/integrations/todoist); [Pricing — Zapier](https://zapier.com/pricing) | Nối trigger Discord "New Message Posted to Channel" (tin nhắn mới trong một kênh cụ thể) hoặc "New Mention" với action Todoist "Create Task" để tự tạo task. | Trigger và action có sẵn, không cần tự viết code; giảm bước đọc lại và chép nhiệm vụ từ một nguồn cụ thể. | Trang tích hợp chỉ cho thấy luồng Discord–Todoist; Zalo, ứng dụng tiếng Anh, Cohort và web khóa học vẫn cần connector hoặc cách nhập khác. Trigger theo kênh bắt mọi tin nhắn mới nên có nguy cơ biến message không phải nhiệm vụ thành task. Theo trang giá, gói Free kiểm tra dữ liệu mới 15 phút/lần và không có Filter (Filter & Paths chỉ có từ gói Professional). | Chỉ pilot với một kênh Discord có cấu trúc rõ. Gói Free không lọc được theo keyword, nên bắt buộc người dùng duyệt task trước khi đưa vào danh sách ưu tiên. Không nên tự động gom mọi message. |
| **Motion — Auto-scheduling** | [Auto-scheduling — Motion Help Center](https://www.usemotion.com/help/time-management/auto-scheduling); [How auto-scheduling works — Motion Help Center](https://www.usemotion.com/help/time-management/auto-scheduling/reference-auto-scheduling/how-auto-scheduling-works-behind-the-scenes) | Sau khi nhiệm vụ đã được tập trung, hệ thống xếp lịch dựa trên duration, deadline, priority, thời gian rảnh và tự sắp lại khi lịch thay đổi. | Giải trực tiếp bottleneck xếp thứ tự/lịch làm; có cảnh báo khi task có nguy cơ trễ và tự điều chỉnh theo thay đổi lịch. | Không tự giải quyết đầy đủ bước lấy nhiệm vụ từ các nguồn của nhóm. Kết quả phụ thuộc vào deadline, duration và priority được nhập đúng; tự sắp lịch sai có thể khiến người dùng tin vào một kế hoạch không phù hợp. | Chỉ cân nhắc mức AI/optimization sau khi dữ liệu task đầu vào đã đủ và đúng; luôn cho người dùng xem, sửa, tắt auto-scheduling hoặc đổi priority. |

**Phạm vi kiểm tra nguồn:** các link trên là tài liệu chính thức, trang tích hợp hoặc trang giá của nhà cung cấp. Đã mở lại toàn bộ link ngày 09/11/2026: tất cả đều truy cập được và nội dung khớp với phần trích trong bảng. Các tính năng mới được kiểm trên tài liệu, chưa thử với tài khoản và kênh dữ liệu thực tế của nhóm; việc này để lại cho bước pilot.

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
| **Actor** | Học viên học song song từ hai chương trình trở lên (trường, trung tâm tiếng Anh, khóa AI). Họ nhận nhiệm vụ từ nhiều nền tảng (với candidate #7 là 5 nền tảng: Zalo, Discord, ứng dụng tiếng Anh, Cohort, web khóa AI) và mỗi ngày tự quyết nên làm việc nào trước. Bằng chứng: candidate #7 (Quân) và 3 học viên được phỏng vấn ở CP4 (A, B, C). |
| **Quy trình** | Đầu ngày hoặc trước mỗi phiên học, tổng khoảng 25 phút/ngày (dao động 15–30): (1) mở lần lượt 5 nền tảng xem thông báo mới: 7' → (2) liệt kê nhiệm vụ vào ghi chú: 5' → (3) kiểm tra deadline và khối lượng từng việc: 5' → (4) xếp thứ tự ưu tiên, chọn việc làm hôm nay: 8' → (5) làm theo thứ tự đã chọn. Số phút lấy từ quy trình nháp của candidate #7 (báo cáo cá nhân của Quân, CP2). |
| **Bottleneck** | Bước 4, xếp thứ tự ưu tiên: khoảng 8 phút/ngày. Đây là bước quyết định làm việc nào trước, nhưng đầu vào thường thiếu. Danh sách ở bước 1–2 có thể sót việc ở nền tảng chưa mở lại (A ưu tiên báo cáo ở trường vì chưa kiểm lại hạn bài lab AI). Bước 3 chỉ có deadline, chưa có ước lượng khối lượng còn lại và thời gian rảnh thực tế (B biết hạn nhưng đánh giá thấp thời gian chuẩn bị bài thuyết trình). Bước 1–2 tốn nhiều phút hơn (12') nhưng chỉ là chi phí thời gian; bước 4 mới là nơi chọn sai dẫn đến làm gấp. |
| **Impact** | Candidate #7 mất khoảng 25 phút/ngày (khoảng 175 phút/tuần) chỉ để kiểm tra và chọn việc, và khoảng 4 lần/tháng phải làm gấp sát deadline nên kết quả chưa đầy đủ. Cả 3 người được phỏng vấn cũng làm gấp 2–4 lần/tháng (A: 4, B: 2, C: 3). Chưa tách được bao nhiêu lần làm gấp do thông tin phân tán hoặc chọn ưu tiên sai, bao nhiêu lần do thiếu thời gian (C vẫn làm gấp dù đã có danh sách và biết thứ tự). |
| **Success Metric** (baseline → target, cách đo) | **Chính, số lần làm gấp:** baseline khoảng 4 lần/tháng (candidate #7 tự ước lượng theo trí nhớ tháng gần nhất) → target tối đa 1 lần/tháng.<br>**Phụ, thời gian kiểm tra và xếp ưu tiên:** baseline khoảng 25 phút/ngày (tự ước lượng, dao động 15–30) → target tối đa 10 phút/ngày.<br>**Cách đo:** (a) bấm giờ mỗi lần kiểm tra, từ lúc mở nền tảng đầu tiên đến lúc chốt việc làm hôm nay; (b) nhật ký deadline, mỗi nhiệm vụ một dòng: ngày giao, ngày biết đến, hạn, ngày bắt đầu, ngày xong, có làm gấp không. "Làm gấp" là khi phần lớn khối lượng phải làm trong 24 giờ cuối trước hạn, hoặc nộp chưa đủ phần yêu cầu. Ghi 2 tuần trước khi thay đổi quy trình để có baseline đo thật, rồi so với 4 tuần sau khi thay đổi. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | **AI (nếu nhóm chọn dùng ở CP6) không được:** tự quyết thứ tự ưu tiên hay việc làm hôm nay (chỉ được đề xuất kèm lý do); tự thêm, sửa hoặc xoá nhiệm vụ và deadline trong danh sách chính khi người học chưa xác nhận; tự đoán deadline khi thông báo không ghi rõ (phải đánh dấu "chưa rõ hạn"); tự gửi tin nhắn, nộp bài hay trả lời giảng viên và nhóm trên bất kỳ nền tảng nào; đọc tin nhắn cá nhân ngoài các kênh và thông báo người học chủ động đưa vào.<br>**Con người kiểm tra (HITL) khi:** (1) có nhiệm vụ mới, trước khi đưa vào danh sách ưu tiên: xác nhận tên, hạn, nguồn; (2) deadline chưa rõ hoặc hai nguồn ghi khác nhau: mở thông báo gốc để đối chiếu; (3) nhiệm vụ còn dưới 48 giờ đến hạn, hoặc khối lượng còn lại có thể vượt thời gian rảnh trước hạn: người học tự quyết chia nhỏ, cắt bớt hay xin gia hạn. Ước lượng khối lượng và thời gian rảnh luôn do người học đưa ra hoặc xác nhận, AI không tự ước lượng thay. |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

Cách phản biện: nhờ Claude đóng vai "PM hoài nghi", đối chiếu bản nháp Problem Statement v0 với kết quả kiểm chứng ở mục 3 và checklist CP5. Các điểm "sửa ngay ở v0" đã có trong bảng trên; các điểm "đưa vào v1" để lại cho CP6.

| # | Điểm AI phản biện | Đồng ý? | Xử lý |
|---:|---|---|---|
| 1 | Cả hai baseline (25 phút/ngày, 4 lần/tháng) là ước lượng theo trí nhớ của 1 người, chưa có log. Nếu baseline sai thì đạt target 4 → 1 cũng không chứng minh được gì. | Đồng ý | Sửa ngay ở v0: ghi rõ nguồn và tính chất tự ước lượng của baseline; thêm 2 tuần ghi nhật ký và bấm giờ trước khi thay đổi quy trình để có baseline đo thật. |
| 2 | Số lần làm gấp/tháng phụ thuộc số deadline trong tháng: tháng ít bài thì tự giảm mà không nhờ thay đổi gì. Ngoài ra C làm gấp vì thiếu thời gian, nguyên nhân mà việc tổng hợp hay xếp ưu tiên không chạm tới. | Đồng ý | Đưa vào v1 (CP6): đổi metric chính thành tỉ lệ nhiệm vụ làm gấp trên tổng nhiệm vụ có hạn trong kỳ; nhật ký ghi thêm nguyên nhân mỗi lần làm gấp (sót thông tin / chọn ưu tiên sai / ước lượng sai khối lượng / thiếu thời gian) và báo cáo riêng từng nhóm nguyên nhân. Dùng tỉ lệ cũng giải quyết việc kỳ baseline (2 tuần) và kỳ so sánh (4 tuần) dài khác nhau. |
| 3 | Metric phụ chỉ đo tốc độ: kiểm tra nhanh hơn có thể kéo theo sót nhiệm vụ nhiều hơn mà metric vẫn "đạt". | Đồng ý | Đưa vào v1: thêm guardrail "số nhiệm vụ bị sót hoặc biết đến khi còn dưới 48 giờ đến hạn không tăng so với 2 tuần baseline", lấy từ cột "ngày biết đến" trong nhật ký. |
| 4 | Bottleneck chọn bước 4 (8') trong khi bước 1–2 cộng lại tốn 12'. Có đang đặt nghẽn sai chỗ không? | Đồng ý một phần | Giữ bước 4 vì đây là bước dẫn đến hậu quả (chọn sai việc → làm gấp), còn bước 1–2 là chi phí thời gian. Sửa ngay ở v0: ghi rõ lý do này và số phút của bước 1–2 trong ô Bottleneck. |
| 5 | Bản nháp Boundary chỉ ghi "AI không tự quyết, con người kiểm tra", chưa nói kiểm khi nào nên không kiểm được. | Đồng ý | Sửa ngay ở v0: liệt kê 3 tình huống bắt buộc con người kiểm tra (nhiệm vụ mới; deadline chưa rõ hoặc lệch nguồn; còn dưới 48 giờ hoặc quá tải). |
| 6 | Actor gộp cả người làm gấp vì thiếu thời gian (C). Với nhóm này, cải thiện việc tổng hợp và xếp ưu tiên có thể không có tác dụng. | Đồng ý một phần | Chưa thu hẹp actor ở v0 vì mới có 1/3 snapshot. Sau 2 tuần baseline, nếu phần lớn lần làm gấp do thiếu thời gian thì v1 thu hẹp actor hoặc ghi rõ phần này nằm ngoài phạm vi. |
| 7 | Target tối đa 1 lần/tháng chưa có căn cứ; dữ liệu 1 tháng của 1 người quá ít để tách thay đổi thật khỏi dao động ngẫu nhiên. | Đồng ý một phần | Giữ target của candidate #7 làm mục tiêu ban đầu vì do chính người gặp vấn đề đặt; xem lại sau khi có baseline đo thật. |
| 8 | Kiểm tra Problem Statement có lẫn giải pháp không. | — | Đạt: 6 trường không nêu tên công cụ hay tính năng; Boundary chỉ nói AI nếu được chọn ở CP6. Khi rà lại đã sửa thêm chữ "nhập" ở Boundary (ngầm giả định có công cụ nhập liệu) thành "đưa ra hoặc xác nhận". |

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
