// C program to check whether you can drive or not.

#include<stdio.h>

int main()

{
    int age;
    
    printf("Enter your age : ");
    scanf("%d", &age);
    
    if(age>=80) //if age is greater than equal to 80
    {
        printf("You are above 90, you cannot drive");
    }
    
    if(age<=18) //if age is less than equal to 80
    {
        printf("You cannot drive");
    }
    
    else //if age is between 19-79
    {
        printf("You can drive");
    }

    return 0;
}
// ![Screenshot (3)](https://user-images.githubusercontent.com/81368657/200573682-aec071ab-ccc3-4012-b9ac-58da3b505b26.png)
