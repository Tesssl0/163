#include <iostream>
using namespace std;
void main()
{

	setlocale(LC_ALL, "Rus");

	//cout << 4 % 2 << endl;

	int var;
	cout << "������� ����� ��� �������� �� ��������" << endl;
	cin >> var;

	if (var % 2)                              //if ( var % 2 == 0)
	{
		cout << "����� �� ������" << endl;   // cout << "�����" <<var << "׸����!" << endl;
	}
	else
	{
		cout << "����� ������" << endl;		// cout << "�����" <<var << "�� ������!" << endl;
	}

}