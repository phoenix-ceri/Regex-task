# Title (replace with your title)

REGEX Email verification

## Summary
End-Users are known to mistype like the rest of us. So to combat the issue of imputing an invalid email address, programmers are able to use a algorithm to validate wither or not the email is a valid address or a non valid address. 


## Table of Contents

- [Character Classes](#character-classes)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components
 ```
email_pattern = "([a-zA-Z0-9\\_\\-\\.]+)@([a-zA-Z]+).(.+)"
```
Lets break that down to the components 
```
[a-zA-Z0-9\\_\\-\\.]+
```
this is the pattern that check for any number of upper or lowercase letters and  numbers 1-9, this is repetend till there are no letters or numbers left in the given string. this also looks for periods, underscores and hyphens.



### Character Classes
in this example we are looking for letters between a-z both upper and lower case, and numbers between 1-9. we are also including hyphens, underscores, and periods in this.

### Bracket Expressions
the email validation hes a bracket expression looking for the letters between a-z and numbers between 1-9
### Greedy and Lazy Match
we have a greedy match in this example, this repetes the pattern till are charitors are matched


## Author
Phoenix-Ceri Mastin  https://github.com/phoenix-ceri?tab=repositories
