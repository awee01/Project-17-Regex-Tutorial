# Regex-Tutorial: Matching a URL

A regular expression is a sequence of characters that specifies a search pattern. The Regex function is used to extract information from a specified text.

In this tutorial, the regex will check to see if a given URL is a valid URL for a website address.

## Summary

This is an example of a regex pattern used to idenfity a valid URL:

```
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```

**1.**  https://<span></span>www<span></span>.<span></span>google.com

**2.**  http://<span></span>www<span></span>.<span></span>google.com

**3.**  www<span></span>.google.com

**4.** htt://www<span></span>.<span></span>google.com

**5.**  ://www<span></span>.<span></span>google.com

<br>


**In Testing the following string inputs:**

Examples 1,2,3, will identify a valid URL

Examples 4,5 will are not identified as a valid URL


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
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

These are located at the front and back of the regex.

![ex1](https://user-images.githubusercontent.com/85651950/138584234-a13aab9f-468b-45a9-9bae-9b6738ae7cdc.png)

- Symbol: `^`

 Beginning of string element of the URL.

- Symbol: `$`

End of string element of the URL. 

### Quantifiers


- Symbol: `?` Regex Code Snipet: `https?`

![ex2](https://user-images.githubusercontent.com/85651950/138584769-f49cc3c2-04cf-4742-b3e9-8c612b51e5e4.png)

Identifies https or http



- Symbol: `*` Regex Code Snipet: `[\/\w \.-]*`

![ex3](https://user-images.githubusercontent.com/85651950/138584812-61a4dc60-2852-440c-b700-a78961adba45.png)

 Identifies a slash (/) followed by string of words (\w). Also identifies lack of a slash(/).
 
 

- Symbol: `+` Regex Code Snipet: `[\da-z\.-]+` 

![ex4](https://user-images.githubusercontent.com/85651950/138584833-8cf0f518-2bab-4a3f-ac65-5426570c9419.png)

Identifies a single digit (\d), lowercase letters (a-z), a dot (.), a hyphen (-) within the text. Does not identify lack of presence of these characters.



- Symbol: `{2,6}` Regex Code Snipet: `[a-z\.]{2,6}`

![ex5](https://user-images.githubusercontent.com/85651950/138584848-e0361bf7-460f-4c8f-ab28-27b4a3dbc5e1.png)

Identifies multiple lowercase letters (a-z), a dot(.) with a min of 2 characters and a max of 6 characters. This idenfities the URL link at the end, e.g: (.com) (.org) (.ca)



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
