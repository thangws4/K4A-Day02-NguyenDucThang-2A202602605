# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Thắng
- Mã học viên: 2A202602605
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): PM cho đồ án tốt nghiệp
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): Đọc tài liệu, phân công task cho member, kiểm tra task của các member, đọc và merge code, báo cáo cho mentor.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Tìm lại thông báo/deadline cũ trong Discord hoặc Canvas của lớp khi làm bài, vì thông tin bị trôi giữa nhiều kênh |team members | [15 phút/lần tìm, 1 lần/ngày] |
| 2 | Tốn thời gian | Đọc slide/tài liệu lab dài trước deadline để biết chính xác cần nộp gì, dễ đọc sót mục | team members | [30 phút/lần đọc] |
| 3 | Tốn thời gian | Tổng hợp code review/feedback rải rác từ nhiều bạn trong nhóm (Discord, GitHub comment) trước khi merge | team members | [60 phút/lần tổng hợp, 3-4 comment bị bỏ sót/lần] |
| 4 | AI có thể tốt hơn | Tóm tắt/so sánh nhiều nguồn tài liệu tham khảo (paper, docs, blog) khi làm assignment | member | [30 phút/nguồn] |
| 5 | Tốn thời gian | Tìm lại quyết định/lý do thảo luận cũ của nhóm (vd vì sao chọn candidate X) khi viết lại Problem Statement | team members | [30 phút/lần tìm lại, 2-3 lần/tuần] |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Gợi ý thêm problem theo 4 lăng kính (lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác) dựa trên bối cảnh PM cho đồ án tốt nghiệp với công việc hằng tuần gồm đọc tài liệu, phân công task cho member, kiểm tra task của các member, đọc và merge code, báo cáo cho mentor
- Ý dùng được: tìm lại thông báo/deadline cũ trong Discord/Canvas, đọc tài liệu lab dài trước deadline, tổng hợp code review rải rác trong nhóm, tóm tắt/so sánh nhiều nguồn tham khảo cho assignment, tìm lại quyết định cũ của nhóm khi viết Problem Statement.
- Ý bỏ vì không phải pain thật: "TA/giảng viên phải trả lời lặp lại câu hỏi trên Discord" — bỏ vì bản thân không phải TA nên không tự đo được số liệu; "trợ lý AI học tập toàn năng" — bỏ vì quá rộng, không có actor và bottleneck cụ thể.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể — 5 dòng, mỗi dòng có actor và số phút/tần suất tự đo
- [x] Dùng ít nhất 3/4 lăng kính — đã dùng 3/4: Lặp lại, Tốn thời gian, AI có thể tốt hơn
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian" — mỗi dòng mô tả rõ workflow và bối cảnh cụ thể

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #3 — Tổng hợp code review/feedback rải rác (Discord + GitHub comment) trước khi merge | Tôi chính là người làm bước này nên workflow vẽ được từng bước; đã đo 60 phút/lần và đếm được 3-4 comment bị sót; có metric kép (thời gian + số comment sót) | Baseline 60 phút mới đo từ trải nghiệm của tôi (n=1), chưa bấm giờ lặp lại nhiều lần |
| 2 | #5 — Tìm lại quyết định/lý do thảo luận cũ của nhóm | Cả 4 người trong nhóm đều gặp, 2-3 lần/tuần; hậu quả rõ: dễ chốt lại khác với quyết định cũ | Có thể chỉ cần decision log thủ công là đủ, chưa chắc cần AI; export/đọc dữ liệu Discord có giới hạn |
| 3 | #4 — Tóm tắt/so sánh nhiều nguồn tài liệu tham khảo cho đồ án | 30 phút/nguồn, lặp lại mỗi tuần khi làm phần literature review; AI mạnh ở việc đọc/tổng hợp ngôn ngữ | Chất lượng "hiểu đúng nguồn" khó đo bằng số; rủi ro trích dẫn sai phải kiểm lại bản gốc |

