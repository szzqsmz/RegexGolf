# RegexGolf

正则表达式练习网站:https://alf.nu/RegexGolf

## Classic
|标题| 题意|答案|备注|
|----|----|----|----|
|Warm up| 包含foo的表达式|foo||
|Anchors|以k结尾的表达式|k$|$表示结尾|
|It never ends|以fu为结尾的表达式|u\b<br/>fu(?!.)|\b匹配空字符串只在开头或者结尾<br>?!表示非|
||||