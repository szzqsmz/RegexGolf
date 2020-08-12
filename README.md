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
||||
||||