THIỆP 20/10 3D - HƯỚNG DẪN DÀNH CHO NGƯỜI MỚI
================================================

CẤU TRÚC THƯ MỤC
- index.html : toàn bộ HTML, CSS, JavaScript
- couple.jpg : ảnh của hai bạn (bạn tự thêm ảnh này vào thư mục)

1. THÊM ẢNH HAI NGƯỜI
- Chọn một ảnh hai bạn muốn đưa vào thiệp.
- Sao chép ảnh vào cùng thư mục với index.html.
- Đổi tên ảnh thành couple.jpg.
- Nếu ảnh là PNG, bạn có thể đổi tên thành couple.png rồi sửa src="couple.jpg"
  trong index.html thành src="couple.png".

Lưu ý: nên chọn ảnh ngang, rõ nét. Hãy chắc chắn cả hai đều đồng ý chia sẻ ảnh nếu đăng thiệp công khai.

2. MỞ PROJECT TRONG VISUAL STUDIO CODE
- Giải nén file ZIP.
- Mở VS Code.
- Chọn File > Open Folder...
- Chọn thư mục Thiep_20_10_3D.
- Mở index.html.

3. CHẠY THỬ TRÊN MÁY TÍNH
Cách nhanh:
- Nhấp đúp index.html để mở bằng Chrome.

Cách dùng VS Code:
- Mở Extensions (biểu tượng các ô vuông bên trái).
- Tìm "Live Server" và cài đặt.
- Nhấp chuột phải index.html > Open with Live Server.
- Kiểm tra cả giao diện máy tính và điện thoại.

4. CÁ NHÂN HÓA LỜI CHÚC
- Mở index.html.
- Tìm đoạn <section class="letter" id="letter">.
- Sửa các đoạn văn thành lời chúc riêng của bạn.
- Nhấn Ctrl + S để lưu.

5. ĐĂNG LÊN MẠNG MIỄN PHÍ BẰNG GITHUB PAGES
Bạn cần tài khoản GitHub:
- Đăng nhập GitHub và tạo repository mới, ví dụ: thiep-20-10.
- Chọn Public để dễ bật GitHub Pages.
- Tải lên index.html và couple.jpg ở ngay thư mục gốc của repository.
- Vào Settings > Pages.
- Ở phần Build and deployment, chọn Deploy from a branch.
- Branch: main; Folder: /(root), rồi bấm Save.
- Chờ GitHub hoàn tất triển khai. URL thường có dạng:
  https://TEN-GITHUB-CUA-BAN.github.io/thiep-20-10/
  Hãy dùng đúng URL GitHub Pages hiển thị trong Settings > Pages.
- Mở URL trên điện thoại để kiểm tra rồi gửi link cho người yêu.

Nếu không thấy mục Pages hoặc link chưa hoạt động, kiểm tra repository, branch và trạng thái deployment trong tab Actions.

QUAN TRỌNG VỀ RIÊNG TƯ
- Nếu repository là Public, ảnh và lời chúc có thể được người khác xem nếu biết đường dẫn.
- Chỉ đăng ảnh mà bạn có quyền chia sẻ và cả hai đều thấy thoải mái.
- Không đưa số điện thoại, địa chỉ nhà, mật khẩu hoặc thông tin riêng tư vào trang.
- Nếu không muốn ảnh công khai, hãy cân nhắc nền tảng lưu trữ có quyền truy cập riêng.

Không cần Node.js, React hay cài thư viện. Project chạy bằng HTML, CSS và JavaScript thuần.
