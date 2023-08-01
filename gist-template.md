# Title (Starter Regex Codes and Terms)

Introductory paragraph (replace this with your text)

## Summary

This is used as a tool to help you understand regex a littler better. Has a break down of the compenents and some short terms. As well
as some code to give you can idea. 

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
Regex components are used to define patterns for searching and manipulating text. The compenents are Achors, Quantifiers,
Grouping Constructs, Bracket Expressions, Character Classes, The OR Operator, Flags, Character Escapes, and Author. Here is a 
starter code that includes all compenets

 `/^[a-z0-9_-]{3,16}$/ `

 This is search from a-z, 0-9 and picking between 3 and 16.
### Anchors
Anchors are pretty simple. With only have two characters one being ^ which is the start of the coding. 
Also have $ which means the end of the code. 

` /^[a-z0-9_-]{3,16}$/ `

Start^          End$
### Quantifiers
Indicate how many times a preceding element should occur, like `*` (zero or more), `+` (one or more), `?` (zero or one), `{n}`, `{n,}`, `{n,m}`, etc. 

### Grouping Constructs
The primary way you group a section of a regex is by using parentheses `(())`. Enclose parts of the pattern in `()` to group and capture them for later use.

### Bracket Expressions
Brackets are what they should like `[]` with a range of characters that used for the code and what you are working with. 

### Character Classes
Match specific sets of characters , any one of which can occur in an input string to fulfill a match.  like `\d` (digits), `\w` (word characters), `\s` (whitespace), etc.
### The OR Operator
Using the OR operator checking for characters to matching using (|). Kinda works like javascript with true or false 
`b(a|e|i)d`
bad bud bod bed bid

So bad, bed,and bid would be true and the others are false.
### Flags
Flags are used to change how the regex code forms. Like `g` is a global search, `i` is used for insensitive search, and `m` is a multi-line search

### Character Escapes
Use `\` when searching for strings that would have special characters that are the same in particular component of the code. Escaping the open curly brace `({)` in regex searches for the character itself instead of starting a quantifier.

## Author
Wanna be author Fabian Barranco. 
Here is a link to my github [Click here](https://github.com/CaptFlopp3y)