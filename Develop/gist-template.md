# Regex-Tutorial: Matching a URL

A regular expression is a sequence of characters that specifies a search pattern. The Regex function is used to extract information from a specified text.

In this tutorial, the regex will check to see if a given URL is a valid URL for a website address.

## Summary

This is an example of a regex pattern used to idenfity a valid URL:

```
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]_)_\/?$/
```

1. https://www.google.com
2. http://www.google.com
3. www.google.com
4. htt://www.google.com
5. ://www.google.com

Testing the following string inputs: 

Examples 1,2,3, will identify a valid URL
Examples 4,5 will are not identified as a valid URL


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

- `^`  **Caret Anchor**:  Beginning of string element of the URL.
- `$`  **Dollar Anchor**:  End of string element of the URL. 

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
