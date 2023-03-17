## Shell Scripting - Hello World

### Objectives

1. Define a variable with the string 'Hello World'
2. Print the value of the variable you've defined and redirect the output to the file "amazing_output.txt"


### Solution
```bash 
#!/bin/bash

out_file=amazing_output.txt
greeting='Hello World'

echo $greeting > $out_file
```                               

### Test
```bash
user@users-MacBook-Pro my_sandbox % ls *.txt
zsh: no matches found: *.txt
user@users-MacBook-Pro my_sandbox % ./hello.sh 
user@users-MacBook-Pro my_sandbox % ls *.txt && cat amazing_output.txt 
amazing_output.txt
Hello World
``` 
