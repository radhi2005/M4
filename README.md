# EX-16-LEFT-SHIFT-OPERATION-&-RIGHT-SHIFT-OPERATION
## AIM
To write a C program to perform the basic left and right shift operation.  

## ALGORITHM
1. Declare an integer a.
2. Input the value of a.
3. Perform a left shift (a << 2) and store the result in left.
4. Perform a right shift (a >> 2) and store the result in right.
5. Print the value of left.
6. Print the value of right.
7. End.

## PROGRAM
```
#include<stdio.h>
int main(){
int a;
scanf("%d",&a);
int left=a<<2;
int right=a>>2;
printf("After Left Shift Operation value of a is:%d",left);
printf("\n");
printf("After Right Shift Operation value of a is:%d",right);
return 0;
}
```
## OUTPUT
![image](https://github.com/user-attachments/assets/60ac87b7-bdec-4260-aa17-c3d1c94c08d5)









## RESULT
Thus the program to perform the basic left and right shift operation has been executed successfully.




 
 


# EX-17-LASTDIGIT-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to find the whether the last digit of given two numbers are equal or not


## ALGORITHM

1. Start.
2. Declare integer variables: num1, num2, lastDigit1, lastDigit2.
3. Input two integers num1 and num2.
4. Find the last digit of num1:
5. lastDigit1 = num1 % 10
6. Find the last digit of num2
7. lastDigit2 = num2 % 10
8. Compare lastDigit1 and lastDigit2:
9. If they are equal
10. Print that they are equal.
11. Else
12. Print that they are not equal.
13. End.

## PROGRAM
```
#include <stdio.h>

int main() {
    int num1, num2, lastDigit1, lastDigit2;
    scanf("%d %d", &num1, &num2);

    lastDigit1 = num1 % 10;
    lastDigit2 = num2 % 10;
    if (lastDigit1 == lastDigit2) {
        printf("%d and %d are equal\n", lastDigit1, lastDigit2);
    } else {
        printf("%d and %d are not equal\n", lastDigit1, lastDigit2);
    }

    return 0;
}

```

## OUTPUT
![image](https://github.com/user-attachments/assets/e3a8d228-93a4-4758-9d1e-3298ba04ea90)

           
## RESULT

Thus the program to find the whether the last digit of given two numbers are equal or not has been executed successfully
 
 


# EX-18-STRING-LENGTH-
## AIM
Write a C Program To find the length of the given string.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using strlen( ) function to find the length of the string.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main(){
    char str[100];
    scanf("%s",str);
    int length=strlen(str);
    printf("Length of Str is %d\n",length);
    return 0;
}
```
## OUTPUT

![image](https://github.com/user-attachments/assets/a97d483a-7aa3-4dd2-b2df-77b159ea842e)



## RESULT
Thus the program To find the length of the given string has been executed successfully
 
 


# EX-19-COUNT-OF-VOWELS-IN-A-STRING
## AIM
Write a C Program to find vowels in a given string using while loop.

## ALGORITHM
1. Start.
2. declare an integer i = 0 
3. declare an integer c = 0 .
4. A character array str of sufficient size 
5. Input a string into str.
6. Loop through the string character-by-character until the null character '\0' is encountered:
7. If the current character is 'a', 'e', 'i', 'o', or 'u':
8. Increment c by 1.
9. After the loop ends, print the value of c (total number of vowels).
10. End.

## PROGRAM
```
#include<stdio.h>
#include<string.h>
int main(){
    int i=0,c=0;
    char str[200];
    scanf("%[^\n]s",str);
    for(i=0;str[i]!='\0';i++){
        if(str[i]=='a'||str[i]=='e'||str[i]=='i'||str[i]=='o'||str[i]=='u'){
            c++;
        }
    }
    printf("%d",c);
    return 0;
}
```
## OUTPUT

![image](https://github.com/user-attachments/assets/f09b8182-a87a-4dbb-a3cf-d9fae63dc6b4)




## RESULT
Thus the program to find vowels in a given string using while loop has been executed successfully
 
 


# EX  -20 LEFT-SHIFT-OPERATION-OPERATION
## AIM
To write a C program to perform the basic left shift operation for 44 integer number with 3 shift.  

## ALGORITHM
1. Declare an integer  n=44.
2. Perform a left shift (n << 3) and store the result in left.
3. Print the value of left.
4. End.

## PROGRAM
```
#include<stdio.h>
int main(){
    int n=44;
    int l=n<<3;
    printf("After Left Shift Operation value of a is:%d",l);
}
```


## OUTPUT
 ![image](https://github.com/user-attachments/assets/3662f738-29a6-4dff-b7fb-9cec79ed8c85)


## RESULT
Thus the C Program to perform the basic left shift operation for 44 integer number with 3 shift has been executed successfully.

