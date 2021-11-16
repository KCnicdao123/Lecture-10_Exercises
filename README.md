# Lecture-10_Exercises
//Descending Stars, Seven Lines
#include <iostream>
using namespace std;

int main()
{
	for (int x = 7; x > 0; x--) {
		for (int s = x; s > 0; s--) {
			cout << "*";
		}
		cout << endl;
	}
}
  
  --------------------------------------------
//Rising Stars, 5 Lines
#include <iostream>
using namespace std;

int main()
{
	for (int x = 5; x > 0; x--) {
		for (int s = x; s <= 5; s++) {
			cout << "*";
		}
		cout << endl;
	}
}
-----------------------------------------------
//Rising and Falling Stars
#include <iostream>
using namespace std;

int main()
{
	for (int x = 5; x > 0; x--) {
		for (int s = x; s <= 5; s++) {
			cout << "*";
		}
		cout << endl;
	}for (int x = 4; x > 0; x--) {
		for (int s2 = x; s2 > 0; s2--) {
			cout << "*";
		}
		cout << endl;
	}
}
----------------------------------------------
//Cubes
#include <iostream>
using namespace std;

int main() {
	cout << "Enter a number." << endl;
	int num;
	int x;
	cin >> num;
	for (int x = 1; x <= num; x++) {
		cout << "The cube of "<< x << " " << "is " << x*x*x << endl;
	}
}
-------------------------------------------------
//Find the 9s
#include <iostream>
using namespace std;

int main()
{

	int x, sum = 0;
	for (int x = 100; x <= 200; x++) {
		if (x % 9 == 0) {
			cout << " " << x;
			sum += x;
			cout << endl;
		}
		}
	cout << "The sum is: " << sum << endl;
}
-------------------------------------------------
