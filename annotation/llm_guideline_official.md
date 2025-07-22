## Prompt for multi-labels annotation

**Objective**: Classify Vietnamese social media comment into one or more of the 27 emotion categories defined by GoEmotions, plus neutral.

---

### **Label Categories**
- **amusement** (Giải trí) 😂: Cảm giác buồn cười trước nội dung hài hước, thú vị.
- **excitement** (Hào hứng) 🤩: Cảm giác vui mừng, phấn khích trước sự kiện, thông tin tích cực.
- **joy** (Niềm vui) 😀: Cảm giác hạnh phúc, vui vẻ, thoải mái trước tình huống tích cực.
- **love** (Tình yêu) ❤️: Bày tỏ yêu thương, gắn bó với người, vật, hoặc ý tưởng.
- **desire** (Mong muốn) 😍: Cảm giác mạnh mẽ về mong muốn có được ai đó hoặc điều gì đó.
- **optimism** (Lạc quan) 🤞: Hy vọng, tin tưởng vào kết quả tốt đẹp cho bản thân hoặc đối tượng khác.
- **caring** (Quan tâm) 🤗: Thể hiện tình cảm, sự chăm sóc, hoặc hỗ trợ người khác.
- **pride** (Tự hào) 😌: Hài lòng, kiêu hãnh về bản thân hoặc người khác.
- **admiration** (Ngưỡng mộ) 👏: Kính trọng, khâm phục ai đó vì phẩm chất hoặc thành tựu.
- **gratitude** (Biết ơn) 🙏: Cảm kích, trân trọng trước sự giúp đỡ, lời nói hoặc điều tích cực.
- **relief** (Nhẹ nhõm) 😅: Thở phào, giảm căng thẳng sau khi vượt qua vấn đề cho bản thân hoặc đối tượng khác.
- **approval** (Chấp thuận) 👍: Đồng tình hoặc ủng hộ một ý kiến, hành động.
- **realization** (Nhận ra) 💡: Hiểu hoặc nhận thức, phát giác một điều gì đó.
- **surprise** (Ngạc nhiên) 😲: Bất ngờ trước thông tin hoặc sự kiện không lường trước.
- **curiosity** (Tò mò) 🤔: Mong muốn tìm hiểu thêm, đặt câu hỏi, thắc mắc.
- **confusion** (Bối rối) 😕: Lúng túng, không rõ ràng hoặc mâu thuẫn về thông tin.
- **fear** (Sợ hãi) 😨: Lo lắng, bất an trước điều nguy hiểm hoặc đáng sợ.
- **nervousness** (Lo lắng) 😬: Căng thẳng, bồn chồn trước tình huống, sự kiện.
- **remorse** (Hối hận) 😔: Hối tiếc, tự trách về một quyết định hoặc hành động sai lầm.
- **embarrassment** (Xấu hổ) 😳: Ngượng ngùng, lúng túng trước tình huống khó xử, không phù hợp ở cá nhân hoặc đối tượng khác.
- **disappointment** (Thất vọng) ~😞: Hụt hẫng vì kỳ vọng không được đáp ứng.
- **sadness** (Buồn bã) 😞: thất vọng hoặc không vui.
- **grief** (Đau buồn) 😢: Đau đớn hoặc buồn sâu sắc khi mất mát hoặc thất bại lớn.
- **disgust** (Ghê tởm) 🤮: Khó chịu, chê bai, chỉ trích, khinh bỉ với điều gì gây phản cảm.
- **anger** (Tức giận) 😡: Giận dữ, bức xúc vì bất công hoặc điều không vừa ý.
- **annoyance** (Khó chịu) 😒: Phiền toái trước điều gì đó không hài lòng.
- **disapproval** (Phản đối) 👎: Không đồng ý, thể hiện sự không hài lòng.
- **neutral** (trung tính): bình luận không thể hiện bất kỳ cảm xúc hay thái độ độ nào cụ thể. Nếu câu được gán neutral thì sẽ không gán các nhãn khác.

---

### **Annotation guidelines**
- Only use labels in label categories.
- Select multiple labels if possible relevant.
- No explaination

---

### **Output example**
**Label**: ["optimism", "confusion", "nervousness"]

---

Annotate the following text:


## Prompt for Multi-Label Emotion Annotation

**Objective**: Annotate Vietnamese social media comments with one or more of the 27 emotion categories from GoEmotions, plus neutral.

---

### **Emotion Categories**
- **amusement** 😂: Feeling entertained or amused by humorous or interesting content.
- **excitement** 🤩: Feeling thrilled, enthusiastic, or highly interested in a positive event or information.
- **joy** 😀: Feeling happy, cheerful, or satisfied in a positive situation.
- **love** ❤️: Expressing affection, attachment, or strong emotional connection toward someone or something.
- **desire** 😍: Strongly wanting someone or something.
- **optimism** 🤞: Hoping for a positive outcome for oneself or others.
- **caring** 🤗: Expressing concern, care, or support for others.
- **pride** 😌: Feeling satisfied or proud of oneself or others.
- **admiration** 👏: Showing respect or appreciation for someone’s qualities or achievements.
- **gratitude** 🙏: Expressing thankfulness or appreciation for help, kindness, or positive events.
- **relief** 😅: Feeling reassured or at ease after overcoming a concern or problem.
- **approval** 👍: Agreeing with or supporting an idea, opinion, or action.
- **realization** 💡: Suddenly understanding or discovering something.
- **surprise** 😲: Expressing astonishment or unexpectedness at an event or information.
- **curiosity** 🤔: Showing interest in learning more or asking questions.
- **confusion** 😕: Feeling uncertain, unclear, or conflicted about information.
- **fear** 😨: Feeling anxious or threatened by something scary or dangerous.
- **nervousness** 😬: Feeling tense, uneasy, or worried about a situation or event.
- **remorse** 😔: Feeling regretful or guilty about a past decision or action.
- **embarrassment** 😳: Feeling awkward or self-conscious in an uncomfortable situation.
- **disappointment** 😞: Feeling let down when expectations are not met.
- **sadness** 😞: Feeling sorrowful or unhappy.
- **grief** 😢: Experiencing deep sorrow due to a major loss or failure.
- **disgust** 🤮: Expressing strong dislike, rejection, or criticism of something unpleasant.
- **anger** 😡: Feeling upset or outraged about injustice or dissatisfaction.
- **annoyance** 😒: Expressing irritation or mild displeasure.
- **disapproval** 👎: Showing disagreement or discontent.
- **neutral**: No specific emotion is conveyed. If "neutral" is assigned, no other labels should be selected.

---

### **Annotation Guidelines**
- Only use labels from the defined emotion categories.
- Assign multiple labels if applicable.
- No explanations required.

---

### **Output Example**
**Label**: ["nervousness", "embarrassment", "disappointment"]

---

Annotate the following text:


