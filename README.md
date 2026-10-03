# Track 1 - Day 17: Product Discovery - Finding and Validating Pain Points

## 1. Thông tin cá nhân và nhóm

- **Họ tên:** Mai Tiến Huy
- **Mã học viên:** 2A202602914
- **Tên nhóm:** DBH
- **Case đã chọn:** B - AI Notes: Personal Learning Notes
- **Thành viên:** Phạm Quốc Đạt (2A202602384), Nguyễn Văn Biển (2A202602416), Mai Tiến Huy (2A202602914)
- **Người được phỏng vấn:** Đinh Trường An (2A202602393)
- **Ngày giờ phỏng vấn:** 03/10/2026, 12:00 (theo Interview Record; chưa đối chiếu với bản ghi)

**Tài liệu phỏng vấn cá nhân:** [Interview Record](interview/notes.md) · [Liên kết bản ghi](interview/recording-link.md). Các câu trả lời được đánh dấu *mock* trong Interview Record chỉ để minh họa, không phải bằng chứng phỏng vấn. Repo chưa có transcript và thông tin xác nhận đồng ý ghi âm, chia sẻ bản ghi.

---

## 2. Problem Hypothesis Brief

**Solution directive:** học viên highlight, đánh dấu "Chưa hiểu" hoặc ghi chú ngắn trong lúc học; sau bài học, AI kết hợp các dấu vết này với nội dung bài để tạo ghi chú có cấu trúc; học viên chỉnh sửa và xác nhận trước khi lưu.

**Capability trung tính:** hỗ trợ người học lưu lại, tổ chức và xem lại những nội dung cần chú ý hoặc chưa hiểu trong quá trình học.

**Chuỗi thay đổi (giả định):** người học lưu lại tín hiệu cần chú ý trong lúc học → thông tin được tổ chức để xem lại → người học có thêm ngữ cảnh khi ôn → giảm việc phải tái dựng nội dung từ ghi chú rời rạc.

**Actor:**

| Actor | Đang làm gì | Pain/hậu quả có thể có | Hưởng lợi |
|---|---|---|---|
| Learner | Học, nghe giảng, ghi chú, xem lại | Không ghi kịp/đủ; ghi chú thiếu ngữ cảnh | Có tài liệu xem lại rõ hơn |
| Instructor | Giảng bài, giải thích khái niệm | Người học bỏ lỡ phần giải thích | Người học theo kịp hơn |

**Actor điều tra trước:** Learner, vì là người trực tiếp ghi chú và trải nghiệm khó khăn khi học và xem lại.

**Situation & Job:** khi đang học một buổi có nhiều khái niệm/từ khóa và phần giải thích diễn ra nhanh, learner muốn lưu lại những nội dung chưa hiểu để xem và tìm hiểu lại sau.

**JTBD Hypothesis:** Khi gặp một khái niệm chưa hiểu trong lúc học, tôi muốn lưu lại đủ thông tin để sau buổi học có thể hiểu lại khái niệm đúng với ngữ cảnh đã được giảng.

**Pain Hypothesis A (điều tra trước):** Khi học một buổi có nhiều kiến thức/từ khóa trình bày nhanh, learner gặp khó khăn trong việc ghi lại nội dung vì không ghi kịp phần giải thích, dẫn đến ghi chú chỉ còn từ khóa hoặc thiếu ngữ cảnh và sau đó không chắc mình hiểu đúng.

**Pain Hypothesis B (cạnh tranh):** Khi xem lại nội dung đã lưu, learner gặp khó khăn trong việc tập hợp và tổ chức các ghi chú rời rạc thành tài liệu dễ xem lại, dẫn đến tốn công sắp xếp hoặc tìm lại thông tin.

**Lý do điều tra A trước:** lượt practice của Đạt cho evidence trực tiếp về việc không ghi kịp và không chắc nội dung ghi lại có đúng; chưa có evidence trực tiếp rằng việc tổ chức ghi chú rời rạc là pain chính.

**Evidence Map:**

