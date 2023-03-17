## Argument Check

### Objectives

Note: assume the script is executed with an argument

1. Write a script that will check if a given argument is the string "pizza"
 1. If it's the string "pizza" print "with pineapple?"
 2. If it's not the string "pizza" print "I want pizza!"

### Solution

```bash 
#!/bin/bash

if [ $1 == "pizza" ]; then
        echo "with pineapple?"
elif [ $1 != "pizza" ]; then
        echo "I want pizza!"
fi
```

### Test
```bash
user@users-MacBook-Pro my_sandbox % bash pizza.sh cheese
I want pizza!
user@users-MacBook-Pro my_sandbox % bash pizza.sh pizza 
with pineapple?
```
