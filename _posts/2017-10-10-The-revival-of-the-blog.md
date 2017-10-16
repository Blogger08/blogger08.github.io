---
title: The revival of the blog
layout: post
author: alex.coyne
permalink: /the-revival-of-the-blog/
source-id: 1U7HNseortjXNFA6UTZKtcSvUlTXY1iII59x750rgKMU
published: true
---
**_The revival of the blog_**

**Week one**

**Encryption****                    ****11/09/17**

**Target for the lesson:**

To begin my understanding of encryption.

**Did I reach my target?**

I believe this lesson has helped me understand the making and encryption of the code.  

Lesson review

This lesson we started the making of the code by moving the letters of the alphabet a certain number for or backwards. I.e. If you moved each letter 3 letters forward, 'A' would become ‘D’ and ‘B’ would become ‘E’. I used the phrase ‘You will not pass’ as the line I would use to encrypt. To code this line you have to write the alphabet vertically down and use a space for number 27. Then you write the alphabet the way you want to so your code is unreadable. To convert your code into the coded message, you will have to go on a line a few rows down and in my case write ‘Y’ in the first box ‘O’ in the second box and carry on with your message horizontally across. Once you have done that you click on the empty box below and type in ‘=vlookup(the box above),$(letter of vertical row)$(number of horizontal row):$(letter of coded message vertical row)$(number of coded message on horizontal row),2, false. For instance my code is =VLOOKUP(F29,$I$1:$J$27,2, false).

To improve I am going to speed up the time I spend doing the exercise.

In the other weeks we have been expanding our knowledge on encryption. One thing that we have completed is putting a word in front of the alphabet I.e. 'Tea' and then write the code in that way using the same code I wrote in the previous paragraph. We also decoded the code by doing the reverse of what we did in the first paragraph. All you have to do is copy the alphabet from one column to the other side of the encrypted code. Then all you have to do is complete the same code again as you did before but by putting the English alphabet on the right hand side rather than on the left side. This finds the message you first typed in. 

Another way to decode a code is by using a series of steps. This way is more accurate and will be used on codes that have more than one letter for each letter in the english alphabet. Firstly you will have to use the concatenate tool to get the whole code into one box. You can do this by typing in '=concatenate(highlight the code)' and that should work. My looks like =CONCATENATE(A30:Q30). Next you will have to go a few rows down and a few columns in and type 1...2...3...4...5...6 and so on so until you are roughly the length of the code. Then you go to the column above and type in =left($(letter of column) $(number of row),1*(the row below). I was doing it on C40 so the code was =left($B$37,1*C41). Next you will have to type this code in on the row below, =if(LEN(name of box 2 rows above)>LEN(the name of box a column before the other box),1, if(len(same as before)=len(same as before),0)). I typed this code in on C42 so the code that I wrote was,

=IF(LEN(C40)>LEN(B40),1, if(len(C40)=len(B40),0))

 

Next go a few rows down and type in =if((the box you just typed the code in = 1), right (2 rows above the other box in this code,1),). I wrote =if((C42=1), right(C40,1),). Finally you go one row down and type in the near exact same code as before by typing =vlookup(the row above,$where you typed in the random letter alphabet in the (first box):where you typed in the normal alphabet the second time (last box),2, false). The code that I did looked like =VLOOKUP(C48,$L$1:$M$27,2, false).

To improve on these lessons I am going to try and depend more on myself than others and fully complete the work before I help others who are behind as it will slow down my learning.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vT8QZJo0LXOuphHRR8Y0G_c_03AQpyw5vr7_oXYgQ2RrN82GMxg9rR7M2rkHL1emPJOaTWqrZ52NHd_/pubhtml?widget=true&amp;headers=false"></iframe>
