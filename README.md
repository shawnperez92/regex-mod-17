# Hex Value Regex Tutorial

This will explain and examine how we use Regex for Hex Values

## Summary

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

This tutorial will walk you through understanding and crafting regex patterns to search for hexadecimal (hex) values.
Hex values are often used in contexts like color codes, memory addresses, and encoded data.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

Anchors ensure that your regex match a pattern at certain positions:
- '^': matches the beginning of the string
- '$': matches the eng of the string

### Quantifiers

Quantifiers tell you how many times a characrter or group should appear.
- {x}: Exact x occurences
- {x,}: at least x occurences
- {x,y}: between x and y occurence

### OR Operator

The OR Operator | allows matching of several patterns.


### Character Classes

Character classes match specific sets of characters
- [a-f0-9]: matches any digit (0-9) or letter (A-F or a-f)

### Flags

Flags modify regex behaviors
- i: Case-insensitive matching
- g: global matching
- m: multi-line matching

### Grouping and Capturing

() create groups for capturing or applying operators.

### Bracket Expressions

[ ]: bracket epressions define a character set.

## Author

Shawn Perez is a new full stack developer learning the in's and out's of javascript and all it has to offer
Github Profile : https://github.com/shawnperez92