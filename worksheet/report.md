# Lab Assignment 1 — Phân tích sản phẩm bị ảnh hưởng nặng bởi AI

**Sản phẩm được chọn: Chegg** (dịch vụ hỗ trợ học tập / giải bài tập trực tuyến, Mỹ)
**"Hung thủ" gây disrupt: ChatGPT (OpenAI)** ra mắt 30/11/2022, sau đó là các tính năng AI miễn phí tích hợp sẵn của Google (SGE/AI Overviews), Microsoft Copilot.

---

## 1. Thu thập thông tin

### 1.1. Case trước AI

| Mục | Nội dung |
|---|---|
| Sản phẩm là gì | Chegg là nền tảng subscription (~$14.95–19.95/tháng) cung cấp: thuê/mua sách giáo khoa, **Chegg Study** (kho giải bài tập có sẵn + hỏi chuyên gia trả lời trong vài giờ), Chegg Writing, Chegg Tutors. |
| User là ai | Sinh viên đại học (chủ yếu Mỹ), đặc biệt sinh viên năm 1–2 học các môn đại cương (Calculus, Chemistry, Physics, Statistics, Accounting...). |
| Họ trả tiền cho cái gì | Trả tiền để **có ngay đáp án/lời giải chi tiết** cho bài tập về nhà, tiết kiệm thời gian tự giải hoặc đi hỏi gia sư/giáo viên. Bản chất là mua "tốc độ có đáp án đúng + lời giải từng bước" với chi phí rẻ hơn gia sư người thật. |
| Sản phẩm thắng nhờ gì | - Kho dữ liệu giải bài tập khổng lồ đã tích lũy nhiều năm (crowdsourced + thuê chuyên gia).<br>- Network effect: càng nhiều câu hỏi/đáp án thì khả năng "có sẵn đáp án đúng bài" càng cao.<br>- Rào cản gia nhập: tốn nhiều năm và nhân lực để build kho dữ liệu tương tự.<br>- Định giá rẻ hơn nhiều so với thuê gia sư 1:1. |

### 1.2. AI shock — mốc thời gian disrupt

- **11/2022**: ChatGPT ra mắt, miễn phí, giải được hầu hết bài tập đại cương (toán, lý, hóa, lập trình, viết luận) **ngay lập tức, không cần chờ "chuyên gia trả lời sau vài giờ"** như Chegg.
- **2023**: Chegg tự phát triển "CheggMate" (tích hợp GPT-4 qua OpenAI) để phản ứng, nhưng ra mắt chậm và không đủ sức cạnh tranh với việc sinh viên dùng trực tiếp ChatGPT miễn phí.
- **5/2023**: CEO Chegg Dan Rosensweig công khai thừa nhận trên báo cáo earnings rằng ChatGPT đang ảnh hưởng đến tăng trưởng người dùng mới — **cổ phiếu Chegg sụt ~48% trong 1 ngày**.
- **2023–2024**: Google tích hợp AI Overviews/SGE vào kết quả tìm kiếm, sinh viên không cần vào Chegg để tìm đáp án mượn từ Google nữa — cắt luôn nguồn traffic SEO khổng lồ mà Chegg phụ thuộc.
- **2024–2025**: Chegg liên tục cắt giảm nhân sự (nhiều vòng layoff, tổng >40% nhân sự), kiện Google vì AI Overviews "đánh cắp" traffic, và cuối cùng cân nhắc bán công ty / rút khỏi sàn.

### 1.3. Tác động quan sát được

- **Doanh thu**: giảm liên tục từ ~$766M (2021) xuống dưới $500M (2024), dự báo tiếp tục giảm.
- **Cổ phiếu**: từ đỉnh ~$113 (2021) xuống dưới $1 (2024–2025), mất hơn 99% giá trị vốn hóa, bị cảnh báo delist khỏi NYSE.
- **Subscriber**: số lượng subscriber Chegg Study giảm liên tục mỗi quý, hàng triệu user rời bỏ trong 2 năm.
- **Traffic**: lượng truy cập organic từ Google sụt mạnh do AI Overviews trả lời trực tiếp trên trang kết quả tìm kiếm.
- **Nhân sự**: nhiều vòng sa thải lớn (2023–2025), CEO/CFO thay đổi liên tục.

---

## 2. Phân tích

### 2.1. Trước AI — JTBD (Job To Be Done) của user là gì?

Sinh viên không thực sự "muốn mua Chegg" — họ muốn **"hoàn thành bài tập về nhà đúng hạn, với điểm chấp nhận được, tốn ít thời gian/công sức nhất."** Chegg thắng vì là cách rẻ và nhanh nhất để làm việc đó so với: tự giải (chậm, tốn công), thuê gia sư (đắt), hỏi bạn bè (không đáng tin cậy với mọi bài).

