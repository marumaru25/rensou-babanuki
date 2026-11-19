# 🃏 連想ババ抜き（Firebase版）

相手のカードを引いて、手札の単語を「つながる言葉」でまとめて捨てていく連想ゲーム。ブラウザだけで遊べます。

▶️ **遊ぶ**: https://marumaru25.github.io/rensou-babanuki/

- 3〜8人（CPU追加OK・CPUの連想と投票は Gemini が判定）
- ルームコード（4桁）／招待リンク／公開ルーム一覧
- チャット・スタンプ・効果音・観戦・結果シェア
- ホストが抜けても自動で引き継ぎ

## 構成
- `index.html` … ゲーム本体（1ファイル・バニラJS）
- Firebase Realtime Database（通信）＋ 匿名認証
- Firebase AI Logic（Gemini Developer API）
- `database.rules.json` … データベースのセキュリティルール

GRAVITY版は [rensou-babanuki-gravity](https://github.com/marumaru25/rensou-babanuki-gravity)。
