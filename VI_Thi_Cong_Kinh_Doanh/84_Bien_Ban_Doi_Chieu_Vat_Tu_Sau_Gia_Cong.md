# BIÊN BẢN ĐỐI CHIẾU VẬT TƯ SAU GIA CÔNG VÀ BỘ HỒ SƠ QUẢN LÝ GIA CÔNG NGOÀI
### QUẢN LÝ NGUYÊN VẬT LIỆU, ĐỊNH MỨC HAO HỤT VÀ NGHIỆM THU CHẤT LƯỢNG CHẾ TẠO CẤU KIỆN KẾT CẤU THÉP
*(Áp dụng cho các dự án/công trình Công ty thuê gia công chế tạo cấu kiện, chi tiết cơ khí bên ngoài)*

| THÔNG TIN QUẢN TRỊ | NỘI DUNG CHI TIẾT |
|:---|:---|
| **Đơn vị ban hành** | `<<CTY_TEN>>` |
| **Mã văn bản** | **D1-84** (Biểu mẫu thực thi nghiệp vụ – STT 84 trong Danh mục lưu hành) |
| **Phiên bản** | **1.0** |
| **Công trình / Dự án áp dụng** | `<<CT_TEN>>` (Mã công trình: `<<CT_MA>>` – Địa điểm: `<<CT_DIA_DIEM>>`) |
| **Bên giao gia công (Công ty)** | `<<CTY_TEN>>` (Mã số thuế: `<<CTY_MST>>`) |
| **Bên nhận gia công (Xưởng GC)** | `<<XUONG_GC_TEN>>` (Mã số thuế: `<<XUONG_GC_MST>>`) |
| **Căn cứ Hợp đồng dịch vụ GC** | Hợp đồng số: `<<GC_HD_SO>>` ký ngày `<<GC_HD_NGAY>>` |

---

## PHẦN I. HƯỚNG DẪN QUẢN TRỊ RỦI RO & CHỨNG TỪ THUẾ KHI THUÊ GIA CÔNG NGOÀI

### 1. Bản chất pháp lý: Hợp đồng dịch vụ gia công vs Hợp đồng mua bán hàng hóa (Phòng tránh rủi ro Thuế GTGT 2 đầu)
1. **Bản chất pháp lý cốt lõi:**
   - Căn cứ quy định từ Điều 542 đến Điều 553 Bộ luật Dân sự số 91/2015/QH13 và Mục 5 Chương VI Luật Thương mại số 36/2005/QH11: Hợp đồng gia công là hợp đồng dịch vụ, theo đó `<<CTY_TEN>>` (Bên đặt gia công) giao toàn bộ hoặc một phần phôi/nguyên vật liệu (thép tấm, thép hình, thép xà gồ, sơn, que hàn...) cho `<<XUONG_GC_TEN>>` (Bên nhận gia công) để thực hiện công việc chế tạo ra sản phẩm hoàn chỉnh (cột thép, dầm thép, vì kèo, giằng, chi tiết bản mã...) theo đúng bản vẽ thiết kế gia công (Shop Drawing) và yêu cầu kỹ thuật đã duyệt.
   - **Quyền sở hữu tài sản:** Toàn bộ nguyên vật liệu, phôi thép và thành phẩm tạo thành trong suốt quá trình gia công luôn thuộc quyền sở hữu hợp pháp của `<<CTY_TEN>>`. Bên nhận gia công chỉ nắm giữ tài sản theo quan hệ nhận ủy thác công việc và quản lý kỹ thuật, không có quyền định đoạt, chuyển nhượng hoặc cầm cố tài sản.
2. **Rủi ro bị ấn định thuế Mua – Bán 2 đầu và giải pháp tuân thủ:**
   - *Rủi ro nghiêm trọng:* Nếu Công ty xuất hóa đơn GTGT bán phôi thép cho xưởng gia công, sau đó xưởng gia công xuất lại hóa đơn GTGT bán thành phẩm kết cấu thép cho Công ty: Giao dịch này sẽ bị cơ quan Thuế thanh tra xem xét là mua bán lòng vòng, làm phình to doanh thu ảo, phát sinh rủi ro thuế GTGT 2 đầu (đặc biệt khi có chênh lệch thời điểm kê khai hoặc thuế suất), đồng thời có nguy cơ bị từ chối khấu trừ thuế nếu đối tác gia công thuộc danh sách rủi ro hóa đơn.
   - *Chuẩn mực chứng từ điều động vật tư:* Khi xuất phôi thép/vật tư cho xưởng gia công, Phòng Kế toán và Ban Điều hành Dự án lập **Lệnh điều động nội bộ** kèm **Phiếu xuất kho kiêm vận chuyển nội bộ** (hoặc Phiếu xuất kho giao hàng gia công theo đúng quy định Luật Quản lý Thuế và Nghị định về hóa đơn, chứng từ). Tuyệt đối không xuất hóa đơn thương mại bán vật tư cho đơn vị gia công.
   - *Yêu cầu đối với hóa đơn đầu vào của Bên nhận gia công:*
     + Khi hoàn thành công việc và được nghiệm thu, Bên nhận gia công chỉ được phép phát hành **Hóa đơn GTGT cung cấp dịch vụ gia công cơ khí cấu kiện thép** (nội dung thể hiện tiền công cắt, gá, hàn, nắn, làm sạch bề mặt, sơn phủ bảo vệ...);
     + Tuyệt đối **không xuất hóa đơn bán thành phẩm kết cấu thép** bao gồm cả giá trị nguyên liệu phôi thép do `<<CTY_TEN>>` cung cấp.
3. **Bộ hồ sơ quyết toán thuế dịch vụ gia công hợp lệ bắt buộc gồm:**
   - [ ] Hợp đồng dịch vụ gia công số `<<GC_HD_SO>>` (kèm dự toán chi tiết đơn giá gia công, bảng quy định định mức tiêu hao, hao hụt kỹ thuật);
   - [ ] Bản vẽ gia công chế tạo (Shop Drawing) đã được Kỹ sư `<<CTY_TEN>>` và Tư vấn giám sát/Tổng thầu phê duyệt;
   - [ ] Biên bản giao nhận phôi/vật tư cho xưởng gia công (Mẫu `D1-84/BM-01`);
   - [ ] Biên bản nghiệm thu kỹ thuật thành phẩm tại xưởng gia công - Factory QC (Mẫu `D1-84/BM-02`);
   - [ ] Biên bản đối chiếu và quyết toán vật tư sau gia công (Mẫu `D1-84/BM-03`);
   - [ ] Biên bản bàn giao & xử lý vật tư thừa, phế liệu thu hồi (Mẫu `D1-84/BM-04`);
   - [ ] Hóa đơn điện tử GTGT tiền công gia công hợp pháp do `<<XUONG_GC_TEN>>` xuất;
   - [ ] Chứng từ thanh toán không dùng tiền mặt (Ủy nhiệm chi ngân hàng) qua tài khoản đã đăng ký của Bên nhận gia công.

