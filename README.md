# import-file
how to import a function from a file to another?


// the following is the code where i want to use the function from another file

#include<iostream>
#include <c.h>
using namespace std;
int main(){
	check();
	return 0;
}

// the following is the code where the required function contains

#include<iostream>
#include<math.h>
#ifndef _C_H
#define _C_H
	void check( );
#endif
using namespace std;
int main(){
	while(1)
		 check(  );
			return 0;
}
 void check( ){

	float ivar,a;double fvar;
	cout<<"entr the num \n";
	cin>>a;
	
	fvar=sqrt((double)a);
	ivar=fvar;
	
	if(fvar==ivar)
		cout<<"perfect square"<<endl;
	 else
		cout<<"imperfect"<<endl;

}

