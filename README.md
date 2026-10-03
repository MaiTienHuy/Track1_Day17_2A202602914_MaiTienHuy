# Track 1 · Day 17 — Problem Interview (Case B: Personal Learning Notes)

> **Trạng thái:** Đã có một lượt phỏng vấn; Interview Record được điền từ phần tóm tắt do interviewer cung cấp và đã có liên kết bản ghi. Ngày giờ phỏng vấn đã được ghi trong record, nhưng chưa đối chiếu với bản ghi. Repo chưa có transcript, tình huống cụ thể đủ chi tiết hoặc thông tin xác nhận đồng ý ghi âm và chia sẻ bản ghi. Phần Chặng 1 là **giả thuyết trước phỏng vấn**; kết quả ban đầu được ghi riêng bên dưới.

## 1. Thông tin cá nhân và nhóm

| Mục | Thông tin |
| --- | --- |
| MHV | 2A202602914 |
| Họ tên | Mai Tiến Huy |
| Người được phỏng vấn | Đinh Trường An — MHV 2A202602393 |
| Ngày giờ phỏng vấn | 03/10/2026, 12:00 (theo Interview Record; chưa đối chiếu với bản ghi) |
| Tên nhóm | **[Điền tên nhóm]** |
| Thành viên | **[Điền họ tên các thành viên]** |
| Case đã chọn | Case B — AI Notes: Personal Learning Notes |

**Tài liệu phỏng vấn:** [Interview Record](interview/notes.md) · [Liên kết bản ghi](interview/recording-link.md). Các câu trả lời được đánh dấu *mock* trong Interview Record chỉ để minh họa, không phải bằng chứng phỏng vấn. Nội dung bản ghi, quyền truy cập và sự đồng ý của người tham gia cần được xác nhận trước khi dùng hoặc chia sẻ.

## 2. Problem Hypothesis Brief — Chặng 1

### Solution → capability trung tính

**Solution directive nguyên văn:** Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu **“Chưa hiểu”**, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu.

**Capability trung tính:** Giúp học viên giữ lại và tìm được những điểm họ chú ý hoặc chưa rõ trong một bài học khi cần ôn tập hay áp dụng về sau. Capability này không quy định công nghệ hoặc hình thức ghi chú; việc học viên có thực sự quay lại hay không vẫn cần kiểm tra.

### Change — chuỗi thay đổi được kỳ vọng

| Mắt xích | Giả thuyết cần kiểm tra |
| --- | --- |
| Output do nhóm tạo | Một bản tổng hợp từ nội dung bài và dấu vết học tập, có thể chỉnh sửa trước khi lưu. |
| Thay đổi nhận thức | Học viên nhận ra điểm quan trọng, câu hỏi còn mở và mối liên hệ giữa các ý đã lưu. |
| Thay đổi hành vi | Học viên xem lại, chỉnh sửa và dùng nội dung đã lưu khi ôn tập hoặc làm bài. |
| Outcome nhóm muốn ảnh hưởng | Học viên tìm lại và dùng đúng kiến thức dễ hơn, chứ không chỉ tạo nhiều ghi chú hơn. |

**Điểm có thể đứt:** Nếu học viên không xem lại ghi chú, bản tổng hợp dù được tạo tốt cũng khó tạo ra outcome trên.

### Actor → Situation & Job

| Actor | Việc họ làm | Pain/hậu quả có thể có | Vai trò nghiên cứu |
| --- | --- | --- | --- |
| Học viên | Học bài, đánh dấu/ghi lại ý, ôn tập hoặc áp dụng kiến thức. | Có thể mất thời gian tìm lại ý hoặc không hiểu được ghi chú cũ. | **Điều tra trước:** trực tiếp làm job và chịu hậu quả. |
| Giảng viên/người thiết kế bài | Soạn nội dung và hỗ trợ học viên hiểu bài. | Có thể không biết học viên vướng ở đâu. | Actor liên quan gián tiếp, chưa phải trọng tâm phỏng vấn. |

**Situation:** Trong 7 ngày gần đây, một học viên đã highlight, ghi chú hoặc lưu một phần của bài học để xem lại, rồi kết thúc bài hoặc chuyển sang việc học khác.

