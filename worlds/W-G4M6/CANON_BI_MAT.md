# ⛔ CANON BÍ MẬT — W-G4M6 "MÙA BÙN ĐEN"

> ⚠️ CẢNH BÁO SPOILER: File này chứa toàn bộ bí mật, điều kiện kết cục và chế độ nhiễm của World.
> Người chơi KHÔNG nên mở nếu muốn giữ trải nghiệm. File được khóa bằng mã băm SHA-256 lúc tạo World;
> mọi phán quyết của ENGINE phải khớp với file này. Không được sửa nội dung sau khi khóa.

---

## 0. THIẾT LẬP (tung bằng RNG thật lúc tạo World)

| Mục | Xúc xắc | Ánh xạ | Kết quả |
|---|---|---|---|
| Độ khó | d5 = 5 | 1..5 = Level 1..5 | **Level 5 — Chuyên gia** (DC cơ bản 16) |
| Chế độ Nhiễm | d2 = 1 | 1 = ĐÓNG, 2 = MỞ (theo thứ tự liệt kê trong prompt) | **ĐÓNG** — Nhiễm 100 → tử vong |
| Gu truyện | d8 = 7 | 1 zombie · 2 nấm/bào tử · 3 biến dị sinh vật · 4 virus tiến hóa · 5 dị năng thức tỉnh · 6 ký sinh · 7 thiên tai + dịch bệnh · 8 sáng tạo tự do | **Thiên tai + dịch bệnh** |
| Mã World | RNG | — | **W-G4M6** |

Hiển thị cho người chơi: Level 5 (công khai vì DC hiện trong mỗi lần tung). Chế độ Nhiễm và gu truyện: **ẨN** (người chơi yêu cầu không biết). Khung trạng thái ghi "Nhiễm: ẨN".

---

## 1. BỐI CẢNH & QUY LUẬT THẾ GIỚI

- Thành phố cảng hư cấu **Hòa Lộc**, duyên hải miền Trung Việt Nam, khoảng 400.000 dân trước thảm họa.
- **11 ngày trước Ngày 1**: động đất 8,9 độ ngoài khơi → sóng thần tràn vào thành phố; vài giờ sau dư chấn làm **vỡ đập thủy điện Sông Chè** ở thượng nguồn → lũ quét. Điện, viễn thông, cầu đường bị phá hủy, thành phố bị cô lập.
- Nước rút một phần, để lại lớp **bùn đen** dày từ trầm tích đáy biển sâu do sóng thần cuốn lên.
- Từ ngày thứ 4 sau thảm họa bùng phát **"sốt bùn"** (dân gọi; tên y khoa tạm "Bệnh phổi đen").
- **Quy luật**:
  - Bùn **ướt** lây qua da và vết thương; bùn **khô** thành bụi, lây qua đường hô hấp (ngày gió mạnh nguy hiểm nhất).
  - Mưa làm bụi giảm nhưng nước ngập dâng lại.
  - Người bệnh giai đoạn cuối **mê sảng, sợ ánh sáng, hung hãn** do viêm não. Họ **vẫn là người**: không phải xác sống, không biến đổi, rồi chết.
  - Dư chấn vẫn xảy ra.
  - **Không có dị năng, không có siêu nhiên.**

---

## 2. KHU VỰC (7)

| # | Khu vực | Nguy hiểm | Ghi chú |
|---|---|---|---|
| L1 | **Trường THCS Lê Lợi** (tầng 3) — ĐIỂM XUẤT PHÁT | Thấp–vừa | Tầng 1 ngập bùn ngang gối. Có Tú & Na. |
| L2 | **Chợ Đầm Cũ** | Cao | Ngập bùn, đã bị cướp gần hết; Bến Cá tuần tra. |
| L3 | **Bệnh viện Đa khoa Hòa Lộc** | Cao (lây nhiễm) | Tầng trệt ngập; khu cách ly tầng 4; kho khóa tầng 5. BS Lam. |
| L4 | **Nhà thờ Giáo xứ Đông Hải** (đồi thấp) | Thấp | Khu an toàn của phe Giáo xứ (~30 người). Vào phải được chấp thuận. |
| L5 | **Cảng Hòa Lộc / bãi container** | Rất cao | Căn cứ Bến Cá. Cầu Bến Ngự gãy. |
| L6 | **Trạm khí tượng Đồi Ăng-ten** | Vừa | Radio VHF, máy phát hỏng nhẹ. Đường lên sạt lở. |
| L7 | **Mũi Đá Vôi** | Vừa | Bãi đá nơi xuồng của tàu Hải Đăng 09 đón người. |

