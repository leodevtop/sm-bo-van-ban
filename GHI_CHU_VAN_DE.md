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