---

### 2. Kiểm soát định mức hao hụt kỹ thuật và nguyên tắc bồi hoàn hao hụt vượt định mức
1. **Kiểm soát định mức hao hụt kỹ thuật:**
   - Trong quá trình chế tạo cơ khí kết cấu thép, việc cắt tôn bản mã, cắt thép hình, vát mép đường hàn, gọt đầu dầm, đột/khoan lỗ bu lông luôn phát sinh hao hụt kỹ thuật tự nhiên (đầu mẩu vụn, ba-vớ, phoi tiện/khoan, xỉ hàn, bụi phun sơn...).
   - Trước khi giao phôi, Phòng Kỹ thuật dự án của `<<CTY_TEN>>` phối hợp cùng Đơn vị gia công thẩm tra sơ đồ cắt phôi (Cutting Plan / Nesting Plan) để xác định định mức hao hụt kỹ thuật chuẩn cho từng chủng loại kết cấu thép:
     + Thép tấm tổ hợp dầm, cột (cắt CNC plasma/gas): Tỷ lệ hao hụt kỹ thuật tối đa từ **2,0% – 3,5%**;
     + Thép hình đúc (I, H, U, V) cắt theo chiều dài modul: Tỷ lệ hao hụt tối đa từ **1,0% – 2,0%**;
     + Thép xà gồ mạ kẽm (C, Z) cắt và đột lỗ tự động: Tỷ lệ hao hụt tối đa từ **0,5% – 1,0%**;
     + Bản mã, sườn tăng cường, chi tiết liên kết nhỏ: Tỷ lệ hao hụt kỹ thuật từ **2,5% – 4,0%**;
     + Sơn chống rỉ và sơn phủ hoàn thiện: Tỷ lệ hao hụt phun sơn kỹ thuật (tàn sơn bay trong không khí) từ **20% – 35%** tùy theo phương pháp phun sơn chân không (Airless Spray) hoặc phun khí nén.
2. **Nguyên tắc xử lý và bồi hoàn hao hụt vượt định mức:**
   - **Hao hụt trong định mức:** Khối lượng hao hụt kỹ thuật thực tế $\le$ Tỷ lệ định mức quy định tại Hợp đồng được Công ty chấp nhận đưa vào chi phí sản xuất hợp lý của dự án `<<CT_TEN>>`.
   - **Hao hụt vượt định mức:** Toàn bộ khối lượng vật tư hao hụt vượt định mức do lỗi của Đơn vị gia công (như cắt sai sơ đồ nesting, hàn cháy thủng cấu kiện, hư hỏng trong quá trình nắn biến dạng, phôi bị rỉ sét do bảo quản kém tại xưởng...) thì **Bên nhận gia công phải chịu trách nhiệm bồi thường 100% giá trị vật tư hao hụt vượt định mức**.
   - **Đơn giá tính bồi hoàn:** Đơn giá bồi hoàn là giá mua vào thực tế của `<<CTY_TEN>>` theo hóa đơn VAT mua vật tư cộng thêm chi phí vận chuyển, bốc xếp đến xưởng gia công; hoặc tính theo đơn giá thép thị trường tại thời điểm quyết toán nếu đơn giá thị trường cao hơn. Khoản bồi thường này được tự động khấu trừ trực tiếp vào giá trị tiền công gia công khi làm thủ tục thanh toán.
   - **Quyền sở hữu đối với phoi thừa và phế liệu:** Toàn bộ thép tấm/thép hình thừa nguyên dạng có thể tái sử dụng (kích thước lớn) và phế liệu phát sinh (đầu mẩu, phoi kim loại) đều thuộc tài sản của `<<CTY_TEN>>`. Bên gia công không được tự ý đem bán hoặc tiêu hủy khi chưa có Biên bản xử lý vật tư thừa (Mẫu `D1-84/BM-04`).

---

### 3. Quy tắc 3 bên khi xuất giao hàng thẳng từ xưởng gia công ra công trường dự án
Khi cấu kiện kết cấu thép sau khi hoàn thiện được chuyển thẳng từ xưởng gia công của `<<XUONG_GC_TEN>>` đến mặt bằng công trình `<<CT_TEN>>` (không qua kho trung chuyển của Công ty), các bên bắt buộc phải tuân thủ nghiêm ngặt **Quy tắc phối hợp 3 bên** nhằm ngăn chặn rủi ro thất thoát hàng hóa, sai lệch quy cách và tranh chấp khuyết tật hư hỏng:

```
[BÊN 1: XƯỞNG GIA CÔNG]
  - Quản đốc & QC Xưởng
  - Đóng gói, gối chèn, niêm phong
  - Lập Packing List & Phiếu xuất xưởng
          │
          ▼
[BÊN 2: KỸ SƯ GIÁM SÁT KỸ THUẬT / QC CÔNG TY (<<CTY_TEN>>)]
  - Nghiệm thu xuất xưởng tại xưởng (Factory QC - Mẫu BM-02)
  - Kiểm tra tem mác, số hiệu cấu kiện, ký xuất xưởng
          │
          ▼  (Vận chuyển trực tiếp ra Công trình <<CT_TEN>>)
[BÊN 3: BAN CHỈ HUY / THỦ KHO CÔNG TRƯỜNG (<<CTY_TEN>>)]
  - Kiểm tra đối chiếu số hiệu cấu kiện, quy cách trên xe
  - Kiểm tra ngoại quan: độ trầy xước sơn, biến dạng va đập khi vận chuyển
  - Ký nhận Biên bản giao nhận tại hiện trường công trình (Mẫu D1-68)
```

1. **Trách nhiệm của Bên 1 (Đại diện Xưởng gia công – `<<XUONG_GC_TEN>>`):**
   - Đảm bảo 100% cấu kiện đã được KCS xưởng tự nghiệm thu đạt chuẩn trước khi mời Kỹ sư `<<CTY_TEN>>` đến kiểm tra;
   - Đánh dấu số hiệu cấu kiện (Marking code) rõ ràng, sơn ký hiệu theo đúng bản vẽ lắp dựng;
   - Bố trí xe cẩu, kê lót gỗ đệm cao su và chằng buộc bằng cáp siết có tăng đơ chuyên dụng, tuyệt đối không để cấu kiện va đập làm xước sơn, biến dạng mép cánh hoặc vặn xoắn trong quá trình vận chuyển;
   - Cung cấp đầy đủ Phiếu xuất xưởng, Bảng kê chi tiết kiện hàng (Packing List) và chứng chỉ phôi/vật liệu cho tài xế mang theo xe.
