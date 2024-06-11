# maximum number of array
 a program to fin maximum number of array or its index using function.
#include<iostream>
using namespace std;
int minimum(int a[10])
{
int m,index=0;
m=a[1];
for(int j=0;j<10;j++)
{
if(a[j]>m)
{
m=a[j];
index=j;
}
}
cout<<"index="<<index<<endl;
return m;
}
int main()
{
 int b[10],r,i;
for(int i=0;i<10;i++)
{
cout<<"enter a number";
cin>>b[i];
}
r=minimum(b);
cout<<"maximum="<<r;
 return 0;
}
