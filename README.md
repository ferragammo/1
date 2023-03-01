#include <iostream>
#include <string>
using namespace std;
int main()
{
    string s;
    int b = 1;
    getline(cin, s);
    for (int i = 1; i < s.length(); i++) 
    {
        if (s[i] > 'Z')
            b = 0;
    }
    if (b != 0) 
    {
        for (int i = 0; i < s.length(); i++)
            s[i] += 32;
        if (s[0] >= 'a' && s[0] <= 'z')
            s[0] -= 32;
        else
            s[0] -= 64;
    }
    cout << s;
    return 0;
}