2. **Trách nhiệm của Bên 2 (Kỹ sư giám sát kỹ thuật / QC của `<<CTY_TEN>>`):**
   - Tiến hành kiểm tra kích thước hình học, độ phẳng, đường hàn và màng sơn bảo vệ trực tiếp tại xưởng theo quy định của Tiêu chuẩn TCVN 170:2007;
   - Lập và ký Biên bản nghiệm thu kỹ thuật thành phẩm tại xưởng (Mẫu `D1-84/BM-02`). Chỉ những cấu kiện được Kỹ sư QC ký xác nhận đạt chuẩn mới được phép bốc xếp lên phương tiện vận chuyển;
   - Giám sát quy cách chằng buộc, kê gối trên thùng xe trước khi xe lăn bánh rời xưởng.
3. **Trách nhiệm của Bên 3 (Chỉ huy trưởng / Kỹ sư hiện trường / Thủ kho tại công trường `<<CT_TEN>>`):**
   - Tiếp nhận xe hàng tại công trường, kiểm tra đối chiếu biển số xe, số hiệu cấu kiện thực tế trên xe so với Packing List và Biên bản nghiệm thu xưởng (BM-02);
   - Kiểm tra ngoại quan 100% cấu kiện **ngay khi còn trên thùng xe tải**: Kiểm tra các điểm móc cẩu, độ cong vênh phát sinh do chở nặng hoặc va đập trên đường, trầy xước màng sơn;
   - Nếu phát hiện hư hỏng, cong vênh hoặc thiếu số lượng: Lập Biên bản ghi nhận hiện trạng tại chỗ có chữ ký của Tài xế vận chuyển và Đại diện xưởng, yêu cầu xưởng cử thợ đến dặm vá sơn, nắn chỉnh lại ngay tại công trường hoặc đổi trả cấu kiện mới. Tuyệt đối không ký nhận hàng lành lặn nếu hiện trạng bị cong vênh trầy xước;
   - Ký xác nhận vào Biên bản giao nhận vật tư tại hiện trường (Biểu mẫu D1-68) và lưu hồ sơ quản lý công trình.

---

## PHẦN II. BIỂU MẪU SỐ 01: BIÊN BẢN GIAO NHẬN VẬT TƯ / PHÔI CHO ĐƠN VỊ GIA CÔNG

<center>

### CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
**Độc lập – Tự do – Hạnh phúc**

---

**DỰ ÁN / CÔNG TRÌNH:** `<<CT_TEN>>` (MÃ CT: `<<CT_MA>>`)  
**Số văn bản:** `......./BBGN-PHOI/<<CT_MA>>-<<VB_NAM>>`  
*Hôm nay, ngày ..... tháng ..... năm 20..., tại kho / bãi tập kết vật tư của `<<CTY_TEN>>` (hoặc tại xưởng gia công), chúng tôi gồm có:*

</center>

### 1. ĐẠI DIỆN BÊN GIAO PHÔI (Bên đặt gia công – `<<CTY_TEN>>`):
- Ông/Bà: ................................................................ Chức vụ: Kỹ sư Quản lý Vật tư / Dự án
- Ông/Bà: ................................................................ Chức vụ: Kỹ sư Giám sát Kỹ thuật / QC
- Ông/Bà: ................................................................ Chức vụ: Thủ kho Công ty
- Căn cứ Lệnh điều động / Phiếu xuất kho nội bộ số: ................................ ngày ...../...../20...

### 2. ĐẠI DIỆN BÊN NHẬN PHÔI (Bên nhận gia công – `<<XUONG_GC_TEN>>`):
- Ông/Bà: ................................................................ Chức vụ: Quản đốc Xưởng gia công
- Ông/Bà: ................................................................ Chức vụ: Kỹ sư KCS / Kỹ thuật xưởng
- Ông/Bà: ................................................................ Chức vụ: Thủ kho Xưởng gia công
- Phương tiện vận chuyển (Biển số xe cẩu/xe tải): ................................. Họ tên lái xe: .................................

Hai bên tiến hành kiểm tra ngoại quan, đo đạc quy cách hình học và bàn giao chi tiết lô vật tư, phôi thép phục vụ gia công chế tạo cấu kiện công trình `<<CT_TEN>>` theo Hợp đồng số `<<GC_HD_SO>>` như sau:

### 3. BẢNG CHI TIẾT DANH MỤC PHÔI / VẬT TƯ GIAO CHO XƯỞNG:

| STT | Tên quy cách chủng loại phôi / vật tư | Mác thép / Tiêu chuẩn kỹ thuật | Kích thước hình học phôi *(Dài x Rộng x Dày mm)* | ĐVT | Số lượng giao | Khối lượng lý thuyết *(Kg)* | Khối lượng cân thực tế *(Kg)* | Chứng chỉ chất lượng kèm theo *(CO, CQ, Mill Test)* | Tình trạng bề mặt & Ngoại quan ban đầu | Mục đích gia công chế tạo |
|:---:|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---|---|
| 1 | Thép tấm kiện `t = 12mm` | SS400 (JIS G3101) | $1.500 \times 6.000 \times 12$ | Tấm | | | | ☐ Đủ CO/CQ số: ............ | ☐ Phẳng, rỉ bề mặt cấp A, không nứt rỗ | Cắt bản cánh dầm dốc Kèo K1 |
| 2 | Thép tấm kiện `t = 16mm` | Q355B (GB/T 1591) | $2.000 \times 8.000 \times 16$ | Tấm | | | | ☐ Đủ CO/CQ số: ............ | ☐ Phẳng, bề mặt sạch dầu mỡ, không tách lớp | Cắt bản bụng Cột chữ H |
| 3 | Thép tấm bản mã `t = 20mm` | SS400 / Q345B | $1.500 \times 6.000 \times 20$ | Tấm | | | | ☐ Đủ CO/CQ số: ............ | ☐ Mới 100%, không rỗ nứt mép | Cắt mặt bích chân cột, nối kèo |
| 4 | Thép hình đúc chữ H `H300` | SS400 | $H300 \times 150 \times 6.5 \times 9 \times 12m$ | Cây | | | | ☐ Đủ Mill Test số: .......... | ☐ Thẳng, không vặn xoắn, không gỉ sâu | Cắt gá dầm sàn tầng lửng |
| 5 | Thép xà gồ phôi Z200 | Mạ kẽm Z275, G450 | Cuộn dải $W=420mm$, $t=2.0mm$ | Cuộn / Kg | | | | ☐ Đủ CO/CQ số: ............ | ☐ Bề mặt sáng bóng, không đọng ố trắng | Cán xà gồ mái Z200 và đột lỗ |
| 6 | Thép góc đều cạnh L75x6 | SS400 | $L75 \times 75 \times 6 \times 6m$ | Cây | | | | ☐ Đủ CO/CQ số: ............ | ☐ Thẳng đều, không gãy góc | Thanh giằng xà gồ, giằng cột |
| 7 | Que hàn / Dây hàn hồ quang | E71T-1C / E7018 | $\phi 1.2mm$ / $\phi 3.2mm$ | Cuộn / Hộp | | | | ☐ Đủ CO/CQ nhà sản xuất | ☐ Bao bì nguyên vẹn, thuốc bọc khô ráo | Hàn tổ hợp cấu kiện |
| 8 | Sơn chống rỉ lót Epoxy | Gốc nhựa Polyamide | Thùng 20 lít (Màu ghi) | Thùng | | | | ☐ Đủ CO/CQ, HSD đạt chuẩn | ☐ Thùng nguyên niêm phong nhà máy | Sơn lót cấu kiện tại xưởng |

