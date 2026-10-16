> [!IMPORTANT]
> **TÀI LIỆU HƯỚNG DẪN KỸ THUẬT NỘI BỘ (LAYER 0)**
> - File này là công cụ tra cứu tham số nguồn và hướng dẫn nghiệp vụ dành riêng cho người quản trị / soạn thảo văn bản nội bộ.
> - **Không có giá trị pháp lý độc lập ra bên ngoài và không dùng để viện dẫn trực tiếp trong các văn bản giao dịch.**
> - Mọi quyền, nghĩa vụ và chế độ pháp lý chính thức đối với bên thứ ba, cơ quan Nhà nước và người lao động được xác lập độc lập tại 74 văn bản chính thức quy định tại 00_Danh_Sach_Van_Ban.md.

# DANH MỤC MÃ DỮ LIỆU `<<MA_DATA>>`

**Quy ước:** mọi chỗ trống trong văn bản dùng dạng `<<MA_DATA>>` (hai dấu nhỏ hơn, mã viết hoa, gạch dưới), ví dụ `<<CTY_TEN>>`, `<<CTY_DC>>`, `<<NLD_HO_TEN>>`. Tiền tố cho biết loại dữ liệu. Các ô để người dùng điền tay khi vận hành (dòng kẻ, bảng trống) không dùng mã.

**Bản đang dùng trong 🟢:** các file cũ ghi `<CTY>`, `<NGAY_THANG_NAM>`, và tên "SAMIN" ghi cứng; khi sửa sẽ đổi hết sang bảng mã này.

## CTY\_ – Công ty (điền một lần)

| Mã                       | Ý nghĩa                                   | Ví dụ, ghi chú  |
| ------------------------ | ----------------------------------------- | --------------- |
| `<<CTY_TEN>>`            | Tên đầy đủ theo giấy đăng ký doanh nghiệp | CÔNG TY TNHH …  |
| `<<CTY_TEN_VT>>`         | Tên viết tắt dùng trong số văn bản        | SM              |
| `<<CTY_DC>>`             | Địa chỉ trụ sở                            |                 |
| `<<CTY_MST>>`            | Mã số thuế                                |                 |
| `<<CTY_DT>>`             | Điện thoại                                |                 |
| `<<CTY_EMAIL>>`          | Email                                     |                 |
| `<<CTY_STK>>`            | Số tài khoản                              |                 |
| `<<CTY_NGAN_HANG>>`      | Ngân hàng                                 |                 |
| `<<CTY_DAI_DIEN>>`       | Họ tên người đại diện theo pháp luật      |                 |
| `<<CTY_CHUC_DANH>>`      | Chức danh người ký                        | Giám đốc        |
| `<<CTY_DIA_DANH>>`       | Địa danh ghi trên văn bản                 | TP. Hồ Chí Minh |
| `<<CTY_NGUOI_AT>>`       | Người phụ trách quản lý an toàn           |                 |
| `<<CTY_NGUOI_DL>>`       | Người phụ trách bảo vệ dữ liệu cá nhân    |                 |
| `<<CTY_KE_TOAN_TRUONG>>` | Kế toán trưởng                            |                 |
| `<<CTY_CD_TEN>>`         | Tên công đoàn cơ sở                       |                 |
| `<<CTY_CD_CHU_TICH>>`    | Chủ tịch công đoàn cơ sở                  |                 |

## VB\_ – Văn bản

| Mã                | Ý nghĩa         | Ví dụ, ghi chú |
| ----------------- | --------------- | -------------- |
| `<<VB_SO>>`       | Số văn bản      | 01/2026/QĐ-SM  |
| `<<VB_NGAY>>`     | Ngày (số)       |                |
| `<<VB_THANG>>`    | Tháng (số)      |                |
| `<<VB_NAM>>`      | Năm             | 2026           |
| `<<VB_NGUOI_KY>>` | Họ tên người ký |                |

## NLD\_ – Người lao động

