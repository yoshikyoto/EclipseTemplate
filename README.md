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

### fore
もともと foreach だったものを消して fore にリネームした
（インポートforeeachと重複する気がするので要調整）

### graph
Node, Edge, ワーシャルフロイド, ダイクストラなどをまとめたもの

### prime
素数を数え上げたりするために使うクラス

### rand
自作ランダムクラス

### regex
patternのmatcherをひっくるめた自作正規表現クラス

### ser
syserr と同じ。serrのほうがいいかも。

### sout
sysoutと同様

### uft
Union-Find Tree
