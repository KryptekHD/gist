# Matching an email Regex
 
Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
    
    The purpose of this paper is to help explain what exactlly a regex is and how there are different types that we are able to use to help make our code more efficent and in this case make sure that we are given a valid email. Above is a regex that will look at a email given by a user and check to see if it has the correct formating so that we have a valid email. Each section of the email will be looked at and examined and compaired to the the regex above to make sure that it meets the requierments.

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
The first component of the regex is the [a-z0-9_\.-] this section looks at everything that comes before the @ and checkes to see if any letters that are in it are from a-z and/or contains numbers 0-9 along with any of these special characters _\.-

The second compone is the @  whic is a seperator that meanss anyting in [] that comes after the @ is in the second part of the email.

The third component of the regex is the [\da-z\.-] this partis the next section that comes after the @ in an email, the section above only allows for letters from a-z and anything else wont be accepted 
the. 

The fourth component is thge \. which just means that add a . to the end of the previous section above

The fifth component of this regex is that [a-z\.] and this means that its will only except lettes here 
### Anchors
Anchors match the starting and ending points of a string or line. For example, you can use ^ to match the beginning of a string, and $ to match the end of a string
### Quantifiers
 +: wich allows you to combine mulitipul sections together.
? : Matches zero or one occurrences of the preceding character or character class.
\: Escapes special characters and allows them to be used as literal characters.
^ : Matches the beginning of a string or line

### Grouping Constructs
([a-z0-9_\.-]+)
([\da-z\.-]+)
([a-z\.]{2,6})

### Bracket Expressions
[a-z0-9_\.-]
[\da-z\.-]
[a-z\.]

### Character Classes
a-z
0-9


## Author

Greg DeCarlo
https://github.com/KryptekHD

