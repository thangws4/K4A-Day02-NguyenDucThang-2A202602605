# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Đức Thắng
- Mã học viên: 2A202602605
- Nhóm: [A-PNV] — Toàn, Huy, Dũng, Cường, Thắng
- Vai trò của tôi trong nhóm: Workflow + research + writer
- Candidate problem nhóm chọn: **#4 — VinWonders: dự báo thời gian chờ theo thời gian thực và điều phối luồng khách bằng vé ảo tại các trò chơi đông khách** (do Toàn pitch). Ba candidate của tôi không được chọn, trong đó #1 "gom code review feedback" là bài có tổng điểm cao nhất (34/35) nhưng nhóm vẫn loại.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 5 problems từ công việc PM đồ án của mình, tự bấm giờ từng bài (15'/lần tìm thông báo, 30'/nguồn tài liệu, 60'/lần gom code review) | Mang 3 candidate vào nhóm (#1, #2, #3 ở bảng 3.1), trong đó bài gom code review là candidate duy nhất của tôi có baseline đã bấm giờ |
| Pitch Problem Card | Pitch card "gom code review feedback": 5 bước workflow kèm thời gian từng bước và 2 con số (60 phút/lần, 3-4 comment sót/lần), và tự nêu luôn 2 câu challenge vào chỗ yếu của chính mình | Bài vào shortlist 3 bài cuối và được chấm cao nhất (34/35) nhờ "Pain có evidence" và "Làm trong lab" |
| Challenge bài của bạn khác | Challenge bài VinWonders ở đúng chỗ bằng chứng: hỏi con số "chờ 30-45 phút" lấy ở đâu ra, đã bấm giờ lần nào chưa, và nhóm có quyền truy cập camera/dữ liệu vé để chạy thử trong lab không | Nhóm hạ VinWonders xuống 2 điểm "Pain có evidence" và 2 điểm "Làm trong lab"; hai ô này về sau chính là lý do quyết định cuối phải là Not Yet chứ không phải Go |
| Gom trùng / cluster | Gom 15 candidate thành 4 cụm và chỉ ra cụm C (gom thông tin rời rạc) đang phình to vì cả 3 bài của tôi lẫn bài của Dũng, Cường đều rơi vào đó | Nhóm nhìn ra cụm C là "một mẫu lặp lại" chứ không phải 8 bài khác nhau, và thấy #4 là bài duy nhất ở cụm D — đây là lập luận dẫn tới việc chọn #4 |
| Chọn candidate problem | Phản đối việc chọn #4 vì đi ngược "problem first, evidence first"; khi nhóm vẫn chọn #4 vì impact và giá trị học tập, tôi đề xuất chốt kèm 2 ràng buộc: không được kết luận Go nếu chưa đo baseline thật, và phải thiết kế được cách validate khả thi với nguồn lực sinh viên | Nhóm chọn #4 nhưng có ghi bất đồng vào báo cáo; 2 ràng buộc này đi thẳng vào Phase 4 và quyết định cuối |
| Validation / research | Tìm 4 nguồn có link kiểm được: Disney Virtual Queue, Disney Lightning Lane, Queue-Times.com API, Universal Virtual Line; đồng thời soạn 5 câu hỏi interview/survey cho phần 4.1 | Phát hiện Queue-Times cho wait time thật + lịch sử của 80+ công viên, miễn phí — nhóm kiểm được giả thuyết dự báo mà không cần xin quyền từ VinWonders. Đây là thứ cứu bài khỏi No-Go |
| Workflow nhóm | Vẽ current workflow 5 bước có thời gian từng bước và future workflow đánh dấu rõ bước nào máy / AI / người, kèm boundary và fallback 2 tầng | Nhóm dùng làm workflow bản cuối; chỉ ra được bottleneck thời gian ở bước 4 (xếp hàng) nhưng nguyên nhân gốc ở bước 1 (khách chọn trò chơi khi mù thông tin) |
| Problem Statement | Viết v0, nhận phản biện về metric rồi sửa sang v1 | v1 tách **metric chính** (MAE dự báo < 5 phút — thứ AI thực sự chịu trách nhiệm) khỏi **metric kết quả** (thời gian chờ < 10-12 phút — phụ thuộc cả vận hành), ghi thẳng baseline 30-45' là ước lượng chưa kiểm chứng, và thêm câu "không hứa tăng công suất" |
| Rule / Workflow / Agent | Lập luận chọn Workflow nhưng đặt trên nền một lớp Rule bắt buộc phải thử trước, và viết đường hạ cấp Agent → Workflow → Rule | Nhóm không nhảy sang Agent; giữ được phương án quay về (nhân viên nhập tay mỗi 15 phút) mà vẫn còn phần lớn giá trị thông tin cho khách |
| Decision | Soát 6 câu hỏi và chỉ ra 4/6 là Not Yet đều rơi về cùng một gốc: chưa có số thật, chưa tiếp cận người vận hành | Kết luận Not Yet + danh sách 4 việc validate xếp theo thứ tự dễ làm trước, việc số 1 (thử dự báo trên dữ liệu Queue-Times) làm được ngay không cần xin phép ai |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Rõ nhất là hai chỗ: (1) tìm ra Queue-Times API — nhờ nó mà một bài nhóm không có
dữ liệu vẫn có đường validate thật, nên kết luận là Not Yet chứ không phải No-Go;
và (2) tách metric chính (MAE dự báo) khỏi metric kết quả (thời gian chờ) trong PS
v1, để nhóm không hứa một con số mà AI không kiểm soát được.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ gợi ý thêm problem theo 4 lăng kính dựa trên bối cảnh PM đồ án | Nhắc ra vài bài tôi quên, ví dụ tìm lại quyết định cũ của nhóm | Gợi ý "TA/giảng viên phải trả lời lặp lại câu hỏi" — tôi không phải TA nên không tự đo được; AI cũng để trống toàn bộ cột dấu hiệu thật | Bỏ bài không đo được; tự bấm giờ và điền số thật (15', 30', 60') vào cột dấu hiệu |
| Problem Card | Nhờ dựng khung 3 card từ số liệu tôi đã đo | Dựng nhanh đủ field, không bỏ sót mục nào | AI tự tick sẵn Quick gut là "Workflow" cho card #1, trong khi tôi thấy phần lớn vấn đề có thể xử lý bằng sửa quy trình | Tôi tick thêm "No AI / process fix" vì rule bắt feedback vào PR có thể đã giải phần lớn — và ghi thẳng vào card rằng phải thử non-AI trước |
| Convergence / cluster | Nhờ đề xuất cách gom 15 candidate thành cụm | Gom nhanh và đặt tên cụm gọn | AI gom theo từ khóa bề mặt: xếp "báo cáo an toàn cuối tuần" chung với "báo tin thiếu vị trí" chỉ vì cùng chữ "an toàn" | Gom lại theo *dạng công việc* chứ không theo lĩnh vực, nên #14/#15 về cụm C còn #13 sang cụm A cùng bài báo cháy giả |
| Research | Nhờ tìm tool/pattern tương tự cho bài hàng chờ công viên | Tìm đúng hướng: virtual queue, Lightning Lane, và gợi ý có dữ liệu wait time công khai | Đưa link kèm số liệu không kiểm được, và một nguồn là trang bên thứ ba nhưng nói như trang chính thức của Universal | Kiểm lại từng link bằng search; chỉ giữ link chính thức, ghi rõ nguồn Orlando Informer là bên thứ ba và phải đối chiếu trước khi trích số |
| Problem Statement | Nhờ phản biện v0, chỉ ra field mơ hồ | Chỉ ra "Impact" toàn mô tả cảm giác, và baseline 30-45 phút chưa ai đo | Không nói được metric nào thuộc trách nhiệm của AI, metric nào phụ thuộc vận hành — cứ gộp chung thành "success metric" | Sửa v1: tách metric chính (MAE < 5') với metric kết quả (chờ < 10-12'), và thêm câu "hệ thống phân phối lại thời gian chờ chứ không tạo thêm chỗ" |
| Workflow | Nhờ chuyển mô tả thành sơ đồ ASCII before/after | Nhanh hơn tự gõ, và ép ghi rõ boundary + fallback | AI coi bước 4 (xếp hàng 30-45') là chỗ duy nhất cần tấn công, tức là nhắm vào bước tốn thời gian nhất | Chỉ ra nguyên nhân gốc nằm ở bước 1 (khách chọn trò chơi khi chưa biết trò nào đông); tấn công bước 4 là tăng công suất, tốn hạ tầng và không phải việc của AI |
| Rule / Workflow / Agent | Nhờ phản biện lựa chọn mức | Ép trả lời đủ 5 câu hỏi chốt, nhất là câu "hạ cấp được không" | AI nghiêng sang Workflow khá nhanh mà chưa cân nhắc kỹ khả năng lớp Rule là đã đủ | Giữ Rule làm lớp nền bắt buộc thử trước, và trả lời câu 1 là "rất có thể rule đủ, nhóm chưa chứng minh được là không" thay vì khẳng định cần AI |
| Decision | Nhờ soát lại 6 câu hỏi Go / Not Yet / No-Go | Chỉ ra 4/6 ô là Not Yet và tất cả cùng một gốc | Kết luận thiên về No-Go vì thiếu dữ liệu, bỏ qua việc nhóm đã tìm được nguồn dữ liệu thay thế | Giữ Not Yet và viết rõ lý do: Queue-Times cho phép kiểm giả thuyết dự báo ngay, nên bài chưa chết mà chỉ là chưa đủ điều kiện triển khai |

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

> **BẢN NHÁP — phải viết lại bằng lời của bạn.** Worksheet quy định reflection không được để AI viết thay. Đoạn dưới bám đúng những gì đã ghi trong báo cáo nhóm, bạn sửa lại giọng văn và thêm chi tiết chỉ bạn nhớ.

**Reflection:**

```text
Thứ tôi học được rõ nhất là khi 15 candidate được xếp cạnh nhau. Cả ba bài tôi mang
tới đều rơi vào một cụm — gom thông tin rời rạc rồi viết lại cho người khác dùng —
và khi nhìn sang bài của Dũng và Cường tôi thấy họ cũng đang ở đúng cụm đó. Tức là
tôi tưởng mình scan được ba vấn đề khác nhau, thật ra tôi chỉ scan đi scan lại một
kiểu vấn đề duy nhất, vì đó là kiểu công việc tôi làm hằng ngày. Bài VinWonders của
Toàn là bài duy nhất không phải "phân loại thứ đã có" mà là "dự đoán thứ sắp xảy ra
rồi điều phối người", và chính vì lạ nên nó ép nhóm phải nghĩ nghiêm túc về sự khác
nhau giữa Rule, Workflow và Agent.

Tôi cũng đổi ý, nhưng đổi theo kiểu miễn cưỡng. Lúc chấm điểm, bài gom code review
của tôi được 34/35, cao nhất, và tôi phản đối việc chọn VinWonders vì đó là bài
nhóm không có dữ liệu, không có actor và không thử được trong lab — đi ngược đúng
nguyên tắc "evidence first" mà buổi lab đang dạy. Nhóm vẫn chọn VinWonders vì impact
và giá trị học tập. Tôi đồng ý đi tiếp nhưng xin chốt kèm hai ràng buộc: không được
kết luận Go nếu chưa đo baseline thật, và phải tìm cho ra một cách validate khả thi
với nguồn lực sinh viên. Đúng hai ràng buộc đó về sau quyết định kết luận cuối là
Not Yet, và cũng chính vì đi tìm cách validate mà tôi mò ra Queue-Times API — nguồn
wait time thật, miễn phí, của hơn 80 công viên. Nếu tôi chỉ phản đối rồi thôi thì
bài sẽ mắc kẹt ở "không có dữ liệu"; phản đối kèm ràng buộc thì nó biến thành việc
phải làm.

Nhóm có bị solution-first một nhịp, nhưng không phải kiểu "làm Agent cho ngầu". Bản
pitch đầu có sẵn mục tiêu tăng CSAT 25% và tăng 15% doanh thu F&B, nghe rất thuyết
phục nhưng không ai truy được nguồn, nên nhóm hạ chúng xuống thành giả thuyết thay
vì success metric. Về phía tôi, điều khó nhất khi viết Problem Statement là metric
chứ không phải boundary. Boundary ra khá nhanh vì có ranh giới đạo đức rõ: AI không
được quyết cho trò chơi chạy hay dừng, không nhận diện khuôn mặt. Nhưng v0 tôi viết
"giảm thời gian chờ xuống 10-12 phút" như thể đó là thành tích của AI, trong khi AI
chỉ ước lượng thời gian chờ — thông lượng thật của trò chơi không đổi. Đến v1 tôi
mới tách metric chính (sai số dự báo dưới 5 phút, thứ AI chịu trách nhiệm) khỏi
metric kết quả (thời gian chờ, phụ thuộc cả vận hành). Nếu làm lại, tôi sẽ challenge
mạnh hơn ngay từ lúc chấm điểm: hỏi thẳng "bài này đo bằng gì" trước khi hỏi "bài
này ảnh hưởng bao nhiêu người", vì impact lớn mà không đo được thì cuối cùng vẫn
phải viết Not Yet.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ 15 candidates về 1 bài (cluster → shortlist → score → chọn, có ghi bất đồng)
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