### 4. GHI NHẬN TÌNH TRẠNG VÀ TRÁCH NHIỆM BẢO QUẢN:
1. **Kiểm tra ngoại quan và chứng từ đi kèm:**
   - Toàn bộ lô phôi thép và vật tư giao nhận nêu trên có đầy đủ chứng chỉ xuất xứ (CO), chứng chỉ chất lượng nhà máy (CQ/Mill Test).
   - Ngoại quan ban đầu: Đạt yêu cầu tiêu chuẩn chế tạo. Các trường hợp phôi có khuyết tật nhẹ đã được hai bên đánh dấu riêng tại biên bản: .....................................................................................................................................................................................................
2. **Trách nhiệm của Bên nhận gia công (`<<XUONG_GC_TEN>>`):**
   - Kể từ thời điểm ký biên bản này, Bên nhận gia công chịu hoàn toàn trách nhiệm pháp lý và vật chất đối với việc trông coi, bảo quản, lưu kho bãi đúng quy chuẩn (kê cao cách mặt đất tối thiểu 20cm, che phủ bạt chống mưa, phân loại theo mác thép và chiều dày để tránh nhầm lẫn);
   - Không được sử dụng phôi thép của `<<CTY_TEN>>` cho bất kỳ mục đích nào khác ngoài phạm vi thực hiện hợp đồng gia công số `<<GC_HD_SO>>`;
   - Chịu trách nhiệm bồi thường nếu để xảy ra mất mát, biến dạng hoặc hư hỏng rỉ sét trong quá trình lưu kho tại xưởng.

---

### CHỮ KÝ XÁC NHẬN CÁC BÊN GIAO NHẬN

| ĐẠI DIỆN THỦ KHO CÔNG TY | KỸ SƯ QUẢN LÝ VẬT TƯ / QC | ĐẠI DIỆN THỦ KHO XƯỞNG GC | QUẢN ĐỐC XƯỞNG GIA CÔNG |
|:---:|:---:|:---:|:---:|
| *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, đóng dấu xưởng)* |
| <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> |
| Họ tên: ....................................... | Họ tên: ....................................... | Họ tên: ....................................... | **`<<XUONG_GC_DAI_DIEN>>`** |

---

## PHẦN III. BIỂU MẪU SỐ 02: BIÊN BẢN NGHIỆM THU KỸ THUẬT THÀNH PHẨM TẠI XƯỞNG GIA CÔNG (FACTORY QC)

<center>

### CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
**Độc lập – Tự do – Hạnh phúc**

---

**DỰ ÁN / CÔNG TRÌNH:** `<<CT_TEN>>` (MÃ CT: `<<CT_MA>>`)  
**Số văn bản:** `......./BBNT-QC-XUONG/<<CT_MA>>-<<VB_NAM>>`  
*Hôm nay, ngày ..... tháng ..... năm 20..., tại Nhà xưởng gia công của `<<XUONG_GC_TEN>>` (Địa chỉ: `<<XUONG_GC_DIA_CHI_XUONG>>`), chúng tôi gồm có:*

</center>

### 1. ĐẠI DIỆN BÊN GIAO GIA CÔNG (`<<CTY_TEN>>`):
- Ông/Bà: ................................................................ Chức vụ: Kỹ sư Giám sát Chất lượng (KCS/QC)
- Ông/Bà: ................................................................ Chức vụ: Trưởng phòng Kỹ thuật / Chỉ huy trưởng
- Ông/Bà: `<<CT_CHI_HUY_TRUONG>>` ................ Chức vụ: Chỉ huy trưởng công trình

### 2. ĐẠI DIỆN BÊN NHẬN GIA CÔNG (`<<XUONG_GC_TEN>>`):
- Ông/Bà: `<<XUONG_GC_DAI_DIEN>>` ................ Chức vụ: Giám đốc xưởng / Quản đốc xưởng
- Ông/Bà: ................................................................ Chức vụ: Trưởng bộ phận KCS/QC Xưởng
- Ông/Bà: ................................................................ Chức vụ: Đội trưởng Tổ gá hàn / Sơn

### 3. CĂN CỨ TIÊU CHUẨN KỸ THUẬT VÀ TÀI LIỆU NGHIỆM THU:
- *Căn cứ Hợp đồng dịch vụ gia công số `<<GC_HD_SO>>` ngày `<<GC_HD_NGAY>>`;*
- *Căn cứ Bản vẽ thiết kế gia công nhà xưởng (Shop Drawing) số: `................................` được duyệt;*
- *Căn cứ Tiêu chuẩn Quốc gia **TCVN 170:2007**: Kết cấu thép – Gia công, lắp ráp và nghiệm thu – Yêu cầu kỹ thuật;*
- *Căn cứ Tiêu chuẩn Quốc gia **TCVN 5575:2024 / TCVN 5575:2012**: Thiết kế kết cấu thép;*
- *Căn cứ Tiêu chuẩn Quốc gia **TCVN 9259-8:2012** và **TCVN 11344:2016** về kiểm tra không phá hủy mối hàn (NDT);*
- *Căn cứ Tiêu chuẩn Quốc gia **TCVN 8789:2011 / TCVN 8790:2011**: Sơn bảo vệ kết cấu thép – Phương pháp thử.*

Hai bên cùng tiến hành đo kiểm thực tế các thông số kỹ thuật của lô cấu kiện hoàn thiện trước khi cho phép xuất xưởng ra công trường:

### 4. BẢNG CHI TIẾT ĐO KIỂM KỸ THUẬT CẤU KIỆN TẠI XƯỞNG:

