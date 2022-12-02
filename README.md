# Postfix Evaluator C

This is a postfix evaluator written in C. It takes a postfix expression as input and evaluates it. It supports the following operators:

`+` `-` `*` `/` `^` `(` `)`

## Usage

To compile the program, run `make` in the root directory. This will create an executable called `postfix`.

To run the program, run `./postfix` in the root directory. This will prompt you for a postfix expression. Enter the expression and press enter. The program will then evaluate the expression and print the result.

## Example

```
$ ./postfix
Enter a postfix expression: 2 3 + 4 *
10
```