**Liên kết di chuyển** (thời gian đi bộ thường; ban đêm/bão +50%):
- L1 ↔ L2: 40 phút, lội bùn.
- L1 ↔ L3: 1 giờ (một đoạn nước ngang ngực, lội) hoặc 1 giờ 30 (đường mái/ban công, không lội; DC Nhanh nhẹn mỗi lần đi).
- L2 ↔ L5: 30 phút, lội bùn.
- L2 ↔ L4: 1 giờ, nửa đường lội bùn.
- L3 ↔ L4: 1 giờ, đường dốc khô (bụi bùn khô).
- L4 ↔ L6: 2 giờ, dốc sạt lở (DC thể chất 16; từ tối Ngày 4 khi bão: 20).
- L6 ↔ L7: 2 giờ, đường mòn ven núi.
- L5 ↔ L7: 1 giờ bằng xuồng máy (cần xuồng của Hắc + xăng). Không có đường bộ từ L5 vì cầu gãy.
- Không có đường trực tiếp L1 ↔ L4, L1 ↔ L5.

---

## 3. CANON (11 sự thật)

| ID | Loại | Sự thật | Điều kiện tiết lộ |
|---|---|---|---|
| C1 | CÔNG KHAI | Động đất, sóng thần, vỡ đập 11 ngày trước; thành phố cô lập, không điện, không sóng điện thoại. | Mở đầu. |
| C2 | CÔNG KHAI | "Sốt bùn" đang lan: sốt, ho, đờm đen; người nặng mê sảng, hung hãn. | Mở đầu. |
| C3 | CÓ THỂ KHÁM PHÁ | Đường lây: bùn/nước ngập qua da và vết thương, uống nước bẩn, bụi bùn khô, giọt bắn của người ho đờm đen, vết cắn/cào. Đun sôi ≥5 phút hoặc clo diệt được trong nước. Khẩu trang làm ướt giảm hít bụi. | BS Lam giải thích; sổ ghi chép bệnh viện; người chơi quan sát và suy luận (chỉ ghi 💭 cho tới khi có căn cứ). |
| C4 | CÓ THỂ KHÁM PHÁ | Tàu **Hải Đăng 09** phát lặp trên kênh 16 (156.8 MHz): xuồng đón người tại **Mũi Đá Vôi lúc 05:30–06:30 mỗi sáng, đến hết sáng Ngày 7**. | Tin đồn từ Tú (dạng ?); xác minh khi nghe radio tại L6, bộ đàm Bến Cá tại L5, hoặc Hắc nói. |
| C5 | BÍ MẬT | Tàu **kiểm dịch**: đo nhiệt, soi họng. Người có **Nhiễm ≥ 40** (triệu chứng rõ) bị **từ chối**. Thủy thủ có vũ khí, không nhân nhượng. | Gọi radio trực tiếp cho tàu (L6); hoặc tận mắt quan sát buổi đón tại L7. |
| C6 | BÍ MẬT | Tác nhân là vi khuẩn cổ từ trầm tích biển sâu; bị ức chế bởi **doxycycline liều cao** khi bệnh còn sớm (Nhiễm < 60). Kho khóa tầng 5 bệnh viện có **6 liều**. | BS Lam nói khi quan hệ ≥ thân thiện hoặc khi S1 hoàn thành; hoặc đọc hồ sơ phòng Lam (DC Trí tuệ 16). |
| C7 | BÍ MẬT | **Hắc** giữ **chiếc xuồng máy duy nhất còn chạy + 20 lít xăng** ở cảng. Hắn biết về tàu, định bán chỗ trên xuồng đổi vật tư, rồi lên tàu. | Thâm nhập L5, thương lượng với Hắc, hoặc Tú thú nhận (khi được hỏi về Bến Cá và quan hệ thân thiện). |
| C8 | BÍ MẬT | **Giếng nhà thờ nhiễm nhẹ.** Cha Phêrô biết từ 2 ngày trước Ngày 1, vẫn cho mọi người uống nước không đun để tránh hoảng loạn và tiết kiệm củi; riêng ông đun sôi nước của mình. | Thấy người trong giáo xứ đổ bệnh + điều tra giếng, hoặc chất vấn ông khi đã có bằng chứng. |
| C9 | CÓ THỂ KHÁM PHÁ | **Bão số 9** đổ bộ từ **18:00 Ngày 4 đến 12:00 Ngày 5**: gió cấp 10, mưa rất lớn, nước dâng. **Sáng Ngày 5 tàu không đón** (tạm ra khơi tránh bão), quay lại từ sáng Ngày 6. | Bản tin trạm khí tượng (L6); radio; Cha Phêrô có radio bán dẫn nghe được tin bão từ chiều Ngày 3. |
| C10 | BÍ MẬT | **Na miễn nhiễm** (chính em không biết). Máu của Na giúp BS Lam điều chế **huyết thanh** (3 liều, mỗi liều −40 Nhiễm, có tác dụng cả giai đoạn muộn). Điều chế cần **điện ≥ 6 giờ** cho máy ly tâm/tủ ấm (máy phát + nhiên liệu). | Quan sát Na tiếp xúc người bệnh/bùn mà không có triệu chứng (≥ 2 lần), rồi xét nghiệm của BS Lam. |
| C11 | CÓ THỂ KHÁM PHÁ | Trạm khí tượng có **máy phát hỏng nhẹ** (sửa: DC 16, kỹ năng Thợ điện +2) và **6 lít diesel** trong hầm. Máy phát mang theo được (nặng, Thể lực −15 cho mỗi chặng đi). 6 lít ≈ 8 giờ chạy. | Lục soát L6. |

