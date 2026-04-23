# Day 16 Submission
**Tên học viên:** Trần Thị Kim Ngân
**Mã học viên:** 2A202600432
**Product:** AI Gym Coach

---

## 1. Idea Reframed

### Original Idea
Xây dựng một ứng dụng mobile dùng AI để phân tích video người dùng tập gym, chỉ ra lỗi kỹ thuật, và cung cấp hướng dẫn cải thiện — thay thế vai trò feedback tức thời của Personal Trainer.

### Reframed as a Product Opportunity

> **Observed gap:** Hơn 8 triệu người tập gym tại Việt Nam không có khả năng tự đánh giá form chuẩn xác — YouTube dạy kỹ thuật cho "người bình thường", không phải cho cơ thể của họ. PT chi phí 200–500K/buổi là rào cản tài chính thực sự.
>
> **Founding belief:** Nếu người dùng được nhìn thấy chính xác mình đang làm gì sai — không phải mô tả chung chung mà là skeleton overlay trên video của bản thân — họ sẽ sửa được. Feedback cụ thể, tức thì, và gắn với tiến trình cá nhân tạo vòng lặp học tập bền vững mà không cần PT.

> 

---

## 2. Customer / Segment Card

- **Segment name:** Solo Beginner (Người tự tập mới)
- **Operational context:** Tập tại phòng gym thương mại (Fit24, California, gym địa phương); 1–3 buổi/tuần; không có PT cố định; sử dụng điện thoại trong hoặc sau khi tập
- **Recurring workflow:** Xem YouTube/TikTok hướng dẫn bài tập trước → vào gym tự làm → không chắc mình làm đúng không → hỏi bạn hoặc bỏ qua
- **Pain moment:** Khi thấy đau khớp, vai, lưng sau buổi tập — hoặc khi tập mãi không thấy cơ phát triển — mà không biết nguyên nhân từ form sai hay lý do khác
- **Why now:** Gen Z VN tập gym tăng mạnh hậu COVID; TikTok fitness content normalize việc self-track; chi phí PT leo thang; smartphone camera chất lượng đủ để phân tích pose
- **Access path:** TikTok demo video AI overlay → App Store download; secondary: bạn bè giới thiệu trong group gym

**One-sentence description:**
> Người trẻ 18–28 tuổi tập gym 1–3 buổi/tuần không có PT, biết mình có thể đang sai form nhưng không có cách nào kiểm chứng ngoài cảm giác chủ quan.


---

## 3. Need Map (3 needs)

### Need #1 : Biết ngay mình đang tập đúng hay sai
-Need statement: Khi tôi tập gym một mình, tôi cần biết ngay tôi đang thực hiện động tác đúng kỹ thuật hay không — để tôi có thể sửa kịp thời trước khi hình thành thói quen xấu hoặc bị chấn thương.
Current workaround:
+Xem đi xem lại video YouTube/TikTok để đối chiếu 
+Soi gương trong phòng tập 
+Tự cảm nhận và điều chỉnh không có feedback ngoài 
+Bỏ qua luôn khi không chắc và tập tiếp — rủi ro chấn thương thực sự 
Pain signal:
+Reddit r/Fitness, r/GYM_VN — "check my form" posts: Người dùng quay video bản thân rồi đăng lên Reddit/Facebook group nhờ người lạ góp ý form — chấp nhận chờ vài giờ, nhận feedback không đồng nhất từ người không phải chuyên gia
+YouTube "squat form check" — hàng triệu lượt xem:  Người ta chủ động tìm kiếm nội dung này để tự so sánh — dù biết rằng video chung chung không giải quyết được vấn đề của riêng họ.Search behavior
-Evidence (or proxy)
+Trực tiếp: "Check my form" là một trong những dạng post phổ biến nhất trên r/fitness) 
+Trực tiếp: Các app như FormCheck, AI Squat Analysis trên App Store có rating 4.5+ với hàng nghìn review
+Proxy: YouTube gym form checker videos có hàng triệu lượt xem — demand đã có sẵn, chỉ thiếu giải pháp cá nhân hóa.
-Why underserved: 
+YouTube/TikTok dạy form chung — không biết họ đang sai ở đâu
+PT offline giải quyết được nhưng nhiều người không đủ điều kiện kinh tế để chi trả
+App gym hiện tại chỉ track reps/sets/weight — không có bất kỳ tính năng phân tích kỹ thuật nào

### Need #2: Thấy mình đang tiến bộ — có bằng chứng, không chỉ cảm giác

- Need statement: 
Khi tôi tập gym đều đặn nhiều tuần, tôi cần thấy được mình đang cải thiện kỹ thuật như thế nào theo thời gian — bằng dữ liệu thực tế, không chỉ cảm giác chủ quan — để tôi có động lực tiếp tục và biết mình đang đi đúng hướng.
- Current workaround
+ Chụp ảnh hoặc quay video định kỳ rồi tự so sánh — không có điểm tham chiếu kỹ thuật
+ Ghi nhật ký tập (số kg, số rep tăng) —  không đo được chất lượng kỹ thuật
+ Phần lớn không theo dõi gì cả — tập theo cảm tính, không có hệ thống đo progress kỹ thuật
- Pain signal: 
+Drop-off tuần thứ 3 là hiện tượng phổ biến nhất trong gym: thói quen chưa hình thành, không thấy kết quả rõ → bỏ cuộc. Đây là hành vi quan sát được, không phải giả định.

