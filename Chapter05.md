# データ型の章

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
文字列　　　型:[例](#文字列(str)型)<br>
整数　　　　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E6%95%B4%E6%95%B0int%E5%9E%8B)<br>
浮動小数点　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E6%B5%AE%E5%8B%95%E5%B0%8F%E6%95%B0%E7%82%B9float%E5%9E%8B)<br>
日付　　　　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E6%97%A5%E4%BB%98datetime%E5%9E%8B)<br>
ブール　　　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E3%83%96%E3%83%BC%E3%83%ABbool%E5%9E%8B)<br>
配列　　　　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E9%85%8D%E5%88%97list%E5%9E%8B)<br>
タプル　　　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E3%82%BF%E3%83%97%E3%83%ABtuple%E5%9E%8B)<br>
辞書　　　　型:[例](https://github.com/Yoshi01O/Study_Python/blob/main/Chapter05.md#%E8%BE%9E%E6%9B%B8dict%E5%9E%8B)<br>
セット　　　型:[例](https://github.com/Yoshiaki010/Study_Python/blob/main/Chapter05.md#%E3%82%BB%E3%83%83%E3%83%88set%E5%9E%8B)<br>

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
### セット(set)型
```Python
i= {0,0,1,2}
print(i)
print(type(i))
```

