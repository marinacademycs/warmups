# Warmup 5
(Includes practice problems on back)

#### 1. Given this code, what is outputted by the printf statements?
```
int main (void)
{
    string myArray[3];
    int a = 0;
    
    myArray[0] = "3a";
    myArray[1] = "hello";
    myArray[2] = "biology";
    
    printf("%s", myArray[2]); 
    printf("%s", myArray[a]); 
    printf("%s", myArray[a + 1]);
    printf("%s", myArray[(a - 1) * (a - 1)]); 
}
```

#### 2. What does check50 do? Where can you see/check the results of check50?
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

#### 3. How are strings related to arrays?
&nbsp;  
&nbsp;  
&nbsp;  
&nbsp; 
&nbsp; 

#### 4. What's wrong with this program?

```
int addTwoNums(int a, int b);

int main (void)
{
  a = 10;
  b = 12;
  printf("Sum is %d", addTwoNums(10,12));
}

int addTwoNums()
{
  int a;
  int b;
  return a + b;
}
```

<div style="page-break-after: always;"></div>


# Practice Problems
## Arrays
#### A. Write a program in C to store elements in an array and print it.

#### B. Write a program in C to read n number of values in an array and display it in reverse order. Hint: user a `for` loop where `i` counts down instead of up.

## Strings
#### C. Write a program in C to input a string and print it.

#### D. Write a program in C to find the length of a string without using library function. (Quick, how do you easily get the length of a string?)

#### E. Write a program in C to separate the individual characters from a string:

helloword > `h e l l o w o r l d`

#### F. Write a program in C to count the total number of words in a string.
