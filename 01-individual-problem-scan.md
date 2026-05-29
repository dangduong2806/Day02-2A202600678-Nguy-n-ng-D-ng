# 01 — Individual Problem Scan

## Scan rộng

 scan 10 problems, vượt mức tối thiểu 5.

| # | Lăng kính | Problem quan sát được | Ai đang đau? | Dấu hiệu thật |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi thứ 2 review lại kết quả đạt được của tuần trước trên notion | project leader, team member | Mất khoảng 60p/buổi |
| 2 | Lặp lại | Taking note lại các ý đã trình bày ở tuần trước, đánh giá kết quả làm việc trong tuần trước của từng thành viên  | project leader | Lặp lại mỗi tuần |
| 3 | Lặp lại | Mỗi người trình bày ý tưởng mới (nếu có) và ghi chép lại vào notion | project leader, team member | 50p/buổi |
| 4 | Tốn thời gian | Review rất nhiều papers (4-5) trước khi trình bày | project leader, team member | 120 phút/buổi|
| 5 | Tốn thời gian | Viết meeting notes sau khi trình bày xong | project leader, team member | 40 phút/buổi |
| 6 | Tốn thời gian | Dùng draw.io để vẽ luồng hoạt động cho ý tưởng nghĩ ra hoặc tìm được | project leader, team member | 40 phút/buổi |
| 5 | AI có thể tốt hơn | Notion không tóm gọn lại những nội dung quan trọng của cả 1 bài meeting notes hoặc nội dung, ý tưởng đã trao đổi| project leader, team member | Quan trọng để giao các task tiếp theo cho từng người những nội dung dài gây mất thời gian đọc và hiệu suất đọc hiểu |
| 6 | AI có thể tốt hơn | Review các paper trên google scholar rất lâu và mỏi mắt | Cả team | khoảng 60 phút/lần review |
| 7 | AI có thể tốt hơn | Vẽ UML trên draw.io cần thao tác rất nhiều và lâu, vẽ xong cũng thấy chưa đẹp mắt | Cả team | khoảng 60 phút/lần vẽ |
| 8 | Pain từ người khác | Developer phải hỏi lại ý tưởng triển khai từ project leader vì ý tưởng chức năng khá trừu tượng | developer member | Hỏi lại 2-3 lần/3 ngày (trong giai đoạn cold start) |
| 8 | Pain từ người khác | project leader hỏi trình bày kết quả nhưng notion, slide chưa hoàn thành | project leader | Hay bị trễ deadline vào thứ 2 |
| 9 | Pain từ người khác | Mọi người hỏi kĩ hơn về kết quả đạt được/ quá trình survey nhưng cá nhân không trả lời được, mất thời gian research lại | project leader, team member | Hay bị vào thứ 2 khi từng member review lại kết quả đạt được trong tuần trước |
| 10 | Lặp lại | Viết báo cáo update kết quả 3 tuần/1 lần cho project manager | project leader | 30-60p/lần |

## Top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Notion/meeting notes quá dài, khó tóm tắt ý chính để giao task tiếp theo | Actor rõ: project leader, team member. Workflow vẽ được: họp → ghi note → đọc lại → tóm ý → giao task. Bottleneck cụ thể: đọc hiểu nội dung dài và rút ra action item. | Cần đo rõ hiện tại mất bao nhiêu phút để đọc lại notes và giao task. |
| 2 | Review nhiều paper trước khi trình bày mất nhiều thời gian | Actor rõ: project leader/team member. Bottleneck rõ: đọc 4-5 papers, lọc ý chính, so sánh relevance. | ần giới hạn scope: chỉ hỗ trợ lọc/tóm tắt paper, không thay người đọc hoàn toàn. |
| 3 | Developer phải hỏi lại project leader vì ý tưởng/chức năng còn trừu tượng | Đây là pain từ người khác, có evidence tốt: hỏi lại 2-3 lần/3 ngày trong giai đoạn cold start. Actor rõ: developer member và project leader. Bottleneck là chuyển ý tưởng mơ hồ thành yêu cầu triển khai rõ ràng | Cần làm rõ input ban đầu là gì: Notion note, slide, verbal idea, hay mô tả feature. |

## Problem Card #1 — Meeting Notes / Notion Summary

**Problem 1 câu:**  
Sau mỗi buổi họp, project leader và team member mất nhiều thời gian đọc lại meeting notes dài trên Notion để rút ra ý chính, action items và giao task tiếp theo.

**Actor:**  
Project leader, team member.

**Thời điểm / bối cảnh:**  
Sau buổi họp hằng tuần hoặc sau khi team trình bày kết quả, ý tưởng mới, nội dung research.

**Current workflow:**

Current workflow 3-7 bước:
1. Team họp và trình bày kết quả/ý tưởng.
2. Một người ghi meeting notes vào Notion.
3. Project leader đọc lại toàn bộ notes.
4. Project leader tự lọc ý chính, vấn đề còn mở, quyết định đã chốt.
5. Project leader chuyển nội dung thành task cho từng thành viên.
6. Team member đọc lại hoặc hỏi lại nếu chưa rõ.


