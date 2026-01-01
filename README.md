# Việt hóa Where Winds Meet | Yến Vân Thập Lục Thanh bản Trung CN->VN Fix Font
Bản Việt hóa Where Winds Meet | Yến Vân Thập Lục Thanh bản Trung (yysls.cn) và fix font

Chức năng:
- Dịch toàn bộ văn bản trích xuất từ file "translate_words_map_zh_cn"
- Fix lỗi font (lớn nhỏ, lên xuống, viền răng cưa) do thiếu ký tự tiếng Việt
- thu nhỏ kích thước font chữ + thu hẹp chiều ngang để hạn chế mất chữ do khi dịch ra, văn bản dài hơn văn bản gốc rất nhiều
- Phương pháp: chỉ fix ở cấp độ API của windows không thay thế font gốc của game.
- Đồng bộ xưng hô cổ phong: ta ngươi, huynh đệ, thúc bá, mẫu thân, nương, a nương, phụ thân, gia gia, bà bà, thiếu gia, thiếu đông gia, cô nương, ... và nhiều đại từ xưng hô khác để phù hợp với bối cảnh game (nhưng có thể vẫn còn sót).
- Hệ thống danh hiệu, địa danh, môn phái, chiêu thức... Hán-Việt đậm chất cổ phong
- Sửa nhiều lỗi dịch thuật (mặc dù còn rất nhiều).

Tiến độ:
- Đã hoàn thành toàn bộ 1.255.160 key và sửa nhiều lỗi dịch thuật

Hướng dẫn tải và cài đặt
- tải file việt hóa mới tại [ĐÂY](https://github.com/NghichGame/yysls-cn-vn/releases/download/1.0.2/VietHoaYenVanCN_NghichGame_1.0.2.zip)  hoặc page release.
- Sau khi tải về nhấp đúp vào file zip để mở (win 10, 11) hoặc mở bằng WinRar lên sẽ thấy có 2 thư mục "Engine" và "LocalData"
- Copy hoặc kéo thả cả 2 thư mục vào thư mục chính của bản game. ví dụ "D:\Games\yysls\yysls_medium" nếu chơi bản 120gb và "D:\Games\yysls\yysls_fast" nếu chơi bản 60gb (Xem ảnh dưới). Lưu ý nên mở Launcher trước và để Launcher cập nhật xong rồi copy.
  ![HD1](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/HD1.png)
- Xuất hiện thông báo ghi đè file, chọn dòng "Repalce the files in the destination"
- Xong! Vào game chơi như bình thường.

Cập nhật:
- Dự án sẽ cố gắng cập nhật, sửa lỗi dịch thuật nhiều nhất có thể
- Chi tiết các bản cập nhật xem ở page release

Hạn chế:
- Một số văn bản như npc xianhua, các văn bản mới cập nhật... không nằm trong file "translate_words_map_zh_cn"vẫn chưa thể dịch.
- Nhiều văn bản đã dịch nhưng trong game vẫn hiển thị tiếng Trung, chưa tìm ra nguyên nhân và cách khắc phục. Đa số là hội thoại, npc talk...Where Winds Meet bản Global có vẻ không bị do được thiết kế đa ngôn ngữ và không dịch trực tiếp trong file _zh_cn. Tới hiện tại, khả năng lớn nhất là do cơ chế cache và hotfix của bản nội địa, có thể khắc phục nếu can thiệp được vào file hotfix lua.
- Hiện tại mới chỉ hỗ trợ bản PC
- Vì khối lượng văn bản lớn, bản dịch không thể tránh các sai sót chưa thể sửa lỗi

Công cụ sử dụng:
- Bản dịch thực hiện thủ công bởi AI Google Gemini web
- Tham khảo sửa lỗi dịch thuật:  Gemini, Quick Translator(QT), https://key.vietphrase.info/, từ điển Hán-Việt https://hvdic.thivien.net/
- Công cụ của WQ223(unpack, pack file) và user854221(extract, repack text) diễn đàn reshax.

Demo:

 [Video demo 1](https://youtu.be/TWB9fqID1Qc), [video demo2](https://youtu.be/8YXyXx1DwKM)

![Demo1](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/1.png)
![Demo2](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/2.png)
![Demo3](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/3.png)
![Demo4](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/4.png)
![Demo5](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/5.png)
![Demo6](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/6.png)
![Demo7](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/7.png)
![Demo8](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/8.png)
![Demo9](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/9.png)
