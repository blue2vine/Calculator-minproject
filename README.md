# Calculator-minproject
/*
date=28/09/2023
name=Mahadev athani
subject=Simple calculator;
*/
// I do code on menu driven
#include <iostream>
using namespace std;
int main()
{
  float a, b, sum = 0, sub = 0, pdt, div;
  int option;
  cout << "Option 1 for addition" << endl;
  cout << "Option 2 for subtraction" << endl;
  cout << "Option 3 for multification" << endl;
  cout << "Option 4 for division" << endl;
  cout << "Enter value of a and b";
  cin >> a >> b;
  cout << "Enter your option=";
  cin >> option;
  switch (option)
  {
  case 1:
    // cout<<"Enter value of a & b="<<endl;
    // cin>>a>>b;
    sum = a + b;
    cout << "Sum of two number is =" << sum;
    break;
  case 2:
    // cout<<"Enter value of a & b=";
    // cin>>a>>b;
    sub = a - b;
    cout << "Difference of two number is =" << sub << endl;
  case 3:
    pdt = a * b;
    cout << "Product od two number is =" << pdt << endl;
    break;
  case 4:
    // cout<<"Enter value of a & b=";
    // cin>>a>>b;
    div = a / b;
    cout << "Division of two number is =" << div << endl;
    break;
  }

  return 0;
}
