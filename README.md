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

patten//02

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
