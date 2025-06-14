# Exercise-3-Caesar-Cipher-solution

Download Here: [Exercise 3: Caesar Cipher solution](https://jarviscodinghub.com/assignment/exercise-3-caesar-cipher-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Create a function which will take in two string parameters and one integer parameter. Both of the string
parameters should be expected to be file names. The
function should take the text contained in the first file,
change all letters to lowercase, remove all non-letter characters, and perform a Caesar (or shift) cipher on the
remaining message. The result should be saved to the
second file name. The Caesar cipher consists of taking
each letter and shifting the letter up in the alphabet by
a given amount (e.g. b shifted by 3 is e). If a letter
should shift beyond z, it should loop back to a. The
amount shifted should be equal to the integer parameter passed in. For example, if the input file contains
Attack At Once! and the shift is 2 the output file
should contain cvvcemcvqpeg .
Hints: list(map(chr, range(97, 123))) will return a list of the 26 lowercase letters. Also, note that
on this list indexing position 3 is the same as indexing
position 29%26. Finally, if ’a’ in some_list: will
be useful to check if a character (specifically ’a’ in this
example) is in a list.

