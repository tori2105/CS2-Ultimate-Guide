<h1 align="center"><img width="23px" style="border-radius: 50%" src="https://raw.githubusercontent.com/tori2105/CS2-Ultimate-Guide/refs/heads/main/IMG/Counter-Strike_2_29.webp"> QUAY VÀ XUẤT FILE MP4/MOV CHẤT LƯỢNG CAO VỚI HLAE</h1>

> - Nguồn: [ThuysKieu](https://steamcommunity.com/id/thuyskieu2207) | [Community Guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3253265356)
> - Lưu ý: Do HLAE can thiệp trực tiếp đến game nên <ins>có rủi ro bị VAC ban khi sử dụng</ins>. Để sử dụng HLAE an toàn, thêm launch option -insecure trước khi sử dụng để tắt VAC

Sử dụng HLAE để quay ra clip CS2 với chất lượng và độ phân giải cao, nhưng thực tế khi xuất ra file .tga và sử dụng VirtualDub sẽ mất ra nhiều thời gian và dung lượng ổ đĩa.
Để giải quyết cách này, nên tải đầu đọc định dạng Ffmpeg cho AFX của HLAE để tối ưu và xử lý nhanh ra file .mp4 và .mov một cách hiểu quả; các bước sau đây vô cùng đơn giản và nhanh gọn.

- Tải định dạng đầu đọc Ffmpeg cho AFX của HLAE
```
https://github.com/GyanD/codexffmpeg/releases/tag/7.0
```
> - Giải nén tập tin sau khi tải
> - Copy tập tin đã giải nén và Paste vào thư mục của HLAE :(C:\thư_mục_chứa_HLAE\hlae_2_1...\ffmpeg)

- Tải Config dành cho CS2 khi đã cài đầu đọc Ffmpeg
```
https://drive.google.com/drive/folders/1A26BO0KACo1xbRG2mUx_o9HvmdI0K1rn
```
> - Khởi động CS2 bằng HLAE
> - Nhập lệnh "exec editcs2", sau đó ghi "codec" hoặc "exec _codec". Ngày lúc này Config sẽ nhập file đầu đọc để biết và xuất ra file clip
> - Đọc các danh sách đầu đọc, đuôi file muốn xuất ra clip. Ví dụ nhập "he1" để ra đầu đọc x265 màu đọc hơn chuẩn 7 triệu màu

Lúc này chỉ cần quay ra clip với bao nhiêu FPS là thành công.<br>
Để tìm hiểu thêm cách sử dụng HLAE, quay ra file clip và sử dụng Camera Cinematic,... Hãy xem video hướng dẫn của OP:
> - https://www.youtube.com/watch?v=ILeKzjXr8Xk
> - https://www.youtube.com/watch?v=eFbcC0fsKE0
