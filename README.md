B4X實驗: 快速的開發B4J Web Server網頁服務器(利用B4J . Jetty開源 ).並寫建立一個簡單的網頁/猜數字網頁(javascript) websocket


參考資料:
https://www.b4x.com/android/forum/threads/server-building-web-servers-with-b4j.37172/#content
https://www.b4x.com/b4j/help/jserver.html#server

使用jServer
'注意使用non-UI模式開發...不然執行時.會有一堆錯誤的(害我花一整天找問題)



1.websocket使用 大致講解...
https://zh.javascript.info/websocket

因為B4X websocket 包裝過了..


2.操作



3.程式碼講解
client
http://192.168.1.162:8080/guessmynumber_ws/index.html
jquery.js
b4j_ws.js
index.html

//一旦 socket 被建立，我们就应该监听 socket 上的事件。一共有 4 个事件：
//open —— 连接已建立，
//message —— 接收到数据，
//error —— WebSocket 错误，
//close —— 连接已关闭。


server
jserver
WebSocket
JQueryElement

程式碼
https://github.com/eric19740521/b4x20220221





