# Regex : Regular Expressions
### Regular expressions, often referred to as regex or regexp, are powerful tools for pattern matching and text manipulation in Python. The re module provides support for regular expressions in Python, enabling developers to search, match, and manipulate strings based on specific patterns.

## Basic Usage
### To use regular expressions in Python, you first need to import the re module:
```bash
$ import re
```
### The re module provides functions like search(), match(), and findall() for pattern matching.

## Common Regex Patterns

```
'\d'        : Matches any digit (0-9).
'\D'        : Matches any non-digit character.
'\w'        : Matches any alphanumeric character (equivalent to [a-zA-Z0-9_]).
'\W'        : Matches any non-alphanumeric character.
'\s'        : Matches any whitespace character (spaces, tabs, newlines).
'\S'        : Matches any non-whitespace character.
'.'         : Matches any character except a newline.
'^'         : Anchors the regex at the start of the string.
'$'         : Anchors the regex at the end of the string.
'[aeiou]'   : Matches any one of the specified characters.
'[^aeiou]'  : Matches any character except the ones specified.
'a{3}'      : Matches exactly three consecutive 'a' characters.
'a?'        : Matches zero or one occurrence of 'a'.
'a+'        : Matches one or more occurrences of 'a'.
: 'a*'      : Matches zero or more occurrences of 'a'.
'(abc)'     : Groups the characters 'abc' together.
'a|b'       : Matches either 'a' or 'b'.
'\'         : Escapes special characters, allowing you to match them literally.
'\bword\b'  : Matches the word only at a word boundary.
'(?i)case-insensitive' : Performs a case-insensitive match.
```
