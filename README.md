# PARKING-BIILL-GENERATOR
#include<stdio.h>
int main (){
    char CustomerId[10],CustomerName[30],CustomerPhoneNo[20],CustomerType[10];
    int hours=0,rate=0,total=0,bike,car;
    float rupees;
    printf("                           PARKING BILL\n");
    printf("========================================================================\n");
    //custmoer details
    printf("Enter Customer Id:");
    scanf("%s",&CustomerId);
    printf("Enter Customer Name:");
    scanf("%s",&CustomerName);
    printf("Enter Customer Phone No:");
    scanf("%s",&CustomerPhoneNo);
    printf("Enter vehicle type(car/bike):");
    scanf("%s",&CustomerType);
    printf("Enter of hours parked:");
    scanf("%d",&hours);
    //rate details
    if(CustomerType[3]==car){
       rate=20;
    }
        else{(CustomerType[4]==bike);
        rate=10;
        };
    total=rate*hours;
     printf("total bill:%d",total); 
     return 0;
}
