
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    char s[1000];
    gets(s);
    int x[10]={0};
    int i;
    for(i=0;s[i]!='\0';i++)
    {
        if(s[i]>='0'&& s[i]<='9')
        {
            int val=s[i]-'0';
            x[val]=x[val]+1;
            
        }
    }  
    for(i=0;i<10;i++)
    printf("%d ",x[i]);
    return 0;
}
