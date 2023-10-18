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