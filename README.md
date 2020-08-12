# RegexGolf

正则表达式练习网站:https://alf.nu/RegexGolf

## Classic
|标题| 题意|答案|备注|
|----|----|----|----|
|Warm up| 包含foo的表达式|foo||
|Anchors|以k结尾的表达式|k$|$表示结尾|
|It never ends|以fu为结尾的表达式|u\b<br/>fu(?!.)|\b匹配空字符串只在开头或者结尾<br>?!表示非|
|Ranges|使用的字符在a-f之间|^[a-f]+$||
|Backrefs|重复一次开头的三个字符|(...).*\1|()表示匹配的字符组合，编号从1开始<br>\number表示字符组合
|Abba|如题不包含abba长度为4的表达式|^(?!.*(.)(.)\2\1)|(?!)取反<br>\number表示第几个组合|
|A man, a plan|字符串是否回文|^(.)(.).*\2\1$|作弊了一点|
|Prime|正则匹配素数个x|||
|Four|存在一个重复四次的字符，并且中间间隔一个|(.)(.\1){3}||
|Order|按字母顺序的表达式|```^a*b*c*d*e*f*g*h*i*j*k*l*m*n*o*p*q*r*s*t*u*v*w*x*y*z*$```<br>^.{5}[^e]?$|作弊根据字母长度|