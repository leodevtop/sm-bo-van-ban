# SỔ QUẢN LÝ LAO ĐỘNG
*(Sổ theo dõi nhân sự bản điện tử / văn bản theo Điều 12 Bộ luật Lao động 2019 và Nghị định 145/2020/NĐ-CP)*

**Mã văn bản:** 82/2026/SQLĐ-<<CTY_TEN_VT>>  
**Phiên bản:** 2.0 | **Ngày lập ban hành:** <<VB_NGAY>>/<<VB_THANG>>/<<VB_NAM>>  
**Đơn vị quản lý:** Phòng Hành chính – Nhân sự <<CTY_TEN>>  
**Người phê duyệt:** Giám đốc <<CTY_DAI_DIEN>>  

---

<div align="center">

**CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM**  
**Độc lập – Tự do – Hạnh phúc**  

---

## SỔ QUẢN LÝ LAO ĐỘNG
*(Áp dụng cho toàn bộ người lao động làm việc tại Công ty và các Công trường)*

**ĐƠN VỊ SỬ DỤNG LAO ĐỘNG:** <<CTY_TEN>>  
**Mã số doanh nghiệp / Mã số thuế:** <<CTY_MST>>  
**Địa chỉ trụ sở:** <<CTY_DC>> &emsp;&emsp; **Điện thoại:** <<CTY_DT>>  
**Đại diện pháp luật:** Ông/Bà **<<CTY_DAI_DIEN>>** &emsp;&emsp; **Chức vụ:** <<CTY_CHUC_DANH>>  

</div>

---

## PHẦN I. NGUYÊN TẮC VÀ QUY ĐỊNH QUẢN LÝ SỔ LAO ĐỘNG

1. **Căn cứ pháp lý bắt buộc:**  
   - Căn cứ Điều 12 Bộ luật Lao động số 45/2019/QH14 và Điều 3 Nghị định số 145/2020/NĐ-CP của Chính phủ, Người sử dụng lao động phải lập Sổ quản lý lao động bằng bản giấy hoặc bản điện tử và xuất trình khi cơ quan quản lý nhà nước về lao động yêu cầu.  
   - **Cảnh báo xử phạt (Nghị định 283/2026/NĐ-CP):** Hành vi không lập Sổ quản lý lao động hoặc lập sổ không đúng thời hạn, không ghi chép đầy đủ các nội dung theo quy định pháp luật sẽ bị xử phạt vi phạm hành chính từ 1.000.000 đồng đến 3.000.000 đồng đối với mức cơ bản ◐ (và có thể tăng nặng tùy số lượng lao động).
2. **Hình thức duy trì:**  
   - Sổ quản lý lao động của Công ty được lập và duy trì dưới dạng **Sổ điện tử** (cơ sở dữ liệu tập trung, có sao lưu định kỳ hàng ngày theo Quy chế C2) và đồng thời kết xuất in lưu trữ tại văn phòng Phòng Hành chính – Nhân sự.
3. **Trách nhiệm và thời hạn cập nhật:**  
   - Phòng Hành chính – Nhân sự chịu trách nhiệm trực tiếp cập nhật thông tin người lao động vào Sổ quản lý lao động trong thời hạn **không quá 30 ngày** kể từ ngày người lao động bắt buộc bắt đầu làm việc hoặc kể từ ngày phát sinh biến động nhân sự (tăng mới, chuyển công tác, điều chỉnh lương, chấm dứt hợp đồng lao động).  
   - Định kỳ 06 tháng một lần, Phòng HC-NS rà soát, đối chiếu dữ liệu với phần mềm quản lý bảo hiểm xã hội và báo cáo Giám đốc Công ty.
4. **Quản lý rủi ro số lần ký Hợp đồng lao động xác định thời hạn:**  
   - Cán bộ nhân sự phải theo dõi sát cột "Số lần ký HĐ xác định thời hạn". Nếu người lao động đã ký đủ 02 lần xác định thời hạn, hệ thống phần mềm phải tự động kích hoạt cảnh báo đỏ để ngăn chặn việc ký tiếp hợp đồng xác định thời hạn lần thứ 3 (trái Điều 20 BLLĐ 2019).