- Evidence (or proxy)

+Proxy: Duolingo, Nike Run Club dùng streak + progress chart → retention tăng 40%+ — đây là pattern đã được validate ở nhiều sản phẩm habit-forming.

- Why underserved:
+App gym hiện tại chỉ theo dõi khối lượng tập (reps/sets/weight) — không đo được chất lượng kỹ thuật theo thời gian
+Không có baseline: muốn đo tiến bộ phải có điểm bắt đầu — hầu hết người tập không có video đầu tiên để so sánh vì không ai nhắc họ quay từ ngày đầu

### Need #3 (optional): Psychological Safety khi tập
---

## 4. Strategy Statement

> For **người tự tập gym 18–30 tuổi tại Việt Nam không có PT**
> who struggle with **không biết kỹ thuật của mình đúng hay sai, và không thấy mình tiến bộ**,
> our product helps them **tập đúng kỹ thuật và cảm nhận được sự tiến bộ rõ ràng theo thời gian**
> through **AI phân tích video cá nhân hóa — nhìn vào cơ thể của bạn, không phải cơ thể người mẫu YouTube**,
> unlike **YouTube (dạy chung), PT (đắt & không scalable), app gym hiện tại (chỉ track reps)**,
> because we can leverage **dataset người Việt Nam + first-mover advantage B2C + data moat từ lịch sử tập cá nhân**.

---

## 5. Moat Hypothesis

**Moat mechanism:** Domain-Learning Flywheel × Personal Progress Lock-in

If we deploy 100K+ phân tích trong vertical gym người Việt (squat, deadlift, bench, overhead press), the following improve:

1. **Model accuracy cho body type Việt Nam** — tỉ lệ cơ thể, góc khớp trung bình, điều kiện ánh sáng gym VN khác với dataset phương Tây. Càng nhiều data VN, model càng ít false positive và false negative.
2. **Benchmark reference library** — "video chuẩn" dần được cá nhân hóa theo phân khúc user (người mới, trung bình, nâng cao) thay vì dùng video một người hoàn hảo. Data từ user tốt → reference cho user mới.
3. **User lock-in qua lịch sử cá nhân** — lịch sử 6 tháng tập luyện với video và điểm số là tài sản cá nhân. User không muốn mất data này khi đổi app. Progress moat mạnh hơn feature moat.

Why competitors cannot easily replicate this:
> Moat chính không phải AI model (có thể mua/build). Moat thực sự là dataset pose người Việt được label chất lượng cao (tốn 6–12 tháng, không thể shortcut), trust từ early user community qua gym partnership, và progress history lock-in — user đã có 3+ tháng data sẽ không switch ngay cả khi có app tốt hơn về tính năng.

>
---

## 6. Initial TAM / SAM / SOM View

| Layer | Estimate | Key Assumptions | Confidence |
|---|---|---|---|
| TAM | $1.8–2.4B / năm | 8–10M người tập gym VN + 80–100M thị trường EN; ~30–40% tự tập không PT; ARPU ~$18/năm | Low |
| SAM | $60–90M / năm | 18–24M người có smartphone, dùng app fitness, sẵn sàng upload video; VN ~3–4M, EN ~15–20M; ARPU ~$4/năm (blended freemium) | Low–Med |
| SOM (12–18 tháng) | 150K–300K users; $70K–175K ARR | VN Phase 1: organic TikTok + gym partnership; Conversion free→Pro 8–12%; ARPU 39K VND/tháng; Growth chủ yếu word-of-mouth | Med |

**Top 3 unknowns requiring further research:**
1. **Conversion rate thực tế của freemium fitness app tại VN** — 8–12% là benchmark global; VN user có willingness-to-pay khác. Cần survey trực tiếp hoặc test pricing page trước khi build Pro tier.
2. **Chi phí AI inference thực tế per video** — nếu GPU cost per analysis > 5K VND thì unit economics không viable ở Free tier. Cần prototype để benchmark cost trước khi commit vào pricing.
3. **Upload Completion Rate thực tế sau install** — Target ≥70% trong Lean Canvas nhưng chưa có benchmark. Đây là funnel metric quan trọng nhất: nếu user không upload, toàn bộ value proposition sụp đổ.

**Judgment:**
- [x] Worth pursuing now — với điều kiện validate Upload Completion Rate ≥50%, GPU cost < 3K VND/video, và willingness-to-pay ≥39K/tháng với ít nhất 20 target user thật trước sprint 1.
- [ ] Worth pursuing but not now
- [ ] Not worth pursuing as currently framed

> 

---

## 7. Positioning Note (2 sentences)

**What we are:**
> AI Gym Coach là công cụ học kỹ thuật cá nhân hóa — như có một người bạn với đôi mắt chuyên nghiệp theo dõi mỗi buổi tập và nói thẳng: "Lần này gối của mày đổ vào trong, sửa đi." Không phán xét, không khen giả tạo, chỉ nói thật.

**What we are not / not yet:**
> Chúng ta không phải Personal Trainer digital, không phải workout planner, không phải nutrition tracker, và chưa phải real-time in-gym coach — Phase 1 là video-based async feedback, mọi feature ngoài core này là distraction trong 12 tháng đầu.

---

## 8. Self-assessment trước Day 17

