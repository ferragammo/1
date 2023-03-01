#include <iostream>
using namespace std;
int main() {
    int l;
    cin >> l;
    cout << (l % 4 == 0 || l % 7 == 0 || l == 44 || l == 47 || l == 74 || l == 77 || l == 444 || l == 447 || l == 474 || l == 477 || l == 744 || l == 747 || l == 774 || l == 777 ? "YES" : "NO");
return 0;
}
