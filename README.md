Phân tích lỗi & Lập bảng Test Cases
1. Phân tích lỗi
 0, false, "" được coi là false nên if (false) không chạy được. Phải đưa về if (true)
2. Test case
a. 
Trường hợp kiểm thử: Tắt điều hòa phòng khách
Dữ liệu đầu vào: updatedData.isActive = false
Kết quả sai thực tế: Bị bỏ qua, isActive vẫn là true
Kết quả đúng mong đợi: updatedData.isActive = false

b. 
Trường hợp kiểm thử: Hạ công suất đèn ngủ về 0W
Dữ liệu đầu vào: updatedData.powerWatts = 0
Kết quả sai thực tế: Bị bỏ qua, powerWatts giữ nguyên vị cũ
Kết quả đúng mong đợi:  updatedData.powerWatts = 0