**Job:** Khi gặp ý quan trọng hoặc chưa hiểu trong lúc học, họ muốn tiếp tục hiểu và áp dụng kiến thức khi cần. Họ có thể dùng highlight, ghi chú tay, ảnh chụp, bookmark hoặc cách riêng; có quay lại các dấu vết đó hay không phải được hỏi, không mặc định.

**JTBD hypothesis:** “Khi học xong một bài có những phần tôi muốn nhớ hoặc chưa hiểu, tôi muốn có cách tiếp tục học và tìm lại ý liên quan lúc cần, để có thể ôn hoặc áp dụng kiến thức.”

### Pain — hai cách giải thích cạnh tranh

| Giả thuyết | Barrier → consequence có thể có |
| --- | --- |
| **A — chọn điều tra trước** | Các ý được đánh dấu nằm rời rạc hoặc thiếu ngữ cảnh, nên khi cần ôn/áp dụng, học viên phải lục lại bài và tự nối các ý; việc này tốn thời gian hoặc khiến họ bỏ qua điều đã lưu. |
| **B — cạnh tranh** | Học viên hiếm khi quay lại ôn vì chưa có việc cần dùng, thiếu thời gian hoặc ưu tiên nguồn khác; nội dung đã lưu không được dùng ngay cả khi được sắp xếp rõ ràng. |

Chọn A để điều tra trước vì nó nối tình huống lưu dấu vết với job tìm và dùng lại kiến thức. B là nhánh có thể làm nhóm đổi hướng: nếu học viên ít khi quay lại, việc sắp xếp ghi chú có thể không giải quyết rào cản chính. Đây là lựa chọn nghiên cứu, chưa phải kết luận rằng A đúng.

**Problem Hypothesis:** Khi cần dùng lại nội dung từng đánh dấu hoặc ghi lại để ôn hay làm bài, học viên gặp khó khăn vì các dấu vết nằm rời rạc hoặc thiếu ngữ cảnh; họ mất thời gian tìm, tự sắp xếp lại, hoặc bỏ qua phần đã lưu. Giả thuyết này sẽ yếu đi nếu họ hiếm khi quay lại vì lý do không liên quan đến cách tổ chức ghi chú.

### Evidence Map

| Cần kiểm tra | Bằng chứng làm A đáng tin hơn | Bằng chứng khiến nhóm sửa/bác bỏ A |
| --- | --- | --- |
| Situation có thật | Kể được một lần trong 7 ngày qua, chỉ rõ bài học, phần đã lưu và thời điểm. | Không có sự kiện gần đây hoặc chỉ nói về thói quen chung. |
| Có quay lại hay không | Kể được lần dùng lại nội dung đã lưu để ôn hoặc làm bài. | Hiếm khi quay lại; lần cần kiến thức họ dùng bài gốc/nguồn khác hoặc không ôn. |
| Pain có ý nghĩa | Khi quay lại, mất công tìm, hiểu hoặc ghép các dấu vết với ngữ cảnh. | Tìm và dùng dễ; sự rời rạc không cản việc học. |
| Workaround | Đã chụp ảnh, chép lại, mở nhiều tab, hỏi người khác, hoặc tự tạo cách sắp xếp. | Không cần cách xử lý nào, hoặc không quay lại vì thiếu nhu cầu/thời gian. |
| Consequence | Mất thời gian, bài tập/ôn tập bị chậm, hoặc bỏ qua ý cần dùng. | Không có hậu quả cụ thể; hoặc không ôn do ưu tiên khác dù ghi chú rõ. |
| Pattern | Tình huống tương tự lặp lại ở nhiều bài/lần học, có mốc thời gian cụ thể. | Chỉ là một ngoại lệ hiếm gặp. |

**Điều phải đúng để A đứng vững:** Học viên thực sự cần dùng lại nội dung đã lưu; cách lưu hiện tại tạo trở ngại đủ đáng kể; việc sắp xếp rời rạc hoặc thiếu ngữ cảnh góp phần gây ra trở ngại ấy.

**Điều có thể làm nhóm đổi hướng:** Học viên hiếm khi quay lại vì không cần ôn, thiếu thời gian hoặc dùng nguồn khác; khi quay lại thì tìm và dùng dễ. Lời khen giải pháp hay lời hứa “sẽ dùng” không được tính là evidence.

### Kết quả ban đầu sau một lượt phỏng vấn

| Câu hỏi cần học | Điều người tham gia kể trong bản tóm tắt | Nhận định tạm thời |
| --- | --- | --- |
| Có quay lại xem không? | Có quay lại, nhưng chỉ thỉnh thoảng. Có nhiều nội dung từng lưu/highlight không được xem lại vì quên nội dung lẫn quên quay lại. | Có nhu cầu dùng lại ở một số thời điểm; không thể mặc định mọi dấu vết sẽ được ôn. |
| Khi quay lại có khó không? | Khoảng cách từ lúc lưu đến khi cần dùng lại được nêu là 6 giờ đến 3–4 ngày. Người tham gia nhắc đến Ctrl+F và việc phải kiểm tra cách ghi chú; họ cho rằng việc này mất công. | Có tín hiệu về khó khăn, nhưng chưa rõ việc kiểm tra diễn ra lúc ghi hay lúc tìm lại; chưa có thời gian thao tác hay kết quả cụ thể. |
| Ghi chú rời rạc hay ít quay lại? | Ghi chú được mô tả là đầy đủ, nhưng người tham gia vẫn chỉ thỉnh thoảng quay lại. | Giả thuyết A và B đều còn khả năng; “đầy đủ” chưa đồng nghĩa “dễ tìm” và chưa giải thích được việc quên ôn. |

**Kết luận nghiên cứu tạm thời:** Chưa đủ cơ sở nói AI Notes giải quyết đúng nguyên nhân chính. Cần theo một lần tìm ghi chú từ lúc phát sinh nhu cầu đến lúc dùng xong, và một lần đã lưu nhưng không mở lại, để xác định rào cản cùng hậu quả thực tế. Chi tiết và giới hạn bằng chứng nằm trong [Interview Record](interview/notes.md).

### Solution Parking Lot — để sau nghiên cứu

| Hướng có thể thử sau khi xác nhận problem | Loại |
| --- | --- |
| Mẫu ghi chú thủ công gồm “ý chính – vì sao lưu – câu hỏi còn mở – nguồn bài”. | Không dùng AI |
| Danh sách các điểm đã lưu kèm liên kết về đúng vị trí trong bài. | Không dùng AI |
| Nhắc học viên viết một câu giải thích bằng lời của mình cho mỗi điểm lưu. | Không dùng AI |
| Gợi ý nhóm các dấu vết theo chủ đề để học viên kiểm tra và sửa. | AI |
| Tạo bản nháp ghi chú từ dấu vết và nội dung bài để học viên chỉnh sửa. | AI |

## 3. Conversation Guide — Chặng 2

**Trạng thái phiên bản:** Ba câu hỏi chính là bản guide trước khi sửa. Phần “Bổ sung sau phỏng vấn” và Revision log là **đề xuất cập nhật** dựa trên phần tóm tắt; chưa có thông tin xác nhận nhóm đã chốt bản cuối.

### Big 3

| Điều quan trọng nhất cần học | Evidence cần tìm | Điều khiến nhóm xem lại giả thuyết |
| --- | --- | --- |
| **1.** Học viên có thật sự quay lại xem nội dung/ghi chú sau khi học không? | Lần lưu gần nhất: khi nào, có mở lại không, để làm gì, đã làm gì. | Nhiều dấu vết chỉ được lưu rồi bỏ đó. |
| **2.** Khi quay lại, việc tìm và sử dụng highlight/ghi chú/câu hỏi có khó hoặc tốn thời gian không? | Một lần tìm/dùng lại cụ thể: cách tìm, các bước, thời gian, kết quả, workaround. | Họ tìm và dùng dễ, không mất công đáng kể. |
| **3. Câu hỏi “đáng sợ”:** Ghi chú rời rạc là rào cản, hay học viên hiếm khi ôn dù ghi chú rõ? | Một lần đã lưu nhưng không xem lại: việc cần làm, lựa chọn nguồn khác hoặc lý do không ôn. | Không quay lại chủ yếu vì thiếu nhu cầu/thời gian hoặc ưu tiên khác; nhóm cần xem lại hướng tổ chức ghi chú. |

