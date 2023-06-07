#include <iostream>
using namespace std;
int main()
{
	
cout << "Welcome to Franks Carpet Cleaning Service!!!" << endl << endl;
cout << "Charges: " << endl;
cout << "$25 per small room" << endl;
int $small_rooms = 25;
cout << "$35 per large room" << endl;
int $large_rooms = 35;
cout << "Sales tax rate is 6%" << endl; 
 cout << "Estimates are valid for 30 days" << endl << endl;
 
int small_rooms;
cout << "How many number of small rooms would you like serviced?: ";
cin >> small_rooms;

int large_rooms;
cout << " How many number of large rooms would you liked serviced?: ";
cin >> large_rooms;


int pretax;
pretax = $small_rooms * small_rooms + $large_rooms * large_rooms; 
cout << "Subtotal: " << pretax << endl;
int tax = pretax * 0.06;
cout << "Tax: " << tax << endl << endl;
cout << "$" << pretax + tax << " is your total." << endl;


return 0;
}