| Mã                       | Ý nghĩa                           | Ví dụ, ghi chú |
| ------------------------ | --------------------------------- | -------------- |
| `<<NLD_MA>>`             | Mã nhân viên                      |                |
| `<<NLD_HO_TEN>>`         | Họ và tên                         |                |
| `<<NLD_GIOI_TINH>>`      | Giới tính                         |                |
| `<<NLD_NGAY_SINH>>`      | Ngày sinh                         |                |
| `<<NLD_CCCD>>`           | Số CCCD                           |                |
| `<<NLD_CCCD_NGAY>>`      | Ngày cấp CCCD                     |                |
| `<<NLD_CCCD_NOI>>`       | Nơi cấp CCCD                      |                |
| `<<NLD_DC_THUONG_TRU>>`  | Địa chỉ thường trú                |                |
| `<<NLD_DC_TAM_TRU>>`     | Chỗ ở hiện nay                    |                |
| `<<NLD_DT>>`             | Điện thoại                        |                |
| `<<NLD_MA_BHXH>>`        | Mã số BHXH                        |                |
| `<<NLD_MST>>`            | Mã số thuế cá nhân                |                |
| `<<NLD_STK>>`            | Số tài khoản nhận lương           |                |
| `<<NLD_NGAN_HANG>>`      | Ngân hàng                         |                |
| `<<NLD_TRINH_DO>>`       | Trình độ chuyên môn, nghề         |                |
| `<<NLD_CHUC_DANH>>`      | Chức danh                         |                |
| `<<NLD_BO_PHAN>>`        | Bộ phận, tổ đội                   |                |
| `<<NLD_NGAY_VAO_LAM>>`   | Ngày vào làm                      |                |
| `<<NLD_LIEN_HE_KC_TEN>>` | Người liên hệ khẩn cấp            |                |
| `<<NLD_LIEN_HE_KC_DT>>`  | Điện thoại người liên hệ khẩn cấp |                |
| `<<NLD_THE_AT_SO>>`      | Số thẻ an toàn                    |                |
| `<<NLD_THE_AT_HAN>>`     | Hạn thẻ an toàn                   |                |
| `<<NLD_KSK_HAN>>`        | Hạn giấy khám sức khỏe            |                |

## HD\_ – Hợp đồng lao động

| Mã                      | Ý nghĩa                                      | Ví dụ, ghi chú   |
| ----------------------- | -------------------------------------------- | ---------------- |
| `<<HD_SO>>`             | Số hợp đồng                                  | 001/2026/HĐLĐ-SM |
| `<<HD_NGAY_KY>>`        | Ngày ký                                      |                  |
| `<<HD_LAN_KY>>`         | Lần ký hợp đồng xác định thời hạn (1 hoặc 2) |                  |
| `<<HD_NGAY_BD>>`        | Ngày bắt đầu                                 |                  |
| `<<HD_NGAY_KT>>`        | Ngày kết thúc (cố định)                      |                  |
| `<<HD_THU_VIEC_NGAY>>`  | Số ngày thử việc                             |                  |
| `<<HD_LUONG_THU_VIEC>>` | Lương thử việc                               |                  |
| `<<HD_LUONG_CB>>`       | Lương cơ bản (số)                            |                  |
| `<<HD_LUONG_CB_CHU>>`   | Lương cơ bản (chữ)                           |                  |
| `<<HD_DON_GIA_CONG>>`   | Đơn giá ngày công                            |                  |
| `<<HD_PHU_CAP>>`        | Phụ cấp                                      |                  |
| `<<HD_KY_TRA_LUONG>>`   | Kỳ trả lương                                 |                  |
| `<<HD_NGAY_TRA_LUONG>>` | Ngày trả lương                               |                  |
| `<<HD_DIA_DIEM_LV>>`    | Địa điểm làm việc                            |                  |
| `<<HD_PHU_LUC_SO>>`     | Số phụ lục                                   |                  |

## CT\_ – Công trình

| Mã                       | Ý nghĩa                 | Ví dụ, ghi chú |
| ------------------------ | ----------------------- | -------------- |
| `<<CT_MA>>`              | Mã công trình           |                |
| `<<CT_TEN>>`             | Tên công trình          |                |
| `<<CT_DIA_DIEM>>`        | Địa điểm                |                |
| `<<CT_TINH>>`            | Tỉnh, thành phố         |                |
| `<<CT_CHI_HUY_TRUONG>>`  | Chỉ huy trưởng          |                |
| `<<CT_AT_VIEN>>`         | An toàn viên            |                |
| `<<CT_NGAY_KHOI_CONG>>`  | Ngày khởi công          |                |
| `<<CT_NGAY_HOAN_THANH>>` | Ngày hoàn thành dự kiến |                |
| `<<CT_BENH_VIEN>>`       | Bệnh viện gần nhất      |                |
| `<<CT_BENH_VIEN_DT>>`    | Điện thoại bệnh viện    |                |

## KH\_ – Tổng thầu, chủ đầu tư, khách hàng

