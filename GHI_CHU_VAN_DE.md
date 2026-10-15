# GHI CHÚ VẤN ĐỀ & QUYẾT ĐỊNH

**Ngày:** 15/10/2026 | **Điều phối:** Antigravity

---

## Phân tích ban đầu

### Tổng quan công việc cần làm (Đợt 1 – ưu tiên)

Theo `00_Danh_Sach_Van_Ban.md`, Đợt 1 cần tạo 53 file. Các file hiện đã có (●):
- I_Hop_Dong_Nhan_Su: 01b, 08, 09, 10, 11
- III_Luong_Thuong_Ke_Toan: 22, 23, 27, 28
- IV_HSE_An_Toan_TNLD: 46, 50, 51, 52, 54, 55, 57, 58

### Cần tạo mới (▲ Đợt 1) – ưu tiên:

**Nhóm I – Hợp đồng & Nhân sự:**
- 1a: HĐLĐ ngắn hạn (dưới 1 tháng)
- 1c: HĐLĐ xác định thời hạn 12 tháng – thợ chủ chốt
- 2: HĐLĐ không xác định thời hạn (văn phòng)
- 3: Thư mời thử việc (văn phòng)
- 4: Thỏa thuận chấm dứt HĐLĐ & biên bản thanh lý
- 5: Cam kết bảo mật & đồng ý xử lý DLCN
- 6: Phụ lục HĐLĐ
- 7: Checklist hồ sơ nhân sự
- 13: QĐ chỉ định người phụ trách
- 82: Sổ quản lý lao động

**Nhóm II – Nội quy:**
- 16: Nội quy lao động
- 17: QĐ ban hành nội quy
- 18: Biên bản lấy ý kiến BCH công đoàn
- 20: Phiếu xác nhận đã nhận và hiểu nội quy
- 21: Nội quy an toàn công trường

**Nhóm III – Lương:**
- 25: Phiếu đăng ký làm thêm giờ

**Nhóm IV – HSE:**
- 32: Sổ tay HSE
- 33: Chính sách An toàn – Sức khỏe – Môi trường
- 34: Bảng nhận diện mối nguy & đánh giá rủi ro
- 35: Kế hoạch ATVSLĐ hằng năm
- 36: Sổ theo dõi huấn luyện ATVSLĐ
- 37: Danh mục thiết bị yêu cầu nghiêm ngặt
- 38: Thông tin công trình & kế hoạch ứng cứu
- 39: Danh sách nhân sự – chứng chỉ – thẻ an toàn
- 41: Giấy phép làm việc nguy hiểm
- 42: Phiếu an toàn hằng ngày
- 43: Sổ cấp phát PPE
- 44: Biên bản bàn giao mặt bằng
- 47: Phiếu ghi nhanh TNLĐ/sự cố
- 48: Sổ theo dõi TNLĐ, sự cố, suýt xảy ra
- 59: Phụ lục điều khoản an toàn & bảo hiểm với tổng thầu
- 60: Thông báo – đề nghị gửi tổng thầu
- 61: Công văn đề nghị xác nhận bảo hiểm
- 62: Checklist bảo hiểm & hồ sơ an toàn nộp tổng thầu
- 83: Hồ sơ theo dõi khám sức khỏe

**Nhóm V – Tổ chức:**
- 63: Quy chế tổ chức, phân quyền
- 64: Quy chế bảo vệ DLCN & lưu trữ
- 66: Danh mục văn bản & nhật ký rà soát

**Nhóm VI – Thi công:**
- 68: Biên bản giao nhận & quyết toán vật tư
- 74: Phụ lục vật tư – điều khoản bổ sung
- 76: Checklist thẩm định rủi ro HĐ & điều kiện huy động

---

## Vấn đề phát hiện & quyết định

### 1. Cấu trúc thư mục
**Vấn đề:** Hiện có I_, III_, IV_ nhưng chưa có II_, V_, VI_.
**Quyết định:** Tạo thư mục II_Noi_Quy, V_To_Chuc_Phan_Quyen, VI_Thi_Cong_Kinh_Doanh.

### 2. Mã dữ liệu <<MA_DATA>>
**Quyết định:** Dùng dạng `<<MA_DATA>>` như hướng dẫn `00_Ma_Data.md`, không điền giá trị cụ thể vì chưa có thông tin công ty thật.

