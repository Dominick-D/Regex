# 🌐 URL Matching Using Regular Expressions

In this tutorial, we'll break down the components of a regular expression (regex) that's designed to match URLs. Regular expressions are powerful tools for pattern matching and validation in text. We'll cover anchors, quantifiers, grouping constructs, bracket expressions, character classes, and character escapes.

## 📝 Summary

The regex we're examining is `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`. This regex is commonly used to validate URLs in many programming contexts.

## 🚀 Table of Contents

- [Anchors ⚓️](#anchors)
- [Quantifiers 🔢](#quantifiers)
- [Grouping Constructs 🧺](#grouping-constructs)
- [Bracket Expressions 🧲](#bracket-expressions)
- [Character Classes 👥](#character-classes)
- [Character Escapes 🏃‍♂️](#character-escapes)

## 🔧 Regex Components

### Anchors ⚓️

The `^` and `$` are start and end anchors. They mark the beginning and the end of the line. This means the regex match will start looking from the beginning of the line and must consume the whole line for it to be considered a match.

### Quantifiers 🔢

Quantifiers indicate numbers of characters or expressions to match. The `?` means zero or one of the preceding element. The `*` means zero or more of the preceding element. 

### Grouping Constructs 🧺

Parentheses `()` are used to define groups in the regex. For example, `(https?:\/\/)` is a group that matches either "http://" or "https://". 

### Bracket Expressions 🧲

Bracket expressions `[]` define a character class, a set of characters to match. The expression `[\da-z\.-]` will match any digit, lowercase letter, or the special characters ".", "-" in the domain name of the URL.

### Character Classes 👥

Character classes are defined inside brackets `[]` and match any one character enclosed. In our regex, `\d` is a character class that matches any digit.

### Character Escapes 🏃‍♂️

The `\/` sequence is a character escape for the forward slash `/`. The escape `\.` is used to match a period `.` exactly, not any character, as `.` is a special character in regex.

## 👩‍💻 Author

This tutorial was written by [Dominick D](https://github.com/dominick-d), If you have any questions about the repo, open an issue or contact me directly at [Here](dominickdonn.me/contact). You can find more of my work on [my portfolio](domdonn.me).
