HLT,LI,ST,CMP,B命令が正しく動作する前提で，それ以外の全命令をチェックします．
実行後のメモリの0~15までの各番地の値が全て0なら全命令が正しく動作したと思われます．
15番地に実行時のINPUTの値が入ります．
また，INPUTの値をOUTPUTします．
特定の番地の値が1なら，対応する命令が正しく動作していません．0なら，正しく動作しています．
以下のように対応しています．
0番地 => B(分岐していない))
1番地 => BE(Z=1で分岐していない)
2番地 => BLT(S=1で分岐していない)
3番地 => BLE(Z=1で分岐していない)
4番地 => BNE(Z=1で分岐している)
5番地 => ADD
6番地 => SUB
7番地 => AND
8番地 => OR
9番地 => XOR
10番地 => MOV
11番地 => SLL
12番地 => SLR
13番地 => SRL
14番地 => SRA

16番地 => LD


