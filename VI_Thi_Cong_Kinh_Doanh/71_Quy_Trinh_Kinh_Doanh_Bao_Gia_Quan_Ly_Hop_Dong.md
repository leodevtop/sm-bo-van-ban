# QUY TRÌNH KINH DOANH, BÁO GIÁ VÀ QUẢN LÝ HỢP ĐỒNG THI CÔNG LẮP DỰNG

| THÔNG TIN QUẢN TRỊ VĂN BẢN | NỘI DUNG CHI TIẾT |
| :--- | :--- |
| **Đơn vị ban hành** | **<<CTY_TEN>>** |
| **Mã văn bản** | `71/QT-KD-<<CTY_TEN_VT>>` |
| **Phiên bản** | `1.0` |
| **Ngày ban hành** | `<<VB_NGAY>>/<<VB_THANG>>/<<VB_NAM>>` |
| **Người phê duyệt** | Giám đốc / Đại diện pháp luật `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` |
| **Phạm vi áp dụng** | Toàn bộ Phòng Kinh doanh - Đấu thầu, Phòng Kỹ thuật, Phòng Tài chính - Kế toán, Ban Chỉ huy công trường và các bộ phận liên quan |

---

## ĐIỀU 1. MỤC ĐÍCH VÀ PHẠM VI ÁP DỤNG

### 1.1. Mục đích
1. Chuẩn hóa toàn bộ chu trình kinh doanh từ tiếp nhận thông tin dự án, khảo sát, lập dự toán báo giá, thẩm định rủi ro pháp lý - thương mại, đàm phán ký kết hợp đồng đến bàn giao triển khai thi công và theo dõi thu hồi công nợ.
2. Kiểm soát chặt chẽ biên lợi nhuận, chi phí huy động xe cẩu - thiết bị nâng hạ, nhân công lắp dựng kết cấu thép và vật tư phụ; ngăn ngừa các rủi ro bất lợi trong hợp đồng thầu phụ với Tổng thầu / Chủ đầu tư.
3. Đảm bảo tính minh bạch, thống nhất trách nhiệm và phân cấp thẩm quyền phê duyệt giữa các bộ phận trong toàn công ty.

### 1.2. Phạm vi áp dụng
- Áp dụng đối với tất cả các hoạt động tìm kiếm cơ hội kinh doanh, báo giá dự thầu, đàm phán ký kết và quản lý thực hiện hợp đồng thi công lắp dựng kết cấu thép nhà xưởng công nghiệp tại **<<CTY_TEN>>**.
- Không áp dụng cho hoạt động sản xuất, gia công kết cấu thép tại nhà máy (Công ty hoạt động chuyên sâu trong lĩnh vực thi công lắp dựng tại hiện trường, cấu kiện thép gia công hoàn thiện và bu lông neo do Tổng thầu/Chủ đầu tư cấp hoặc Công ty đặt mua từ nhà máy gia công chuyên nghiệp).

---

## ĐIỀU 2. LƯU ĐỒ QUY TRÌNH TỔNG THỂ

```
[B1: Tiếp nhận RFQ / Lead]
          ↓
[B2: Khảo sát hiện trường & Thu thập dữ liệu kỹ thuật]
          ↓
[B3: Bóc tách khối lượng, Định mức cẩu & Lập dự toán]
          ↓
[B4: Thẩm duyệt đơn giá & Báo giá theo thẩm quyền]
          ↓
[B5: Gửi Báo giá & Đàm phán kỹ thuật - thương mại]
          ↓
[B6: Thẩm định rủi ro HĐ (Checklist 76) & Trình ký HĐ]
          ↓
[B7: Ký kết hợp đồng & Bàn giao triển khai thi công]
          ↓
[B8: Theo dõi thực hiện, Phát sinh (VO) & Thu hồi công nợ]
          ↓
[B9: Quyết toán và Thanh lý hợp đồng (Biên bản 77)]
```

---

## ĐIỀU 3. CÁC BƯỚC THỰC HIỆN CHI TIẾT