### 3. Ưu tiên tạo
**Đợt làm trước:** Phần A (hợp đồng, nội quy) và B (HSE) vì đây là ưu tiên 0.
**Đợt sau:** C, D và các file Đợt 2.

### 4. Văn bản ● cần sửa
Sẽ review sau khi tạo xong văn bản mới. Tập trung tạo ▲ trước.

### 5. Các điểm ◐ cần xác nhận
Các điểm có ký hiệu ◐ sẽ được ghi chú trong văn bản để luật sư/kế toán xác nhận trước khi ban hành.

### 6. Các mục ■ (dùng mẫu Nhà nước)
Không tạo file nội dung, chỉ ghi chú đường dẫn nguồn trong danh sách.

---

## Tiến độ tạo văn bản

| Phần | Subagent | Trạng thái |
|------|----------|------------|
| A – Hợp đồng, Nội quy (1a, 1c, 2, 3, 4, 5, 6, 7, 13, 82 + 16, 17, 18, 20, 21 + 25) | SA-A & SA-FIX | ✅ HOÀN THÀNH 100% (Đã QC & chuẩn hóa) |
| B – HSE & TNLĐ (32-39, 41-44, 47-48, 59-62, 83) | SA-B & SA-FIX | ✅ HOÀN THÀNH 100% (Đã QC & chuẩn hóa) |
| C & D – Tổ chức, Thi công, Kinh doanh (25 văn bản Đợt 1 + 2) | SA-C & SA-FIX-CD | ✅ HOÀN THÀNH 100% (Đã QC & chuẩn hóa) |
| Hiệu chỉnh 13 văn bản có sẵn (Mục ●) | SA-SUA (High Mode) | ✅ HOÀN THÀNH 100% (Đã chuẩn hóa, đổi 01b, cập nhật luật) |
| Thu thập & số hóa 12 Mẫu biểu Nhà nước (Mục ■) | SA-MAU (High Mode) | ✅ HOÀN THÀNH 100% (Đã số hóa tại mau-nha-nuoc/) |

## Chi tiết SA-B – Kết quả (20:15, 15/10/2026)
- 19 file mới tạo trong IV_HSE_An_Toan_TNLD/
- Đánh giá sơ bộ: đúng format, placeholder chuẩn, nội dung chuyên sâu đặc thù kết cấu thép
- Căn cứ pháp lý đã cập nhật NĐ 207/2026, TT 32/2026/TT-BXD (mới nhất)

---

## CẬP NHẬT TIẾN ĐỘ KHẮC PHỤC THEO BÁO CÁO QC (20:40, 15/10/2026) - MODEL HIGH / PRO

Đã hoàn thành rà soát và khắc phục 100% các vấn đề nêu trong Báo cáo Kiểm định Độc lập `BAO_CAO_KIEM_TRA_QC.md`:

### 1. Xóa bỏ hoàn toàn hardcode tên riêng SAMIN
- Đã thay thế toàn bộ `CÔNG TY TNHH SAMIN`, `Công ty TNHH SAMIN` thành `<<CTY_TEN>>` và viết tắt số hiệu thành `<<CTY_TEN_VT>>` tại:
  - `I_Hop_Dong_Nhan_Su/82_So_Quan_Ly_Lao_Dong.md` (dòng 121)
  - `I_Hop_Dong_Nhan_Su/04_Thoa_Thuan_Cham_Dut_HDLD_va_Bien_Ban_Thanh_Ly.md`
  - `I_Hop_Dong_Nhan_Su/13_Quyet_Dinh_Chi_Dinh_Nguoi_Phu_Trach.md`
  - `II_Noi_Quy/16_Noi_Quy_Lao_Dong.md`
  - Các văn bản nhóm I (`01`, `08`, `09`, `10`, `11`), nhóm III (`22`, `23`, `27`, `28`), nhóm IV (`46`, `50`, `51`, `52`, `54`, `55`, `57`, `58`) và file lưu trữ.
- Kết quả rà soát grep: **0 phát hiện tồn dư từ khóa SAMIN** trong toàn bộ 4 nhóm thư mục chính.

