# Alpha Interview Assignment (1)

ほとんど以下のサイトのコードを理解しながら写して、UIを少し変更しただけです。

https://hitotsu-eye.com/python_02/

## 概要
Pythonのtkinterライブラリを使用したオセロゲーム。

python3とnumpyがインストールされている環境でothello.pyを実行するとプレイ可能。

ユーザーはマウスクリックで石を置くことが可能。

### 主な機能

プレイヤーが二人いる場合、対戦可能なオセロ

盤面のgui表示

ゲーム終了時の勝敗判定

白と黒の現在の個数の表示

以下実行した際の動画です。
(途中部分はカットしています。)



### この後実装してみようと思うこと

・対戦ができるcpuの作成　（初級、中級、上級の三つの強さを用意）

-初級：石を置ける場所にランダムで置く

-中級：以下のアルゴリズムに基づき石を置く

  ・できるだけ角を取る、また取られないようにする
  
  ・序盤はできるだけ少ない数の石を取るようにする
  
-上級：ディープラーニングを用いたcpu

pandasを用いてオセロ連盟が公開しているオセロの棋譜データベースWTHOR（csv形式）を読み込み、8*8（盤面の数）を入力、8*8を出力、チャンネル数2(自分と相手のデータ)の学習データを作成。

現在の盤面が入力データとし、その時に打たれた手を教師データとする。

ニューラルネットワークのモデルを作成し、学習させたい。


### 以下は実行した際の動画です。（一部編集でカットしています）

https://github.com/renya-create/Alpha/assets/83385126/3fc7073e-7a6a-440c-8ecc-cfaf9a3bdcdb