### Bước 1: Tiếp nhận yêu cầu báo giá (Lead / RFQ)
1. **Đầu mối tiếp nhận:** Phòng Kinh doanh - Đấu thầu tiếp nhận thông tin dự án qua thư mời thầu (RFP/RFQ), email, mối quan hệ đối tác hoặc đăng ký thông tin từ Tổng thầu/Khách hàng `<<KH_TEN>>`.
2. **Thu thập thông tin sơ bộ:**
   - Tên công trình: `<<CT_TEN>>`, địa điểm thi công: `<<CT_DIA_DIEM>>`.
   - Chủ đầu tư: `<<CDT_TEN>>`, Tổng thầu chính: `<<KH_TEN>>`.
   - Quy mô dự án: Diện tích nhà xưởng, tổng khối lượng kết cấu thép ước tính (tấn), chiều cao đỉnh mái, khẩu độ nhịp kèo lớn nhất, trọng lượng cấu kiện nặng nhất.
   - Hình thức hợp đồng dự kiến: Chỉ nhân công và xe máy thiết bị (Nhân công + Cẩu) HOẶC Cung cấp trọn gói vật tư kết cấu thép + Lắp dựng hoàn thiện.
   - Tiến độ yêu cầu và mốc thời gian bàn giao mặt bằng dự kiến.
3. **Sàng lọc ban đầu:** Trưởng phòng Kinh doanh đánh giá tính khả thi về năng lực huy động thiết bị và nhân sự. Trường hợp không phù hợp, làm văn bản từ chối lịch sự trong vòng 02 ngày làm việc.

### Bước 2: Khảo sát hiện trường & Thu thập dữ liệu kỹ thuật
1. Phòng Kinh doanh phối hợp với Phòng Kỹ thuật cử kỹ sư chuyên trách tiến hành khảo sát thực địa tại `<<CT_DIA_DIEM>>`:
   - Kiểm tra đường giao thông tiếp cận công trường, tải trọng cầu đường, bán kính quay xe cho xe rơ-moóc chở cấu kiện siêu trường siêu trọng.
   - Kiểm tra mặt bằng lắp dựng: Tình trạng san nền, độ chặt nền đất, khả năng chịu tải của nền cho xe cẩu chuyên dụng (cẩu bánh lốp 50T - 200T, cẩu bánh xích).
   - Kiểm tra hệ thống móng, tim cốt bu lông móng (anchor bolts), tình trạng vướng chướng ngại vật trên cao (đường dây điện cao thế) hoặc ngầm dưới đất.
   - Nguồn cấp điện thi công, nước sinh hoạt, mặt bằng lán trại tạm và khu vực tập kết vật tư.
2. Lập **Biên bản khảo sát hiện trường** có chữ ký xác nhận của cán bộ khảo sát và đại diện Tổng thầu (nếu có mặt tại hiện trường).

### Bước 3: Bóc tách khối lượng, Tính định mức thiết bị & Lập dự toán
1. **Phòng Kỹ thuật:**
   - Bóc tách chi tiết khối lượng cấu kiện thép: Cột, kèo, xà gồ mái/vách, giằng, tôn lợp, bu lông liên kết (cấp bền 8.8, 10.9), bu lông neo.
   - Lập phương án tổ chức thi công sơ bộ: Lựa chọn chủng loại cẩu chính, cẩu phụ, xe nâng người boom lift/scissor lift, giàn giáo, sàn thao tác treo.
   - Tính toán số ca máy/tháng thuê xe cẩu và tiêu hao nhiên liệu, nhân lực lắp dựng cần thiết cho từng phân đoạn thi công.
