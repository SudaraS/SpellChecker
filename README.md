# Spell Checker

This is a simple spell checker algorithm that uses dynamic programming to suggest corrections for misspelled words. It runs in the browser and is powered by JavaScript, HTML and a dictionary file. (Pride and Prejudice)

## Features
- Finds the 10 closest matches to the input word based on a dictionary.
- Utilizes the sequence alignment algorithm with penalties:
  - Exact match = 0
  - Consonant/Consonant or Vowel/Vowel mismatch = 1
  - Vowel/Consonant mismatch = 3
  - Gap = 2
- Interactive UI for entering words and viewing suggestions.

## How to Use
1. Type a word into the input box.
2. Click the "Check" button.
3. View the top 10 suggestions for the word.

## Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/SudaraS/SpellChecker.git
   
