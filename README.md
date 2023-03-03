Usage:
```cpp
#include "ConsoleColorFormat.h"
```

Example:
```cpp
// C++
EnableColor(); // Before using

std::cout << FG_RED << "Hello World!\n" << RESET_COLOR;
std::cout << FG_GREEN << "My name is Jeff!\n" << RESET_COLOR;

DisableColor();  // After using (optional)
```

```c
// C
EnableColor(); // Before using

printf(FG_RED "Hello World!\n" RESET_COLOR);
printf(FG_GREEN "My name is Jeff!\n" RESET_COLOR);

DisableColor();  // After using (optional)
```
