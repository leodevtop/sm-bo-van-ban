# ĐƠN ĐẶT HÀNG MUA VẬT TƯ / CẤU KIỆN KẾT CẤU THÉP (PURCHASE ORDER - PO)

| THÔNG TIN ĐƠN HÀNG | NỘI DUNG CHI TIẾT |
| :--- | :--- |
| **Đơn vị đặt hàng (Bên mua)** | **<<CTY_TEN>>** |
| **Mã đơn đặt hàng** | `PO-<<CT_MA>>-<<VB_NAM>>-<<SO_PO>>` |
| **Mã biểu mẫu** | `75/BM-VT-<<CTY_TEN_VT>>` |
| **Phiên bản** | `1.0` |
| **Ngày lập đơn** | `<<VB_NGAY>>/<<VB_THANG>>/<<VB_NAM>>` |
| **Công trình / Dự án** | **<<CT_TEN>>** |
| **Hợp đồng nguyên tắc / Khung** | Số `<<SO_HD_KHUNG>>` ký ngày `<<NGAY_HD_KHUNG>>` *(nếu có)* |

---

## 1. THÔNG TIN CÁC BÊN GIAO DỊCH

### BÊN ĐẶT HÀNG (BÊN MUA):
- **Tên đơn vị:** **<<CTY_TEN>>**
- Mã số thuế: `<<CTY_MST>>`
- Địa chỉ trụ sở: `<<CTY_DC>>`
- Đại diện theo pháp luật: `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` - Chức vụ: Giám đốc
- Người phụ trách mua hàng: `<<NV_MUA_HANG_TEN>>` - Điện thoại: `<<NV_MUA_HANG_SDT>>`
- **Bộ phận nhận hàng tại công trường:**
  - Địa điểm công trường: `<<CT_DIA_DIEM>>`
  - Người nhận hàng (Chỉ huy trưởng): `<<CHT_TEN>>` - Điện thoại: `<<CHT_SO_DIEN_THOAI>>`

### BÊN CUNG CẤP (BÊN BÁN):
- **Tên nhà cung cấp / Nhà máy:** **<<NCC_TEN>>**
- Mã số thuế: `<<NCC_MST>>`
- Địa chỉ nhà máy / Trụ sở: `<<NCC_DIA_CHI>>`
- Người đại diện: `<<NCC_NGUOI_DAI_DIEN>>` - Chức vụ: `<<NCC_CHUC_VU>>`
- Điện thoại: `<<NCC_SO_DIEN_THOAI>>` - Email: `<<NCC_EMAIL>>`
- Số tài khoản ngân hàng: `<<NCC_STK>>` tại Ngân hàng: `<<NCC_NGAN_HANG>>`

---

## 2. NỘI DUNG VẬT TƯ / CẤU KIỆN ĐẶT HÀNG

Bên Mua đồng ý đặt hàng và Bên Bán đồng ý cung cấp các chủng loại vật tư, cấu kiện kết cấu thép phục vụ thi công lắp dựng tại công trình **<<CT_TEN>>** với danh mục chi tiết dưới đây:

