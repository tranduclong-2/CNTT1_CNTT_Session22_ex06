# Bài 6: Ứng dụng AI trong khắc phục lỗi Git Permission Denied
### 1. Prompt 3 thành phần
**Vai trò:** Bạn là một người hướng dẫn lập trình cho sinh viên mới học Git.

**Vấn đề:** Terminal báo lỗi `error: open(".git/FETCH_HEAD"): Permission denied` khi tôi đẩy code lên GitHub.

**Yêu cầu:** Hãy giải thích nguyên nhân bằng ngôn ngữ đơn giản và hướng dẫn cách sửa từng bước, phù hợp với người mới học.

### 2. Cách khắc phục lỗi
- Đóng Terminal hoặc VS Code đang mở.
- Mở PowerShell bằng quyền Run as Administrator.
- Di chuyển đến thư mục dự án.
- Thử chạy lại lệnh Git.
Ví dụ:
git push
Nếu vẫn lỗi, cần kiểm tra quyền truy cập thư mục .git thay vì tiếp tục chạy quyền Administrator.
### 3. Tin nhắn nhờ giảng viên hỗ trợ
**Tiêu đề: Nhờ hỗ trợ lỗi Git Permission Denied**

Em chào thầy/cô,

Trong quá trình đẩy code lên GitHub, em gặp lỗi:

`error: open(".git/FETCH_HEAD"): Permission denied`

**Context:** Em đang sử dụng Git trên Windows.

**Expected:** Đẩy code lên GitHub thành công.

**Actual:** Terminal báo lỗi Permission denied và không thể đẩy code.

**Log:** `error: open(".git/FETCH_HEAD"): Permission denied`

**Đã thử:** Chạy lại Terminal bằng quyền Administrator nhưng vẫn chưa khắc phục được.

Em mong thầy,cô hướng dẫn em cách xử lý lỗi này.

Em cảm ơn thầy/cô ạ!
