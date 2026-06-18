---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** Chegg — pivot sang "AI Study Companion" (trợ giảng AI cá nhân hóa, kế thừa bài học từ Lab 1)
**Người làm:** Vũ Ngọc Vinh — 2A202600864
**Ngày:** 18/06/2026

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [ ] **1 nhóm người dùng chính**
- [ ] **1 hoàn cảnh / tình huống rõ**
- [ ] **1 job cốt lõi**
- [ ] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** Thiết kế lại Chegg theo hướng "AI Study Companion" — trợ giảng AI cá nhân hóa, có xác thực, thay cho mô hình kho đáp án tĩnh đã bị ChatGPT làm dư thừa (rút từ verdict Lab 1: "phải đổi rất mạnh sang mô hình trợ giảng cá nhân hóa có xác thực").
- **Lát cắt tôi chọn để phân tích hôm nay là:** Sinh viên đại học làm bài tập về nhà (homework) có deadline cận kề, cần hiểu cách giải đúng môn học của mình (không phải chỉ chép đáp án) để vẫn qua được bài kiểm tra/thi sau đó.
- **Vì sao tôi chọn lát cắt này:**  
  > Đây chính là lát cắt mà Chegg từng thắng và đang mất vào tay ChatGPT (Lab 1 — E2, E4). Nếu Chegg muốn sống, phải thắng lại đúng ở lát cắt này, nhưng bằng giá trị khác (cá nhân hóa + xác thực) mà ChatGPT thuần không có.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Sinh viên cần hoàn thành bài tập đúng hạn và hiểu đủ để qua bài kiểm tra, nhưng kho đáp án tĩnh kiểu cũ của Chegg không còn cạnh tranh được với AI generative miễn phí, tức thời.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Sinh viên đại học (undergrad), đặc biệt các môn STEM/toán/lập trình có bài tập tính toán định kỳ, đang quen dùng ChatGPT để giải bài nhưng vẫn lo bị phát hiện gian lận hoặc không hiểu thật.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Hỏi trực tiếp ChatGPT/Gemini đề bài của mình để có đáp án ngay, đôi khi kèm tìm kiếm Google hoặc hỏi bạn cùng lớp, gần như không còn vào Chegg để tra kho đáp án cũ.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Sinh viên đại học phải làm nhiều bài tập định kỳ (problem sets) trong khi vẫn cần hiểu kiến thức để thi cuối kỳ; áp lực thời gian cao vì học nhiều môn song song.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Vào các đợt deadline dồn (giữa kỳ, cuối kỳ), khi bài tập khó, môn không phải chuyên ngành chính, hoặc giảng viên dạy nhanh không kịp hiểu trên lớp.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > ChatGPT/Gemini miễn phí (trả lời tức thời, đúng đề bài riêng), nhóm chat bạn học, gia sư 1:1 (đắt, khó sắp lịch), và phần còn lại của Chegg (kho đáp án cũ, đang mất khách).

4. **Vì sao đây là thời điểm đáng giải?**  
   > AI generative đã giải quyết xong vấn đề "có đáp án nhanh", nhưng để lại một vấn đề mới chưa ai giải tốt: sinh viên dùng AI để chép nhưng không học được gì, và nhà trường ngày càng siết gian lận AI — tạo ra khoảng trống cho một sản phẩm "AI hỗ trợ học thật, có xác thực" thay vì "AI cho đáp án".

### Tóm tắt market context trong 3-4 dòng

> Sinh viên đại học hiện có quá nhiều cách lấy đáp án nhanh (ChatGPT, Gemini) nhưng gần như không có cách nào tốt để vừa nhanh vừa đảm bảo họ thực sự hiểu và không gian lận.  
> Thị trường "kho đáp án trả phí" mà Chegg từng thống trị đã sụp vì AI generative làm dư thừa giá trị đó (xem Lab 1).  
> Khoảng trống còn lại là lớp giá trị "học thật + có xác thực", thứ AI thuần (ChatGPT) không tự cung cấp và trường học ngày càng yêu cầu.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Sinh viên đại học năm 2-4 đang tự làm bài tập về nhà cho một môn học cụ thể (không phải nhà trường, không phải phụ huynh trả tiền hộ).
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Chính sinh viên là người mở app/tab, gõ đề bài, đọc lời giải và quyết định có dùng lại cách giải đó khi đi thi không. Nhà trường/giảng viên là người ảnh hưởng (đặt ra deadline, chính sách gian lận) nhưng không trực tiếp "thuê" sản phẩm để hoàn thành job này.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [ ] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [ ] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [ ] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng AI chatbot để giải bài tập về nhà nhanh trước deadline.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: "AI chatbot"

### Bản chốt

