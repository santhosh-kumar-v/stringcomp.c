#include<stdio.h>
#include<string.h>

int main() {
 char str[1000];
 int i,j,c=1;
 scanf("%s",str);
 int l=strlen(str);
 while(i<l)
 {
     for(j=i+1;j<l;j++)
     {
         if(str[i]==str[j])
            c++;
          
            else
            break;
     }
 printf("%c%d",str[i],c);
 c=1;
 i=j;
 }
}
