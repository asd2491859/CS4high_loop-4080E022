# 10-1
print("hello!")
print(3*2*(17-2.1))
print("abc"+"def")

```

```
1.print("5*2*(17-16)")會印出甚麼結果:
(A)0   (B)10  (C)出現錯誤,無法印出  (D)5*2*(17-16)
答案:D ("" < 貼上符號內的算式)


2.print(7*2*(22-15))會印出甚麼結果:
(A)0   (B)98  (C)出現錯誤,無法印出  (D)3*2*(17-2)
答案:B( 直接計算 )


3.print("hello""+""olleh")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)hello+olleh  (C)hello""+""olleh  (D)helloolleh
答案:B 


4.print("he"+"llo")會印出甚麼結果:
(A)出現錯誤,無法印出   (B)he+llo  (C)he""+""llo  (D)hello
答案:D

5.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z",3))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz
答案:C ( 前3個a取代 )

6.底下程式執行後結果為何?
word = "arttarataaa"
print(word.replace("a", "z"))
(A)出現錯誤,無法印出   (B)arttarataaa  (C)zrttzrztaaa (D)zrttzrztzzz  
答案:D

7根據底下程式,下列敘述何者為非?[複選題]
ames = ['龍', '聖']
index = 0

while index < len(names):
    name = names[index]
    print(name)
    index = index + 1
    
(A)len(names)=2  
(B)names[1]是 龍 
(C)程式執行完後,index最後為2
(D)如果把條件改成 index > len(names),中index最後為2
答案:

```
註解:字串的replace()有何用途?

str.replace(old, new[, max])

Python replace() 方法把字串中的 舊字串(old) 替換成 新字串(new)，
如果指定第三個參數max，則替換不超過 max 次。

[參考資料]https://www.runoob.com/python/att-string-replace.html

[用途]串改信件
word = "Mydeargreatteacher, this is my work. My name is HIHIHIHI "
print(word.replace(" HIHIHIHI", "547547"))

```
答案是:Mydeargreatteacher, this is my work. My name is547547 

```
word = "artaarjjjj"
print(word.replace("a", "j",2))
```
```
答案是:jrtjarjjjj
```
```

