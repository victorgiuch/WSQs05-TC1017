# WSQs05-TC1017
Temperature
#include <iostream>

using namespace std;

int main()
{
	int f,c ;

	cout <<"Give me the temperature in fahrenheit" << endl;
	cin >> f;

    c = 5 * (f-32)/9;
    cout << "The temperature in celsius is" << c << endl;

if (c >= 100)
{
	cout << "Water would boil at this temperature" << endl;
}
else
{
    cout << " Water would not boil at this temperature" << endl;
}
return 0;
}
