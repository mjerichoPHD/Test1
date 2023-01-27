#include<iostream>
using namespace std;

int main() {

//Nested For Loops-------------------------------------------------
for (int i = 0; i < 3; i++) {
	for (int j = 0; j < 6; j++) {
		cout << "*";
	}
	cout << endl;
}
//Single For Loops-------------------------------------------------
	//prints out 25 to 45
	for (int i = 25; i <= 45; i++)
		cout << i << " ";
	cout << endl;
	
	//prints out 90 to 70 counting by 2
	for (int i = 90; i >= 70; i -= 2)
		cout << i << " ";
	cout << endl;

	//prints out 90 to 70 counting by 2
	for (int i = 10; i <= 5000; i *= 5)
		cout << i << " ";
	cout << endl;

	//if statement-------------------------------------------------
	int cookie;
	cout << " how many cookies do you have? " << endl;
	cin >> cookie;

	if (cookie < 5)
		cout << "You want a cookie?" << endl;

	else if (cookie <= 10)
		cout << "That's a good amount cookies" << endl;

	else if (cookie > 10)
		cout << "That's too many cookies! I should get one" << endl;

	cout << endl;

	char character;
	cout << " What is you like best? (b)art simpson, (s)cooby doo, (r)ick, (d)affy duck, or (p)ikachu" << endl;
	cin >> character;

	if (character == 'b')
		cout << "eat my shorts?" << endl;

	else if (character == 's')
		cout << "scooby dooby doo" << endl;

	else if (character == 'r')
		cout << "Wubba lubba dub dub" << endl;

	else if (character == 'd')
		cout << "sufferin' succotash!" << endl;

	else if (character == 'p')
		cout << "pika pika" << endl;
}
