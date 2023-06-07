//Anirudh Calculator
#include <iostream>
#include <cmath>
using namespace std;

int main() {
	long double a;
	long double b;
	cout << "Enter 'a' 'b' value for sum here or press 1 enter 1 for multiplication" << endl;
	 cin >> a >> b;

	cout << a + b << endl;
	long double c;
	long double d;
	cout << "Enter 'a' 'b' value for multiplication here or press 1 enter 1 for subtraction" << endl;
	cin >> c >> d;
	cout << c * d << endl;
	long double e;
	long double f;
	cout << "Enter 'a' 'b' value for subtraction here or press 1 enter 1 for division" << endl;
	cin >> e >> f;
	cout << e - f << endl;
	long double g;
	long double h;
	cout << "Enter 'a' 'b' value for division here or press 1 enter 1 for remainder calculator(only for integers)" <<endl;
	cin >> g >> h;
	cout << g / h << endl;
int k;
int j;
cout << "Enter 'a' 'b' value for remainder calculator here.( Note that a,b should be integer only). " << endl;
cin >> k >> j;
cout << k % j << endl;
double x;
 double y;

cout << "Enter 'a' 'b' value for power calculator here.( Note that a,b should be integer only). "<< endl;
cin >> x >> y ;
int abc = pow(x,y);
    cout << abc << endl;
int ab;
cout << "Enter any number for root of it here!" << endl;
cin >> ab;
cout << pow(ab, 0.5)<< endl;

}

