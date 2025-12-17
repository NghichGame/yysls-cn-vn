# Việt hóa Where Winds Meet | Yên Vân Thập Lục Thanh CN->VN Fix Font
Bản Việt hóa Where Winds Meet | Yên Vân Thập Lục Thanh bản nội địa Trung (yysls.cn) fix font

Chức năng:
- Dịch toàn bộ văn bản trích xuất từ file "translate_words_map_zh_cn"
- Fix lỗi font (lớn nhỏ, lên xuống, viền răng cưa) do thiếu ký tự tiếng Việt
- thu nhỏ kích thước font chữ + thu hẹp chiều ngang để hạn chế mất chữ do khi dịch ra, văn bản dài hơn văn bản gốc rất nhiều
- Phương pháp: chỉ fix ở cấp độ API của windows không thay thế font gốc của game.

Tiến độ:
- Đến 17/12 đã hoàn thành 1248026/1255160 key và sửa nhiều lỗi dịch thuật
- Bản phát hành và hướng dẫn: Sẽ có sẵn khi hoàn thành dịch hết key

Hạn chế:
- Một số văn bản nằm trong "translate_words_map_zh_cn" đã dịch nhưng vẫn hiển thị tiếng Trung, chưa tìm ra nguyên nhân :(
- Một số văn bản không nằm trong file "translate_words_map_zh_cn" vẫn chưa thể dịch.
- Hiện tại mới chỉ hỗ trợ bản PC
- Vì khối lượng văn bản lớn, bản dịch không thể tránh các sai sót chưa thể sửa lỗi

Công cụ sử dụng:
- Bản dịch thực hiện 100% bởi AI Google Gemini
- Tham khảo sửa lỗi dịch thuật: Quick Translator(QT), https://key.vietphrase.info/, từ điển Hán-Việt https://hvdic.thivien.net/
- Công cụ của WQ223(unpack, pack file) và user854221(extract, repack text) diễn đàn reshax.

Demo:
![Demo1](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/1.png)
![Demo2](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/2.png)
![Demo3](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/3.png)
![Demo4](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/4.png)
![Demo5](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/5.png)
![Demo6](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/6.png)
![Demo7](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/7.png)
![Demo8](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/8.png)
![Demo9](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/9.png)
