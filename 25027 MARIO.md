#include <iostream>
using namespace std;

int main(){
  int height;
    cout <<"輸入高度";
    cin >> height;
 for (int x = 0; x < height; x++) {
        for (int y = height; y > x; y--) {
            cout << " ";
        }
        for (int y = 0; y <= x; y++) {
            cout << "#";
        }
        cout << " " ;
        for (int y = 0; y <= x; y++) {
            cout << "#";
        }
        cout << "\n";
    }
}
