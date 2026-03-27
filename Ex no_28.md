# EX 28 C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
## DATE:
## AIM:
To write a C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.

## Algorithm
1.Start. 2. Declare enum type 3. Declare all days in a week 4. Print result 5. End  

## Program:
```
/*
C program that demonstrates the use of enum (enumeration) type to define and use named integer constants.
Developed by: 
RegisterNumber:  
*/
```
```

#include <stdio.h>
enum weekdays {
 Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
};
int main() {
 enum weekdays today = Wednesday;
 if (today == Wednesday) {
 printf("Today is Wednesday.\n");
 }
}
```


## Output:

<img width="465" height="198" alt="image" src="https://github.com/user-attachments/assets/1fd8103c-fa34-40ee-9d77-80dbd4c3c24f" />


## Result:
Thus the program was executed and the output was verified successfully.
