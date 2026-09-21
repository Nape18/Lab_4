#include<iostream>
#include <string>
#include<iomanip>

int main()
{
string foodName;
char itemCode;
int itemQuantity;
double unitPrice;
char memberInput 

cout << "Enter food name: ";
getline(cin, foodName);

cout << "Enter item code: ";
cin >> itemCode;

cout << "Enter quanitity: ";
cin >> itemQuantity;

cout << "Enter unit price: $";
cin>> unitPrice;

cout << "Are you a member? (y/n): ";
cin >> memberInput;

bool isMemeber = (memberInput == 'y' || memberInput == 'Y');

double subtotal = itemQuantity * unitPrice;

cout << left << setw(20) << "Item:" << foodName << '\n';
cout << left << setw(20) << "Item Code:" << itemCode << '\n';
cout << left << setw (20) << "Quantity:" << itemQuantity << '\n';

cout << fixed << setprecision(2);
cout << left << setw(20) << "Unit Price:" << right << setw(10) << "$" << unitPrice << '\n';

cout << left << setw(20) << "subtotal:" << right << setw(10) << "$" << subtotal << '\n';

cout << left <<setw(20) << "Member:" << (isMember? "Yes" : "No") << '\n;
cout << "=================================================================\n";




}
