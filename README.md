#include <stdio.h>
#include <conio.h>
#include <string.h>
int main()
{
    double username;
    int password;
    printf("*****************************welcome to ABC matric Hr Sec School*********************\n");
    printf("           Username:");
    scanf("%lf",&username);
    printf("           Password:");
    scanf("%d",&password);
    if(username== 519982)
    {
        if(password==12345)
        {
            printf("Login successfull!\n");
            printf("-------------------------------------------------------------\n");
            printf("Name: U.Ajitha  Roll No: 519982\n");
            printf("     ==============================================================\n");
            printf("         S.No\t\t\tSUBJECT\t\t\tMarks\n");
            printf("     ==============================================================\n");
            printf("          1  \t\t\tEnglish\t\t\t 85\n");
            printf("     ==============================================================\n");
            printf("          2  \t\t\tTamil\t\t\t 95\n");
            printf("     ==============================================================\n");
            printf("          3  \t\t\tMaths\t\t\t 97\n");
            printf("     ==============================================================\n");
            printf("          4  \t\t\tScience\t\t\t 91\n");
            printf("     ==============================================================\n"); 
            printf("          5  \t\t\tSocial\t\t\t 95\n");
            printf("     ==============================================================\n");
            printf("                    \t\tTotal\t\t\t463\n");
            printf("     ==============================================================\n");
            printf(" \t\t\t\tYou have Passed!\n\n\n");
            printf("*******************************Thank You***************************");
        }
        else
        {
            printf("password is incorrect ,Try again.");
        }
    }
    else
    {
        printf("username is incorrect,Try again. ");
    }
    /* else
    {
        printf("Both username and password  is  incorrect");
    }*/
}
