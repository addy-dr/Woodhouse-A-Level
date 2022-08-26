## Algorithm to detect palindromes

- Get the word to check
- Lowercase all letters
- Identify the length of the word by checking every character until one not in the ASCII (or regional writing system) set is reached
- Multiply each character's position in the list by -1. What this does is invert the word (so the letter in position 1 goes to position -1, aka the letter before the end of the new word. 2 goes to -2, etc. Programs will automatically convert these to integer values of position).
- Check each character of the original word against the new inverted word. If at least one letter is different, abort the checks and determine that the word is not a palindrome.
- Else, the word is a palindrome.

# Examples of abstractions:

- Low level programming languages
- The Computer Terminal
- Interacting with Servers
- Control flow - loops, coroutines, etc
- Classes and Inhertiance in some programming languages
- Data managmenet