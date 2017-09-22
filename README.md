# font-preview
Check Out Programming Fonts

https://talyian.github.com/font-preview

```cpp
#include <stdio.h>
#include <stdint.h>
#include "fizzbuzz.h"

void FizzBuzzer::fizzBuzz(int32_t n) {
    for (int32_t i=0; i<n; i++) {
        if (i % 15 == 0) printf("fizzbuzz\n");
        else if (i % 3 == 0) printf("fizz\n");
        else if (i % 5 == 0) printf("buzz\n")
        else printf("%d\n", i);
    }
}
```
