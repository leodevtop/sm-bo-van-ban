# Kế hoạch Bổ sung Quy trình & Bộ Hồ sơ Đối chiếu Vật tư Sau Gia công

- **Date:** 2026-10-16
- **Author:** Antigravity
- **Status:** Proposed

---

## 1. Mục tiêu

Chuẩn hóa và hoàn thiện bộ văn bản quản trị cho trường hợp **Công ty thuê đối tác bên ngoài gia công cấu kiện/hạng mục dự án** (áp dụng khi Công ty chỉ thi công hoặc cung cấp cả vật tư nhưng không tự gia công cơ khí chế tạo). Đảm bảo tính chặt chẽ về mặt kỹ thuật công trình, quản lý hao hụt vật tư và tính hợp lệ chi phí đối với cơ quan Thuế.

---

## 2. Kết quả kiểm tra hiện trạng

Kiểm tra đối chiếu file `bo-van-ban/00_Danh_Sach_Van_Ban.md` và các tài liệu liên quan trong hệ thống:

1. **Danh sách văn bản (`00_Danh_Sach_Van_Ban.md`):**
   - **CHƯA CÓ** văn bản riêng cho nghiệp vụ *"Biên bản đối chiếu vật tư sau gia công"* hay *"Hồ sơ quản lý gia công ngoài"*.
   - Mục 68 (`VI_Thi_Cong_Kinh_Doanh/68_Bien_Ban_Giao_Nhan_va_Quyet_Toan_Vat_Tu.md`) hiện chỉ điều chỉnh 2 trường hợp:
     - Dạng 1: Tổng thầu giao vật tư trực tiếp cho Công ty lắp dựng tại công trường.
     - Dạng 2: Công ty mua vật tư thành phẩm từ Nhà cung cấp đem đến lắp dựng.
   - Chưa có biểu mẫu hay quy trình điều chỉnh việc: **Xuất phôi/vật tư cho xưởng gia công $\rightarrow$ Nghiệm thu kỹ thuật tại xưởng $\rightarrow$ Đối chiếu cân đối vật tư (hao hụt, vật tư thừa, phế liệu) $\rightarrow$ Quyết toán dịch vụ gia công.**

2. **Bộ khung kiến trúc (`bo-van-ban/bo-khung/`):**
   - Các file `D1-quy-trinh-thi-cong-vat-tu-nghiem-thu.md`, `D2`, `C1` và `00-README-huong-dan-ban-hanh.md` hiện đều mặc định ghi nhận nguyên tắc: *"Công ty không sản xuất, gia công; vật tư thép, bu lông, phụ kiện được mua thành phẩm"*.
   - Cần bổ sung phân nhánh nghiệp vụ cho trường hợp thuê ngoài gia công để bộ khung bao quát đúng thực tế vận hành.

---

## 3. Danh mục tài liệu cần tạo mới và cập nhật

### A. Tài liệu tạo mới (Biểu mẫu thực thi)
- **Tên tài liệu:** `84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md`
- **Vị trí lưu trữ:** `./VI_Thi_Cong_Kinh_Doanh/84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md`
- **Mã hệ thống:** D1-84 / STT 84
- **Nội dung bao gồm 5 cấu phần trọn gói:**
  1. *Phần I: Hướng dẫn quản trị rủi ro & Checklist pháp lý thuế gia công* (Hợp đồng gia công vs mua bán; kiểm soát hao hụt định mức; xuất hóa đơn dịch vụ; quy tắc giao thẳng ra công trường).
  2. *Phần II (Biểu mẫu 01): Biên bản bàn giao vật tư/phôi cho đơn vị gia công* (Quy cách, số lượng, khối lượng, mác thép, CO/CQ kèm theo, tình trạng ngoại quan ban đầu).
  3. *Phần III (Biểu mẫu 02): Biên bản nghiệm thu kỹ thuật thành phẩm tại xưởng gia công (QC/KCS)* (Kích thước hình học, độ dày sơn, mối hàn, cấu kiện đạt/không đạt xuất xưởng).
  4. *Phần IV (Biểu mẫu 03): Biên bản đối chiếu và quyết toán vật tư sau gia công* (Bảng cân đối 5 cột: Cấp vào - Định mức tạo thành phẩm - Hao hụt cho phép vs thực tế - Vật tư thừa hoàn trả - Khối lượng phế liệu phát sinh).
  5. *Phần V (Biểu mẫu 04): Biên bản xử lý vật tư thừa và phế liệu gia công* (Phương án thu hồi về kho hoặc thanh lý cấn trừ chi phí tiền gia công).

