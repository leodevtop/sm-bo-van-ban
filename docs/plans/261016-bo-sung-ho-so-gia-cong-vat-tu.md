# Kế hoạch Bổ sung Quy trình & Bộ Hồ sơ Đối chiếu Vật tư Sau Gia công

- **Date:** 2026-10-16
- **Author:** Antigravity
- **Status:** Completed

---

## 1. Mục tiêu

Chuẩn hóa và hoàn thiện bộ văn bản quản trị cho trường hợp **Công ty thuê đối tác bên ngoài gia công cấu kiện/hạng mục dự án** (áp dụng khi Công ty chỉ thi công hoặc cung cấp cả vật tư nhưng không tự gia công cơ khí chế tạo). Đảm bảo tính chặt chẽ về mặt kỹ thuật công trình, quản lý hao hụt vật tư và tính hợp lệ chi phí đối với cơ quan Thuế.

**Yêu cầu điều chỉnh kiến trúc (Phase 2):**
- Tách bạch tuyệt đối: Phần **hướng dẫn quản trị rủi ro, tạo lập và kiểm soát văn bản** được tích hợp trọn vẹn vào **Bộ Khung** (`bo-van-ban/bo-khung/D1-quy-trinh-thi-cong-vat-tu-nghiem-thu.md`).
- File thực thi tại [84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md](file:///Users/leo/projects/QL_SM/VI_Thi_Cong_Kinh_Doanh/84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md) **chỉ là văn bản ban hành, có giá trị pháp lý** (văn bản giao kết và các biểu mẫu ký kết chính thức, không chứa bài viết hướng dẫn nghiệp vụ nội bộ).

---

## 2. Kết quả kiểm tra hiện trạng

Kiểm tra đối chiếu file `bo-van-ban/00_Danh_Sach_Van_Ban.md` và các tài liệu liên quan trong hệ thống:

1. **Danh sách văn bản (`00_Danh_Sach_Van_Ban.md`):**
   - Đã bổ sung mục 84 (D1-84).
2. **Bộ khung kiến trúc (`bo-van-ban/bo-khung/`):**
   - Đã bổ sung Mục 2C tại D1, Mục 5B tại D2, Mục 4C tại D3.

---

## 3. Danh mục tài liệu cần điều chỉnh

### A. Bộ khung kiến trúc (`bo-van-ban/bo-khung/`)
- Tích hợp toàn bộ nội dung hướng dẫn quản trị từ Phần I của file 84 vào `bo-van-ban/bo-khung/D1-quy-trinh-thi-cong-vat-tu-nghiem-thu.md` (Mục 2C):
  + Bản chất pháp lý HĐ gia công vs Mua bán hàng hóa, giải pháp tránh thuế GTGT 2 đầu.
  + Kiểm soát định mức hao hụt kỹ thuật theo sơ đồ cắt phôi (Nesting Plan) và nguyên tắc bồi hoàn 100%.
  + Quy tắc phối hợp 3 bên và lưu đồ khi giao hàng thẳng ra công trường.
  + Checklist 8 thành phần hồ sơ quyết toán thuế dịch vụ gia công hợp lệ.

### B. Văn bản thực thi ban hành (`VI_Thi_Cong_Kinh_Doanh/`)
- Tinh giản `84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md`:
  + Loại bỏ Phần I (hướng dẫn quản trị nội bộ).
  + Giữ nguyên và chuẩn hóa các biểu mẫu có giá trị pháp lý để ký ban hành:
    - Biểu mẫu số 01 (D1-84/BM-01): Biên bản giao nhận vật tư/phôi cho đơn vị gia công.
    - Biểu mẫu số 02 (D1-84/BM-02): Biên bản nghiệm thu kỹ thuật thành phẩm tại xưởng gia công.
    - Biểu mẫu số 03 (D1-84/BM-03): Biên bản đối chiếu và quyết toán vật tư sau gia công.
    - Biểu mẫu số 04 (D1-84/BM-04): Biên bản bàn giao & xử lý vật tư thừa, phế liệu gia công.
  + Quy định căn cứ pháp lý, hiệu lực thi hành và bảng ký duyệt pháp lý giữa Công ty và Xưởng gia công.

---

## 4. Checklist công việc thực hiện (Task Breakdown)

### Phase 1: Xây dựng & Tích hợp sơ bộ (Đã hoàn thành)
- [x] **Task 1: Cập nhật tài liệu khung kiến trúc D1, D2, D3 tại `bo-van-ban/bo-khung/`**
- [x] **Task 2: Biên soạn tài liệu thực thi STT 84 tại `VI_Thi_Cong_Kinh_Doanh/`**
- [x] **Task 3: Cập nhật tài liệu danh mục và quản lý**
- [x] **Task 4: Đánh giá chất lượng & Rà soát độc lập (QA / Review)**

### Phase 2: Tinh chỉnh kiến trúc & Tách bạch vai trò văn bản
- [x] **Task 5: Chuyển toàn bộ nội dung hướng dẫn quản trị vào `bo-van-ban/bo-khung/D1-quy-trinh-thi-cong-vat-tu-nghiem-thu.md`**
- [x] **Task 6: Tinh gọn file `VI_Thi_Cong_Kinh_Doanh/84_Bien_Ban_Doi_Chieu_Vat_Tu_Sau_Gia_Cong.md` thành văn bản ban hành thuần túy pháp lý**
- [x] **Task 7: Thẩm định QA độc lập sau tinh chỉnh**