| STT | Ký hiệu mã cấu kiện | Tên cấu kiện & Tiết diện thiết kế *(mm)* | ĐVT | Số lượng kiểm tra | Kích thước hình học & Dung sai theo TCVN 170:2007 *(Dài, Rộng, Cao, Tim lỗ)* | Độ thẳng, độ phẳng bản mã & Độ võng cánh/bụng dầm | Chất lượng mối hàn tổ hợp *(Ngoại quan & Siêu âm UT)* | Chiều dày màng sơn khô trung bình DFT *($\mu m$)* | Đánh giá phân loại *(Đạt / Sửa lại / Hủy)* |
|:---:|---|---|:---:|:---:|---|---|---|:---:|:---:|
| 1 | Cột `C1` đến `C6` | Cột thép tổ hợp $H(600 \sim 300) \times 250 \times 10 \times 16$; $L=9.500mm$ | Cấu kiện | 06 | ☐ Chiều dài sai số: $\le \pm 3mm$ <br> ☐ Tiết diện: $\le \pm 2mm$ <br> ☐ Tim lỗ bu lông móng: $\le \pm 1.5mm$ | ☐ Độ lệch tâm: $< 3mm$ <br> ☐ Bản mã chân cột phẳng <br> ☐ Không cong vênh cánh | ☐ Mối hàn ngấu đều, không rỗ khí <br> ☐ Đã siêu âm UT 100% đường nối cánh, bụng đạt cấp II | Lớp lót: $65\mu m$ <br> Lớp phủ: $60\mu m$ <br> *(Tổng DFT: $125\mu m$)* | **ĐẠT XUẤT XƯỞNG** |
| 2 | Kèo `K1` đến `K4` | Vì kèo mái dốc $H(700 \sim 400) \times 200 \times 8 \times 12$; $L=12.000mm$ | Cấu kiện | 04 | ☐ Chiều dài sai số: $\le \pm 4mm$ <br> ☐ Góc dốc đỉnh kèo: Đúng bản vẽ | ☐ Độ cong phẳng: $< L/1000$ <br> ☐ Bản bích liên kết chuẩn | ☐ Mối hàn giáp mối đạt chuẩn <br> ☐ Không cháy chân, vát mép đúng | Lớp lót: $60\mu m$ <br> Lớp phủ: $65\mu m$ <br> *(Tổng DFT: $125\mu m$)* | **ĐẠT XUẤT XƯỞNG** |
| 3 | Dầm sàn `B1-B8` | Thép hình đúc $I300 \times 150 \times 6.5 \times 9$; $L=6.000mm$ | Cấu kiện | 08 | ☐ Cắt đúng kích thước $\pm 2mm$ <br> ☐ Khoan lỗ đột tròn đều | ☐ Cây thẳng, không võng xoắn | ☐ Đường hàn bản mã dầm kín khít | Lớp lót: $60\mu m$ <br> Lớp phủ: $60\mu m$ | **ĐẠT XUẤT XƯỞNG** |
| 4 | Xà gồ `Z200` | Xà gồ mạ kẽm $Z200 \times 65 \times 20 \times 2.0$; $L=6.500mm$ | Cây | 120 | ☐ Chiều dài $\pm 3mm$ <br> ☐ Lỗ đột Oval đúng cữ tim | ☐ Cạnh thẳng góc, không móp | Phôi mạ kẽm nguội | Lớp mạ kẽm gốc $Z275 \ge 20\mu m$ | **ĐẠT XUẤT XƯỞNG** |
| 5 | Hệ giằng cáp, giằng góc | Giằng góc $L75 \times 75 \times 6$ kèm bản mã tai giằng | Bộ | 16 | ☐ Kích thước bản mã đạt | ☐ Phẳng, vát mép ba-vớ | ☐ Hàn kín liên tục bản mã | Lớp lót: $60\mu m$ <br> Lớp phủ: $60\mu m$ | **ĐẠT XUẤT XƯỞNG** |

### 5. GHI NHẬN CÁC SAI LỆCH VÀ YÊU CẦU XỬ LÝ KHẮC PHỤC (NẾU CÓ):
1. **Các cấu kiện chưa đạt yêu cầu kiểm tra lần này:**
   - Mã cấu kiện: ........................................ Khuyết tật phát hiện: .................................................................................................................
   - Biện pháp khắc phục bắt buộc: [ ] Nắn thẳng bằng nhiệt/cơ học; [ ] Tẩy mối hàn lỗi và hàn lại theo WPS; [ ] Xả nhám và sơn dặm lại đạt chiều dày DFT quy định.
   - Thời hạn Bên nhận gia công phải hoàn thành sửa chữa: Trước ngày ...../...../20... và phải mời Kỹ sư QC kiểm tra lại.
2. **KẾT LUẬN CỦA ĐOÀN NGHIỆM THU:**
   - [x] **CHẤP THUẬN CHO PHÉP XUẤT XƯỞNG:** Toàn bộ các cấu kiện đạt yêu cầu tại Mục 4 đã được đóng dấu kiểm định (Marking), sơn mã hiệu rõ ràng, cho phép Bên nhận gia công làm thủ tục bốc xếp lên phương tiện vận chuyển để chuyển thẳng ra mặt bằng công trình `<<CT_TEN>>`.
   - [ ] Nghiêm cấm đưa các cấu kiện chưa được kiểm tra hoặc cấu kiện bị lỗi ra khỏi phạm vi nhà xưởng.

---

### CHỮ KÝ XÁC NHẬN NGHIỆM THU KỸ THUẬT

| KCS / QC XƯỞNG GIA CÔNG | QUẢN ĐỐC XƯỞNG GIA CÔNG | KỸ SƯ GIÁM SÁT KỸ THUẬT / QC | CHỈ HUY TRƯỞNG CÔNG TRÌNH |
|:---:|:---:|:---:|:---:|
| *(Ký, ghi rõ họ tên)* | *(Ký, đóng dấu)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* |
| <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> |
| Họ tên: ....................................... | **`<<XUONG_GC_DAI_DIEN>>`** | Họ tên: ....................................... | **`<<CT_CHI_HUY_TRUONG>>`** |

---

## PHẦN IV. BIỂU MẪU SỐ 03: BIÊN BẢN ĐỐI CHIẾU VÀ QUYẾT TOÁN VẬT TƯ SAU GIA CÔNG

<center>

### CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
**Độc lập – Tự do – Hạnh phúc**

---

