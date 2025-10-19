# 조은정

```cpp
#include <memory>
#include <vector>
#include "Wanted_UE2nd.h"

int main()
{   
    std::shared_ptr<Wanted> 조은정 = new std::make_shared<Wanted>("지식");

    for (Wanted* Ojirapper : SmartMembers)
    {
        Ojirapper = 조은정.Get();
    }

    return 0;
}
```
