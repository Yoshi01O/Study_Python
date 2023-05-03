# 入出力の章
こちらの章は、関数、入出力、データ型、四則演算、便利な関数についてです。てんこ盛り！
## コードを書く前に
コードを書く際は、必ず半角でお願いします。理由は後々説明します。

---

## 数値を表示してみよう
数値を表示するために、printという関数を使います。<br>
関数がわからない人のために関数について少し触れておきます。
### 関数とは？
「関数」を目にして、苦手意識を持ちがちですが、コードでの関数とは、指示や命令のことです。<br>
犬をしつける時、「おすわり」の掛け声や手振りを決めます。この掛け声や手振りが関数にあたります。<br>
また、掛け声や手振りが違うと犬が理解できないように、文字が違ったり、形式が1つでも違うと、エラーをはきます。<br>
### 実践
pythonでは、表示させる関数が「print()」になります。<br>
printは、()内を出力してくれるので、()の中に0を入れます。<br>
下のコードと同じか確認し、表示してみましょう！
```Python
print(0)
```
---

## こんにちわを表示してみよう
次に、文字である「こんにちわ」を表示してみましょう。
### 実践
()の中に「"こんにちわ"」を入れます。<br>
下のコードと同じか確認し、表示してみましょう！
```Python
print("こんにちわ")
```
次の節で、こんにちわを""で囲んだわけについて書かれています。

---

## データ型とは？
前の節では、文字を""で囲みました。しかし、数値の際は、何も囲みませんでした。
タイトルにある通り、この違いにはデータ型が関係しています。
いちから説明すると、変数には型があります。<br>
それぞれの型によって、決まりがあります。
例えば、文字は、文字列型で、"（ダブルクォーテーション）または、'（シングルクォーテーション）で囲む必要があります。
数値は、整数型で、特に囲む必要はありません。<br>
それら以外のデータ型一覧は、一番下に載せています。<br>
気になる方はこちらへ→https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E3%83%87%E3%83%BC%E3%82%BF%E5%9E%8B%E4%B8%80%E8%A6%A7<br>
## 型の注意点
数値を囲むと、文字列型になるので、演算処理が行われません。<br>


---

## 四則演算してみよう
次に、変数aに6を、変数bに3を代入し、変数aと変数bで、四則演算を試してみましょう！
```Python
a=6
b=3
print(a+b)#たし算
print(a-b)#ひき算
print(a*b)#かけ算
print(a/b)#わり算
```
---


## データ型一覧
文字列　　　型：文字、文字列<br>
整数　　　　型：小数点を含まない数値<br>
浮動小数点　型：小数点を含む数値<br>
日付　　　　型：日付<br>
ブール　　　型：TrueやFalse<br>
配列　　　　型：複数の要素を［］で囲んだデータ。","で区切る。要素の変更不可<br>
タプル　　　型：複数の要素を（）で囲んだデータ。","で区切る。要素の変更可能<br>
辞書　　　　型：複数の要素を｛｝で囲んだデータ。：の前後が対応している。","で区切る。要素の変更可能<br>
セット　　　型：複数の要素を｛｝で囲んだデータ。同一な要素が存在しない。","で区切る。<br>

---

### こちらから飛べます。
文字列　　　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E6%96%87%E5%AD%97%E5%88%97str%E5%9E%8B<br>
整数　　　　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E6%95%B4%E6%95%B0int%E5%9E%8B<br>
浮動小数点　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E6%B5%AE%E5%8B%95%E5%B0%8F%E6%95%B0%E7%82%B9float%E5%9E%8B<br>
日付　　　　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E6%97%A5%E4%BB%98datetime%E5%9E%8B<br>
ブール　　　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E3%83%96%E3%83%BC%E3%83%ABbool%E5%9E%8B<br>
配列　　　　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E9%85%8D%E5%88%97list%E5%9E%8B<br>
タプル　　　型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E3%82%BF%E3%83%97%E3%83%ABtuple%E5%9E%8B<br>
辞書型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#%E8%BE%9E%E6%9B%B8dict%E5%9E%8B<br>
セット型:例↓<br>
https://github.com/Yoshi01O/Study_Python/blob/main/Chapter01.md#set%E5%9E%8B<br>

---

### 文字列(str)型
```Python
i= "文字は"
print(i)
print(type(i))          
```
### 整数(int)型
```Python
i= 0
print(i)
print(type(i))          
```
### 浮動小数点(float)型
```Python
i= 1.0
print(i)
print(type(i))          
```
### 日付(datetime)型
```Python
import datetime
i= datetime.date.today()
print(i)
print(type(i))
```
### ブール(bool)型
```Python
i= 0==0 
print(i)
print(type(i))
```
### 配列(list)型
```Python
i= [0,1,2]
print(i)
print(type(i))
```
### タプル(tuple)型
```Python
i= (0,1,2)
print(i)
print(type(i))
```
### 辞書(dict)型
```Python
i= {0:"ゼロ",1:"イチ",2:"ニ"}
print(i)
cdprint(i[0])
print(type(i))
```
### set型
```Python
i= {0,0,1,2}
print(i)
print(type(i))

```
