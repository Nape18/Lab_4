#include<iostream>
#include <string>
#include<iomanip>
using namespace std; 

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

cout << left << setw(22) << "Member Discount:" << right << setw(10) << "$" << discount << '\n';

cout <<left << setw(22) << "Tax:" << right << setw(10) << "$" << tax << '\n';

cout <<left << setw(22) << "Total:" << right << setw(10) << "$" << total << '\n';

cout << left <<setw(20) << "Member:" << (isMember? "Yes" : "No") << '\n;

cout << "=================================================================\n";

// Inventory Audit Table 
cout << "\nINVENTORY AUDIT\n";
cout << "====================================\n";

cout << left << setw(20) << "Item" << setw(12) << "Code" << setw(12) << "Quantity" << right << setw(12) << "Price" << '\n'
cout << "=========================================================\n"

cout << left << setw(20) << foodName << setw(12) << itemCode << setw(12) << itemQuantity << right << setw(12) << unitPrice << '\n';
cout << "-----------------------------------------------------\n"




}