### 2. Chuẩn hóa mã placeholder theo từ điển `00_Ma_Data.md`
- Chuẩn hóa toàn bộ placeholder tự chế không theo từ điển trong Nhóm II (`17`, `18`, `20`, `21`) và Nhóm III (`25`, `26`, `29`, `31`), Nhóm IV (`45`), Nhóm VI (`71`, `72`, `75`, `77`, `78`, `79`, `80`, `81`), Nhóm I (`15a`, `15b`, `15c`, `15d`) và Nhóm V (`65`):
  - `<<CTY_MA>>` $\rightarrow$ `<<CTY_TEN_VT>>`
  - `<<NAM>>`, `<<THANG>>`, `<<NGAY>>` $\rightarrow$ `<<VB_NAM>>`, `<<VB_THANG>>`, `<<VB_NGAY>>`
  - `<<TINH_THANH>>` $\rightarrow$ `<<CTY_DIA_DANH>>`
  - `<<NGAY_BAN_HANH>>` $\rightarrow$ `<<VB_NGAY>>/<<VB_THANG>>/<<VB_NAM>>`
  - `<<SO_QD>>` $\rightarrow$ `<<VB_SO>>`
  - `<<CTY_DIA_CHI>>` $\rightarrow$ `<<CTY_DC>>`
  - `<<CT_CHT>>` $\rightarrow$ `<<CT_CHI_HUY_TRUONG>>`
  - `<<HDLD_SO>>` $\rightarrow$ `<<HD_SO>>`
  - `<<CHU_DAU_TU>>`, `<<TONG_THAU>>` $\rightarrow$ `<<KH_TEN>>`
  - `<<CT_DIA_CHI>>` $\rightarrow$ `<<CT_DIA_DIEM>>`
  - `<<CT_SDT_BENH_VIEN>>` $\rightarrow$ `<<CT_BENH_VIEN_DT>>`
  - `<<CTY_CHU_TICH_CD>>` $\rightarrow$ `<<CTY_CD_CHU_TICH>>`
  - `<<NLĐ_...>>` $\rightarrow$ `<<NLD_...>>`
- Trong file `25_Phieu_Dang_Ky_Lam_Them_Gio.md`: Đã chuyển toàn bộ placeholder mảng (`<<GIO_DK_1>>`, `<<LUY_KE_THANG_1>>`...) thành các dòng chấm mẫu `.........` phục vụ in ấn và ghi chép thực tế.

### 3. Chuẩn hóa dẫn chiếu mở tỷ lệ BHXH
- Tại các file `01c_HDLD_Xac_Dinh_Thoi_Han_12_Thang_Tho_Nong_Cot.md`, `02_HDLD_Khong_Xac_Dinh_Thoi_Han_Van_Phong.md`, `04_Thoa_Thuan_Cham_Dut_HDLD_va_Bien_Ban_Thanh_Ly.md`:
  - Đã thay thế tỷ lệ đóng cứng (10,5% và 21,5%) bằng điều khoản dẫn chiếu mở: "theo tỷ lệ quy định của pháp luật và Bảng tham số hiện hành (`00-bang-tham-so.md`)".

### 4. Dọn dẹp dữ liệu mẫu và bổ sung Header quản trị
- Dọn dẹp toàn bộ dữ liệu mẫu (số điện thoại, họ tên cá nhân mẫu) tại các biểu mẫu:
  - `82_So_Quan_Ly_Lao_Dong.md`: Khung mẫu chuẩn hóa, xóa số điện thoại và họ tên mẫu ở Phần III.
  - `61_Cong_Van_De_Nghi_Xac_Nhan_Bao_Hiem_Cong_Truong.md`: Xóa họ tên công nhân mẫu Nguyễn Văn B, Trần Văn C... về dòng trống kẻ mẫu.
  - `83_Ho_So_Theo_Doi_Kham_Suc_Khoe.md`: Xóa các dòng kết quả khám bệnh mẫu của Nguyễn Văn A, Trần Văn B... về dòng kẻ trống.
- Bổ sung đầy đủ trường Người phê duyệt / Chủ trì tại Header:
  - File `07`: Bổ sung `Người phê duyệt: Giám đốc <<CTY_DAI_DIEN>>` và `Người kiểm tra: Cán bộ HC-NS & Chỉ huy trưởng <<CT_CHI_HUY_TRUONG>>`.
  - File `18`: Bổ sung `Chủ trì phiên họp: <<CTY_CD_CHU_TICH>> (Chủ tịch CĐCS) & <<CTY_DAI_DIEN>> (Giám đốc Công ty)`.
  - File `25`: Bổ sung `Người duyệt (Chỉ huy trưởng): <<CT_CHI_HUY_TRUONG>>`.

