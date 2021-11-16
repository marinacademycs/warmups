# Warmup 6


#### 1. Given this code, what is outputted by the printf statements?
```
{
    string myArray[5];
    
    myArray[1] = "hello world";
    myArray[3] = "comp sci";
    
    printf("%c\n", myArray[1][6]);
    printf("%c\n", myArray[3][2]);
}
```
#### 2. Using the above code as a starting point, write out the code to assign the 2nd and 4th items in `myArray` to strings of your choosing.

&nbsp;  
&nbsp;  
&nbsp;  
&nbsp;  

#### 3. What does this program print out?
```
{
  string a = "Chairs";
  
  printf("%c\n", a[0]);
  printf("%c\n", a[3]);
  printf("%d\n", a[3]);
  printf("%c\n", a[6]);
  printf("%d\n", a[6]);
  printf("%lu\n", strlen(a));  //notice strlen usese unsigned int as its data type!
}
```

#### 4. What does the following for loop print? What do you notice that is different about the structure of this for loop? Why do you think that is?

```
string a = "Chairs";

for (int i = 0, n = strlen(a); i < n; i++)
  {
      printf("%c !", a[i]);
  }
    printf("\n");
```

#### 5. What does the following code print?

```
string a ="Hello! How Are You?";

  for (int i = 0, n = strlen(a); i < n; i++)
  {
    if (isupper(a[i]) && isalpha(a[i]))
        printf("%c", tolower(a[i]));
    else
        printf("%c", toupper(a[i]));
  }
    printf("\n");
}
```