| Mã                 | Ý nghĩa        | Ví dụ, ghi chú |
| ------------------ | -------------- | -------------- |
| `<<KH_TEN>>`       | Tên đơn vị     |                |
| `<<KH_DC>>`        | Địa chỉ        |                |
| `<<KH_MST>>`       | Mã số thuế     |                |
| `<<KH_DAI_DIEN>>`  | Người đại diện |                |
| `<<KH_CHUC_DANH>>` | Chức danh      |                |
| `<<KH_HD_SO>>`     | Số hợp đồng    |                |
| `<<KH_HD_NGAY>>`   | Ngày hợp đồng  |                |

## NCC\_ – Nhà cung cấp, thầu phụ, đối tác dịch vụ

| Mã                 | Ý nghĩa                 | Ví dụ, ghi chú |
| ------------------ | ----------------------- | -------------- |
| `<<NCC_TEN>>`      | Tên đơn vị hoặc cá nhân |                |
| `<<NCC_DC>>`       | Địa chỉ                 |                |
| `<<NCC_MST>>`      | Mã số thuế hoặc CCCD    |                |
| `<<NCC_DAI_DIEN>>` | Người đại diện          |                |
| `<<NCC_STK>>`      | Số tài khoản            |                |

## XUONG_GC_ / GC_ – Đơn vị gia công ngoài và Hợp đồng gia công

| Mã                           | Ý nghĩa                                    | Ví dụ, ghi chú |
| ---------------------------- | ------------------------------------------ | -------------- |
| `<<XUONG_GC_TEN>>`           | Tên xưởng / đơn vị nhận gia công kết cấu   |                |
| `<<XUONG_GC_MST>>`           | Mã số thuế đơn vị gia công                 |                |
| `<<XUONG_GC_DAI_DIEN>>`      | Người đại diện theo pháp luật / Quản đốc   |                |
| `<<XUONG_GC_DIA_CHI_XUONG>>` | Địa chỉ nhà xưởng gia công                 |                |
| `<<GC_HD_SO>>`               | Số hợp đồng dịch vụ gia công               |                |
| `<<GC_HD_NGAY>>`             | Ngày ký hợp đồng dịch vụ gia công          |                |

## TN\_ – Tai nạn, sự cố (dùng cho phiếu ghi nhanh và quyết định bồi thường)

| Mã                | Ý nghĩa                                              | Ví dụ, ghi chú |
| ----------------- | ---------------------------------------------------- | -------------- |
| `<<TN_NGAY_GIO>>` | Ngày, giờ xảy ra                                     |                |
| `<<TN_DIA_DIEM>>` | Địa điểm xảy ra                                      |                |
| `<<TN_LOAI>>`     | Phân loại: nhẹ, nặng, chết người, sự cố, suýt xảy ra |                |
| `<<TN_MO_TA>>`    | Mô tả diễn biến                                      |                |

## TS\_ – Tham số (con số hay thay đổi hoặc do Giám đốc quyết định)

| Mã                           | Ý nghĩa                                    | Ví dụ, ghi chú                               |
| ---------------------------- | ------------------------------------------ | -------------------------------------------- |
| `<<TS_LUONG_TOI_THIEU_V1>>`  | Lương tối thiểu tháng vùng I               | 5.310.000 đồng (Nghị định 293/2025)          |
| `<<TS_NGUONG_CHUYEN_KHOAN>>` | Ngưỡng bắt buộc chuyển khoản lương mỗi đợt | 5.000.000 đồng (nguồn thứ cấp, cần xác nhận) |
| `<<TS_TL_BHXH_NLD>>`         | Tỷ lệ BHXH người lao động đóng             | Theo Bảng tham số                            |
| `<<TS_TL_BHYT_NLD>>`         | Tỷ lệ BHYT người lao động đóng             | Theo Bảng tham số                            |
| `<<TS_TL_BHTN_NLD>>`         | Tỷ lệ BHTN người lao động đóng             | Theo Bảng tham số                            |
| `<<TS_PHU_CAP_CONG_TRUONG>>` | Phụ cấp công trường (đồng/ngày)            | Giám đốc quyết định                          |
| `<<TS_CONG_TAC_PHI>>`        | Công tác phí (đồng/ngày)                   | Giám đốc quyết định                          |
| `<<TS_THUONG_AT>>`           | Thưởng an toàn theo kỳ                     | Giám đốc quyết định                          |
| `<<TS_KPI_TL_LNG>>`          | Tỷ lệ quỹ KPI trên lợi nhuận gộp           | Theo Quy chế KPI hiện hành (20%)             |
| `<<TS_KPI_TRAN>>`            | Trần quỹ KPI trên giá trị hợp đồng         | Theo Quy chế KPI hiện hành (5%)              |
| `<<TS_NGUONG_BAO_GIA>>`      | Ngưỡng Giám đốc duyệt báo giá              | Giám đốc quyết định                          |
| `<<TS_NGUONG_HD_NCC>>`       | Ngưỡng Giám đốc ký hợp đồng nhà cung cấp   | Giám đốc quyết định                          |
| `<<TS_NGUONG_CHI_TP>>`       | Ngưỡng chi Trưởng phòng duyệt              | Giám đốc quyết định                          |

