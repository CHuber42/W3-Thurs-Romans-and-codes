# Pig Latin Translator

#### A program that allows users to input ????? 04/02/2020

#### By **Kelly Eidsvik and Christopher Huber**

## Description

A website created with Javascript/JQuery and HTML ?????


### Specs
| Spec | Input | Output |
| :-------------     | :------------- | :------------- |
| **Homepage** | User accesses localhost:5004 | Homepage with user input form |
| **Take an input from a user of a number between 0-3999**| User Input: 4| Output: IV |
| **Loop: If the input is over 1000, subtract 1000, append "M"** | Input: "1596" | Output: "M", "596" |
| **If: Does the remainder start with "9"? branch --> yes, special behavior; no: next spec** | Input: "596" | Output: "MD", "96" |
| **Is the remainder > 500? Yes: subtract 500, append "D"; no: skip** | Input: "596" | Output: "MD", "96" |
| **Loop: Is the remainder > 100? Yes: subtract 100, append "C"; no: skip** | Input: "596" | Output: "MD", "96" |
| **If: Does the remainder start with "9"? branch --> yes, special behavior; no: next spec** | Input: "96" | Output: "MDXC", "6" |
| **If: is the remainder > 50? Yes: subtract 50, append "L", no: next spec** | Input: "6" | Output: "MDXC", "6" |
| **Loop: is the remainder > 10? Yes: subtract 10, append "X", no: next spec** | Input: "6" | Output: "MDXC", "6" |
| **If: is the remainder "9"? Yes: special behavior; no: next spec**  | Input: "6" | Output: "MDXC", "6" |
| **If: is the remainder > "5"? Yes: subtract 5, append "V"; no: next spec** | Input: "6" | Output: "MDXCV", "1" |   
| **Loop: append "I" for every "1".** | Input: "1" | Output: "MDXCVI" |
| **Are there four of the same character in a row? Yes: Fix it (see below) No: DONE!** | Input: ????? | Output: ????? |




## Setup/Installation Requirements

1. Open with GHPages [here].
2. Clone in terminal.
3. Open in web browser.
4. Go nuts. 

## Known Bugs
* No known bugs at this time.

## Technologies Used
* JQuery
* Javascript
* HTML
* CSS

## Support and contact details

_Email no one with any questions, comments, or concerns._

### License

*{This software is licensed under the MIT license}*

Copyright (c) 2020 **_{Christopher Huber, Kelly Eidsvik}_**