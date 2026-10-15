# BẢNG TỔNG HỢP QUYẾT TOÁN CHI PHÍ VÀ HIỆU QUẢ CÔNG TRÌNH

| THÔNG TIN BẢNG QUYẾT TOÁN | NỘI DUNG CHI TIẾT |
| :--- | :--- |
| **Công ty ban hành** | **<<CTY_TEN>>** |
| **Mã công trình / Dự án** | `<<CT_MA>>` |
| **Tên công trình** | **<<CT_TEN>>** |
| **Địa điểm thi công** | <<CT_DIA_DIEM>> |
| **Chủ đầu tư / Tổng thầu** | <<CDT_TEN>> / **<<KH_TEN>>** |
| **Mã biểu mẫu** | `31/BM-QTCP-<<CTY_TEN_VT>>` |
| **Phiên bản** | `1.0` |
| **Thời gian thi công thực tế** | Từ ngày `<<NGAY_KHOI_CONG>>` đến ngày `<<NGAY_HOAN_THANH>>` |
| **Chế độ kế toán áp dụng** | **Thông tư số 133/2016/TT-BTC** *(Tài khoản 154 theo dõi theo dự án)* |

---

## 1. TỔNG HỢP DOANH THU QUYẾT TOÁN CÔNG TRÌNH

*(Căn cứ theo Biên bản thanh lý hợp đồng số `77/BB-TLHD-<<CTY_TEN_VT>>` và Hóa đơn GTGT đã xuất)*

| STT | Chỉ tiêu doanh thu | Giá trị theo Hợp đồng gốc *(VNĐ)* | Giá trị Phát sinh được duyệt *(VNĐ)* | Giá trị Quyết toán cuối cùng *(VNĐ)* | Ghi chú |
| :---: | :--- | :---: | :---: | :---: | :--- |
| 1 | Doanh thu trước thuế (Doanh thu thuần) | <<DT_GOC_CHUA_THUE>> | <<DT_PS_CHUA_THUE>> | **<<DOANH_THU_THUAN>>** | Ghi nhận TK 5112 |
| 2 | Thuế Giá trị gia tăng (VAT) | <<VAT_GOC>> | <<VAT_PS>> | **<<TONG_THUE_VAT>>** | Ghi nhận TK 33311 |
| 3 | **Tổng giá trị thanh toán bao gồm VAT:** | **<<TONG_DT_GOC>>** | **<<TONG_DT_PS>>** | **<<TONG_DOANH_THU>>** | Hạch toán TK 131 |

---

## 2. BẢNG SO SÁNH DỰ TOÁN NGÂN SÁCH VÀ CHI PHÍ THỰC TẾ (TK 154)

*(Đơn vị tính: VNĐ)*

| Mã TK kế toán | Khoản mục chi phí công trình | Dự toán ngân sách duyệt ban đầu *(Budget - A)* | Chi phí thực tế tập hợp trên sổ sách *(Actual - B)* | Chênh lệch tăng/giảm *(C = B - A)* | Tỷ lệ thực hiện so với DT *(% B/A)* | Nguyên nhân chênh lệch và giải trình |
| :---: | :--- | :---: | :---: | :---: | :---: | :--- |
| **1541** | **I. Chi phí nguyên vật liệu trực tiếp** | **<<DT_1541>>** | **<<TT_1541>>** | **<<CL_1541>>** | **<<TL_1541>>%** | |
| 15411 | Vật tư phụ lắp dựng (que hàn, sơn dặm vá, giẻ lau, oxy-gas...) | <<DT_15411>> | <<TT_15411>> | <<CL_15411>> | <<TL_15411>>% | Tối ưu đường hàn và tiết kiệm sơn dặm vá hiện trường |
| 15412 | Bu lông liên kết, ty giằng bổ sung hiện trường | <<DT_15412>> | <<TT_15412>> | <<CL_15412>> | <<TL_15412>>% | Hao hụt bu lông đạt định mức cho phép (< 1.5%) |
| 15413 | Cấu kiện thép mua ngoài *(nếu nhận thầu trọn gói theo PO 75)* | <<DT_15413>> | <<TT_15413>> | <<CL_15413>> | <<TL_15413>>% | Mua đúng giá thầu đã chốt với Nhà máy <<NCC_TEN>> |
| **1542** | **II. Chi phí nhân công trực tiếp** | **<<DT_1542>>** | **<<TT_1542>>** | **<<CL_1542>>** | **<<TL_1542>>%** | |
| 15421 | Lương thợ lắp dựng nòng cốt & thợ hàn bậc cao | <<DT_15421>> | <<TT_15421>> | <<CL_15421>> | <<TL_15421>>% | Chi trả 100% qua tài khoản ngân hàng cá nhân |
| 15422 | Lương nhân công thời vụ / thợ phụ hỗ trợ | <<DT_15422>> | <<TT_15422>> | <<CL_15422>> | <<TL_15422>>% | Điều động linh hoạt theo tiến độ khung kèo |
| 15423 | Phụ cấp độc hại, phụ cấp làm việc trên cao | <<DT_15423>> | <<TT_15423>> | <<CL_15423>> | <<TL_15423>>% | Theo Bảng chấm công thực tế trên cao |
| 15424 | Phụ cấp công trình xa nhà & tiền làm thêm giờ (OT) | <<DT_15424>> | <<TT_15424>> | <<CL_15424>> | <<TL_15424>>% | Làm đêm 03 ca để cẩu kèo băng qua đường nội bộ |
| **1543** | **III. Chi phí máy thi công** | **<<DT_1543>>** | **<<TT_1543>>** | **<<CL_1543>>** | **<<TL_1543>>%** | |
| 15431 | Thuê xe cẩu bánh lốp chính (50T - 100T) | <<DT_15431>> | <<TT_15431>> | <<CL_15431>> | <<TL_15431>>% | Rút ngắn được 02 ngày thuê nhờ cẩu liên tục |
| 15432 | Thuê xe cẩu phụ phục vụ bốc dỡ & xe nâng Boom lift | <<DT_15432>> | <<TT_15432>> | <<CL_15432>> | <<TL_15432>>% | Theo ca máy thực tế có ký xác nhận của TVGS |
| 15433 | Chi phí vận chuyển huy động và giải tỏa cẩu | <<DT_15433>> | <<TT_15433>> | <<CL_15433>> | <<TL_15433>>% | Hóa đơn đơn vị vận tải chuyên dụng |
| 15434 | Nhiên liệu dầu Diesel, máy hàn điện, máy nén khí | <<DT_15434>> | <<TT_15434>> | <<CL_15434>> | <<TL_15434>>% | Tiêu hao định mức theo giờ máy chạy |
| **1547** | **IV. Chi phí chung công trình** | **<<DT_1547>>** | **<<TT_1547>>** | **<<CL_1547>>** | **<<TL_1547>>%** | |
| 15471 | Lán trại tạm, điện nước thi công & mặt bằng | <<DT_15471>> | <<TT_15471>> | <<CL_15471>> | <<TL_15471>>% | Tận dụng nhà xưởng giai đoạn 1 làm kho chứa |
| 15472 | Chi phí trang bị bảo hộ lao động (PPE), lưới an toàn | <<DT_15472>> | <<TT_15472>> | <<CL_15472>> | <<TL_15472>>% | Đầy đủ hóa đơn mua từ nhà cung cấp bảo hộ |
| 15473 | Phí kiểm định kỹ thuật an toàn máy móc thiết bị | <<DT_15473>> | <<TT_15473>> | <<CL_15473>> | <<TL_15473>>% | Trung tâm kiểm định an toàn cấp tem |
| 15474 | Bảo hiểm mọi rủi ro xây dựng (CAR) & bên thứ ba | <<DT_15474>> | <<TT_15474>> | <<CL_15474>> | <<TL_15474>>% | Hợp đồng bảo hiểm công trình |
| 15475 | Chi phí lương Ban chỉ huy CT & tiếp khách, VPP | <<DT_15475>> | <<TT_15475>> | <<CL_15475>> | <<TL_15475>>% | Theo hạn mức quỹ tiền mặt công trường |
| | **TỔNG GIÁ THÀNH THI CÔNG (TK 154 = I+II+III+IV):** | **<<TONG_DT_154>>** | **<<TONG_TT_154>>** | **<<CL_TONG_154>>** | **<<TL_TONG_154>>%** | **Kết chuyển sang TK 632** |
| 6422 | Chi phí quản lý doanh nghiệp phân bổ (tỷ lệ 3% - 5%) | <<DT_6422>> | <<TT_6422>> | <<CL_6422>> | <<TL_6422>>% | Theo quy chế tài chính công ty |
| | **TỔNG CHI PHÍ CÔNG TRÌNH:** | **<<TONG_CP_DT>>** | **<<TONG_CP_TT>>** | **<<CL_TONG_CP>>** | **<<TL_TONG_CP>>%** | |

