# Word-Analyzer (Exercise 4)
## What is Word Analyzer?
A **Word Analyzer** analyzes any word and determine number of consonants and vowels.
You need to develop a simple React Native mobile application that analyzes any word
given by a user.
## How it works?
**I use RegExp(regular expression) method**
1. User type their input (word or sentences)
2. The application will count the total character from the input and ignore the blank space as I use 
string.replace(/ /g, "").length
4. Beside, this application also will check whether the input is match with the vowel letter array and count total vowel letters and return it using string.match(/[aeiou]/gi);
5. Next, this application will substract the total letter of vowel with total character of input to get the total letter of consonant

![Function](function.png)
