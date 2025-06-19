#include<iostream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    for(int i=0;i<n;i++){
        for(int j=0;j<n-i;j++){
            cout<<" * ";
        }
        cout<<"\n";
    }
}

patten//02(TRAINGLE)

#include<iostream>
using namespace std;
int main()
{
    int n=5;
    for(int i=0;i<n;i++)
        {
            for(int j=0;j<n;j++){
                cout<<" ";
                
                if(i+j==n-1||i==j){
                cout<<"*";
            }
            else {
               cout<<" ";
        }
    }
      cout<<"\n";  
    }
    
}

patten//03(Z PATTEN)

#include<iostream>
using namespace std;
int main()
{
    int n=5;
    for(int i=0;i<n;i++)
        {
            for(int j=0;j<n;j++){
                cout<<" ";
                
                if(i+j==n-1||i==0||i==n-1){
                cout<<"*";
            }
            else {
               cout<<" ";
        }
    }
      cout<<"\n";  
    }
    
}       

patten// 04 BOX PATTEN)

#include<iostream>
using namespace std;
int main()
{
    int n=7;
    for(int i=0;i<n;i++)
        {
            for(int j=0;j<n;j++){
                cout<<" ";
                
                if(i+j==n-1||i==0||i==n-1||j==0||j==n-1||i==j){
                cout<<"*";
            }
            else {
               cout<<" ";
        }
    }
      cout<<"\n";  
    }
    
}       
