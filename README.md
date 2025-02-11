# Petya-and-Strings#include<iostream>
#include<string>
using namespace std;
string toLowerCase(string str){
    for(int i=0;i<str.length();i++){
       str[i]=tolower(str[i]); 
       
    }
    return str;
}
int main(){
    string str1,str2;
    cin>>str1>>str2;
    str1=toLowerCase(str1);
    str2=toLowerCase(str2);
    if(str2==str1){
        cout<<0;
    }
    else if(str1>str2){
        cout<<1;
    }
    else{
        cout<<-1;
    }
}
