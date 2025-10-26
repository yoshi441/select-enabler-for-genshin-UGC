# User Select Enabler for act.hoyoverse.com

act.hoyoverse.comサイトで`user-select: none`を上書きして、テキスト選択を可能にするChrome拡張機能です。

## 機能

- act.hoyoverse.comのすべてのページで`user-select: text`を強制適用
- ページ読み込み開始時にCSSを注入するため、即座に有効化

## インストール方法

1. Chromeで`chrome://extensions/`を開く
2. 右上の「デベロッパーモード」を有効にする
3. 「パッケージ化されていない拡張機能を読み込む」をクリック
4. このフォルダを選択

## 使い方

インストール後、act.hoyoverse.comにアクセスすると自動的にテキスト選択が有効になります。

## ファイル構成

- `manifest.json` - 拡張機能の設定ファイル
- `content.css` - テキスト選択を有効化するCSSファイル
- `README.md` - このファイル