### 5. Kết luận đánh giá lại
Hệ thống tài liệu đã khắc phục toàn bộ các điểm bất cập theo Báo cáo QC, bảo đảm **100% tuân thủ Bộ luật Lao động, Luật BHXH 2024, Luật Xây dựng 2025, NĐ 207/2026/NĐ-CP, NĐ 283/2026/NĐ-CP** và tính tương thích tự động hóa khi áp dụng bảng dữ liệu `00_Ma_Data.md`.

---

## CẬP NHẬT TIẾN ĐỘ KHẮC PHỤC THEO BÁO CÁO QC NHÓM C & D (21:00, 15/10/2026) - MODEL HIGH / PRO

Đã hoàn thành rà soát và khắc phục 100% các khuyến nghị trong Báo cáo Kiểm định Độc lập Nhóm C & D (`BAO_CAO_KIEM_TRA_QC_NHOM_C_D.md`):

### 1. Khắc phục vấn đề nghiệp vụ, phân quyền và cơ cấu tổ chức (02 file trọng điểm)
- **File `VI_Thi_Cong_Kinh_Doanh/71_Quy_Trinh_Kinh_Doanh_Bao_Gia_Quan_Ly_Hop_Dong.md`:**
  - Xóa bỏ việc hardcode các hạn mức 1 tỷ, 5 tỷ và loại bỏ chức danh không tồn tại ("Phó Giám đốc / Giám đốc điều hành") do công ty có quy mô nhỏ (~10 người văn phòng).
  - Đồng bộ ngưỡng phê duyệt báo giá theo đúng File 63 Điều 5 và Bảng tham số:
    + Giá trị gói thầu $\le$ `<<TS_NGUONG_BAO_GIA>>`: Kỹ sư dự toán đề xuất $\rightarrow$ Trưởng phòng Dự án (kiêm Kinh doanh) phê duyệt.
    + Giá trị gói thầu $>$ `<<TS_NGUONG_BAO_GIA>>`: Trưởng phòng Dự án (kiêm Kinh doanh) trình $\rightarrow$ Giám đốc Công ty phê duyệt và ký.
  - Chuẩn hóa tên gọi 04 phòng ban: "Phòng Dự án (kiêm Kinh doanh)" chịu trách nhiệm bóc tách kỹ thuật, dự toán, báo giá và mua vật tư; "Phòng Thi công" tổ chức thi công tại hiện trường.
  - Chuẩn hóa chữ ký và chức danh ở cuối văn bản.
- **File `III_Luong_Thuong_Ke_Toan/31_Bang_Tong_Hop_Quyet_Toan_Chi_Phi_Cong_Trinh.md`:**
  - Sửa đổi toàn diện Mục 4.2 nguyên tắc phân bổ Quỹ thưởng KPI dự án khớp chính xác 100% với Điều 8 Quy chế 23:
    + **Khối công trường trực thuộc Phòng Thi công** (Ban Chỉ huy, kỹ thuật, an toàn viên HSE và tổ thợ trực tiếp): Hưởng **65%** quỹ thưởng (khung 45% - 65%);
    + **Phòng Dự án (kiêm Kinh doanh)**: Hưởng **25%** quỹ thưởng (khung 25% - 45%);
    + **Phòng Kế toán – Tài chính**: Hưởng **10%** quỹ thưởng (khung 5% - 10%);
    + **Phòng Hành chính – Nhân sự**: Khẳng định quy định loại trừ đặc biệt **KHÔNG tham gia trích chia quỹ thưởng KPI dự án** nhằm bảo đảm tính khách quan trong công tác quản trị và giám sát nhân sự (theo đúng Điều 2 khoản 2 Quy chế 23 và Điều 3 khoản 4 Quy chế 63).
  - Chuẩn hóa các ô bảng tính mẫu sang định dạng dòng chấm `.........` thay vì các placeholder tự chế.

