# 25331A05E8-switch-case
#include <stdio.h>
int main(){
    int a,b;
    printf("25331A05E8\n");
    printf("enter the numbers\n");
    scanf("%d%d",&a,&b);
    int choice;
    printf("1.ADDITION\n 2.SUBSTRACTION \n 3.MULTIPLICATION \n 4.DIVISION \n");
    scanf("%d",&choice);
    switch(choice){
        case 1:
        printf("%d",a+b);
        break;
        
        case 2:
        printf("%d",a-b);
        break;
        
        case 3:
        printf("%d",a*b);
        break;
        
        case 4:
        printf("%f",(float)a/b);
        break;
        
        default :
        printf("invalid choice");
        
        return 0;
    }
    
}
