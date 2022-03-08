# Warmup 1 - Unit 1 -  The Return of C!

### 1. In the following code, find the following:

- functions
- function prototype
- variables and variable types
- conditionals
- and / or
- loops
- constants
- custom types
- comments
- commandline arguments
- arrays

```
#include <cs50.h>
#include <stdio.h>
#include <string.h>

#define MAX 9

typedef struct
{
    string name;
    int votes;
}
candidate;

candidate candidates[MAX];

int candidate_count;

bool vote(string name);
void print_winner(void);

int main(int argc, string argv[])
{
    if (argc < 2)
    {
        printf("Usage: plurality [candidate ...]\n");
        return 1;
    }

    candidate_count = argc - 1;
    if (candidate_count > MAX)
    {
        printf("Maximum number of candidates is %i\n", MAX);
        return 2;
    }
    for (int i = 0; i < candidate_count; i++)
    {
        candidates[i].name = argv[i + 1];
        candidates[i].votes = 0;
    }
    
    int voter_count = get_int("Number of voters: ");
    
    for (int i = 0; i < voter_count; i++)
    {
        string name = get_string("Vote: ");
        if (!vote(name))
            printf("Invalid vote.\n");
    }
    print_winner();
}

bool vote(string name)
{
    for (int i = 0; i < candidate_count; i++)
    {
        if (!strcmp(name, candidates[i].name))
        {
            candidates[i].votes++;
            return true;
        }
    }
    return false;
}

void print_winner(void)
{
    int max = 0;
    for (int i = 0; i < candidate_count; i++)
    {
        if (candidates[i].votes > max)
            max = candidates[i].votes;
    }

    for (int i = 0; i < candidate_count; i++)
    {
        if (candidates[i].votes == max)
            printf("%s\n", candidates[i].name);
    }
}
```

### 2. Using the space below, can you remember how to write a simple C program that asks a user for two numbers, adds them, and prints the result? Check your work using the CS50 IDE.

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

## Part 2: Hexadecimal (After mini lesson)

Convert the following from decimal numbers to hexadecimal (these numbers represent RGB values):

- 66, 166, 88
&nbsp;  

Convert the following from hexadecimal to decimal:

- B4, CE, E6
