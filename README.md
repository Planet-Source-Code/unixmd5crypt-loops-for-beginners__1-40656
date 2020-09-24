<div align="center">

## ^^^Loops For Beginners


</div>

### Description

This Code Shows The Various Loops and how they can be applied, great for beginners looking for a solution timers can't seem to provide.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[UnixMd5Crypt](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/unixmd5crypt.md)
**Level**          |Beginner
**User Rating**    |3.4 (51 globes from 15 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/unixmd5crypt-loops-for-beginners__1-40656/archive/master.zip)





### Source Code

Okay, The First Loop is the Do Until Loop, This Loop checks the environment for a specification and as soon as that specification is met it ends.
===========
Do Until
===========
X = 0
Do Until X = 10
X = X + 1
if X = 10 then
msgbox X
end if
Loop
-----------
Now Lets Take A Look at this, this loop will loop until X = 10. This is a very simple loop all it does is loop until x = 10. Then when x = 10 it will display a message box saying 10. This doesn't seem to important now but it has its uses.
Next is the While Wend Loop. You will often see this used in file handling. I'll show you how to use it in file handling.
===============
While/Wend
===============
open "c:\windows\desktop\new text document.txt" for binary access read as #1
while not eof(1)
input #1, $TheText
wend
close #1
---------------
This May look more complicated but I'll explain step by step. That First Sentence The "open c:\... for binary ... as #1" opens a file for reading. then the wend loop takes the first line of text and loads it into the string $TheText then it does taht with each consecutive line until it reaches the end, that's what the while not eof(1) part is. it loops until EOF(<b>E</b>nd <b>O</b>f <b>F</b>ile) = true then it stops. The 1 in eof(<b>1</b>) tells that the file you opened under the name #1 is the file to check while not eof and the input #1 calls the text from the selected file, in our case new text document.txt.
Next is Do/While Loops
these loops do something until something is not true, this is often used with boolean(true or false) statments.
===============
Do/While
===============
x = true
Do while x = true
y=y+1
if y = 100 then
x=false
end if
loop
This Loop will add y until y = 100, when y = 100 then it tells x to become false, now when that happens x is no longer true then the loop ends, fairly simple. These are 3 of the loops, I beleive there are more but I haven't much time left. I hope that you can learn from these examples and if you have questions feel free to ask it. After all we all started at some time and we've all had our share of questions to be had. don't be afraid of asking, for he who flames a newbie must remember he too was once a newbie. Thank you all, and enjoy.