Vì sao chưa chọn #1 và #2: cả hai chủ yếu là vấn đề quy trình. Thông báo/deadline trôi kênh có thể xử lý bằng rule (pin thông báo, một kênh duy nhất cho deadline, checklist nộp bài) mà chưa cần AI, nên impact của AI ở đây thấp hơn 3 bài trên.

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tổng hợp code review/feedback trước khi merge

```text
Problem 1 câu:
Mỗi lần chuẩn bị merge code cho đồ án, tôi (PM) phải gom feedback nằm rải rác ở
GitHub PR comment và chat Discord của 3 member, mất khoảng 60 phút và vẫn sót 3-4
comment nên có feedback không được xử lý.

Actor:
Tôi — PM đồ án tốt nghiệp, người đọc và merge code cho nhóm 4 người.

Thời điểm / bối cảnh:
Trước mỗi lần merge (khoảng 2 lần/tuần), sau khi các member đã review chéo và đã
bàn thêm ngoài PR trong Discord.

Current workflow 3-7 bước:
1. Mở PR, đọc diff để hiểu member đã sửa gì (15')
2. Đọc comment review nằm trong PR (10')
3. Lục Discord tìm feedback đã nói ngoài PR (15')   <-- bottleneck
4. Gom tất cả thành một list việc cần sửa (15')     <-- bottleneck
5. Nhắc member sửa, kiểm lại rồi merge (5')

Bottleneck:
Bước 3-4: feedback nằm ở hai nơi và không có danh sách thống nhất, nên tôi phải
đọc lại thủ công rồi tự gom. Đây là chỗ 3-4 comment bị sót mỗi lần.

Impact:
60 phút/lần × 2 lần/tuần = khoảng 120 phút/tuần của PM. Comment bị sót làm member
phải sửa lại ở lần merge sau, và có feedback tốt bị bỏ quên hoàn toàn.

Success metric:
Giảm 60 phút → dưới 25 phút/lần; số comment bị sót từ 3-4 → 0-1.
Cách đo: bấm giờ 3 lần merge kế tiếp; sau mỗi lần đối chiếu list việc cần sửa với
toàn bộ comment PR + Discord để đếm số comment bị bỏ ra ngoài.

Non-AI alternative:
Ra rule: mọi feedback bắt buộc nằm trong PR comment, không bàn code trong Discord;
thêm PR template + review checklist. Cách này xử lý được phần "rải rác hai nơi",
nhưng chưa giảm thời gian đọc và phân loại comment.

AI hypothesis:
AI gom comment từ PR (và Discord export), phân loại thành must-fix / nice-to-have /
câu hỏi, rồi xuất ra checklist việc cần sửa. Tôi vẫn tự đọc diff và tự quyết định
merge.

Quick gut:
[x] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 5 bước, 60 phút/lần × 2 lần/tuần

[1 Đọc diff PR để hiểu member đã sửa gì: 15' - PM]
→ [2 Đọc comment review nằm trong PR: 10' - PM]
→ [3 Lục Discord tìm feedback đã nói ngoài PR: 15' - PM]   <-- bottleneck
→ [4 Gom tất cả thành một list việc cần sửa: 15' - PM]     <-- bottleneck
→ [5 Nhắc member sửa, kiểm lại rồi merge: 5' - PM]

Handoff yếu: feedback nằm ở HAI nơi (PR comment + Discord) và không có danh sách
thống nhất, nên 3-4 comment bị sót mỗi lần và member phải sửa lại ở lần merge sau.

FUTURE STATE — 5 bước, 23 phút

[1 Script kéo comment PR + Discord export về một chỗ: 2']      -- Rule/script
→ [2 AI phân loại must-fix / nice-to-have / câu hỏi: 1']       -- Workflow step
→ [3 AI xuất checklist kèm link tới comment gốc: 1']           -- Workflow step
→ [4 PM đọc diff + đối chiếu checklist, tự quyết merge: 15']   -- Human boundary
→ [5 Nhắc member sửa + merge: 4']

Boundary:
- AI chỉ gom và phân loại comment, luôn kèm link tới comment gốc để PM kiểm.
- AI KHÔNG đánh giá code đúng/sai, KHÔNG tự merge, KHÔNG tự đóng comment.

Fallback:
AI phân loại sai hoặc bỏ sót comment → bỏ checklist, PM đọc thẳng danh sách comment
thô đã được gom sẵn ở bước 1 (bước 1 vẫn có giá trị dù không có AI).
Script hỏng → quay về cách cũ: tự lục PR + Discord như hiện tại.

Bottleneck mới:
Bước 4 — PM đọc diff và đối chiếu checklist. Đây là bottleneck chấp nhận được vì đó
là điểm kiểm soát chất lượng trước khi merge.
```

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Tổng thời gian | 60 phút | Dưới 25 phút | Target chính |
| Số comment bị sót | 3-4 | 0-1 | Metric thứ hai, quan trọng ngang thời gian |
| Số bước thủ công | 5/5 | 2/5 | PM vẫn đọc diff và quyết merge |
| Bottleneck chính | Gom feedback từ 2 nơi | PM review + quyết merge | Human boundary |
| Risk mới | Không có | AI phân loại sai mức độ, bỏ sót comment | Checklist bắt buộc kèm link comment gốc |


