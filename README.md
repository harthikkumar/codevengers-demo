**Write a C++ program to compute the sum of two given integer values. If the two values are the same, then return triple their sum.**
#include<iostream>
using namespace std;
int main(){
    int a,b,sum;
    cout<<"enter a first number";
    cin>>a;
    cout<<"enter a second number";
    cin>>b;
    sum=a+b;
    if(a==b){
        cout<<"the sum is"<<(sum)*3<<endl;
    }
    else{
        cout<<"the sum is"<<sum<<endl;
    }
}
