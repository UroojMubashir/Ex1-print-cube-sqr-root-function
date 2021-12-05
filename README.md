#include <string>
#include <iostream>
#include <math.h>
#include <array>
using namespace std;

int main()
{
    double number;
cout<<"Kindly enter any number\n";
cin>> number;
while(cin.fail())
{
    cin.clear();
    cin.ignore();
    cout<<"\n Invalid Input TRY AGAIN! \n\n Input a Number again:\n\n";
    cin>>number;
}

cout<<"Square-root:" <<sqrt(number) <<"Cube-root:"<<cbrt(number);
    return 0;
}
