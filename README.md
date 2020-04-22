# 将棋ソフト「技巧」のMac用派生一時置き場

## 目的
Macで「技巧」エンジンを使用するには、gccのコンパイラーをインストールするなどして開発環境を構築してビルドする必要があります。しかし、他のアプリとgccのバージョンの不整合が発生してどちらかが動作しなくなる可能性もあります。
そこで、環境に依存しないよう、静的リンクでビルドできるようにしたものとビルドしてできた実行イメージをここに置いておきます。

## ビルド方法

```
cd Gikou
make mac_static
```

次の実行ファイルができます。
- bin/mac_static

## 動作環境
動作確認できている環境は、以下のとおりです。
- OS: macOS 10.13〜macOS 10.15
- ハードウェア等: MacBook Pro 2012/2019, VirtualBox

次のGUIで棋譜解析ができることを確認しました。
- [エンジン将棋盤](https://kisagai.com/downloads/engineshogiban/)

## 実行ファイルのダウンロード
本家のWindows用ダウンロードパッケージの中のWindows用実行ファイルをMac用実行ファイル(mac_static)に置き換えたものを置いておきます。
(v2.0.2-mac01以降のバージョン)
- ダウンロード場所: https://github.com/GoodMorningCall/Gikou/releases
---
GUIでエンジンを指定をする際は、ダウンロードしたフォルダの中のmac_staticを選択してください。