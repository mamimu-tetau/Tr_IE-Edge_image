## IEとEdgeでは、画像を50%以上縮小するとギザギザになる件

#### 症状
* 先日デザイン＆コーディングしたサイトのブラウザチェックで、ロゴがIEとEdgeで信じられないほどギザギザで表示されてしまいました（特にロゴなので「これはまずい」ということになり…）。

#### 原因
* 色々調べた結果、書き出した画像をコーディングの段階で50％以上縮小して設定すると、ギザギザになってしまうとのことでした。

#### 対応
* クライアントさんからいただいたロゴデータをそのまま使わず、表示させたい等倍で書き出したら、ギザギザ無く表示されました。
```
以前、ブラウザで画像がボケて表示された時、「大きく書き出せば良い」と言われてから、「大きければくっきり表示されて良いだろう」
ということで、基本大きめに書き出していたのですが、この一件から大きければ良いというものでも無いな、と思いました。
```
