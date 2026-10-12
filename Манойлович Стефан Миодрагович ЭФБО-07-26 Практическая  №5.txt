Задание 1 пример 1 через for
#include <iostream>
using namespace std;

#include <iostream>
using namespace std;
int main() {
    double X, Y;
    cin >> X >> Y;
    int day = 1;
    for (; X < Y; day++) {
        X *= 1.1;
    }
    cout << day << endl;
    return 0;
}

пример 2 через while
#include <iostream>
using namespace std;

int main() {
    double X, Y;
    cin >> X >> Y;

    int day = 1;

    while (X < Y) {
        X *= 1.1;
        day++;
    }

    cout << day << endl;

    return 0;
}

пример 3 через do-while
#include <iostream>
using namespace std;
int main() {
    double X, Y;
    cin >> X >> Y;
    int day = 1;
    do {
        if (X >= Y) {
            break;
        }
        X *= 1.1;
        day++;
    } while (X < Y);
    cout << day << endl;
    return 0;
}

