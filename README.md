# MONACA GUIDE & SIMPLE TAKING NOTE

### INSTALLATION
`npm install -g monaca`

> Khởi tạo 1 project
`monaca create helloworld`

* Sau khi khởi tạo sẽ có phần thêm chọn framwork cho monaca

### DEBUG & BUILD LOCAL DEV
``
* Thêm platform (Android, IOS)

`cd helloworld`

* Android

`cordova platform add android`

* iOS

`cordova platform add ios`

* Chạy app

`monaca run` 

> Có thể chọn platform đằng sau ko thì mặc định sẽ chọn android

`monaca run android`

`monaca run ios`

* Build App ra file Debug

`monaca build android`

* Build App ra file Release 

`monaca build --release android`

### DEBUG & BUILD ONLINE

Nếu build remote thì yêu cầu cần nhập tài khoản MONACA 

`monaca login`

Đăng ký MONACA sau đó có thể build remote 

`monca remote build android`

> Điều này cho phép bạn tạo project trên phần server của Monaca quản lý ( trong phần tài khoản của bạn sau khi đăng nhập vào Monaca)




