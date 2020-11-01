# hangman-algorithms
Use a lambda expression and map at least once somewhere in your code. You can use this page as reference.
Only 10 times guesses, including correct and incorrect guesses, are allowed. You can assume that there are at most 10 different letters in any word in words.txt.
Only allow alphabetic characters to be considered. If a user enters a *, skip over the input. (Python has a pretty useful function to check if a string is alphabetic.). In this case, print "Only allow alphabetic characters." Do not count this input.
If a user input empty or more than one characters in one input like 'as', do not consider this kind of input and do not count this input. In this case, print "Only one character is allowed in each input".
The file you are choosing words from (words.txt) contains all lower-case characters. You can allow a user to enter an upper-case alphabetic character (A .. Z), but get its lower-case equivalent when comparing.
If a user enters a character that appears more than once in the word (i.e. 'aardvark' where 'a' occurs multiple times) be sure to identify each occurrence of the character, and not just the first.
Allow a user to guess a character only once. If they enter the same character more than once, print out a message indicating the character has already been considered and only count the same character once. Furthermore, if the character is an incorrect guess, only count it as an incorrect guess the first time. In this case, print "The letter", ch, "has already been used."
If a user enters a character that is not in the correct word, print ch,"does not occur."
If scuess, print 'Congratulations!', otherwise, print 'Sorry dude, the word is', word
Print the current times of count along with each output.