| STT | Mã cấu kiện / Tên quy cách vật tư | Tiêu chuẩn kỹ thuật / Mác thép | Kích thước / Chiều dài (mm) | ĐVT | Khối lượng / Số lượng | Đơn giá *(VNĐ)* | Thành tiền *(VNĐ)* | Tiến độ giao hàng yêu cầu |
| :---: | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **A** | **CẤU KIỆN KẾT CẤU THÉP CHÍNH (Gia công hoàn thiện)** | | | | | | | |
| 1 | Cột thép tổ hợp chữ H (Mã C1 - C12) | SS400 / Q355B (TCVN 5575) | Tiết diện H(500~300)x250x8x12; L=10.500 | Tấn | <<KL_PO_C>> | *Theo Bảng TS* | <<TT_PO_C>> | Đợt 1: Ngày <<NGAY_GIAO_D1>> |
| 2 | Kèo thép tổ hợp chữ I (Mã K1 - K8) | Q355B / SS400 | Tiết diện dốc biến đổi H(600~350)x200x8x10 | Tấn | <<KL_PO_K>> | *Theo Bảng TS* | <<TT_PO_K>> | Đợt 1: Ngày <<NGAY_GIAO_D1>> |
| 3 | Dầm sàn thao tác, dầm giằng ngang (Mã B1 - B16) | SS400 | Thép hình I/H đúc hoặc hàn | Tấn | <<KL_PO_B>> | *Theo Bảng TS* | <<TT_PO_B>> | Đợt 2: Ngày <<NGAY_GIAO_D2>> |
| 4 | Xà gồ mái chữ Z, xà gồ vách chữ C mạ kẽm (Z200, C150) | Thép mạ kẽm Z275, G450 | Dày 1.8mm - 2.0mm, đột lỗ tự động | Tấn | <<KL_PO_XG>> | *Theo Bảng TS* | <<TT_PO_XG>> | Đợt 2: Ngày <<NGAY_GIAO_D2>> |
| 5 | Hệ giằng cáp thép $\phi 16$, giằng góc L65x65x5 | Thép SS400 / Cáp mạ kẽm | Kèm tăng đơ, cóc nối cáp | Bộ / Tấn | <<KL_PO_G>> | *Theo Bảng TS* | <<TT_PO_G>> | Đợt 1: Ngày <<NGAY_GIAO_D1>> |
| **B** | **BU LÔNG LIÊN KẾT & PHỤ KIỆN LẮP DỰNG** | | | | | | | |
| 6 | Bu lông cường độ cao cấp bền 8.8 (Kèm đai ốc, 2 lông đền) | Cấp bền 8.8 (TCVN 1916) | M20 x 70 (hoặc M24 x 80) | Bộ | <<SL_PO_BL>> | *Theo Bảng TS* | <<TT_PO_BL>> | Cùng Đợt 1 |
| 7 | Bu lông mạ kẽm liên kết xà gồ cấp bền 4.6 | Thép mạ kẽm nhúng nóng | M12 x 35 | Bộ | <<SL_PO_BLXG>> | *Theo Bảng TS* | <<TT_PO_BLXG>> | Cùng Đợt 2 |
| 8 | Bu lông neo chân cột móng (Anchor Bolt L-type / J-type) | Thép tròn CT3 / C45 / Gr 8.8 | M27 / M30, Dài L=800mm (Ren 150mm) | Bộ | <<SL_PO_NEO>> | *Theo Bảng TS* | <<TT_PO_NEO>> | Giao trước thi công móng |
| **C** | **SƠN DẶM VÁ & VẬT TƯ TIÊU HAO HIỆN TRƯỜNG** | | | | | | | |
| 9 | Sơn chống rỉ lót Epoxy / Alkyd (Đúng chủng loại màu xưởng) | Tiêu chuẩn nhà máy | Thùng 20 lít | Thùng | <<SL_PO_SON1>> | *Theo Bảng TS* | <<TT_PO_SON1>> | Cùng Đợt 1 |
| 10 | Dung môi pha sơn (Thinner) chuyên dụng | Tiêu chuẩn nhà máy | Thùng 20 lít | Thùng | <<SL_PO_DM>> | *Theo Bảng TS* | <<TT_PO_DM>> | Cùng Đợt 1 |
| | **TỔNG CỘNG CHƯA THUẾ (VNĐ):** | | | | | | **<<TONG_CHUA_THUE_PO>>** | |
| | **Thuế Giá trị gia tăng (VAT 8% / 10%):** | | | | | | **<<VAT_PO>>** | |
| | **TỔNG GIÁ TRỊ ĐƠN HÀNG (VNĐ):** | | | | | | **<<TONG_GIA_TRI_PO>>** | |

*(Số tiền bằng chữ: <<SO_TIEN_BANG_CHU_PO>>)*

---

## 3. TIÊU CHUẨN KỸ THUẬT VÀ YÊU CẦU CHẤT LƯỢNG

1. **Hồ sơ chất lượng bắt buộc kèm theo mỗi chuyến hàng:**
   - Phiếu xuất xưởng và Chứng chỉ chất lượng của Nhà máy (CQ - Factory Test Certificate).
   - Chứng chỉ xuất xứ nguồn gốc phôi thép tấm/thép hình (CO/Mill Test Certificate).
   - Báo cáo kết quả kiểm tra thí nghiệm không phá hủy mối hàn xưởng (NDT: VT 100%, UT tối thiểu 10% - 20% các mối hàn đối đầu chịu kéo theo yêu cầu đồ án thiết kế).
   - Biên bản kiểm tra độ dày lớp màng sơn khô (DFT) đạt chuẩn thiết kế (tối thiểu $\ge 80\mu m$).
2. **Quy cách đánh mã cấu kiện và đóng gói vận chuyển:**
   - Từng cấu kiện phải được quét sơn hoặc đóng dấu mã hiệu cấu kiện rõ ràng, không bị nhòe (ví dụ: `C1-1`, `K1-2`, `D1-3`) khớp 100% với Bản vẽ lắp dựng (Erection Drawing).
   - Các bề mặt lắp ghép bu lông (bản mã, mặt bích) phải được bảo vệ không để dính dầu mỡ, không cong vênh quá sai số cho phép theo TCVN 10307:2014.
   - Bu lông cường độ cao phải được đóng thùng gỗ hoặc bao bì chuyên dụng có bọc màng chống ẩm, phân loại riêng từng kích cỡ và cấp bền.
