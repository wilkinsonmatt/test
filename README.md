# Portfolio

#### By Matt Wilkinson

#### Programming Language Suggester

## Github links
* https://wilkinsonmatt.github.io/Programming_Language_Suggester/
* https://wilkinsonmatt.github.io/Programming_Language_Suggester/
* https://github.com/wilkinsonmatt/Programming_Language_Suggester.git

## Technologies Used

* CSS
* HTML
* Bootstrap
* JS
* Jquery

## Description

 A Programming Language Suggester webpage that asks future students a series of questions about themselves and provides a language suggestion based on their answers. 
 
 (Unfortunately the results aren't based in science)

## Tests

Describe: pigLatin()

Test: "It recognizes a single vowel."
Code: pigLatin("a");
Expected Output: true

Test: "It will add 'way' to the end of words that begin with a vowel."
Code: pigLatin("a");
Expected Output: "away"

Test: "It should return 'no input' for an empty string."
Code: pigLatin("");
Expected Output: "no input"

Test: "It should return 'no input' for a string that is only spaces."
Code: pigLatin("            ");
Expected Output: "no input"

Test: "It should not count numbers as words."
Code: pigLatin("77");
Expected Output: "No words entered"

Test: "It ignores non-alphabetical characters since they can't be vowels."
Code: pigLatin("*&$92%");
Expected Output: 0

Test: "It should identify a vowel match regardless of case."
Code: pigLatin(A);
Expected Output: "Away"

Test: "It will move consonants to the end of the word and add 'ay'"
code: pigLatin("code");
Expected Output: "odecay"

Test: " If the consonants include 'qu, move the 'q' and 'u'"
code: pigLatin('quick');
Expected Output: "ickquay"

<!-- Test: "It should return a word match regardless of punctuation."
Code:
pigLatin();
Expected Output:  -->





## Setup/Installation Requirements

* Download entire github file
* launch index.HTML file in Google Chrome

## Known Bugs

* N/A

## License

Copyright (c) 2022 Matt Wilkinson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR I