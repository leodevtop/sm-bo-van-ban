# Kế hoạch Bổ sung Bộ Hồ sơ Giao khoán Nhân công Công trình

- **Date:** 2026-10-16
- **Author:** Orchestrator
- **Status:** Completed
- **Branch:** `feature-bo-ho-so-giao-khoan`

---

## 1. Mục tiêu & Bối cảnh

Kiểm tra hiện trạng hệ thống văn bản tại `bo-van-ban/00_Danh_Sach_Van_Ban.md`: **Chưa có Bộ hồ sơ giao khoán** (hiện mới chỉ có mục 81 là Hợp đồng dịch vụ cá nhân bên ngoài và mục 22 có quy định khung ở Chương V nhưng chưa có bộ biểu mẫu hồ sơ hoàn chỉnh).

Mục tiêu kế hoạch là xây dựng và tích hợp hoàn chỉnh **Bộ hồ sơ giao khoán nhân công công trình (STT 85)** cho Công ty lắp dựng kết cấu thép nhà xưởng theo đúng Kiến trúc 2 tầng (Tầng 0: Bộ Khung; Tầng 1: Văn bản thực thi ban hành độc lập pháp lý 100%), tuân thủ nghiêm ngặt các hướng dẫn tại `README.md`, `bo-van-ban/00-README-huong-dan-ban-hanh.md`, Bộ luật Lao động 2019, Luật Xây dựng 2025, Nghị định 207/2026/NĐ-CP, Nghị định 283/2026/NĐ-CP và Thông tư 133/2016/TT-BTC.

---

## 2. Các yêu cầu cốt lõi

1. **Phân định bản chất pháp lý (Tránh tái phân loại HĐLĐ):**
   - Rõ ràng ranh giới giữa Hợp đồng giao khoán công việc/nhân công theo khối lượng và HĐLĐ (Điều 13 BLLĐ 2019).
   - Khoán theo sản phẩm/khối lượng hoàn thành (tấn kết cấu, m² tôn/xà gồ, cụm liên kết neo...), tự chủ về thời gian làm việc nhưng tuân thủ tiến độ và nội quy an toàn dự án.

2. **Quản trị an toàn lao động (HSE):**
   - Tuyệt đối không "khoán trắng" an toàn lao động.
   - 100% thợ trong tổ khoán phải có Thẻ an toàn Nhóm 3 còn hạn (làm việc trên cao, cẩu lắp kết cấu).
   - Bắt buộc có bảo hiểm cho người lao động thi công trên công trường (Điều 10 Luật Xây dựng 2025, NĐ 67/2023 sửa đổi bởi NĐ 220/2026).
   - Không áp dụng phạt tiền, trừ tiền khoán trái luật (vi phạm an toàn thì đình chỉ công việc, xử lý bằng chế tài hợp đồng/đình chỉ thanh lý).

3. **Tính hợp lệ về Kế toán & Thuế:**
   - Hợp đồng giao khoán ký giữa Giám đốc và Người đại diện tổ đội khoán kèm Giấy ủy quyền của 100% thành viên tổ.
   - Biên bản nghiệm thu khối lượng có xác nhận của Chỉ huy trưởng/Kỹ thuật công trường.
   - Bảng kê phân chia tiền công có chữ ký, CCCD, MST, STK ngân hàng của từng cá nhân thợ.
   - Khấu trừ thuế TNCN 10% theo quy định (hoặc cam kết 08/CK-TNCN nếu đủ điều kiện).
   - Trả tiền qua tài khoản ngân hàng (100% không tiền mặt đối với các khoản từ 5 triệu đồng trở lên).

4. **Kiến trúc 2 tầng:**
   - **Tầng 0 (`bo-khung/`):** Tích hợp hướng dẫn quản trị rủi ro, phân định trách nhiệm phòng ban, điều kiện nghiệm thu, quy trình luân chuyển chứng từ.
   - **Tầng 1 (Văn bản thực thi STT 85):** Thuần túy là văn bản ban hành có giá trị pháp lý, độc lập bản in 100%, tuân thủ thể thức NĐ 30/2020/NĐ-CP, tuyệt đối không chèn bài viết hướng dẫn nghiệp vụ/tutorial vào văn bản ký kết.

---

## 3. Checklist công việc thực hiện (Task Breakdown)

### Phase 1: Xây dựng nội dung Tầng 0 & Tầng 1 (Chạy song song tối đa 2 subagent - High Mode)
- [x] **Task 1: Cập nhật tài liệu khung kiến trúc Tầng 0 (`bo-khung/A1-bo-hop-dong-ho-so-nhan-su.md` & `bo-khung/A3-quy-che-luong-thuong-kpi.md`)**
  - Giao cho: `Implementor-1`
  - Bổ sung hướng dẫn quản trị rủi ro giao khoán nhân công tổ đội, phân định ranh giới HĐLĐ vs HĐ khoán việc, quản trị HSE và điều kiện chứng từ thuế.
- [x] **Task 2: Soạn thảo Bộ hồ sơ giao khoán nhân công Tầng 1 (`I_Hop_Dong_Nhan_Su/85_Bo_Ho_So_Giao_Khoan_Nhan_Cong.md`)**
  - Giao cho: `Implementor-2`
  - Xây dựng văn bản ban hành độc lập pháp lý 100% gồm: Hợp đồng giao khoán công việc chính thức + 07 Biểu mẫu phụ lục (Giấy ủy quyền đại diện tổ, Bảng khối lượng & đơn giá khoán, Biên bản nghiệm thu khối lượng khoán hoàn thành, Bảng thanh toán tiền khoán & phân chia tiền công, Biên bản thanh lý hợp đồng giao khoán, Bản cam kết tuân thủ HSE & PCCC, Bản cam kết thuế TNCN Mẫu 08/CK-TNCN theo TT 80/2021).

### Phase 2: Cập nhật Hệ thống danh mục & Đăng ký văn bản Layer 0
- [x] **Task 3: Cập nhật tài liệu danh mục và sổ đăng ký Layer 0**
  - Giao cho: `Implementor-1`
  - Cập nhật `bo-van-ban/00_Danh_Sach_Van_Ban.md` (thêm STT 85, cập nhật thống kê Đợt 1 / tổng số file).
  - Cập nhật `bo-van-ban/00-so-dang-ky-van-ban.md` (thêm STT 85, ghi nhật ký rà soát).
  - Cập nhật `README.md` (cập nhật cấu trúc thư mục và số lượng văn bản).

### Phase 3: Thẩm định & QA Độc lập
- [x] **Task 4: Thẩm định QA độc lập toàn bộ bộ hồ sơ giao khoán và hệ thống liên quan**
  - Giao cho: `Reviewer`
  - Rà soát tính độc lập bản in 100%, căn cứ pháp lý, tính chuẩn xác theo NĐ 30/2020, kiểm tra mã dữ liệu `<<...>>`, bảo đảm không vi phạm các nguyên tắc cấm (không phạt tiền, bắt buộc an toàn nhóm 3, chứng từ thuế). Đã hoàn thành thẩm định độc lập 8 tiêu chí: ĐẠT (PASS 8/8 tiêu chí).
