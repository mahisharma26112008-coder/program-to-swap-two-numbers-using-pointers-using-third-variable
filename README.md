# program-to-swap-two-numbers-using-pointers-using-third-variable

#include<iostream>
  using namespace std;  
    int main(){
        int x,y,temp;
        cout<<"enter the value of x and y : "<<"\n";
        cin>>x>>y;

        int *p=&x;
        int *q=&y;

        cout<<"before swap : "<<x<<" "<<y<<"\n";

       temp=*p;
        *p=*q;
        *q=temp;

        cout<<"after swap : "<<x<<" "<<y<<"\n";

        return 0;
    }
