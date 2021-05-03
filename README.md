#include<stdio.h>
main()
{
//1. Display the menu
printf("Pick an item : \n1. Pizza\n2. Burger\n3. Pasta\n4. French Fries\n5. Sandwich");
//2. Read their choice
int choice=0;
scanf("%d" , &choice);
//3. Display based on their choice

switch(choice)
{
case1:
printf("Food item is Pizza and its price is Rs239");
break;
case2:
printf("Food item is Burger and its price is Rs129");
break;
case3:
printf("Food item is Pasta and its price is Rs179");
break;
case4:
printf("Food item is French Fries and its price is Rs99");
break;
case5:
printf("Food item is Sandwich and its price is Rs149");
break;
default : printf("Invalid choice");
}
}
