## Basic Date

### Objectives

1. Write a script that will put the current date in a file called "the_date.txt"

### Solution
```bash
#!/bin/bash

echo $(date) >> the_date.txt
```
### Test
```bash
user@users-MacBook-Pro ~ % cat the_date.txt
Fri Mar 17 08:23:58 CET 2023
Fri Mar 17 08:24:07 CET 2023
```