2. **Phòng Kinh doanh:**
   - Thu thập báo giá từ các nhà máy gia công thép (nếu hợp đồng bao gồm cung cấp vật tư) theo chuẩn chất lượng yêu cầu.
   - Lấy báo giá thuê cẩu, xe nâng từ các nhà cung ứng thiết bị tại địa phương lân cận công trường để tối ưu chi phí vận chuyển huy động.
   - Lập Bảng tính dự toán giá vốn nội bộ (Cost Sheet) bao gồm:
     + Chi phí nhân công trực tiếp (thợ lắp dựng, thợ hàn 3G/4G, thợ phụ, chỉ huy trưởng, an toàn viên HSE).
     + Chi phí máy thi công (cẩu lắp, xe nâng, máy hàn, máy siết bu lông chuyên dụng, máy phát điện).
     + Chi phí vật tư phụ (que hàn, sơn dặm vá, giẻ lau, cáp cẩu, ma-nê, dây an toàn, lưới hứng rơi).
     + Chi phí gián tiếp (lán trại, bảo hiểm CAR/TNDS, an toàn vệ sinh lao động, chi phí quản lý dự án).
     + Dự phòng rủi ro thời tiết, chậm trễ bàn giao mặt bằng (tối thiểu 3% - 5%).
     + Lợi nhuận mục tiêu định mức.

### Bước 4: Thẩm duyệt đơn giá & Phân cấp thẩm quyền phê duyệt
Mức đơn giá dự thầu và giá trị chào thầu phải tuân thủ hạn mức phân quyền phê duyệt của Công ty (chi tiết quy định theo Bảng tham số hiện hành):

| Phân nhóm giá trị gói thầu | Thẩm quyền thẩm định | Thẩm quyền phê duyệt báo giá cuối cùng |
| :--- | :--- | :--- |
| **Dưới 1.000.000.000 VNĐ** | Kỹ sư dự toán & Kế toán trưởng | Trưởng phòng Kinh doanh |
| **Từ 1.000.000.000 VNĐ đến 5.000.000.000 VNĐ** | Kế toán trưởng & Trưởng phòng Kỹ thuật | Phó Giám đốc / Giám đốc điều hành |
| **Trên 5.000.000.000 VNĐ** | Hội đồng thẩm định giá nội bộ | Giám đốc / Đại diện pháp luật `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` |

> *Ghi chú:* Bất kỳ báo giá nào có biên lợi nhuận gộp (Gross Margin) dự kiến thấp hơn ngưỡng tối thiểu quy định tại Bảng tham số hiện hành bắt buộc phải có văn bản phê duyệt ngoại lệ của Giám đốc Công ty.

### Bước 5: Lập Báo giá & Đàm phán thương thảo
1. Lập Hồ sơ chào giá hoàn chỉnh theo biểu mẫu `72_Mau_Bao_Gia.md`, bao gồm:
   - Thư chào giá (Form 1: Chỉ nhân công + thiết bị; Form 2: Cung ứng vật tư + lắp dựng).
   - Bảng phân tích đơn giá chi tiết, tiến độ thi công cam kết, điều kiện kỹ thuật loại trừ.
   - Giới hạn trách nhiệm về mặt bằng, nền móng, sai lệch bu lông móng của bên giao thầu.
2. Đàm phán hợp đồng: Phòng Kinh doanh chủ trì đàm phán thương mại (đơn giá, tạm ứng, giữ lại bảo hành, thanh toán theo tiến độ); Phòng Kỹ thuật tham gia đàm phán điều kiện kỹ thuật, biện pháp an toàn và tiến độ bàn giao.

### Bước 6: Thẩm định rủi ro hợp đồng (Checklist 76) & Trình ký
1. Trước khi trình ký bất kỳ hợp đồng thi công hoặc hợp đồng thầu phụ nào, Trưởng phòng Kinh doanh bắt buộc phải phối hợp với Bộ phận Pháp lý/Kế toán rà soát toàn bộ dự thảo hợp đồng dựa trên biểu mẫu `76_Checklist_Tham_Dinh_Rui_Ro_HD_va_Dieu_Kien_Huy_Dong.md`.
2. Kiểm tra các điều khoản then chốt:
   - Tỷ lệ tạm ứng hợp đồng (tối thiểu 10% - 20% giá trị gói thầu trước khi huy động quân).
   - Cơ chế nghiệm thu khối lượng theo đợt / theo từng trục khung dầm đã lắp giằng hoàn chỉnh.
   - Thời hạn thanh toán (không quá 15 - 30 ngày kể từ khi ký biên bản nghiệm thu).
   - Điều khoản trượt giá vật tư (nếu hợp đồng bao thầu thép).
   - Quyền tạm dừng thi công khi Tổng thầu chậm thanh toán mà không bị phạt vi phạm tiến độ.
   - Bảo hiểm công trình và bồi thường tai nạn lao động (liên kết mẫu `59_Phu_Luc_Dieu_Khoan_AT_Bao_Hiem_Tong_Thau.md`).
