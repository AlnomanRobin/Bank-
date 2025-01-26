# Bank-

#include<stdio.h>
int main()
{
    int num,taka100,taka50,taka20,taka10,taka5,taka2,taka1;
    scanf("%d",&num);
    taka100=num/100;
    taka50=(num-taka100*100)/50;
    taka20=(num-(taka100*100+taka50*50))/20;
    taka10=(num-(taka100*100+taka50*50+taka20*20))/10;
    taka5=(num-(taka100*100+taka50*50+taka20*20+taka10*10))/5;
    taka2=(num-(taka100*100+taka50*50+taka20*20+taka10*10+taka5*5))/2;
    taka1=(num-(taka100*100+taka50*50+taka20*20+taka10*10+taka5*5+taka2*2+taka1*1))/1;
    printf("%d\n",num);
    printf("%d nota(s) de R$ 100,00%d\n",taka100);
    printf("%d nota(s) de R$ 50,00%d\n",taka50);
    printf("%d nota(s) de R$ 20,00%d\n",taka20);
    printf("%d nota(s) de R$ 10,00%d\n",taka10);
    printf("%d nota(s) de R$ 5,00%d\n",taka5);
    printf("%d nota(s) de R$ 2,00%d\n",taka2);
    printf("%d nota(s) de R$ 1,00%d\n",taka1);
    return 0;
}
