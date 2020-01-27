# maxmines-changelog
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
