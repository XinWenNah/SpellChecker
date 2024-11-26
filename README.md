# SpellChecker
The code is designed to check whether an input matches any words from a provided file.

Usage

Create an object of the SpellChecker class with the file name. The file should contain a list of words.
Use the check function to verify the spelling of an input word.

If the input partially matches any words in the file, it will return up to the top 3 suggested words based on the following criteria:

Common shared prefix
Frequency (how often the word appears in the file)
Lexicographical order
If the input does not match any words or matches exactly, it will return None.