### B. Cập nhật tài liệu hướng dẫn trong `bo-van-ban/bo-khung/`
- **`bo-van-ban/bo-khung/D1-quy-trinh-thi-cong-vat-tu-nghiem-thu.md`:**
  - Cập nhật Mục 0: Mở rộng nguyên tắc quản lý vật tư sang trường hợp ủy thác/thuê xưởng gia công cấu kiện ngoài.
  - Bổ sung Mục **2C – Quản lý gia công cấu kiện qua đối tác ngoài (Thuê xưởng gia công)**: Quy định rõ luồng giao nhận, kiểm soát định mức hao hụt, KCS xưởng và chốt số liệu đối chiếu vật tư.
  - Bổ sung mã biểu mẫu D1-08 đến D1-11 vào bảng danh mục biểu mẫu vật tư.
- **`bo-van-ban/bo-khung/D2-quy-trinh-kinh-doanh-hop-dong.md`:**
  - Bổ sung quy định về Hợp đồng dịch vụ gia công ngoài trong chu trình dự toán & lựa chọn đối tác chế tạo cấu kiện.
- **`bo-van-ban/bo-khung/D3-quy-trinh-tai-chinh-ke-toan.md`:**
  - Bổ sung Mục **4C – Chi phí gia công ngoài**: Hướng dẫn chứng từ hợp lệ (Hợp đồng, Biên bản giao phôi, Biên bản nghiệm thu xưởng, Biên bản đối chiếu vật tư, Hóa đơn GTGT dịch vụ gia công).

### C. Cập nhật các tài liệu danh mục và quản lý
- **`bo-van-ban/00_Danh_Sach_Van_Ban.md`:**
  - Thêm STT 84 vào Bảng Nhóm VI (Thi công, Kinh doanh & Dân chủ).
  - Cập nhật số liệu tổng hợp văn bản (Đợt 1 / Đợt 2, tổng số file).
- **`bo-van-ban/00-so-dang-ky-van-ban.md`:**
  - Bổ sung dòng nhật ký rà soát ngày 16/10/2026 về việc chuẩn hóa quy trình gia công ngoài.
- **`bo-van-ban/00-README-huong-dan-ban-hanh.md`:**
  - Cập nhật mô tả bổ trợ cho trường hợp Dạng 1 & Dạng 2 có phát sinh công đoạn gia công cấu kiện ngoài.

---

## 4. Lộ trình thực hiện chi tiết

| Bước | Hạng mục công việc | File tác động | Trạng thái |
|:---:|---|---|:---:|
| 1 | Lập kế hoạch bổ sung & trình người dùng phê duyệt | `docs/plans/261016-bo-sung-ho-so-gia-cong-vat-tu.md` | Hoàn thành |
| 2 | Cập nhật tài liệu khung kiến trúc D1, D2, D3 | `bo-van-ban/bo-khung/D1-*.md`, `D2-*.md`, `D3-*.md` | Chờ duyệt |
| 3 | Biên soạn trọn bộ tài liệu thực thi STT 84 | `VI_Thi_Cong_Kinh_Doanh/84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md` | Chờ duyệt |
| 4 | Cập nhật Danh sách văn bản & Sổ đăng ký | `bo-van-ban/00_Danh_Sach_Van_Ban.md`, `00-so-dang-ky-van-ban.md`, `00-README-*.md` | Chờ duyệt |
| 5 | Rà soát chéo (QC) tính nhất quán mã dữ liệu `<<...>>` và căn cứ pháp lý | Toàn bộ các file được cập nhật | Chờ duyệt |
