# array
#include<stdio.h>
void main()
{
  int x[3],[3]={{1,2,3},{4,5,6},{7,8,9}};
  int r,c;
  clrscr();
  printf("first value is %d",x[0][0]);
  printf("\n matrix is:\n");
  for(r=0;r<=2;r++)
  {
    for(c=0;c<=2;c++)
      {
        printf("%d",x[r][c]);
      }
    printf("\n")
  }
 getch();
}
