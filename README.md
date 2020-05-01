# simple_sample
SIMPLE向けサンプルプログラム

## BubbleSort
### BubbleSort.txt

SIMPLE用のアセンブリ言語で書かれたバブルソートのソースコードです。

あらかじめ与えられたデータに対してソートを実行し、SIMPLEのOUT命令で昇順にデータを出力します。

### BubbleSort.mif

BubbleSort.txtを[simple_simulator](https://github.com/kuis-isle3hw/simple_simulator)でアセンブルしたものです。

プログラムは0x000から0x3FF(0から1023)に、データは0x400から0x7FF(1024から2047)に格納されています。
