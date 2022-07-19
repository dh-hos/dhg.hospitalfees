### DHG.Hospital Fees - Thông tin cập nhật

<div align="center" style="font-size:xx-small">(✨: Chức năng mới,🐛: Chỉnh lỗi, #️⃣: Giải quyết công việc) </div>

-  🐛: Fix Không đủ chổ trống ghi nhận số tiền trên bảng kết toán viện phí nên hiển thị số tiền ######## [OK]
-  🐛: Bệnh nhân có stent 2 đã thu hết chi phí nhưng bảng kết toán viện phí vẫn ghi nhận bệnh nhân còn nợ. [OK]
-  🐛: Bảng kê bệnh nhân nợ viện phí cũng hiển thị bệnh nhân còn nợ [OK]
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/49 [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/46 [OK]
-  #️⃣: Truyền thêm thông tin số tài khoản (phiếu thu) khi lập hóa đơn điện tử của VNPT. (đổi `ComBankNo` sang `CusBankNo`) [OK]

-  ✨: Bổ sung thêm chổ thu tự do cho nhập đầy đủ Đơn vị tính, đơn giá, số lượng, thành tiền. (Kết nối với Hddt: `VAT, VNPT`, `VIETTEL`, `MISA`, `EASYINVOICE`). Ghi chú: `Khi điều kiện để đưa thông tin số lượng, đơn giá lên cổng hóa đơn là: có đơn vị tính, số lượng và đơn giá lớn hơn 0.` [OK]
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/47 [OK]

-  ✨: Yêu cầu trong nhật ký gửi Hóa đơn điện tử của VAT bổ sung thêm thời gian bắt đầu và kết thúc khi Lập hóa đơn điện tử. [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/52 [OK]
-  ✨: Bổ sung lý do khi xóa hddt của Viettel vào trường `reasonDelete` [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/53 [OK]
-  🐛: In phiếu thu trên lưới chứng từ thu chi thiếu matracuu_hddt [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/51 [OK]
-  ✨: Mở chức năng Viện phí dành riêng cho nhà thuốc đối với BV Nhi Đồng (TP Cần Thơ - 92003) [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/54 [OK]
-  ✨: Áp dụng thêm tham số `vpnhathuoc`,`vpnhathuoc_khocp` đối với đối tượng BHYT và Trẻ em (lấy toàn bộ thông tin thuốc thuộc BHYT và thuốc Nhà thuốc theo cấu hình `vpnhathuoc_khocp`) [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/57 [OK]
-  ✨: Đổi tiêu đề trên bảng kê biên lai [Dịch vụ (viện phí)] => [Chi phí (viện phí)],[Dịch vụ (nhà thuốc)] => [Chi phí (nhà thuốc)] [OK]
-  🐛: Fix Bảng kê biên lai thể hiện âm chi phí viện phí khi có chi phí thuộc nhà thuốc [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/55 [OK]
-  #️⃣: https://github.com/dh-hos/dhg.hospitalfees/issues/58 [OK]
-  🐛: Fees không tính được tiền của stent thứ 2 có số lượng lớn [OK]
