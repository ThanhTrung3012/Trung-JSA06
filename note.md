I> Cách sử dụng
- 1 số khái niệm
+ clone : Clone là 1 bản sao của kho mã nguồn . Khi bạn muốn làm việc với 1 dự án, bạn có thể clone dự án đố về máy của mình và làm việc với dự án đó
+ commit : Mỗi lần thay đổi mã nguồn, bạn cần commit để luuw lại phiê bản hiện tại của mã nguồn.
+ Push : Đẩy code  từ máy lên git sau khi chung ta commit
+ pull : Lấy code commit từ trên git về máy tinh. Kh i bạn muốn lấy các commit mới nhất
 về máy

 - Cách sử dụng câu lệnh
 B1 : Đăng nhập gitHub và tạo Repo ( để chế độ public )
 B2 : Lên google : Git Download : tải về theo phiên bản của máy
 B3 : Kết nối giữa máy mình với tktreen github : Gõ trên google : git config global
 B4 : Khởi tạo tên người dùng ( trên Github) + mail đăng ký Github
 - $git config--global user.name "thanhtrung"
 - $git config --global user.email dothanhtrung3112@gmail.com
 B5 : Kiểm tra xem đã config được hay chưa thì gõ như sau :
 - $git config --list 
 B6 : Vào thư mục gốc chứa sản phẩm : chuột phải chon gitBash
 B7 : Khởi tạo : git init ( file gốc sẽ hiện thị 1 file .git)
 B8 : Kết nối, liên kết git trong máy của mình với git trên internet
 -$ git remote add origin .......
 B9 : Kiểm tra xem kết nối được chưa :
 -$ git remove -v
 B10 : Đưa toàn bộ code lên GitHub :
 - $git add
 - Gói lại : $git commit -m ".."
 - Đẩy từ máy lên gitbub : git push origin master