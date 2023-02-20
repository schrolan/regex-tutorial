# Regex Tutorial

Introductory paragraph (replace this with your text)

## Summary

#   Regex, or regular expressions, is a combonation of special characters known as operators. The special character operators control a search that can be used for advanced find and/or to replace. This tutorial will breakdown the expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ which is matching an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

#   The ^ anchor matches at the begnining of the string. The $ anchor matches at the end of the target string.

### Quantifiers

#   The quantifiers here are + and {2,6}. The + means one or more, and the {2,6} is the min and max value repectively.

### OR Operator

#   The OR operator here is []. So for this example, [a-z0-9_\.-], this is showing that any character can be used as well as any number and the symbols _, . , or -.

### Character Classes

#   The character classes here are /d which means any digit character 0-9.

### Flags

#   Flags are placed at the end of a regex, after the second slash, and they define additional functionality or limits for the regex. There are none fot this expression.

### Grouping and Capturing0

#   Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of parentheses.

### Bracket Expressions

#   Anything inside a set of square brackets ([]) represents a range of characters that we want to match

### Greedy and Lazy Match

#   Greedy will consume as much as possible. Where when you add ? this makes it repeat as few times as possible, this is the lazy part.

### Boundaries

#   \b anchors the regex at a word boundary or the position between a word and a non-word character, or vice versa.

### Back-references

#   Backreferences match the same text as previously matched by a capturing group.

### Look-ahead and Look-behind

#   Lookahead: 	Asserts that what immediately follows the current position in the string. Lookbehind: Asserts that what immediately precedes the current position in the string.

## Author

Lance Schroeder
