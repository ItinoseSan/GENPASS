[![Build Status](https://travis-ci.org/ItinoseSan/GENPASS.svg?branch=1129)](https://travis-ci.org/ItinoseSan/GENPASS)
# Gen-Pass　
Java password generator.
# How to use
### 1.Clone this repository
https
```
git clone https://github.com/ItinoseSan/GENPASS.git
```
ssh
```
git clone git@github.com:ItinoseSan/GENPASS.git
```
### 2.You can generate 20charactor password on Java console.
generate password
```
genpass g password
```
generate number password
```
genpass g -number password
```
generate mix password
```
genpass g -mix password
```
# Demo dump
```
genpass>genpass g password
X5Y3BV6SOTXpzLMTnBPb
You could generate password.Please set the name of password
FooBar
Generated password is saved on CSV file.
```

# Contributing
I welcome it.but if you pullrequest to this repository,you should write description of pullrequest content in English.


jp 
# Gen-Pass
Javaで作ったパスワード生成アプリです。生成されたパスワードは名前をつけてcsvファイルに保存できます。使いかたは簡単なので上の説明を呼んでください。
# 今後
ランダム文字列生成をラッパーに頼ってるので自力で実装しようか検討中です。



