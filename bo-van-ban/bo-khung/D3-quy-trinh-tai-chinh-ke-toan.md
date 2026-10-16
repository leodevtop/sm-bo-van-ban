> **BẢN THIẾT KẾ KIẾN TRÚC & CĂN CỨ LẬP LUẬN (CORE ARCHITECTURE & DESIGN RATIONALE)**
> - **Mục đích:** Tài liệu thiết kế nguồn, giải thích nguyên lý "vì sao như vậy" và căn cứ lập luận để xây dựng, đối chiếu và tái lập hệ thống văn bản vận hành của Công ty.
> - **Văn bản thực thi tương ứng trong Danh mục lưu hành:**
>   - STT 29: Quy trình tài chính, kế toán công trình (gồm tạm ứng, thanh toán)
>   - STT 30: Giấy đề nghị & thanh toán tạm ứng
>   - STT 31: Bảng tổng hợp quyết toán chi phí công trình

# D3 – QUY TRÌNH TÀI CHÍNH, KẾ TOÁN (TỐI GIẢN)

|                            |                                                                                 |
| -------------------------- | ------------------------------------------------------------------------------- |
| **Đơn vị ban hành**        | {{TEN_CONG_TY}}                                                                 |
| **Mã văn bản / Phiên bản** | D3 / 2.0                                                                        |
| **Ngày ban hành**          | {{NGAY_BAN_HANH}}                                                               |
| **Người ký ban hành**      | Giám đốc {{GIAM_DOC}}                                                           |
| **Rà soát kế toán**        | 6 tháng kể từ ngày ban hành, hoặc khi thay đổi quy định thuế, hóa đơn, bảo hiểm |

## 0. Phạm vi

Văn bản này chỉ quy định **quy trình nội bộ**. Chế độ kế toán, thuế, hóa đơn thực hiện theo **quy định pháp luật hiện hành** (Luật Kế toán, Luật Quản lý thuế, các luật thuế giá trị gia tăng, thu nhập doanh nghiệp, thu nhập cá nhân, quy định hóa đơn điện tử) và hướng dẫn của Kế toán trưởng. Thuế suất và hạn nộp do Kế toán kiểm tra theo văn bản hiện hành và **không ghi cứng** trong quy trình này.

## 1. Nguyên tắc

1. **Mỗi công trình là một đối tượng theo dõi chi phí và doanh thu** (theo mã công trình).
2. Mọi khoản chi có **chứng từ hợp lệ** và **được duyệt trước** theo C1.
3. **Thanh toán không dùng tiền mặt** đối với khoản đến ngưỡng theo quy định hiện hành (chuyển khoản).
4. **Lương trả qua tài khoản** để có chứng từ hợp lệ (A3).
5. Hợp đồng, nghiệm thu, hóa đơn và thanh toán **phải khớp nhau**.
6. **Tách nhiệm vụ:** người đề nghị, người duyệt, người chi, người hạch toán là các người khác nhau.

## 2. Tạm ứng

| Bước | Việc                                                                                 | Người                  |
| ---- | ------------------------------------------------------------------------------------ | ---------------------- |
| 1    | Giấy đề nghị tạm ứng (Mẫu D3-01): mục đích, công trình, số tiền, thời hạn quyết toán | Người đề nghị          |
| 2    | Kiểm tra không còn tạm ứng quá hạn; còn ngân sách dự toán                            | Kế toán                |
| 3    | Duyệt theo hạn mức (C1)                                                              | Trưởng phòng, Giám đốc |
| 4    | Chi                                                                                  | Thủ quỹ, ngân hàng     |
| 5    | **Quyết toán tạm ứng** (Mẫu D3-02) trong thời hạn tại Bảng tham số; hoàn trả phần dư | Người nhận             |
| 6    | Không cho tạm ứng mới nếu còn tạm ứng quá hạn                                        | Kế toán                |

**Mẫu D3-01 – Giấy đề nghị tạm ứng**

| Họ tên, bộ phận | Công trình (mã) | Mục đích | Số tiền | Thời hạn quyết toán | Trưởng phòng duyệt | Giám đốc duyệt |
| --------------- | --------------- | -------- | ------- | ------------------- | ------------------ | -------------- |
|                 |                 |          |         |                     |                    |                |

