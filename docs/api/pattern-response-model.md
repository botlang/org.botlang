# Pattern/ response model

Botlang's underlying powerful pattern-response model makes the core of the language. It allows the user to define simple string pattern which enable the interpreter to respond with one or more predefined responses. The interpreter is case insensitive.

A pattern definition starts with a plus sign (`+`) followed by a string enclosed in double quotation marks (`"`). A response is defined by a minus sign (`-`) followed by a string enclosed in double quotation marks.

Example:
```
+ "Hey"
- "Hi, how are you?"
```

If more than one response are defined the botlang interpreter will choose one randomly.

Example:
```
+ "Hey"
- "Hi, how are you?"
- "Hey, how are you?"
- "Hi, how is it going?"
```
