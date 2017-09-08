# Chatworkのメッセージ入力時に、Enterキー (or Enter + Shift)押下による誤送信を防ぐ方法

- Chromeの拡張機能で以下をインストールする
 - https://chrome.google.com/webstore/detail/scriptautorunner/gpgjofmpmjjopcogjgdldidobhmjmdbm

<br><br>
- 図のとおりにアイコンをクリック
![aaaa](image1.png)
<br><br>

- 開かれる画面にて以下の部分をクリック
![aaaa](image2.png)
<br><br>

- 以下の通りにコードを入力
![aaaa](image3.png)

 - コード入力欄  
 ```javascript
 $('#_chatText').unbind('keyup');
 ```

 - ホスト名入力欄  
   - Chatworkの場合： `www.chatwork.com`  
   - KDDI Chatworkの場合： `kcw.kddi.ne.jp`
<br><br>

- 以下の通りにコンセント部分をクリック
![aaaa](image4.png)
