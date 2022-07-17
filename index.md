## Basics:

1- Write a C program to print “Software Engineering”. Make use of ‘Comment’ in the file.

```markdown

#include <stdio.h>

int main()
{
    // single line comment
    printf("Software Engineering");

    return 0;
}

```

2- Write a C program to perform input & output operations of all basic data types.

```markdown



```

3- Write a C program that will include your knowledge on constants and symbolic constants. 

```markdown



```

4- Write a C program to perform arithmetic operations.

```markdown



```

5- Write a C program to check the differences between pre, post increment and decrement operators.

```markdown



```

6- Write a C program that takes hours and minutes as input, and calculates the total number of minutes.

```markdown

#include<stdio.h>
void main()
{
    int a,b,c;
    scanf("%d%d",&a,&b);
    c=a*60+b;
    printf("total minute=%d",c);
}


```

7- Write a C program that will take a sentence as an input and will print that.

```markdown


```

8- Write a C Program to find the Size of data types

```markdown

#include<stdio.h>
int main()
{
    printf("Size of char: %ld byte\n",sizeof(char));
    printf("Size of int: %ld bytes\n",sizeof(int));
    printf("Size of float: %ld bytes\n",sizeof(float));
    printf("Size of double: %ld bytes", sizeof(double));
    return 0;
}

```

9- Write a C Program to Print ASCII Value

```markdown

#include <stdio.h>  
int main()  
{  
    char ch; 
    printf("Enter a character");  
    scanf("%c",&ch);
    printf("\n The ascii value is: %d", ch);  
    return 0;  
}  

```

10- Write a C program to Calculate Area of Square

```markdown

#include <stdio.h>  
int main()  
{  
    float area, side; 
    printf("Enter the length of a side: ");  
    scanf("%f",&side);
    area = side*side;
    printf("Area of a square is: %f", area);  
    
    return 0;  
} 

```

11- Write a C Program to Calculate Area of Rectangle

```markdown

#include <stdio.h>  
int main()  
{  
    int l, b, area; 
    printf("Enter the length: ");  
    scanf("%d",&l);
    printf("Enter the breadth: ");  
    scanf("%d",&b);
    area = l*b;
    printf("Area of a Rectangle is: %d", area);  
    
    return 0;  
}  

```

12- Write a C Program to convert days to years, weeks and days.

```markdown

#include <stdio.h> 
int main()
{
    int d, years, weeks, days;
    printf("Enter Days:");
    scanf("%d",&d);

    years = d/365; 
    weeks = (d % 365)/7;
    days  = (d*365)%7;

    printf("Years: %d Weeks: %d Days: %d", years, weeks, days);

    return 0;
}

```

13- Write a C Program to convert Celsius value into Fahrenheit value. (Formula : F = 9C ∕ 5 +32;

```markdown

#include <stdio.h> 
int main()
{
    float c, F;
    printf("Enter Celsius:");
    scanf("%f",&c);
    
    F = 9*c/5+32;

    printf("Fahrenheit Value is: %f", F);

    return 0;
} 

```


## Conditional:

## Loop:

1- Write a C program to print even numbers between a range of numbers, For   example, from 1-10, using a for,while & do-while loop.

```markdown

#include <stdio.h>  
   
int main() {  
    int i; 
    printf("Even numbers between 1 to 10 Using For Loop\n"); 
    
    for(i = 1; i <= 10; i++) {  
        if(i%2 == 0) { 
            printf("%d ", i);  
        }  
    } 
    
    int w=1;
    printf("\nEven numbers between 1 to 10 Using While Loop\n"); 

    while(w <=10 ){
        if(w%2 == 0) { 
            printf("%d ", w);  
        } 
        w++;
    }
    
    int d=1;
    printf("\nEven numbers between 1 to 10 Using Do While Loop\n"); 
    do {
        if(d%2 == 0) { 
            printf("%d ", d);  
        }  
        d++;
    }
    while(d <= 10);
   
    return 0;  
}

```

2- Write C program to print alphabets from a to z

```markdown

#include <stdio.h>
int main() {
    char c;
    for (c = 'A'; c <= 'Z'; c++){
        printf("%c ", c);
    }
    return 0;
}

```

3- Write C program to print ASCII values of all characters

```markdown

#include <stdio.h>
int main() {
    char c;
    for (c = 'A'; c <= 'Z'; c++){
        printf("%d ", c);
    }
    
    printf("\n");
    
    for (c = 'a'; c <= 'z'; c++){
        printf("%d ", c);
    }
    return 0;
}

```

4- Write C program to print multiplication table of a given number

```markdown

#include <stdio.h>
int main() {
    
  int n, i;
  printf("Enter an number: ");
  scanf("%d", &n);
  
  for (i = 1; i <= 10; ++i) {
    printf("%d * %d = %d \n", n, i, n * i);
  }
  return 0;
}

```

5- Write a C program to print all natural numbers in reverse order

```markdown

#include <stdio.h>
int main()
{
    int i, start;

    printf("Enter Number: ");
    scanf("%d", &start);

    for(i=start; i>=1; i--){
        printf("%d\n", i);
    }

    return 0;
}

```

6- 

```markdown



```

7- Write C program to find sum of even numbers between 1 to n

```markdown

#include <stdio.h>
int main()
{
    int i, n, sum=0;

    printf("Enter Number: ");
    scanf("%d", &n);

    for(i=2; i<=n; i+=2)
    {
        sum = sum+i;
    }

    printf("Sum of all even number between 1 to %d = %d", n, sum);

    return 0;
}

```

8- Write C program to find sum of odd numbers between 1 to n

```markdown

#include <stdio.h>
int main()
{
    int i, n, sum=0;

    printf("Enter Number: ");
    scanf("%d", &n);

    for(i=1; i<=n; i+=2)
    {
        sum = sum+i;
    }

    printf("Sum of all Odd number between 1 to %d = %d", n, sum);

    return 0;
}

```

8- Write a C Program to display the following different triangles.

```markdown

#include <stdio.h>
int main()
{
    int n,row,col;
    printf("Enter number: ");
    scanf("%d",&n);
    
    for(row=1; row<=n; row++){
        for(col=1; col<=row; col++){
            printf("* ");
        }
        printf("\n");
    }
}

```

## Switch Case:

## Function & Recursion:

