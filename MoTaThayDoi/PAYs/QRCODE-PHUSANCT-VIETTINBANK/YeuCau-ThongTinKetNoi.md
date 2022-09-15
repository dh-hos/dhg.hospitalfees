1. Giao tiếp giữa Viettin và Bệnh viện có cần thực hiện thông qua hệ thống Leased line không?

qrGenerator
	1. Xin cung cấp thông tin kết nối cho BV PHỤ SẢN CẦN THƠ 
		MAIN_URL
		x-ibm-client-secret
		x-ibm-client-id
		providerId
		merchantId
		merchantName
		terminalId
		version
	2. Giá trị cần truyền là gì
		payMethod (QR: thanh toán bằng QR code)
		channel: MOBILE, WEB, POS, BRANCH
	3. Khi nhận được qrData trả về, chuyển phần này thành hình ảnh QR để khách hàng thanh toán hay thế nào?
		
qrConfirm
	1. Method  phía Vietbank gọi là gì (POST, PUT,....)
	2. Khi nào thì giao dịch mới được hoàn thành (khách hàng thanh toán xong, tiền đã vào Tài khoản BV): 
		2.1 - Lúc Viettin gọi hàm qrConfirm là hoàn thành? 
		2.2 - Hay Lúc Viettin nhận được response từ phía bệnh viện?