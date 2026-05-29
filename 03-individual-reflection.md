# Phase 7 — Individual Reflection — Dương

## 1. Top 3 Problem Cards cá nhân

- Tóm tắt meeting notes dài thành action items.
- Review 4-5 papers trước khi trình bày cho team.
- Biến ý tưởng chức năng trừu tượng thành requirement rõ hơn.

---

## 2. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng |
|---|---|---|
| Scan cá nhân | Đưa ra các problem trong bối cảnh building project: meeting notes, review paper và requirement ambiguity. | Nhóm có thêm góc nhìn từ workflow thực tế của Dương. |
| Pitch Problem Card | Pitch tốt các workflow có actor rõ như project leader, team member, developer. | Các problem được đưa vào danh sách 15 candidates của nhóm. |
| Challenge bài của bạn khác | Có thể challenge nhóm về ranh giới giữa summarization thông thường và workflow thật sự có impact. | Giúp nhóm không chọn bài chỉ vì nghe hấp dẫn, mà phải xét actor, bottleneck, metric và scope. |
| Gom trùng / cluster | Đóng góp vào cluster Notes/Report, Paper Review và Requirement/Product Context. | Giúp nhóm nhìn ra pattern chung giữa các problem thay vì xét từng bài rời rạc. |
| Chọn candidate problem | Một số ý của Dương liên quan mạnh tới shortlist, đặc biệt Paper Review và Requirement Clarification. | Nhóm hội tụ về candidate Legal QA Debugging. |
| Validation / research | Cùng nhóm xem pain có thật không, đã có tool tương tự chưa, và bài toán có nên dùng AI không. | Nhóm xác định khoảng trống: không làm Legal QA cho end-user, mà làm debug/verification workflow cho AI Engineer. |
| Workflow nhóm | Góp ý current workflow và future workflow theo hướng before/after. | Nhóm có workflow rõ: current ~30 phút/query, future kỳ vọng dưới 10 phút/query. |
| Problem Statement | Cùng nhóm kiểm tra actor, workflow, bottleneck, impact, success metric và boundary. | Problem Statement v0/v1 rõ hơn, không bị solution-first. |
| Rule / Workflow / Agent | Cùng nhóm so sánh Rule, Workflow và Agent. | Nhóm chọn mức **Workflow**, không chọn Rule-only hoặc full Agent. |
| Decision | Tham gia quyết định Go / Not Yet / No-Go. | Nhóm quyết định **Go với pilot nhỏ 3-5 query lỗi**. |

---

## 3. Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý cách diễn đạt problem và kiểm tra workflow có đủ actor/input/output không. | Giúp cấu trúc hóa ý tưởng nhanh. | AI dễ viết chung chung nếu không có context thật. | Bổ sung ví dụ, thời gian ước lượng và pain thật của mình. |
| Problem Card | Gợi ý format problem card và câu chữ ngắn gọn. | Giúp card rõ hơn: actor, bottleneck, metric. | AI có thể phóng đại impact hoặc viết như solution. | Giữ lại phần mình thật sự trải nghiệm, bỏ phần quá chung. |
| Workflow | Gợi ý before/after workflow. | Giúp chia bước rõ hơn. | AI có thể tự thêm bước không có trong thực tế. | Chỉnh lại theo workflow nhóm thực sự thảo luận. |
| Research | Gợi ý tool/pattern tương tự như RAG evaluation, legal AI, citation-backed answer. | Giúp nhóm thấy thị trường đã có giải pháp liên quan. | AI có thể đưa claim nếu không verify link. | Chỉ giữ nguồn có link và claim kiểm tra được. |
| Problem Statement | Kiểm tra 6 field: actor, workflow, bottleneck, impact, metric, boundary. | Giúp phát hiện field còn mơ hồ. | AI có xu hướng viết lại thay vì phản biện. | Tự giữ decision của nhóm và chỉ dùng AI như checklist. |
| Rule / Workflow / Agent | Gợi ý so sánh 3 mức. | Giúp nhóm thấy Workflow phù hợp hơn Agent. | AI có thể thiên về Agent vì nghe “AI hơn”. | Nhóm tự đặt boundary pháp lý và chọn Workflow. |
| Decision | Gợi ý tiêu chí Go/Not Yet/No-Go. | Giúp quyết định có lý do rõ. | AI không biết data thật của nhóm đã đủ chưa. | Ghi rõ “Go với pilot nhỏ”, nhưng baseline/data vẫn cần đo thật. |

---

## 4. Reflection câu hỏi mở

### Tôi học được gì khi nghe top 3 problems của các bạn khác?

```text
- Tôi nhận ra nhiều problem nhìn khác nhau nhưng cùng pattern: thông tin rải rác, phải đọc/lọc/tổng hợp thủ công.
- Tôi học được rằng problem tốt không chỉ là pain lớn, mà phải có actor rõ, bottleneck cụ thể và metric đo được.
- Tôi thấy các bài của bạn khác giúp nhóm so sánh được domain rộng như paper review/product workflow với domain hẹp hơn như Legal QA debugging.
```

