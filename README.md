# front-env-static

## 実行手順
1. リポジトリをクローン
	```
	git clone git@github.com:ken17yama/front-env-static.git
	```
1. 開発環境に移動
	```
	cd front-env-static
	```
1. モジュールをインストール
	```
	npm install
	```
1. 開発環境の実行
	```
	npm run watch
	```
1. 開発環境の停止
	>Ctrl + c

## ディレクトリの説明
src：ここにソースを記述<br>
dist/css：コンパイルされたcssが出力される<br>
dist/img：普通に画像格納用<br>
dist/bundle.js：バンドルされたjsが出力される<br>
dist/*.html：HTMLファイルは個々の直下に格納する<br>