**Bottleneck:**  
Bước 3-5: đọc lại notes dài, lọc ý quan trọng và biến thành action items. Mất khoảng 40-60 phút/buổi, dễ bỏ sót ý hoặc giao task chưa rõ.

**Impact:**  
Nếu notes không được tóm tắt tốt, team mất thời gian đọc lại, project leader giao task chậm, member dễ hỏi lại hoặc hiểu sai việc cần làm.

**Success metric:**  
Giảm thời gian đọc/tổng hợp meeting notes từ khoảng 40-60 phút xuống dưới 15-20 phút; giảm số lần member phải hỏi lại về task sau họp.

**Non-AI alternative:**  
Dùng template meeting notes cố định gồm: decision, action item, owner, deadline, blocker. Cách này giúp chuẩn hóa nhưng vẫn cần người đọc và tổng hợp thủ công.

**AI hypothesis:**  
AI hỗ trợ tóm tắt meeting notes, trích decision/action items, gợi ý owner/deadline nếu có trong nội dung. Project leader vẫn review và chốt trước khi giao task.


**Quick gut:**  
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

## Problem Card #2 — Review papers
**Problem 1 câu:**  
Team mất nhiều thời gian review 4-5 papers trước khi trình bày vì phải đọc, lọc ý chính, so sánh nội dung và chọn phần liên quan đến project.


**Actor:**  
Project leader, team member.

**Thời điểm / bối cảnh:**  
Team mất nhiều thời gian review 4-5 papers trước khi trình bày vì phải đọc, lọc ý chính, so sánh nội dung và chọn phần liên quan đến project.


**Current workflow:**

Current workflow 3-7 bước:
1. Team member tìm papers trên Google Scholar hoặc nguồn khác.
2. Mở từng paper và đọc abstract/introduction.
3. Đọc sâu phần method, result hoặc contribution.
4. Ghi lại ý chính từ từng paper.
5. So sánh paper nào liên quan nhất đến project.
6. Chuẩn bị nội dung trình bày cho team.


**Bottleneck:**  
Bước 2-5: đọc nhiều paper và lọc ý quan trọng. Bạn ghi nhận mất khoảng 60-120 phút/lần review, gây mỏi mắt và dễ mất tập trung.


**Impact:**  
Research chậm làm team mất nhiều thời gian trước khi ra quyết định. Nếu đọc không kỹ hoặc lọc sai, team có thể chọn hướng không phù hợp.


**Success metric:**  
Giảm thời gian review ban đầu từ 60-120 phút xuống còn 30-45 phút; mỗi paper có summary ngắn gồm problem, method, result, điểm liên quan đến project.


**Non-AI alternative:**  
Dùng checklist review paper cố định hoặc chia paper cho từng member đọc. Cách này giúp phân công rõ hơn nhưng vẫn tốn nhiều công đọc và tổng hợp.


**AI hypothesis:**  
AI hỗ trợ tóm tắt paper, trích contribution/method/result, so sánh nhiều paper theo tiêu chí có sẵn. Người đọc vẫn kiểm tra lại nội dung quan trọng trong paper gốc.



**Quick gut:**  
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

## Problem Card #3 — Ý Tưởng Chức Năng Còn Trừu Tượng
**Problem 1 câu:**  
Developer thường phải hỏi lại project leader vì ý tưởng hoặc mô tả chức năng còn trừu tượng, chưa đủ rõ để triển khai.


**Actor:**  
Developer member, project leader.

**Thời điểm / bối cảnh:**  
Giai đoạn cold start của feature mới, sau khi project leader trình bày ý tưởng hoặc giao task triển khai.


**Current workflow:**

Current workflow 3-7 bước:
1. Project leader nêu ý tưởng chức năng ở meeting hoặc Notion.
2. Developer đọc lại mô tả/notes.
3. Developer tự suy luận yêu cầu cần làm.
4. Developer phát hiện điểm chưa rõ về input, output, flow hoặc edge case.
5. Developer hỏi lại project leader.
6. Project leader giải thích thêm hoặc chỉnh lại mô tả.
7. Developer mới bắt đầu triển khai rõ hơn.


**Bottleneck:**  
Bước 3-6: chuyển ý tưởng trừu tượng thành yêu cầu triển khai rõ ràng. Có dấu hiệu hỏi lại 2-3 lần trong 3 ngày ở giai đoạn cold start.


**Impact:**  
Developer bị chậm khi bắt đầu task, project leader bị gián đoạn để giải thích lại, feature có nguy cơ bị hiểu sai hoặc phải sửa lại.


**Success metric:**  
Giảm số lần hỏi lại từ 2-3 lần/3 ngày xuống còn 0-1 lần; giảm thời gian clarify trước khi dev bắt đầu triển khai; tăng tỷ lệ task có đủ input/output/acceptance criteria.



**Non-AI alternative:**  
Dùng template mô tả feature gồm: mục tiêu, user, input, output, main flow, edge cases, acceptance criteria. Cách này tốt nhưng project leader vẫn phải tự viết đủ chi tiết.

