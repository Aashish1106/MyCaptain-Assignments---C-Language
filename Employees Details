#include <stdio.h>
#include <stdlib.h>
 
typedef struct{
 
    char name[30];
    char dept[20];
    int id;
    float salary;
 
} Employee;
 
int main()
{
    int i, n=20;
 
    Employee employees[n];
 
    //Taking each employee detail as input
 
    printf("Enter %d Employee Details \n \n",n);
    for(i=0; i<n; i++){
 
        printf("Employee %d:- \n",i+1);
        //Name
        printf("Name: ");
        scanf("%s",employees[i].name);
        //ID
        printf("Id: ");
        scanf("%d",&employees[i].id);
        //Salary
        printf("Salary: ");
        scanf("%f",&employees[i].salary);
        //department
        printf("Department:");
        scanf("%s",&employees[i].dept);
 
        printf("\n");
    }
 
    //Displaying Employee details
 
    printf("-------------- All Employees Details ---------------\n");
 
    for(i=0; i<n; i++){
 
        printf("Name \t: ");
        printf("%s \n",employees[i].name);
 
        printf("Id \t: ");
        printf("%d \n",employees[i].id);
 
        printf("Salary \t: ");
        printf("%f \n",employees[i].salary);
        
        printf("Department \t:");
        printf("%s \n",employees[i].dept);
 
        printf("\n");
    }
 
    return 0;
     
}