## Dòng tiêu đề CSV để chạy mailing

```
CTY_TEN,CTY_TEN_VT,CTY_DC,CTY_MST,CTY_DT,CTY_EMAIL,CTY_STK,CTY_NGAN_HANG,CTY_DAI_DIEN,CTY_CHUC_DANH,CTY_DIA_DANH,CTY_NGUOI_AT,CTY_NGUOI_DL,CTY_KE_TOAN_TRUONG,CTY_CD_TEN,CTY_CD_CHU_TICH,VB_SO,VB_NGAY,VB_THANG,VB_NAM,VB_NGUOI_KY,NLD_MA,NLD_HO_TEN,NLD_GIOI_TINH,NLD_NGAY_SINH,NLD_CCCD,NLD_CCCD_NGAY,NLD_CCCD_NOI,NLD_DC_THUONG_TRU,NLD_DC_TAM_TRU,NLD_DT,NLD_MA_BHXH,NLD_MST,NLD_STK,NLD_NGAN_HANG,NLD_TRINH_DO,NLD_CHUC_DANH,NLD_BO_PHAN,NLD_NGAY_VAO_LAM,NLD_LIEN_HE_KC_TEN,NLD_LIEN_HE_KC_DT,NLD_THE_AT_SO,NLD_THE_AT_HAN,NLD_KSK_HAN,HD_SO,HD_NGAY_KY,HD_LAN_KY,HD_NGAY_BD,HD_NGAY_KT,HD_THU_VIEC_NGAY,HD_LUONG_THU_VIEC,HD_LUONG_CB,HD_LUONG_CB_CHU,HD_DON_GIA_CONG,HD_PHU_CAP,HD_KY_TRA_LUONG,HD_NGAY_TRA_LUONG,HD_DIA_DIEM_LV,HD_PHU_LUC_SO,CT_MA,CT_TEN,CT_DIA_DIEM,CT_TINH,CT_CHI_HUY_TRUONG,CT_AT_VIEN,CT_NGAY_KHOI_CONG,CT_NGAY_HOAN_THANH,CT_BENH_VIEN,CT_BENH_VIEN_DT,KH_TEN,KH_DC,KH_MST,KH_DAI_DIEN,KH_CHUC_DANH,KH_HD_SO,KH_HD_NGAY,NCC_TEN,NCC_DC,NCC_MST,NCC_DAI_DIEN,NCC_STK,XUONG_GC_TEN,XUONG_GC_MST,XUONG_GC_DAI_DIEN,XUONG_GC_DIA_CHI_XUONG,GC_HD_SO,GC_HD_NGAY,TN_NGAY_GIO,TN_DIA_DIEM,TN_LOAI,TN_MO_TA,TS_LUONG_TOI_THIEU_V1,TS_NGUONG_CHUYEN_KHOAN,TS_TL_BHXH_NLD,TS_TL_BHYT_NLD,TS_TL_BHTN_NLD,TS_PHU_CAP_CONG_TRUONG,TS_CONG_TAC_PHI,TS_THUONG_AT,TS_KPI_TL_LNG,TS_KPI_TRAN,TS_NGUONG_BAO_GIA,TS_NGUONG_HD_NCC,TS_NGUONG_CHI_TP
```

## Thay thế hàng loạt bằng Python

```python
import glob, json
data = json.load(open("du_lieu.json", encoding="utf-8"))   # {"CTY_TEN": "CÔNG TY ...", "CTY_DC": "..."}
for f in glob.glob("*.md"):
    s = open(f, encoding="utf-8").read()
    for k, v in data.items():
        s = s.replace("<<%s>>" % k, v)
    open(f, "w", encoding="utf-8").write(s)
```

Với mailing theo từng người (công nhân): tạo một dòng CSV cho mỗi người với các cột `NLD_`, `HD_`, `CT_`; chạy vòng lặp trên bản sao của file mẫu, lưu mỗi người một file.
