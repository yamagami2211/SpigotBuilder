# SpigotBuilder
Seaoftrees08 氏が作成した [SpigotBuilder](https://github.com/Seaoftrees08/SpigotBuilder) を改造したものです。

![](https://imgix.yama2211.jp/SpigotBuilder/image2.png)

[改造版SpigotBuilder](https://d.yama2211.jp/SpigotBuilder/)

## 改造点
+ Java.exeのPathを指定できるように (Select Java.exe)でjava.exeを選択することでPathが自動で入ります。)
+ BuildToolsのコマンドラインフラグを指定できるようにした

### コマンドラインフラグについて
+ disable-certificate-check: HTTPS証明書チェックを無効にする
+ disable-java-check: Javaのバージョンチェックをしない
+ dont-update: Gitからアップデートをプルしない
+ skip-compile: コンパイルをスキップする
+ generate-docs: JavaDocを生成する(Bukkit用にのみ生成する)
+ compile craftbukkit: craftbukkitをビルドする
+ compile-if-changed: BuildToolsリポジトリで変更が検知された場合にのみコンパイルする。

# 改造版ダウンロード
[v1.2](https://github.com/yamagami2211/SpigotBuilder/releases/tag/v1.2)  
[v1.1](https://github.com/yamagami2211/SpigotBuilder/blob/master/src/SpigotBuilder/bin/Release/SpigotBuilder.exe?raw=true) / [v1.1](https://file.yama2211.jp/SpigotBuilder/SpigotBuilder.exe)  
今後はReleaseに上げます。

# 本家版
https://github.com/Seaoftrees08/SpigotBuilder