3. Nếu còn điểm bất lợi chưa thống nhất được với đối tác, phải đánh dấu `◐ cần xác nhận trước khi áp dụng` và báo cáo Giám đốc quyết định.

### Bước 7: Ký kết hợp đồng & Bàn giao triển khai nội bộ
1. Hợp đồng chính thức được ký bởi Đại diện pháp luật `<<NGUOI_DAI_DIEN_PHAP_LUAT>>` hoặc người được ủy quyền hợp pháp bằng văn bản.
2. Đóng dấu, lưu trữ bản gốc tại Phòng Kế toán - Pháp chế và scan bản mềm lưu trên hệ thống dữ liệu số.
3. Tổ chức cuộc họp **Bàn giao hợp đồng nội bộ (Handover Meeting)** trong vòng 03 ngày làm việc kể từ ngày ký:
   - Phòng Kinh doanh chuyển giao toàn bộ hồ sơ dự thầu, hợp đồng đã ký, dự toán ngân sách nội bộ (Budget Target) cho Ban Chỉ huy công trường (Chỉ huy trưởng `<<CHT_TEN>>`) và Phòng Tài chính - Kế toán.
   - Thống nhất mốc tiến độ huy động quân, máy móc xe cẩu theo `Checklist 76`.

### Bước 8: Quản lý thực hiện hợp đồng, Phát sinh (VO) & Thu hồi công nợ
1. **Theo dõi khối lượng và phát sinh (Variation Order - VO):**
   - Chỉ huy trưởng và Kỹ sư hiện trường chỉ được thi công các phần việc phát sinh ngoài phạm vi hợp đồng khi có Biên bản hiện trường hoặc Chỉ thị công việc (Site Instruction) bằng văn bản được ký bởi đại diện có thẩm quyền của Tổng thầu.
   - Chuyển thông tin phát sinh về Phòng Kinh doanh trong vòng 48 giờ để lập dự toán bổ sung và phát hành Phụ lục hợp đồng trước khi thanh quyết toán.
2. **Nghiệm thu và Hồ sơ thanh toán:**
   - Phối hợp với TVGS/Tổng thầu nghiệm thu từng giai đoạn lắp dựng bằng Phiếu yêu cầu và Biên bản nghiệm thu theo mẫu `69_Phieu_Yeu_Cau_va_Bien_Ban_Nghiem_Thu_Lap_Dung.md`.
   - Lập hồ sơ đề nghị thanh toán theo đợt gửi Tổng thầu kèm hóa đơn GTGT hợp lệ.
3. **Quản lý và đôn đốc thu hồi nợ:**
   - Kế toán công nợ theo dõi sát sao hạn thanh toán.
   - Nếu quá hạn 07 ngày: Gửi Thông báo đôn đốc lần 1.
   - Nếu quá hạn 15 ngày: Ban hành Công văn cảnh báo và thông báo khả năng kích hoạt quyền tạm dừng thi công theo hợp đồng.

### Bước 9: Quyết toán và Thanh lý hợp đồng
1. Sau khi hoàn thành lắp dựng toàn bộ hạng mục, căn chỉnh bu lông, dặm vá sơn và bàn giao hạng mục cho Tổng thầu:
   - Lập Hồ sơ quyết toán công trình (khối lượng thực tế thi công + khối lượng phát sinh được duyệt).
   - Thực hiện đối chiếu vật tư hao hụt (nếu Tổng thầu cấp thép) theo mẫu `68_Bien_Ban_Giao_Nhan_va_Quyet_Toan_Vat_Tu.md`.
