#include<iostream>
#include<conio.h>
using namespace std;
int main()
{
    int cp;
    cout<<"Enter cost price : ";
    cin>>cp;
    int sp;
    cout<<"Enter selling price : ";
    cin>>sp;
    if (sp>cp)
    {
        cout<<"profit";
    }
    if(sp<cp)
    {
        cout<<"loss";
    }
    if(sp==cp)
    {
        cout<<"NO profit no loss";
    }
    getch();
}


