# Unit 0 - Warmup 9, Exit Codes and Command Line Arguments

## Warmup Problems
#### 1. What terminal command do you use to view the exit code a program exited with?

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;   

#### 2. There are errors with the following program. They could be syntax or logical errors. Can you find them?
```
import sys

def main():
    argv_length = len(sys.argv)

    if argv_length > 2:
        print("Too many arguments.")
    elif argv == 1:
        print("One argument entered")

    if sys.argv[1] == '8':
        print("8")
    elif sys.argv[2] == '9':
        print("9")
    elif sys.argv[3] == '10':
        print("10")
    else:
        print("How did the world come to this?")
        exit(1)

main()
```

#### 3. Write a program that does the following:

- Accepts commdand line arguments
- If no arguments are given, exit 1 and print the message "You forgot the arguments"
- If between 2 and 4 arguments are given, exit 2 print the message "You reached he goldilocks zone."
- If more than 4 arguments are given, print "Woah, that's too many"
- If the 3rd argument is "hello" (any version with capitals and lower case letters), print "Goodbye"
- print all command line arguments.


## Practice Problem for Today

#### Write a program in Python to remove duplicate items from a list.

First, create a list with 1000 random integers between 0 and 200.
Next, remove any duplicates. If a duplicate is removed, print out a message that you removed duplicate X, where X is the number removed.
Finally, print out the list without any of the duplicates.

For example:  

```
    myList = [ 12, 45, 2, 3, 5, 3, 4, 4, 1, 2, 12 ]    
```

Output:
```
    Removed 2
    Removed 3
    Removed 4
    Removed 12
    [ 12, 45, 2, 3, 5, 4, 1 ]
```
