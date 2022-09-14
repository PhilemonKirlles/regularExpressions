# regularExpressions--Digits


"Unicode 15.0 adds 4,489 characters, for a total of 149,186 characters. These additions include 2 new scripts, for a total of 161 scripts, along with 20 new emoji characters, and 4,193 CJK (Chinese, Japanese, and Korean) ideographs."--unicode.org (V.15.0.0)


As we become more connected, as geographical and cultural boundries blurre away, we inquire more chrachters to particepate in our communication, creations and media. Chrachters we use today are numirus. Unicode standrizes the meaning and the uses of such a dinse forest of orthographs. 
To find a chrachter among such density
would be an extra hard task, but imagin the complexity if we count in the relationships and meanings these chracters form. Finding a comperhinsable string of chrachters can reach impossibilty in some cases.

regular expression (regex) are essintial in simplfying such task. If you want to fing the lyrics of the sigment of chrachters <"na Mah"> in the the lyrics of the (Mana Mana) song in a collection of all modern US lyrics, regex is the set of keys that correspond to our goal. 

in this tutorial, I will focus on degets as a regex concept.

Mahna Mahna do do do do do Mahna Mahna do do do do
Mahna Mahna do do do do do do do do do do do do do do do do do
Mahna Mahna--Piero Umiliani - Mah-Na-Mah-Na (original mono 45) (1969).
[link][https://www.youtube.com/watch?v=D2AnF7Qwc5s&ab_channel=menchitty11](<https://www.youtube.com/watch?v=D2AnF7Qwc5s&ab_channel=menchitty11>)



<!-- Introductory paragraph (replace this with your text) -->

## Summary
Digit (0-9). In different combnations and with the additions of especial chrachters, we create strings of numbers to convay information. like how the compnation of "(tree)three-four" as a stnring hints to a phone number. with the addition of especial chrachters like ("-|.| |+|+1|") we imphsise the information, and exband the perception of what the digits meant and what they are used for.
in the below example example a table of phone numbers, written as a regular expressions, and digits which will use through out this tutorial. 

| Table |  1      |  2      |
| -----:|:-------:|:-------:|
| | | |
|| ||
||| |
| |||

| Table |  1      |  2      |
| -----:|:-------:|:-------:|
| | | |
|| ||
||| |
| |||


<!-- Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary. -->

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components (know the tools
| Table |  1      |  2      |
| -----:|:-------:|:-------:|
| | | |
|| ||
||| |
| |||

| Table |  1      |  2      |
| -----:|:-------------------------------:|:-------------:|
| [ ]   |- Matches Characters in brackets | Match any of the characters present in the brackets. As in find any of these [a,b,or c]|
| ^     |- Beginning of a String | a caret symbol indicates the beginning of a string. As in saying the string starts here|
|$ |- End of a String | a caret ^ symbol indicates the end of a string. As in: the string which you have begun at the ^, has ended at $|
| [^ ] |- Matches Characters NOT in brackets |As in find [^a,b,or] as long as they are not contained in the brackets |
| | |- Either Or | As in find the first or the second item. like saying either or would satisfy |
| ( ) |- Group | As in saying find 1, 2, and 3 (123) consecutively or find three ds (ddd) in a row |
| \d |- Digit (0-9) | |a back slash and a small letter \d are looking for digits, all 0-9 qualify. ie \d 95320 |
| \D     |- Not a Digit (0-9) | a back slash and a capital letter \D looking for digits, all numbers qualify |
| \w     |- Word Character (a-z, A-Z, 0-9, \_) | a character that can be included in a word like "cafe_56" or and character in the words "cafe fifty six
| \W |-             Not a Word Character - | using the back slash and a captal \W indicates that what follows is not a character of a word. ie, \W-
| \s |- Whitespace (space, tab, newline)  | as in find all empty spaces|
| \S |- Nowhitespace (space, tab, newline) | as in find everything but the white spaces|
| \b |-                Word Boundary       | as in find everything within the \b....\b boundaries. Like \bexample\bs|
| \B |-                Not a Word Boundary | don't look for the slash and b "\b" within the context of a word boundary"

### Anchors

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)




| Table |  1      |  2      |
| -----:|:-------------------------------:|:-------------:|
| [ ]   |- Matches Characters in brackets | Match any of the characters present in the brackets. As in find any of these [a,b,or c]|
| ^     |- Beginning of a String | a caret symbol indicates the beginning of a string. As in saying the string starts here|
|$ |- End of a String | a caret ^ symbol indicates the end of a string. As in: the string which you have begun at the ^, has ended at $|
| [^ ] |- Matches Characters NOT in brackets |As in find [^a,b,or] as long as they are not contained in the brackets |
| | |- Either Or | As in find the first or the second item. like saying either or would satisfy |
| ( ) |- Group | As in saying find 1, 2, and 3 (123) consecutively or find three ds (ddd) in a row |
| \d |- Digit (0-9) | |a back slash and a small letter \d are looking for digits, all 0-9 qualify. ie \d 95320 |
| \D     |- Not a Digit (0-9) | a back slash and a capital letter \D looking for digits, all numbers qualify |
| \w     |- Word Character (a-z, A-Z, 0-9, \_) | a character that can be included in a word like "cafe_56" or and character in the words "cafe fifty six
| \W |-             Not a Word Character - | using the back slash and a captal \W indicates that what follows is not a character of a word. ie, \W-
| \s |- Whitespace (space, tab, newline)  | as in find all empty spaces|
| \S |- Nowhitespace (space, tab, newline) | as in find everything but the white spaces|
| \b |-                Word Boundary       | as in find everything within the \b....\b boundaries. Like \bexample\bs|
| \B |-                Not a Word Boundary | don't look for the slash and b "\b" within the context of a word boundary"

email: mr.pmo@gmail.com
email: mr_pmo@gmail.com
email: Mr_pmo@gmail.com

answer this question (1) befor you start
question:

search this code for ()

match the code to the output

explanation

digits search pattern

introducing the string:

Mahna Mahna do do do do do Mahna Mahna do do do do
Mahna Mahna do do do do do do do do do do do do do do do do do
Mahna Mahna

search this code for ()
match the code to the output

explanation

using the string search pattern

introducing the grouping:
search this code for ()
match the code to the output

explanation

www.website.com
www.website.gov
www.website.edu
website.com

#### Sample Regexs

[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9-.]+

Sourses I consulted:
1-(<https://computersciencewiki.org/index.php/Regular_expressions>)
2-<https://www.regular-expressions.info/>
3-<https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables>
4-<https://stackoverflow.com/questions/39378020/how-to-display-table-in-readme-md-file-in-github>
5-<https://www.youtube.com/watch?v=ZfQFUJhPqMM&ab_channel=freeCodeCamp.org>
6-<https://en.wikipedia.org/wiki/List_of_typographical_symbols_and_punctuation_marks>