---

## 3. ĐÁNH GIÁ HIỆU QUẢ TÀI CHÍNH VÀ LỢI NHUẬN CÔNG TRÌNH

| STT | Chỉ tiêu tài chính | Mục tiêu ban đầu | Kết quả thực tế đạt được | Chênh lệch so với kế hoạch | Đánh giá |
| :---: | :--- | :---: | :---: | :---: | :--- |
| 1 | **Doanh thu thuần (chưa VAT):** | <<DT_MUC_TIEU>> | <<DOANH_THU_THUAN>> | <<CL_DT_THUAN>> | Đạt <<TL_DT>>% kế hoạch |
| 2 | **Giá vốn xây lắp (TK 632 = TK 154):** | <<TONG_DT_154>> | <<TONG_TT_154>> | <<CL_TONG_154>> | Tiết kiệm chi phí: <<TIET_KIEM_CP>> VNĐ |
| 3 | **Lợi nhuận gộp (Gross Profit = 1 - 2):** | **<<LN_GOP_DT>>** | **<<LN_GOP_TT>>** | **<<CL_LN_GOP>>** | Vượt mục tiêu: <<VUOT_MUC_TIEU>> VNĐ |
| 4 | **Tỷ suất lợi nhuận gộp (%):** | **<<TY_SUAT_LN_DT>>%** | **<<TY_SUAT_LN_TT>>%** | **+<<TANG_TY_SUAT>>%** | Biên lợi nhuận đạt yêu cầu |
| 5 | **Lợi nhuận trước thuế sau phân bổ QLDN:** | <<LN_ST_DT>> | <<LN_ST_TT>> | <<CL_LN_ST>> | Hoàn thành xuất sắc |

---

## 4. ĐỀ XUẤT TRÍCH LẬP QUỸ THƯỞNG DỰ ÁN

Căn cứ Quy chế tiền lương thưởng và Quy chế thưởng KPI dự án (`23_Quy_Che_Luong_KPI_Du_An_2026.md`), do công trình hoàn thành vượt tiến độ, đảm bảo an toàn tuyệt đối và tiết kiệm chi phí, Hội đồng xét thưởng đề xuất:
1. **Tổng quỹ thưởng hiệu quả dự án đề xuất trích lập:** `<<TONG_QUY_THUONG_DA>>` VNĐ.
2. **Nguyên tắc phân chia quỹ thưởng:**
   - Ban Chỉ huy công trường (Chỉ huy trưởng, kỹ sư trắc đạc, an toàn viên HSE): 50% quỹ thưởng.
   - Tổ đội công nhân lắp dựng trực tiếp & thợ hàn nòng cốt: 30% quỹ thưởng.
   - Phòng Kỹ thuật - Thi công & Phòng Kinh doanh: 20% quỹ thưởng.
3. **Quy định loại trừ đặc biệt:** **Phòng Hành chính - Nhân sự KHÔNG tham gia trích chia quỹ thưởng KPI dự án này** (tuân thủ nghiêm ngặt theo Quy chế thưởng dự án nhằm đảm bảo tính khách quan trong công tác quản trị và giám sát nhân sự).

---

## CĂN CỨ PHÁP LÝ

1. Luật Kế toán số 88/2015/QH13.
2. Thông tư số 133/2016/TT-BTC ngày 26/08/2016 của Bộ Tài chính hướng dẫn Chế độ kế toán doanh nghiệp nhỏ và vừa.
3. Luật Thuế Thu nhập doanh nghiệp số 14/2008/QH12 và các văn bản hướng dẫn thi hành.
4. Hợp đồng thi công số `<<HD_SO>>` và Biên bản thanh lý hợp đồng số `77/BB-TLHD-<<CTY_TEN_VT>>`.
5. Quy chế tiền lương, tiền thưởng và quy chế thưởng KPI dự án của **<<CTY_TEN>>**.

---

| KỸ SƯ DỰ TOÁN CÔNG TRÌNH | CHỈ HUY TRƯỞNG CÔNG TRƯỜNG | KẾ TOÁN TRƯỞNG | GIÁM ĐỐC CÔNG TY PHÊ DUYỆT |
| :---: | :---: | :---: | :---: |
| *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký tên và đóng dấu)* |
| | | | **<<NGUOI_DAI_DIEN_PHAP_LUAT>>** |
| | **<<CHT_TEN>>** | **<<KTT_TEN>>** | Đại diện pháp luật |
