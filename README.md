# Valid Parentheses (C++)

A small console program that checks whether an input string has correctly matched and nested parentheses, braces, and square brackets.

## How it works

The program uses a stack. It pushes each opening bracket, then checks each closing bracket against the most recent opener. It reports the input as valid only when every pair matches and the stack is empty at the end.

## Build and run

Requires a C++11-compatible compiler.

```sh
g++ -std=c++11 valid_parentheses.cpp -o valid_parentheses
./valid_parentheses
```

Enter a bracket string when prompted, for example `()[]{}` or `([)]`. The program reads one whitespace-delimited string.