**Core JTBD cuối cùng:**  
> Hoàn thành bài tập về nhà đúng hạn với mức hiểu đủ để tự làm lại được câu tương tự trong bài kiểm tra, trong điều kiện thời gian rất hạn chế.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | tối hôm trước hạn nộp bài tập Toán/Lý mà tôi chưa hiểu cách giải | có lời giải từng bước theo đúng đề bài của tôi, kèm giải thích vì sao làm vậy | vừa nộp đúng hạn vừa hiểu đủ để làm câu tương tự khi thi | job thật không phải "có đáp án" mà là "có đáp án + hiểu được" |
| JS2 | giảng viên thông báo sẽ chấm gắt nếu phát hiện dùng AI chép nguyên văn | có một công cụ AI mà tôi dùng minh bạch, biết chắc không bị quy là gian lận | nộp bài tự tin, không lo bị accuse hoặc bị 0 điểm | "xác thực/an toàn học thuật" là một phần của job, không chỉ tốc độ |
| JS3 | làm bài tập một môn không phải chuyên ngành, kiến thức nền yếu | được hỏi lại đúng phần tôi đang hiểu sai thay vì nhận nguyên một bài giải dài | tiết kiệm thời gian ôn lại đúng lỗ hổng, không phải đọc lại cả chương | cá nhân hóa theo lỗ hổng kiến thức quan trọng hơn một lời giải chung |

### Tự kiểm nhanh

- [ ] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [ ] 3 story không trùng hệt nhau
- [ ] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Alt 1: ChatGPT/Gemini miễn phí | giải nhanh đúng đề bài riêng, tức thời | nhanh, miễn phí, hiểu ngôn ngữ tự nhiên, giải mọi môn | không xác thực học thuật, dễ sai mà không biết, không theo dõi lỗ hổng kiến thức, dễ bị quy gian lận | Thấp — chỉ cần mở tab khác |
| Alt 2: bạn cùng lớp / nhóm chat | hỏi nhanh, đối chiếu đáp án, học theo cách bạn giải thích | tin tưởng cao, ngữ cảnh đúng theo lớp/giảng viên | chậm, phụ thuộc bạn có rảnh và biết giải không, không phải lúc nào cũng đúng | Thấp |
| Alt 3: gia sư 1:1 / trung tâm | có người xác nhận hiểu đúng, kèm sát theo lỗ hổng cá nhân | chất lượng cao, cá nhân hóa thật, có người chịu trách nhiệm | đắt, khó sắp lịch gấp, không có sẵn lúc nửa đêm trước deadline | Cao (tốn tiền, tốn công tìm) |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Quay lại dùng trực tiếp ChatGPT/Gemini miễn phí (switching cost thấp nhất), chấp nhận đánh đổi rủi ro gian lận và không hiểu sâu, vì đó vẫn là lựa chọn nhanh nhất hiện có.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | xác định đề bài yêu cầu gì, mục tiêu là điểm hay là hiểu thật | tự đọc đề, đôi khi hỏi bạn | thường bỏ qua bước này, nhảy thẳng vào tìm đáp án | Low |
| Locate | tìm nơi có thể lấy lời giải hoặc gợi ý | ChatGPT, Google, bạn cùng lớp, Chegg cũ | quá nhiều lựa chọn nhưng không biết cái nào đáng tin / an toàn học thuật | Med |
| Prepare | gõ/chụp đề bài, mô tả ngữ cảnh môn học để AI hiểu đúng | copy-paste vào ChatGPT, chụp ảnh đề | AI đôi khi hiểu sai đề, ký hiệu toán/hình vẽ khó nhập | Med |
| Confirm | kiểm tra lời giải có đúng theo cách giảng viên dạy không | tự đối chiếu, không có gì xác nhận chắc chắn | N/A rõ ràng — đây là bước hầu như bị bỏ qua hoàn toàn | **High** |
| Execute | làm theo lời giải, viết lại bài nộp | chép lại nguyên văn hoặc diễn đạt lại sơ sài | dễ chép máy móc, không thực sự xử lý lại bằng tư duy của mình | **High** |
| Monitor | theo dõi mình có đang hiểu thật không trong lúc làm | gần như không có cơ chế nào theo dõi | hoàn toàn bị bỏ trống — không ai/không gì nhắc sinh viên dừng lại tự kiểm | High |
| Modify | điều chỉnh cách giải nếu không hợp với cách lớp đang học | hiếm khi làm, vì đã hết thời gian | N/A — thường bỏ qua vì áp lực deadline | Low |
| Conclude | nộp bài và kỳ vọng sẽ làm được câu tương tự khi thi | nộp xong là coi như xong | không có tổng kết, không có "đã học được gì", lỗ hổng tích lũy đến kỳ thi | Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Confirm — không có cách nào xác nhận lời giải AI đúng theo cách giảng viên dạy, và không có gì xác thực đây là "học thật" chứ không phải gian lận.
**Bước đau nhất #2:** Monitor — trong và sau khi làm bài, không có cơ chế nào cho sinh viên biết mình có thực sự hiểu hay chỉ đang chép.

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây đúng là hai bước mà ChatGPT thuần hoàn toàn bỏ trống — nó trả lời rất tốt ở Locate/Prepare/Execute, nhưng không chủ động xác nhận hiểu hay theo dõi tiến bộ.  
> Đây cũng chính là khoảng trống tạo ra rủi ro gian lận học thuật mà nhà trường đang siết — nếu Chegg giải được đúng hai bước này, đó là giá trị khác biệt thật, không phải tính năng "có AI cho vui".

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Confirm | sau khi đưa lời giải, AI tự đặt 1-2 câu hỏi ngược để sinh viên giải thích lại bước quan trọng nhất, rồi mới "chốt" lời giải kèm chứng nhận "đã hiểu" | AI làm việc này rẻ và nhanh hơn gia sư người, và có thể làm mọi lúc kể cả nửa đêm | nếu câu hỏi ngược quá dễ/máy móc, sinh viên học cách "qua mặt" mà vẫn không hiểu thật |
| Monitor | AI âm thầm theo dõi loại lỗi sai lặp lại của sinh viên qua nhiều bài, gợi ý ôn lại đúng phần yếu trước kỳ thi | AI giỏi phát hiện pattern qua dữ liệu lớn hơn con người tự nhận ra | rủi ro privacy nếu lưu dữ liệu học tập cá nhân không minh bạch với user |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Bước Confirm — AI không chỉ đưa lời giải mà chủ động kiểm tra ngược (Socratic check) trước khi coi bài tập là "đã hoàn thành", tạo ra lớp xác thực "học thật" mà ChatGPT thuần không làm.

