*This project has been created as part of the 42 curriculum by ael-mota.*

# ft_printf

## Description

`ft_printf` is my own implementation of the standard C `printf` function, compiled into a static library (`libftprintf.a`). It handles variadic arguments and prints formatted output for the required conversions.

## Instructions

```bash
make          # create libftprintf.a
make clean    # remove the .o files
make fclean   # remove the .o files and libftprintf.a
make re       # rebuild everything
```

To use it, add `#include "ft_printf.h"` in your code and compile with:

```bash
cc -Wall -Wextra -Werror main.c -L. -lftprintf
```

## Conversions

- `%c`: prints a single character
- `%s`: prints a string
- `%p`: prints a pointer address in hexadecimal
- `%d` / `%i`: prints a signed decimal integer
- `%u`: prints an unsigned decimal integer
- `%x` / `%X`: prints a hexadecimal number in lowercase / uppercase
- `%%`: prints a percent sign

## Resources

- [GeeksforGeeks](https://www.geeksforgeeks.org/) - variadic functions (`stdarg.h`) and format specifiers
- [Beej's Guide to C Programming](https://beej.us/guide/bgc/) - pointers and memory addresses
- [Stack Overflow](https://stackoverflow.com/) - debugging and edge cases
- [Linux man pages (`man 3 printf`)](https://man7.org/linux/man-pages/man3/printf.3.html) - behavior and return values
- [Total Phase - What is a Register in a CPU?](https://www.totalphase.com/blog/2023/05/what-is-register-in-cpu-how-does-it-work/) - CPU registers and argument passing mechanics
- [ScienceDirect - Floating-Point Register](https://www.sciencedirect.com/topics/computer-science/floating-point-register) - register architecture and ABI conventions

### AI usage

AI was used only to help write this README. All the code was written and tested by me.