---

#### Problem Card #2 — Tìm lại quyết định cũ của nhóm

```text
Problem 1 câu:
Khi viết lại tài liệu đồ án hoặc trả lời mentor, nhóm mất khoảng 30 phút lục
Discord để tìm lại vì sao đã chốt một quyết định, 2-3 lần/tuần.

Actor:
Cả nhóm 4 người; tôi là PM nên là người bị hỏi lại nhiều nhất.

Thời điểm / bối cảnh:
Khi viết tài liệu, khi mentor hỏi "vì sao chọn hướng này", hoặc khi có người muốn
mở lại một quyết định cũ.

Current workflow 3-7 bước:
1. Nhớ mang máng là đã bàn rồi, nhưng không nhớ ở đâu (5')
2. Search keyword trong Discord (10')
3. Đọc nhiều thread dài để tìm đúng đoạn chốt (10')   <-- bottleneck
4. Hỏi lại trong nhóm nếu không tìm được (5')
5. Viết lại kết luận vào tài liệu

Bottleneck:
Bước 3: quyết định nằm lẫn trong đoạn chat dài, không có tiêu đề và không ai
tổng kết lại, nên search keyword thường ra hàng chục message không liên quan.

Impact:
30 phút × 2-3 lần/tuần = khoảng 60-90 phút/tuần cho cả nhóm. Rủi ro lớn hơn:
chốt lại một hướng khác với quyết định cũ vì không tìm được lý do ban đầu.

Success metric:
Giảm 30 phút → dưới 5 phút/lần tìm; số lần phải hỏi lại cả nhóm từ 2-3 → dưới 1
lần/tuần. Đo bằng cách ghi lại 5 lần tra cứu kế tiếp.

Non-AI alternative:
Decision log trong repo: mỗi quyết định 1 dòng (ngày, quyết định, lý do, link
thread). Rẻ, làm được ngay, và rất có thể đã đủ — đây là lý do card này chưa
phải rank 1.

AI hypothesis:
Semantic search trên dữ liệu chat đã export, trả lời kèm link tới message gốc để
người đọc tự kiểm.

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[x] Chưa biết  (phải thử decision log trước khi kết luận cần AI)
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 4 bước, 30 phút/lần × 2-3 lần/tuần

[1 Nhớ mang máng là đã bàn rồi, không nhớ ở đâu: 5' - người hỏi]
→ [2 Search keyword trong Discord: 10' - người hỏi]
→ [3 Đọc nhiều thread dài để tìm đúng đoạn chốt: 10' - người hỏi]   <-- bottleneck
→ [4 Hỏi lại cả nhóm nếu không tìm được: 5' - cả nhóm]
→ [5 Viết lại kết luận vào tài liệu]

Handoff yếu: quyết định nằm lẫn trong chat dài, không có tiêu đề và không ai tổng
kết lại, nên search keyword ra hàng chục message không liên quan. Bước 4 còn kéo
thêm 3 người khác vào việc của 1 người.

FUTURE STATE — 3 bước, 5 phút

[1 Decision log: 1 dòng/quyết định ghi ngay khi chốt: 1']    -- Rule (người ghi)
→ [2 Tra decision log; nếu không có thì semantic search
   trên chat export: 2']                                     -- Workflow step
→ [3 Người mở link thread gốc kiểm lại trước khi dùng: 2']   -- Human boundary

Boundary:
- AI chỉ tìm và trả về đoạn chat liên quan, BẮT BUỘC kèm link tới message gốc.
- AI KHÔNG tóm tắt thành "quyết định của nhóm" nếu không trỏ được về nguồn.

Fallback:
Search trả lời sai hoặc không có nguồn → quay về hỏi trực tiếp trong nhóm như hiện
tại. Decision log ở bước 1 vẫn còn giá trị hoàn toàn độc lập với AI — đây là lý do
card này Quick gut là "chưa biết": rất có thể chỉ bước 1 đã đủ.

Bottleneck mới:
Bước 1 — kỷ luật ghi decision log. Nếu nhóm quên ghi thì cả workflow sụp, và đây là
vấn đề quy trình chứ không phải vấn đề AI.
```

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Thời gian 1 lần tra cứu | 30 phút | Dưới 5 phút | Đo bằng cách ghi lại 5 lần tra cứu kế tiếp |
| Số lần phải hỏi lại cả nhóm | 2-3 lần/tuần | Dưới 1 lần/tuần | Metric thứ hai: đo chi phí lan sang người khác |
| Risk mới | Không có | AI trả lời sai hoặc bịa "quyết định" không có thật | Bắt buộc kèm link message gốc để người tự kiểm |


