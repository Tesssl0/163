#include <iostream>
using namespace std;
void main()
{

	setlocale(LC_ALL, "Rus");

	//cout << 4 % 2 << endl;

	int var;
	cout << "Введите число дял проверки на чётность" << endl;
	cin >> var;

	if (var % 2)                              //if ( var % 2 == 0)
	{
		cout << "Число не чётное" << endl;   // cout << "Число" <<var << "Чётное!" << endl;
	}
	else
	{
		cout << "число чётное" << endl;		// cout << "Число" <<var << "Не чётное!" << endl;
	}

}