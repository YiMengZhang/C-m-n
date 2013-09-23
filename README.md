C-m-n
=====
#include<iostream>
using namespace std;
double C(int x,int y){
        int m,n,q=1,p=1;
		m=x,n=y;
		int s;
		for(s=1;s<n+1;s++){
			q=q*m;
			m--;
               }
		for(;n>0;n--){
			p=p*n;
		}
       double result;
	   result=p/q;
	   return result;
}
int main()
{cout<<"输入m,n"<<endl;
 int m,n;
 cin>>m>>n;
 cout<<"result is"<<C(m,n)<<endl;
 }
