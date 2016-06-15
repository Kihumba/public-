# Outcome 7 - Regular Expressions

**Skill Description**
----------
A regular expression (regex or regexp for short) is a special text string for describing a search pattern.

**Output**
----------

Find the output for this skill [here](Output/README.md)


**Objectives**
----------

## **Knowledge**

| Knowledge Unit   |      Studied      | Applied |
|:-------------|:------------------:|:--------:|
|I can describe the following words: | | |
| <ul><li> Regex | [ ] | [ ]  |
| <ul><li> Regexes     | [ ] | [ ]  |
| <ul><li> Regex Engine       | [ ] | [ ]  |
|I know what the following special characters are used for: | | |
| <ul><li> \ | [ ] | [ ]  |
| <ul><li> ^    | [ ] | [ ]  |
| <ul><li> $      | [ ] | [ ]  |
| <ul><li> . | [ ] | [ ]  |
| <ul><li> \|    | [ ] | [ ]  |
| <ul><li> ?      | [ ] | [ ]  |
| <ul><li> * | [ ] | [ ]  |
| <ul><li> +    | [ ] | [ ]  |
| <ul><li> (      | [ ] | [ ]  |
| <ul><li> ) | [ ] | [ ]  |
| <ul><li> [  | [ ] | [ ]  |
| <ul><li> {      | [ ] | [ ]  |
|I know of the following non-printable characters as well as when/how to use them: | | |
| <ul><li> \r | [ ] | [ ]  |
| <ul><li> \n     | [ ] | [ ]  |
| <ul><li> \t       | [ ] | [ ]  |
| <ul><li> \v       | [ ] | [ ]  |
| <ul><li> \a       | [ ] | [ ]  |
| <ul><li> \f       | [ ] | [ ]  |
|I understand how to create a character set including when to use a: | | |
| <ul><li> Range | [ ] | [ ]  |
| <ul><li> Special characters     | [ ] | [ ]  |
| <ul><li> Negation       | [ ] | [ ]  |
| <ul><li> Subtraction    | [ ] | [ ]  |
| <ul><li> Nested Subtraction      | [ ] | [ ]  |
|I am aware of the different shorthand character classes and their use cases. Including the following: | | |
| <ul><li> \d | [ ] | [ ]  |
| <ul><li> \D    | [ ] | [ ]  |
| <ul><li> \w       | [ ] | [ ]  |
| <ul><li> \W | [ ] | [ ]  |
| <ul><li> \s    | [ ] | [ ]  |
| <ul><li> \S       | [ ] | [ ]  |
|I can effectively describe dot notation as it applies to regular expressions. I know: | | |
| <ul><li> What it represent | [ ] | [ ]  |
| <ul><li> How it relate with line breaks    | [ ] | [ ]  |
| <ul><li> When to use it      | [ ] | [ ]  |
| <ul><li> How it compares with character sets | [ ] | [ ]  |
|I can tell when to use any of the following anchors: | | |
| <ul><li> ^ | [ ] | [ ]  |
| <ul><li> $     | [ ] | [ ]  |
| <ul><li> \A       | [ ] | [ ]  |
| <ul><li> \Z       | [ ] | [ ]  |
| <ul><li> \z       | [ ] | [ ]  |
|I can fully take advantage of the grouping and capturing feature of regular expressions since I fully understand: | | |
| <ul><li> What groups are | [ ] | [ ]  |
| <ul><li> How to create groups     | [ ] | [ ]  |
| <ul><li> How to capture a group       | [ ] | [ ]  |
| <ul><li> What non-capturing groups are       | [ ] | [ ]  |
| <ul><li> How do you retrieve text matched by a captured group       | [ ] | [ ]  |
| <ul><li> What are backreferences using \1, \2     | [ ] | [ ]  |
| <ul><li> What named groups are      | [ ] | [ ]  |
| <ul><li> How to create named groups       | [ ] | [ ]  |
| <ul><li> What branch reset groups really are      | [ ] | [ ]  |
|I know what the following regex modes mean and use cases of application: | | |
| <ul><li> m | [ ] | [ ]  |
| <ul><li> i     | [ ] | [ ]  |
| <ul><li> s       | [ ] | [ ]  |
|I fully understand the concept of `LookAround` and can describe the different kinds of LookAround including: | | |
| <ul><li> Negative lookahead | [ ] | [ ]  |
| <ul><li> Positive lookahead     | [ ] | [ ]  |
| <ul><li> Negative lookbehind       | [ ] | [ ]  |
| <ul><li> Positive lookbehind       | [ ] | [ ]  |

----------


## **Behaviors**

| Observable Behavior   |      Practiced      | Observed |
|:-------------|:------------------:|:--------:|
| **Context:** When writing regular expression... **Action:** I will always comment on the regular expression so that other developers can figure out what kind of pattern I want to match. | [ ] | [ ]  |
| **Context:** When working on strings... **Action:** I only resort to regular expressions if I can’t manipulate a given string using other string methods. |   [ ]   |   [ ]  |
| **Context:** When writing regular expression... **Action:** I make sure they are easy to understand | [ ] |    [ ] |
| **Context:** When working with special kind of inputs from user(eg phone number, email,SSN, ISBN) **Action:** I always validate such inputs using regular expressions. | [ ] |    [ ] |
| **Context:** When writing regular expression... **Action:** I alway take advantage of online tools like [regex 101](https://regex101.com), [regex r](http://www.regexr.com) etc. | [ ] |    [ ] |
| **Context:** When working with inputs from a user... **Action:** I use regular expressions to do the following: <br> <ul><li>Validate the input</li><li>Clean  the input</li><li>Restructure the input</li><li>Look for substrings within the input</li><ul>. | [ ] |    [ ] |


----------


## **Beliefs**


| Embodied Belief   |      Felt      | Demonstrated |
|:-------------|:------------------:|:--------:|
| I believe I can effectively use regular expression for pattern matching. | [ ] | [ ]  |
| I believe I can use regular expressions to find and replace text. | [ ] | [ ]  |
| I believe I there are many use cases for  regular expressions including: <br> <ul><li>Parsing user input</li><li>Parsing various text files</li><li>Examining web server logs</li><li>Examining test results</li><li>Finding text in emails</li><li>Reading configuration files</li><ul>.| [ ] | [ ]  |
| I believe there are cases where regular find/replace is better than using regular expression to find and replace text. | [ ] | [ ]  |
| I believe regular expression is needed to validate text entered by a user eg to validate an email, web address etc. | [ ] | [ ]  |
| I believe regular expressions are powerful and fun to learn and write. | [ ] | [ ]  |
| I believe I can show restraint and only use regular expressions when absolutely necessary. | [ ] | [ ]  |
| I believe I can take advantage of the following resources when learning regular expressions: <br> <ul><li>[Code school course on regular expression](https://www.codeschool.com/courses/breaking-the-ice-with-regular-expressions)</li><li>[Regular expression info](http://www.regular-expressions.info/)</li><li>[Regex crossword](https://regexcrossword.com/)</li><ul> | [ ] | [ ]  |
