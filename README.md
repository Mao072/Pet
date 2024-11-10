# 專案結構
本專案組織為多個主要資料夾，各自負責不同的功能模組：

### 📂 backend
包含**資料庫**設定與管理資料及fetch政府API的**腳本**。
###  📂 breads
包含**辨識模型(desnet、yolo)**及處理影像分類任務的**API**。
### 📂 frontend
包含**前端網頁**程式碼。
### 📂 hono
負責路由與執行伺服器端操作的**後端框架**。

# 🐾 專案介紹
本專案透過前端介面結合 Python 辨識模型 API（使用 Flask 部屬），提供使用者一個互動式的狗品種辨識平台。主要功能包括：

### 1.狗品種辨識
使用者可以上傳狗的照片，按下預測按鈕系統會**自動裁切好圖片**、**預測**並**顯示品種**。
### 2.狗狗圖鑑與飼養知識
提供各種狗狗的**圖鑑資訊**與詳細的**飼養知識**，幫助使用者更了解不同品種的特性。
### 3.流浪動物查詢
利用抓取下來的流浪動物資訊製作**搜尋介面**，使用者可以**透過選擇品種及地區來篩選想要認養的流浪動物**，促進流浪動物的收養。
