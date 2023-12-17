#include<iostream>
using namespace std;
int main() {
    int uservalue;
    int result;

    cout << "Enter a value:";
    cin >> uservalue;

    if (uservalue < 0) {
        result = -1;
        cout << "Result is " << result;
    }
    else if (uservalue > 0 && uservalue <= 5) {
        result = 0;
        cout << "Result is " << result;
    }
    else if (uservalue > 5 && uservalue <= 12) {
        result = 1;
        cout << "Result is " << result;
    }
    else if (uservalue > 12 && uservalue <= 19) {
        result = 2;
        cout << "Result is " << result;
    }
    else if (uservalue > 19 && uservalue <= 50) {
        result = 3;
        cout << "Result is " << result;
    }
    else if (uservalue > 50 && uservalue <= 60) {
        result = 4;
        cout << "Result is " << result;
    }
    else if (uservalue > 60 && uservalue <= 101) {
        result = 5;
        cout << "Result is " << result;
    }
    else if (uservalue > 101) {
        result = -1;
        cout << "Result is " << result;
    }
    else {
        cout << "Invalid Input.";
    }



    return 0;

}
