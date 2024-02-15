# js_pagination

## 完成イメージ


## 環境構築
yarnを初期化。パッケージのインストール
```
yarn init -y
yarn add sass --dev
```
package.jsonに以下を追加
```
  "scripts": {
    "scss": "sass src/scss:public/css"
  },
```
以下コマンドでsassをコンパイル
```
yarn scss
```
