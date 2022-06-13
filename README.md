làm quen với git và github:

# Terms
Repository(Repo)
Branch: Cành - một dự án có thể có nhiều cảnh khác nhau ,và branch mặc định của chúng ta là master

# Commands
- git init : lệnh này làm cho dự án của chúng ta trở thành một Repository
- git status: lệnh này cho chúng ta thấy được trạng thái dự án của mình như những thay đổi trên dự án...
- git add : cho phép chúng ta lưu lại thời điểm hiện tại của dự án 
   // git add + tên file mà chúng ta cần chuẩn bị lưu ;;; ví dụ : git add index,html
   hoặc trong trường hợp dự án của chúng ta có nhiều file thì chúng ta dùng:
   // git add .: để chuẩn bị lưu lại tất cả các file trong dự án

- git reset: chúng ta muốn lấy ra file chuẩn bị lưu 
- git commit : lệnh chính thức lưu 
  // lệnh này chúng ta cần phải ghi chú lại một chi tiết trước khi lưu để chúng ta biết được quá trình trên dự án của chúng ta đang ở đâu hoặc chúng ta đang làm một feature gì đó
  // git commit -m ' ghi chú nằm trong đây'

- git log: lệnh này giúp chúng ta xem lại thời điểm chúng ta đã lưu
  /// ghi chú: bấm phím 'q' để thoát quá trình xem log
- git log --oneline: lệnh này sẽ gọn hơn lệnh trên

- git checkout {id commit} : nếu chúng ta muốn trở lại thời điểm ban đầu của commit
- git checkout {branch name}: nếu chúng ta muốn trở lại thời điểm hiện tại của commit
- git branch: chúng ta sẽ thấy được branch mặc định của chúng ta là {master}
- git checkout -b{branch name}: để tạo ta 1 branch mới 
  // trước khi tạo ra branch mới, chúng ta cần dùng lệnh git add . để lưu lại , 
  và git commit -m'second commit' để cập nhật trạng thái của dự án 
  sau đó sử dụng lệnh trên để tạo ra branch mới
- git push : đẩy code lên github

