#  Module-1 Day-2 SEB 
## AIM:
To write a C program to read two number and check whether the first number is equal to 5 or not and if equal to 5 then check whether the second number is equal to 10 or not using  nested if.

## For example:
<img width="328" height="97" alt="image" src="https://github.com/user-attachments/assets/8fd9c0bf-d6af-4b87-b3b0-308e6458c85a" />

## Programme:
```c
#include <stdio.h>
int main()
{ 
    int a,b;
    scanf("%d %d",&a,&b);
    if (a==5){
     printf("The first number is equal to 5\n");
        if(b==10){
        printf("The second number is equal to 10");
        }
        else{ 
            printf("The second number is not equal to 10");
         }
    }
      else{
          printf("The first number is NOT equal to 5");
    }
      return 0;
    }
```
## Output:
<img width="746" height="192" alt="image" src="https://github.com/user-attachments/assets/949aa5b3-d9d5-4a05-9c81-bc779092b791" />


