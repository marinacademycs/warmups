# Warmup 2: malloc, free, valgrind

### 1. In your own words, describe what each of the following do:

- malloc()
- free()
- valgrind

### 2. Provide code examples of each of the above.

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

### 3. Copy the following two programs that attempt to swap two variables. Which one of these works as intended and why?

ex1:
```
#include <stdio.h>

void swap(int a, int b);

int main(void)
{
    int x = 1;
    int y = 2;

    swap(x, y);
}

void swap(int a, int b)
{
    int tmp = a;
    a = b;
    b = tmp;
}
```

ex2:
```
#include <stdio.h>

void swap(int *a, int *b);

int main(void)
{
    int x = 1;
    int y = 2;

    swap(&x, &y);
}

void swap(int *a, int *b)
{
    int tmp = *a;
    *a = *b;
    *b = tmp;
}
```

