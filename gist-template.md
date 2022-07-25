# Matching an Email: Regex Tutorial

## Summary

This is a tutorial on how you can use a regular expression to verify email parameters in an input. The steps below will describe where each part of the expression comes from and the purpose that it serves.

Snippet: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

The anchors for this expression are the "^" at the beginning and "$" at the end

### Quantifiers

Quantifiers specify how many instances of a character must be present in the input for the input to match an email. The first quantifier in this example is "([a-z0-9_.-]+)" which means that the first part of the email can be matched with any digit or letter from a-z. The same is true for the second part after the "@", which is ([\da-z\.-]+). The "{2,6}" indicates that the part of the email that typically has '.com' must have a minimum of 2 characters and a maximum of 6.

### OR Operator

The OR Operator | is used to separate characters and look for either of the characters provided. There is no OR Operator in this Regex example.

### Character Classes

In a character class, you tell the regex engine to match only one out of several characters. These characters are enclosed within square brackets. The character classes in this example are: 
[a-z0-9_\.-]
[\da-z\.-]
[a-z\.]

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

sean.mcdaniel1@outlook.com
github.com/seanxmcdaniel