# caesar-cracker
A Python program to decrypt Caesar-encrypted ciphers

Team: 2-4 people

Challenge: Intermediate/Hard

The Caesar cipher (https://en.wikipedia.org/wiki/Caesar_cipher) is one of the simplest forms 
of encoding messages, and it's also one of the simplest to break.  This program will take an input 
Caesar-encoded text and return the decoded output.

In broad terms, the program should

* Guess the shift constant used to encode the message.  The strategy is left to the development 
team, but a letter-frequency analysis is a good place to start.  A brute-force approach is a 
valid strategy, but much less fun.

* Decode and display the message using the guessed shift constant.

Hard Challenge

After the program has guessed the shift constant, use a web-accessible dictionary API (like the 
Oxford Dictionaries API at https://developer.oxforddictionaries.com/) to confirm that the 
decoded text is correct by verifying that it consists of standard English words.