---

## PHẦN II. BẢNG DỮ LIỆU SỔ QUẢN LÝ LAO ĐỘNG (KHUNG CHUẨN)

| Cột | Tên trường thông tin | Quy ước / Mã dữ liệu tương ứng | Mục đích theo dõi / Lưu ý |
| :---: | :--- | :--- | :--- |
| **1** | **STT** | Số thứ tự tăng dần (01, 02, 03...) | Quản lý danh sách |
| **2** | **Mã nhân viên** | `<<NLD_MA>>` | Mã số định danh nội bộ duy nhất |
| **3** | **Họ và tên** | `<<NLD_HO_TEN>>` | Họ tên đầy đủ theo CCCD |
| **4** | **Giới tính** | `<<NLD_GIOI_TINH>>` | Nam / Nữ |
| **5** | **Ngày tháng năm sinh** | `<<NLD_NGAY_SINH>>` | Định dạng: DD/MM/YYYY |
| **6** | **Quốc tịch** | Việt Nam | Theo quy định pháp luật |
| **7** | **Số CCCD / Định danh** | `<<NLD_CCCD>>` | 12 số định danh cá nhân |
| **8** | **Ngày cấp & Nơi cấp CCCD** | `<<NLD_CCCD_NGAY>>` / `<<NLD_CCCD_NOI>>` | Đối chiếu bản sao chứng thực |
| **9** | **Địa chỉ thường trú** | `<<NLD_DC_THUONG_TRU>>` | Theo thông tin cư trú CCCD |
| **10** | **Chỗ ở hiện nay (tạm trú)** | `<<NLD_DC_TAM_TRU>>` | Để liên hệ khi công tác |
| **11** | **Số điện thoại liên hệ** | `<<NLD_DT>>` | Số điện thoại chính chủ |
| **12** | **Trình độ chuyên môn / Nghề** | `<<NLD_TRINH_DO>>` | Đại học/Cao đẳng/Trung cấp/Chứng chỉ thợ |
| **13** | **Số thẻ an toàn Nhóm 3** | `<<NLD_THE_AT_SO>>` (Hạn: `<<NLD_THE_AT_HAN>>`) | Bắt buộc đối với thợ trên cao/cẩu |
| **14** | **Chức danh công việc** | `<<NLD_CHUC_DANH>>` | Theo Thang bảng lương nội bộ |
| **15** | **Bộ phận / Công trình** | `<<NLD_BO_PHAN>>` / `<<CT_TEN>>` | Phòng ban hoặc tên dự án thi công |
| **16** | **Loại Hợp đồng lao động** | Không xác định thời hạn / Xác định thời hạn | Theo Điều 20 BLLĐ 2019 |
| **17** | **Số HĐLĐ & Ngày ký** | `<<HD_SO>>` - `<<HD_NGAY_KY>>` | Mã số hợp đồng lưu trữ |
| **18** | **Số lần ký HĐ xác định thời hạn** | **Lần 1** / **Lần 2** / **KXDTH** | **CỘT CẢNH BÁO PHÁP LÝ (Tránh ký lần 3)** |
| **19** | **Ngày bắt đầu làm việc** | `<<HD_NGAY_BD>>` | Căn cứ tính thâm niên, phép năm |
| **20** | **Ngày kết thúc HĐ (dự kiến)** | `<<HD_NGAY_KT>>` | Để nhắc hạn trước 45 ngày |
| **21** | **Mức lương chính (làm căn cứ BHXH)** | `<<HD_LUONG_CB>>` đồng | Theo hợp đồng lao động |
| **22** | **Mã số BHXH** | `<<NLD_MA_BHXH>>` | 10 số sổ BHXH |
| **23** | **Mã số thuế cá nhân** | `<<NLD_MST>>` | Phục vụ quyết toán thuế TNCN |
| **24** | **Số tài khoản ngân hàng nhận lương** | `<<NLD_STK>>` tại `<<NLD_NGAN_HANG>>` | Chuyển khoản lương chính chủ |
| **25** | **Người liên hệ khẩn cấp** | `<<NLD_LIEN_HE_KC_TEN>>` (`<<NLD_LIEN_HE_KC_DT>>`) | Xử lý khi có tai nạn, sự cố |
| **26** | **Ngày chấm dứt HĐLĐ** | DD/MM/YYYY | Khi nghỉ việc hoặc thanh lý HĐ |
| **27** | **Lý do chấm dứt HĐLĐ** | Hết hạn HĐ / Thỏa thuận / Đơn phương... | Theo Điều 34 BLLĐ 2019 |
| **28** | **Trạng thái lao động** | Đang làm việc / Nghỉ không lương / Đã thôi việc | Phân loại báo cáo |
| **29** | **Ghi chú** | Thợ nòng cốt, điều chuyển công trình... | Thông tin bổ sung |

