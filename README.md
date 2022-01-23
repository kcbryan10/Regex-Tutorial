# Regex matching an Email 

in this tutorial i will explain to you the functionality of the regular expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. which can be used to validate emails.

## Summary

A regex is a sequence of symbols and characters expressing a string or pattern to be searched for within a longer piece of text.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Components of Regex

### Anchors
 The anchors in this regex are ^, which starts the string. and $, which ends the string.
### Quantifiers
 There are two quantifiers within this regex. the first is +, this is used to connect email name, email service, and .com. the second quantifier in this regex is {2,6}, which allows 2-6 characters from the character set of [a-z\.].
### Character Classes
  The character class in this regex is \d, which will match a character that is a digit from 0-9. it will only match a single digit ("6" not "66")
### Grouping and Capturing
  There are three capturing groups in this regex. first is ([a-z0-9_\.-]+), this matches the email name. The seconds capturing group is ([\da-z\.-]+), this matches the email service. the third and last capturing group is ([a-z\.]{2,6}), which matches .com.
### Bracket Expressions
  
### Greedy and Lazy Match

## Author

Author is Bryan Kelller. Github: 