**Vì sao không phải ở bước khác:**  
> Locate/Prepare/Execute đã bị ChatGPT giải quá tốt và miễn phí rồi — cạnh tranh ở đó là thua chắc (giống bài học Lab 1: content/inventory moat không còn ăn). Confirm và Monitor là hai bước AI thuần đang bỏ trống, và cũng là đúng chỗ nhà trường/giảng viên quan tâm nhất (gian lận, hiểu thật) — nên đây là chỗ một sản phẩm mới có thể tạo giá trị khác biệt thật.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp sinh viên đại học hoàn thành job "hiểu đủ để tự làm lại bài tương tự" tốt hơn ở bước Confirm và Monitor,
> bằng cách thêm một lớp kiểm tra ngược (Socratic check) và theo dõi lỗ hổng kiến thức cá nhân quanh lời giải AI,
> thì họ sẽ chuyển từ việc dùng ChatGPT thuần (chỉ lấy đáp án, không xác thực) sang dùng AI Study Companion của Chegg,
> vì sản phẩm này giải quyết luôn nỗi lo "không hiểu thật" và "bị nghi gian lận" mà ChatGPT không xử lý.

### Tín hiệu sớm nếu hypothesis này đúng

1. Sinh viên dùng lại sản phẩm nhiều lần trong một học kỳ (retention theo tuần) thay vì chỉ thử một lần rồi quay lại ChatGPT.
2. Tỷ lệ sinh viên hoàn thành bước "kiểm tra ngược" (Confirm) trước khi đóng app cao, thay vì bỏ qua/skip ngay khi có đáp án.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Job executor đúng là sinh viên tự trả/tự dùng, không phải nhà trường mua hộ | Nếu thực ra nhà trường là buyer chính, sản phẩm phải thiết kế khác (B2B, tích hợp LMS) | Chỉ có suy luận từ mô hình Chegg cũ (B2C subscription), chưa có khảo sát thật | Phỏng vấn 5-10 sinh viên: ai trả tiền, ai quyết định dùng công cụ nào |
| A2: Pain ở Confirm/Monitor đủ đau để sinh viên đổi thói quen | Sinh viên có thể không quan tâm "hiểu thật", chỉ cần qua môn, nên bỏ qua bước xác thực | Chỉ có suy luận logic, chưa có dữ liệu hành vi thật | Quan sát/khảo sát: hỏi sinh viên có từng lo "dùng ChatGPT mà không hiểu gì" không, mức độ thường xuyên |
| A3: User sẽ chấp nhận tốn thêm vài giây/phút cho bước kiểm tra ngược trước deadline | Dưới áp lực deadline, user có xu hướng bỏ qua mọi bước thêm không bắt buộc | Chưa có | A/B test prototype: có bước Confirm bắt buộc vs không, đo completion rate |
| A4: AI thực sự tạo giá trị đáng tin ở bước Confirm (đặt câu hỏi ngược đúng trọng tâm) | Nếu câu hỏi AI đặt ra hời hợt/sai trọng tâm, sinh viên sẽ thấy đây là "thêm bước vô nghĩa" và bỏ qua | Chưa có, cần thử với LLM thật trên vài đề bài mẫu | Thử nghiệm prototype với 10-20 đề bài thật, cho giảng viên đánh giá chất lượng câu hỏi ngược |
| A5: Sinh viên đủ tin "chứng nhận đã hiểu" từ AI để đưa vào workflow ôn thi thật | Nếu sinh viên không tin AI đánh giá đúng mức hiểu của mình, tính năng Monitor sẽ bị bỏ qua | Chưa có | Khảo sát mức độ tin tưởng vào đánh giá của AI so với giảng viên/gia sư người |

