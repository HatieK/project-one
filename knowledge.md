1. Cách nhúng font vào dự án không dùng google fonts
2. Dùng convert fonts
3. JPG không hỗ trợ ảnh trong suốt (rỗng nền, ảnh bị đổi nhòe hơn khi nén)
4. PNG hỗ trợ ảnh rỗng nền (ảnh không bị đổi khi nén)
5. Logo icon xuất SVG vì ảnh này ít chi tiết 
6. có thể tối ưu ảnh PNG bằng web tinypng.com
===============================//===============================
Lưu ý code
phần header là toàn bộ phần đầu và đánh giá là nó có height = 100vh
phần content luôn nằm ở giữa với width là 1110px
thẻ a khi làm dạng button có padding phải có inline-block để xét đúng kích thước
với lớp giả before ở phần guide
left:50% là dịch từ bên trái sang 50% của thẻ cha relative
với transform(translateX -50%) thì dịch sang trái 50% độ dài của lớp giả

khi thẻ cha có display flex và có 3 thẻ con và thẻ con có flex:1 nghĩa là 3 thẻ con này sẽ tự động chia các kích thước bằng nhau và lấp đầy khoảng trống vào thẻ cha

Lưu ý khoảng cách giữa các thành phần

Lưu ý phần stats. kích thước width của nó là 1048px

margin: auto chỉ tác dụng vs thẻ block

<!-- DEPLOY GITHUB -->