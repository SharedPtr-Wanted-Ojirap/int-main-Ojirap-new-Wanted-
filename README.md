# int-main-Ojirap-new-Wanted-

```cpp
#include <memory>
#include <vector>
#include "Wanted_UE2nd.h"

// main Repo 입니다.
int main() 
{   
    std::shared_ptr<Wanted> Ojirap = new std::make_shared<Wanted>("지식");

    for (Wanted* Ojirapper : SmartMembers)
    {
        Ojirapper = Ojirap.Get();
    }

    return 0;
}
```


## 목차

### [Memory Block 1](./1.MemoryBlock/)
### [Memory Block 2](./2.MemoryBlock/)