---

## 4. NPC & PHE

### Phe
- **Giáo xứ Đông Hải** (L4, ~30 người): ban đầu trung lập; không nhận người có triệu chứng.
- **Bến Cá** (L5, ~12 người, gậy dao, 1 súng săn 3 viên): ban đầu trung lập–cảnh giác; giao dịch được, bạo lực nếu bị đe dọa.
- **Bệnh viện** (L3, BS Lam + 2 y tá + ~15 bệnh nhân): ban đầu trung lập.

### NPC
- **Nguyễn Văn Tú**, 38 tuổi, tài xế xe tải, ở cùng người chơi tại L1. **Thân thiện.**
  - Biết: tin đồn có tàu đón người ở "mũi phía bắc" (nghe từ người lạ, chưa rõ giờ giấc).
  - Che giấu: từng theo Bến Cá 3 ngày, đi cướp thức ăn; biết Hắc có xuồng (C7). Xấu hổ, chỉ nói khi được tin tưởng và hỏi thẳng.
  - Động cơ: đưa Na ra khỏi thành phố bằng mọi giá. **Sẽ phản bội người chơi nếu chỉ còn một chỗ cho Na.**
  - Diễn biến: trưa Ngày 3 Tú nhiễm (Nhiễm 35) sau một chuyến đi kiếm đồ một mình, nếu người chơi không đi cùng hoặc không ngăn.
- **Na**, 9 tuổi, con gái Tú. Ít nói, hay vẽ bằng than. **Thân thiện** (rụt rè). Miễn nhiễm (C10). Biết vẽ lại những gì em thấy, kể cả ánh đèn tàu ngoài khơi vào lúc rạng sáng.
- **BS Lam Thục**, 45 tuổi, bác sĩ truyền nhiễm. **Trung lập**, kiệt sức, thực dụng.
  - Biết C3, C6; nghi ngờ có người miễn nhiễm nhưng chưa tìm được ai.
  - Nói dối bệnh nhân rằng "cứu hộ sắp đến".
  - Cần: nước sạch hoặc clo, nhiên liệu/máy phát.
  - Diễn biến: Ngày 3 bắt đầu sốt (Nhiễm 50). Nếu không được giúp, cuối Ngày 6 kiệt sức nằm liệt → bệnh viện sụp đổ, H1 thất bại.
