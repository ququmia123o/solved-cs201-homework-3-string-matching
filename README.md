Download Link: https://assignmentchef.com/product/solved-cs201-homework-3-string-matching
<br>



<h2>Sample Run 1</h2>

This program searches a search string in a source string with the option of wildcards.

Example inputs with their meaning in parantheses:

<ul>

 <li>thislectureisawesome (to enter a new source string)</li>

 <li>lecture (to enter a new source string) 2 t?r? (to enter a source string with wildcards)</li>

 <li>(to exit the program)</li>

</ul>

Enter your choice and string: <strong><em>1 changingthesourcestring</em></strong>

Source word has been changed to “changingthesourcestring”

Enter your choice and string: <strong><em>2 the</em></strong>

For the source word “changingthesourcestring” and search word “the”, “the” has been found at index 8

Enter your choice and string: <strong><em>2 ing</em></strong>

For the source word “changingthesourcestring” and search word “ing”,

“ing” has been found at index 5

“ing” has been found at index 20

Enter your choice and string: <strong><em>2 i?g</em></strong>

For the source word “changingthesourcestring” and search word “i?g”,

“ing” has been found at index 5

“ing” has been found at index 20

Enter your choice and string: <strong><em>2 is</em></strong>

For the source word “changingthesourcestring” and search word “is”, no match has been found.

Enter your choice and string: <strong><em>2 ?es</em></strong>

For the source word “changingthesourcestring” and search word “?es”,

“hes” has been found at index 9

“ces” has been found at index 15

Enter your choice and string: <strong><em>2 ?e?</em></strong>

For the source word “changingthesourcestring” and search word “?e?”,

“hes” has been found at index 9

“ces” has been found at index 15

Enter your choice and string: <strong><em>3</em></strong>

See you!

<h2>Sample Run 2</h2>

This program searches a search string in a source string with the option of wildcards.

Example inputs with their meaning in parantheses:

<ul>

 <li>thislectureisawesome (to enter a new source string)</li>

 <li>lecture (to enter a new source string) 2 t?r? (to enter a source string with wildcards) 3 (to exit the program)</li>

</ul>

Enter your choice and string: <strong><em>1 newsourcestring</em></strong>

Source word has been changed to “newsourcestring”

Enter your choice and string: <strong><em>1 newsourcestringv2 </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>1 newsourcestringvtwo </em></strong>Source word has been changed to “newsourcestringvtwo”

Enter your choice and string: <strong><em>2 ? </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>2 ??? </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>2 erf2 </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>2 sou*ce </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>2 ?o</em></strong>

For the source word “newsourcestringvtwo” and search word “?o”,

“so” has been found at index 3

“wo” has been found at index 17

Enter your choice and string: <strong><em>3 </em></strong>See you!

<h2>Sample Run 3</h2>

This program searches a search string in a source string with the option of wildcards.

Example inputs with their meaning in parantheses:

<ul>

 <li>thislectureisawesome (to enter a new source string)</li>

 <li>lecture (to enter a new source string) 2 t?r? (to enter a source string with wildcards)</li>

 <li>(to exit the program)</li>

</ul>

Enter your choice and string: <strong><em>2 sabanci </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>1 helloworld? </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>1 thisissourcestring</em></strong>

Source word has been changed to “thisissourcestring”

Enter your choice and string: <strong><em>2 this</em></strong>

For the source word “thisissourcestring” and search word

“this”,

“this” has been found at index 0

Enter your choice and string: <strong><em>2 ?i?</em></strong>

For the source word “thisissourcestring” and search word

“?i?”,

“his” has been found at index 1

“sis” has been found at index 3

“rin” has been found at index 14

Enter your choice and string: <strong><em>2 t?</em></strong>

For the source word “thisissourcestring” and search word “t?”,

“th” has been found at index 0

“tr” has been found at index 13

Enter your choice and string: <strong><em>2 thisissourcestring</em></strong>

For the source word “thisissourcestring” and search word

“thisissourcestring”,

“thisissourcestring” has been found at index 0

Enter your choice and string: <strong><em>2 thisissourcestrin?</em></strong>

For the source word “thisissourcestring” and search word

“thisissourcestrin?”,

“thisissourcestring” has been found at index 0

Enter your choice and string: <strong><em>2 ?hisissourcestrin?</em></strong>

For the source word “thisissourcestring” and search word

“?hisissourcestrin?”,

“thisissourcestring” has been found at index 0

Enter your choice and string: <strong><em>5 </em></strong>Choice can be 1, 2 or 3! Try again.

Enter your choice and string: <strong><em>Cs201 </em></strong>Choice can be 1, 2 or 3! Try again.

Enter your choice and string: <strong><em>3</em></strong>

See you!

<h2>Sample Run 4</h2>

This program searches a search string in a source string with the

option of wildcards.

Example inputs with their meaning in parantheses:

<ul>

 <li>thislectureisawesome (to enter a new source string)</li>

 <li>lecture (to enter a new source string)</li>

 <li>t?r? (to enter a source string with wildcards)</li>

 <li>(to exit the program)</li>

</ul>

Enter your choice and string: <strong><em>1 sabanciuniversity</em></strong>

Source word has been changed to “sabanciuniversity”

Enter your choice and string: <strong><em>2 university</em></strong>

For    the                  source word “sabanciuniversity” and search word

“university”,

“university” has been found at index 7

Enter your choice and string: <strong><em>2 ab?n</em></strong>

For the source word “sabanciuniversity” and search word “ab?n”, “aban” has been found at index 1

Enter your choice and string: <strong><em>2 uni?er</em></strong>

For the source word “sabanciuniversity” and search word “uni?er”, “univer” has been found at index 7

Enter your choice and string: <strong><em>2 un??er</em></strong>

For the source word “sabanciuniversity” and search word “un??er”,

“univer” has been found at index 7

Enter your choice and string: <strong><em>2 u?i?er</em></strong>

For the source word “sabanciuniversity” and search word “u?i?er”, “univer” has been found at index 7

Enter your choice and string: <strong><em>2 s???</em></strong>

For the source word “sabanciuniversity” and search word “s???”,

“saba” has been found at index 0

“sity” has been found at index 13

Enter your choice and string: <strong><em>1 university</em></strong>

Source word has been changed to “university”

Enter your choice and string: <strong><em>2 sabanciuniversity </em></strong>Wrong input format! Try again.

Enter your choice and string: <strong><em>2 university</em></strong>

For the source word “university” and search word “university”,

“university” has been found at index 0

Enter your choice and string: <strong><em>3</em></strong>

See you!