| Cần kiểm tra | Làm A mạnh hơn | Làm A yếu đi/bị bác bỏ |
|---|---|---|
| Situation có thật | Kể được một buổi học cụ thể có nhiều từ khóa | Không nhớ tình huống nào tương tự |
| Pain có ý nghĩa | Không ghi kịp khiến ghi chú thiếu ngữ cảnh | Chỉ ghi từ khóa mà vẫn hiểu bình thường |
| Workaround tồn tại | Phải tìm hiểu lại hoặc hỏi nguồn khác | Không cần làm gì thêm |
| Consequence tồn tại | Hiểu sai hoặc không chắc, phải học lại | Ghi thiếu không ảnh hưởng thực tế |
| Pattern lặp | Xảy ra trong nhiều buổi | Chỉ là trường hợp cá biệt |

**Problem Hypothesis mang sang Conversation Guide:**

Khi học một buổi có nhiều kiến thức/từ khóa trình bày nhanh, learner có thể gặp khó khăn trong việc ghi lại đủ phần giải thích cho những khái niệm chưa hiểu, khiến ghi chú thiếu ngữ cảnh và khi xem lại họ không chắc mình hiểu/nhớ đúng, từ đó phải tìm hiểu lại sau buổi học.

**Điều cần đúng để hypothesis đứng vững:** learner thật sự gặp tình huống phải ghi trong lúc bài giảng nhanh; ghi thiếu gây thiếu chắc chắn hoặc hiểu sai khi xem lại; learner phải bỏ thêm công sức để tìm hiểu lại.

**Điều có thể khiến sửa hoặc bác bỏ:** learner vẫn hiểu đúng dù chỉ ghi từ khóa; không cần xem lại sau buổi học; nguyên nhân thật là nội dung khó chứ không phải việc ghi chú; các cuộc phỏng vấn sau không thấy pattern tương tự.

**Solution Parking Lot:**

| Hướng giải quyết | AI / Không AI |
|---|---|
| Đánh dấu nhanh chỗ chưa hiểu trong lúc học để quay lại sau | Không AI |
| Template ghi chú: từ khóa - giải thích - ví dụ - câu hỏi còn lại | Không AI |
| Liên kết ghi chú với đúng phần nội dung/slide đang học | Không AI |
| Tóm tắt có cấu trúc từ dấu vết learner đã lưu, learner chỉnh sửa | AI |
| Gợi ý lại ngữ cảnh/kiến thức liên quan đến từ khóa đã đánh dấu | AI |

Đây là các buổi practice nên nhóm **chưa tuyên bố hypothesis đã được validated**.

---

## 3. Conversation Guide (phiên bản cuối)

**Tiêu chí tuyển:** người đã ghi chú, highlight hoặc lưu lại nội dung trong lúc học để xem lại sau trong 7 ngày gần đây.

**Recruitment check:** "Trong 7 ngày gần đây, bạn có lần nào ghi chú, highlight hoặc lưu lại nội dung khi đang học để xem lại sau không?"

**Lời mở đầu:** "Mình đang tìm hiểu cách mọi người ghi lại và xem lại nội dung trong quá trình học. Mình muốn nghe trải nghiệm thực tế của bạn, không có câu trả lời đúng hay sai. Nếu bạn đồng ý, mình xin phép ghi âm để xem lại phục vụ bài học; bản ghi chỉ dùng cho mục đích review của bài."

**Story opener:** "Hãy kể về một buổi học cụ thể gần đây mà bạn đã ghi chú, highlight hoặc lưu lại một nội dung để xem lại sau. Lúc đó bạn đang học gì?"

**Big 3:**

| Điều cần học | Câu hỏi |
|---|---|
| Người học ghi lại nội dung như thế nào | "Trong buổi học đó, bạn đã ghi/lưu nội dung như thế nào? Bạn kể lại những gì bạn đã làm được không?" |
| Barrier khi ghi chú | "Trong quá trình đó, phần nào khiến bạn khó ghi lại hoặc khó theo kịp nhất?" |
| Hậu quả và cách xử lý | "Khi xem lại mà thấy ghi chú thiếu hoặc không chắc mình nhớ đúng, bạn đã làm gì? Việc đó gây ra vấn đề gì cho bạn?" |