### Assumption nguy hiểm nhất nếu tôi đang sai

> A2 — nếu sinh viên thực ra không quan tâm "hiểu thật" mà chỉ cần qua môn nhanh nhất có thể, thì toàn bộ lớp giá trị Confirm/Monitor mà chúng tôi đặt cược vào sẽ không tạo ra động lực chuyển đổi nào, và sản phẩm quay lại đúng vấn đề cũ của Chegg: không khác biệt đủ so với ChatGPT miễn phí.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| Sinh viên dưới deadline áp lực rất ít khi tự nguyện làm thêm một bước "kiểm tra ngược" — nguy cơ bị bỏ qua ngay | Assumption A3, AI leverage point ở Confirm | Sửa: làm bước Confirm nhẹ hơn (1 câu hỏi nhanh, không phải một bài kiểm tra), và thử nghiệm trước khi khẳng định feature này sống được |
| Job executor có thể không chỉ là sinh viên — một số trường đã mua license Chegg cho cả lớp, nên nhà trường có thể là buyer thật | Job executor, market context | Giữ sinh viên là job executor (người trực tiếp dùng), nhưng ghi rõ thêm nhà trường có thể là buyer/influencer riêng cần khảo sát thêm (A1) |
| Core JTBD vẫn còn hơi rộng, "hiểu đủ" là một khái niệm mơ hồ, khó đo | Core JTBD | Giữ nguyên ý chính nhưng note thêm: cần định nghĩa "hiểu đủ" bằng tiêu chí cụ thể hơn khi build (ví dụ: giải lại được câu tương tự không cần xem lại lời giải cũ) |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [x] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Giữ `job executor` và `core JTBD` vì phản biện không bác bỏ được job thật (vẫn là sinh viên cần hoàn thành đúng hạn và hiểu đủ), chỉ cảnh báo thêm rủi ro thực thi.  
> Sửa `AI leverage point`: làm nhẹ bước Confirm (1 câu hỏi nhanh thay vì một quy trình kiểm tra dài) để giảm rủi ro bị bỏ qua dưới áp lực deadline, đúng góp ý của bàn.

### Version cuối cùng tôi nộp

**Job executor:**  
> Sinh viên đại học năm 2-4 đang tự làm bài tập về nhà cho một môn học cụ thể, tự quyết định dùng công cụ nào để hoàn thành, không phải nhà trường hay phụ huynh.

**Core JTBD:**  
> Hoàn thành bài tập về nhà đúng hạn với mức hiểu đủ để tự làm lại được câu tương tự trong bài kiểm tra, trong điều kiện thời gian rất hạn chế.

**2 bước đau nhất trong workflow:**  
> Confirm (không có cách xác nhận lời giải đúng và "học thật") và Monitor (không có cơ chế nào theo dõi sinh viên có thực sự hiểu hay chỉ chép).

**AI leverage point chính:**  
> Ở bước Confirm, AI đặt đúng 1 câu hỏi ngược ngắn, trọng tâm nhất của lời giải, để xác nhận sinh viên hiểu trước khi "chốt" bài — đủ nhẹ để không bị bỏ qua dưới áp lực deadline, nhưng đủ để tạo lớp xác thực mà ChatGPT thuần không có.

**Product hypothesis:**  
> Nếu chúng ta giúp sinh viên đại học hoàn thành job "hiểu đủ để tự làm lại bài tương tự" tốt hơn ở bước Confirm và Monitor, bằng một câu hỏi kiểm tra ngược ngắn gọn quanh lời giải AI, thì họ sẽ chuyển từ ChatGPT thuần sang AI Study Companion của Chegg, vì sản phẩm này giải quyết được nỗi lo "không hiểu thật" và "bị nghi gian lận" mà ChatGPT không xử lý.

**Assumption cần validate đầu tiên:**  
> A2 — pain ở Confirm/Monitor có đủ đau và đủ thường xuyên để sinh viên thực sự muốn đổi thói quen, hay họ chỉ cần qua môn nhanh nhất có thể và sẽ bỏ qua mọi bước xác thực thêm.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
