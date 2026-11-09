Hello các con vợ, anh lên đây để chia sẻ một số nội dung của dự án 580 esp32
vì anh cũng đang ở trong quá trình tìm hiểu nên sẽ có chút sai sót.
hôm nay anh lên đây để chia sẻ với các e datasheet của màn hình casio 580 fake
Sơ đồ :
nhìn từ đằng sau màn hình ta đọc từ phải sang trái lần lượi từ 1-20
ta có p1, p20 là hai chân cố định cap, không có chức năng
p2 - LCD CD
p3 - LCD RD
p4 - LCD WR0
từ p5-p12 lần lượi là 8 chân data từ d0-d7
p13 - LCD RST
p14 - CS0
p15 - VCC (3,3v)
p16 - GND (0v)
Trên hình ảnh ta thấy p16 và p17 nối vs nhau qua tụ, p18 và p19 cũng vậy, theo t thì không nên can thiệp vào nó.
NHẮC LẠI: T CŨNG DNG TÌM HIỂU NÊN SẼ CÓ CHÚT SAI SÓT TRONG QUÁ TRÌNH VỌC VẠCH 
ĐÂY CHỈ LÀ SƠ ĐỒ MÀN HÌNH 580, CHƯA PHẢI DATASHEET HOÀN THIỆN
mẹo: ae mua mạch Logic Analyzer về để đào sâu hơn nhé 😘😘😘
