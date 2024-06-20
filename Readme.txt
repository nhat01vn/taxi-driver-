Hướng dẫn cài đặt cho macos

Máy phải cài đặt yarn, nodejs

Đăng ký account firebase
  Tạo realtime database
  Tạo Storage để lưu avatar user
  Tạo messaging để làm push notification
  Go to settting => service account => generate new private key => tạo file serviceAccountKey.json
Đăng ký account google map API
  Enable API server for google map
  Create API key

Đối với taxi_dispatcher_backend-master
  Connect database để lấy thông tin username và password
  cp .env.template .env
  Thay thế các biến env phù hợp với môi trường
  yarn install
  yarn serve

Đối với taxi_frontend-master
  cp .env.template .env && yarn install && yarn serve

Đối với taxi_driver_app-master và taxi_user_app-master và taxi_dashboard-master
  Install flutter
  https://www.youtube.com/watch?v=f09c-nw15K8
  Kiểm tra các cài đặt phụ thuộc bằng lệnh flutter doctor, nếu thiếu denpendencies gì cài đặt vào
  Cài đặt android studio
  Thay thế google API trong project
  Thay thế FirebaseCloudMessaging key trong Project
  Build app and run driver and user

  Build run app admin: flutter run -d chrome --web-renderer html

Trong Source.zip gồm có:
- dashboard: là trang web thống kê các hoạt động kinh doanh
- driver: là app driver
- user: là app client
- frontend: là website call center
- backend: là toàn bộ backend 