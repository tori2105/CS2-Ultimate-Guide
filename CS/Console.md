<h1 align="center">CÁC LỆNH CONSOLE HỮU ÍCH</h1>

<h2>LƯU Ý</h2>

> - Các lệnh Toggle là lệnh tắt bật luân phiên
<hr>

## Lệnh cần thiết
1. Chỉ hiện số lượng người chơi thay vì avatar
> - Chỉ hiển thị mỗi bên có bao người chơi còn sống, đỡ gây xao nhãng khi chơi
```
cl_teamcounter_playercount_instead_of_avatars 1
```
2. Tắt giới hạn FPS
> - Nếu cần giới hạn theo refresh rate của màn hình, sửa giá trị thành rate + 30
> - Ví dụ: Màn 144hz giới hạn fps thì để fps_max 174
> - Cá nhân mình thấy cái này sẽ hiệu quả hơn với bật VSync
```
fps_max 0
```
## Lệnh tuỳ chỉnh
1. Lệnh đổi tay nhanh (Toggle)
```
bind PHÍM "switchhands;toggle cl_prefer_lefthanded 0 1"
```
2. Ẩn/hiện tên người chơi (Toggle)
```
bind PHÍM "toggle cl_sanitize_player_names 1 0"
```
3. Ẩn/hiện avatar người chơi (Toggle)
```
bind PHÍM "toggle cl_hide_avatar_images 1 0"
```
4. Ẩn/hiện tất cả (tên + avatar) [Toggle]
```
bind PHÍM "toggle cl_sanitize_player_names 1 0;toggle cl_hide_avatar_images 1 0"
```
5. Khoá mồm team địch (Toggle)
```
bind PHÍM "toggle cl_mute_enemy_team 1 0"
```
6. Cho phép tháo giảm thanh
```
"cl_silencer_mode" "0"
```
7. Tắt build info (góc trái bên dưới màn hình)
```
"r_show_build_info" "false"
```
8. Hiện tâm của mình khi xem người chơi khác
```
"cl_show_observer_crosshair" "0"
```
9. Ping tối đa khi ghép trận
> - Lệnh này chỉ hoạt động tốt nhất trong điều kiện mạng ổn định
> - Giá trị 50 ở dưới cho phép ghép server Hongkong, đồng thời là cả Singapore nếu ping thấp
> - Sửa giá trị = 40 nếu chỉ muốn ghép server Hongkong
> - Sửa giá trị = 65 nếu chỉ muốn ghép Hongkong + Singapore
> - Sửa giá trị = 100 nếu muốn ghép Hongkong + Singapore + Tokyo + Seoul (Tokyo và Seoul dễ gặp tình trạng lệch rank hơn)
```
mm_dedicated_search_maxping 50
```
10. Thay đổi hình nền inspect vật phẩm
> - Với mã map, anh em chịu khó tham khảo Google nếu không biết
> - Ví dụ: ui_inspect_bkgnd_map_9CA40421 de_mirage
> - Mã map mặc định là "warehouse"
```
ui_inspect_bkgnd_map_9CA40421 MÃ MAP
```
11. Thay đổi hình nền sảnh
> - Tương tự như trên
```
ui_mainmenu_bkgnd_movie_9CA40421$11 MÃ MAP
```
