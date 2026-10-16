> **BẢN THIẾT KẾ KIẾN TRÚC & CĂN CỨ LẬP LUẬN (CORE ARCHITECTURE & DESIGN RATIONALE)**
> - **Mục đích:** Tài liệu thiết kế nguồn, giải thích nguyên lý "vì sao như vậy" và căn cứ lập luận để xây dựng, đối chiếu và tái lập hệ thống văn bản vận hành của Công ty.
> - **Văn bản thực thi tương ứng trong Danh mục lưu hành:**
>   - STT 71: Quy trình kinh doanh, báo giá & quản lý hợp đồng
>   - STT 72: Mẫu báo giá (Dạng 1 và 2)
>   - STT 73: Hợp đồng thi công trực tiếp với chủ xưởng – chỉ thi công (hoãn)
>   - STT 74: Phụ lục vật tư – điều khoản bổ sung (hợp đồng thầu phụ gồm vật tư)
>   - STT 75: Đơn đặt hàng mua vật tư (Dạng 2)
>   - STT 76: Checklist thẩm định rủi ro HĐ & điều kiện huy động
>   - STT 77: Biên bản thanh lý hợp đồng
>   - STT 81: Hợp đồng dịch vụ (cá nhân bên ngoài)
>   - STT 84: Biên bản đối chiếu vật tư sau gia công (áp dụng HĐ gia công ngoài)

# D2 – QUY TRÌNH KINH DOANH VÀ HỢP ĐỒNG

|                            |                                                                           |
| -------------------------- | ------------------------------------------------------------------------- |
| **Đơn vị ban hành**        | {{TEN_CONG_TY}}                                                           |
| **Mã văn bản / Phiên bản** | D2 / 2.0                                                                  |
| **Ngày ban hành**          | {{NGAY_BAN_HANH}}                                                         |
| **Người ký ban hành**      | Giám đốc {{GIAM_DOC}}                                                     |
| **Rà soát kế tiếp**        | 6 tháng kể từ ngày ban hành, hoặc khi có văn bản mới về hợp đồng xây dựng |

## 0. Phạm vi và nguyên tắc

Quy trình đi từ báo giá đến thanh toán. Hợp đồng xây dựng tuân thủ quy định hiện hành về hợp đồng xây dựng (kiểm tra văn bản hướng dẫn sau Luật Xây dựng 2025). Nếu chủ đầu tư hoặc tổng thầu cung cấp **mẫu hợp đồng**, Công ty ưu tiên dùng mẫu đó và bổ sung điều khoản tại B4; nếu không, dùng mẫu hợp đồng của Bộ Xây dựng (bản hiện hành) kèm các điều khoản tại mục 4 và mục 5.

```
Yêu cầu báo giá → Khảo sát hồ sơ → Dự toán → Phê duyệt giá → Gửi báo giá → Thương thảo
→ Rà soát hợp đồng (B4, mục 6 của văn bản này) → Ký → Chuyển giao Dự án, Thi công → Theo dõi → Nghiệm thu, thanh toán, công nợ
```

## 1. Xác định dạng hợp đồng

|                       | **Dạng 1 – Chỉ thi công**                             | **Dạng 2 – Gồm vật tư**                                               |
| --------------------- | ----------------------------------------------------- | --------------------------------------------------------------------- |
| Giá                   | Nhân công + máy + chi phí chung + lợi nhuận           | Vật tư + nhân công + máy + vận chuyển + chi phí chung + lợi nhuận     |
| Rủi ro                | Vật tư bên giao thầu giao sai, chậm; chờ mặt bằng     | **Biến động giá thép**, chất lượng vật tư, nhà cung cấp chậm, công nợ |
| Thanh toán thường gặp | Theo khối lượng, giai đoạn                            | Tạm ứng vật tư + theo giai đoạn                                       |
| Điều khoản trọng yếu  | Vật tư bên giao thầu, mặt bằng, an toàn, chậm tiến độ | **Điều chỉnh giá vật tư**, bảo hành vật tư, hồ sơ chất lượng          |

## 2. Tiếp nhận cơ hội và sàng lọc

