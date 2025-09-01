# -program-to-evaluate-the-expression-a-b-c---d-.

 #include <stdio.h>
int main()
{
  int a,b,c,d,z;
  
  printf("enter a\n");
  scanf("%d", &a);
  
  printf("enter b\n");
  scanf("%d", &b);
  

  
  printf("enter c\n");
  scanf("%d", &c);
  
  printf("enter d\n");
  scanf("%d", &d);
  
  z=(a+b)*(c-d);
  
  printf("(a+b)*(c-d) %d" , z);
  
  
}
