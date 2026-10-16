> **BẢN THIẾT KẾ KIẾN TRÚC & CĂN CỨ LẬP LUẬN (CORE ARCHITECTURE & DESIGN RATIONALE)**
> - **Mục đích:** Tài liệu thiết kế nguồn, giải thích nguyên lý "vì sao như vậy" và căn cứ lập luận để xây dựng, đối chiếu và tái lập hệ thống văn bản vận hành của Công ty.
> - **Văn bản thực thi tương ứng trong Danh mục lưu hành:**
>   - STT 63: Quy chế tổ chức, phân quyền, chức danh công trường, báo cáo nội bộ

# C1 – QUY CHẾ TỔ CHỨC VÀ PHÂN QUYỀN

|                            |                                     |
| -------------------------- | ----------------------------------- |
| **Đơn vị ban hành**        | {{TEN_CONG_TY}}                     |
| **Mã văn bản / Phiên bản** | C1 / 2.0                            |
| **Ngày ban hành**          | {{NGAY_BAN_HANH}}                   |
| **Người ký ban hành**      | Giám đốc {{GIAM_DOC}}               |
| **Rà soát kế tiếp**        | Hằng năm, hoặc khi thay đổi tổ chức |

Quy chế này thay thế các văn bản riêng về tổ chức, ủy quyền, thẩm quyền ký duyệt, nhiệm vụ ban chỉ huy công trường, con dấu và văn thư.

## 1. Cơ cấu tổ chức

```
Giám đốc
├─ Phòng Thi công (Chỉ huy trưởng, kỹ sư công trường, an toàn viên, tổ thợ, thủ kho công trường)
├─ Phòng Dự án kiêm Kinh doanh (kế hoạch, kỹ thuật, hồ sơ chất lượng, vật tư; báo giá, hợp đồng, khách hàng, công nợ)
├─ Phòng Kế toán – Tài chính (kế toán, tài chính, thuế, thủ quỹ)
└─ Hành chính – Nhân sự (nhân sự, hợp đồng lao động, BHXH, văn thư, IT)
```

1. Cơ cấu này khớp với bốn phòng tham gia Quỹ KPI dự án (Thi công 50%; Dự án kiêm Kinh doanh 25%; Kế toán – Tài chính 15%; Hành chính – Nhân sự 10%). Công ty **không sản xuất, gia công**; vật tư thép, bu lông, phụ kiện được mua thành phẩm từ nhà cung cấp. Nhiệm vụ mua vật tư thuộc Phòng Dự án, kho và thiết bị tại công trường thuộc Phòng Thi công.
2. **Người phụ trách quản lý an toàn** ({{NGUOI_PT_AN_TOAN}}) thuộc Phòng Dự án và có quyền báo cáo trực tiếp Giám đốc về an toàn.
3. Khi Công ty tách riêng phòng Vật tư – Thiết bị hoặc phòng Kinh doanh, Giám đốc chuyển các nhiệm vụ vật tư, thiết bị hoặc kinh doanh ở mục 2 sang phòng đó, cập nhật tỷ lệ KPI (A3 Phụ lục 2) và ghi vào nhật ký rà soát.

## 2. Chức năng các phòng

