# Chatworkのメッセージ入力時に、Enterキー (or Enter + Shift)押下による誤送信を防ぐ方法

1. Chromeの拡張機能で以下をインストールする
- https://chrome.google.com/webstore/detail/scriptautorunner/gpgjofmpmjjopcogjgdldidobhmjmdbm

2. 図のとおりにアイコンをクリック
![aaaa](image1.png)

3. 開かれる画面にて以下の部分をクリック
![aaaa](image2.png)

4. 以下の通りにコードを入力
![aaaa](image3.png)

- コード入力欄  

```javascript
$('#_chatText').unbind('keyup');
```

- ホスト名入力欄  
  - Chatworkの場合： `www.chatwork.com`  
  - KDDI Chatworkの場合： `kcw.kddi.ne.jp`
