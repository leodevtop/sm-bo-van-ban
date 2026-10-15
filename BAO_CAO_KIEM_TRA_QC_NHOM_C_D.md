# BÁO CÁO KIỂM TRA ĐỘC LẬP (QC) TOÀN DIỆN VĂN BẢN NHÓM C & D
**HỆ THỐNG VĂN BẢN QUẢN LÝ VẬN HÀNH CÔNG TY THI CÔNG KẾT CẤU THÉP NHÀ XƯỞNG**

---

| THÔNG TIN BÁO CÁO QC | CHI TIẾT |
|:---|:---|
| **Đơn vị thẩm tra** | Bộ phận Kiểm soát Chất lượng Độc lập (QC Chuyên gia) |
| **Ngày kiểm tra** | 15/10/2026 |
| **Phạm vi kiểm tra** | Toàn bộ 25 văn bản Nhóm C & D mới được soạn thảo |
| **Tài liệu quy chuẩn đối chiếu** | `bo-van-ban/00-README-huong-dan-ban-hanh.md`, `bo-van-ban/00_Danh_Sach_Van_Ban.md`, `bo-van-ban/00_Ma_Data.md`, `bo-van-ban/00-bang-tham-so.md`, `C1`, `C2`, `D1`, `D2`, `D3`, `D4`, `README.md` |
| **Căn cứ pháp lý cập nhật** | Nghị định 207/2026/NĐ-CP, Thông tư 32/2026/TT-BXD, Nghị định 283/2026/NĐ-CP, Luật Bảo vệ dữ liệu cá nhân 91/2025/QH15 & Nghị định 356/2025/NĐ-CP, Luật Xây dựng 135/2025/QH15, Bộ luật Lao động 2019, Thông tư 133/2016/TT-BTC |

---

## PHẦN I. TỔNG QUAN KẾT QUẢ ĐÁNH GIÁ (PASS / FAIL MATRIX)

Qua rà soát độc lập toàn diện 25 file văn bản, kết quả phân loại mức độ đáp ứng như sau:

| Phân loại kết quả | Số lượng văn bản | Tỷ lệ (%) | Ý nghĩa & Hướng xử lý |
|:---|:---:|:---:|:---|
| **1. ĐẠT CHUẨN HOÀN TOÀN (PASS)** | **8 / 25** | **32.0%** | Văn bản chuẩn xác 100% về cấu trúc tổ chức, nội dung nghiệp vụ, pháp lý cập nhật 2026 và danh mục placeholder `00_Ma_Data.md`. Đủ điều kiện ban hành ngay. |
| **2. ĐẠT NỘI DUNG - CẦN CHUẨN HÓA MÃ PLACEHOLDER (PASS WITH MINOR FIXES)** | **15 / 25** | **60.0%** | Nội dung quản trị, pháp lý và biểu mẫu rất tốt; tuy nhiên tác giả sử dụng một số mã placeholder alias ngoài danh mục `00_Ma_Data.md` (như `<<NGUOI_DAI_DIEN_PHAP_LUAT>>`, `<<CHT_TEN>>`, `<<KTT_TEN>>`) hoặc gán placeholder tự tạo vào ô bảng tính. Cần chuẩn hóa lại mã để phục vụ chạy tự động (mail merge / Python). |
| **3. CẦN ĐIỀU CHỈNH NGHIỆP VỤ & PHÂN QUYỀN (NEEDS SUBSTANTIVE REVISION)** | **2 / 25** | **8.0%** | Có xung đột với nguyên tắc phân quyền và cơ cấu tổ chức cốt lõi của Công ty (File 71 và File 31). Cần chỉnh sửa nội dung trước khi trình Giám đốc ký. |
| **TỔNG CỘNG** | **25 / 25** | **100%** | **Tỷ lệ văn bản đạt chất lượng pháp trị và nghiệp vụ tổng thể: 92.0% (23/25 file)** |

---

### BẢNG ĐÁNH GIÁ CHI TIẾT 25 VĂN BẢN

