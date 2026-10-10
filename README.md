1st project using only c programming 


#include<stdio.h>
#include<stdlib.h>


int main()
{   float bill,rate[5] ={20,45,30,25,45};
    int p[5],q;
    printf("===== college canteen =====\n");
    printf("->menu\n1. Samosa        ₹20\n2. Sandwitch     ₹45\n3. French fries  ₹30\n4. Steam momos   ₹25\n5. Fried momos   ₹45");
    printf("\nenter Item no ");
    scanf(" %d",&p[0]);
    printf("enter quantity no ");
    scanf(" %d",&q);
    if(p[0]==1){
    printf("Total amount     ₹%f",rate[0]*q);
    }
    if(p[0]==2){
    printf("Total amount     ₹%f",rate[1]*q);
    }
   if(p[0]==3){
    printf("Total amount     ₹%f",rate[2]*q);
    }
    if(p[0]==4){
    printf("Total amount     ₹%f",rate[3]*q);
    }
   if(p[0]==5){
    printf("Total amount     ₹%f",rate[4]*q);
    }
    return 0; 
}