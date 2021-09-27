# Exercise-2
C++basics
#include<iostream>
using namespace std;
int main()
{
	double a;
	cout << "Enter an integer of your own choice : " << endl;
	cin >> a;
	if (a > 0)
	{
		cout << "It's a positive number! " << endl;
	}
	else if (a < 0)
	{
		cout << "It's a negative number! " << endl;
	}
	else
	{
		cout << "It is zero." << endl;
	}
	return 0;
}