| STT | Mã VB | Thư mục & Tên file văn bản | Mức độ đáp ứng | Đánh giá tóm tắt & Vấn đề chính |
|:---:|:---:|:---|:---:|:---|
| **I** | | **V_To_Chuc_Phan_Quyen/** | | |
| 1 | 63 | `63_Quy_Che_To_Chuc_Phan_Quyen_Chuc_Danh_Bao_Cao.md` | **ĐẠT (PASS)** | Xuất sắc. Đúng cơ cấu 04 phòng ban; Giám đốc là thẩm quyền tối cao; phân định rõ ranh giới duyệt; khẳng định HC-NS không tham gia quỹ KPI dự án. Căn cứ pháp lý ở cuối. |
| 2 | 64 | `64_Quy_Che_Bao_Ve_Du_Lieu_Ca_Nhan_va_Luu_Tru.md` | **ĐẠT (PASS)** | Xuất sắc. Bảng thời hạn lưu trữ chuẩn luật (TNLĐ chết người 15 năm; NLĐ nghỉ việc; kế toán 10 năm); chuẩn Luật BVDLCN 2025 & NĐ 356/2025; mẫu Legal Hold C2-2. |
| 3 | 65 | `65_Bien_Ban_Tieu_Huy_Ho_So.md` | **PASS (Minor Fix)** | Nội dung pháp lý tiêu hủy chuẩn (Luật Lưu trữ 2024, Luật BVDLCN 2025). Cần chuẩn hóa mã `<<CTY_DAI_DIEN>>`, `<<CTY_KE_TOAN_TRUONG>>` và sửa tên "Phòng Thi công" thay vì "Kỹ thuật - Thi công". |
| 4 | 66 | `66_Danh_Muc_Van_Ban_va_Nhat_Ky_Ra_Soat.md` | **ĐẠT (PASS)** | Rất tốt. Hệ thống hóa đầy đủ 83 văn bản quản trị; chu kỳ rà soát 06 tháng; sự kiện bắt buộc rà soát khi sửa luật ATVSLĐ; có gắn nhãn `◐` rõ ràng. |
| **II** | | **VI_Thi_Cong_Kinh_Doanh/** | | |
| 5 | 67 | `67_Quy_Trinh_Thi_Cong_Kiem_Soat_Chat_Luong_Nghiem_Thu.md` | **ĐẠT (PASS)** | Xuất sắc. 8 bước lắp dựng chuẩn; TCVN 170:2007; bắt buộc nghiệm thu công việc che khuất; nhật ký theo Phụ lục II NĐ 207/2026; căn cứ ở cuối; Giám đốc duyệt. |
| 6 | 68 | `68_Bien_Ban_Giao_Nhan_va_Quyet_Toan_Vat_Tu.md` | **ĐẠT (PASS)** | Xuất sắc. Áp dụng cho cả 2 dạng hợp đồng (Dạng 1 kiểm soát lỗi tránh đền oan; Dạng 2 định mức hao hụt chuẩn: thép 0.5%, xà gồ 1%, tôn 1.5%, bu lông 2%). |
| 7 | 69 | `69_Phieu_Yeu_Cau_va_Bien_Ban_Nghiem_Thu_Lap_Dung.md` | **ĐẠT (PASS)** | Xuất sắc. Phiếu yêu cầu nghiệm thu và Biên bản nghiệm thu công việc xây dựng với 10 thông số dung sai trắc địa TCVN 170:2007. NĐ 207/2026 & TT 32/2026 ở cuối. |
| 8 | 71 | `71_Quy_Trinh_Kinh_Doanh_Bao_Gia_Quan_Ly_Hop_Dong.md` | **CẦN SỬA (Revision)** | **Lỗi phân quyền & cơ cấu:** Bảng Bước 4 hardcode hạn mức báo giá 1 tỷ, 5 tỷ và viện dẫn chức danh "Phó Giám đốc/Giám đốc điều hành" không có trong cơ cấu tổ chức; tách riêng "Phòng Kinh doanh" và "Phòng Kỹ thuật" sai lệch mô hình 04 phòng; dùng mã placeholder alias. |
| 9 | 72 | `72_Mau_Bao_Gia.md` | **PASS (Minor Fix)** | Cấu trúc báo giá 2 Form rất tốt (Form 1 chỉ nhân công cẩu, Form 2 trọn gói). Cần đổi tên "Phòng Dự án (kiêm Kinh doanh)"; đổi mã placeholder alias (`<<KH_DC>>`, `<<KH_DAI_DIEN>>`, `<<CTY_DAI_DIEN>>`); dọn bớt placeholder tự tạo trong ô bảng tính. |
| 10 | 74 | `74_Phu_Luc_Vat_Tu_Dieu_Khoan_Bo_Sung_HopDong_ThauPhu.md` | **ĐẠT (PASS)** | Xuất sắc. Điều khoản bảo vệ nhà thầu thi công gói Dạng 2; điều chỉnh giá thép khi biến động $\pm 5\%$; tạm ứng mua thép; phân định ranh giới cung cấp; luật ở cuối. |
| 11 | 75 | `75_Don_Dat_Hang_Mua_Vat_Tu.md` | **PASS (Minor Fix)** | Điều khoản mua thép thành phẩm, cam kết CO/CQ/Mill Test, phạt chậm tối đa 8% đúng Luật Thương mại. Cần chuẩn hóa placeholder alias (`<<CTY_DAI_DIEN>>`, `<<NCC_DC>>`, `<<NCC_DAI_DIEN>>`). |
| 12 | 76 | `76_Checklist_Tham_Dinh_Rui_Ro_HD_va_Dieu_Kien_Huy_Dong.md` | **ĐẠT (PASS)** | Rất xuất sắc. Cơ chế đèn giao thông (Đỏ - Vàng - Xanh); 100% công nhân có HĐLĐ, thẻ an toàn, bảo hiểm, tạm ứng mới cho quân vào công trường. Tuyệt đối cấm phạt tiền/trừ lương. |
| 13 | 77 | `77_Bien_Ban_Thanh_Ly_Hop_Dong.md` | **PASS (Minor Fix)** | Đầy đủ khối lượng hoàn công, quyết toán công nợ, bảo hành 12 tháng (giữ lại 5% hoặc thư bảo lãnh). Cần chuẩn hóa mã alias `<<CTY_DAI_DIEN>>`, `<<KH_DAI_DIEN>>`, `<<KH_DC>>`. |
| 14 | 78 | `78_Quy_Che_Dan_Chu_va_Doi_Thoai.md` | **PASS (Minor Fix)** | Quy trình đối thoại 1 năm/lần chuẩn NĐ 145/2020 và NĐ 283/2026; ghi rõ Phòng Nhân sự không nhận KPI dự án. Cần chỉnh chuẩn hóa tên phòng ban và mã `<<CTY_DAI_DIEN>>`, `<<CTY_CD_CHU_TICH>>`. |
| 15 | 79 | `79_Bien_Ban_Doi_Thoai_Dinh_Ky.md` | **PASS (Minor Fix)** | Biên bản họp đối thoại thiết thực (PPE trên cao, lán trại nước sinh hoạt, phụ cấp leo cao); có gắn nhãn `◐ Cần xác nhận trước khi áp dụng`. Cần sửa mã alias `<<CTY_DAI_DIEN>>`, `<<CTY_CD_CHU_TICH>>`. |
| 16 | 80 | `80_So_Theo_Doi_Tiep_Nhan_Kien_Nghi.md` | **PASS (Minor Fix)** | Sổ theo dõi minh bạch, phân luồng thời gian giải quyết khẩn cấp (an toàn 2-4h, lán trại 24-48h). Cần sửa mã alias `<<CTY_DAI_DIEN>>`. |
| 17 | 81 | `81_Hop_Dong_Dich_Vu_Ca_Nhan_Ben_Ngoai.md` | **PASS (Minor Fix)** | Chuẩn xác pháp lý cao: Phân định rạch ròi hợp đồng dịch vụ dân sự (BLDS 2015) không phải HĐLĐ (tránh bị xử phạt); khấu trừ 10% thuế TNCN tại nguồn; BVDLCN 2025. Cần đổi `<<CTY_DAI_DIEN>>`, `<<CTY_DT>>`. |
| **III** | | **III_Luong_Thuong_Ke_Toan/** | | |
| 18 | 26 | `26_Bien_Ban_Danh_Gia_Cham_Thuong_An_Toan.md` | **PASS (Minor Fix)** | Thang điểm 100 gắn liền với đặc thù kết cấu thép (dây 2 móc giảm chấn, bán kính cẩu, toolbox meeting, near-miss); trả lương qua ngân hàng. Cần sửa mã `<<CTY_DAI_DIEN>>`, `<<CT_CHI_HUY_TRUONG>>`. |
| 19 | 29 | `29_Quy_Trinh_Tai_Chinh_Ke_Toan_Cong_Trinh.md` | **PASS (Minor Fix)** | Áp dụng đúng Thông tư 133/2016/TT-BTC (TK 154 theo mã công trình, tiểu khoản 1541, 1542, 1543, 1547); 100% trả lương qua ngân hàng; ghi rõ HC-NS không nhận KPI. Cần chỉnh chức danh Trưởng phòng Dự án (kiêm KD) và mã alias. |
| 20 | 31 | `31_Bang_Tong_Hop_Quyet_Toan_Chi_Phi_Cong_Trinh.md` | **CẦN SỬA (Revision)** | **Lỗi phân chia Quỹ thưởng KPI:** Mục 4 phân chia 50% BCH, 30% công nhân, 20% "Phòng Kỹ thuật - Thi công & KD" -> bỏ sót hoàn toàn **Phòng Kế toán – Tài chính** (được hưởng 5-10% theo Quy chế 23); sai tên phòng ban chức năng; chèn nhiều placeholder tự tạo vào bảng chi phí. |
| **IV** | | **IV_HSE_An_Toan_TNLD/** | | |
| 21 | 45 | `45_Bao_Cao_Tong_Ket_An_Toan_Cuoi_Cong_Trinh.md` | **PASS (Minor Fix)** | Chỉ số an toàn đầy đủ (Safe Man-hours, Fatalities = 0, LTI = 0, 100% thẻ nhóm 3); NĐ 207/2026 ở cuối; Giám đốc phê duyệt. Cần chuẩn hóa mã `<<CTY_DAI_DIEN>>`, `<<CT_CHI_HUY_TRUONG>>`, `<<KH_TEN>>`. |
| **V** | | **I_Hop_Dong_Nhan_Su/** | | |
| 22 | 15a | `15a_Bien_Ban_Vi_Pham.md` | **PASS (Minor Fix)** | **Tuyệt đối nghiêm cấm phạt tiền, trừ lương** (khoản 2 Điều 127 BLLĐ); chỉ lập biên bản ghi nhận khách quan tại hiện trường; căn cứ ở cuối. Cần chuẩn hóa mã placeholder. |
| 23 | 15b | `15b_Thong_Bao_Hop_Xu_Ly_Ky_Luat.md` | **PASS (Minor Fix)** | Báo trước ít nhất 05 ngày làm việc theo Điều 70 NĐ 145/2020; đầy đủ quyền bào chữa và thủ tục dời họp; Giám đốc ký; căn cứ ở cuối. Cần chuẩn hóa mã `<<CTY_DAI_DIEN>>`, `<<CT_CHI_HUY_TRUONG>>`. |
| 24 | 15c | `15c_Bien_Ban_Hop_Xu_Ly_Ky_Luat.md` | **PASS (Minor Fix)** | Phiên họp có BCH Công đoàn tham gia; tuân thủ 04 hình thức kỷ luật luật định, tuyệt đối cấm phạt tiền/trừ lương; Giám đốc chủ trì. Cần chuẩn hóa mã alias `<<CTY_DAI_DIEN>>`, `<<CTY_CD_CHU_TICH>>`. |
| 25 | 15d | `15d_Quyet_Dinh_Xu_Ly_Ky_Luat.md` | **PASS (Minor Fix)** | Áp dụng hình thức luật định (khiển trách); thời hiệu 03 tháng đương nhiên xóa án tích (Điều 126 BLLĐ); Giám đốc ký; căn cứ ở cuối. Cần chuẩn hóa mã alias `<<CTY_DAI_DIEN>>`. |

---

## PHẦN II. ĐÁNH GIÁ ĐỘC LẬP THEO CÁC TIÊU CHÍ BẮT BUỘC

### 1. Tiêu chí 1: Placeholder & Tên riêng (Đối chiếu `00_Ma_Data.md`)
- **Tên riêng SAMIN:** **ĐẠT 100%**. Toàn bộ 25 file đã loại bỏ hoàn toàn việc hardcode tên riêng "SAMIN" / "Samin", thay thế bằng các biến `<<CTY_TEN>>`, `<<CTY_TEN_VT>>`.
- **Placeholder kiểu cũ `{{...}}`:** **ĐẠT 100%**. Không còn xuất hiện định dạng dấu ngoặc nhọn cũ `{{...}}`.
- **Placeholder chuẩn `00_Ma_Data.md`:**
  - Có 8/25 file tuân thủ hoàn hảo danh mục `00_Ma_Data.md` (Files 63, 64, 66, 67, 68, 69, 74, 76).
  - Có 17/25 file xuất hiện hiện tượng tạo các mã **placeholder alias** (mã tự tạo thay cho mã đã được quy chuẩn hóa trong `00_Ma_Data.md`), dẫn đến nguy cơ các công cụ tự động hóa (script Python, mail merge) bị lỗi khi quét theo `du_lieu.json` hoặc tiêu đề CSV mailing:
    + `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` (xuất hiện trong 15 file) $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<CTY_DAI_DIEN>>`.
    + `<<CHT_TEN>>` hoặc `<<CHT_DAI_DIEN>>` (xuất hiện trong 8 file) $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<CT_CHI_HUY_TRUONG>>`.
    + `<<KTT_TEN>>` (xuất hiện trong 5 file) $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<CTY_KE_TOAN_TRUONG>>`.
    + `<<CHU_TICH_CONG_DOAN>>` (xuất hiện trong 4 file) $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<CTY_CD_CHU_TICH>>`.
    + `<<CDT_TEN>>` (xuất hiện trong 3 file) $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<KH_TEN>>`.
    + `<<KH_DIA_CHI>>` và `<<KH_CHUC_VU>>` (xuất hiện trong 2 file) $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<KH_DC>>` và `<<KH_CHUC_DANH>>`.
    + `<<NCC_DIA_CHI>>` và `<<NCC_NGUOI_DAI_DIEN>>` $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<NCC_DC>>` và `<<NCC_DAI_DIEN>>`.
    + `<<NGAY_KHOI_CONG>>`, `<<NGAY_HOAN_THANH>>` $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<CT_NGAY_KHOI_CONG>>`, `<<CT_NGAY_HOAN_THANH>>`.
    + `<<CTY_SO_DIEN_THOAI>>` $\rightarrow$ Chuẩn `00_Ma_Data.md` là: `<<CTY_DT>>`.
- **Quy ước về ô bảng tính điền tay:** Tại một số biểu mẫu (File 72, 75, 77, 31), người soạn thảo đã gắn mã placeholder vào từng ô con số (`<<KL_COT_KEO>>`, `<<TT_COT_KEO>>`, `<<DT_1541>>`...). Cần lưu ý theo hướng dẫn tại `00_Ma_Data.md` (dòng 3): "Các ô để người dùng điền tay khi vận hành (dòng kẻ, bảng trống) không dùng mã" nhằm tránh làm rác hệ thống danh mục mã dữ liệu.

### 2. Tiêu chí 2: Các nguyên tắc quản trị cốt lõi

#### a) Thẩm quyền ký kết cấp Công ty
- **ĐẠT 100%**: Thống nhất **Giám đốc** là người có thẩm quyền duy nhất ký toàn bộ quyết định, quy chế, hợp đồng kinh tế và phê duyệt cấp Công ty.
- Các biểu mẫu tại hiện trường phân định thẩm quyền rõ ràng: Chỉ huy trưởng ký nghiệm thu, bàn giao vật tư, nhật ký thi công; Kỹ sư an toàn ký biên bản vi phạm, phiếu an toàn; Thư ký ghi chép; Giám đốc là người ký phê duyệt ban hành cuối cùng.
- *Lưu ý vi phạm:* File 71 (bước 4) đưa thẩm quyền duyệt báo giá cho "Phó Giám đốc / Giám đốc điều hành" là không phù hợp với cơ cấu thực tế, cần sửa đổi.

#### b) Cơ cấu tổ chức 04 phòng ban chức năng
- Mô hình chuẩn đã được chuẩn hóa tại `README.md` và `63_Quy_Che_To_Chuc_Phan_Quyen_Chuc_Danh_Bao_Cao.md`:
  1. **Phòng Thi công** (quản lý công trường, chỉ huy trưởng, kỹ thuật, an toàn và tổ thợ);
  2. **Phòng Dự án (kiêm Kinh doanh)** (bóc tách khối lượng, đàm phán hợp đồng thầu phụ, mua vật tư kết cấu thép);
  3. **Phòng Kế toán – Tài chính** (kế toán, dòng tiền, thanh toán, lương, thuế);
  4. **Phòng Hành chính – Nhân sự** (hồ sơ lao động, BHXH, bảo vệ dữ liệu cá nhân).
- *Lỗi phát hiện:* Một số file (71, 29, 31, 65, 78) còn dùng tên cũ "Phòng Kỹ thuật", "Phòng Kinh doanh" riêng biệt, hoặc "Phòng Kỹ thuật - Thi công". Cần thống nhất tuyệt đối về tên gọi 04 phòng ban nêu trên.

#### c) Phòng Hành chính – Nhân sự KHÔNG tham gia Quỹ thưởng KPI dự án
- **ĐẠT XUẤT SẮC**:
  + File 63 (Điều 3 khoản 4) khẳng định rõ: "Phòng Hành chính – Nhân sự KHÔNG tham gia phân chia Quỹ KPI dự án (theo đúng quy tắc quản trị thực tế của Công ty quy định tại README và Bảng tham số)".
  + File 31 (Mục 4.3) ghi rõ: "Phòng Hành chính - Nhân sự KHÔNG tham gia trích chia quỹ thưởng KPI dự án này".
  + File 29 (Điều 4.2) và File 78 (Điều 5.2) đều nhấn mạnh quy định loại trừ này nhằm đảm bảo tính khách quan của công tác nhân sự.

#### d) Chế độ kế toán áp dụng Thông tư 133/2016/TT-BTC
- **ĐẠT 100%**: File 29 và File 31 áp dụng chuẩn xác Chế độ kế toán doanh nghiệp nhỏ và vừa theo **Thông tư 133/2016/TT-BTC**:
  + Tập hợp chi phí giá thành thi công qua **Tài khoản 154** mở chi tiết theo từng mã công trình (`<<CT_MA>>`).
  + Các tiểu khoản chuẩn: 1541 (Nguyên vật liệu trực tiếp), 1542 (Nhân công trực tiếp), 1543 (Máy thi công), 1547 (Chi phí chung công trình).
  + Kết chuyển giá vốn sang TK 632; hạch toán doanh thu TK 5112, công nợ TK 131, thuế VAT TK 33311.
  + Không trộn lẫn mẫu biểu của Thông tư 200/2014/TT-BTC hay Thông tư 99/2025/TT-BTC.

#### e) Trả lương 100% qua tài khoản ngân hàng chính chủ
- **ĐẠT 100%**: Toàn bộ các quy chế và quy trình (29, 63, 78, 79, 26, 31) đều quán triệt nguyên tắc chuyển đổi số: 100% chi trả lương, phụ cấp, thưởng an toàn qua tài khoản ngân hàng cá nhân chính chủ của người lao động. Tuyệt đối không chi tiền mặt tại công trường.

#### f) Tuyệt đối KHÔNG phạt tiền, trừ lương thay kỷ luật lao động
- **ĐẠT 100% (Rất xuất sắc)**:
  + Bộ 04 văn bản kỷ luật `15a`, `15b`, `15c`, `15d` tại Nhóm I đều đặt khung cảnh báo pháp lý nổi bật: viện dẫn khoản 2 Điều 127 Bộ luật Lao động 2019, **tuyệt đối nghiêm cấm phạt tiền hoặc trừ lương người lao động**.
  + File 76 (Checklist rủi ro mục 2.5) đưa tiêu chí từ chối các quy định phạt tiền nội bộ vô lý của Tổng thầu.
  + Mọi vi phạm chỉ xử lý theo 04 hình thức luật định (Điều 124 BLLĐ): Khiển trách, kéo dài nâng lương, cách chức, sa thải.

#### g) Cập nhật căn cứ pháp lý mới nhất và vị trí đặt
- **Căn cứ pháp lý 2026**: Toàn bộ 25 văn bản đã cập nhật đầy đủ các văn bản quy phạm pháp luật mới nhất:
  + Nghị định 207/2026/NĐ-CP & Thông tư 32/2026/TT-BXD (thay thế Nghị định 06/2021/NĐ-CP và Thông tư 10/2021/TT-BXD về quản lý chất lượng thi công xây dựng).
  + Nghị định 283/2026/NĐ-CP (thay thế Nghị định 12/2022/NĐ-CP về xử phạt vi phạm hành chính trong lĩnh vực lao động, bảo hiểm xã hội).
  + Luật Bảo vệ dữ liệu cá nhân 91/2025/QH15 & Nghị định 356/2025/NĐ-CP (hiệu lực 01/01/2026).
  + Luật Xây dựng số 135/2025/QH15.
- **Vị trí đặt căn cứ pháp lý**: **ĐẠT 100%**. Toàn bộ 25 văn bản đều tuân thủ quy tắc kiến trúc hệ thống: Mục Căn cứ pháp lý được đặt ở **CUỐI VĂN BẢN** (hoặc chương cuối cùng), không rải rác trong thân văn bản, giúp văn bản gọn gàng và dễ cập nhật khi luật thay đổi.

### 3. Tiêu chí 3: Quản lý các điểm cờ cảnh báo `◐`
- Các điểm cần Giám đốc hoặc chuyên gia xác nhận đều được gắn ký hiệu `◐` kèm nhãn giải thích rõ ràng:
  + File 63 & 66: Gắn nhãn đối với quy định đăng ký lao động trực tuyến theo NĐ 318/2025 và mẫu sổ lao động.
  + File 71: Gắn nhãn `◐ cần xác nhận trước khi áp dụng` đối với các điều khoản thương thảo hợp đồng thầu phụ bất lợi.
  + File 79: Gắn nhãn `◐ Cần xác nhận trước khi áp dụng` đối với đề xuất thưởng Tết cho công nhân dưới 1 tháng căn cứ kết quả tài chính cuối năm.

---

## PHẦN III. PHÂN TÍCH CHI TIẾT 02 VĂN BẢN CẦN CHỈNH SỬA NGHIỆP VỤ (REVISION)

### 1. File `VI_Thi_Cong_Kinh_Doanh/71_Quy_Trinh_Kinh_Doanh_Bao_Gia_Quan_Ly_Hop_Dong.md`
- **Vấn đề 1 (Xung đột phân cấp thẩm quyền):**
  + *Hiện trạng (dòng 92-94):* Bảng phân cấp phê duyệt báo giá quy định: Dưới 1 tỷ đồng (Trưởng phòng Kinh doanh duyệt); từ 1 đến 5 tỷ đồng ("Phó Giám đốc / Giám đốc điều hành duyệt"); trên 5 tỷ đồng (Giám đốc duyệt).
  + *Sai lệch:* Công ty quy mô nhỏ (~10 người văn phòng), không có chức danh "Phó Giám đốc" hay "Giám đốc điều hành". Ngoài ra, việc hardcode con số "1 tỷ", "5 tỷ" vi phạm nguyên tắc quản trị tại `00-README` và `00-bang-tham-so` (các ngưỡng giá trị phải tham chiếu theo tham số `<<TS_NGUONG_BAO_GIA>>`).
  + *Hướng sửa chữa:* Sửa lại bảng phân quyền theo đúng File 63 (Điều 5):
    * Gói thầu có giá trị $\le$ `<<TS_NGUONG_BAO_GIA>>`: Kỹ sư dự toán đề xuất $\rightarrow$ Trưởng phòng Dự án (kiêm Kinh doanh) phê duyệt.
    * Gói thầu có giá trị $>$ `<<TS_NGUONG_BAO_GIA>>`: Trưởng phòng Dự án trình $\rightarrow$ Giám đốc Công ty phê duyệt và ký.
- **Vấn đề 2 (Cơ cấu phòng ban):**
  + *Hiện trạng:* Văn bản chia nhỏ thành "Phòng Kinh doanh - Đấu thầu" và "Phòng Kỹ thuật".
  + *Hướng sửa chữa:* Hợp nhất tên gọi theo chuẩn 04 phòng ban: "Phòng Dự án (kiêm Kinh doanh)" chịu trách nhiệm bóc tách kỹ thuật, dự toán, báo giá và mua vật tư; "Phòng Thi công" tiếp nhận hồ sơ để tổ chức thi công tại công trường.
- **Vấn đề 3 (Placeholder):** Đổi `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` $\rightarrow$ `<<CTY_DAI_DIEN>>`; `<<CDT_TEN>>` $\rightarrow$ `<<KH_TEN>>`; `<<CHT_TEN>>` $\rightarrow$ `<<CT_CHI_HUY_TRUONG>>`.

### 2. File `III_Luong_Thuong_Ke_Toan/31_Bang_Tong_Hop_Quyet_Toan_Chi_Phi_Cong_Trinh.md`
- **Vấn đề 1 (Xung đột phân chia Quỹ thưởng KPI dự án):**
  + *Hiện trạng (dòng 78-80):*
    * Ban Chỉ huy công trường (Chỉ huy trưởng, kỹ sư, HSE): 50% quỹ thưởng.
    * Tổ đội công nhân lắp dựng & thợ hàn nòng cốt: 30% quỹ thưởng.
    * Phòng Kỹ thuật - Thi công & Phòng Kinh doanh: 20% quỹ thưởng.
  + *Sai lệch nghiêm trọng:*
    * Đã bỏ sót hoàn toàn **Phòng Kế toán – Tài chính**. Theo Quy chế lương KPI dự án số 23 (`23_Quy_Che_Luong_KPI_Du_An_2026.md` Điều 8) và `README.md`, quỹ KPI của dự án được phân bổ cho 03 phòng ban: Phòng Thi công (60-70%), Phòng Dự án kiêm Kinh doanh (20-30%), và **Phòng Kế toán – Tài chính (5-10%)**.
    * Dùng sai tên phòng ban ("Phòng Kỹ thuật - Thi công & Phòng Kinh doanh").
  + *Hướng sửa chữa:* Điều chỉnh Mục 4.2 của File 31 cho khớp với Quy chế 23:
    * Khối công trường trực thuộc Phòng Thi công (gồm Ban chỉ huy công trường, an toàn và tổ thợ): Hưởng 65% quỹ thưởng;
    * Phòng Dự án (kiêm Kinh doanh): Hưởng 25% quỹ thưởng;
    * Phòng Kế toán – Tài chính: Hưởng 10% quỹ thưởng;
    * Khẳng định: Phòng Hành chính - Nhân sự KHÔNG tham gia trích chia quỹ thưởng KPI dự án.
- **Vấn đề 2 (Placeholder):**
  + Đổi `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` $\rightarrow$ `<<CTY_DAI_DIEN>>`; `<<KTT_TEN>>` $\rightarrow$ `<<CTY_KE_TOAN_TRUONG>>`; `<<CHT_TEN>>` $\rightarrow$ `<<CT_CHI_HUY_TRUONG>>`; `<<CDT_TEN>>` $\rightarrow$ `<<KH_TEN>>`.
  + `<<NGAY_KHOI_CONG>>` $\rightarrow$ `<<CT_NGAY_KHOI_CONG>>`; `<<NGAY_HOAN_THANH>>` $\rightarrow$ `<<CT_NGAY_HOAN_THANH>>`.

---

## PHẦN IV. BẢNG TRA CỨU ĐỒNG BỘ MÃ PLACEHOLDER (ALIAS MAPPING)

Để hệ thống 25 văn bản vận hành trơn tru với các công cụ tự động (Python/Mailing) theo đúng `bo-van-ban/00_Ma_Data.md`, khuyến nghị thực hiện chuẩn hóa thay thế đồng loạt các mã alias sau:

| Mã Alias đang dùng trong các file | Mã Chuẩn bắt buộc theo `00_Ma_Data.md` | Các file cần chuẩn hóa |
|:---|:---|:---|
| `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` | `<<CTY_DAI_DIEN>>` | 15b, 15c, 15d, 26, 29, 31, 45, 65, 71, 72, 75, 77, 78, 79, 80, 81 |
| `<<CHT_TEN>>` hoặc `<<CHT_DAI_DIEN>>` | `<<CT_CHI_HUY_TRUONG>>` | 15b, 15c, 26, 29, 31, 45, 71, 75, 79 |
| `<<KTT_TEN>>` | `<<CTY_KE_TOAN_TRUONG>>` | 29, 31, 65, 79 |
| `<<CHU_TICH_CONG_DOAN>>` | `<<CTY_CD_CHU_TICH>>` | 15c, 78, 79 |
| `<<CDT_TEN>>` | `<<KH_TEN>>` | 31, 45, 71 |
| `<<KH_DIA_CHI>>` | `<<KH_DC>>` | 72, 77 |
| `<<KH_CHUC_VU>>` | `<<KH_CHUC_DANH>>` | 72, 77 |
| `<<KH_NGUOI_DAI_DIEN>>` | `<<KH_DAI_DIEN>>` | 72, 77 |
| `<<NCC_DIA_CHI>>` | `<<NCC_DC>>` | 75 |
| `<<NCC_NGUOI_DAI_DIEN>>` | `<<NCC_DAI_DIEN>>` | 75 |
| `<<NCC_CHUC_VU>>` | `<<NCC_CHUC_DANH>>` *(nếu có)* | 75 |
| `<<CTY_SO_DIEN_THOAI>>` | `<<CTY_DT>>` | 77, 81 |
| `<<NGAY_KHOI_CONG>>` | `<<CT_NGAY_KHOI_CONG>>` | 31, 45 |
| `<<NGAY_HOAN_THANH>>` | `<<CT_NGAY_HOAN_THANH>>` | 31, 45 |
| `<<HD_NGAY>>` | `<<KH_HD_NGAY>>` hoặc `<<HD_NGAY_KY>>` | 77 |
| `<<HO_TEN_NLD>>` | `<<NLD_HO_TEN>>` | 80 |

---

## PHẦN V. KẾT LUẬN VÀ KIẾN NGHỊ CỦA CHUYÊN GIA QC

### 1. Đánh giá chung
- **Chất lượng nội dung chuyên môn:** **RẤT XUẤT SẮC**. Bộ 25 văn bản Nhóm C & D thể hiện mức độ am hiểu thực tế sâu sắc về ngành thi công lắp dựng kết cấu thép nhà xưởng công nghiệp (từ công tác cẩu lắp dầm kèo, an toàn làm việc trên cao, siết bu lông cờ-lê lực, nghiệm thu công việc che khuất, bảo quản bãi thép, hợp đồng thầu phụ đến quy trình hạch toán kế toán TK 154 và dân chủ cơ sở).
- **Tính tuân thủ pháp luật:** Cực kỳ chặt chẽ. Đã bám sát toàn bộ các văn bản quy phạm pháp luật cập nhật đến tháng 10/2026 (NĐ 207/2026, TT 32/2026, NĐ 283/2026, Luật BVDLCN 2025, NĐ 356/2025). Đặc biệt, bộ hồ sơ xử lý kỷ luật (15a - 15d) tuân thủ nghiêm ngặt lệnh cấm phạt tiền, trừ lương theo Bộ luật Lao động 2019.
- **Tính thống nhất hệ thống:** Đã đồng bộ tốt với `00-README-huong-dan-ban-hanh.md`, các căn cứ pháp lý được quy hoạch khoa học ở cuối văn bản.

### 2. Kế hoạch hành động khuyến nghị
1. **Ưu tiên 1 (Khắc phục nội dung 02 file):**
   - Chỉnh sửa File `71_Quy_Trinh_Kinh_Doanh_Bao_Gia_Quan_Ly_Hop_Dong.md`: đưa thẩm quyền duyệt báo giá về đúng Giám đốc theo ngưỡng tham số `<<TS_NGUONG_BAO_GIA>>` của File 63; hợp nhất tên phòng ban về "Phòng Dự án (kiêm Kinh doanh)" và "Phòng Thi công".
   - Chỉnh sửa File `31_Bang_Tong_Hop_Quyet_Toan_Chi_Phi_Cong_Trinh.md`: cập nhật lại nguyên tắc phân chia Quỹ thưởng KPI dự án bao gồm đủ 03 phòng ban (Thi công, Dự án, Kế toán - Tài chính) theo đúng Quy chế lương KPI số 23.
2. **Ưu tiên 2 (Chuẩn hóa mã Placeholder):**
   - Chạy script chuẩn hóa tự động các mã alias theo Bảng tra cứu tại Phần IV (đổi `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` $\rightarrow$ `<<CTY_DAI_DIEN>>`, `<<CHT_TEN>>` $\rightarrow$ `<<CT_CHI_HUY_TRUONG>>`...).
3. **Tiến hành ban hành:**
   - Sau khi thực hiện 2 bước trên, toàn bộ 25 văn bản hoàn toàn đạt chuẩn chất lượng cấp cao nhất (Grade A+) để Giám đốc Công ty ký duyệt ban hành chính thức.

---
*Báo cáo được lập bởi Chuyên gia Kiểm định Độc lập (QC Model High/Pro).*
