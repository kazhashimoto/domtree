# domtree

## Install
domtreeはNode.jsの以下のパッケージを使用しています。記載のバージョンは動作確認に使用したバージョンです。
- [commander](https://github.com/tj/commander.js/) v8.0.0
- [jsdom](xx) v16.6.0
- [debug](xx) v4.3.2

## Usage
コマンドライン引数にローカルのHTMLファイルもしくはリモートのHTMLファイルを指定してdomtree.jsを実行します。
```
$ node domtree.js examples/index.html
$ node domtree.js https://github.com/about
```

## Debug
debug modeを有効にして実行すると詳細なログが標準エラーに書き出されます。
```
$ DEBUG=* node domtree.js ...
```
