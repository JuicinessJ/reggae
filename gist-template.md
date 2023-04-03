# The RegEx || REGGAE

Welcome, here we'll go over what these regex ideas do and what they're functions are. 

## Summary

Regular Expression, also known as RegEx to others is a sequence of characters that specifies a pattern in the text. This is generally used inside a string-searching algorithm to find or find and replace a string. It’ll take a control or basis which would be your RegEx sequence. This will compare against a database of strings or a given string to validate if the RegEx sequence matches your input or the database of strings. 

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

An anchor is a character that lets the algorithm know where the start and end of the sequence are. This sequence will be the basis for the algorithm and will be compared with other strings in databases or inputs. The character that indicates this is the beginning of the sequence is the "^" and the end is the "$".

### Quantifiers

A quantifier is another character that allows the creator to specify how many characters or classes should be matched. These characters will be the “*” for matching zero or more occurrences before the usage of the character. As for “+” will be matching one or more occurrences before the usage of that character. 

### OR Operator

The OR Operator or the Alternation Operator allows the creator to specify multiple searching patterns. This character is the "|" which allows the creator to match either 2 characters besides the usage of the character. This operator is commonly used with the usage of boolean statements such as IF and Switch Case statements. 

### Character Classes

The character class allows the creator to define specific sets of characters to be used inside the sequence. This has multiple characters that can be used for different results. By using “\d” you can match any digit between 0 and 9. “\w” matches alphanumeric characters which include lowercase, uppercase, and numbers. 

### Flags

The flags are a set of instructions that changes the behavior of our sequence. 

### Grouping and Capturing

Grouping and Capturing. To start, your grouping character is the parentheses or “(...)” This will group together a partial meant to be compared against. Whatever is inside the parentheses will be compared against the input.

### Bracket Expressions

The Bracket is similar to the parentheses however, it’ll match with anything in between, while the parentheses are strictly looking for the value.

### Greedy and Lazy Match

The Greedy Quanitier. The greedy functions in an odd way. To start off it’ll look for the first character inside the sequence to compare against the input. Which starts off normal it’ll keep going down the input’s position until the character is found. Once found it’ll go toward the next sequence character. It’ll keep going down the entire input until it has either found the sequence character or it runs out of input length. If it were to run out, it’ll backtrack until the next sequence character is found. Once found the first character that was considered a match to the last character consider a match will be returned.

The Lazy Quantifier. The opposite of Greedy. Instead of going down the line looking for the second character inside the sequence. The sequence will actually go down the line until the next character inside the sequence is a match to the input. This means it’ll look for an open and a close which will return a shorter value. 


### Boundaries

There are 4 types of boundaries. Word, Not a Word, and Left or Right Word Boundary. The Word boundary character is the “\b” depending on how it is used will have 2 different results. By using the boundary before the sequence it’ll strictly look for inputs that begin with the sequence while using the boundary towards the end will do the opposite. However, using the boundary on both sides simultaneously will strictly look for the sequence regardless of whether the input begins or ends.

As for Not A Word, The character would be the “\B” an uppercase B. This boundary works similarly to how Word functions. However, with an added benefit of looking in between characters of a word. If the word possesses the sequence in the middle it’ll be returned. Now based on where the boundary is stated either at the beginning or the end of the sequence will function the same as the word boundary does. 

Finally, The Left or Right Word Boundary. It possesses a special character. Instead of “\” it uses, “[[:<:]]” or “[[:>:]]”. If the arrow used is pointing towards the left it’ll mean it's looking for the beginning of the word now the opposite also applies here. If the arrow points to the right it’ll look for the ending of the word. Now depending on where the sequence letters are placed on either the left or the right side of the boundary will have different results. 

### Back-references

The Back-References will match the same text is has previously been matched by the capturing.

### Look-ahead and Look-behind

The look-ahead or look-behind is a tool that allows the creator access to looking ahead of behind which is included in the match. Adding the match with a look ahead of behind the tag will look for every possible instance of the mentions in either ahead of behind in the sentence.

## Author

https://github.com/JuicinessJ
