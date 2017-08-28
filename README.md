4
#include<stdio.h>
void jolly(void);
void deny(void);
int main(void)
{
       printf("1.\n");
       jolly();
       deny();
       getchar();
       return 0;                //return 0后的“；”不能省！！！
}
void jolly(void)
{
       printf("2.\n");          //"xxxxxxxxxx.\n"!!!

}
void deny(void)
{
       printf("3.\n");

}
5
#include<stdio.h>
void br();
void ic();
int main(void)
{
       printf("Brazil,Russia,India,China.\n");
       ic();
       br();
       getchar();
       return 0;
}
void ic(void)
{
       printf("India,China.\n");//{;}!!!
}
void br(void)
{
       printf("Brazil,RUssa.\n");//{;!!!}
}
6
#include<stdio.h>
int main(void)
{
       int toes,toes2,toes3;//声明后要加；！！！实在找不到bug就再写一遍

       toes=10;
       toes2=toes * 2;
       toes3=toes*toes;
       printf("toes=%d and toes的两倍=%d and toes的平方=%d.\n", toes, toes2, toes3);
       getchar();
       return 0;

}


