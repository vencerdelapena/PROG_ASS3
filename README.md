#include<iostream>
using namespace std;

int main()
{
    int num1, num2;
    int sum;
    cout<< "Sum calculator\n";;
    cout<< "Enter first number: ";
    cin >> num1;
    
    cout<< "Enter second number: ";
    cin >> num2;

    sum = num1 + num2;
    
    cout << "Sum of first number and second number: " << sum << endl;
    
    return 0;
}
