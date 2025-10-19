# 허지웅

```cpp
#include <memory>
#include <vector>
#include "Wanted_UE2nd.h"

int main()
{   
    std::shared_ptr<Wanted> 허지웅 = new std::make_shared<Wanted>("지식");

    for (Wanted* Ojirapper : SmartMembers)
    {
        Ojirapper = 허지웅.Get();
    }

    return 0;
}
```
