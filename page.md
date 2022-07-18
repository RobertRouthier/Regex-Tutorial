
# Regex Tutorial

Regular expression or Regex for short

## Summary

The phrase "regular expression" was conceptualized in the 1950's by a mathematician, back then referred to as regular language.
Regular expression is the sequence of characters that is usually find or find and replace operations on strings

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

There are a few different types of regex anchors, We have string, line, attempt, and match anchors.

String anchors like the caret or dollar sign match the start or end of a string

Line anchors (also) the caret and the dollar sign match match the line break in addition to matching the start or end of a string

Attempt anchors like \A match the start of the string to the regex pattern it is already applied to

Match anchors like \G match either at the end of a previous match attempt or at the start of the string during the first match attempt 

### Quantifiers

An example of a quantifier is {n}. It appends to a character, character class or spread set and specifies how many is needed

### Grouping Constructs

Grouping contstructs delineate the subexpressions of a regex and capture the substring of an input string. The possibilities of using grouping contstructs are:
Match a subexpression, apply a quantifier to the subexpression, and retrieve an individual subexpression

### Bracket Expressions

A bracket expression, or "[]", is a regex that matches a specific set of single characters or multi-character elements based on the non=empty set of list
expressions contained in the bracket expression

### Character Classes

Character classes distinguish kinds of characters such as letters and digits

### The OR Operator

Sometimes referred to as "alternation", the "or" operator("|"), helps continue to search through different options in the expression,
allowing said expression to continue to run without breaking

### Flags

There are six flags in javascript regex, (i, g, m, s, u, y)
i- allows search to be case sensitive

g- searches for all matches, otherwise search only returns first match

m- mulitline mode

s-enables "dotall" mode which allows the dot or "." to match the new line character \n

u- enables full unicode support

y-"sticky" mode. searches for exact position in text

### Character Escapes

The escape character or "\" allows the restoration of the literal meaning of the character that follows like \n for new line
\w for word character or \s for space

## Author

Robert Routhier

https://github.com/RobertRouthier
Full stack developer from Irvine California. About four months experience in the field. Currently have attempted at least one project in the front end only as well as the backend