3. **Thứ tự giao hàng đồng bộ:** Bên Bán phải giao hàng theo đúng tiến độ phân đợt của Bên Mua. Tuyệt đối không giao rời rạc dẫn đến việc có kèo mà không có cột, hoặc thiếu bu lông liên kết làm đình trệ công tác cẩu lắp tại hiện trường.

---

## 4. PHƯƠNG THỨC GIAO NHẬN VÀ NGHIỆM THU HIỆN TRƯỜNG

1. **Địa điểm giao nhận:** Giao hàng đến chân công trình tại `<<CT_DIA_DIEM>>`.
2. **Bốc dỡ hàng hóa:** 
   - Bên Mua bố trí xe cẩu và công nhân bốc dỡ cấu kiện từ xe rơ-moóc của Bên Bán xuống bãi tập kết vật tư tại công trường.
   - Thời gian hạ hàng tối đa không quá 03 giờ/xe kể từ khi xe vào vị trí bốc dỡ an toàn.
3. **Nghiệm thu vật tư đầu vào:**
   - Hai bên tiến hành kiểm tra số lượng, ngoại quan, mã hiệu, độ dày sơn và lập **Biên bản giao nhận và nghiệm thu vật tư** theo mẫu `68_Bien_Ban_Giao_Nhan_va_Quyet_Toan_Vat_Tu.md`.
   - Mọi cấu kiện bị móp méo, cong vênh quá dung sai, rách mối hàn hoặc sai lệch lỗ bu lông sẽ bị Bên Mua từ chối nhận. Bên Bán có trách nhiệm sửa chữa hoặc thay thế trong vòng 48 giờ bằng chi phí của Bên Bán.

---

## 5. ĐIỀU KHOẢN THANH TOÁN VÀ PHẠT VI PHẠM

1. **Điều kiện thanh toán:**
   - **Tạm ứng:** <<TY_LE_TAM_UNG_PO>>% giá trị đơn hàng sau khi Bên Bán xác nhận đơn hàng và phát hành thông báo kế hoạch sản xuất.
   - **Thanh toán từng đợt:** Thanh toán đến 90% giá trị của từng chuyến hàng trong vòng 07 ngày làm việc kể từ ngày giao nhận thành công và Bên Mua nhận đầy đủ hóa đơn GTGT kèm hồ sơ chất lượng.
   - **Thanh toán quyết toán:** Thanh toán 10% còn lại sau khi hoàn thành nghiệm thu lắp dựng toàn bộ cấu kiện và không có khiếu nại về chất lượng.
2. **Phạt chậm giao hàng:** Nếu Bên Bán chậm giao hàng so với mốc thời gian thỏa thuận mà không do sự kiện bất khả kháng, Bên Bán chịu phạt 0.5% giá trị lô hàng chậm cho mỗi ngày chậm trễ, nhưng tổng mức phạt không vượt quá 8% giá trị đơn hàng, đồng thời phải bồi thường chi phí chờ đợi xe cẩu của Bên Mua phát sinh tại công trường.

---

## 6. HIỆU LỰC ĐƠN ĐẶT HÀNG VÀ CĂN CỨ PHÁP LÝ

Đơn đặt hàng này có giá trị pháp lý ràng buộc hai bên kể từ ngày đại diện có thẩm quyền của hai bên ký xác nhận. Mọi sửa đổi phải được lập thành văn bản bổ sung.

**CĂN CỨ PHÁP LÝ:**
1. Bộ luật Dân sự số 91/2015/QH13.
2. Luật Thương mại số 36/2005/QH11.
3. TCVN 10307:2014 về Kết cấu thép - Gia công, lắp dựng và nghiệm thu.
4. Quy định mua sắm và quản lý tài chính hiện hành của **<<CTY_TEN>>**.

---

| ĐẠI DIỆN BÊN BÁN (NHÀ CUNG CẤP) | NGƯỜI PHỤ TRÁCH MUA HÀNG | ĐẠI DIỆN PHÁP LUẬT BÊN MUA |
| :---: | :---: | :---: |
| *(Xác nhận nhận đơn, ký tên & đóng dấu)* | *(Ký và ghi rõ họ tên)* | *(Ký tên và đóng dấu công ty)* |
| **<<NCC_NGUOI_DAI_DIEN>>** | **<<NV_MUA_HANG_TEN>>** | **<<NGUOI_DAI_DIEN_PHAP_LUAT>>** |
