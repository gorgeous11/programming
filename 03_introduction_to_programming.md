# プログラミング入門

## 準備

1. [Google Colaboratory](https://research.google.com/colaboratory/)で「Python 3の新しいノートブック」を作る．
1. ノートブックの名前を「03」に変える．

## 演習

**問題：** 次のコードを参考に，「こんにちは！」と10回表示させる．

```python
for i in range(5):
    print("Hello, World!")
```

**問題：** コメントを示す文字は何か．

```python
for i in range(5):
    # print("さようなら")
    print("Hello, World!")
```

**問題：** コメントを付ける．

```python
import math

a = 3
b = 4
math.sqrt(a**2 + b**2)
```

**問題：** 引用符を`"`から`"""`に変える．

```python
print("た
て
よ
み")
```

**問題：** バックスラッシュの字形を確認する．（「\」と「¥」の区別）

```python
print\
("Hello, World!")
```

参考：JavaScriptのコードを実行する．

```javascript
for (i = 0; i < 5; i++) {
    console.log("Hello, World!");
    console.log("こんにちは");
}
```

1. ブラウザでF12．
1. コンソール
1. コードをコピペする．

参考：[Pythonのデータ型](https://pycamp.pycon.jp/textbook/3_types.html)

**問題：** 以下の計算をする．算術演算子の意味がわかるか．

1. `2 + 2`
1. `2 - 2`
1. `2 * 2`
1. `7 / 3`
1. `7 // 3`
1. `7 % 3`
1. `2 ** 2`

**問題：** 演算子の優先順位を確認する．

```python
2 + 2 * 2
```

**問題：** 代入演算子「`=`」を使って，変数に代入する．（データに名前を付ける．）

```python
a = 100
a + 100
```

**問題：** 計算結果を変数に代入する．

```python
a = 100
b = a + 100
b
```

**問題：** インクリメント（1）

```python
a = a + 1
a
```

**問題：** インクリメント（2）

```python
a += 1
a
```

**問題：** aの値を10だけ減らす2通りの記法

**問題：** 浮動小数点数は厳密ではなことを確認する．（プログラミングでは`1`と`1.0`は違う．算数や数学ではもちろん同じ．）

```python
a = 9007199254740992
a + 1
```

```python
a = 9007199254740992
a + 1.0
```

```python
0.1 + 0.1 + 0.1
```

```python
a = 5999856
b = 99992800
c = 100000000
a ** 3.0 + b ** 3.0 == c ** 3.0
```

**問題：** 演算子を使う例を作る．

演算子|意味
-|-
`>`|より大きい（超過）
`<`|より小さい（未満）
`>=`|以上
`<=`|以下
`==`|等価
`!=`|非等価
`and`|かつ（論理積）
`or`|または（論理和）
`not`|でない（否定）

参考：命名の原則

1. 英単語を使う．単語間は「`_`」アンダースコア
1. ASCIIの英数字とアンダースコアだけを使う．（1文字に数字は不可）
1. [Pythonのキーワード](https://docs.python.org/ja/3/reference/lexical_analysis.html#keyword)は不可．

**問題：** エラーメッセージを日本語に翻訳する．

```python
10 / 0
```

```python
a = 1
 b = 2
```

**問題：** 「数値は偶数です」と出力されるように，`x`の値を設定する．

```python
x = 11
if x % 2 == 0:
  print("数値は偶数です．")
if x % 2 != 0:
  print("数値は奇数です．")
```

```python
x = 11
if x % 2 == 0:
  print("数値は偶数です．")
else:
  print("数値は奇数です．")
```

```python
x = 11
if x % 2 == 0:
  print("数値は偶数です．")
elif x % 2 != 0:
  print("数値は奇数です．")
```

**問題：** my_score（点数）とmy_absences（欠席）の値によって出力を変えるプログラムを完成させよ．

```python
my_score = 80
my_absences = 5

if ...
# 実行すると「欠席」と表示される
```

```python
my_score = 60
my_absences = 3

if ...
# 実行すると「合格」と表示される
```

```python
my_score = 40
my_absences = 3

if ...
# 実行すると「不合格」と表示される
```

```python
my_score = 40
my_absences = 6

if ...
# 実行すると「欠席」と表示される
```
