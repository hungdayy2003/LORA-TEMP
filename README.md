🚀 Tổng Quan Dự Án
Mục tiêu: Phát triển hệ thống giám sát tiêu thụ năng lượng thấp, truyền dữ liệu khoảng cách xa sử dụng LoRa.

Công nghệ sử dụng: LoRa (SX1278), ESP32, MAX31865, PC817, LM393, LM2596, LM358, ICL7660,...

Phạm vi thực hiện: Từ thiết kế mạch, vẽ PCB, đến lập trình firmware và kiểm tra hệ thống thực tế.

🛠 Chức Năng Chính
Thu thập dữ liệu từ các cảm biến:

Cảm biến nhiệt độ PT100 (qua IC MAX31865 – giao tiếp SPI)

Điện trở nhiệt NTC (đọc tín hiệu analog qua ADC)

Cảm biến độ ẩm đất (tín hiệu kỹ thuật số)

Cảm biến tiệm cận (cách ly bằng opto PC817)

Tín hiệu dòng điện 4–20mA (chuyển đổi sang điện áp)

Truyền dữ liệu qua LoRa (433MHz) sử dụng module RA-02 (SX1278)

Mạch nguồn sử dụng LM2596 và các linh kiện bảo vệ như diode, cuộn cảm

PCB được thiết kế hoàn chỉnh bằng phần mềm OrCAD; lập trình bằng Arduino IDE

📦 Kiến Trúc Phần Cứng
ESP32: Vi điều khiển trung tâm (tích hợp WiFi, Bluetooth, ADC, SPI...)

Module RA-02 LoRa: Truyền thông không dây

Cảm biến: PT100, NTC, cảm biến tiệm cận, cảm biến độ ẩm đất, tín hiệu 4-20mA

Nguồn: LM2596 (giảm áp từ 24VDC và ổn định nguồn)

Thiết kế mạch in (PCB): Schematic & layout đầy đủ bằng OrCAD


💡 Ứng Dụng Thực Tế
Giám sát công nghiệp từ xa

Nông nghiệp thông minh

Hệ thống IoT giám sát môi trường

Mạng cảm biến không dây

PCB IMAGE: https://github.com/user-attachments/assets/07938951-aa42-4927-9651-53b58e0074ba" >
