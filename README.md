#include<bits/stdc++.h>
using namespace std;
int main()
{
int N,arr[100],i,s=0;
cout<<"\nEnter limit:";
cin>>N;
for(i=0;i<N-1;i++)
{
arr[i]=i+1;
s=s+arr[i];
}
arr[N-1]=s*-1;
for(i=0;i<N;i++)
cout<<arr[i]<<" ";
return 0;
}
