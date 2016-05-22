# polymer-parts

## 起動方法

以下のコマンドでlocalhost:8888が立ち上がります。
※動作確認用にindex.htmlが配置してあります。

```
node server.js
```


## 主な使用技術
※bower.jsonの中身参照のこと

Google Polymer(webcmponents実現用polyfilライブラリ)  
Bootstrap(デザイン)  
bower(ライブラリ管理に使用)  
node(動作確認用サーバ)  

# importするHTMLの圧縮

```
npm install -g vulcanize
vulcanize -o build.html index.html
```

index.htmlに記載されているimportを解析してbuild.htmlを組み立てる。
なので、事前に全てのelementsをimportした上で、vulcanizeする。
