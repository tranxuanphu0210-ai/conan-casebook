CONAN CASEBOOK — PWA NETLIFY DROP

Cách triển khai:
1. Giải nén ZIP này.
2. Upload toàn bộ nội dung bên trong thư mục đã giải nén lên Netlify Drop (index.html phải ở thư mục gốc).
3. Mở URL HTTPS Netlify trên Chrome Android, chọn menu ⋮ rồi Install app / Add to Home screen nếu có.

Đã sửa cú pháp import trong Babel standalone để dùng React global từ CDN.
PWA vẫn cần Internet để tải React, ReactDOM, Babel và Tailwind từ CDN; ngoại tuyến đầy đủ chưa được bảo đảm.
Dữ liệu tiếp tục dùng localStorage key bk_flow_conan_v3 trên cùng trình duyệt. Không xóa dữ liệu trình duyệt và hãy sao lưu trước khi đổi bản.
