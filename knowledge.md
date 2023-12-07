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

position sticky ko thể bám với kích thước bên ngoài thẻ cha chứa nó

<!-- DEPLOY GITHUB -->
1. Chọn gitbash mũi tên xuống bên phải khi bật terminal
2. vào github chọn create new repository
3. git init
4. git add .
5.  git commit -m "first commit"
6.  git branch -M main
7.  git remote add origin https://github.com/HatieK/project-one.git
8.  git push -u origin main
9.  vào setting
10. chọn page
11. nhánh main và bấm save
<!-- push lại code sau khi sửa -->
1. git add . 
2. git commit -m ""
3. git push origin main

<!-- GIT CĂN BẢN -->
1. git status ==> nothing to commit ==> file chưa thay đổi gì cả
2. git diff + (tên file) ==> hiện ra sự khác nhau trước và sau commit
3. khi sự thay đổi quá nhiều hiện dấu : thì bấm nút q
<!-- CLONE DỰ ÁN GITHUB -->
1. copy đường link
2. chọn chỗ chứa dự án mở terminal: git clone + link dự án

<!-- GIT PULL -->

