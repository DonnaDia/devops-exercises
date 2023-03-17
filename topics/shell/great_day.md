## Great Day

### Objectives

1. Write a script that will print "Today is a great day!" unless it's given a day name and then it should print "Today is <given day>"

Note: no need to check whether the given argument is actually a valid day

  
### Solution
```bash
#/bin/bash

if [ -z $1 ]; then
        echo "Today is a great day!"
else
        echo "Today is $1"
fi
```
  
### Test
```bash 
user@users-MacBook-Pro my_sandbox % ./great_day.sh 
Today is a great day!
user@users-MacBook-Pro my_sandbox % ./great_day.sh Friday
Today is Friday
```
