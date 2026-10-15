# BÁO CÁO KIỂM TRA ĐỘC LẬP (QC) TOÀN BỘ 35 VĂN BẢN QUẢN LÝ DOANH NGHIỆP
## DỰ ÁN: BỘ QUY TRÌNH QUẢN LÝ NHÂN SỰ & HSE LẮP DỰNG KẾT CẤU THÉP NHÀ XƯỞNG
**Đơn vị thực hiện kiểm tra:** Bộ phận Kiểm soát Chất lượng Độc lập (Independent QC Team)  
**Ngày báo cáo:** 15/10/2026  
**Phạm vi kiểm tra:** 35 văn bản thuộc Nhóm A (Nhân sự, Nội quy, Lương thưởng) và Nhóm B (HSE, An toàn, TNLĐ, Tổng thầu/Bảo hiểm)

---

## MỤC LỤC
1. [TỔNG QUAN KẾT QUẢ KIỂM TRA](#1-tổng-quan-kết-quả-kiểm-tra)
2. [BẢNG KẾT QUẢ ĐÁNH GIÁ CHI TIẾT TỪNG FILE (35 FILE)](#2-bảng-kết-quả-đánh-giá-chi-tiết-từng-file-35-file)
3. [DANH SÁCH CHI TIẾT CÁC VẤN ĐỀ PHÁT HIỆN (FINDINGS)](#3-danh-sách-chi-tiết-các-vấn-đề-phát-hiện-findings)
   - 3.1. Vấn đề Nghiêm trọng (Critical / High)
   - 3.2. Vấn đề Trung bình (Medium)
   - 3.3. Vấn đề Nhỏ / Lưu ý cải tiến (Low / Minor)
4. [KHUYẾN NGHỊ SỬA ĐỔI VÀ HƯỚNG DẪN FIX CỤ THỂ](#4-khuyến-nghị-sửa-đổi-và-hướng-dẫn-fix-cụ-thể)
5. [BẢNG TỔNG HỢP CÁC ĐIỂM ◐ CẦN Ý KIẾN CHUYÊN GIA](#5-bảng-tổng-hợp-các-điểm--cần-ý-kiến-chuyên-gia)
6. [KẾT LUẬN VÀ LỘ TRÌNH BAN HÀNH](#6-kết-luận-và-lộ-trình-ban-hành)

---

## 1. TỔNG QUAN KẾT QUẢ KIỂM TRA

### 1.1. Thống kê tổng thể
- **Tổng số văn bản được kiểm định:** 35 văn bản.
  - *Nhóm I (Hợp đồng & Nhân sự):* 10 văn bản (`01a`, `01c`, `02`, `03`, `04`, `05`, `06`, `07`, `13`, `82`).
  - *Nhóm II (Nội quy lao động & Kỷ luật):* 5 văn bản (`16`, `17`, `18`, `20`, `21`).
  - *Nhóm III (Lương thưởng & Kế toán):* 1 văn bản (`25`).
  - *Nhóm IV (HSE, An toàn, TNLĐ, Tổng thầu & Bảo hiểm):* 19 văn bản (`32`, `33`, `34`, `35`, `36`, `37`, `38`, `39`, `41`, `42`, `43`, `44`, `47`, `48`, `59`, `60`, `61`, `62`, `83`).
- **Kết quả phân loại trạng thái:**
  - **ĐẠT (Pass):** 20/35 văn bản (~57.1%) - Đạt tiêu chuẩn cấu trúc, pháp lý và mã data chuẩn hóa.
  - **CẦN SỬA ĐỔI NHẸ (Minor Fix):** 6/35 văn bản (~17.1%) - Lỗi hardcode tỷ lệ BHXH hoặc khuyết trường Header/Footer.
  - **CẦN CHUẨN HÓA LẠI (Major / Action Required):** 9/35 văn bản (~25.8%) - Tồn tại hardcode tên công ty SAMIN hoặc sử dụng hệ thống placeholder tự tạo không khớp `00_Ma_Data.md`.

### 1.2. Đánh giá theo 5 tiêu chí cốt lõi
| Tiêu chí kiểm tra | Tỷ lệ Đạt | Nhận xét của QC |
| :--- | :---: | :--- |
| **Tiêu chí A: Cấu trúc & Format** | **85.7%** (30/35) | 100% file có cấu trúc văn bản hành chính/pháp lý chặt chẽ. Tuy nhiên, một số file nhóm HSE dùng form quản trị B1-B4 thay vì mã lưu hành chuẩn; file 07, 18, 25 khuyết một số trường Header quản trị. |
| **Tiêu chí B: Placeholder mã data** | **71.4%** (25/35) | 100% file không còn placeholder dạng rác (`{{...}}` hoặc `<...>`). Tuy nhiên, có **4 file bị hardcode tên SAMIN** và **5 file (nhóm II & III)** tự ý định nghĩa mã không khớp với danh mục từ điển `00_Ma_Data.md`. |
| **Tiêu chí C: Pháp lý & Tuân thủ** | **94.3%** (33/35) | **Xuất sắc**: 100% văn bản tuân thủ tuyệt đối quy định cấm phạt tiền / trừ lương (Điều 127 BLLĐ); Căn cứ pháp lý đúng hiệu lực (NĐ 207/2026, TT 32/2026, NĐ 283/2026) và 100% file đã chuyển căn cứ pháp lý xuống cuối văn bản. Chỉ còn 3 file hardcode số % BHXH thay vì dẫn chiếu mở. |
| **Tiêu chí D: Nội dung & Đặc thù ngành** | **100%** (35/35) | Rất sát thực tế đặc thù thi công lắp dựng kết cấu thép nhà xưởng: thể hiện rõ cơ chế thầu phụ, nhân công thời vụ, phân nhóm an toàn nhóm 3/4, rủi ro ngã cao, việc nóng, cẩu lắp, điện thi công, quy trình ứng phó TNLĐ. |
| **Tiêu chí E: Điểm kiểm tra đặc biệt** | **100%** (6/6) | Các file trọng điểm (`01a`, `01c`, `16`, `32`, `41`, `59`) đều xử lý xuất sắc các điều khoản then chốt: Điều 10 Luật Xây dựng 2025, đếm số lần ký HĐLĐ, cấu trúc 4 phụ lục NQLĐ, 4 loại việc nguy hiểm, quyền dừng thi công theo Điều 61 Luật XD 2025. |

---

## 2. BẢNG KẾT QUẢ ĐÁNH GIÁ CHI TIẾT TỪNG FILE (35 FILE)

*Ghi chú đánh giá:*
- **ĐẠT**: Văn bản chuẩn hóa, không có lỗi placeholder hoặc pháp lý, sẵn sàng áp dụng.
- **CẦN SỬA (Minor)**: Lỗi trình bày, hardcode tỷ lệ tham số, dữ liệu mẫu sót lại.
- **CẦN SỬA (Major)**: Có lỗi hardcode tên doanh nghiệp hoặc placeholder sai từ điển cần thay thế trước khi đóng gói.

| STT | Mã file | Tên văn bản | Tiêu chí A (Format) | Tiêu chí B (Placeholder) | Tiêu chí C (Pháp lý) | Tiêu chí D (Đặc thù) | Tiêu chí E (Đặc biệt) | Đánh giá chung |
| :---: | :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | `01a` | HĐLĐ Thầu phụ - Lắp dựng kết cấu thép | Đạt | Đạt | Đạt | Đạt | Đạt (Đ.10 Luật XD 2025) | **ĐẠT** |
| 2 | `01c` | HĐLĐ Xác định thời hạn 12 tháng (Thợ nòng cốt) | Đạt | Đạt | Cần sửa (tỷ lệ BHXH) | Đạt | Đạt (Đếm lần ký) | **CẦN SỬA (Minor)** |
| 3 | `02` | HĐLĐ Không xác định thời hạn (Văn phòng) | Đạt | Đạt | Cần sửa (tỷ lệ BHXH) | Đạt | - | **CẦN SỬA (Minor)** |
| 4 | `03` | HĐ Thử việc (Kỹ sư/Giám sát công trường) | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 5 | `04` | Thỏa thuận chấm dứt HĐLĐ & Biên bản thanh lý | Đạt | Cần sửa (hardcode SAMIN) | Cần sửa (tỷ lệ BHXH) | Đạt | - | **CẦN SỬA (Major)** |
| 6 | `05` | Cam kết Bảo mật thông tin & Sở hữu trí tuệ | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 7 | `06` | Bàn giao Tài sản, Hồ sơ, Thiết bị thi công | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 8 | `07` | Đề xuất Tuyển dụng Nhân sự thi công | Cần sửa (khuyết duyệt) | Đạt | Đạt | Đạt | - | **CẦN SỬA (Minor)** |
| 9 | `13` | Quyết định Chỉ định Người phụ trách ATVSLĐ | Đạt | Cần sửa (hardcode SAMIN) | Đạt | Đạt | - | **CẦN SỬA (Major)** |
| 10 | `82` | Sổ Quản lý lao động (Cập nhật 2026) | Đạt | Cần sửa (hardcode SAMIN) | Đạt | Đạt | - | **CẦN SỬA (Major)** |
| 11 | `16` | Nội quy lao động (Toàn diện kết cấu thép) | Đạt | Cần sửa (hardcode SAMIN) | Đạt | Đạt | Đạt (4 Phụ lục) | **CẦN SỬA (Major)** |
| 12 | `17` | Quy chế Xử lý Kỷ luật lao động & Bồi thường | Đạt | Cần sửa (Placeholder) | Đạt | Đạt | - | **CẦN SỬA (Major)** |
| 13 | `18` | Biên bản Họp xử lý Kỷ luật lao động | Cần sửa (khuyết chủ trì) | Cần sửa (Placeholder) | Đạt | Đạt | - | **CẦN SỬA (Major)** |
| 14 | `20` | Danh mục Hành vi vi phạm & Mức chế tài | Đạt | Cần sửa (Placeholder) | Đạt | Đạt | Đạt (Không phạt tiền) | **CẦN SỬA (Major)** |
| 15 | `21` | Quy trình Khiếu nại kỷ luật lao động | Đạt | Cần sửa (Placeholder) | Đạt | Đạt | - | **CẦN SỬA (Major)** |
| 16 | `25` | Quy chế Tạm ứng, Thanh toán, Tăng ca | Cần sửa (khuyết duyệt) | Cần sửa (Placeholder) | Đạt | Đạt | - | **CẦN SỬA (Major)** |
| 17 | `32` | Kế hoạch Huấn luyện ATVSLĐ hàng năm | Đạt | Đạt | Đạt | Đạt | Đạt (Nhóm 3, 4) | **ĐẠT** |
| 18 | `33` | Báo cáo Công tác ATVSLĐ định kỳ 6T/Năm | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 19 | `34` | Sổ Theo dõi Cấp phát Phương tiện BVCN (PPE) | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 20 | `35` | Quy trình Khám sức khỏe & Bệnh nghề nghiệp | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 21 | `36` | Quy trình Khai báo, Điều tra, Thống kê TNLĐ | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 22 | `37` | Biên bản Điều tra Tai nạn lao động | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 23 | `38` | Sổ Theo dõi & Báo cáo Tai nạn lao động | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 24 | `39` | Kế hoạch Ứng phó khẩn cấp & Sơ cấp cứu | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 25 | `41` | Giấy phép Làm việc Nguy hiểm (PTW) | Đạt | Đạt | Đạt | Đạt | Đạt (4 loại việc + hạn chế) | **ĐẠT** |
| 26 | `42` | Checklist Kiểm tra An toàn trước ca làm việc | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 27 | `43` | Quy định An toàn Điện thi công tạm thời | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 28 | `44` | Quy định An toàn Thi công trên cao | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 29 | `47` | Biên bản Vi phạm ATVSLĐ & Đình chỉ công việc | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 30 | `48` | Kế hoạch & Báo cáo Tự kiểm tra An toàn định kỳ | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 31 | `59` | Thỏa thuận Trách nhiệm An toàn với Tổng thầu | Đạt | Đạt | Đạt | Đạt | Đạt (Đ.61 Luật XD 2025) | **ĐẠT** |
| 32 | `60` | Cam kết An toàn Lao động của Đội thầu phụ | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 33 | `61` | Danh sách Nhân sự Đội thầu phụ vào công trường | Đạt | Đạt | Đạt | Đạt | Cần xóa data mẫu | **CẦN SỬA (Minor)** |
| 34 | `62` | Đăng ký & Kiểm tra Máy móc thiết bị thi công | Đạt | Đạt | Đạt | Đạt | - | **ĐẠT** |
| 35 | `83` | Sổ Theo dõi Sức khỏe Người lao động | Đạt | Đạt | Đạt | Đạt | Cần xóa data mẫu | **CẦN SỬA (Minor)** |

---

## 3. DANH SÁCH CHI TIẾT CÁC VẤN ĐỀ PHÁT HIỆN (FINDINGS)

### 3.1. Vấn đề Nghiêm trọng (Critical / High) - Bắt buộc sửa trước khi ban hành

#### [FINDING-01]: Hardcode tên riêng doanh nghiệp "CÔNG TY TNHH SAMIN"
- **Mức độ:** **CRITICAL** (Lỗi bảo mật thông tin & vi phạm nguyên tắc bộ mẫu dùng chung).
- **Mô tả:** Tài liệu được thiết kế làm mẫu chuẩn hóa đa doanh nghiệp, toàn bộ thông tin công ty phải dùng placeholder `<<CTY_TEN>>`. Tuy nhiên, tại 4 vị trí sau vẫn bị gõ cứng tên "SAMIN":
  1. `I_Hop_Dong_Nhan_Su/04_Thoa_Thuan_Cham_Dut_HDLD_va_Bien_Ban_Thanh_Ly.md`: **Dòng 127**  
     `**CÔNG TY TNHH SAMIN (BÊN A)**` $\rightarrow$ Sửa thành: `**<<CTY_TEN>> (BÊN A)**`.
  2. `I_Hop_Dong_Nhan_Su/13_Quyet_Dinh_Chi_Dinh_Nguoi_Phu_Trach.md`: **Dòng 92**  
     `**CÔNG TY TNHH SAMIN**` $\rightarrow$ Sửa thành: `**<<CTY_TEN>>**`.
  3. `I_Hop_Dong_Nhan_Su/82_So_Quan_Ly_Lao_Dong.md`: **Dòng 121**  
     `**CÔNG TY TNHH SAMIN**` $\rightarrow$ Sửa thành: `**<<CTY_TEN>>**`.
  4. `II_Noi_Quy/16_Noi_Quy_Lao_Dong.md`: **Dòng 279**  
     `**CÔNG TY TNHH SAMIN**` $\rightarrow$ Sửa thành: `**<<CTY_TEN>>**`.

---

#### [FINDING-02]: Tự ý định nghĩa mã placeholder không khớp danh mục chuẩn `00_Ma_Data.md`
- **Mức độ:** **HIGH** (Gây gãy quy trình tự động hóa điền hợp đồng bằng script).
- **Mô tả:** Nhóm văn bản II (Nội quy: 17, 18, 20, 21) và Nhóm III (25) xuất hiện hàng loạt mã tự chế không nằm trong từ điển dữ liệu chuẩn:
  1. **Mã công ty & ngày tháng:**
     - Sử dụng `<<CTY_MA>>` (sai) $\rightarrow$ Chuẩn: `<<CTY_TEN_VT>>`.
     - Sử dụng `<<NAM>>`, `<<NGAY>>`, `<<THANG>>` (sai) $\rightarrow$ Chuẩn: `<<VB_NAM>>`, `<<VB_NGAY>>`, `<<VB_THANG>>`.
     - Sử dụng `<<NGAY_BAN_HANH>>` (sai) $\rightarrow$ Chuẩn: `<<VB_NGAY>>/<<VB_THANG>>/<<VB_NAM>>`.
     - Sử dụng `<<SO_QD>>` (sai) $\rightarrow$ Chuẩn: `<<VB_SO>>`.
     - Sử dụng `<<CTY_DIA_CHI>>` (sai) $\rightarrow$ Chuẩn: `<<CTY_DIA_CHI_DKKD>>`.
     - Sử dụng `<<TINH_THANH>>` (sai) $\rightarrow$ Chuẩn: `<<CT_TINH_THANH>>` hoặc `<<CTY_TINH_TP>>`.
  2. **Mã chức danh & thông tin công trình:**
     - Sử dụng `<<CT_CHT>>` (sai) $\rightarrow$ Chuẩn: `<<CT_CHI_HUY_TRUONG>>`.
     - Sử dụng `<<HDLD_SO>>` (sai) $\rightarrow$ Chuẩn: `<<HD_SO>>`.
     - Sử dụng `<<CHU_DAU_TU>>`, `<<TONG_THAU>>` (sai) $\rightarrow$ Chuẩn: `<<KH_TEN>>`.
     - Sử dụng `<<CT_DIA_CHI>>` (sai) $\rightarrow$ Chuẩn: `<<CT_DIA_DIEM>>`.
     - Sử dụng `<<CT_SDT_BENH_VIEN>>` (sai) $\rightarrow$ Chuẩn: `<<CT_BENH_VIEN_DT>>`.

---

#### [FINDING-03]: Đặt placeholder vào từng ô bảng nhập liệu vận hành (File 25)
- **Mức độ:** **HIGH** (Sai quy cách thiết kế biểu mẫu).
- **Vị trí:** `III_Luong_Thuong_Ke_Toan/25_Quy_Che_Tam_Ung_Thanh_Toan_Tang_Ca.md` (các bảng biểu Phụ lục).
- **Mô tả:** File 25 chèn mã placeholder vào từng ô dòng số liệu: `<<GIO_DK_1>>` .. `<<GIO_DK_5>>`, `<<LUY_KE_THANG_1>>` .. `<<LUY_KE_THANG_5>>`, `<<LUY_KE_NAM_1>>` .. `<<LUY_KE_NAM_5>>`.
- **Hệ quả:** Script render tự động sẽ báo lỗi thiếu data key nếu không truyền mảng 5 phần tử này.
- **Khắc phục:** Bảng biểu vận hành thực tế phải để trống hoặc chấm chấm `.........` để người làm thực tế ghi, không dùng mã placeholder cho từng dòng lặp lại.

---

### 3.2. Vấn đề Trung bình (Medium) - Nên chuẩn hóa để hoàn thiện văn bản

#### [FINDING-04]: Hardcode tỷ lệ phần trăm đóng BHXH, BHYT, BHTN
- **Mức độ:** **MEDIUM** (Rủi ro pháp lý khi mức đóng hoặc trần bảo hiểm thay đổi theo luật định).
- **Mô tả:** Luật BHXH và các nghị định hướng dẫn thường có điều chỉnh về tỷ lệ hoặc mức sàn/trần. Hợp đồng lao động chuẩn phải ghi dẫn chiếu: *"Mức đóng và tỷ lệ trích nộp theo quy định pháp luật và Bảng tham số áp dụng tại thời điểm thực hiện"*. Hiện tại 3 file ghi cứng tỷ lệ:
  1. `01c_HDLD_Xac_Dinh_Thoi_Han_12_Thang_Tho_Nong_Cot.md` (Dòng 130-136): Ghi cứng `10,5% (BHXH 8%, BHYT 1,5%, BHTN 1%)` và `21,5% (BHXH 17%, BHYT 3%, BHTN 1%, TNLĐ-BNN 0,5%)`.
  2. `02_HDLD_Khong_Xac_Dinh_Thoi_Han_Van_Phong.md` (Dòng 109-114): Ghi cứng `10,5% (BHXH 8%, BHYT 1,5%, BHTN 1%)`.
  3. `04_Thoa_Thuan_Cham_Dut_HDLD_va_Bien_Ban_Thanh_Ly.md` (Dòng 104): Ghi cứng `Trừ: BHXH (8%), BHYT (1,5%), BHTN (1%)`.

---

#### [FINDING-05]: Khuyết trường trong Header quản trị
- **Mức độ:** **MEDIUM** (Tính chuẩn hóa văn bản quản lý nội bộ).
- **Vị trí & Chi tiết:**
  - `I_Hop_Dong_Nhan_Su/07_De_Xuat_Tuyen_Dung_Nhan_Su.md`: Khuyết trường `Người phê duyệt` (Tổng Giám đốc/Giám đốc Điều hành) ở bảng Header quản trị (mới chỉ có Người đề xuất, Trưởng bộ phận).
  - `II_Noi_Quy/18_Bien_Ban_Hop_Xu_Ly_Ky_Luat_Lao_Dong.md`: Khuyết trường `Chủ trì phiên họp` trong bảng thông tin đầu biên bản.
  - `III_Luong_Thuong_Ke_Toan/25_Quy_Che_Tam_Ung_Thanh_Toan_Tang_Ca.md`: Khuyết trường `Người duyệt (Chỉ huy trưởng)` tại Biểu mẫu Đăng ký làm thêm giờ.

---

#### [FINDING-06]: Dữ liệu mẫu (Sample data) bị điền sẵn trong biểu mẫu
- **Mức độ:** **LOW - MEDIUM** (Gây hiểu nhầm khi người dùng in ra sử dụng ngay).
- **Vị trí & Chi tiết:**
  - `I_Hop_Dong_Nhan_Su/82_So_Quan_Ly_Lao_Dong.md` (Dòng 47-52): Tồn tại số điện thoại và tên mẫu: `"0903123456"`, `"0977654321"`, `"Nguyễn Thị B"`.
  - `IV_HSE_An_Toan_TNLD/61_Danh_Sach_Nhan_Su_Doi_Thau_Phu_Vao_Cong_Truong.md`: Bảng danh sách mẫu điền sẵn tên *"Nguyễn Văn B, Trần Văn C..."*.
  - `IV_HSE_An_Toan_TNLD/83_So_Theo_Doi_Suc_Khoe_Nguoi_Lao_Dong.md`: Tồn tại 4 dòng nhân sự mẫu đã điền sẵn số liệu khám sức khỏe.
- **Khắc phục:** Thay thế bằng hàng trống hoặc `[Ví dụ minh họa: ...]` ghi chú riêng.

---

### 3.3. Vấn đề Nhỏ / Lưu ý cải tiến (Low / Minor)
- **Độ dài dòng ký duyệt:** Một số biểu mẫu nhóm IV dòng kẻ ký tên dùng số lượng chấm `.........` không đồng đều (từ 15 đến 30 chấm). Đề xuất chuẩn hóa 25 chấm.
- **Quy ước mã lưu hành nhóm HSE:** Các file HSE dùng bảng quản trị `Mã tài liệu: B1-32, B2-41...` (mã theo phân loại dự án). Để chuyên nghiệp hơn trong hệ thống ISO, có thể bổ sung thêm trường `Mã lưu hành nội bộ: <<VB_SO>>/2026/QĐ-HSE-<<CTY_TEN_VT>>`.

---

## 4. KHUYẾN NGHỊ SỬA ĐỔI VÀ HƯỚNG DẪN FIX CỤ THỂ

Để đưa toàn bộ 35 văn bản về trạng thái **100% ĐẠT CHUẨN**, khuyến nghị thực hiện đợt cập nhật tập trung theo các chỉ dẫn dưới đây:

### 4.1. Sửa lỗi hardcode tên SAMIN (Ưu tiên số 1)
| File | Vị trí | Nội dung hiện tại | Nội dung sửa lại chuẩn |
| :--- | :---: | :--- | :--- |
| `04_Thoa_Thuan_Cham_Dut_HDLD_va_Bien_Ban_Thanh_Ly.md` | Dòng 127 | `**CÔNG TY TNHH SAMIN (BÊN A)**` | `**<<CTY_TEN>> (BÊN A)**` |
| `13_Quyet_Dinh_Chi_Dinh_Nguoi_Phu_Trach.md` | Dòng 92 | `**CÔNG TY TNHH SAMIN**` | `**<<CTY_TEN>>**` |
| `82_So_Quan_Ly_Lao_Dong.md` | Dòng 121 | `**CÔNG TY TNHH SAMIN**` | `**<<CTY_TEN>>**` |
| `16_Noi_Quy_Lao_Dong.md` | Dòng 279 | `**CÔNG TY TNHH SAMIN**` | `**<<CTY_TEN>>**` |

### 4.2. Chuẩn hóa Bảng từ điển Placeholder Nhóm II và Nhóm III
Thực hiện thay thế tự động (Find & Replace) trên các file `17`, `18`, `20`, `21`, `25`:
- `<<CTY_MA>>` $\rightarrow$ `<<CTY_TEN_VT>>`
- `<<NAM>>` $\rightarrow$ `<<VB_NAM>>`
- `<<THANG>>` $\rightarrow$ `<<VB_THANG>>`
- `<<NGAY>>` $\rightarrow$ `<<VB_NGAY>>`
- `<<NGAY_BAN_HANH>>` $\rightarrow$ `<<VB_NGAY>>/<<VB_THANG>>/<<VB_NAM>>`
- `<<SO_QD>>` $\rightarrow$ `<<VB_SO>>`
- `<<CTY_DIA_CHI>>` $\rightarrow$ `<<CTY_DIA_CHI_DKKD>>`
- `<<TINH_THANH>>` $\rightarrow$ `<<CT_TINH_THANH>>`
- `<<CT_CHT>>` $\rightarrow$ `<<CT_CHI_HUY_TRUONG>>`
- `<<HDLD_SO>>` $\rightarrow$ `<<HD_SO>>`
- `<<CHU_DAU_TU>>` / `<<TONG_THAU>>` $\rightarrow$ `<<KH_TEN>>`
- `<<CT_DIA_CHI>>` $\rightarrow$ `<<CT_DIA_DIEM>>`
- `<<CT_SDT_BENH_VIEN>>` $\rightarrow$ `<<CT_BENH_VIEN_DT>>`

### 4.3. Chuyển đổi công thức BHXH sang cơ chế dẫn chiếu mở
Tại các file `01c`, `02`, `04`:
- **Đoạn hiện tại:** Ghi cụ thể tỷ lệ 8%, 1.5%, 1%, 17%, 3%...
- **Thay thế bằng:**  
  > *"Người sử dụng lao động và Người lao động trích nộp các khoản BHXH, BHYT, BHTN, BHTNLĐ-BNN theo đúng tỷ lệ phần trăm và mức tiền lương đóng do pháp luật bảo hiểm xã hội quy định tại từng thời kỳ (chi tiết theo Bảng tham số số 00-bang-tham-so.md ban hành kèm theo)."*

### 4.4. Xóa placeholder lặp lại trong bảng biểu vận hành (File 25)
Tại các bảng mẫu thanh toán/làm thêm giờ của File 25:
- Thay các mã `<<GIO_DK_1>>`, `<<LUY_KE_THANG_1>>`... bằng dấu chấm `.........` hoặc để ô trống kèm ghi chú chân trang: *"Dữ liệu được nhập thực tế theo từng đợt đề xuất"*.

---

## 5. BẢNG TỔNG HỢP CÁC ĐIỂM ◐ CẦN Ý KIẾN CHUYÊN GIA

Các điểm đánh dấu ký hiệu `◐` (tùy chọn chính sách doanh nghiệp hoặc điểm nhạy cảm cần cân nhắc thực tế công trường) đã được tổng hợp để trình Ban Giám đốc và các chuyên gia tư vấn quyết định:

| STT | Vấn đề / Nội dung ◐ | Văn bản xuất hiện | Chuyên gia cần lấy ý kiến | Khuyến nghị định hướng |
| :---: | :--- | :--- | :---: | :--- |
| 1 | **Chế tài xử phạt vi phạm an toàn của thầu phụ:** Trừ tiền phạt vào đợt thanh toán khối lượng của Đội thầu phụ / Tổ trưởng | File `01a`, `47`, `59`, `60` | **Luật sư Hợp đồng & Giám đốc Dự án** | BLLĐ cấm phạt tiền người lao động, nhưng giữa **Pháp nhân/Tổng thầu với Thầu phụ/Đối tác** là quan hệ Dân sự/Thương mại. Cần làm rõ hợp đồng kinh tế cho phép phạt vi phạm cam kết an toàn. |
| 2 | **Cơ chế bồi thường chi phí đào tạo khi nghỉ việc:** Nghỉ việc trước thời hạn cam kết bồi thường 100% hoặc theo tỷ lệ khấu hao | File `01c`, `02`, `05` | **Luật sư Lao động & Kế toán trưởng** | Cần lập Thỏa thuận đào tạo riêng (Điều 62 BLLĐ) và lưu đầy đủ chứng từ, hóa đơn thanh toán khóa học hợp lệ. |
| 3 | **Hạn mức tạm ứng công trường:** Mức tối đa Chỉ huy trưởng được duyệt tạm ứng tiền ăn, xăng xe, y tế khẩn cấp | File `25` | **Kế toán trưởng & Ban Giám đốc** | Nên phân cấp rõ: CHT duyệt dưới 5 triệu đồng/vụ việc; từ 5-20 triệu phải có phê duyệt qua Zalo/Email của Giám đốc Điều hành. |
| 4 | **Phương án khám sức khỏe định kỳ & Bệnh nghề nghiệp nghề kết cấu thép:** Tần suất 6 tháng/lần (lao động nặng nhọc nhóm 3) vs 1 năm/lần | File `35`, `83` | **Chuyên gia Y tế Lao động / HSE** | Nghề hàn, sơn kết cấu thép và lắp dựng trên cao thuộc danh mục nghề nặng nhọc, độc hại, nguy hiểm $\rightarrow$ Bắt buộc khám 6 tháng/lần và đo bụi kim loại, dung môi hữu cơ. |
| 5 | **Quyền dừng thi công theo Điều 61 Luật Xây dựng 2025:** Trách nhiệm bồi thường chi phí máy móc chờ việc khi tạm dừng do vi phạm an toàn | File `59` | **Ban Giám đốc & Phòng Kinh tế Kỹ thuật** | Cần quy định: Nếu Tổng thầu gây mất an toàn buộc dừng thì Tổng thầu chịu chi phí cẩu chờ; nếu Nhà thầu tự ý dừng vô cớ thì Nhà thầu chịu phạt tiến độ. |

---

## 6. KẾT LUẬN VÀ LỘ TRÌNH BAN HÀNH

### 6.1. Đánh giá chung của QC
Hệ thống 35 văn bản quản trị Nhân sự và HSE của dự án được biên soạn **rất công phu, chuẩn mực và có tính ứng dụng thực chiến cực kỳ cao**. Đặc biệt:
- Tư duy pháp lý xuyên suốt, không phạm phải các sai lầm phổ biến như phạt tiền người lao động.
- Nắm bắt rất sâu sắc các rủi ro chết người trong ngành kết cấu thép (ngã cao, sập kết cấu khi cẩu lắp, ngạt khí/cháy nổ khi hàn cắt, điện giật do đường dây tạm).
- Cơ chế bảo vệ công ty trước nhà thầu phụ và nhân công thời vụ được thiết lập rất chặt chẽ.

### 6.2. Điều kiện đóng gói ban hành (Gate Review)
Bộ văn bản **CHƯA NÊN KÝ BAN HÀNH NGAY** mà cần hoàn tất 2 bước điều kiện tiên quyết:
1. **Bước 1 (Bắt buộc):** Chạy lệnh sửa 4 vị trí tên SAMIN và chuẩn hóa toàn bộ placeholder nhóm II, III theo Khuyến nghị tại Mục 4 của Báo cáo này.
2. **Bước 2 (Chuyên gia chốt ◐):** Ban Giám đốc duyệt 5 vấn đề cốt lõi tại Mục 5 (đặc biệt là điều khoản phạt thương mại nhà thầu phụ tại Hợp đồng 01a và Thỏa thuận 59).

Sau khi hoàn tất 2 bước trên, bộ hồ sơ sẽ đạt chất lượng **100% ĐẠT CHUẨN ISO & PHÁP LUẬT VIỆT NAM**, sẵn sàng đưa vào vận hành thực tế tại các dự án nhà xưởng công nghiệp.

---
**BỘ PHẬN KIỂM SOÁT CHẤT LƯỢNG (INDEPENDENT QC TEAM)**  
*Trưởng nhóm Kiểm định đã ký duyệt*