---

#### Problem Card #3 — Tóm tắt/so sánh nhiều nguồn tài liệu cho đồ án

```text
Problem 1 câu:
Khi làm phần cơ sở lý thuyết của đồ án, tôi và member research mất khoảng 30 phút
cho mỗi nguồn, trong đó phần nặng nhất là so sánh các nguồn nói khác nhau về cùng
một vấn đề.

Actor:
Tôi và member phụ trách research của nhóm đồ án.

Thời điểm / bối cảnh:
Khi cần chốt hướng kỹ thuật hoặc viết phần tài liệu tham khảo trước buổi báo cáo
mentor.

Current workflow 3-7 bước:
1. Tìm nguồn (paper, docs, blog) (10')
2. Đọc từng nguồn (30'/nguồn)
3. Note lại ý chính theo cách mỗi người tự nghĩ ra (10')
4. So sánh các nguồn, tìm chỗ chúng nói khác nhau (20')  <-- bottleneck
5. Viết vào tài liệu đồ án

Bottleneck:
Bước 4: phải giữ nhiều nguồn trong đầu cùng lúc để so sánh, mà note của mỗi người
lại không cùng cấu trúc nên không đối chiếu trực tiếp được.

Impact:
Khoảng 5 nguồn/tuần ≈ 150 phút/tuần cho 2 người. Hậu quả khi làm vội: chốt hướng
kỹ thuật dựa trên một nguồn duy nhất, đến lúc mentor hỏi mới thấy nguồn khác nói
ngược lại.

Success metric:
Giảm thời gian đọc-hiểu 1 nguồn từ 30 phút → dưới 12 phút; số nguồn bị trích dẫn
sai ý = 0 (kiểm bằng cách đọc lại bản gốc trước khi đưa vào tài liệu).

Non-AI alternative:
Template note cố định cho mọi nguồn: vấn đề / phương pháp / kết quả / hạn chế.
Chỉ cần thống nhất template là bước so sánh đã dễ hơn nhiều.

AI hypothesis:
AI tóm tắt mỗi nguồn theo đúng template rồi lập bảng so sánh các nguồn; người đọc
kiểm lại từng ô bằng bản gốc trước khi dùng.

Quick gut:
[x] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 5 bước, ~60 phút cho 1 nguồn + phần so sánh

[1 Tìm nguồn (paper, docs, blog): 10' - người]
→ [2 Đọc từng nguồn: 30'/nguồn - người]
→ [3 Note lại ý chính theo cách mỗi người tự nghĩ ra: 10' - người]
→ [4 So sánh các nguồn, tìm chỗ nói khác nhau: 20' - người]   <-- bottleneck
→ [5 Viết vào tài liệu đồ án]

Handoff yếu: note của mỗi người không cùng cấu trúc nên không đối chiếu trực tiếp
được; người so sánh phải giữ nhiều nguồn trong đầu cùng lúc.

FUTURE STATE — 4 bước, 25 phút

[1 Tìm nguồn: 10' - người]
→ [2 AI tóm tắt mỗi nguồn theo template 4 mục
   (vấn đề / phương pháp / kết quả / hạn chế): 2']            -- Workflow step
→ [3 AI lập bảng so sánh các nguồn theo đúng 4 mục đó: 1']    -- Workflow step
→ [4 Người đọc kiểm TỪNG Ô bằng bản gốc trước khi
   viết vào tài liệu: 12']                                    -- Human boundary

Boundary:
- AI chỉ tóm tắt và xếp vào template, mỗi ô phải trỏ được về trang/đoạn trong bản gốc.
- AI KHÔNG kết luận "nguồn nào đúng", KHÔNG tạo trích dẫn, KHÔNG viết thay phần
  tài liệu nộp.

Fallback:
AI tóm tắt sai ý hoặc trích dẫn không có trong bản gốc → bỏ bản tóm tắt, đọc thẳng
nguồn và điền tay vào template 4 mục. Template ở bước 2 là phần non-AI và vẫn giúp
bước so sánh dễ hơn hẳn dù không có AI.

Bottleneck mới:
Bước 4 — người kiểm từng ô bằng bản gốc. Không được rút ngắn bước này, vì rủi ro
lớn nhất của card là trích dẫn sai ý một nguồn rồi đưa thẳng vào tài liệu đồ án.
```

