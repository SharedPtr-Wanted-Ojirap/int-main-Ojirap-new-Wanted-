# 박원서

```cpp
#include <memory>
#include <vector>
#include "Wanted_UE2nd.h"

int main()
{   
    std::shared_ptr<Wanted> 박원서 = new std::make_shared<Wanted>("지식");

    for (Wanted* Ojirapper : SmartMembers)
    {
        Ojirapper = 박원서.Get();
    }

    return 0;
}
```
