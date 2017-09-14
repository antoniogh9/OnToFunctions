# OnToFunctions
This program adds, substract, multiply, divide and gives the remainder of two given number.

#include <iostream>
using namespace std;

//Functions
int Sum(int a, int b) {
		return a + b ;
	}
int Diff(int a, int b) {
		return a - b ;
	}
int Product (int a, int b) {
		return a * b ;
}
int Div (int a, int b) {
		return a / b ;
}
int Remainder (int a, int b) {
		return a % b ;
}

int main()
{
	int x, y;

	//User Input
	cout << "Enter your first number:" << endl ;
	cin >> x ;
	cout << "Enter your second number:" << endl ;
	cin >> y ;

	//Verification
	cout << endl ;
	cout << "You chose the numbers " << x << " and " << y << "." << endl ;
	cout << endl ;

	//Results
	cout << "The addition of those numbers is " << Sum (x,y) << "." << endl ;
	cout << "The difference of those numbers is " << Diff (x,y) << "." << endl ;
	cout << "The product of those numbers is " << Product (x,y) << "." << endl ;
	cout << "The division of those numbers is " << Div (x,y) << "." << endl ;
	cout << "The remainder of those numbers is " << Remainder (x,y) << "." << endl ;

return 0;
}