### Tuyển người và mở đầu

**Tiêu chí tuyển:** Người trong 7 ngày gần đây đã chủ động highlight, ghi chú, đánh dấu “chưa hiểu” hoặc lưu một phần bài học để xem lại. Không cần họ biết hay dùng AI Notes.

**Recruitment check, không tính là evidence chính:** “Trong 7 ngày qua, bạn có lần nào đang học một bài rồi đánh dấu hoặc ghi lại một phần để xem sau không? Lần gần nhất là ngày nào và bạn đã lưu bằng cách gì?” Nếu không có sự kiện phù hợp, đổi người phỏng vấn.

**Lời mở đầu:** “Mình muốn tìm hiểu cách mọi người ghi lại nội dung bài học và học lại sau đó. Mình muốn nghe những việc bạn đã làm trong một lần gần đây; không có câu trả lời đúng sai. Bạn có thể bỏ qua câu nào không muốn trả lời.”

**Xin phép ghi âm, nói trước khi bấm ghi:** “Mình muốn ghi âm để nghe lại chính xác và viết notes cho bài học. Bản ghi chỉ dùng để xem lại, bóc transcript và phục vụ bài học; không chia sẻ công khai. Bạn có đồng ý cho mình ghi âm buổi này không?” Chỉ ghi khi có câu trả lời đồng ý rõ ràng; ghi trạng thái consent vào `interview/notes.md`.

**Story opener:** “Kể mình nghe về lần gần nhất, trong 7 ngày qua, bạn đánh dấu hoặc ghi lại một phần của bài học để xem lại. Hôm đó bạn đang học gì và chuyện diễn ra từ lúc nào?”

### Ba câu hỏi chính

| Nối với Big 3 | Câu hỏi dùng sau story opener |
| --- | --- |
| 1 | “Sau khi lưu nội dung đó, lần tiếp theo bạn cần dùng lại nó là khi nào? Bạn đã làm gì? Nếu chưa có lần nào, từ lúc lưu đến nay chuyện gì đã xảy ra với phần đó?” |
| 2 | “Nếu đã từng tìm lại, lúc đó bạn tìm bằng cách nào? Mất khoảng bao lâu, kết quả ra sao? Có bước nào mất công hoặc khó không?” |
| 3 | “Bạn nhớ lần gần đây nào đã lưu hoặc highlight một phần nhưng sau đó không quay lại xem không? Lúc đó bạn định dùng nó vào việc gì, và điều gì xảy ra tiếp theo?” |

**Probe bank, chỉ hỏi theo câu chuyện:** “Rồi sau đó thì sao?” · “Bạn đã làm gì tiếp?” · “Mất khoảng bao lâu?” · “Bạn đã dùng những app hoặc công cụ nào?” · “Cuối cùng bạn có tìm được không?” · “Việc đó ảnh hưởng gì đến việc học/làm bài?” · “Lần gần nhất trước đó là khi nào?” Chỉ hỏi về thời gian/công cụ khi họ đã mô tả một hành động tương ứng; không mặc định rằng họ phải mở app khác hoặc đã gặp khó khăn. Nếu họ luôn quay lại xem, bỏ qua câu 3 theo dạng “không xem lại” và đào sâu lần dùng lại gần nhất.

**Bổ sung sau phỏng vấn:** Nếu nghe câu trả lời chung như “thỉnh thoảng”, “mất công” hoặc “ghi chú đầy đủ”, đề nghị người tham gia chọn **một lần gần nhất** và kể theo thứ tự: cần dùng ý gì → mở ở đâu → tìm bằng từ khóa nào → kiểm tra ghi chú nào → có tìm được không → mất bao lâu → ảnh hưởng gì. Với lần lưu mà không xem lại, hỏi lúc đó họ có cần kiến thức ấy không và đã làm gì thay thế. Chỉ hỏi một nhánh khi người tham gia thực sự đã trải qua tình huống đó.

