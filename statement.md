#description: 
 int* can be implicity converted to int const* -- 4.4.  There is no implicit conversion from int const* to int*. 

```C++ runnable
#include <iostream>

using namespace std;

 int main()
 {
     int a = 2;
 
     int* b = &a;
 
     int const* c = b;

     b = c;
 
    return 0;
 } 
```

