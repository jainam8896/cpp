# cppinclude<iostream.h>

#include<conio.h>

template<class T>

T add(T a, T b)

{


	T result= a+b;

	return result;

}

int main()

{

	clrscr();

	cout<<"Addition of Interger: "<<add(1,2)<<endl;

	cout<<"Addition Of Float: "<<add(1.6,2.5)<<endl;

	getch();

}
