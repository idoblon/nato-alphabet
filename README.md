NATO Alphabet
Description

This project provides a simple Python implementation of the NATO Phonetic Alphabet (also known as the International Radiotelephony Spelling Alphabet). It includes a .csv data file with all the code words and a script (main.py) to convert plain text into its NATO equivalent.

The NATO phonetic alphabet is widely used in aviation, military, emergency services, and other fields to make verbal communication clearer and prevent misunderstandings.


Features

-Convert any input text (A–Z, numbers, punctuation) into NATO phonetic form

-Data-driven: uses a CSV file (nato_phonetic_alphabet.csv) for flexibility

-Easy to extend or modify (you can add or change code words)

Installation
1. Clone the repository:
   -git clone https://github.com/idoblon/nato-alphabet.git

2. Navigate into the project folder:
   -cd nato-alphabet
   
3. Install any dependencies (if required):
   -pip install -r requirements.txt

Usage
Run the script using:
-python main.py
You will be prompted to enter text (a sentence, word, or characters). The script will then output the NATO phonetic version of that text.

Example:

Input: HELLO

Output: Hotel Echo Lima Lima Oscar

Data File (nato_phonetic_alphabet.csv)

-This CSV contains mappings from characters to their NATO code words. You can:

-Update or correct entries

-Add custom mappings (e.g., for symbols or non-English letters)

-Use it in other projects to build your own phonetic-conversion tools

Why Use This Project

-Educational: Great for learning or teaching what the NATO phonetic alphabet is and how it's used.

-Practical: Useful in applications where you need to convert text to a more foolproof spoken form — for example, in voice-based systems, call-centers, or radio comms.

-Flexible: Easy to adapt to new alphabets or custom phonetic codes.

Contributing

-Contributions are welcome! Here are some ways you can help:

-Fix or improve the CSV data (spelling, add IPA, pronunciation notes)

-Add support for converting more than just letters (e.g., numbers, punctuation)

-Write tests or improve the CLI/UX

-Add more languages or alternate phonetic alphabets

To contribute:

-Fork the repo

-Create a feature branch (git checkout -b feature-name)

-Make your changes

-Submit a pull request
