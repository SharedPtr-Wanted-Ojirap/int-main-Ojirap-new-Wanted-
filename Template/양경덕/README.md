# 양경덕

```cpp
#include <memory>
#include <vector>
#include "Wanted_UE2nd.h"

int main()
{   
    std::shared_ptr<Wanted> 양경덕 = new std::make_shared<Wanted>("지식");

    for (Wanted* Ojirapper : SmartMembers)
    {
        Ojirapper = 양경덕.Get();
    }

    return 0;
}
```
