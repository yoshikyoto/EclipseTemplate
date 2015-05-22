# Eclipse テンプレート XML

## はじめに

主にプロコン用
Java用


## インポート/エクスポート

EclipseのPrefrences > Java > Templates

* Import で XML ファイルを指定してインポート
  * 自作のものはインポートすると重複してしまうので注意
* Export は、ExportしたいものをチェックしてExport


## 自作テンプレート一覧

* memo: アルファベット順にすること

### arrcomp
配列の中身を見て昇順に並び替えるためのComparator

```java
Arrays.sort(arr, new ArrayComp())
```

### br
標準入力のBufferedReader

### countpair
aの中から、合計がborderを超えるペア（重複除く）の数を数える

### digit
int nの桁数を求める

### dist
squareを入れてから入れる。距離を測るライブラリ

### fore
もともと foreach だったものを消して fore にリネームした
（インポートforeeachと重複する気がするので要調整）

### gcd
最大公約数を求める関数

### graph
Node, Edge, ワーシャルフロイド, ダイクストラなどをまとめたもの

### iscross
線分が交差しているかどうかを判定するクラス

### islower
charが小文字英字かどうか確かめる関数

### isparallel
線分が並行かどうかを求める関数

### isupper
charが英語大文字ならtrueを返す関数

### mcomb
DPで書かれたCombination (long)
intではオーバーフローすることがある。

### mcombint
DPのCombination (int)

### prime
素数を数え上げたりするために使うクラス

### rand
自作ランダムクラス

### regex
patternのmatcherをひっくるめた自作正規表現クラス

### scanner
標準入力scannerの初期化

### ser
syserr と同じ。serrのほうがいいかも。

### sout
sysoutと同様

### square
int と double の2乗の関数

### swap
配列のi番目とj番目の値を入れ替える関数

### tolower
charを小文字に変える関数

### toupper
charを大文字に変える関数

### uft
Union-Find Tree
