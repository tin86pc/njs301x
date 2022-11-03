# njs301x
Nơi lưu các bài lab của môn NJS301x

lab2.1: Tạo ra file hello.txt với nội dung Hello from node.js
 
//chạy code
node first-app.js



// Gỡ bỏ tài khoản git cũ
git config --global credential.useHttpPath true


// khơi tạo
git init

// Tạo commit
git add .
git commit -m "bat dau njs301x"

// Tạo branch
git branch -m lab

// Kết nối đến kho git
git remote add origin https://github.com/tin86pc/njs301x.git

// Up lên kho git
git push -u origin lab


// Xóa branch trên máy
git branch -d lab

// xóa branch trên kho git
git push origin --delete lab