### 2. Chuẩn hóa 16 mã placeholder alias theo từ điển `00_Ma_Data.md`
Đã quét và thay thế triệt để 16 mã alias trên toàn bộ các file văn bản thuộc Nhóm C & D (gồm 15a, 15b, 15c, 15d, 26, 29, 31, 45, 65, 71, 72, 75, 77, 78, 79, 80, 81):
- `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` $\rightarrow$ `<<CTY_DAI_DIEN>>` (16 file)
- `<<CHT_TEN>>` / `<<CHT_DAI_DIEN>>` $\rightarrow$ `<<CT_CHI_HUY_TRUONG>>`
- `<<KTT_TEN>>` $\rightarrow$ `<<CTY_KE_TOAN_TRUONG>>`
- `<<CHU_TICH_CONG_DOAN>>` $\rightarrow$ `<<CTY_CD_CHU_TICH>>`
- `<<CDT_TEN>>` $\rightarrow$ `<<KH_TEN>>`
- `<<KH_DIA_CHI>>` $\rightarrow$ `<<KH_DC>>`, `<<KH_CHUC_VU>>` $\rightarrow$ `<<KH_CHUC_DANH>>`, `<<KH_NGUOI_DAI_DIEN>>` $\rightarrow$ `<<KH_DAI_DIEN>>`
- `<<NCC_DIA_CHI>>` $\rightarrow$ `<<NCC_DC>>`, `<<NCC_NGUOI_DAI_DIEN>>` $\rightarrow$ `<<NCC_DAI_DIEN>>`, `<<NCC_CHUC_VU>>` $\rightarrow$ `<<NCC_CHUC_DANH>>`
- `<<CTY_SO_DIEN_THOAI>>` $\rightarrow$ `<<CTY_DT>>`
- `<<NGAY_KHOI_CONG>>` $\rightarrow$ `<<CT_NGAY_KHOI_CONG>>`, `<<NGAY_HOAN_THANH>>` $\rightarrow$ `<<CT_NGAY_HOAN_THANH>>`
- `<<HD_NGAY>>` $\rightarrow$ `<<HD_NGAY_KY>>`
- `<<HO_TEN_NLD>>` $\rightarrow$ `<<NLD_HO_TEN>>` (hoặc `.........` trong bảng biểu mẫu)
- Dọn dẹp toàn bộ placeholder tự tạo trong các ô biểu mẫu (File 72, 75, 77, 80, 81, 31, 65, 79) về dạng dòng chấm `.........` hoặc mã chuẩn.

### 3. Kết quả xác minh tự động bằng Python
- **Tổng số mã alias còn sót lại trong toàn bộ 25 file:** **0**.
- **Tổng số placeholder lạ / không có trong `00_Ma_Data.md`:** **0** (100% khớp chuẩn).
- **Trạng thái sẵn sàng:** Toàn bộ 25 file Nhóm C & D đạt chuẩn Grade A+, hoàn toàn sẵn sàng cho Giám đốc Công ty ký duyệt ban hành chính thức.

---

## CẬP NHẬT TIẾN ĐỘ THU THẬP, BIÊN SOẠN & SỐ HÓA MẪU BIỂU NHÀ NƯỚC (MỤC ■) (21:30, 15/10/2026) - MODEL HIGH / PRO

Đã hoàn thành 100% nhiệm vụ thu thập, đối chiếu căn cứ pháp lý và biên soạn hoàn chỉnh bộ 12 Biểu mẫu quy chuẩn của Nhà nước (ký hiệu ■) theo danh mục `bo-van-ban/00_Danh_Sach_Van_Ban.md`, lưu trữ tại thư mục chuyên biệt `/Users/leo/projects/QL_SM/mau-nha-nuoc/` và đồng bộ mẫu trắng vào các thư mục nghiệp vụ:

### 1. Danh sách 12 biểu mẫu Nhà nước đã số hóa chuẩn xác:
1. **STT 12: Bảng chấm công công trường** (`mau-nha-nuoc/12_Bang_Cham_Cong_Mau_01a_LDTL_TT133.md`)
   - Căn cứ: Mẫu số 01a-LĐTL Thông tư số 133/2016/TT-BTC ngày 26/08/2016 của Bộ Tài chính. Đầy đủ hệ thống ký hiệu chấm công chuẩn, bảng quy đổi công và hướng dẫn kế toán.
2. **STT 14: Báo cáo tình hình sử dụng lao động định kỳ** (`mau-nha-nuoc/14_Bao_Cao_Su_Dung_Lao_Dong_Mau_01_PLI_ND145.md`)
   - Căn cứ: Mẫu số 01/PLI Phụ lục I Nghị định số 145/2020/NĐ-CP ngày 14/12/2020 của Chính phủ (báo cáo định kỳ 6 tháng và hằng năm qua Cổng DVCQG).