---

## PHẦN III. BIỂU MẪU DÒNG DỮ LIỆU ĐIỂN HÌNH

```text
[KHUNG DÒNG THEO DÕI LAO ĐỘNG KHỐI VĂN PHÒNG]:
STT: …… | Mã NV: <<NLD_MA>> | Họ tên: <<NLD_HO_TEN>> | Giới tính: <<NLD_GIOI_TINH>> | Ngày sinh: <<NLD_NGAY_SINH>>
CCCD: <<NLD_CCCD>> | Ngày cấp: <<NLD_CCCD_NGAY>> | Nơi cấp: <<NLD_CCCD_NOI>>
Thường trú: <<NLD_DC_THUONG_TRU>> | Điện thoại: <<NLD_DT>> | Trình độ: <<NLD_TRINH_DO>>
Chức danh: <<NLD_CHUC_DANH>> | Bộ phận: <<NLD_BO_PHAN>>
Loại HĐ: Không xác định thời hạn | Số HĐ: <<HD_SO>> | Ngày ký: <<HD_NGAY_KY>>
Số lần ký: Không áp dụng (KXDTH) | Ngày vào làm: <<HD_NGAY_BD>> | Ngày kết thúc: Không xác định
Lương căn cứ BHXH: <<HD_LUONG_CB>> đồng | Mã BHXH: <<NLD_MA_BHXH>> | MST: <<NLD_MST>>
Số TK: <<NLD_STK>> tại <<NLD_NGAN_HANG>> | Trạng thái: Đang làm việc

[KHUNG DÒNG THEO DÕI THỢ NÒNG CỐT / THỜI VỤ CÔNG TRƯỜNG]:
STT: …… | Mã NV: <<NLD_MA>> | Họ tên: <<NLD_HO_TEN>> | Giới tính: <<NLD_GIOI_TINH>> | Ngày sinh: <<NLD_NGAY_SINH>>
CCCD: <<NLD_CCCD>> | Ngày cấp: <<NLD_CCCD_NGAY>> | Nơi cấp: <<NLD_CCCD_NOI>>
Thường trú: <<NLD_DC_THUONG_TRU>> | Điện thoại: <<NLD_DT>> | Trình độ: <<NLD_TRINH_DO>>
Số thẻ AT Nhóm 3: <<NLD_THE_AT_SO>> (Hạn đến: <<NLD_THE_AT_HAN>>)
Chức danh: <<NLD_CHUC_DANH>> | Bộ phận: <<NLD_BO_PHAN>> - Dự án: <<CT_TEN>>
Loại HĐ: Xác định thời hạn | Số HĐ: <<HD_SO>> | Ngày ký: <<HD_NGAY_KY>>
Số lần ký: <<HD_LAN_KY>> (Cảnh báo: Tối đa 2 lần ký xác định thời hạn; sau 2 lần bắt buộc chuyển KXDTH)
Ngày vào làm: <<HD_NGAY_BD>> | Ngày kết thúc: <<HD_NGAY_KT>> | Lương căn cứ BHXH: <<HD_LUONG_CB>> đồng
Mã BHXH: <<NLD_MA_BHXH>> | MST: <<NLD_MST>> | Số TK: <<NLD_STK>> tại <<NLD_NGAN_HANG>>
Người liên hệ KC: <<NLD_LIEN_HE_KC_TEN>> (<<NLD_LIEN_HE_KC_DT>>) | Trạng thái: Đang làm việc
```