1. Ghi **Sổ cơ hội**: ngày – khách hàng hoặc tổng thầu – công trình – giá trị – nguồn – người phụ trách – trạng thái.
2. Sàng lọc: năng lực, uy tín thanh toán của khách, vị trí, tiến độ, **yêu cầu HSE đặc biệt** của tổng thầu (người quản lý an toàn đánh giá chi phí); quyết định tham gia hoặc không.

## 3. Dự toán và báo giá

1. Dự toán **tách riêng**: nhân công; máy, thiết bị (cẩu, xe nâng); vật tư; vận chuyển; ăn ở, đi lại; **an toàn (PPE, huấn luyện, giàn giáo, bảo hiểm)**; bảo hành; dự phòng; lợi nhuận.
2. **Chi phí an toàn và bảo hiểm phải có trong giá**; Công ty không ký báo giá thiếu các khoản này.
3. Dạng 2: báo giá thép có **thời hạn hiệu lực**; ghi rõ điều kiện điều chỉnh khi giá biến động.
4. Giám đốc duyệt giá theo ngưỡng thẩm quyền (C1 mục 3); lưu bản phê duyệt.
5. Báo giá ghi rõ **thời hạn hiệu lực, giả định, loại trừ** (mặt bằng, điện nước, thay đổi thiết kế, biến động giá thép, lương tối thiểu).
6. **Thuê xưởng gia công cấu kiện ngoài (khi dự án có gia công cơ khí/kết cấu thép):**
   - **Lựa chọn xưởng gia công:** Đánh giá thực tế mặt bằng, hệ thống máy móc (cắt CNC/plasma, máy hàn, uốn, nắn, cẩu trục), quy trình KCS nội bộ của xưởng, chứng chỉ thợ hàn và năng lực thực hiện đúng tiến độ. Lấy tối thiểu 02–03 báo giá gia công cạnh tranh theo Bảng tham số (C1).
   - **Cơ cấu giá gia công trong dự toán:** Tách bạch đơn giá gia công chế tạo (tính theo kg hoặc tấn cho từng cấu kiện như kèo, cột, xà gồ, giằng, bản mã...) và chi phí vận chuyển trung chuyển (kho/đại lý thép $\rightarrow$ xưởng gia công $\rightarrow$ công trường); dự toán phải tính toán định mức hao hụt kỹ thuật hợp lý (thường 1,5% – 3% tùy loại phôi tấm hay thép hình).

**Bảng dự toán tóm tắt:** nhân công – bảo hiểm (BHXH, bảo hiểm công trường) – **vật tư (Dạng 2)** – **dịch vụ gia công ngoài (nếu có)** – thiết bị (cẩu, xe nâng) – vận chuyển – chi phí an toàn (PPE, huấn luyện, rào chắn, kiểm định) – ăn ở, đi lại – chi phí chung, rủi ro – lợi nhuận – tổng.

## 4. Mẫu 1 – Điều khoản chính của hợp đồng chỉ thi công (Dạng 1)

| Điều khoản                   | Nội dung cần có                                                                                                             |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Phạm vi                      | Hạng mục, khối lượng, bản vẽ, tiêu chuẩn                                                                                    |
| **Vật tư bên giao thầu cấp** | Danh mục, tiến độ giao, địa điểm, **giao nhận có biên bản (D1-01)**, hao hụt cho phép, bên giao thầu chịu khuyết tật có sẵn |
| Mặt bằng                     | Bàn giao đúng hạn, lối đi, điện, nước, kho bãi                                                                              |
| Đơn giá, thanh toán          | Theo khối lượng, giai đoạn; tạm ứng; thời hạn thanh toán sau nghiệm thu                                                     |
| Tiến độ                      | Các mốc; **gia hạn khi bên giao thầu chậm vật tư, mặt bằng hoặc do thời tiết**                                              |
| An toàn, bảo hiểm            | Theo B4                                                                                                                     |
| Nghiệm thu, bảo hành         | Quy trình, thời hạn, tỷ lệ giữ lại                                                                                          |
| Chấm dứt, phạt               | Mức phạt cân bằng hai phía; có mức trần                                                                                     |
| Giải quyết tranh chấp        | Thương lượng; sau đó trọng tài hoặc tòa án                                                                                  |

## 5. Mẫu 2 – Điều khoản bổ sung cho hợp đồng gồm vật tư (Dạng 2) và Hợp đồng gia công ngoài

### 5A. Điều khoản cho hợp đồng gồm vật tư (Dạng 2)

