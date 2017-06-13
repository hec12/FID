完備辞書 

ビット列に対する定数時間のrankとselectを実現できるデータ構造

- rank(pos,digit): ビット列の先頭から位置 pos までに digit のビットの個数   
- select(idx,digit): ビット列の先頭から見て、idx+1 個目の digit のビットの位置   

Fully Indexable Dictionary

This data structure can realize constant time "rank" and "select" for the bitstream.

- rank(pos,digit): # ```digit``` bits from the beginning to position ```pos``` of the bitstream.
- select(idx,digit): the position of ```idx+1``` th `digit` from the beginning of the bitstream.

This software is released under the MIT License, see LICENSE.txt.
