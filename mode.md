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
- command press d0 => xóa từ vị trí hiện tại đền đẩu line
- command press d$ => xóa từ vị trí hiện tại đền cuối line.
- command press yiw => copy toàn bộ word inner
- command press ciw = xóa word và chỉnh sửa tại ví trí xóa đi.

# Command normal mode
- command press di" => xóa nội dung giữa dấu "
- command press ci" => xóa nội dung giũa dấu " vả vào insert mode.
- đặt con trỏ ở vị trí mở { , sau đó command press % => nhảy tới close }
- command press d% => xóa tất cả ở giữa dấu {}
- command press t[ký tự] => nhảy trước trước vị trí ký tự  => dt( => xóa từ vị trí con trỏ đến trước (
- command press f[ký tư] => nhảy tới vị trí kí tự
- command press T hoặc F => sẽ dảo ngược vị trí so với t, f

- command press gg => nhảy tới đẩu file
- command press G => nhảu tới cuối file
- command press :lineNumber or linenumber + G => nhảy tới line cần nhảy

# Tạo Indent
- command press >> => tabs
- command press << => shift tabs

# Visual Line
- command press Shift v => visual chọn line.
- 
