# Venture into Vim Cheatsheet

#Basics:
<tt>i</tt> to go into Insert mode

<tt>esc</tt> will leave Insert Mode and go back into Command mode

<tt>:w</tt> writes to a file

<tt>:q</tt> quits vim

<tt>:wq</tt> writes and quits vim

#Command Mode Movements:
<tt>K</tt> up

<tt>J</tt> down

<tt>H</tt> left

<tt>L</tt> right

<tt>w</tt> move forward one word

<tt>$</tt> go to end of the line

<tt>0</tt> go to beginning of the line

<tt>Shift + G</tt> go to the bottom of the page

<tt>gg</tt> go to the top of the page

<tt>x</tt> remove a character in command mod

<tt>CTRL + F</tt> forward a page in the terminal

<tt>CTRL + B</tt> back a page in the terminal

<tt>d</tt> delete

<tt>dd</tt> delete a line

<tt>d$</tt> delete from certain point to end of the line

<tt>r</tt> replace - type the character you want to replace over current one

<tt>v + arrow keys</tt> highlight text

<tt>y</tt> copy text while highlighted 

<tt>:number</tt> jumps to specific line number

<tt>:set number</tt> shows all line numbers

<tt>/term</tt> searches for the term you're looking for in the document

<tt>n</tt> will go to the next item of the term you searched for

<tt>Shift + V</tt> highlights entire line. use arrow keys to highlight additional lines.

<tt>a</tt> goes into Insert mode 1 char after highlighted letter or word

<tt>b</tt> Jump back a word

<tt>B</tt> Jump back a whole word separated by space

<tt>W</tt> Jump words separated by space

<tt>^</tt> Goes to first non-space char

<tt>f + any letter</tt> will find the first occurrence of that letter in current line

<tt>F + any letter</tt> will find the first occurrence of that letter in current line backwards

#Insert Mode Commands:
Capital <tt>I</tt> goes into Insert mode beginning of the line

Capital <tt>A</tt> goes into Insert mode at the end of the line

Capital <tt>O</tt> creates a new line above where I am

Lowercase <tt>o</tt> creates a new line below where I am