**DỰ ÁN / CÔNG TRÌNH:** `<<CT_TEN>>` (MÃ CT: `<<CT_MA>>`)  
**Số văn bản:** `......./BBDC-QT-VT/<<CT_MA>>-<<VB_NAM>>`  
*Hôm nay, ngày ..... tháng ..... năm 20..., tại văn phòng Ban Điều hành Dự án `<<CTY_TEN>>`, chúng tôi gồm có:*

</center>

### 1. ĐẠI DIỆN BÊN ĐẶT GIA CÔNG (`<<CTY_TEN>>`):
- Ông/Bà: `<<CTY_DAI_DIEN>>` ................... Chức vụ: Giám đốc / Đại diện pháp luật
- Ông/Bà: `<<CT_CHI_HUY_TRUONG>>` ............ Chức vụ: Chỉ huy trưởng công trình
- Ông/Bà: ................................................................ Chức vụ: Trưởng phòng Kỹ thuật / Kỹ sư QC
- Ông/Bà: ................................................................ Chức vụ: Kế toán Vật tư / Kế toán trưởng

### 2. ĐẠI DIỆN BÊN NHẬN GIA CÔNG (`<<XUONG_GC_TEN>>`):
- Ông/Bà: `<<XUONG_GC_DAI_DIEN>>` ............ Chức vụ: Giám đốc đơn vị gia công
- Ông/Bà: ................................................................ Chức vụ: Quản đốc Xưởng gia công
- Ông/Bà: ................................................................ Chức vụ: Kế toán theo dõi công nợ

### 3. CĂN CỨ THỰC HIỆN ĐỐI CHIẾU VÀ QUYẾT TOÁN:
- *Căn cứ Hợp đồng dịch vụ gia công số `<<GC_HD_SO>>` ngày `<<GC_HD_NGAY>>`;*
- *Căn cứ các Biên bản giao nhận phôi/vật tư từ ngày ...../...../20... đến ngày ...../...../20... (Mẫu D1-84/BM-01);*
- *Căn cứ các Biên bản nghiệm thu kỹ thuật thành phẩm tại xưởng và Biên bản bàn giao cấu kiện tại công trường `<<CT_TEN>>` (Mẫu D1-84/BM-02 và D1-68);*
- *Căn cứ hồ sơ bản vẽ hoàn công gia công chế tạo (As-built Shop Drawing).*

Hai bên tiến hành tổng hợp số liệu, đối chiếu cân đối lượng nguyên vật liệu cấp vào, thành phẩm tạo thành, tỷ lệ hao hụt thực tế và xác định trách nhiệm vật chất theo bảng cân đối dưới đây:

### 4. BẢNG CÂN ĐỐI VÀ QUYẾT TOÁN VẬT TƯ GIA CÔNG CHI TIẾT:

| STT | (1) Tên chủng loại vật tư, phôi thép cấp | (2) ĐVT | (3) Tổng số lượng / khối lượng cấp vào $(A)$ | (4) Thành phẩm tạo thành đã nghiệm thu $(B)$ | (5) Định mức tiêu hao kỹ thuật $(\%)$ | (6) Khối lượng cấu thành thành phẩm $(C = B)$ | (7) Hao hụt cho phép theo định mức $(D = C \times \%ĐM)$ | (8) Hao hụt thực tế $(E = A - B - G)$ | (9) Chênh lệch thừa / thiếu ngoài định mức $(F = E - D)$ | (10) Khối lượng vật tư thừa thu hồi $(G)$ | (11) Khối lượng phế liệu phát sinh $(H)$ |
|:---:|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | Thép tấm tổ hợp $t = 12 \div 20mm$ (SS400/Q355B) | Kg | 45.000 | 41.500 | 3,0% | 41.500 | 1.245 | 1.350 | **+ 105** *(Vượt ĐM)* | 2.150 | 1.350 |
| 2 | Thép hình đúc chữ H ($H300$, $H200$) | Kg | 28.000 | 26.800 | 1,5% | 26.800 | 402 | 380 | **- 22** *(Tiết kiệm)* | 820 | 380 |
| 3 | Thép xà gồ phôi Z200 mạ kẽm cuộn | Kg | 15.500 | 15.200 | 0,8% | 15.200 | 121,6 | 120 | **- 1,6** *(Tiết kiệm)* | 180 | 120 |
| 4 | Thép góc đều cạnh $L75 \times 6$, giằng | Kg | 6.200 | 5.950 | 2,0% | 5.950 | 119 | 115 | **- 4** *(Tiết kiệm)* | 135 | 115 |
| 5 | Sơn chống rỉ lót Epoxy | Lít | 450 | 320 | 25,0% | 320 | 80 | 95 | **+ 15** *(Vượt ĐM)* | 35 | 0 |
| 6 | Que hàn, dây hàn CO2 | Kg | 1.200 | 1.050 | 10,0% | 1.050 | 105 | 102 | **- 3** *(Tiết kiệm)* | 48 | 0 |
| | **TỔNG CỘNG THÉP CÁC LOẠI:** | **Kg** | **94.700** | **89.450** | — | **89.450** | **1.887,6** | **1.965** | **+ 77,4** | **3.285** | **1.965** |

*Nguyên tắc cân đối:*  
$$\text{Tổng vật tư cấp vào } (A) = \text{Thành phẩm nghiệm thu } (B) + \text{Vật tư thừa thu hồi } (G) + \text{Hao hụt thực tế } (E)$$  
*Trong đó: Toàn bộ lượng hao hụt thực tế được thể hiện dưới dạng phế liệu kim loại phát sinh (H) đã được thu gom cân đo thực tế.*

### 5. ĐÁNH GIÁ KẾT QUẢ VÀ TRÁCH NHIỆM BỒI HOÀN VẬT TƯ:
1. **Xác nhận về vật tư thừa nguyên dạng và phế liệu:**
   - Tổng khối lượng phôi thép thừa nguyên dạng có thể tái sử dụng (Cột 10): **`3.285` kg** (Được xử lý bàn giao theo Biểu mẫu số 04 - Mẫu `D1-84/BM-04`).
   - Tổng khối lượng phế liệu kim loại phát sinh (Cột 11): **`1.965` kg** (Được xử lý thanh lý hoặc thu hồi theo Biểu mẫu số 04).
2. **Xác nhận trách nhiệm bồi hoàn hao hụt vượt định mức:**
   - Căn cứ Cột (9), số lượng vật tư bị hao hụt vượt định mức cho phép do lỗi kỹ thuật gia công của `<<XUONG_GC_TEN>>` gồm:
     + Thép tấm tổ hợp $t = 12 \div 20mm$: Vượt định mức **105 kg**;
     + Sơn lót chống rỉ Epoxy: Vượt định mức **15 lít**.
   - Đơn giá bồi hoàn theo thỏa thuận Hợp đồng:
     + Thép tấm: ........................................ VNĐ/kg $\rightarrow$ Thành tiền bồi hoàn: ........................................ VNĐ.
     + Sơn lót Epoxy: ................................ VNĐ/lít $\rightarrow$ Thành tiền bồi hoàn: ........................................ VNĐ.
   - **Tổng giá trị Bên nhận gia công phải bồi hoàn cho `<<CTY_TEN>>`:** ........................................ VNĐ.  
     *(Số tiền bằng chữ: .................................................................................................................................................................)*
