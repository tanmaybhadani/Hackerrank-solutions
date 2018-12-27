# Hackerrank-solutions
#include<iostream>
using namespace std;
int main()
{
    int n,i,j,c=0,c1=0,p=-1;
    cin>>n;
    int a[n];
    for(i=0;i<n;i++)
    {
        cin>>a[i];
    }
    for(i=0;i<n;i++)
    {
        c=1;
        for(j=i+1;j<n;j++)
        {
            if(a[i]==a[j])
            {
                a[j]=p;
                c++;
                p--;
            }
        }
        c1+=c/2;
    }
    cout<<c1;
}