- **Cha Phêrô Vũ**, 62 tuổi, linh mục giáo xứ Đông Hải. **Trung lập.**
  - Che giấu C8. Có radio bán dẫn.
  - Động cơ: giữ trật tự, bảo vệ đàn chiên; sợ hoảng loạn hơn sợ bệnh.
  - Thu nhận người khỏe mạnh nếu họ chịu làm việc.
- **Lò Văn Hắc**, 34 tuổi, cựu bốc vác cảng, thủ lĩnh Bến Cá. **Trung lập–cảnh giác.**
  - Biết C4, C7. Nói dối "tàu cứu hộ không có thật" để giữ đàn em.
  - Thèm: thuốc men, nhiên liệu, người biết sửa máy.
  - Diễn biến: sáng Ngày 6 dùng xuồng ra tàu cùng người trả giá cao. Nếu đã thù địch với người chơi → cho người chặn đường L6–L7 từ Ngày 6.
- **Mạc**, 22 tuổi, đàn em của Hắc, đang nhiễm (Nhiễm 45), muốn phản Hắc để có thuốc. Có thể thành đồng minh hoặc nội gián.

---

## 5. NHÂN VẬT NGƯỜI CHƠI

- **Trần An**, 26 tuổi, thợ sửa điện dân dụng. Mất liên lạc với gia đình ở quê; sống sót nhờ trèo lên mái trường lúc sóng thần.
- **Chỉ số** (bổ trợ d20): Sức mạnh +1 · Nhanh nhẹn +1 · Trí tuệ +2 · Ý chí 0 · Giao tiếp 0 · Sinh tồn 0.
- **Kỹ năng**: Thợ điện (+2 khi sửa/vận hành thiết bị điện, máy phát, radio).
- **Dị năng**: không có (World không có dị năng).
- **Trạng thái đầu**: Máu 17/20 · Đói 45 · Khát 50 · Thể lực 60 · Nhiễm 8.
- **Thương tích đầu**: Vết xước cẳng chân trái (mức 1), chưa sát trùng, chưa băng → vết thương hở.
- **Túi đồ đầu**: Đèn pin (pin ~30%) ×1 · Dao rọc giấy ×1 · Chai nhựa 500ml (rỗng) ×1 · Khẩu trang vải ×1 · Bật lửa (≈5 lần) ×1 · Túi nylon ×2 · Bánh quy gói nhỏ ×1.

---

## 6. LUẬT SỐ (Level 5)

**Tiêu hao**
- Đói: +4/giờ khi thức, +2/giờ khi ngủ.
- Khát: +6/giờ (trời oi nóng +2; khi bão +0).
- Thể lực: hoạt động nặng (lội, leo, chiến đấu) −10/giờ; nhẹ −4/giờ; ngủ/nghỉ +10/giờ (+15 nếu ăn uống đủ).
- Đói/Khát ≥ 80: −5 Thể lực và −1 Máu mỗi giờ. Đói/Khát = 100: −2 Máu/giờ.
- Thể lực < 30: +2 DC thể chất. Thể lực < 10: +4 DC thể chất.

**Thương tích (Level 5 nặng hơn)**: mức 1 = −0 · mức 2 = +1 DC thể chất · mức 3 = +2, −1 Máu/6 giờ nếu chưa băng · mức 4 = +4, −1 Máu/2 giờ · mức 5 = bất động, −1 Máu/giờ.

**Ăn uống**
- Bánh quy gói nhỏ: −10 Đói.
- Mì gói ăn sống/nấu: −20 Đói.
- Cá mòi hộp: −25 Đói.
- 1 phần lương khô: −35 Đói.
- Cháo giáo xứ: −20 Đói, −5 Khát.
- 500ml nước: −20 Khát.

