# Compiler_Langauge_Go
A new programming language is being introduced in the industry for young children. This is 
being designed to introduce the basics of programming using a simpler version of GO 
language. This progarm will design a parser for this language
# Language Specification
This programming language should have basic features to print data, read data, take input 
from user perform arithmetic operations and compressions of value. Currently, it should 
support only integer and single literal character to store the data. A brief description of main 
element take makes up the language is as follow:
1. Basic type of data: integer, char.
2. Keywords: 
a. Decision statement: if elif else
b. Looping statement: while
c. Read data statement: in
d. Function declaration statement: func
e. Write data statement: print (print and remain on same line), println (print 
and move to next line)
3. Arithmetic Operators: + - * /
4. Relational operators: < <= > >= = /=
5. Comments: /* enclose comment in */
6. Identifier: a letter followed by any number of letters or digits
7. Numeric constants: only integers
8. Variable declaration Operator: :
9. Literal constants: a letter enclosed in single quotes.
10. Strings: only used in print statements(no need to declare variables for them)
11. parenthesis, braces, square brackets
12. Aassignment operator: :=
13. Input operators: >>
14. semi colon, colon, comma
# Interface
1. This parser will have a main that asks for file name as input.
2. First the leximal analyzer will run and generate the output of token and lexeme pair in output.txt
3. Then the parser will take that file as an input and generate the parse tree for all the defined CFGs

