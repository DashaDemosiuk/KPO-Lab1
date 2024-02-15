# KPO-Lab1
#include <iostream>
#include <cmath>
using namespace std;
int main() {

	int n;
	cout << "number of repetitions: ";
	cin >> n;


	double x;
	cout << "enter the value of x: ";
	cin >> x;

	double value = 0;
	for (int i = 1; i < n+1; i++) {
		value += (10 / i)*(1 - x);
	}
	cout << "the end result of the sequence: " << value;


}


