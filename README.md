# simple_sample

[計算機科学実験及演習3(HW)](http://www.lab3.kuis.kyoto-u.ac.jp/~takase/le3a/)の仕様に準拠して記述されたサンプルプログラム集です．

## InstructionTest

SIMPLE仕様で規定されている命令のテストプログラム(txtおよびmifファイル)です．

テスト対象の命令や期待される動作などの詳細は，各ディレクトリのreadme.txtを参照してください．

## BubbleSort
### BubbleSort.txt

SIMPLE用のアセンブリ言語で書かれたバブルソートのソースコードです。

あらかじめ与えられたデータに対してソートを実行し、SIMPLEのOUT命令で昇順にデータを出力します。

### BubbleSort.mif

BubbleSort.txtを[simple_simulator](https://github.com/kuis-isle3hw/simple_simulator)でアセンブルしたものです。

プログラムは0x000から0x3FF(0から1023)に、データは0x400から0x7FF(1024から2047)に格納されています。

## Fibbonacci

- [フィボナッチ数列](https://ja.wikipedia.org/wiki/%E3%83%95%E3%82%A3%E3%83%9C%E3%83%8A%E3%83%83%E3%83%81%E6%95%B0)をOUT命令で順に出力します．
- IN命令で受け取れる値は1以上の整数です．
- [simple_simulator](https://github.com/kuis-isle3hw/simple_simulator)に同梱されているsample.txtと同じものです．

## 注意点など

- [MIT License](LICENSE) です．この条項下で自由にご利用ください．また，本ツールの使用にあたって何か問題が起きても，スタッフは一切の責任を負いません．
- [SIMPLEアーキテクチャの基本命令セット](http://www.lab3.kuis.kyoto-u.ac.jp/~takase/le3a/#SIMPLE)のみに対応しています．
  - この範囲内でbugなどあればぜひ [Issue](../../issues) で教えてください．
  - この範囲内で機能追加や改善があれば [Pull request](../../pulls) も歓迎します．
  - 課題でもある独自の改良や拡張については，対応しません．
