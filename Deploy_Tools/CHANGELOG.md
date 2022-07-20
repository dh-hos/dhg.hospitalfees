### DHG.Hospital Fees - Thông tin cập nhật

<div align="center" style="font-size:xx-small">(✨: Chức năng mới,🐛: Chỉnh lỗi, #️⃣: Giải quyết công việc) </div>

##### [v3.22.0720.1]()

-  🐛: Fix trường hợp lập phiếu thu không theo tham số phieuthubnchuaxv
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/55#issuecomment-1189693317

##### [v3.22.0719.2]()

-  🐛: Fees không tính được tiền của stent thứ 2 có số lượng lớn
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/58
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/55

##### [v3.22.0719.1]()

-  🐛: Fix Bảng kê biên lai thể hiện âm chi phí viện phí khi có chi phí thuộc nhà thuốc
-  ✨: Đổi tiêu đề trên bảng kê biên lai [Dịch vụ (viện phí)] => [Chi phí (viện phí)],[Dịch vụ (nhà thuốc)] => [Chi phí (nhà thuốc)]
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/57

##### [v3.22.0708.1]()

-  ✨: Áp dụng thêm tham số `vpnhathuoc`,`vpnhathuoc_khocp` đối với đối tượng BHYT và Trẻ em (lấy toàn bộ thông tin thuốc thuộc BHYT và thuốc Nhà thuốc theo cấu hình `vpnhathuoc_khocp`)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/54

##### [v3.22.0707.1]()

-  ✨: Mở chức năng Viện phí dành riêng cho nhà thuốc đối với BV Nhi Đồng (TP Cần Thơ - 92003)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/51

##### [v3.22.0706.1]()

-  🐛: In phiếu thu trên lưới chứng từ thu chi thiếu matracuu_hddt
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/53

##### [v3.22.0629.5]()

-  ✨: Bổ sung lý do khi xóa hddt của Viettel vào trường `reasonDelete`
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/52

##### [v3.22.0629.4]()

-  ✨: Yêu cầu trong nhật ký gửi Hóa đơn điện tử của VAT bổ sung thêm thời gian bắt đầu và kết thúc khi Lập hóa đơn điện tử.
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/50

##### [v3.22.0629.3]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/47
-  ✨: Bổ sung thêm chổ thu tự do cho nhập đầy đủ Đơn vị tính, đơn giá, số lượng, thành tiền. (Kết nối với Hddt: `VAT, VNPT`, `VIETTEL`, `MISA`, `EASYINVOICE`). Ghi chú: `Khi điều kiện để đưa thông tin số lượng, đơn giá lên cổng hóa đơn là: là phiếu thu tự do (loai='pttd') có đơn vị tính, số lượng và đơn giá lớn hơn 0.`

##### [v3.22.0629.2]()

-  #️⃣: Truyền thêm thông tin số tài khoản (phiếu thu) khi lập hóa đơn điện tử của VNPT. (đổi `ComBankNo` sang `CusBankNo`)
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/46

##### [v3.22.0629.1]()

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/49
-  🐛: Bảng kê bệnh nhân nợ viện phí cũng hiển thị bệnh nhân còn nợ
-  🐛: Bệnh nhân có stent 2 đã thu hết chi phí nhưng bảng kết toán viện phí vẫn ghi nhận bệnh nhân còn nợ.
-  🐛: Fix Không đủ chổ trống ghi nhận số tiền trên bảng kết toán viện phí nên hiển thị số tiền ########

##### [v3.22.0623.1]()

-  ✨: Bổ sung theo dõi nội dung cập nhật module Fees [tại đây](https://github.com/dh-hos/dhg.hospitalfees/blob/main/Deploy_Tools/CHANGELOG.md)
