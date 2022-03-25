# compornent（共通部品）

## イメージ画像

- xxx

## 概要

- button 要素と擬似要素を使用（ホバー時に左からスワイプ）
- `a`タグを使用すると w3c html チェックでエラーが出るので、`onclick`で実装してます。

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- button 要素配下に`div`、`a`タグを使うと w3c html チェックでエラーになります。
- button 要素を`a`タグの配下にしても同様に w3c html チェックでエラーになります。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> btn をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/

## portfolio url:

- https://c-0035.wtb.cfbx.jp/

## 参考にしたサイト

- CSS：ボタンホバー時に背景がスライドしたり領域を覆うアニメーションサンプル 10
- https://www.nxworld.net/10-css-hover-fill-animation.html
- ボタンをクリック(onClick )してメソッドを実行してみよう！ Javascript 超初心者の勉強
- https://programmer-life.work/javascript/onclick
- 【HTML】button タグでリンクを貼る方法
- https://tinyurl.com/ycus3c3m
- 【初心者でもわかる】疑似要素が表示されない時に確認する 7 つの事 ＆ 確認方法
- https://qiita.com/7note/items/7cb88dca241a22b54e5c

## 更新履歴

- 2022/3/25 button 要素と擬似要素を使用して表示（w3c html、css チェック対応済）→ 作成済

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