**Probe bank:** "Lúc đó chuyện gì xảy ra tiếp theo?" · "Bạn đã làm gì?" · "Vì sao lúc đó bạn làm như vậy?" · "Phần nào khó nhất?" · "Bạn đã thử cách nào khác chưa?" · "Việc đó kéo theo hậu quả gì?" · "Bạn có nhớ một ví dụ cụ thể không?" · "Lần khác có tình huống tương tự không?"

**Nguyên tắc:** hỏi về sự kiện và hành vi đã xảy ra; không giới thiệu Case B/AI Notes; không hỏi "bạn có muốn/dùng feature không"; không coi lời khen hay ý định tương lai là evidence; khi câu trả lời chung chung thì quay lại một tình huống cụ thể.

---

## 4. Practice Reflection

*Phần 1–2 dựa trên ghi chép cá nhân của Mai Tiến Huy; repo chưa có transcript để đối chiếu nguyên văn.*

**1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?**
Câu hỏi về thời điểm cần dùng lại gợi ra khoảng từ 6 giờ đến 3–4 ngày. Câu hỏi về cách tìm gợi ra việc dùng Ctrl+F và kiểm tra cách ghi chú. Mình chưa neo được câu trả lời vào một bài học và một lần tìm cụ thể, nên đây mới là tín hiệu ban đầu.

**2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?**
- Khi nghe “mất công” và “Ctrl+F”, mình cần hỏi tiếp họ tìm ở đâu, kiểm tra những phần nào, mất bao lâu, có tìm được không và việc đó ảnh hưởng gì đến việc học hoặc làm bài.
- Khi nghe “quên quay lại”, mình cần hỏi về lần gần nhất thay vì chỉ ghi nhận đây là chuyện xảy ra nhiều lần.

**3. Nhóm đã sửa Conversation Guide ở đâu và vì sao?**
- **Story opener:** đổi từ "lần gần nhất" sang "một buổi học cụ thể gần đây", vì người được phỏng vấn khó nhớ chính xác lần gần nhất nhưng vẫn kể được một sự kiện thật khi được neo vào buổi học.
- **Câu hỏi barrier:** chuyển sang câu trung tính "phần nào khiến bạn khó ghi lại hoặc khó theo kịp nhất?", vì câu cũ đặt sẵn hai lựa chọn.
- **Câu hậu quả/workaround:** thêm câu hỏi về việc đã làm gì khi ghi chú thiếu hoặc không chắc đúng, để thu evidence về hành vi, workaround và hậu quả.

---

## 5. AI Support Log

| AI đã giúp gì | Điểm có thể sai/hời hợt | Việc người học cần tự kiểm tra, sửa |
| --- | --- | --- |
| Phác thảo chuỗi Solution → Change → Actor → Situation & Job → Pain → Evidence cho Case B; đề xuất Evidence Map và câu hỏi phỏng vấn. | Bản AI đầu tiên nghiêng về việc học viên sẽ dùng lại ghi chú và đặt nhánh cạnh tranh là “chưa hiểu bài”, chưa đúng trọng tâm người học muốn kiểm tra. | Người học chốt lại ba điều cần học: có quay lại không, khi quay lại có khó không, và ghi chú rời rạc hay ít ôn mới là vấn đề; AI sửa brief/guide theo hướng đó. Sau phỏng vấn vẫn cần đối chiếu với evidence thật. |
| Tạo khung README và Interview Record. | AI không có mặt trong buổi phỏng vấn; không thể tự biết lời kể, nội dung bản ghi, consent hay thay đổi guide thực tế. | Đối chiếu notes và reflection với bản ghi hoặc ghi chép gốc; xác nhận liên kết bản ghi, quyền truy cập và sự đồng ý của người tham gia. |
| Chuyển phần tóm tắt hậu phỏng vấn thành Interview Record, kết quả ban đầu và câu hỏi đào sâu. | Từ khóa ngắn như “đầy đủ” và “mất công” có thể bị diễn giải quá mức; phần tóm tắt thiếu một câu chuyện hoàn chỉnh và exact quote. | Xác nhận ý của người tham gia, thời gian/kết quả thao tác và tác động thực tế; sửa mọi chỗ không khớp lời kể gốc trước khi nộp. |
