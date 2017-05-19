# Multiple Choice Matching

The multiple choice matching pattern let you define an arbitrary array of matching options. Multiple
choice options are enclosed by parentheses and separated by the pipe character
`(option_one|option_two|...)`.

Example:
```
+ "* (bye|goodbye|done|exit|quit) *"
- "Goodbye. It was nice talking to you."
- "Goodbye. This was really a nice talk."
```
