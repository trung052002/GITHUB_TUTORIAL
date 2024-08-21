# Terms
Repository (Repo)
Branch
Conflict
Local
Remote


# Commands
- git init: khởi tạo repo
- git status: lấy ra tình trạng các file trong repo
- git add + (files_name): thêm những files chuyển bị được lưu
- git add .: chuẩn bị lưu lại tất cả file trong repo
- git reset: lấy ra các files trong phần chuẩn bị được lưu của "git add"
- git commit  -m "message": lưu lại thay đổi
- git log: lấy ra lịch sử commit
- git log --oneline
- git checkout <id commit (trong git log)>: quay trở về thời điểm commit trong quá khứ
- git checkout <branch_name (VD: master)>: quay trở lại thời điểm hiện tại/ hoặc di chuyển giữa các nhánh
- git branch: xem nhánh hiện tại
- git branch -b <branch_name> : tạo ra nhánh mới
- git merge <branch_name>: gộp branch
- git branch -d <branch_name>: xóa branch

- git push <link_repo> <branch_name>: đẩy lên repo trên github
- git remote add <ten_alias> <link_repo>: gán link repo bằng 1 cái tên, nên lúc sau chỉ cần git push <ten_alias> <branch_name>
- git push -u origin <branch_name>: đẩy branch lên remote
- git fetch origin: lấy các branch trên remote về
- git checkout -b <local_branch_name> origin/<remote_branch>: gán remote branch thành 1 local branch