# How-to-create-AP-Series
#include <bits/stdc++.h>
using namespace std;
 
void printAP(int a, int d, int n)
{
 int term;
term=a;
for (int i = 1; i <= n; i++)
{   cout << a << " ";
    a =a + d;
}
}
int main()
{
    cout<< "Enter First Number = " ;
    int a;
    cin >> a;
    cout<< "Common difference = " ;
    int d;
    cin >> d ;
    cout<< "Enter Number of Terms = " ;
    int n;
    cin >> n ;
    cout << "AP is ";
    printAP(a, d, n);
    return 0;
}