| Khi câu trả lời lệch khỏi evidence | Phản xạ | Cách hỏi tiếp |
| --- | --- | --- |
| Lời khen/đánh giá ý tưởng | Deflect | “Cảm ơn bạn. Quay lại lần học đó, bạn đã làm gì sau khi lưu phần ấy?” |
| Câu chung chung hoặc lời hứa tương lai | Anchor | “Lần gần nhất chuyện đó xảy ra là khi nào?” |
| Feature request | Dig | “Ý tưởng đó giúp bạn làm việc gì? Lần gần nhất bạn gặp việc ấy, bạn đã xử lý ra sao?” |

**Rà soát guide trước phỏng vấn:** Câu hỏi bắt đầu từ sự kiện gần đây; không nêu AI Notes trong lời hỏi; không hỏi “bạn có muốn dùng tính năng không”; Big 3 có một câu có thể khiến nhóm bỏ hướng ghi chú; nếu recruitment check không đạt thì đổi cặp. Khi thực hành, interviewer theo câu chuyện thay vì đọc bảng hỏi nguyên thứ tự.

### Revision log sau phỏng vấn

| Quan sát từ lượt phỏng vấn | Câu hỏi trong guide trước khi sửa | Câu hỏi đề xuất | Vì sao sửa |
| --- | --- | --- | --- |
| Người tham gia nhắc đến Ctrl+F và việc kiểm tra cách ghi chú, nhưng chưa rõ việc kiểm tra diễn ra lúc ghi hay lúc tìm; phần tóm tắt cũng thiếu thời gian và kết quả. | “Nếu đã từng tìm lại, lúc đó bạn tìm bằng cách nào? Mất khoảng bao lâu, kết quả ra sao? Có bước nào mất công hoặc khó không?” | “Ở lần gần nhất bạn cần tìm lại ghi chú, bạn đã mở gì và tìm thế nào? Nếu dùng Ctrl+F, bạn tìm trong đâu và đã làm gì tiếp? Việc kiểm tra cách ghi chú diễn ra lúc đang ghi hay lúc tìm lại?” | Câu cũ hỏi về công cụ và cảm nhận khó, nhưng phần tóm tắt chưa xác định đúng bước gây tốn công hoặc hậu quả của bước đó. **Đề xuất sửa; chưa xác nhận đã chốt cùng nhóm.** |
| Người tham gia nói ghi chú đầy đủ nhưng chỉ thỉnh thoảng quay lại; lý do “quên” chưa được gắn với một lần cụ thể. | “Bạn nhớ lần gần đây nào đã lưu hoặc highlight một phần nhưng sau đó không quay lại xem không? Lúc đó bạn định dùng nó vào việc gì, và điều gì xảy ra tiếp theo?” | “Hãy kể lần gần nhất bạn lưu một phần rồi không mở lại: lúc lưu bạn định dùng nó khi nào, sau đó có lúc nào cần đến kiến thức ấy không, và bạn đã làm gì?” | Câu mới phân biệt không có nhu cầu, quên quay lại, hay dùng nguồn khác; tránh kết luận từ tần suất chung. **Đề xuất sửa; chưa xác nhận đã chốt cùng nhóm.** |

## 4. Practice Reflection — Chặng 4

> Reflection dựa trên phần tóm tắt của chính interviewer. Repo chưa có transcript để đối chiếu câu chữ hoặc xác nhận việc nhóm đã duyệt các sửa đổi.

