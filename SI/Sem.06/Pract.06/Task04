#include<iostream>
using namespace std;

int codedNumber(int n, int k) {
	int lastKdigits = 1;
	for (int i = 1; i <= k; i++) {
		lastKdigits *= 2;
	}
	lastKdigits -= 1;
	return (n & lastKdigits);
}

int main() {
	int n = 0;
	int k = 0;
	cin >> n;
	cin >> k;
	cout << codedNumber(n, k);
	return 0;
}
