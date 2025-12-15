# yysls-cn-vn
Bản dịch Việt hóa Yên Vân Thập Lục Thanh (yysls.cn) fix font

Chức năng:
- Dịch toàn bộ văn bản trích xuất từ file "translate_words_map_zh_cn"
- Fix lỗi font (lớn nhỏ, lên xuống, viền răng cưa) do thiếu ký tự tiếng Việt
- thu nhỏ kích thước font chữ + thu hẹp chiều ngang để hạn chế mất chữ do khi dịch ra, văn bản dài hơn văn bản gốc rất nhiều
- Phương pháp: chỉ fix ở cấp độ API của windows không thay thế font gốc của game.
- Có thể sử dụng cho bản global không? Có thể, nhưng chưa test vì bản global đã có nhiều nhóm làm và hình như cũng không cần fix font (không rõ)

Tiến độ:
- Đến 15/12 đã hoàn thành 1170681 key và sửa lỗi dịch thuật cơ bản
- Bản phát hành và hướng dẫn: Sẽ có sẵn khi hoàn thành dịch hết key

Hạn chế:
- Một số văn bản nằm trong "translate_words_map_zh_cn" đã dịch nhưng vẫn hiển thị tiếng Trung, chưa tìm ra nguyên nhân :(
- Một số văn bản không nằm trong file "translate_words_map_zh_cn" vẫn chưa thể dịch.
- Hiện tại chỉ hỗ trợ bản PC
- Vì khối lượng văn bản lớn, bản dịch không thể tránh các sai sót chưa thể sửa lỗi

Công cụ sử dụng:
- Bản dịch thực hiện 100% bởi AI Google Gemini
- Tham khảo sửa lỗi dịch thuật: Quick Translator(QT), https://key.vietphrase.info/, từ điển Hán-Việt https://hvdic.thivien.net/
- Công cụ của WQ223(unpack, pack file) và user854221(extract, repack text) diễn đàn reshax.