2. Ký kết **Biên bản thanh lý hợp đồng** theo biểu mẫu `77_Bien_Ban_Thanh_Ly_Hop_Dong.md`.
3. Phòng Kế toán thu hồi toàn bộ công nợ còn lại (ngoại trừ tiền bảo hành giữ lại, thay thế bằng Thư bảo lãnh bảo hành ngân hàng nếu đối tác chấp thuận) và đóng mã dự án nội bộ.

---

## ĐIỀU 4. TRÁCH NHIỆM THI HÀNH VÀ BẢNG THAM SỐ ÁP DỤNG

### 4.1. Phân định trách nhiệm
1. **Phòng Kinh doanh - Đấu thầu:** Chịu trách nhiệm toàn diện từ khâu tìm kiếm khách hàng, lập dự toán, đàm phán, trình ký hợp đồng và phối hợp thu hồi công nợ đến khi thanh lý.
2. **Phòng Kỹ thuật:** Chịu trách nhiệm bóc tách khối lượng chính xác, lập biện pháp thi công, xác định phương án cẩu tối ưu và an toàn.
3. **Phòng Tài chính - Kế toán:** Chịu trách nhiệm kiểm soát dòng tiền dự án, thẩm định năng lực tài chính đối tác, phát hành bảo lãnh tạm ứng/thực hiện hợp đồng, xuất hóa đơn và đối chiếu công nợ.
4. **Ban Chỉ huy công trường:** Chịu trách nhiệm tổ chức thi công đúng phạm vi hợp đồng, ghi nhận kịp thời khối lượng phát sinh và ký biên bản nghiệm thu hiện trường.

### 4.2. Bảng tham số định mức và hạn mức kinh doanh
*(Các giá trị biến động được điều chỉnh định kỳ theo Quyết định ban hành Bảng tham số hiện hành của Giám đốc Công ty)*:
- Ngưỡng biên lợi nhuận gộp tối thiểu (Gross Margin Target): Theo Bảng tham số hiện hành (thông thường $\ge 12\% - 15\%$ đối với thầu nhân công + thiết bị; $\ge 8\% - 10\%$ đối với thầu trọn gói cung cấp kết cấu thép và lắp dựng).
- Tỷ lệ tạm ứng hợp đồng mục tiêu: Theo Bảng tham số hiện hành (khuyến nghị $\ge 15\% - 20\%$).
- Tỷ lệ phạt chậm thanh toán áp dụng đối với đối tác: Bằng lãi suất nợ quá hạn của ngân hàng thương mại tại thời điểm phát sinh hoặc theo quy định hợp đồng.

---

## ĐIỀU 5. CĂN CỨ PHÁP LÝ

1. Luật Dân sự số 91/2015/QH13 ngày 24/11/2015 và các văn bản hướng dẫn thi hành.
2. Luật Thương mại số 36/2005/QH11 ngày 14/06/2005.
3. Luật Xây dựng số 50/2014/QH13, Luật sửa đổi số 62/2020/QH14 và Luật Xây dựng sửa đổi bổ sung năm 2025 (Luật số 135/2025/QH15).
4. Nghị định số 37/2015/NĐ-CP và Nghị định số 50/2021/NĐ-CP của Chính phủ quy định chi tiết về hợp đồng xây dựng.
5. Nghị định số 207/2026/NĐ-CP của Chính phủ về quản lý chất lượng, thi công xây dựng và bảo trì công trình xây dựng (thay thế Nghị định 06/2021/NĐ-CP từ 01/07/2026).
6. Điều lệ tổ chức và hoạt động hiện hành của **<<CTY_TEN>>**.

---

| NGƯỜI LẬP QUY TRÌNH | TRƯỞNG PHÒNG KINH DOANH | ĐẠI DIỆN PHÁP LUẬT PHÊ DUYỆT |
| :---: | :---: | :---: |
| *(Ký, ghi rõ họ tên)* | *(Ký, ghi rõ họ tên)* | *(Ký, đóng dấu công ty)* |
| | | **<<NGUOI_DAI_DIEN_PHAP_LUAT>>** |
