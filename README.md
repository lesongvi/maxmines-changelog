# maxmines-changelog
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
