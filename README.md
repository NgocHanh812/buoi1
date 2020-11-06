          BÀI 1


#include <stdio.h>
int main()
  { 
    int n;
  printf("moi ban nhap so n= ");
  scanf("%d",&n);
  if (n % 2 == 0)
    printf("n la so chan");
  else
    printf("n la so le");
  }

 

        BÀI 2

#include <stdio.h>
#include <math.h>
int main()
{
  int a, b;
  int result = a*b;
  printf("Hay nhap so a: ");
  scanf("%d", &a);
  printf("\nHay nhap so b: ");
  scanf("%b", &b);
 if (result>0)
  printf("\na va b cung dau");
 else 
 printf("\na va b trai dau");
  return 0;
}



            BÀI 3

#include <stdio.h>
#include <math.h>
int main()
{ 
  int a, b, h;
  float dt;
  printf("\nNhap do dai day lon a: ");
  scanf("%d", &a);
  printf("\nNhap do dai day nho b: ");
  scanf("%d", &b);
  printf("\nNhap do dai chieu cao h: ");
  scanf("%d", &h);
  dt=(((a+b)/2)*h);
  printf("\ndien tich hinh thang la: %d",dt);
  getch();
  return 0;
}




         BÀI 4

#include <stdio.h>
int main()
{ int a, b;
  printf("\nMoi ban nhap so a: ");
  scanf("%d", &a);
  printf("\nMoi ban nhap so b: ");
  scanf("%d", &b);
//toantu
 (a>b) ? printf("\nSo lon nhat la:%d", a) : printf("\nSo lon nhat la:%d", b);
//if_else
/*if ( a<b)
 printf("\nSo lon nhat la: %d", b);
else
 printf("\nSo lon nhat la: %d", a);*/
  return 0;
}




            BÀI 5

#include <stdio.h>
int main()
{
int t;
  printf("Nhap so t: ");
  scanf("%d", &t);
switch ( t )
 {
  case 1: printf("Thu Hai"); break;
  case 2: printf("Thu Ba"); break;
  case 3: printf("Thu Tu"); break;
  case 4: printf("Thu Nam"); break;
  case 5: printf("Thu Sau"); break;
  case 6: printf("Thu Bay"); break;
  case 7: printf("Chu Nhat"); break;
  default: printf("Hay nhap lai"); break;
 }
   return 0;
}
