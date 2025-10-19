# 김재민

```cpp
#include <memory>
#include <vector>
#include "Wanted_UE2nd.h"

int main() 
{   
    std::shared_ptr<Wanted> 김재민 = new std::make_shared<Wanted>("지식");

    for (Wanted* Ojirapper : SmartMembers)
    {
        Ojirapper = 김재민.Get();
    }

    return 0;
}
```
