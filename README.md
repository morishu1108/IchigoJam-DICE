# IchigoJam-DICE
Source code for dice.Including practice for making new icon.
サイコロプログラム。POKEコマンドにて絵文字を作る練習を含む。

# サイコロの絵文字作成
2進数で1行ずつインデントをそろえてコーディングすることで絵文字の完成形が見えやすい。
<img width="544" alt="2019-01-15 6 19 49" src="https://user-images.githubusercontent.com/7673806/51141950-e7355c00-188d-11e9-8218-532f87ca8e00.png">

# 補足
* キャラクターコード224〜255の32文字、8x8のパターンをPOKEコマンドを使って自由に書き換え可能なので、224〜229をサイコロの1〜６までのアイコンに再定義  
* キャラクターパターン(#700-#7FF)
* RND(6)の乱数を用いて、ランダムにサイコロの目を決定

# 改造例
* サイコロが小さくて見えにくい場合は拡大表示してもよいかも  (VIDEO5)  
* 画面中央に表示し、サイコロの目がルーレットのようにアニメーションして、結果が表示されるとよりサイコロらしくみえるかも (LOCATE, GOTO)  

# License
[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)
