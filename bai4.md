**Bài 4 : Rủi ro đánh cắp mật khẩu từ trình duyệt** 

**3\. Yêu cầu đầu ra**

- Lập bảng so sánh dựa trên các tiêu chí: Khả năng chống Infostealer, Zero-Knowledge Architecture, và khả năng đồng bộ chéo nền tảng.


| Tiêu chí | Google Chrome Password Manager | Bitwarden |
| ----- | ----- | ----- |
| Khả năng chống Infostealer | Kém: Khóa giải mã lưu trên máy rất dễ bị mã độc quét và lấy sạch toàn bộ mật khẩu trong vài giây. | Tốt: phải mở được Master Password thì mới lấy được mật khẩu của web mà mình đã đặt, tự khóa lại khi tắt nên mã độc sẽ không đọc trộm được. |
| Zero-Knowledge Architecture  | Google mặc định giữ khóa giải mã để hỗ trợ khôi phục, nếu tài khoản hoặc máy chủ bị lộ ra ngoài. | Tuyệt đối: mã hóa ngay tại máy của cá nhân; chỉ cá nhân mới biết mật khẩu và Bitwarden cũng không thể xem trộm. |
| Đồng bộ chéo nền tảng | Chỉ đồng bộ tốt khi lướt web trên Chrome; khó dùng cho app trên máy tính | Dùng mượt trên mọi trình duyệt Chrome, Edge, Firefox, app trên máy tính  |


   

- **Lập luận tại sao Bitwarden thắng thế về mặt bảo mật dù tốn thêm thao tác nhập Master Password.**  
+ Vì Bitwarden nó sẽ không lưu master password nó chỉ chứa các ký tự mã hóa, một dãy ký tự không có ý nghĩa và nếu server Bitwarden có bị hack thì dữ liệu chỉ là các khối mã hóa hỗn loạn ko thể giải mã.


