#include<iostream>
#include<string>
using namespace std;
int main()
    {
    char c[]="ABCDEFGHIJKLMNOPQRSTUVWXYZ" ;
    string s;
    cin>>s;
    int i=string.size(),h=1;
    for(int y=0;y<i;y++)
        {
        for(int u=0;u<26;u++)
            {
            if(s[y]=c[u])
                {
                h++;
            }
        }
    }
    cout<<h;
    return 0;
}
//https://www.hackerrank.com/challenges/camelcase
