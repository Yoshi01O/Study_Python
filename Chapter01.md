<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
</head>
<body>
<h1>入出力の章</h1>
<p>こちらの章は、関数、入出力、データ型、四則演算についてです。てんこ盛り！</p>
<h2>コードを書く前に</h2>
<p>コードを書く際は、必ず半角でお願いします。理由は後々説明します。</p>
<h2>実行環境が整っていない人</h2>
<p>[こちら]()では、VScodeとcmd（コマンドプロンプト）を使って、実行する方法は載せてあります。</p>

---

<h1>出力の節</h1>
<h2>数値を表示してみよう</h2>
<p>数値を表示するために、`print()`という関数を使います。<br>
関数がわからない人のために関数について少し触れておきます。</p>
<h2>関数とは？</h2>
<p>「関数」を目にして、苦手意識を持ちがちですが、コードでの関数とは、指示や命令のことです。<br>
犬をしつける時、「おすわり」の掛け声や手振りを決めます。この掛け声や手振りが関数にあたります。<br>
また、掛け声や手振りが違うと犬が理解できないように、文字が違ったり、形式が1つでも違うと、エラーをはきます。<br></p>
<h3>実践</h3>
<p>printは、()内を出力してくれるので、()の中に0を入れます。<br>
下のコードと同じか確認し、実行してみましょう！
```Python
print(0)
```
</p>
<h2>こんにちわを表示してみよう</h2>
<p>次に、文字である「こんにちわ」を表示してみましょう。</p>
<h3>実践</h3>
<p>()の中に"こんにちわ"を入れます。<br>
下のコードと同じか確認し、実行してみましょう！
```Python
print("こんにちわ")
```
</p>
<h2>データ型とは？</h2>
<p>前の節は、文字を"で囲みました。数値の際では、囲みませんでした。
タイトルにある通り、この違いにはデータ型が関係しています。
データには型があります。また、その型によって、約束事があります。<br>
例えば、文字のデータは文字列型となり、"（ダブルクォーテーション）または、'（シングルクォーテーション）で囲む必要があります。<br>
※"'のように、異なる記号で囲むとエラーになるので、同じ記号で囲んでください。
数値は、整数型で、囲む必要はありません。<br>
それら以外のデータ型一覧は、[こちら](https://github.com/Yoshiaki010/Study_Python/blob/main/Chapter05.md)<br></p>
<h2>型の注意点</h2>
<p>数値を囲むと、文字列型になるので、演算処理が行われません。<br></p>

---

<h1>入力の節</h1>
<h2>データを受け取り、表示してみよう</h2>
<p>データを受け取る際は、`input()`という関数を使います。受け取るだけなので、変数に代入すると、扱いやすくなります。<br>
また、読み込まれたデータ型は、文字列型となります。</p>
<h3>実践</h3>
<p>読み込んだデータをxに代入し、表示させます。<br>
下のコードと同じか確認し、実行してみましょう！
```Python
x= input()
print(x)
```
</p>
<h2>四則演算してみよう</h2>
<p>四則演算とは、たし算ひき算かけ算わり算のことです。</p>
<h3>実践</h3>
<p>aに6を、bに3を代入し、aとbで、四則演算を試してみましょう！
```Python
a=6
b=3
print(a+b)#たし算
print(a-b)#ひき算
print(a*b)#かけ算
print(a/b)#わり算
```
</p>
<p>[次の章へ行く](https://github.com/Yoshiaki010/Study_Python/blob/main/Chapter02.md)</p>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
  <title>CaféCandle</title>
</head>
<header></header>
<body background ="http://www.tmyun.com/mid/yun_1986.jpg">
<p>*このカフェは、実在しません。</p>
<h1 class ="title" style="text-align:center">CaféCandle</h1>
<h3 class ="subtitle" style="text-align:right"　vertical-align = "top"><font color="#fff">ココの空はあなた色</font></h3><br/><br/><br/>
  <p style="text-align:center"><font color = "#fff">日々頑張り、疲れているあなたに<br>最上級の癒しをお届けします<br>好きな景色、好きな空間誰もいないこの場所で<br>この非日常を体感しませんか？</font></p><br/><br/>
  <h2 style="text-align:center"><u class="under"><font color="#fff">営業時間</font></u></h2>
  <h4 style="text-align:center"><font color="#fff">14:00 - 24:00</font></h4><br/><br/>
<h2 style="text-align:center"><u class="under"><font color="#fff">アクセス</font></u></h2>
  <h4 style="text-align:center"><font color="#fff">恵比寿駅から徒歩５分<br>広尾タワー8階</font></h4>
</body>
</html>