**Nhiễm — nguồn tăng**
- Lội bùn/nước ngập: +3/giờ (tính theo tỉ lệ thời gian); thêm +2/giờ nếu có vết thương hở chưa băng.
- Uống nước bẩn chưa xử lý: +15. Giếng nhà thờ: +6. Bồn nước mái L1: +5.
- Bụi bùn khô ngày gió mạnh: không khẩu trang +4/giờ; khẩu trang vải ướt +1/giờ; N95 +0.
- Tiếp xúc gần người ho đờm đen không khẩu trang: +5/lần.
- Bị người bệnh cắn/cào: +10 và thương tích mức 2.

**Nhiễm — tự tiến triển**: Nhiễm ≥ 30: +1 mỗi 2 giờ. Nhiễm ≥ 60: +1 mỗi giờ.

**Triệu chứng**
- 30–59: sốt nhẹ, +1 DC thể chất.
- 60–79: ho đờm đen, +2 DC mọi hành động; NPC khỏe mạnh nhận ra.
- 80–99: mê sảng từng cơn, +3 DC mọi hành động; mỗi 6 giờ phải tung Ý chí DC 16, thất bại → mất 1 giờ trong ảo giác.
- Chế độ ĐÓNG: Nhiễm 100 → **tử vong**.

**Nhiễm — giảm**
- Doxycycline: −15/liều, tối đa 1 liều/ngày, chỉ hiệu quả khi Nhiễm < 60; khi Nhiễm ≥ 60 chỉ chặn tự tiến triển 12 giờ.
- Huyết thanh (H1): −40/liều, hiệu quả mọi mức.
- Ngủ ≥ 8 giờ với Đói và Khát < 40: −2.
- Sát trùng + băng vết thương: hết trạng thái vết thương hở.

**Biến cố ngẫu nhiên**: tung d100 khi vào khu vực nguy hiểm Cao/Rất cao và mỗi 2 giờ ở ngoài trời; ban đêm cộng thêm 15 vào xác suất R1/R4.

---

## 7. VẬT PHẨM & TÀI NGUYÊN (khan hiếm cực cao)

- **L1 Trường**
  - Phòng y tế tầng 1 (ngập ngang gối, lội): 1 cuộn băng gạc, 1 chai cồn 70% 100ml (đủ sát trùng 3 lần). Tìm: DC Sinh tồn 16.
  - Căng tin: 2 gói mì trên kệ cao (DC 12 với ghế/leo).
  - Phòng thí nghiệm tầng 3: 1 đèn cồn + 200ml cồn đốt (đun sôi ~4 lần 500ml), 1 ca inox 500ml.
  - Bồn inox trên mái: ~20 lít nước mưa, nắp hở một phần.
- **L2 Chợ**
  - Gác xép nhà bà Sáu: 3kg gạo ẩm, 4 hộp cá mòi. Tìm: DC 16; Bến Cá lục soát định kỳ.
  - Tiệm thuốc Phúc An: 1 vỉ paracetamol (10 viên; giảm 1 DC do sốt trong 6 giờ, không giảm Nhiễm), 1 hộp Oresol 5 gói (mỗi gói −10 Khát khi pha với nước sạch, −5 Đói nếu Đói/Khát ≥ 80). Tìm: DC 16.
- **L3 Bệnh viện**
  - Kho khóa tầng 5: 6 liều doxycycline, 20 viên clo (mỗi viên xử lý 1 lít, 30 phút), 3 khẩu trang N95, 1 bộ khâu vết thương.
  - Mở kho: chìa khóa của BS Lam, hoặc phá khóa (DC 16, gây ồn → R1 chắc chắn xảy ra trong 1 giờ).
  - BS Lam có thể chữa thương tích nếu quan hệ ≥ trung lập và được trả công.
