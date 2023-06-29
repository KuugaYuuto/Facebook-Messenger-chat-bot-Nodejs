# Facebook-Messenger-chat-bot-Nodejs
- Một Facebook Messenger Chatbot đơn giản sử dụng Mesenger Platform (Node.js)

## Làm sao để chạy project ? 

### 1. Tải project này về
- Copy file .env.example -> Tạo 1 file .env tại thư mục gốc -> Điền tất cả ứng dụng khả thi vào file .evn
- Chạy "npm install" để test project tại localhost

### 2. Tạo 1 Heroku app, a Facebook Page, a Facebook App.
#### 2.1 Tạo Heroku app
- Triển khai ứng dụng lên Heroku ( cần phải setup dev dependencies:
heroku config:set NPM_CONFIG_PRODUCTION=false
)
- Config biến env (setup dev dependencies)
#### 2.2 Facebook Page
- Tạo 1 trang Facebook
- Config miền (Domains) trong Whitelisted (thêm miền (Domain) ứng dụng Heroku)
#### 2.3 Facebook App
- Tạo Facebook App (Messenger)
- Config webhook
