# Andon EDGE
## Yêu cầu môi trường cài đặt:
### Thiết bị
1. Raspberry 4
2. Đầu đọc thẻ RFID CF-RU5602 (link: http://www.chafon.com/productdetails.aspx?pid=969)
3. Bộ thẻ RFID
### Phần mềm 
1. Erlang 24.1.7
2. RabbitMQ 3.9.11
3. Python 3.8
4. Database: sqlite
## Mô tả năng của service Edge:
1. Đọc data từ module RFID
2. Phân tích data và đóng thành bản tin thành json
3. Forward tin lên server RabbitMQ (trường hợp connect bị lỗi thì lưu lại bản tin vào database)