- **L4 Nhà thờ**: giếng (nhiễm nhẹ, xem C8); cháo 2 bữa/ngày cho thành viên (07:00, 17:00) nếu làm việc ≥ 4 giờ/ngày; củi.
- **L5 Cảng (kho Bến Cá)**: ~40 chai nước 500ml đóng kín, 15kg gạo, xuồng máy + 20 lít xăng, súng săn (3 viên, do Hắc giữ), 1 bộ đàm.
- **L6 Trạm khí tượng**: radio VHF (cần điện), máy phát hỏng nhẹ, 6 lít diesel (hầm), 2 thùng lương khô quân đội (mỗi thùng 6 phần), 1 áo mưa, sổ bản tin thời tiết.
- **L7 Mũi Đá Vôi**: không có vật tư.

---

## 8. NHIỆM VỤ

- **[CHÍNH] Rời Hòa Lộc**: lên được tàu Hải Đăng 09 tại L7 (05:30–06:30) trước hết sáng Ngày 7. Hiển thị ban đầu: "Sống sót và tìm đường rời Hòa Lộc"; cập nhật khi có tin về tàu.
  - Thất bại: hết 06:30 Ngày 7 mà chưa lên tàu, hoặc chết.
  - Lên tàu cần qua kiểm dịch C5 (Nhiễm < 40).
- **[PHỤ] S1 — Đôi bàn tay bác sĩ**: mang cho BS Lam ≥ 10 lít nước sạch, HOẶC máy phát chạy được + nhiên liệu.
  - Thưởng: quan hệ thân thiện, chìa khóa kho (được chia 3 liều doxycycline + 2 N95 + 10 viên clo), tiết lộ C6.
  - Thất bại: BS Lam gục (cuối Ngày 6).
- **[PHỤ] S2 — Giếng thánh**: phát hiện C8 và thuyết phục Cha Phêrô đun nước/dùng clo trước 12:00 Ngày 5.
  - Thưởng: Giáo xứ thân thiện, được ở lâu dài, Cha Phêrô cho mượn radio bán dẫn.
  - Thất bại: biến cố E-d.
- **[PHỤ] S3 — Không ai bị bỏ lại**: đưa Na (và Tú nếu còn sống, Nhiễm < 40) lên tàu.
  - Thất bại: Na chết hoặc bị bỏ lại khi tàu rời Ngày 7.
- **[ẨN] H1 — Dòng máu của Na**: phát hiện C10, đưa Na và nguồn điện ≥ 6 giờ đến BS Lam (Lam còn đứng được) → nhận 3 liều huyết thanh + mẫu chủng. Thời hạn: trước 06:30 Ngày 7 nếu muốn mang lên tàu; hoặc truyền công thức qua radio L6 cho tàu.
- **[ẨN] H2 — Kênh 16**: sửa máy phát tại L6, gọi tàu.
  - Thưởng: xác minh C4, tiết lộ C5; tàu đồng ý gửi xuồng đến L5 một lần lúc 06:00 ngày kế tiếp (cảng do Bến Cá kiểm soát → phải xử lý Hắc).

---

## 9. BIẾN CỐ

### Ngẫu nhiên (d100)

| Kết quả | Biến cố |
|---|---|
| 01–15 | **R1** Người sốt giai đoạn cuối lảng vảng, hung hãn (đêm 01–30). |
| 16–25 | **R2** Đội tuần Bến Cá 2–3 người (tại L2/L5: 16–40). |
| 26–35 | **R3** Dư chấn — DC Nhanh nhẹn 16, thất bại: thương tích mức 2. |
| 36–45 | **R4** Đàn chó hoang (chỉ ban đêm; ban ngày coi như R9). |
| 46–55 | **R5** Gió giật cuốn bụi bùn khô (áp dụng luật bụi 1 giờ). |
| 56–63 | **R6** Người lạ cần giúp (tung d2: 1 thật, 2 là bẫy). |
| 64–70 | **R7** Nước dâng bất ngờ (gần L2/L5; nơi khác coi như R9). |
| 71–75 | **R8** Vật tư nhỏ (d3: 1 chai nước kín 500ml, 2 hộp đồ ăn −20 Đói, 3 pin AA ×2). |
| 76–100 | **R9** Không có gì. |

