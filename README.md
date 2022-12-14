# Postfix Evaluator C

This is a postfix evaluator written in C. It takes a postfix expression as input and evaluates it. It supports the following operators:

`+` `-` `*` `/` `^` `(` `)`

## Usage

To compile the program, run `gcc PostfixEvaluator.c -o PostfixEvaluator` in the root directory. This will create an executable called `PostfixEvaluator`.

To run the program, run `./PostfixEvaluator` with the postfix expression as an argument. For example, `./PostfixEvaluator 23+` will evaluate `2 + 3` and print `5`.

## Example

```
$ ./PostfixEvaluator "25+"
7

$ ./PostfixEvaluator "29*"
18

$ ./PostfixEvaluator "642+*"
36
```

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.

© Copyright Max Base, 2022
