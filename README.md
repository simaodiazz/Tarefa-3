# Exercicio 1

```cpp
#include <iostream>

using namespace std;

void main() {
    char s[] = "Hello, World";
    char *prt = s;
    for (; *prt != '\0'; ++prt) {
        cout << *prt << endl;
    }
    system("pause");
}
```

# Exercicio 2

```cpp
#include <iostream>

using namespace std;

int main() {
    char s[100];
    char *prt = s;
    cout << "Introduza uma string: ";
    cin >> *prt;

    if (s[0] == '\0') {
        cout << "String vazia";
    } else {
        int i = 0;
        while (prt[i] != '\0') {
            cout << prt[i];
            i++;
        }

        cout << endl;
        
        while (i > -1) {
            cout << prt[i]; 
            i--;
        }

        cout << endl;
    }

    return 0;
}
```