
```cpp


// Online C++ compiler to run C++ program online
#include <iostream>
#include <bits/stdc++.h>

using namespace std;

int main() {
    // Write C++ code here
    string mystr;
    cin >> mystr;
    cout << mystr;
    
    for(auto i = mystr.begin();i != mystr.end();++i){
        cout << *i << " ";
    }
    for (char j : mystr){
        cout << j << " ";
    }
    cout << "Hello world!";

    return 0;
}

```
