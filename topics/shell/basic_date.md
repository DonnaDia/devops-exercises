## Basic Date

### Objectives

1. Write a script that will put the current date in a file called "the_date.txt"

### Solution
```bash
#!/bin/bash

#the command will append current date to the output file
echo $(date) >> the_date.txt
```
### Test
```bash
user@users-MacBook-Pro ~ % chmod +x shelldate.sh && ./shelldate.sh && cat the_date.txt
Fri Mar 17 08:29:06 CET 2023
user@users-MacBook-Pro ~ % ./shelldate.sh && cat the_date.txt 
Fri Mar 17 08:29:06 CET 2023
Fri Mar 17 08:29:27 CET 2023
```
