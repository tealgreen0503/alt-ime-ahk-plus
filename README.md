# alt-ime-ahk-plus

## 概要

左右 Alt キーの空打ちで IME を OFF/ON する AutoHotKey スクリプトです。

- 左 Alt キーの空打ちで IME を「英数」に切り替え
- 右 Alt キーの空打ちで IME を「かな」に切り替え
- Alt キーを押している間に他のキーを打つと通常の Alt キーとして動作

[本家様](https://github.com/karakaram/alt-ime-ahk)のスクリプトを改良して下記の機能を追加しました。

- コロンとセミコロンの入力をスイッチ
- 右 Shift キーの空打ちでアンダーバーを入力（Mac-JIS likeに）


## 動作環境

- Windows10
- Windwos11

## 使い方

[releases](https://github.com/tealgreen0503/alt-ime-ahk-plus/releases) から alt-ime-ahk-plus.exe をダウンロードし、alt-ime-ahk-plus.exe を好きな場所に置き、起動してください。 タスクトレイに常駐します。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは alt-ime-ahk-plus.exe を削除するだけで OK です。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに

IntelliJ IDEA など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。

オフのまま使うと Alt キーを離した際に alt-ime-ahk-plus.exe がエラー終了します。

## ブログの紹介ページ（本家様）

[Altの空打ちで日本語入力(IME)を切り替えるツールを作った](http://www.karakaram.com/alt-ime-on-off/)