| Điều khoản                    | Nội dung cần có                                                                                               |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Danh mục và tiêu chuẩn vật tư | Mác thép, cấp bền bu lông, tiêu chuẩn, nhà cung cấp được chấp thuận                                           |
| **Hồ sơ chất lượng vật tư**   | Công ty (bên cung cấp) nộp CO, CQ, kết quả thử nghiệm khi được yêu cầu                                        |
| **Điều chỉnh giá vật tư**     | Công thức hoặc chỉ số tham chiếu, ngưỡng biến động, thời điểm áp dụng; hoặc giá cố định đến một ngày xác định |
| Tiến độ cung ứng              | Ngày giao, địa điểm, bên nhận; **chậm giao do nhà cung cấp**                                                  |
| Chuyển quyền sở hữu, rủi ro   | Khi nào chuyển (khi giao hay khi thanh toán) và ai chịu rủi ro trong kho                                      |
| Bảo hành vật tư               | Thời hạn, điều kiện; **mối quan hệ với bảo hành của nhà cung cấp**                                            |
| Tạm ứng vật tư                | Mức, bảo lãnh tạm ứng (nếu có), điều kiện hoàn ứng                                                            |
| Thuế, hóa đơn                 | Giá có hay không có VAT; thời điểm xuất hóa đơn vật tư và thi công (D3)                                       |

### 5B. Điều khoản bắt buộc trong Hợp đồng dịch vụ gia công ngoài (thuê xưởng chế tạo)

Khi ký hợp đồng thuê đối tác/xưởng gia công cơ khí, chế tạo kết cấu thép, Hợp đồng dịch vụ gia công bắt buộc phải bao gồm các điều khoản ràng buộc sau:

| Điều khoản bắt buộc | Nội dung cụ thể cần xác lập |
| ------------------- | --------------------------- |
| **Cam kết tiêu chuẩn và dung sai kỹ thuật** | Gia công chính xác theo bản vẽ shop-drawing được duyệt; tuân thủ nghiêm ngặt tiêu chuẩn TCVN kết cấu thép về kích thước hình học, độ phẳng, độ thẳng, sai lệch khoảng cách lỗ bu lông liên kết, chất lượng mối hàn (NDT khi có yêu cầu) và chiều dày sơn bảo vệ. |
| **Tỷ lệ hao hụt tối đa cho phép** | Quy định rõ tỷ lệ hao hụt kỹ thuật tối đa (ví dụ không quá 2,0% – 3,0% đối với thép tấm/thép hình tùy quy cách); mọi phần hao hụt vượt tỷ lệ thỏa thuận này do xưởng gia công tự chịu chi phí. |
| **Trách nhiệm bồi thường khi làm hỏng phôi thép** | Vật tư/phôi thép bàn giao thuộc sở hữu của Công ty. Nếu xưởng gia công làm sai quy cách, cháy hỏng mép cắt, biến dạng nhiệt không khắc phục được hoặc làm hỏng phôi thép, xưởng phải bồi thường 100% giá trị phôi thép hư hỏng theo giá thị trường tại thời điểm phát sinh hoặc hoàn trả lại phôi thép mới đúng mác thép và quy cách. |
| **Nghiệm thu tại xưởng trước khi xuất kho** | Toàn bộ cấu kiện phải được kỹ sư QC/đại diện Công ty kiểm tra, nghiệm thu đạt chất lượng tại xưởng gia công và ký Biên bản nghiệm thu kỹ thuật thành phẩm (D1-09) mới được phép xuất kho. Xưởng không được tự ý vận chuyển cấu kiện ra công trường khi chưa có biên bản nghiệm thu xuất xưởng. |
| **Đối chiếu vật tư và xử lý phế liệu** | Kết thúc đợt gia công, hai bên bắt buộc lập Biên bản đối chiếu và quyết toán vật tư (D1-10) và Biên bản xử lý phế liệu (D1-11). Thép thừa nguyên thanh/tấm được thu hồi về kho Công ty; phế liệu đầu mẩu/ba-via được cân thực tế và cấn trừ tiền gia công theo đơn giá thỏa thuận. |
| **Bản chất dịch vụ và hóa đơn tài chính** | Xác lập rõ quan hệ là Hợp đồng dịch vụ gia công (không phải mua bán thương mại thép). Xưởng xuất Hóa đơn GTGT dịch vụ gia công, tuyệt đối không xuất hóa đơn bán hàng hóa vật tư đối với lượng phôi do Công ty cấp (khớp quy định D3). |

