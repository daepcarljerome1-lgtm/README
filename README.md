# Reverse App 

## Compilation & Run
```bash
javac ReverseApp.java Reverser.java StackX.java
java ReverseApp


Features

- Reverse entire string

- Reverse each word in-place

- Palindrome checker (ignores spaces/punctuation/case)

- Balanced brackets validator

Enhancements Implemented

- CLI menu for choosing tasks

- Refactored StackX into a generic class

Sample I/O

1. Reverse Entire String
Input: Carl Jerome Daep
Output: peaD emoreJ lraC

2. Reverse Each Word In-Place
Input: Carl Jerome Daep
Output: lraC emoreJ peaD

3. Palindrome Checker
Input: No lemon, no melon
Output: true

4. Balanced Brackets Validator
Input:  {[()]}
Output: Balanced!

4. Balanced Brackets Validator
Input: {[(])}
Output: Error: mismatched ']' at position 3 

Complexity

- Reverse string: O(n) time, O(n) space

- Reverse words: O(n) time, O(n) space

- Palindrome checker: O(n) time, O(n/2) space

- Bracket validation: O(n) time, O(n) space
