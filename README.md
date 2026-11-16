# 対戦リバーシ

ブラウザで遊べるリバーシです。オンライン対戦（ルームコード式）、同じ画面での2人対戦、CPU対戦の3モードがあります。

## 遊ぶ

https://peragami.github.io/reversi/

- オンライン対戦: 「ルームを作る」で6文字コードを発行し、相手に伝えて参加してもらいます。通信は Firebase Realtime Database の HTTPS REST（ポーリング）です。
- オフライン: 同じ画面での2人対戦とCPU対戦は通信なしで遊べます。

## 仕組み

単一の `index.html` だけで動く静的ページです。GitHub Pages で公開しています。
