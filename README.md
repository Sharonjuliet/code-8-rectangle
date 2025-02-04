#include <stdio.h>

int main()
{
    int n,m,i,j;
    printf("enter the row size of the matrix:\n");
    scanf("%d",&n);
    printf("enter the column size of the matrix:\n");
    scanf("%d",&m);
    for(i=0;i<n;i++){
        for(j=0;j<m;j++){
            printf(" *");
        }
        printf(" \n");
    }

    return 0;
}
