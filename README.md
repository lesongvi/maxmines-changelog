# maxmines-changelog
## Quá trình bản địa hóa CachedMine (ngày 10/03/2020)
- Hiện tại trang [Góp ý chỉnh sửa CachedMine](https://maxmines.com/translate) đã được đưa trở lại hoạt động.  
*Xin lưu ý rằng, dù chúng tôi rất coi trọng tinh thần đóng góp của bạn, nhưng chúng tôi cũng không tha thứ cho những hành động spam phá hoại. Nếu bạn đang có ý định spam, hãy dừng lại.*
- Fix bug trang Dashboard, Góp ý chỉnh sửa.
## Update bảo mật (ngày 09/03/2020)
- Cập nhật bảo mật thông tin user nâng cao. Giảm, ẩn hoàn toàn thông tin nhạy cảm
- Cập nhật nhỏ cho web app.
- Sẵn sàng cho phần mềm MaxMines!
## Fix bug chữ (ngày 08/03/2020)
- Fix lỗi bug chữ trong trang trợ giúp opt-in. Không quá nặng nhưng nó làm khó chịu đối với người dùng.  
```
Mấy nay mình nhận được báo cáo một số dịch vụ như Maxmines Captcha, auth shortlink,... bị lỗi đứng giữa chừng hoặc công cụ khai thác chậm hơn bình thường. Ví dụ bình thường là 80H/s giờ chỉ còn trên dưới 20H/s thì các bạn vui lòng gửi email chi tiết:
- Khoảng thời gian bạn bị lỗi/bug
- Dịch vụ lúc đó (auth shortlink, captcha, miner, custom miner...)
- Thông số máy tính của bạn
- Tốc độ kết nối internet của bạn (có thể kiểm tra tại SpeedTest by Ookla)
- Public key site của bạn/công cụ khai thác hoặc địa chỉ, phần mềm, app đào lúc đó.
- Địa chỉ IP lúc đó của bạn (có thể kiểm tra tại ipchicken)
Địa chỉ email báo cáo: vi@rqn9[.]com
```
## Cập nhật sửa lỗi đăng nhập (ngày 04/03/2020)
- Đã fix tài khoản developer Facebook
## Đăng nhập Facebook lỗi (ngày 03/03/2020)
- Tài khoản developer Facebook bị khóa hiện tại không thể đăng nhập bằng Facebook vào Dashboard MaxMines chân thành xin lỗi các bạn. Trong thời gian chờ tài khoản được mở khóa mấy bạn vẫn có thể truy cập Dashboard MaxMines bằng các mxh khác hoặc đăng nhập bình thường.
## Fix bug dashboard (ngày 26/02/2020)
- Fix bug dashboard mobile
## Update referral system (ngày 24/02/2020)
- Cập nhật referral system pack 1.0
- Fix bug referral system pack
## Update tốc độ (ngày 23/02/2020)
- Tăng tốc độ tải của website, cải thiện chất lượng người dùng.
## Update OAuth (ngày 20/02/2020)
- Cập nhật đăng nhập bằng tài khoản mạng xã hội vào MaxMines. Hỗ trợ Facebook/Google/Amazon OAuth2, Github OAuthV4
## Update free pool (ngày 19/02/2020)
- Đã update đa dạng pool và coin để chuẩn bị cho bản cập nhật tiếp theo (mặc định là "xmr" tức Monero)
- Hiện script MaxMines hoạt động như một open pool (nếu bạn am hiểu và có kiến thức về Javascript bạn có thể sử dụng nó để đào các pool ngoài danh sách pool của MaxMines)
## Lời nhắc và update API (ngày 17/02/2020)
- Nếu bạn đang sử dụng thư viện đào theo maxmines.min.js và không thể đào được, vui lòng tắt phần mềm diệt virus đi. Phần mềm diệt virus gây ra một số khó khăn khi sử dụng thư viện của maxmines.min.js, hoặc bạn có thể chuyển qua thư viện cachedmine.min.js.
- Update method ```/user/list``` thêm 2 object *withdrawn* (số hashes đã rút) và *balance* (số dư hashes khả dụng, có thể rút)
## Update trang chủ (ngày 16/02/2020)
- Cập nhật special miner cho trang chủ MaxMines (lưu ý: bản special miner này không thể được gọi qua [Giao diện miner đơn giản](https://maxmines.com/documentation/simple-ui) của MaxMines)
- Chuẩn bị cho App MaxMines for Mobile mới.
## Thống kê chi tiết hơn cho Admin (ngày 13/02/2020)
- Làm tròn 2 chữ số thập phân thay vì xoá hẳn nó như trước đây, đem lại thống kê chi tiết và chính xác hơn.
## Little bugs (ngày 12/02/2020)
- **Nếu bạn là self-hosting, bạn cần chú ý các file được cập nhật:**
```
maxmines.min.js (Version: 1448110220, salt: Terrixus)
cachedmine.min.js (Version: 2048100220, salt: Fattez75)
```
## Fix bug shortlink (ngày 11/02/2020)
- Fix bug shortlink bị lỗi token
## Chạy thử nghiệm bản vá bảo mật tháng 2 (ngày 09/02/2020)
- Bản vá tháng 2 cập nhật thuật toán máy chủ mới.
- Bảo mật chống gian lận.
- MaxMines cập nhật thay đổi lớn trong thuật toán máy chủ và các file self-hosting, vì vậy nếu bạn không cập nhật các file lỗi thời các bạn sẽ bị mất tiền đã đào được. Mình sẽ không giải quyết các trường hợp sử dụng các file self-hosting lỗi thời bị mất tiền.
- **Nếu bạn là self-hosting, bạn cần chú ý các file được cập nhật:**
```
maxmines.min.js (Version: 1443090220, salt: Buxysh22)
cachedmine.min.js (Version: 1443090220, salt: Yokaberp)
```
## Cập nhật thời gian thay đổi xuất chi 1M (ngày 07/02/2020)
- Xuất chi được cập nhật mỗi 1 giờ của ngày chứ không phải theo giá trị không xác định như trước.
## Cập nhật Admin Dashboard (ngày 05/02/2020)
- Cập nhật Admin Dashboard mới cùng một số stuff
## Cập nhật giao diện MaxMines (ngày 03/02/2020)
- MaxMines cập nhật giao diện mới tràn 2 bên trang
- Làm nổi các thẻ tiêu đề trang.
## Cập nhât nhỏ UI Miner (ngày 02/02/2020)
- Ẩn nút stop khi đang đào, nút stop trước đây làm ẩn vài giá trị quan trọng
## Cập nhật MaxMines Captcha (ngày 30/01/2020)
- Cập nhật một số thông báo lỗi cho Captcha MaxMines
- Chuẩn bị update coin mới cho MaxMines, sẽ đào được nhiều coin cùng lúc
## Cập nhật UIMiner đơn giản (ngày 29/01/2020)
- Cập nhật EventListener cho UIMiner [chi tiết tài liệu](https://maxmines.com/documentation/simple-ui)  
``
Tất cả các sự kiện từ API JavaScript được chuyển tiếp đến UIMiner. Vì simple-ui.min.js được tải không đồng bộ, bạn phải đợi cho đến khi nó được tải để cài đặt EventListener của bạn. Sử dụng biến toàn cục onMaxMinesUIReady.
``
## Cập nhật mode (ngày 28/01/2020)
- Cập nhật 3 chế độ đào coin mới xem chi tiết tại [MaxMines Javascript Mode](https://maxmines.com/documentation/miner#miner-start)
  
Với **MaxMines.IF_EXCLUSIVE_TAB**  
``Công cụ khai thác sẽ chỉ bắt đầu nếu không có tab nào khác đang khai thác. Nếu tất cả các công cụ khai thác trong các tab khác bị dừng hoặc đóng tại một điểm sau đó, thì công cụ khai thác sẽ bắt đầu. Điều này đảm bảo rằng một công cụ khai thác luôn chạy miễn là một tab của trang web của bạn được mở trong khi giữ cho các kết nối lại nhóm tốn kém ở mức tối thiểu.
``  
  
Với **MaxMines.FORCE_EXCLUSIVE_TAB**  
``Công cụ khai thác sẽ luôn bắt đầu và ngay lập tức tắt tất cả các công cụ khai thác trong các tab khác chưa được chỉ định MaxMines.FORCE_MULTI_TAB.
``  
  
Với **MaxMines.FORCE_MULTI_TAB**  
``Công cụ khai thác sẽ luôn bắt đầu. Nó sẽ không thông báo sự hiện diện của nó với các tab khác, sẽ không tắt bất kỳ công cụ khai thác nào khác và không thể bị tắt bởi những công cụ khai thác khác.
``
- **Nếu bạn là self-hosting, bạn cần chú ý các file được cập nhật:**
```
maxmines.min.js (Version: 1659280120, salt: Fillano2)
cachedmine.min.js (Version: 1659280120, salt: Jejsbontol)
```
## Cập nhật nhỏ (ngày 27/01/2020)
- MaxMines và CachedMine cập nhật nhỏ một số thuật toán sửa lỗi nhỏ.
- Fix bug đồ thị thống kê tại dashboard MaxMines
- **Nếu bạn là self-hosting, bạn cần chú ý các file được cập nhật:**
```
maxmines.min.js (Version: 0813270120, salt: Hashplaz3)
cachedmine.min.js (Version: 0816270120, salt: Pitfule5)
```

## Cập nhật API (ngày 26/01/2020)
- MaxMines HTTP API update global errors: Mã lỗi ~~bad_request~~ được thay thế bằng các mã lỗi cụ thể hơn như **wrong_method** (phương thức kết nối không hợp lệ), **missing_input** (thiếu giá trị đầu vào), **not_found** (điểm cuối API không hợp lệ)
- Fix bug API **/user/withdraw**, **/link/create**
- Fix bug login **MaxMines for Mobile Speed Booster**
- Vẫn có vấn đề với VISA nên chưa thể publish app **MaxMines for Mobile Speed Booster**
- Phương thức JS API ***.getAutoThreadsEnabled()***, ***.setAutoThreadsEnabled()*** hiện vẫn đang được thử nghiệm nếu bạn sử dụng tính năng này mà project của bạn bị lỗi thì các bạn nên xóa nó đi nhé.
- **Nếu bạn là self-hosting, bạn cần chú ý các file được cập nhật:**
```
maxmines.min.js (Version: 1314260120, salt: Jgastease)
cachedmine.min.js (Version: 1318260120, salt: Blestone3)
```