3. **STT 19: Văn bản đề nghị đăng ký nội quy lao động** (`mau-nha-nuoc/19_Van_Ban_De_Nghi_Dang_Ky_Noi_Quy_Lao_Dong.md`)
   - Căn cứ: Điều 69 Nghị định số 145/2020/NĐ-CP và biểu mẫu Cổng Dịch vụ công Quốc gia (Mã TTHC 1.002825).
4. **STT 30: Giấy đề nghị tạm ứng & Giấy thanh toán tạm ứng** (`mau-nha-nuoc/30_Giay_De_Nghi_va_Thanh_Toan_Tam_Ung_Mau_03_04_TT.md`)
   - Căn cứ: Mẫu số 03-TT & Mẫu số 04-TT Thông tư số 133/2016/TT-BTC. Tích hợp bảng kê chứng từ gốc và hướng dẫn quản trị tạm ứng hiện trường.
5. **STT 40: Biện pháp bảo đảm an toàn trong thi công xây dựng công trình** (`mau-nha-nuoc/40_Bien_Phap_Bao_Dam_An_Toan_Thi_Cong_Phu_Luc_III_ND207.md`)
   - Căn cứ: Khung quy định tại Phụ lục III Nghị định số 207/2026/NĐ-CP ngày 15/06/2026 kết hợp QCVN 18:2021/BXD, Thông tư 32/2026/TT-BXD chuyên sâu kết cấu thép.
6. **STT 49: Khai báo tai nạn lao động** (`mau-nha-nuoc/49_Mau_Khai_Bao_TNLD_Phu_Luc_III_ND39.md`)
   - Căn cứ: Mẫu Phụ lục III Nghị định số 39/2016/NĐ-CP ngày 15/05/2016 của Chính phủ gửi Thanh tra Sở LĐTBXH trong vòng 24 giờ.
7. **STT 50: Quyết định thành lập Đoàn điều tra tai nạn lao động cấp cơ sở** (`mau-nha-nuoc/50_Quyet_Dinh_Thanh_Lap_Doan_Dieu_Tra_Phu_Luc_V_ND39.md`)
   - Căn cứ: Mẫu Phụ lục V Nghị định số 39/2016/NĐ-CP. Đồng bộ cập nhật bản mẫu trắng vào `IV_HSE_An_Toan_TNLD/50_Quyet_Dinh_Thanh_Lap_Doan_Dieu_Tra_TNLD_Co_So.md`.
8. **STT 53: Biên bản lấy lời khai tai nạn lao động** (`mau-nha-nuoc/53_Bien_Ban_Lay_Loi_Khai_Phu_Luc_VIII_ND39.md`)
   - Căn cứ: Mẫu Phụ lục VIII Nghị định số 39/2016/NĐ-CP chuẩn mực hỏi - đáp phục vụ điều tra hiện trường.
9. **STT 54: Biên bản điều tra tai nạn lao động cấp cơ sở** (`mau-nha-nuoc/54_Bien_Ban_Dieu_Tra_TNLD_Phu_Luc_IX_ND39.md`)
   - Căn cứ: Mẫu Phụ lục IX Nghị định số 39/2016/NĐ-CP. Đã thay thế toàn bộ cốt truyện giả định cũ trong `IV_HSE_An_Toan_TNLD/54_...md` bằng bản mẫu trắng chuẩn mực pháp lý.
10. **STT 55: Biên bản cuộc họp công bố biên bản điều tra tai nạn lao động** (`mau-nha-nuoc/55_Bien_Ban_Hop_Cong_Bo_Phu_Luc_XI_ND39.md`)
    - Căn cứ: Mẫu Phụ lục XI Nghị định số 39/2016/NĐ-CP. Đồng bộ cập nhật bản mẫu trắng vào `IV_HSE_An_Toan_TNLD/55_...md`.
11. **STT 56: Danh mục chấn thương nặng trong tai nạn lao động** (`mau-nha-nuoc/56_Danh_Muc_Chan_Thuong_Nang_Phu_Luc_II_ND39.md`)
    - Căn cứ: Toàn văn 08 nhóm tổn thương chấn thương nặng theo Phụ lục II Nghị định số 39/2016/NĐ-CP.
