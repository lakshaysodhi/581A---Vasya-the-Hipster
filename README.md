# 581A---Vasya-the-Hipster
#include <bits/stdc++.h>
using namespace std;


int main(){

    int a,b;
    int fashionpair,samepair;
    cin>>a>>b;
    if(a<b){
        fashionpair=a;
        samepair=(b-a)/2;
    }else{
        fashionpair=b;
        samepair=(a-b)/2;
    }
    cout<<fashionpair<<" "<<samepair;
}
