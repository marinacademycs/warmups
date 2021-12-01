# Unit 3, Warmup 2

### 1. What search algorithm is the code below implementing?

```
#include <stdio.h>
int main()
{
  int array[] = {54, 23, 76, 12, 1, 987, 43 , 19, 24, 9, 6, 0, 123, 4, 15};
  int length = 15;  
  int current_position, temp;

  for (int i = 0; i < length; i++)
  {
    current_position = i;

    for (int j = i + 1; j < length; j++)
    {
      if (array[current_position] > array[j])
        current_position = j;
    }
    if (current_position != i)
    {
      temp = array[i];
      array[i] = array[current_position];
      array[current_position] = temp;
    }
  }

  printf("Sorted list in ascending order:\n");

  for (int i = 0; i < length; i++)
    printf("%d\n", array[i]);

  return 0;
}
```

### 2. Based on the code below, what do you think the function `strcmp()` does?

```
#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
    string names[] = {"Bill", "Charlie", "Fred", "George", "Ginny", "Percy", "Ron"};

    for (int i = 0; i < 7; i++)
    {
        printf("%d\n", strcmp(names[i], "Ron"));
        if (strcmp(names[i], "Ron") == 0)
        {
            printf("Found: %s\n", names[i]);
            return 0;
        } 
    }
    printf("Not found\n");
    return 1;
}
```

&nbsp;  
&nbsp;  
&nbsp;  

### 3. Read through the following code. Try to figure out what is going on. Make notes of what you understand and what you don't.

```
#include <cs50.h>
#include <stdio.h>
#include <string.h>

typedef struct
{
    string name;
    string number;
}
person;

int main(void)
{
    person x;
    person y;

    x.name = "Kyle";
    x.number = "+1-415-867-5309";

    y.name = "Eric";
    y.number = "+1-425-555-1000";

    printf("The name of Mr X is %s and his number is %s.\n", x.name, x.number);
    printf("The name of Mr Y is %s and his number is %s.\n", y.name, y.number);
}
```
