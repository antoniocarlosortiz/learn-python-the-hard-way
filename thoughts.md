## Thougts on the Book
---
<br />
##### Appendix A: A Command Line Crash Course
Most of them I've come across already, but I'm glad to know about pushd and popd!
- pushd - Use this in place of cd for the computer to remember the current directory.
- popd - Use this to come back to the directory before pushd was called.

<br />
##### Exercise 0: The Setup
Quick startup!
Best to use gedit, TextWrangles, or Notepad++ for beginners.

<br />
##### Exercise 1: A Good First Program
It's a very simple exercise on the print function- just print stuff!

<br />
##### Exercise 2: Comments and Pound Characters
Another simple exercise. I learned that reading code backwards could be helpful. Nice.
\# character can also be called octothorpe.

<br />
##### Exercise 3: Numbers and Math
Pretty self-explanatory when you know basic math and how to print strings. Comma is important after the string when joining strings with other types such as integers.

<br />
##### Exercise 4: Variables and Names
Good reminder- not all operands have to be floating point numbers for the answer to be a floating point.

<br />
##### Exercise 5: More Variables and Printing
I've used these before. For height_in_cm, the answer produces too many decimal places (6 to be exact) even when the numerator is an integer and the denominator only has 2 decimal places. Interesting.

<br />
##### Exercise 6: Strings and Text
%s is used for display whereas %r is for debugging.

<br />
##### Exercise 7: More Printing
Learned the comma trick for joining two strings with space between them.

<br />
---
#### So far... 
Very basic stuff! I've come across them before, but I learned some new things I could use for better code/debugging in the future, which is cool. 

---

<br />
##### Exercise 8: Printing, Printing
More examples for using %r!

<br />
##### Exercise 9: Printing, Printing, Printing
Intro to new line and multiline text string.

Two ways for printing out multi-line text strings:
- Method 1: using \n 
- Method 2: using """

<br />
##### Exercise 10: What Was That?
\n and \r aren't so similar after all. 
- \n is for linebreaks
- \r is for return carriage.  

Nice exercise. I wish the descriptions for the other escape sequences shown on the table were more explicit though. e.g. ASCII bell (BEL) to describe \a. It wasn't that helpful.

<br />
##### Exercise 11: Asking Questions
Learned the difference between input() and raw_input(). Reading the common student questions really helps.

<br />
##### Exercise 12: Prompting People
Putting the question inside the raw_input() function is exactly the same as printing out the question first and then asking for raw_input().
The module pydoc conventiently generates documentation from Python modules. e.g.
- open() - It's used for opening files using the file() type, and returns a file object.
- file() - It's used for opening a file, wherein a mode is chosen i.e. reading, writing or appending. However, open() is the preferred method for opening files.
- os - Importing this increases chances of partability between platforms.
- sys - This provides access to things like command line args, module search paths, and modules.

<br />
##### Exercise 13: Parameters, Unpacking, Variables
sys.argv module - used for inputting arguments before the script is run
  1. Input variables like this: python filename.py var1 var2 ... varx
  2. We import it like this: from sys import argv
  3. We unpack it inside the script like this: script var1 var2 ... varx  = argv
<br />
Modules = Features!!!

<br />
##### Exercise 14: Prompting and Passing
Zork and Adventure is cool!
Recyclable prompt is nifty.

<br />
---
#### So far...
I've learned about escape sequences and two ways of inputting data:
- raw_input()
- unpacking argv

---