### Nhóm có lúc nào bị solution-first không?

```text
- Có, nhóm đã nghĩ ngay đến AI Agent hoặc RAG tool trước khi chốt workflow.
- Sau đó nhóm kéo lại bằng cách hỏi: actor là ai, bottleneck ở bước nào, metric là gì, nếu AI sai thì ai kiểm tra.
```

### Tôi có thay đổi ý kiến sau khi bị challenge không?

```text
- Ban đầu tôi nghĩ candidate của mình có thể được chọn vì pain rõ.
- Sau khi nghe challenge, tôi hiểu rằng bài được chọn cần không chỉ hay mà còn phải pilot được, có boundary rõ và so sánh Rule/Workflow/Agent tốt.
```

### Tôi đóng góp gì thật sự vào artifact cuối?

```text
- Đóng góp cụ thể của mình: problem card, cluster, câu hỏi challenge, workflow, metric, boundary hoặc decision.
```

### Điều khó nhất khi viết Problem Statement là gì?

```text
- Khó nhất là không viết thành solution.
- Khó tách rõ bottleneck khỏi impact.
- Khó đưa metric vừa đo được vừa không quá tham vọng.
- Khó đặt boundary để AI không làm quá vai trò.
```

### Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

```text
- Tôi sẽ hỏi kỹ hơn về dữ liệu pilot: có query lỗi thật không, có chunks/luật gốc không.
- Tôi sẽ yêu cầu đo baseline thật thay vì chỉ ước lượng.
- Tôi sẽ challenge mạnh hơn câu hỏi: Rule có đủ chưa, vì sao cần AI?
```

---

## 5. Reflection cá nhân — bản nháp để tự sửa

```text
Trong quá trình làm nhóm, tôi tham gia từ bước đưa ra top 3 problem cá nhân, pitch problem card, nghe và challenge ý tưởng của các bạn khác, đến lúc nhóm gom cluster và chọn candidate cuối cùng. Qua quá trình này, tôi nhận ra một problem tốt không chỉ là một vấn đề nghe “hay” hoặc có vẻ cần AI, mà phải có actor cụ thể, workflow hiện tại rõ, bottleneck nằm ở một bước cụ thể, impact đo được và boundary đủ an toàn.

Tôi học được nhiều từ việc nghe top 3 problems của các bạn khác. Nhiều bài có pattern giống nhau: người dùng phải đọc nhiều thông tin rải rác, tự lọc ý chính, rồi biến thành quyết định hoặc action tiếp theo. Tuy nhiên, không phải bài nào cũng nên giải bằng AI. Một số bài có thể xử lý bằng rule, template hoặc checklist. Vì vậy, nhóm cần so sánh kỹ Rule / Workflow / Agent trước khi quyết định.

Trong artifact cuối, tôi đóng góp bằng cách đưa ra problem cá nhân, tham gia gom trùng, thảo luận shortlist, góp ý workflow trước/sau và đồng thuận với hướng chọn Workflow cho bài Legal QA Debugging. Tôi cũng hiểu rằng trong domain pháp luật, AI không nên tự quyết định đúng/sai cuối cùng. Vai trò hợp lý hơn là hỗ trợ tách claim, map evidence, tóm tắt nguồn và gợi ý lỗi; còn người thật vẫn phải review.

Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần validation. Cụ thể, tôi sẽ yêu cầu có query lỗi thật, retrieved chunks thật và luật gốc thật để đo baseline thay vì chỉ dùng estimate. Tôi cũng sẽ hỏi kỹ hơn liệu rule/template có giải được một phần lớn workflow không trước khi đưa AI vào.
```

---

## 6. Tự kiểm cuối bài

- [ ] [12đ cá nhân] Cá nhân có 5+ problems và top 3 Problem Cards.
- [ ] [12đ cá nhân] Tôi đã pitch rõ và challenge nhóm đúng trọng tâm.
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài.
- [ ] [15đ nhóm] Nhóm có workflow trước/sau.
- [ ] [20đ nhóm] Nhóm có Problem Statement v0/v1 với metric và boundary rõ.
- [ ] [15đ nhóm] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [ ] [10đ nhóm] Nhóm có Go / Not Yet / No-Go và lý do rõ.
- [ ] [10đ cá nhân] Reflection cá nhân có nói rõ vai trò trong nhóm, cách dùng AI, điều học được và nếu làm lại sẽ đổi gì.
- [ ] [6đ cá nhân] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp với AI.

---

## 7. Một câu tự giải thích mạch problem → workflow → metric → boundary → AI fit

```text
Problem của nhóm là AI Engineer debug Legal QA quá chậm vì phải đọc và đối chiếu nhiều điều luật; workflow hiện tại mất khoảng 20-30 phút/query; metric kỳ vọng là giảm xuống dưới 10 phút/query; boundary là AI chỉ hỗ trợ phân tích còn người thật quyết định cuối; vì vậy mức phù hợp là Workflow có AI hỗ trợ, không phải Rule-only hay full Agent.
```
