#include <iostream>
using namespace std;

int main()
{
	float dif = 0.00;
	int amount;
	char select;
	
	cout << "\t\t\t-------------------------------------------------------------------" << endl;
	cout << "\t\t\t WELCOME To Our Online Candy Shop" << endl;
	cout << "\t\t\t-------------------------------------------------------------------" << endl;
	cout << "\t\t\t[1] Maxx" << endl;
	cout << "\t\t\t[2] Snow beer" << endl;
	cout << "\t\t\t[3] Dynamite" << endl;
	cout << "\t\t\t[4] Lips" << endl;
	cout << "\t\t\t-------------------------------------------------------------------";
	cout << "\n\nWhat would you like to buy? ";
	cin >> select;
	
	
	switch(select)
	{
		case '1':
			cout << "------------------------------" << endl;
			cout << "Maxx cost P120.00/pack" << endl;
			cout << "------------------------------" << endl;
			cout << "Enter payment to proceed: ";
			cin >> amount;
				if (amount >= 120)
				{
					float dif = amount - 120;
					cout << "\nTransaction Successful!";
					cout << "\nChange: " << dif;
				}
				else 
					cout << "\nPayment not sufficient...";	
			break;
			
		case '2':
			cout << "----------------------------------" << endl;
			cout << "Snow beer cost P115.00/pack" << endl;
			cout << "----------------------------------" << endl;
			cout << "Enter payment to proceed: ";
			cin >> amount;
				if (amount >= 115)
				{
					dif = amount - 115;
					cout << "\nTransaction Successful!";
					cout << "\nChange: " << dif;
				}
				else 
					cout << "\nPayment not sufficient...";	
			break;
		
		case '3':
			cout << "------------------------------" << endl;
			cout << "Dynamite cost P120.00/pack" << endl;
			cout << "------------------------------" << endl;
			cout << "Enter payment to proceed: ";
			cin >> amount;
				if (amount >= 120)
				{
					dif = amount - 120;
					cout << "\nTransaction Successful!";
					cout << "\nChange: " << dif;
				}
				else 
					cout << "\nPayment not sufficient...";	
			break;
		
		case '4':
			cout << "------------------------------" << endl;
			cout << "Lips cost P125.00/pack" << endl;
			cout << "------------------------------" << endl;
			cout << "Enter payment to proceed: ";
			cin >> amount;
				if (amount >= 125)
				{
					dif = amount - 125;
					cout << "\nTransaction Successful!";
					cout << "\nChange: " << dif;
				}
				else 
					cout << "\nPayment not sufficient...";	
			break;
			
		default:
			cout << "\n\nERROR....";
		
	}
}
