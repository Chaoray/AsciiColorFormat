# ConsoleColorFormat
Usage:
```cpp
#include "ConsoleColorFormat.h"
```

Example:
```cpp
std::cout << FG_GREEN << "Hello World!\n" << RESET_COLOR;
std::cout << BG_CYAN << "My name is Jeff!\n" << RESET_COLOR;
```
Output:  
<p color="green">Hello World!</p><br>
<p style="background-color: #0093B0">My name is Jeff!</p>