## 6. Rà soát trước khi ký (checklist)

| #   | Nội dung                                                          | Đạt |
| --- | ----------------------------------------------------------------- | --- |
| 1   | Phạm vi và ranh giới khớp với báo giá                             | ☐   |
| 2   | Có điều khoản **vật tư** phù hợp Dạng 1 hoặc Dạng 2               | ☐   |
| 3   | Điều khoản **an toàn – bảo hiểm** (B4 mục 2, 3, 5)                | ☐   |
| 4   | Điều kiện thanh toán, tạm ứng, thời hạn, **giữ lại bảo hành**     | ☐   |
| 5   | Gia hạn khi chậm mặt bằng, vật tư, thời tiết                      | ☐   |
| 6   | Mức phạt, mức trần phạt, bồi thường hợp lý                        | ☐   |
| 7   | Quyền dừng việc khi mất an toàn                                   | ☐   |
| 8   | Nghiệm thu, hồ sơ hoàn công, bảo hành rõ ràng                     | ☐   |
| 9   | Luật sư xem điều khoản rủi ro cao (giá trị lớn, phạt cao, vật tư) | ☐   |
| 10  | Giám đốc phê duyệt ký (C1)                                        | ☐   |
| 11  | HĐ gia công ngoài: đủ dung sai kỹ thuật, trần hao hụt, bồi thường hỏng phôi, KCS tại xưởng | ☐   |

## 7. Điều kiện huy động

Công ty chỉ **huy động công nhân và vật tư** khi: hợp đồng đã ký; **bảo hiểm đã được xác nhận** (B4); danh sách nhân sự được tổng thầu chấp nhận; tạm ứng hoặc thanh toán đợt đầu theo hợp đồng. Sau khi ký: tạo **mã công trình**, mở hồ sơ B2, thông báo Dự án, Kế toán, Hành chính – Nhân sự.

## 8. Theo dõi hợp đồng

1. Mỗi hợp đồng có **hồ sơ** gồm hợp đồng, phụ lục, báo giá, biên bản, chứng từ thanh toán.
2. Sổ theo dõi: mốc tiến độ, mốc thanh toán, hạn bảo lãnh và bảo hành, **ngày hết hạn bảo hiểm**.
3. Phát sinh, điều chỉnh: lập **văn bản** trước khi làm (D1 mục 3).
4. Công nợ: Kế toán theo dõi; Kinh doanh nhắc khách (D3).

## 9. Công nợ và thanh lý

**Sổ công nợ phải thu:** khách hàng – hợp đồng – đợt thanh toán – giá trị – hạn – đã thu – còn nợ – quá hạn (ngày) – hành động.

| Mức quá hạn          | Hành động                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------ |
| Trước hạn 5 ngày     | Nhắc nhẹ                                                                                               |
| Quá hạn 1–15 ngày    | Gửi email chính thức                                                                                   |
| Quá hạn 16–45 ngày   | Giám đốc làm việc trực tiếp; cân nhắc tạm hoãn huy động người mới (nếu hợp đồng cho phép)              |
| Quá hạn trên 45 ngày | Hỏi ý kiến luật sư về quyền dừng thi công; việc dừng phải có căn cứ hợp đồng và thông báo bằng văn bản |

Thanh lý hợp đồng khi hoàn thành nghĩa vụ; lập biên bản thanh lý; đánh giá khách hàng (thanh toán, phối hợp, an toàn) để dùng cho lần sau.

## 10. Biểu mẫu chính thức của Nhà nước áp dụng cùng văn bản này

| Việc                        | Biểu mẫu                                                                      |
| --------------------------- | ----------------------------------------------------------------------------- |
| Hợp đồng xây dựng, thầu phụ | Mẫu của Bộ Xây dựng hoặc của tổng thầu (bản hiện hành sau Luật Xây dựng 2025) |

## 11. Căn cứ

Luật Xây dựng 2025; Bộ luật Dân sự; Luật Thương mại; quy định hiện hành về hợp đồng xây dựng; Nghị định 207/2026/NĐ-CP. Xem `00-can-cu-phap-ly.md`.