**Giả định nền tảng giúp Chegg thắng**: lời giải chi tiết là một **tài sản hữu hạn, tốn công tạo ra**, nên ai sở hữu kho lời giải lớn nhất + rẻ nhất sẽ chiếm thị phần. Đây là một dạng "lợi thế dữ liệu/kho hàng" (inventory moat).

### 2.2. Sau AI — kỳ vọng user đổi ở đâu? JTBD có đổi thật không?

**JTBD gốc không đổi** — sinh viên vẫn cần hoàn thành bài tập, vẫn cần lời giải đúng nhanh. Cái thay đổi là **cách hoàn thành job đó**:

- Trước: "tìm trong kho có sẵn đáp án của ai khác đã giải" → trả phí theo subscription.
- Sau: "hỏi AI giải tại chỗ, theo đúng đề bài của riêng mình" → miễn phí (hoặc gần miễn phí), nhanh hơn (giây thay vì giờ), và **cá nhân hóa hơn** (AI giải đúng version đề bài của user, không cần đề đã từng có trong kho).

→ Đây không chỉ là đổi *cách* hoàn thành job — nó **xóa bỏ luôn lợi thế cạnh tranh cốt lõi** của Chegg, vì giả định nền tảng (lời giải là tài sản hữu hạn cần kho tích lũy) không còn đúng nữa: AI generative tạo lời giải theo yêu cầu, không cần kho có sẵn.

### 2.3. Cục diện mới của thị trường

- **Ai đang thay thế**: ChatGPT (và các AI chatbot miễn phí/giá rẻ khác: Claude, Gemini, Copilot) thay thế trực tiếp chức năng giải bài tập của Chegg.
- **Ai phản ứng tốt hơn**: 
  - Google — biến đe dọa (mất traffic search) thành lợi thế bằng AI Overviews, giữ user ở lại trang kết quả tìm kiếm thay vì để họ click qua Chegg.
  - Các nền tảng học tập có "moat" khác ngoài lời giải thuần (ví dụ Duolingo dùng gamification/habit, Coursera dùng chứng chỉ có giá trị với nhà tuyển dụng) ít bị tổn thương hơn vì JTBD của họ không chỉ là "có đáp án nhanh."
- **Phân khúc bị xóa sổ hay tái cấu trúc?**
  - Phân khúc **"kho đáp án có sẵn trả phí" gần như bị xóa sổ** — vì AI generative làm cho mô hình "trả tiền xem đáp án người khác đã giải" trở nên dư thừa.
  - Phân khúc **"hỗ trợ học tập" nói chung không biến mất** mà tái cấu trúc: giá trị chuyển từ "có đáp án" sang "được giải thích/kèm 1:1 theo nhu cầu cá nhân, có tính tương tác, có xác thực/đánh giá (assessment) chống gian lận."

### 2.4. Ai đang thắng trong phân khúc mới, và thắng nhờ gì?

- **OpenAI/ChatGPT, Google AI Overviews, Microsoft Copilot**: thắng nhờ chi phí cận biên gần 0 để tạo lời giải mới (không cần kho tích lũy), tốc độ tức thì, và độ phổ biến/miễn phí giúp chiếm luôn thói quen của sinh viên.
- **Các nền tảng giáo dục sống sót/thích nghi tốt** (Khan Academy với Khanmigo, Duolingo): thắng nhờ tích hợp AI như một **trợ giảng cá nhân hóa** thay vì kho đáp án tĩnh, đồng thời giữ được lớp giá trị mà AI thuần không thay thế được (lộ trình học có cấu trúc, động lực, chứng chỉ).
- **Điều thay đổi vĩnh viễn**: "lợi thế kho dữ liệu/nội dung tĩnh" (content moat) không còn là rào cản gia nhập bền vững trong các ngành mà AI generative có thể tái tạo nội dung tương tự theo yêu cầu, theo thời gian thực, với chi phí gần 0. Bất kỳ sản phẩm nào có giá trị cốt lõi nằm ở "tổng hợp/cung cấp thông tin có sẵn" (lời giải, tóm tắt, tra cứu) đều đối mặt rủi ro tương tự Chegg, trừ khi xây được lớp giá trị khác (xác thực, cộng đồng, chứng chỉ, trải nghiệm cá nhân hóa sâu) mà AI generative khó sao chép.

---

## 3. Tóm tắt 1 dòng

Chegg bán "đáp án có sẵn" — một tài sản từng cần nhiều năm tích lũy mới có giá trị; ChatGPT khiến đáp án trở thành thứ tạo ra tức thời và miễn phí, xóa sổ chính lợi thế cạnh tranh mà Chegg được xây dựng trên đó.
