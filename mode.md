# modes
- Có 2 mode : insert mode và command mode
- để vào insert mode dùng :
  + i : tại vị trí con trỏ. 
  + Shift + i => đầu hàng
  + a : sau vị trí con trỏ
  + Shift + a : cuối line
  + o : xuống hàng
  + shift + o : line mới ở trên
- Để vào command mode : press ESC 
- Để hiển thị number của line dùng command : => :set number
- Ở command mode , có thể kết hợp số vào phím mũi tên để di chuyển con trỏ : => 5 + phím xuống => con trỏ nhảy xuống 5 dòng. => 5 + phìm qua phải => con trỏ nhảy qua phải 5 ký tự.

# Undo 
- command press u => undo
- command press Ctrl + R => ngược lại với u

# Visual mode
- commmand press v => sau đó click các phím mũi tên để chọn.
- Sau khi chọn có thể press d => để delete
- press 2 lần Esc để thoát visual mode.


- Để copy ta dùng command press y => copy.
- Đế paste ta dùng command press p => paste.
- select word and command press c => xóa đoạn chọn và edit tại đó.

## Delete
- command press d => xóa vùng được chọn
- command press dd => xóa line hiện tại.
- command press 5dd => xóa 5 line.
- commnd press D => xóa từ vị trí con trỏ để cuối line.

- Xóa line và chỉnh sửa ngay tại line đó ta dùng command press cc => xóa line và chỉnh sửa tại line đó.

## Copy and paste
- command press yy => copy line hiện tại.
- command press 5p => paste 5 lần.
- command press P (uppercase) => paste ở line trên.

## Word and before word
- command press w => nhảy tới word tiếp theo.
- command press b => nhảy tới word trước đó.
- command press W => bỏ qua ký tự được xem là tách word như ";" , "-"

## Kết hợp delete word
- command press d[nubmer of word]w => xóa word
- command press diw => xóa word hiện tại nếu con trỏ nằm ở giữa.
- command press ciw => xóa và edit word.
- command press e => nhảy tới cuối cùng của woro.
- command press $ => nhảy tới cuối hàng ở normal mode.
- command press 0 => nhảy tới đẩu hàng ở normal mode.
