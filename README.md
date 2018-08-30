#include<iostream.h>
#include<conio.h>
void main()
{
    clrscr();
    int n; float s;
    cout<<"Enter the number whose log you want to calculate:";
    cin>>n;
    s=log10(n);
    cout<<"The log of "<<n<<" is:"<<s;
    getch();
}
