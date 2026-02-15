#include<reg51.h>
#define motorpina RB0
#define motorpinb RB1
void main()
{
TRISB0=0X00;
RB0=1;
RB1=0;
delay();
RB0=1;
RB1=1;
delay();
RB0=0
RB1=1;
delay();
RB0=0;
RB1=0;
delay();
}
while(1)
{
void delay()
{
int i,j;
for(i=0;i<1000;i++)
{
for(j=0;j<1000;j++);
}
}
}
