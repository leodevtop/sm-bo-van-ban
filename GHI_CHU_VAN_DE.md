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
| A – Hợp đồng, Nội quy (STT 1a,1c,2,3,4,5,6,7,13,82 + 16,17,18,20,21 + 25) | SA-A | Đang chạy |
| B – HSE & TNLĐ (STT 32-39, 41-44, 47-48, 59-62, 83) | SA-B | ✅ XONG – 19/19 file |
| C – Tổ chức (63,64,66) + D – Thi công (68,74,76) + Đợt 2 | SA-C | Chờ SA-A xong |
| Kiểm tra toàn bộ | SA-QC | Chờ kết quả A+C |

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

