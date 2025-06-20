# C++ -DSA
More Practice Each Questions
# Rectangal Shape 
 #include<iostream>
 using namespace std;
 int main()
 {
     int m;    // m-> Rows and n-> Columns
     cout<<"Enter the Number of rows :";
     cin>>m;
     int n;    // m-> Rows and n-> Columns
     cout<<"Enter the Number of colomns :";
     cin>>n;
     for(int i=1;i<=m;i++)
     {
         for(int j=1;j<=n;j++)
         {
         cout<<"*";
     }
     cout<<endl;
     }
     return 0;
 }
 # Solid Shape star Printing
 #include<iostream>
using namespace std;
int main()
{
    int n;
    cout<<"Enter the Number of rows :";
    cin>>n;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n;j++)
        {
            cout<<"* ";
        }
        cout<<endl;
    }
    return 0;
}
// Print the Number Printing
1 2 3 4 
1 2 3 4 
1 2 3 4 
1 2 3 4 
code
#include <iostream>
using namespace std;
int main()
{
    int n;
    cout<<"Enter Side of Square :";
    cin>>n;
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n;j++)
        {
            cout<<j<<" ";
          
        }
        cout<<endl;
    }
    return 0;
}
Print This Pattern
1 1 1 1 1 1 1 
2 2 2 2 2 2 2 
3 3 3 3 3 3 3 
4 4 4 4 4 4 4 
5 5 5 5 5 5 5 
6 6 6 6 6 6 6 
7 7 7 7 7 7 7 
#include <iostream>
using namespace std;
int main()
{
    int n;
    cout<<"Enter Side of Square :";
    cin>>n;
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n;j++)
        {
            cout<<i<<" ";
          
        }
        cout<<endl;
    }
    return 0;
}
A B C D 
A B C D 
A B C D 
A B C D
code
#include <iostream>
using namespace std;
int main()
{
    int n;
    cout<<"Enter Side of Square :";
    cin>>n;
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n;j++)
        {
            cout<<(char)(j+64)<<" ";
          
        }
        cout<<endl;;
    }
return 0;
}