3. **Phương thức cấn trừ thanh toán:**
   - Hai bên thống nhất số tiền bồi hoàn nói trên được **khấu trừ trực tiếp** vào đợt thanh toán quyết toán tiền công gia công theo Hợp đồng số `<<GC_HD_SO>>`.
   - Phòng Kế toán của `<<CTY_TEN>>` có trách nhiệm lập chứng từ bù trừ công nợ hợp lệ theo quy định của pháp luật kế toán và thuế.

---

### CHỮ KÝ XÁC NHẬN QUYẾT TOÁN VẬT TƯ

| ĐẠI DIỆN KỸ SƯ / QC | KẾ TOÁN VẬT TƯ CÔNG TY | CHỈ HUY TRƯỞNG CÔNG TRÌNH | ĐẠI DIỆN PHÁP LUẬT XƯỞNG GC | ĐẠI DIỆN THEO PHÁP LUẬT `<<CTY_TEN>>` |
|:---:|:---:|:---:|:---:|:---:|
| *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, đóng dấu)* | *(Ký, đóng dấu)* |
| <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> |
| Họ tên: ............................. | Họ tên: ............................. | **`<<CT_CHI_HUY_TRUONG>>`** | **`<<XUONG_GC_DAI_DIEN>>`** | **`<<CTY_DAI_DIEN>>`** |

---

## PHẦN V. BIỂU MẪU SỐ 04: BIÊN BẢN BÀN GIAO & XỬ LÝ VẬT TƯ THỪA, PHẾ LIỆU GIA CÔNG

<center>

### CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM
**Độc lập – Tự do – Hạnh phúc**

---

**DỰ ÁN / CÔNG TRÌNH:** `<<CT_TEN>>` (MÃ CT: `<<CT_MA>>`)  
**Số văn bản:** `......./BBXL-VT-PL/<<CT_MA>>-<<VB_NAM>>`  
*Hôm nay, ngày ..... tháng ..... năm 20..., tại Xưởng gia công `<<XUONG_GC_TEN>>`, chúng tôi gồm có:*

</center>

### 1. ĐẠI DIỆN BÊN GIAO (Bên sở hữu vật tư – `<<CTY_TEN>>`):
- Ông/Bà: ................................................................ Chức vụ: Chỉ huy trưởng công trình / Kỹ sư đại diện
- Ông/Bà: ................................................................ Chức vụ: Thủ kho / Cán bộ quản lý vật tư
- Ông/Bà: ................................................................ Chức vụ: Kế toán thanh toán / Vật tư

### 2. ĐẠI DIỆN BÊN NHẬN (Đơn vị nhận gia công – `<<XUONG_GC_TEN>>`):
- Ông/Bà: `<<XUONG_GC_DAI_DIEN>>` ................ Chức vụ: Giám đốc / Đại diện đơn vị gia công
- Ông/Bà: ................................................................ Chức vụ: Quản đốc xưởng gia công
- Ông/Bà: ................................................................ Chức vụ: Thủ kho xưởng

Căn cứ Biên bản đối chiếu và quyết toán vật tư sau gia công số `......./BBDC-QT-VT/<<CT_MA>>-<<VB_NAM>>` ngày ...../...../20...;  
Hai bên thống nhất lập biên bản bàn giao, phân loại và lựa chọn phương án xử lý đối với toàn bộ khối lượng phôi thép thừa nguyên dạng và phế liệu phát sinh như sau:

### 3. BẢNG THỐNG KÊ CHI TIẾT VẬT TƯ THỪA VÀ PHẾ LIỆU THU HỒI:

| STT | Tên quy cách chủng loại vật tư / Phế liệu | Kích thước hiện trạng *(mm)* | ĐVT | Số lượng | Khối lượng cân thực tế *(Kg)* | Hiện trạng phẩm chất | Phương án xử lý thống nhất *(Phương án 1 / Phương án 2)* |
|:---:|---|:---:|:---:|:---:|:---:|---|:---:|
| **A** | **VẬT TƯ THỪA NGUYÊN DẠNG CÒN SỬ DỤNG ĐƯỢC (TÁI SỬ DỤNG)** | | | | | | |
| | *(Ghi chú phân bổ: Tổng lượng thép thừa theo BM-03 là 3.285 kg, trong đó 2.121,4 kg được thanh lý cấn trừ theo Phương án 2; phần còn lại 1.163,6 kg được thu hồi về kho Công ty theo Phương án 1)* | | | | | | |
| 1 | Thép tấm đầu khổ lớn $t=16mm$ (SS400) | $1.200 \times 2.500 \times 16$ | Tấm | 02 | 753,6 | Mới 95%, bề mặt phẳng, dùng làm bản mã | [ ] Thu hồi về kho Công ty <br> [ ] Xưởng mua thanh lý |
| 2 | Thép tấm đầu khổ $t=12mm$ (Q355B) | $1.000 \times 3.000 \times 12$ | Tấm | 03 | 847,8 | Mới 95%, tái sử dụng cho công trình sau | [ ] Thu hồi về kho Công ty <br> [ ] Xưởng mua thanh lý |
| 3 | Thép hình đúc chữ H ($H300 \times 150$) đoạn dài | Đoạn $L = 2.5m \div 3.8m$ | Đoạn | 05 | 520,0 | Thẳng, không khuyết tật | [ ] Thu hồi về kho Công ty <br> [ ] Xưởng mua thanh lý |
| 4 | Sơn lót Epoxy nguyên thùng chưa khui | Thùng 20 lít | Thùng | 01 | 25,0 | Còn nguyên seal niêm phong của hãng | [ ] Thu hồi về kho Công ty <br> [ ] Xưởng nhận cấn trừ tiền |
| **B** | **PHẾ LIỆU THÉP, PHOI TIỆN, ĐẦU MẨU KHÔNG THỂ TÁI SỬ DỤNG** | | | | | | |
| 5 | Thép tấm đầu mẩu vụn, ba-vớ cắt CNC | Kích thước nhỏ vụn, mép cháy | Kg | Lô | 1.350,0 | Phế liệu sắt vụn loại 1 | [ ] Thu gom bán phế liệu <br> [ ] Xưởng mua cấn trừ công nợ |
| 6 | Đầu mẩu thép hình đúc cắt ngắn | Đoạn $L < 300mm$ | Kg | Lô | 380,0 | Phế liệu sắt vụn loại 1 | [ ] Thu gom bán phế liệu <br> [ ] Xưởng mua cấn trừ công nợ |
| 7 | Đầu mẩu xà gồ mạ kẽm Z200 vụn | Vụn cắt đầu mẩu | Kg | Lô | 120,0 | Phế liệu thép mạ kẽm | [ ] Thu gom bán phế liệu <br> [ ] Xưởng mua cấn trừ công nợ |
| 8 | Đầu mẩu thép góc L75 | Đoạn vụn | Kg | Lô | 115,0 | Phế liệu sắt vụn | [ ] Thu gom bán phế liệu <br> [ ] Xưởng mua cấn trừ công nợ |