| Metric | Trước | Sau kỳ vọng | Ghi chú |
|---|---:|---:|---|
| Thời gian đọc-hiểu 1 nguồn | 30 phút | Dưới 12 phút | Target chính |
| Số nguồn bị trích dẫn sai ý | chưa đếm | 0 | Kiểm bằng cách đọc lại bản gốc trước khi đưa vào tài liệu |
| Cấu trúc note | mỗi người một kiểu | template 4 mục thống nhất | Phần này là **non-AI**, làm được ngay |
| Risk mới | Không có | AI tóm tắt sai ý / bịa trích dẫn | Bước 4 kiểm từng ô là bắt buộc |


---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

> Phần này nên viết lại bằng lời của bạn trước khi pitch — worksheet quy định không dùng AI để nói thay. Dưới đây là bản nháp để bạn sửa.

**Card tôi muốn pitch nhất:**

```text
Card #1 — Tổng hợp code review/feedback rải rác (GitHub PR + Discord) trước khi merge.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Tôi chính là người làm workflow này 2 lần/tuần nên vẽ được đủ 5 bước và biết
bottleneck nằm ở bước gom feedback từ hai nơi, không phải ở bước đọc code.
Tôi đã bấm giờ 60 phút/lần và đếm được 3-4 comment bị sót mỗi lần, nên bài này có
metric kép: thời gian và số comment bị bỏ quên.
Impact khoảng 120 phút/tuần của PM, và comment bị sót còn làm member phải sửa lại
ở lần merge sau.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu chỉ ra rule "mọi feedback bắt buộc nằm trong PR comment" thì phần AI còn
   lại có đáng làm không, hay rule đã giải xong 70-80% vấn đề?
2. Metric "số comment bị sót" do chính tôi tự đếm thì đo thế nào cho khách quan,
   vì tôi vừa là người gom vừa là người kiểm?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: baseline 60 phút chỉ đến từ trải nghiệm của một người và chưa bấm giờ lặp lại; metric "comment bị sót" do chính actor tự đếm nên dễ thiên vị; rule-based fix (bắt buộc feedback vào PR) có thể đã đủ nên dễ bị kết luận là cần AI quá sớm.
- Tôi sửa gì: thêm cách đo cụ thể vào metric (bấm giờ 3 lần merge kế tiếp, đối chiếu checklist với toàn bộ comment để đếm số bị sót), và ghi rõ trong card rằng non-AI alternative phải được thử trước khi kết luận cần AI.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
