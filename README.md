# finalproject220
A mini compiler that takes a simple math expression, breaks it into tokens, validates the structure, builds an expression tree, and prints the result.
All files in this repository are required. Do not delete or move any of them.
Open the file called COMPILER — that is the only program you need to run. Type a math expression when prompted and the compiler will output the token stream, expression tree, and final result.
This project's goal was to make a minicompiler that will take simple expressions. It should take that expression and give the tokens, result and print out a tree that represents the output.
### Lexer
Reads the raw input and converts it into a stream of tokens. Defined with (NUMBER, PLUS, MINUS, etc.)
### Parser
The parser is the set of grammatical rules for the inputs like BIDMAS.
### Syntax Tree Builder
Is created by the parser and it is a display of the operator procedure. 

