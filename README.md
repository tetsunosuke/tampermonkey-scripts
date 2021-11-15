# tampermonkey-scripts

Chrome 拡張機能である Tampermonkey （[Chrome Web Storeはこちら](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo/related?hl=ja)）で使えるスクリプトを活用して社内で便利であろうツールを作成したものです

みんなが使えそうなものを作ったり、そのアイデアがあればぜひ教えて下さい

## Tampermonkey とは

スクリプトを書くことでブラウザの挙動をカスタマイズする GreaseMonkey という仕組みを使うことができます。


## インストールと初期設定

### 拡張機能本体のインストール

[TampermonkeyのChromeWebStore](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo/related?hl=ja) を新しいウィンドウで開き、「Chromeへ追加」ボタンを押してインストールします

### 初期設定


- [zipファイル](https://github.com/tetsunosuke/tampermonkey-scripts/releases/download/v1.0/tampermonkey-1.0.zip)をダウンロードしておきます（解凍する必要はありません）
- 拡張機能のオプション画面を開きます
    - URLに `chrome-extension://dhdgffkkebhmkfjojejmpbldmpobfkfo/options.html#nav=utils` を入力します
    - `ユーティリティ` タブを開きます
- `ZIP` の `インポート` から先程ダウンロードしたzipファイルを選択してダウンロードしたファイルをインポートします

## 不要な機能を無効化する

人によっては使わない拡張を誤って起動しないように無効化したい人もいると思います。下記の手順で無効化できます

- 拡張機能のオプション画面を開きます
    - URLに `chrome-extension://dhdgffkkebhmkfjojejmpbldmpobfkfo/options.html#nav=utils` を入力します
    - `インストール済みUserScript` タブを開きます
    - `有効` 欄にあるスイッチで On/Off を切り替えます


## 配布スクリプトの更新方法

こちらは初期インストール後にスクリプトの更新があった場合の手順です。更新の案内があった際に実行します。

- Chromeのメニュー `その他のメニュー` から `拡張機能`
- [拡張機能のユーティリティ](chrome-extension://dhdgffkkebhmkfjojejmpbldmpobfkfo/options.html#nav=utils) を開く
- 画面下部`URL からインストール` に更新用にもらったURLを貼り付けてインストールを押す
- `再インストール`を押す
- （再読み込みが必要かも？）

## スクリプトの自作方法、修正方法

[Development How-To](./development_how_to.md) をごらんください


## その他

（何かあれば書く）