**Mẫu D3-02 – Bảng quyết toán tạm ứng**

| Khoản chi | Chứng từ (số, ngày) | Số tiền | Ghi chú |
| --------- | ------------------- | ------- | ------- |
|           |                     |         |         |

Tổng tạm ứng: **\_\_** Tổng đã chi: **\_\_** Hoàn trả hoặc chi thêm: **\_\_** Kế toán xác nhận: **\_\_**

## 3. Chu trình thu tiền (từ nghiệm thu)

| #   | Việc                                                                                                                                    | Người làm      |
| --- | --------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| 1   | Biên bản nghiệm thu khối lượng hoặc giai đoạn (D1)                                                                                      | Dự án          |
| 2   | Hồ sơ thanh toán theo hợp đồng (biên bản, bảng khối lượng, hóa đơn)                                                                     | Dự án, Kế toán |
| 3   | **Xuất hóa đơn đúng thời điểm và nội dung** theo hợp đồng và quy định về hóa đơn (Dạng 2: tách vật tư và thi công nếu hợp đồng yêu cầu) | Kế toán        |
| 4   | Theo dõi thanh toán, nhắc khách; **ghi nhận tiền về theo từng đợt**                                                                     | Kế toán        |
| 5   | Chuyển thông tin tiền về để tính **quỹ KPI** (A3 Chương IV)                                                                             | Kế toán        |
| 6   | Theo dõi **tiền giữ lại bảo hành** và ngày thu hồi                                                                                      | Kế toán        |

## 4. Chu trình chi

### 4A. Chi vật tư (Dạng 2) và nhà cung cấp

1. Đề nghị mua (Dự án) → báo giá → Giám đốc duyệt theo ngưỡng.
2. Hợp đồng hoặc đơn đặt hàng (D1 mục 2B).
3. Nhập kho có phiếu; nghiệm thu đầu vào (D1-05).
4. Đối chiếu **ba bên: đơn đặt hàng – phiếu nhập – hóa đơn**; có sai khác thì không thanh toán.
5. Thanh toán theo điều kiện hợp đồng; lưu chứng từ.

### 4B. Chi nhân công và chi phí công trường

| Khoản                                          | Quy trình                                                            | Chứng từ                                      |
| ---------------------------------------------- | -------------------------------------------------------------------- | --------------------------------------------- |
| Lương công nhân                                | Bảng chấm công (A4-02) → bảng lương (A3) → duyệt → **chuyển khoản**  | Bảng chấm công, bảng lương, ủy nhiệm chi      |
| Phụ cấp công trường                            | Theo A3                                                              | Bảng kê                                       |
| Tạm ứng                                        | Giám đốc duyệt; **hoàn ứng đúng hạn**                                | Giấy đề nghị tạm ứng, bảng quyết toán tạm ứng |
| Thuê cẩu, thiết bị                             | Hợp đồng thuê, hồ sơ kiểm định, nghiệm thu giờ máy                   | Hợp đồng, biên bản, hóa đơn                   |
| Thầu phụ, tổ đội                               | Hợp đồng với từng bên có chứng từ pháp lý; **nghiệm thu khối lượng** | Hợp đồng, biên bản, hóa đơn                   |
| An toàn (PPE, huấn luyện, bảo hiểm, kiểm định) | Ghi **mã chi phí an toàn** để theo dõi ngân sách                     | Hóa đơn                                       |

Công ty **không** trả công trực tiếp bằng tiền mặt cho công nhân không có hợp đồng và không có bảng chấm công.

## 5. Quyết toán công trình

| #   | Việc                                                                   | Thời hạn              |
| --- | ---------------------------------------------------------------------- | --------------------- |
| 1   | Chốt doanh thu theo nghiệm thu và hóa đơn                              | Sau khi hoàn thành    |
| 2   | Chốt chi phí: vật tư, nhân công, máy, thầu phụ, an toàn, chi phí chung | Sau khi hoàn thành    |
| 3   | So sánh với dự toán (D2); phân tích chênh lệch                         | Theo Bảng tham số     |
| 4   | **Tính KPI** theo tiền về thực tế (A3)                                 | Theo kỳ               |
| 5   | Theo dõi bảo hành, hoàn trả bảo lãnh và tiền giữ lại                   | Hết thời hạn bảo hành |
| 6   | Lưu hồ sơ theo C2                                                      | Sau khi quyết toán    |