---

## PHẦN IV. BẢO MẬT THÔNG TIN VÀ KHAI THÁC DỮ LIỆU

1. Sổ quản lý lao động chứa các thông tin cá nhân cơ bản và nhạy cảm của người lao động. Việc truy cập, chỉnh sửa cơ sở dữ liệu Sổ quản lý lao động chỉ được phân quyền cho:  
   - Giám đốc Công ty (quyền xem và phê duyệt toàn bộ);  
   - Trưởng phòng Hành chính – Nhân sự (quyền quản trị, cập nhật và trích xuất);  
   - Nhân viên phụ trách nhân sự & BHXH (quyền cập nhật theo phân công).  
2. Nghiêm cấm mọi hành vi sao chép, phát tán hoặc sử dụng dữ liệu trong Sổ quản lý lao động vào mục đích khác ngoài phạm vi quản lý nội bộ và báo cáo cơ quan nhà nước theo quy định tại Luật Bảo vệ dữ liệu cá nhân 2025.

---

<br>

| **NGƯỜI LẬP SỔ (CÁN BỘ HC-NS)**<br>*(Ký, ghi rõ họ tên)* | | **TRƯỞNG PHÒNG HÀNH CHÍNH – NHÂN SỰ**<br>*(Ký, ghi rõ họ tên)* | | **<<CTY_TEN>>**<br>**GIÁM ĐỐC DUYỆT**<br>*(Ký tên, đóng dấu và ghi rõ họ tên)* |
| :---: | :---: | :---: | :---: | :---: |
| <br><br><br><br>……………………………… | | <br><br><br><br> **<<CTY_NGUOI_DL>>** | | <br><br><br><br> **<<CTY_DAI_DIEN>>** |

---

## PHỤ LỤC: CĂN CỨ PHÁP LÝ & GHI CHÚ

1. **Bộ luật Lao động số 45/2019/QH14:**
   - Điều 12: Trách nhiệm lập, quản lý và sử dụng sổ quản lý lao động bằng bản giấy hoặc bản điện tử; xuất trình sổ quản lý lao động khi cơ quan nhà nước có thẩm quyền yêu cầu;
   - Điều 20: Giới hạn số lần ký hợp đồng lao động xác định thời hạn (tối đa 2 lần).
2. **Nghị định số 145/2020/NĐ-CP:**
   - Điều 3: Quy định chi tiết nội dung lập và quản lý sổ quản lý lao động của người sử dụng lao động trong thời hạn 30 ngày kể từ ngày bắt đầu hoạt động.
3. **Nghị định số 283/2026/NĐ-CP (hiệu lực từ 10/09/2026):**
   - Xử phạt vi phạm hành chính đối với hành vi không lập sổ quản lý lao động hoặc không ghi đầy đủ các nội dung theo quy định.
4. **Luật Việc làm số 74/2025/QH15 và Nghị định số 318/2025/NĐ-CP (hiệu lực từ 01/01/2026):**
   - Đồng bộ dữ liệu thông tin thị trường lao động và đăng ký lao động quốc gia.
5. **◐ Điểm cần lưu ý/xác nhận:** Cán bộ kế toán và nhân sự cần xác nhận với cơ quan bảo hiểm địa phương về phương thức kết xuất báo cáo sử dụng lao động định kỳ từ sổ quản lý lao động trên Cổng Dịch vụ công Quốc gia.