**AI hypothesis:**  
AI hỗ trợ biến ý tưởng/meeting notes thành draft requirement rõ hơn: user story, acceptance criteria, flow cơ bản, câu hỏi còn thiếu. Project leader review trước khi giao cho developer.




**Quick gut:**  
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết

## Problem Card #1 — Meeting Notes / Notion Summary
### Draft current workflow

CURRENT STATE — 40-60 phút

[1 Team họp + trình bày: 30-60']
→ [2 Ghi meeting notes vào Notion: trong lúc họp]
→ [3 Project leader đọc lại toàn bộ notes: 15']
→ [4 Lọc ý chính, decision, blocker: 10-15']  <-- bottleneck
→ [5 Viết action items cho từng member: 10-20']  <-- bottleneck
→ [6 Giao task / nhắc lại trong Notion hoặc chat: 5']
→ [7 Member đọc lại hoặc hỏi lại nếu chưa rõ: 5-15']

Pain chính:
Notes dài, ý quan trọng bị lẫn với phần thảo luận. Project leader phải tự đọc lại và chuyển thành task.

### Draft future workflow
FUTURE STATE — 15-25 phút

[1 Team họp + trình bày: 30-60']
→ [2 Ghi meeting notes vào Notion theo template: trong lúc họp]
→ [3 AI tóm tắt notes thành decision, action items, blocker: 1-2']
→ [4 AI gợi ý task, owner, deadline nếu có dữ liệu: 1-2']
→ [5 Project leader review + chỉnh lại: 10-15']  <-- human boundary
→ [6 Giao task cho member: 3-5']
→ [7 Member phản hồi nếu task vẫn chưa rõ: 3-5']

Fallback:
AI tóm tắt sai hoặc thiếu context → project leader đọc lại notes gốc và tự chỉnh action items.

## Problem Card #2 — Review Papers
### Draft current workflow
CURRENT STATE — 60-120 phút

[1 Tìm paper trên Google Scholar / nguồn khác: 10-20']
→ [2 Mở từng paper, đọc abstract + introduction: 20-30']
→ [3 Đọc method/result của paper liên quan: 30-45']  <-- bottleneck
→ [4 Ghi chú ý chính từng paper: 15-20']
→ [5 So sánh paper nào phù hợp với project: 15-20']  <-- bottleneck
→ [6 Chuẩn bị nội dung trình bày cho team: 10-20']

Pain chính:
Phải đọc nhiều paper liên tiếp, dễ mỏi mắt, khó nhớ paper nào đóng góp gì và liên quan đến project ở điểm nào.

### Draft future workflow
FUTURE STATE — 30-45 phút

[1 Tìm paper theo keyword hoặc topic: 10-15']
→ [2 AI tóm tắt từng paper theo format cố định: 3-5']
→ [3 AI tạo bảng so sánh problem, method, result, relevance: 3-5']
→ [4 Team member đọc lại paper gốc ở phần quan trọng: 15-20']  <-- human boundary
→ [5 Chọn paper phù hợp và ghi nhận insight chính: 5-10']
→ [6 Chuẩn bị nội dung trình bày: 5-10']

Fallback:
AI summary không đáng tin hoặc paper quá chuyên sâu → member đọc trực tiếp abstract, method, result trong paper gốc.


## Problem Card #3 — Ý Tưởng Chức Năng Còn Trừu Tượng
### Draft current workflow
CURRENT STATE — 2-3 lần hỏi lại trong 3 ngày

[1 Project leader nêu ý tưởng feature trong meeting / Notion: 10-20']
→ [2 Developer đọc lại mô tả hoặc notes: 5-10']
→ [3 Developer tự suy luận input, output, flow: 15-30']  <-- bottleneck
→ [4 Developer phát hiện điểm chưa rõ: 5']
→ [5 Developer hỏi lại project leader: 5-15']
→ [6 Project leader giải thích thêm hoặc sửa mô tả: 10-20']  <-- bottleneck
→ [7 Developer bắt đầu triển khai: sau khi đủ rõ]

Pain chính:
Ý tưởng ban đầu còn mơ hồ, thiếu acceptance criteria, edge cases hoặc flow cụ thể nên developer phải hỏi lại nhiều lần.

### Draft future workflow
FUTURE STATE — 0-1 lần hỏi lại trước khi triển khai

[1 Project leader nêu ý tưởng feature trong meeting / Notion: 10-20']
→ [2 AI chuyển ý tưởng thành draft requirement: 2-3']
→ [3 AI gợi ý user story, input/output, main flow, edge cases: 2-3']
→ [4 AI liệt kê câu hỏi còn thiếu để project leader bổ sung: 1-2']
→ [5 Project leader review + chỉnh requirement: 10-15']  <-- human boundary
→ [6 Developer đọc requirement rõ ràng hơn: 5-10']
→ [7 Developer hỏi lại nếu còn thiếu: 0-1 lần]
→ [8 Developer bắt đầu triển khai]

Fallback:
AI hiểu sai ý tưởng hoặc tạo requirement quá chung → project leader dùng template thủ công để viết lại mục tiêu, flow và acceptance criteria.

