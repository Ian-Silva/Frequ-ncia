# Frequ-ncia
#include <stdio.h>

int main(int argc, char **argv)
{
    int n,i,k,v[37]={0};



    scanf("%d",&n);

    for(i=0;i<n;i++)
    {
        scanf("%d",&k);
        v[k]++;

    }

    for(i=0;i<36;i++)
    {
        printf("%d, ",v[i]);
    }
    printf("%d. \n",v[i]);





    return 0;
}
