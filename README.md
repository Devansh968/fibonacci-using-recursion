# fibonacci-using-recursion
#include<bits/stdc++.h>
using namespace std;
 
 int fibonacci(int n){
 
 
 if(n==0 || n==1){
 	return n;
 }
 
 int fibnum = fibonacci(n-1)+fibonacci(n-2);
 return fibnum;
}




int main(){
	
	int n;
	cin>>n;
	
	cout<<fibonacci(n);
	return 0;
}
