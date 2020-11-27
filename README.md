# request-response-time

## 功能描述 (features)

- 依據請求產生 server log，包括時間 | 方法 | URL | 收到請求到送出回應的時間，格式：2019-5-17 18:51:12 | GET from / | total time: 8ms

## 安裝與執行步驟 (installation and execution)

- 下載專案到本地端

  ```
  git clone https://github.com/Ellen-ho/request-response-time.git
  ```

- 打開終端機進入到下載的資料夾

  ```
  cd request-response-time
  ```

- 執行指令安裝所需套件

  ```
  npm install
  ```

- 新增種子資料

  ```
  npm run seed
  ```

- 安裝完成後，執行 nodemon 啟動專案

  ```
  npm run dev
  ```

  或想直接使用 node 指定啟動專案，可以執行以下指令

  ```
  npm start
  ```

- 看到終端機顯示 "Express is listening on localhost:3000"，即可開啟瀏覽器在網址列輸入 localhost:3000 進入網站

## 環境建置與需求 (prerequisites)

- Node.js: v10.15.0
- express: v4.17.1
- dayjs: v1.9.6