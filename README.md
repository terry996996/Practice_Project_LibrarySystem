智慧圖書館借還書系統個人實作練習

展示影片連結:

https://www.youtube.com/watch?v=uakbGfBK1YU

本機快速run版本啟動本專案步驟:

1.下載本專案至本地端

2.資料庫: 

Step1. 開啟DB資料夾

Step2. DB 資料夾中運行schema.sql 的程式 

Step3. DB 資料夾中運行data.sql 的程式 

Step4. DB 資料夾中運行procedures.sql 的程式 (USE LibrarySystem; 要先執行) 

3.後端:

Step1. 開啟backend資料夾

Step2. 到 src/main/resources中，application.properties組態檔內，改掉 SQL 的帳號和密碼 

Step3. 運行 Spring Boot 程式 

4.前端 

Step1. 開啟frontend資料夾

Step2. Terimal 輸入 npm install 

Step3. Terimal 輸入 npm run dev (啟動vue3專案) 

Step4. 網址列輸入http://localhost:5173/

Step5. 可順利造訪本網站~

網站介紹: (詳見-----智慧圖書館系統網頁地圖與功能簡要說明文件.pdf)

重要的功能列表 

1. 登入功能 
2. 登入時手機號碼欄位的資料比對 
3. 登入時密碼規則與驗證的比對 
4. 註冊功能 
5. 註冊時的欄位驗證與密碼規則 
6. 身分驗證機制(JWT、Spring Security) 
7. 借書功能(一位用戶可以借多本書，但同一種書只能借一本) 
8. 書籍狀態自動更新 
9. 分頁功能 
10. 還書功能 
11. 館藏書籍資料與借閱書籍資料的自動更新 
12. 借書日期與應還日期 
13. 登出功能
