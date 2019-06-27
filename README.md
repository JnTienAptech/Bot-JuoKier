# Bot-JuoKier

Tạo web bot trong vài phút với code BOT JuoKier

Code demo: joshoangtien.herokuapp.com.

Cài đặt và chạy thử tại máy cá nhân

Bạn cần có 1 tài khoản tại Heroku CLI.

Bạn cần cài đặt Node.js và Heroku CLI và Git.

Mở cmd chạy command sau:

$ git clone https://github.com/JnTienAptech/Bot-JuoKier.git # lấy bản code mẫu
$ cd BOT-ChuyHiep
$ npm install
$ npm start
Ứng dụng sẽ chạy tại localhost:3456.

Đưa code lên Heroku
Mở cmd chạy command sau:

$ heroku login # nhập email và mật khẩu tài khoản heroku 
$ heroku create myapp # myapp là tên app tại heroku
$ git push heroku master
$ heroku open
Tắt bật app
$ heroku ps:scale web=0 # Tắt app
$ heroku ps:scale web=1 # Bật app
# Lưu ý các lưu trữ cục bộ trên heroku sẽ mất khi bạn tắt app hoặc resart app
