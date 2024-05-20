# c-code
// #include<stdio.h>
// int main() {
//     int i=0;
//     int n;
//     printf("enter the value of n \n");
//     scanf("%d", &n);


//     do{
//        printf("the number is %d \n", i+1);
//         i++;
//     }while(i<n);
//     return 0;
// }
// #include<stdio.h>

// int main() {
//     int i=0;
//     int n;
//     printf("enter the numbr \n");
//     scanf("%d", &n);                                                                                
//     for{
//         printf("the numbr  %d \n", i+1);
//         i++;
//         if{
//            printf(i<n); 
//         }
    
//     }
//     return 0;
// }
 
// TODO:  this  function should  be implemented  by the  compiler
// #include<stdio.h>

// int main() {
//     int n;
//     printf("enter the numbr \n");
//     scanf("%d", &n);                                                                                
//     for(int i=n; i;  i--){
//         printf("the value of i is  %d \n", i);
//         }
//        return 0;
//     }
    
 
file io 

#include<stdio.h>

int main() {
    FILE *ptr;
    int num;
    ptr = fopen("yavi.c", "r");   
    if (ptr == NULL) {
        printf("the file doesn't exist please write the coorect file name \n");
    
    }
    else{
    fscanf(ptr, "%d", &num);    
    printf(" the value of the number in ths file : %d\n", num);
    }
    return 0;
}
