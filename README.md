# EasyCapture (WIP)
ソフトウェア名称は仮名。もう少しまともな名前にそのうち変更する。

## 前提
Windows。
高解像度モニタで表示倍率を変更している場合に既存キャプチャソフトがうまく動かないので自作した。

## 現バージョン
完全に私用。汚い。そのうちリファクタリング&汎用化する。

## 実行ファイル
今のところ実行ファイルは配布していません。各自 Visual Studio 2015 等でビルドしてください。

## 使い方
Ctrl + F2 を押すと現在のアクティブウィンドウをまるごとキャプチャし、C:\_tmp\capt_YYYYMMDD_hhmmss_nn.png という形式でファイル保存を行う。
保存先を変更したい場合は各自でソース書き換えてビルドしてください。
