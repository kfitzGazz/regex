# Regex Tutorial

This tutorial breaks down regular expression and is about matching a Hex Value using the following: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

## Summary

Summarizing anchors and contents and syntax for regex

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
It's setting a search parameter within the  ^ symbol and the $ sign

Here are examples: 

^The        matches any string that starts with The -> Try it!
end$        matches a string that ends with end
^The end$   exact string match (starts and ends with The end)
roar        matches any string that has the text roar in it

### Quantifiers
Quantifiers are identified by a ? in this example tuturial, and is requiring a match of zero to one within the parantheses that follow it. Also, within the curly brackets is a requirement to sum up to 6 and/or up to 3 since they're 2 sets of curly brackets.

here are some examples:

abc*        matches a string that has ab followed by zero or more c -> Try it!
abc+        matches a string that has ab followed by one or more c
abc?        matches a string that has ab followed by zero or one c
abc{2}      matches a string that has ab followed by 2 c
abc{2,}     matches a string that has ab followed by 2 or more c
abc{2,5}    matches a string that has ab followed by 2 up to 5 c
a(bc)*      matches a string that has a followed by zero or more copies of the sequence bc
a(bc){2,5}  matches a string that has a followed by 2 up to 5 copies of the sequence bc


### Grouping Constructs


### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
