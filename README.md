# Title (Reg_ch)

Regex or regular expression can be used to match patterns in strings, reformatting text, pulling out and replacing information from a given body of code as well as input validation.


## Summary

The code that follows /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ will be used througout this tutorial to show how the components of (Regex) validate emails and to make sure they follow the correct format.


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
An anchor is what starts and ends the regular expression. The anchors are the ^ (the beginning) and $ (the end) parts of the code. 
### Quantifiers
Quantifier match between {2,6} of the preceding token. The + is to match 1 or more of the preceding token
### Grouping Constructs
([a-z0-9_\.-]+) In this example we are grouping the tokens a-z, 0-9, _, \., - and creates a capture group for extracting or using a back reference. The same happens for ([\da-z\.-]+) and ([a-z\.]{2,6}).
### Bracket Expressions

### Character Classes
([\da-z\.-]+) in this example the \d is used to match any character (0-9)
### The OR Operator
The or (|) operator is not currently present is this example of code. However the or operator is used to match characters or expressions on either side of the | operator
### Flags
Flags (i, g, m, u, y, s) are not currently present in this example of code. i (ignore case) makes the whole expression case insensitive. g (global search) retains the index of the last match allowing searches to start from the end of the previoous match. m (multiline) when multiline flag is enabled beginning and end anchors (^ and $) will match the start and end of a line instead of the beginning and end of an entire string. u (unicode) you can use extended unicode escapes in the form of \x{FFFFF} it also makes escapes stricter, causing unreognized escapes to throw an error. y (sticky) will only match from its last index position and ignores the g (global) flag if set.
### Character Escapes

## Author

This tutorial was created by Mario Ulloa Github: (https://github.com/Mulloa90)