| Phòng                       | Chức năng chính                                                                                                                                                                                                           | Đầu ra                                                                     | Văn bản        |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- | -------------- |
| **Thi công**                | Tổ chức thi công an toàn, đúng tiến độ, chất lượng; thực hiện B2; điều hành công trường; nghiệm thu nội bộ; cấp phát PPE; quản lý thiết bị công trường                                                                    | Nhật ký thi công, hồ sơ B2                                                 | B1, B2, D1     |
| **Dự án (kiêm Kinh doanh)** | Kế hoạch, biện pháp thi công, hồ sơ chất lượng, hoàn công; **mua vật tư, nhà cung cấp, nghiệm thu vật tư đầu vào (hợp đồng gồm vật tư)**; quản lý an toàn; tìm khách, báo giá, thương thảo, ký hợp đồng, theo dõi công nợ | Hồ sơ công trình, hoàn công, sổ vật tư, hợp đồng, báo giá, báo cáo công nợ | D1, D2, B1, B4 |
| **Kế toán – Tài chính**     | Tạm ứng, thanh toán, quyết toán công trình, thuế, lương                                                                                                                                                                   | Báo cáo tài chính, quyết toán                                              | D3, A3         |
| **Hành chính – Nhân sự**    | Tuyển dụng, hợp đồng lao động, chấm công, BHXH, văn thư, lưu trữ, dữ liệu, đối thoại                                                                                                                                      | Hồ sơ nhân sự, sổ văn bản                                                  | A1–A4, C2, D4  |

## 3. Thẩm quyền ký, duyệt

Các ngưỡng giá trị lấy theo Bảng tham số (Phần III.5).

| Việc                                                              | Người soạn              | Người kiểm tra                                      | **Người ký, duyệt**                                                                                 |
| ----------------------------------------------------------------- | ----------------------- | --------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| Báo giá, đấu thầu                                                 | Dự án (kiêm Kinh doanh) | Kế toán                                             | Giám đốc (giá trị trên ngưỡng báo giá); dưới ngưỡng: Trưởng phòng Dự án, báo cáo Giám đốc hằng tuần |
| **Hợp đồng với chủ đầu tư, tổng thầu** (kèm điều khoản B4)        | Dự án (kiêm Kinh doanh) | Kế toán, người phụ trách an toàn, luật sư (khi cần) | **Giám đốc**                                                                                        |
| Hợp đồng nhà cung cấp, thầu phụ, thuê thiết bị                    | Dự án                   | Kế toán                                             | Giám đốc nếu trên ngưỡng hợp đồng nhà cung cấp; dưới ngưỡng: Trưởng phòng Dự án                     |
| Hợp đồng lao động, phụ lục, quyết định tuyển dụng, kỷ luật        | Hành chính – Nhân sự    | Trưởng phòng                                        | Giám đốc                                                                                            |
| Biện pháp an toàn công trình (B2-03)                              | An toàn viên            | Người phụ trách quản lý an toàn                     | **Giám đốc**, kèm chấp thuận của chủ đầu tư hoặc tổng thầu                                          |
| Giấy phép làm việc nguy hiểm (B2-05)                              | Tổ trưởng               | An toàn viên                                        | Chỉ huy trưởng                                                                                      |
| Nhật ký thi công, hoàn công                                       | Chỉ huy trưởng          | Dự án                                               | Chỉ huy trưởng và đại diện bên giao thầu                                                            |
| Đề nghị thanh toán, quyết toán công trình                         | Dự án, Kế toán          | Trưởng phòng                                        | Giám đốc                                                                                            |
| Khoản chi không vượt ngưỡng chi của Trưởng phòng                  | Người đề nghị           | Trưởng phòng                                        | Trưởng phòng                                                                                        |
| Khoản chi vượt ngưỡng chi của Trưởng phòng                        | Người đề nghị           | Kế toán trưởng                                      | Giám đốc                                                                                            |
| Báo cáo cơ quan nhà nước (lao động, BHXH, thuế, an toàn lao động) | Phòng phụ trách         | Trưởng phòng                                        | Giám đốc hoặc người được ủy quyền                                                                   |
| **Dừng việc vì an toàn**                                          | Bất kỳ ai               | –                                                   | Chỉ huy trưởng, an toàn viên **có quyền quyết định ngay**                                           |

**Ủy quyền** thực hiện bằng văn bản, nêu phạm vi và thời hạn; không ủy quyền lại trừ khi văn bản ủy quyền nêu rõ; không ủy quyền quyết định đình chỉ vì an toàn cho người không có chuyên môn.

## 4. Nhiệm vụ chức danh công trường

**Chỉ huy trưởng.** Chịu trách nhiệm toàn bộ hiện trường (tiến độ, chất lượng, an toàn, nhân sự, chi phí). Tổ chức thi công theo B2 và hợp đồng; **dừng việc** khi thiếu an toàn; duyệt phiếu làm thêm giờ và bảng chấm công; cấp giấy phép làm việc nguy hiểm; làm việc với tổng thầu, chủ đầu tư và lưu biên bản kiểm tra; lập nhật ký thi công và báo cáo; xử lý ban đầu tai nạn, sự cố (B3). Điều kiện: được huấn luyện an toàn, vệ sinh lao động nhóm phù hợp, đủ năng lực theo hợp đồng.

**An toàn viên.** Kiểm tra hằng ngày; họp an toàn; lập hồ sơ B2; đánh giá rủi ro; lập phiếu khắc phục; có quyền yêu cầu dừng việc; **báo cáo trực tiếp người phụ trách quản lý an toàn và Giám đốc khi xung đột với tiến độ**.

**Thủ kho.** Nhận, xuất, tồn vật tư; cấp, kiểm tra, thu hồi PPE (B2-08); quản lý công cụ; không xuất khi thiếu phiếu được duyệt; kiểm kê hằng tháng; báo thiếu hụt (D1).

**Tổ trưởng.** Phân công; chấm công; kiểm tra PPE; báo nguy cơ; họp đầu ca; **không giao việc yêu cầu nghiêm ngặt cho người chưa có thẻ an toàn**.

## 5. Chế độ báo cáo

| Báo cáo              | Người lập                    | Gửi                   | Tần suất                  |
| -------------------- | ---------------------------- | --------------------- | ------------------------- |
| Nhật ký công trường  | Chỉ huy trưởng               | Dự án                 | Hằng ngày                 |
| Báo cáo an toàn      | An toàn viên                 | Người quản lý an toàn | Hằng tuần                 |
| Tiến độ, khối lượng  | Chỉ huy trưởng               | Giám đốc              | Hằng tuần hoặc hằng tháng |
| Nhân sự, chấm công   | Hành chính – Nhân sự         | Giám đốc, Kế toán     | Hằng tháng                |
| Kho, vật tư          | Thủ kho                      | Dự án, Kế toán        | Hằng tháng                |
| Tài chính công trình | Kế toán                      | Giám đốc              | Hằng tháng                |
| Tai nạn, sự cố       | Chỉ huy trưởng, an toàn viên | Giám đốc              | Ngay (B3)                 |
| Cơ quan nhà nước     | Phòng phụ trách              | Cơ quan nhà nước      | Theo luật                 |

## 6. Con dấu, chữ ký, văn thư

1. Con dấu do {{NGUOI_GIU_DAU}} giữ; chỉ đóng khi có chữ ký của người có thẩm quyền; ghi sổ sử dụng.
2. Văn bản đi, đến ghi sổ (C2 mục 6); bản gốc lưu tại Công ty, bản sao lưu tại công trình.

## 7. Nguyên tắc chung

1. Mỗi việc có **một người chịu trách nhiệm**; trường hợp kiêm nhiệm phải ghi rõ bằng văn bản.
2. Người làm an toàn không phụ thuộc áp lực tiến độ: có quyền báo cáo trực tiếp Giám đốc.
3. Xung đột thẩm quyền giải quyết theo mục 3; nếu không rõ thì Giám đốc quyết định.
4. Họp giao ban tuần; họp xem xét HSE hằng quý (B1).

## 8. Căn cứ

Luật Doanh nghiệp; Điều lệ Công ty; Nghị định 207/2026/NĐ-CP. Xem `00-can-cu-phap-ly.md`.

---

{{DIA_DANH}}, ngày **_ tháng _** năm **\_\_**

**GIÁM ĐỐC**
(ký, đóng dấu, ghi rõ họ tên: {{GIAM_DOC}})
