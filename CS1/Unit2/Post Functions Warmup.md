# Post-Functions Warmup

### 1. What is wrong with the following code?

```
#include <stdio.h>

int main(void)
{
    int a = 5, b = 10, c = 12;
    
    if (a >= b || c)
    {
        printf("A is biggest.\n");
    }
    else
    {
        printf("A is not the biggest.\n");
    }
}
```

### 2. What is printed out in the following program?

```
#include <stdio.h>
#include <cs50.h>
#include <string.h>

int main(void)
{
    string s = "Hello CS Students!";
    
    for (int i = 0; i < 5; i++)
        printf("%c\n", s[i]);
    
    for (int i = 0; i < strlen(s); i++)
        printf("%c", s[i]);
    printf("\n");
    
    printf("The 18th char is %c\n", s[17]);
    printf("The 25th char is %c\n", s[25]);

}
```

### 3. If you have yet solved this problem, do so now in your group:

Write a function that takes a long integer and reverses it, so 12345 should return 54321.

If you have solved that problem, please complete this followup problem:

Open the code where you reversed the integer. Now create another function in the same file called `isPalindrome` that takes a single long int as input and tests whether it is a palindrome or not. The `isPalindrome` function should call the function that reverses the integer. The reverse function should reverse the long number and return to isPalindrom. IsPalindrime should return True or False. The program flow should work like this:

```
main (gets the nubmer) > isPalindrome > reverseNumber > isPalindrome > main
```
