#include <iostream>
using namespace std;
int main()
{
   int n,result;
   cout<<"please enter a number ";
     cin>>n;
   
    try {
     
        if(n<1)
        {
            throw n;
        }
         result = 10/n;
        cout<<"the value of result "<<  result; 
     }
     catch(int n){
        cout<<"the calculation not possible ";
    }
    
    return 0;
}
