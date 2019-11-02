# Lifeforfun
1.從文山區慢慢向外擴展  
2.依食衣住行等分類，再從時間、地點排序  
3.不定期推撥自己和其他使用者的生活記錄  
4.每項生活記錄都有一定成就點數  
5.讓用戶之間在不同領域的積分排行  
6.也讓用戶間可以選擇性分享私人資訊 Ex.心跳、步數、電池資訊...  
7.共同行事曆...  
...  
...  
等等一堆可能寫不完也寫不出來的功能。  

# Preview
介面往後都還會大改，包括LOGO、Map圖片、積分表等等  
功能也偏向預覽性質  
導覽頁不像導覽頁  
流量問題檔案讀不到等等BUG Q  
持續修正中 暫不提供預覽  

## QUICK START  
npm i && npm start   

# 整體架構  
## 導覽頁  
App 介紹、下載、使用流程  
Bootstrap4 template 版型  
Jquery/Css3 互動  
Nodejs/Server、Express/Router (index.js)  
Firebase Login Logout  
FB/Google/Github/Youtube API  
Heroku/GoogleCloud  
GoogleAnalytics 目前平均日流量3 Q  

## 會員頁
主要實作
查看自己紀錄、其他使用者紀錄、排行等  
React => [基本環境架構](https://github.com/LinX9581/React-Webpack4-babel7)  
React-Router-Dom Fontend Router  
Nodejs/Express Backend Router  
MongoDB  
FB/Google/Github/Youtube API  
GoogleCloud  

Cloud Services Database => [基本環境架構](https://github.com/LinX9581/Note)  
...  
...  
## Android/IOS
累計自己成就、瀏覽其他使用者紀錄、排行等  
Expo 跨平台Android/IOS  
Nativebase => [基本環境架構](https://github.com/LinX9581/NativeBaseInit)  
React-native-router-flux Router  
...  
...  
# 主功能頁  
## index.html  
Bootstrap4  
Css3/Animatation  
Jquery plugin / Mansonry BigVideo Colorbox Chart  
...  
...  

## chat.html  
Nodejs Server  
Node_modules / Socket.io Express  
Css3/Animatation  

即時聊天室 分成所有頻聊天、私人聊天，記錄存放Mongodb。    
較詳細介紹可前往 [node-realtime-chatroom](https://github.com/LinX9581/node-realtime-chatroom)  

目前還沒和登入頁面做連動、只能暫時性建立使用者名稱進行聊天  
且動態新增聊天介面很吃流量，佈署上去常常造成Css跑走Q，往後會用Webpack打包，或者移至GCD。  

## login.html
Bootstrap4 template  
Jquery Plugin / Validate  
Firebase  
可以做簡易註冊、登入、第三方登入，較詳細介紹可前往 [firebase-login-validate](https://github.com/LinX9581/firebase-login-validate)  
只是信箱驗證、登入後續處理還沒實作Q  

## about.html
...  
...  