### Có điều kiện
- **E-a**: 20:00 Ngày 2, Bến Cá lục soát L1. Ai ở đó gặp R2 chắc chắn; đồ để lại tầng 3 bị lấy 50%.
- **E-b**: Ngày 3, BS Lam bắt đầu sốt; cuối Ngày 6 gục nếu S1 chưa xong.
- **E-c**: Bão số 9 từ 18:00 Ngày 4 đến 12:00 Ngày 5. Sáng Ngày 5 tàu không đón. Đường L4–L6 DC 20. Ngoài trời: −10 Thể lực/giờ thêm.
- **E-d**: 12:00 Ngày 5, nếu S2 chưa xong → 6 người giáo xứ đổ bệnh, nhà thờ đóng cửa với người ngoài, quan hệ giáo xứ không còn tăng được.
- **E-e**: 05:00 Ngày 6, Hắc ra tàu bằng xuồng. Nếu thù địch với người chơi → chặn đường L6–L7 từ Ngày 6 (2 người, 1 súng săn).
- **E-f**: trưa Ngày 3, Tú nhiễm (Nhiễm 35) nếu đi kiếm đồ một mình (mặc định có, trừ khi người chơi đi cùng/ngăn cản/đã đưa cha con Tú đến nơi an toàn).

---

## 10. KẾT CỤC

| Mã | Loại | Tên | Điều kiện | Hoàn thành World? |
|---|---|---|---|---|
| E1 | THẮNG | Rời bến | Lên tàu (Nhiễm < 40) trước hạn. | ✔ |
| E1+ | THẮNG TRỌN | Không ai bị bỏ lại | E1 + hoàn thành S3 + ít nhất 1 trong S1/S2. | ✔ |
| E2 | THẮNG (tốt nhất) | Ánh đèn bệnh viện | Hoàn thành H1 và mang huyết thanh/mẫu chủng lên tàu hoặc truyền công thức cho tàu qua radio; người chơi còn sống. | ✔ |
| E3 | THẮNG MỘT PHẦN | Ở lại | Không lên tàu nhưng sống sót đến 23:59 Ngày 10. | ✘ |
| E4 | THUA | Bùn đen | Tử vong (Máu = 0 hoặc Nhiễm = 100). | ✘ |
| E5 | THUA | Cánh cửa đóng | Bị từ chối tại kiểm dịch và hết hạn Ngày 7 mà không có đường khác, rồi chết trước Ngày 10. | ✘ |

---

## 11. TỬ VONG & HỒI SINH

- Máu = 0 hoặc Nhiễm = 100 → chết hoàn toàn.
- Cơ chế hồi sinh: **không có**.

---

## 12. CHECKPOINT (Level 5 — rất hiếm)

- **CP0**: Điểm xuất phát (Ngày 1, 06:10, L1).
- **Tối đa 3 checkpoint khác, mỗi loại 1 lần**:
  1. Lần đầu được Giáo xứ thu nhận.
  2. Hoàn thành nhiệm vụ phụ đầu tiên.
  3. Liên lạc được với tàu qua radio (H2).

---

## 13. TỰ KIỂM ĐỊNH

- [x] Đủ 11 phần.
- [x] Không mâu thuẫn: chế độ ĐÓNG ↔ người bệnh không biến đổi; C9 ↔ E-c thống nhất giờ.
- [x] Đường thắng tối thiểu tồn tại: L1 → L2 (0:40) → L4 (1:00) → L6 (2:00) → L7 (2:00) ≈ 6 giờ. Nhiễm phát sinh ước tính +5..+10 nếu băng vết thương và đeo khẩu trang → dưới 40 khả thi. Lối dự phòng: H2 + xuồng tại L5.
- [x] Không vòng phụ thuộc: H1 cần điện (L6) và Lam (L3) — độc lập với tàu; S1 có 2 cách hoàn thành.
- [x] Khan hiếm khớp Level 5: túi đồ đầu tối thiểu, nước sạch hữu hạn.
- [x] World đầu tiên trong cuộc trò chuyện.
