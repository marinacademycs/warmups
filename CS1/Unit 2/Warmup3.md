# Functions Warmup

### 1. In the following code circle the function declaration, function definition, and function call:

    #include <stdio.h>

    int max(int num1, int num2);

    int main (void) 
    {
       int a = 100, b = 200, ret;

       ret = max(a, b);

       printf( "Max value is : %d\n", ret );
    }


    int max(int num1, int num2) 
    {
       int result;

       if (num1 > num2)
          result = num1;
       else
          result = num2;

       return result; 
    }

### 2. Read the following code. How might you improve the design of this if statement?  

```
    if (first2 == 40 || first2 == 41 || first2 == 42 || first2 == 43 ... first2 == 48 || first2 == 49)
```
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;

### 3. In the code in question 1, the variables in `main` are named `a` and `b`, but they don't appear anywhere in my function even though I call max with those variables as inputs. Why?

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

### 4.  Write pseudocode for a function that takes three integers as parameters and returns the largest integer.