**Mẫu D3-03 – Quyết toán công trình**

| Khoản mục        | Dự toán | Thực tế | Chênh lệch | Nguyên nhân |
| ---------------- | ------- | ------- | ---------- | ----------- |
| Doanh thu        |         |         |            |             |
| Nhân công        |         |         |            |             |
| BHXH và bảo hiểm |         |         |            |             |
| Vật tư (Dạng 2)  |         |         |            |             |
| Thiết bị         |         |         |            |             |
| Chi phí an toàn  |         |         |            |             |
| Chi phí chung    |         |         |            |             |
| **Lợi nhuận**    |         |         |            |             |

## 6. Công nợ phải trả và tiền

1. Sổ theo dõi nhà cung cấp, thầu phụ; thanh toán đúng hạn hợp đồng; đối chiếu công nợ định kỳ.
2. Quỹ tiền mặt: thủ quỹ kiểm kê hằng tháng; mức tồn quỹ tối đa theo Bảng tham số; đối chiếu ngân hàng hằng tháng.
3. Trích nộp BHXH, BHYT, BHTN đúng hạn; **thiếu đóng hoặc chậm đóng bị xử phạt theo Nghị định 283/2026/NĐ-CP**: Kế toán kiểm tra trước khi chốt kỳ.

## 7. Bảo lãnh, bảo hiểm, tiền giữ lại

1. Theo dõi **bảo lãnh thực hiện hợp đồng, bảo lãnh tạm ứng, bảo lãnh bảo hành**: ngày hiệu lực, thời hạn, chi phí.
2. Theo dõi **hợp đồng bảo hiểm công trường** (B4): thời hạn, phạm vi, phí; gia hạn khi công trình kéo dài.

## 8. Thuế và nghĩa vụ lao động

| Nghĩa vụ                            | Việc Kế toán làm                                                                                                                                                                          |
| ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thuế thu nhập cá nhân từ tiền lương | Khấu trừ theo Luật Thuế thu nhập cá nhân 2025: giảm trừ gia cảnh và biểu thuế 5 bậc theo Bảng tham số; công nhân thời vụ có hợp đồng dưới 03 tháng xử lý theo quy định khấu trừ hiện hành |
| BHXH, BHYT, BHTN                    | Khai tăng, giảm đúng hạn; đóng đúng kỳ (A4)                                                                                                                                               |
| Kinh phí công đoàn                  | Trích đóng theo quy định                                                                                                                                                                  |
| Thuế GTGT, TNDN, hóa đơn            | Theo hướng dẫn thuế hiện hành; Kế toán rà soát hợp đồng Dạng 2 (vật tư và thi công)                                                                                                       |

## 9. Báo cáo quản trị (hằng tháng, tối giản)

| Báo cáo                             | Nội dung                                | Gửi                                       |
| ----------------------------------- | --------------------------------------- | ----------------------------------------- |
| Doanh thu – tiền về theo công trình | Hóa đơn, đã thu, còn phải thu           | Giám đốc                                  |
| Chi phí theo công trình             | So với dự toán                          | Giám đốc, Dự án                           |
| Công nợ nhà cung cấp, thầu phụ      | Tuổi nợ                                 | Giám đốc                                  |
| Dòng tiền 03 tháng tới              | Thu, chi, bảo lãnh                      | Giám đốc                                  |
| An toàn                             | Chi phí an toàn thực tế so với kế hoạch | Giám đốc, người phụ trách quản lý an toàn |

## 10. Căn cứ

Luật Kế toán; Luật Quản lý thuế; Luật Thuế thu nhập cá nhân 2025; quy định về hóa đơn điện tử; Luật Bảo hiểm xã hội 2024; Nghị định 283/2026/NĐ-CP. Xem `00-can-cu-phap-ly.md`.