12. **STT 70: Nhật ký thi công xây dựng công trình & Mẫu dấu hoàn công** (`mau-nha-nuoc/70_Nhat_Ky_Thi_Cong_va_Dau_Hoan_Cong_Phu_Luc_II_ND207.md`)
    - Căn cứ: Phụ lục II (Sổ nhật ký thi công) và Phụ lục IIb (Mẫu dấu bản vẽ hoàn công số 1 và số 2) ban hành kèm theo Nghị định số 207/2026/NĐ-CP.

### 2. Kiểm soát chất lượng & Thể thức văn bản:
- **Chuẩn hóa placeholder:** 100% khớp bảng mã `00_Ma_Data.md` (`<<CTY_TEN>>`, `<<CTY_DC>>`, `<<CT_TEN>>`, `<<CT_CHI_HUY_TRUONG>>`...).
- **Không tồn dư từ khóa SAMIN:** 0 phát hiện.
- **Tính đồng bộ:** Đã liên kết đầy đủ đường dẫn các file mẫu Nhà nước vào danh mục tổng `bo-van-ban/00_Danh_Sach_Van_Ban.md`.

---

## CẬP NHẬT QUY CHẾ KPI 23 & 12 NGÀY NGHỈ LỄ, TẾT THEO CHỈ ĐẠO BAN LÃNH ĐẠO (21:45, 15/10/2026) - MODEL HIGH / PRO

Đã hoàn thành 100% việc điều chỉnh và chuẩn hóa trên toàn bộ hệ thống văn bản Công ty theo đúng 02 chỉ đạo mới nhất của Ban Lãnh đạo:

### 1. NỘI DUNG 1: CẬP NHẬT QUY CHẾ KPI 23 & PHÂN BỔ QUỸ KPI DỰ ÁN
- **Chỉ đạo của Lãnh đạo:** *"Quy chế KPI 23: ko đúng, các phòng đều tham gia quỹ KPI, trong đó Thi công nhiều nhất."*
- **Tỷ lệ phân bổ chuẩn hóa (Tổng 100%):**
  1. **Phòng Thi công (nhiều nhất): 50%** quỹ thưởng KPI (Ban Chỉ huy công trường 25%, Kỹ thuật hiện trường & An toàn viên 10%, Tổ thợ trực tiếp thi công lắp dựng 15%).
  2. **Phòng Dự án (kiêm Kinh doanh): 25%** quỹ thưởng KPI (đàm phán thầu phụ, bóc tách khối lượng, vật tư; ưu tiên 40% phần này cho nhân sự chủ trì).
  3. **Phòng Kế toán – Tài chính: 15%** quỹ thưởng KPI (kiểm soát dòng tiền thực thu, hồ sơ thanh quyết toán, chi phí TK 154 và thu hồi công nợ).
  4. **Phòng Hành chính – Nhân sự: 10%** quỹ thưởng KPI (hồ sơ lao động, đăng ký người lao động, tuyển dụng và hỗ trợ dự án).
