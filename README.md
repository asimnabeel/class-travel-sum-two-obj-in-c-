# class-travel-sum-two-obj-in-c-
using Class travel sum two object in #C++
#include<iostream>
using namespace std;
class Travel
{
int km, hr;
public:
Travel()
{
km = 0;
hr = 0;
}
Travel(int k, int h)
{
km = k;
hr = h;
}
void input()
{
cout << "Enter kilo meter:" << endl;
cin >> km;
cout << "Enter hour:" << endl;
cin >> hr;
}
void display()
{
cout << "kilometer:" << km << endl;
cout << "Hour:" << hr << endl;
}
Travel sum_travel(Travel T)
{
Travel T1;
T1.km = km +T.km;
T1.hr = hr + T.hr;
return T1;
}
};
int main()
{
Travel T4;
Travel T2(33, 44),T3(33,66);
T2.display();
T4 = T2.sum_travel(T3);
T4.display();
}
