# Việt hóa Where Winds Meet | Yến Vân Thập Lục Thanh bản Trung CN->VN Fix Font
Bản Việt hóa Where Winds Meet | Yến Vân Thập Lục Thanh bản Trung (yysls.cn) và fix font

Chức năng:
- Dịch toàn bộ văn bản trích xuất từ file "translate_words_map_zh_cn", chất lượng bản dịch cao
- Fix lỗi font (lớn nhỏ, lên xuống, viền răng cưa) do thiếu ký tự tiếng Việt
- thu nhỏ kích thước font chữ + thu hẹp chiều ngang để hạn chế mất chữ do khi dịch ra, văn bản dài hơn văn bản gốc rất nhiều
- Fix hoàn toàn lỗi fallback về tiếng Trung với đa số hội thoại
- Dịch bổ sung thêm các text cập nhật chưa có trong file words_map (sự kiện, vật phẩm, map, nhiệm vụ mới...)
- Phương pháp: chỉ fix ở cấp độ API của windows không thay thế font gốc của game.
- Đồng bộ xưng hô cổ phong: ta ngươi, huynh đệ, thúc bá, mẫu thân, nương, a nương, phụ thân, gia gia, bà bà, thiếu gia, thiếu đông gia, cô nương, ... và nhiều đại từ xưng hô khác để phù hợp với bối cảnh game.
- Hệ thống danh hiệu, địa danh, môn phái, chiêu thức... Hán-Việt đậm chất cổ phong
- Sửa rất rất nhiều lỗi dịch thuật.

Tiến độ:
- Đã hoàn thành toàn bộ 1.321.058 key + hơn 2000 key proxy
- Từ phiên bản 1.0.2, dịch thêm phần UI đăng nhập, đăng ký Email, SĐT, quét mã QR, Trung tâm người dùng
- Từ phiên bản 1.1.0 fix được hoàn toàn cơ chế callback của game với văn bản hội thoại, npc talk về tiếng trung, đã có thể hiển thị gần như toàn bộ văn bản đã dịch có trong file words_map, sự kiện mới, vật phẩm, võ học mới, map Hô Đà mới. Tỉ lệ hiển thị tiếng Việt đạt ~99%
- Từ phiên bản 1.1.2 Donate 50k/1 năm sử dụng + xóa thông báo logo. Vẫn có thể sử dụng miễn phí, thông báo xuất hiện ngẫu nhiên.
- Xem video demo hội thoại map Bất Kiến Sơn
  [![Video Demo Việt Hóa](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/10.png)](https://www.youtube.com/playlist?list=PLrtlgPMKxfkEldat51wY_1JOmQ5ezjEXG "Click xem video Demo")

  

Hướng dẫn tải và cài đặt
- tải file việt hóa mới nhất (VietHoaYenVanCN_NghichGame_xxx.zip) tại [ĐÂY](https://github.com/NghichGame/yysls-cn-vn/releases/)  hoặc bấm vào page release.
- Sau khi tải về nhấp đúp vào file zip để mở (win 10, 11) hoặc mở bằng WinRar lên sẽ thấy có 2 thư mục "Engine" và "LocalData"
- Copy hoặc kéo thả cả 2 thư mục vào thư mục chính của bản game. ví dụ "D:\Games\yysls\yysls_medium" nếu chơi bản full và "D:\Games\yysls\yysls_fast" nếu chơi bản nhẹ (Xem ảnh dưới). Lưu ý nên mở Launcher trước và để Launcher cập nhật xong rồi copy.
  ![HD1](https://github.com/NghichGame/yysls-cn-vn/blob/main/assets/HD1.png)
- Xuất hiện thông báo ghi đè file, chọn dòng "Repalce the files in the destination"
- Xong! Vào game chơi như bình thường.

Cập nhật:
- Dự án sẽ cố gắng cập nhật, sửa lỗi dịch thuật nhiều nhất có thể
- Chi tiết các bản cập nhật xem ở page release

Hạn chế:
- Hiện tại mới chỉ hỗ trợ bản PC
- Vì khối lượng văn bản lớn, bản dịch không thể tránh các sai sót chưa thể sửa lỗi

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