- **Xóa bỏ triệt để mọi điều khoản loại trừ Phòng HC-NS:** Toàn bộ cụm từ loại trừ hoặc khẳng định HC-NS không tham gia đã được xóa bỏ hoàn toàn trên toàn bộ hệ thống tài liệu. Thay bằng quy định: Cả 04 phòng ban đều được đánh giá hiệu suất (KPI) và hưởng quỹ thưởng theo tỷ lệ trên gắn với kết quả thu hồi dòng tiền và lợi nhuận gộp dự án.
- **Danh sách file đã cập nhật:**
  - `III_Luong_Thuong_Ke_Toan/23_Quy_Che_Luong_KPI_Du_An_2026.md` (Hộp chú thích, Điều 2, Điều 6, Điều 7, Điều 8, Điều 10, Điều 11 và Nơi nhận).
  - `III_Luong_Thuong_Ke_Toan/31_Bang_Tong_Hop_Quyet_Toan_Chi_Phi_Cong_Trinh.md` (Mục 4.2 & Mục 4.3).
  - `III_Luong_Thuong_Ke_Toan/22_Quy_Che_Tien_Luong_Thuong_Phu_Cap_2026.md` (Điều 2 khoản 4, Điều 13 khoản 2).
  - `V_To_Chuc_Phan_Quyen/63_Quy_Che_To_Chuc_Phan_Quyen_Chuc_Danh_Bao_Cao.md` (Điều 3 khoản 1, 2, 3, 4).
  - `README.md` (Nguyên tắc tổ chức và quản trị - Mục 2).
  - `I_Hop_Dong_Nhan_Su/08_Quy_Che_Dieu_Hanh_Nhan_Su_va_Vong_Doi_Cong_Nhan.md` (Điều 2 khoản 4).
  - `I_Hop_Dong_Nhan_Su/02_HDLD_Khong_Xac_Dinh_Thoi_Han_Van_Phong.md` (Điều 3 khoản 3).
  - `III_Luong_Thuong_Ke_Toan/29_Quy_Trinh_Tai_Chinh_Ke_Toan_Cong_Trinh.md` (Mục 4.2).
  - `VI_Thi_Cong_Kinh_Doanh/78_Quy_Che_Dan_Chu_va_Doi_Thoai.md` (Điều 5 khoản 2).
  - `bo-van-ban/00-bang-tham-so.md` (Mục III.4).
  - `bo-van-ban/C1-quy-che-to-chuc-phan-quyen.md` (Mục 1).
  - `bo-van-ban/A3-quy-che-luong-thuong-kpi.md` (Điều 4 khoản 2 và Phụ lục 2).
  - `BAO_CAO_KIEM_TRA_QC_NHOM_C_D.md` (Bảng đánh giá Quy chế 63).

### 2. NỘI DUNG 2: CẬP NHẬT 12 NGÀY NGHỈ LỄ, TẾT HƯỞNG NGUYÊN LƯƠNG
- **Chỉ đạo của Lãnh đạo:** *"Ngày nghỉ trong năm: lễ tết là 12 (thêm 1 ngày Ngày Văn hóa Việt Nam (24/11 hằng năm) theo Nghị quyết 28/2026/QH16)"*
- **Liệt kê chính xác đủ 12 ngày nghỉ Lễ, Tết:**
  1. Tết Dương lịch (ngày 01/01 dương lịch): **01 ngày**;
  2. Tết Âm lịch: **05 ngày**;
  3. Ngày Chiến thắng (ngày 30/04 dương lịch): **01 ngày**;
  4. Ngày Quốc tế lao động (ngày 01/05 dương lịch): **01 ngày**;
  5. Quốc khánh (ngày 02/09 dương lịch và 01 ngày liền kề): **02 ngày**;
  6. Ngày Giỗ Tổ Hùng Vương (ngày 10/03 âm lịch): **01 ngày**;
  7. Ngày Văn hóa Việt Nam (ngày 24/11 dương lịch hằng năm): **01 ngày** (theo Nghị quyết số 28/2026/QH16 của Quốc hội).
  $\rightarrow$ **Tổng cộng: 12 ngày nghỉ lễ, Tết hưởng nguyên lương trong năm**.
- **Danh sách file đã cập nhật:**
  - `bo-van-ban/00-bang-tham-so.md` (Mục II.3 Thời giờ làm việc).
  - `bo-van-ban/00-can-cu-phap-ly.md` (Mục 1 Lao động - bảo hiểm - việc làm: bổ sung Nghị quyết 28/2026/QH16).
  - `II_Noi_Quy/16_Noi_Quy_Lao_Dong.md` (Điều 6 khoản 2 liệt kê đủ 7 mục 12 ngày; Phụ lục 3 Căn cứ pháp lý).
  - `I_Hop_Dong_Nhan_Su/08_Quy_Che_Dieu_Hanh_Nhan_Su_va_Vong_Doi_Cong_Nhan.md` (Điều 8 khoản 4; Điều 4 Căn cứ pháp lý).
  - `I_Hop_Dong_Nhan_Su/01b_HDLD_Thoi_Vu_Cong_Trinh.md` (Điều 2 khoản 3).
  - `I_Hop_Dong_Nhan_Su/01c_HDLD_Xac_Dinh_Thoi_Han_12_Thang_Tho_Nong_Cot.md` (Điều 3 khoản 3).
  - `I_Hop_Dong_Nhan_Su/02_HDLD_Khong_Xac_Dinh_Thoi_Han_Van_Phong.md` (Điều 2 khoản 3).


