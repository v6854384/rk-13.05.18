#include <iostream>
using namespace std;

void pow(int a, int b){
int res = a;
if (b % 2 == 0)
        {
        b = b/2;
        for (int i = 0; i < b; i++)
        a = a*a;
        cout << a << endl;
        }
else
        {
        b = (b-1)/2;
        for (int i = 0; i < b; i++)
        a = a*a;
        cout << res*a << endl;
        }
}

int main() {
int a, b, c, d, f;
cout << "Введите 3 числа, у которых нужно найти медиану" << endl;
cin >> a >> b >> c;
cout << "Введите число и его степень" << endl;
cin >> d >> f;
if (a + b <= c)
        if (a < b)
        cout << b << endl;
        else
        cout << a << endl;
if (a + c <= b)
        if (a < c)
        cout << c << endl;
        else
        cout << a << endl;
if (b + c <= a)
        if (b < c)
        cout << c << endl;
        else
        cout << b << endl;
pow(d, f);
return 0;
}
