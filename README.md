#include<stdio.h>
#include<conio.h>
int main(){
    int choice;
    //Display the menu 
    printf("1.Pizza-Rs.239\n");
    printf("2.Burger-Rs.129\n");
    printf("3.Pasta-Rs.179\n");
    printf("4.French Fries-Rs.99\n");
    printf("5.Sandwich-Rs149\n");
    printf("\n");


    //input the random number from the user
    printf("Enter your number: ");
    scanf("%d",&choice);
    printf("\n");
    

    //display the menu based on the user choice
    switch (choice)
    {
    case 1:printf("Food item-Pizza\n");
           printf("Price-Rs 239");
        break;
    case 2:printf("Food item-Burger\n");
           printf("Price-Rs 129");
        break;
    case 3:printf("Food item-Pasta\n");
           printf("Price-Rs 179");
        break;
    case 4:printf("Food item-French Fries\n");
           printf("Price-Rs 99");
        break;
    case 5:printf("Food item-Sandwich\n");
           printf("Price-Rs 149");
        break;
    default:printf("Invalid choice ");
        break;
    }

    return 0;


}
