#include<iostream>
using namespace std;
int main()
{
	//https://www.onlinegdb.com/online_c++_compiler
	//password storage keeper
	//while loop 
	
	char username[10];
	char password[10];
	char engine[10];
    
    //while loop
    int a;
    a=1;
    while(a<4)
	{
	cout<<"\n\nplease input username: "<<endl;
	cin>>username;
	
	cout<<"please input password: "<<endl;
	cin>>password;
	
	cout<<"please enter engine: "<<endl;
	cin>>engine;

	cout<<"\nUsername: \n"<<username;
   	cout<<"\nPassword: \n"<<password;
    	cout<<"\nEngine: \n"<<engine;
	}
	
	
	return 0;
}
