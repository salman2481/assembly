# assembly
hacktoberfest-accepted
#include <iostream>
using namespace std;
int main()
{
	int var1=0;
	char var2= 'a';
	float var3=2.1;
	int *ptr=&var1;
	char *ptr1=&var2;
   float *ptr2=&var3;
	cout<<&ptr2<<endl;
	cout<<&ptr<<endl;
	cout<<&ptr1<<endl;
	cout<<*ptr2<<endl;
	cout<<*ptr<<endl;
	cout<<*ptr1;
	
	return 0;
}
