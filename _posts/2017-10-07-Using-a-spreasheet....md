---
title: Using a spreasheet...
layout: post
author: nathan.higgins
permalink: /using-a-spreasheet.../
source-id: 1XSRHOxwpW-BZjI1zgVG4w-NnFiQaoJf3jFVmH4jXhcc
published: true
---
For the last few weeks we were using spreadsheets. Now when you think of spreadsheets, you think of tables and numbers and boring things like that but spreadsheets can be used for a lot more things if you know how to. There are lots of functions in spreadsheets that not many people know about. However, we have been making codes and decoding codes using spreadsheets.

We started off by creating a simple code, the Caesar cipher. To do this, we just put the alphabet in one column, for example A1-A27, and put the coded alphabet in another column for example B1-B27.  Then we created a cell in the spreadsheet that would have our message using the normal alphabet(one cell would have one letter of the message) and underneath it a cell that would have our message coded in our new coded language(one cell would have one letter of the message). Then we had to use the function Vlookup to translate our original message into code. We used the Vlookup function in the coded cells. For each cell we would give it the function, =vlookup (to tell the program to run the vlookup function), then the cell it would want to translate into the coded language(for example H5), then put the code $A$1:$B$27. This would make it search for the letter in the cell from the original alphabet and the coded alphabet. You would then put comma 2 to tell it to only find the letter B for example in the first column, the original alphabet, and paste the corresponding letter in the encoded cell, the coded alphabet. We did that for every cell and eventually it encoded our original message. 

Once we did this, we made a decoding machine. This is pretty much the same but you translate from coded language to the original alphabet.  We then also did the same but with binary instead. This was pretty much the same but for every row that would have the 8 digit binary you would have to click format, number, plain text so it would show all eight digits.

Then finally we had to concatenate our code, this mean that the message is all in one cell, not across 20 different cells. To do this you simply do =CONCATENATE(the cell where your coded message starts: the cell were your coded message ends).

 To separate a concatenated message, you have to type =left(the cell the concatenated message is in) and do this for how every many letters your message is and for every adding 1 or 2 or 3 etc.. 

Then you do the same with the broken down cells but to the right. right(the cell where z, or the ze etc…). That is what we have done using spreadsheets.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vShm9DGx1crJ8KZueAECxzr2dM2Dkh8E8wx3A-MM6i8rwWShGhs0WDTHEH-MHgKe8pGZumhV-xaE1AB/pubhtml?widget=true&amp;headers=false"></iframe>