1. **Câu hỏi nào giúp người tham gia kể tình huống cụ thể?** Theo phần tóm tắt, câu hỏi về thời điểm cần dùng lại gợi ra khoảng từ 6 giờ đến 3–4 ngày; câu hỏi về cách tìm gợi ra Ctrl+F và việc kiểm tra cách ghi chú. Chưa có transcript để xác nhận câu chữ đã hỏi. Mình cũng chưa neo được câu trả lời vào **một** bài học và **một** lần tìm cụ thể.
2. **Chỗ nào mình cần làm tốt hơn?** Khi nghe “mất công” và “Ctrl+F”, mình cần hỏi tiếp ngay: họ tìm ở đâu, kiểm tra bao nhiêu phần, mất bao lâu, có tìm được không và việc đó ảnh hưởng gì đến học/làm bài. Khi nghe “quên quay lại”, mình cần hỏi về lần gần nhất thay vì chỉ ghi nhận đây là chuyện xảy ra nhiều lần.
3. **Sau lượt phỏng vấn, Conversation Guide được đề xuất sửa ở đâu và vì sao?** Mình bổ sung nhánh hỏi theo trình tự một lần tìm và một lần không quay lại; Revision log ghi câu cũ và câu đề xuất. Cách sửa này nhằm biến câu trả lời khái quát thành bằng chứng hành vi. **Chưa có thông tin nhóm đã cùng chốt các sửa đổi.**

## 5. AI Support Log

| AI đã giúp gì | Điểm có thể sai/hời hợt | Việc người học cần tự kiểm tra, sửa |
| --- | --- | --- |
| Phác thảo chuỗi Solution → Change → Actor → Situation & Job → Pain → Evidence cho Case B; đề xuất Evidence Map và câu hỏi phỏng vấn. | Bản AI đầu tiên nghiêng về việc học viên sẽ dùng lại ghi chú và đặt nhánh cạnh tranh là “chưa hiểu bài”, chưa đúng trọng tâm người học muốn kiểm tra. | Người học chốt lại ba điều cần học: có quay lại không, khi quay lại có khó không, và ghi chú rời rạc hay ít ôn mới là vấn đề; AI sửa brief/guide theo hướng đó. Sau phỏng vấn vẫn cần đối chiếu với evidence thật. |
| Tạo khung README và Interview Record. | AI không có mặt trong buổi phỏng vấn; không thể tự biết lời kể, nội dung bản ghi, consent hay thay đổi guide thực tế. | Đối chiếu notes và reflection với bản ghi hoặc ghi chép gốc; xác nhận liên kết bản ghi, quyền truy cập và sự đồng ý của người tham gia. |
| Chuyển phần tóm tắt hậu phỏng vấn thành Interview Record, kết quả ban đầu và câu hỏi đào sâu. | Từ khóa ngắn như “đầy đủ” và “mất công” có thể bị diễn giải quá mức; phần tóm tắt thiếu một câu chuyện hoàn chỉnh và exact quote. | Xác nhận ý của người tham gia, thời gian/kết quả thao tác và tác động thực tế; sửa mọi chỗ không khớp lời kể gốc trước khi nộp. |

## Kiểm tra trước khi nộp

- [x] Repo hiện có tên `Track1_Day17_2A202602914_MaiTienHuy`, theo mẫu `Track1_Day17_MHV_HoVaTen`.
- [x] README có đủ năm phần và bản chuẩn bị cho Chặng 1–2.
- [ ] Điền tên nhóm, thành viên và đối chiếu Problem Hypothesis Brief với kết quả nhóm đã chốt.
- [x] Đã có một lượt phỏng vấn và điền `interview/notes.md` từ phần tóm tắt được cung cấp.
- [ ] Đối chiếu ngày giờ phỏng vấn đã ghi với bản ghi; xác minh bài học/lần lưu trong 7 ngày và tiêu chí tuyển; bổ sung một câu chuyện cụ thể cùng hậu quả hoặc chi phí thực tế.
- [ ] Xác nhận sự đồng ý ghi âm và chia sẻ bản ghi trước khi sử dụng hoặc nộp.
- [x] Đã thêm liên kết bản ghi trong `interview/recording-link.md`.
- [ ] Kiểm tra liên kết trỏ đúng bản ghi và chỉ cấp quyền cho giảng viên/TA theo phạm vi người tham gia đã đồng ý.
- [x] Đã đề xuất sửa Conversation Guide, điền Revision log và ba câu Practice Reflection dựa trên dữ liệu hiện có.
- [ ] Nhóm đối chiếu bản sửa với ghi chép gốc và xác nhận phiên bản cuối.
