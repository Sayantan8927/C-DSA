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