### 4. THỎA THUẬN PHƯƠNG ÁN XỬ LÝ VẬT TƯ THỪA VÀ PHẾ LIỆU:

Hai bên thỏa thuận lựa chọn phương án xử lý theo các điều khoản cụ thể sau:

#### ☐ PHƯƠNG ÁN 1: THU HỒI VỀ KHO CỦA CÔNG TY (`<<CTY_TEN>>`)
- Địa điểm tập kết nhận hàng: Kho `<<CTY_TEN>>` tại địa chỉ: `<<CTY_DC>>` (hoặc bãi chứa công trình: `<<CT_DIA_DIEM>>`).
- Phương tiện vận chuyển và bốc xếp: Do Bên `................................` bố trí và chịu mọi chi phí.
- Thời hạn hoàn thành bốc xếp vận chuyển: Trước 17h00 ngày ...../...../20...
- Thủ kho `<<CTY_TEN>>` căn cứ phiếu cân tải trọng và biên bản này để làm thủ tục nhập kho tài sản.

#### ☐ PHƯƠNG ÁN 2: BÁN THANH LÝ TRỰC TIẾP CHO BÊN NHẬN GIA CÔNG CẤN TRỪ CÔNG NỢ GIA CÔNG
- `<<CTY_TEN>>` đồng ý bán thanh lý và `<<XUONG_GC_TEN>>` đồng ý thu mua lại toàn bộ khối lượng vật tư thừa và phế liệu theo bảng giá thỏa thuận dưới đây:

| STT | Phân loại hàng thanh lý | Khối lượng thanh lý *(Kg)* | Đơn giá thỏa thuận chưa VAT *(VNĐ/Kg)* | Thành tiền chưa VAT *(VNĐ)* | Thuế GTGT *(8% hoặc 10%)* | Tổng giá trị thanh toán *(VNĐ)* |
|:---:|---|:---:|:---:|:---:|:---:|:---:|
| 1 | Thép tấm / Thép hình thừa tái sử dụng (Mục 1, 2, 3) | 2.121,4 | ................................... | ................................... | ................................... | ................................... |
| 2 | Sơn lót Epoxy tồn kho nguyên thùng (Mục 4) | 01 thùng | ................................... | ................................... | ................................... | ................................... |
| 3 | Phế liệu sắt vụn, đầu mẩu (Mục 5, 6, 7, 8) | 1.965,0 | ................................... | ................................... | ................................... | ................................... |
| | **TỔNG GIÁ TRỊ THANH LÝ CẤN TRỪ (VNĐ):** | — | — | **...................................** | **...................................** | **...................................** |

*(Số tiền bằng chữ: .............................................................................................................................................................)*

- **Quy trình cấn trừ và chứng từ thuế:**
  + `<<CTY_TEN>>` phát hành Hóa đơn điện tử bán hàng thanh lý phôi thừa/phế liệu cho `<<XUONG_GC_TEN>>` theo đúng quy định pháp luật thuế;
  + Hai bên ký Biên bản đối chiếu bù trừ công nợ giữa Tiền công dịch vụ gia công phải trả (theo hóa đơn của Bên gia công) và Tiền bán thanh lý vật tư/phế liệu phải thu (theo hóa đơn của Công ty);
  + Số tiền chênh lệch còn lại (nếu có) được thanh toán dứt điểm qua tài khoản ngân hàng của hai bên.

---

### CĂN CỨ PHÁP LÝ & TIÊU CHUẨN KỸ THUẬT ÁP DỤNG
- *Bộ luật Dân sự số 91/2015/QH13 (Mục 11 – Hợp đồng gia công, từ Điều 542 đến Điều 553);*
- *Luật Thương mại số 36/2005/QH11 (Mục 5 Chương VI – Gia công trong thương mại);*
- *Luật Xây dựng số 50/2014/QH13 và Luật Xây dựng sửa đổi bổ sung năm 2025;*
- *Luật Thuế Giá trị gia tăng và các văn bản hướng dẫn về hóa đơn, chứng từ hợp lệ được trừ khi xác định nghĩa vụ thuế TNDN;*
- *Nghị định số 207/2026/NĐ-CP ngày 15/06/2026 của Chính phủ quy định chi tiết về quản lý an toàn và chất lượng trong thi công xây dựng công trình;*
- *Tiêu chuẩn Quốc gia TCVN 170:2007: Kết cấu thép – Gia công, lắp ráp và nghiệm thu – Yêu cầu kỹ thuật;*
- *Tiêu chuẩn Quốc gia TCVN 8789:2011: Sơn bảo vệ kết cấu thép – Yêu cầu kỹ thuật và phương pháp thử;*
- *Hợp đồng dịch vụ gia công số `<<GC_HD_SO>>` giữa `<<CTY_TEN>>` và `<<XUONG_GC_TEN>>`.*

---

### CHỮ KÝ XÁC NHẬN BÀN GIAO VÀ XỬ LÝ VẬT TƯ

| ĐẠI DIỆN THỦ KHO CÔNG TY | KẾ TOÁN THANH TOÁN CÔNG TY | CHỈ HUY TRƯỞNG CÔNG TRÌNH | THỦ KHO XƯỞNG GIA CÔNG | ĐẠI DIỆN PHÁP LUẬT XƯỞNG GC | ĐẠI DIỆN THEO PHÁP LUẬT `<<CTY_TEN>>` |
|:---:|:---:|:---:|:---:|:---:|:---:|
| *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, đóng dấu)* | *(Ký, đóng dấu)* |
| <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> | <br><br><br><br> |
| Họ tên: ............................. | Họ tên: ............................. | **`<<CT_CHI_HUY_TRUONG>>`** | Họ tên: ............................. | **`<<XUONG_GC_DAI_DIEN>>`** | **`<<CTY_DAI_DIEN>>`** |
