#include<bits/stdc++.h>
using namespace std;
int main()
{
    long long n,x,y;
    cin>>n>>x>>y;
    string s;
    cin>>s;
    long long group = 0;
    if(s[0]=='0') group=1;
    for(int i=0;i<n-1;i++){
        if(s[i]=='1' && s[i+1]=='0') group++;
    }
    if(group==0) cout<<0;
    else {
        long long cost = (group - 1)*min(x,y) + y;
        cout<<cost;
    }
	return 0;
}
