# ft_printf

The ft_printf project is a crucial exercise at 42, challenging students to implement their version of the standard C library function `printf`. This function is widely used in C programming for formatted output. Implementing `printf` provides a deep dive into string formatting, variable arguments handling, and advanced concepts in C programming.

---

## About

The ft_printf project is a cornerstone of the 42 curriculum, designed to develop students' understanding of string formatting and variable argument handling in C. By creating a custom implementation of `printf`, students enhance their grasp of fundamental programming concepts and lay a solid groundwork for tackling complex projects.

For 42 students, it's highly recommended to approach the implementation of `ft_printf` methodically, understanding each aspect of the function's behavior and testing thoroughly to ensure its correctness and robustness.

The ft_printf project is a cornerstone of the 42 curriculum, designed to develop students' understanding of string formatting, variable argument handling, and variadic functions in C. By creating a custom implementation of printf, students enhance their grasp of fundamental programming concepts and lay a solid groundwork for tackling complex projects.

## How to Use

1. **Clone the full repository: 42_rank_01 (Which includes -libft -ft_printf -get_next_line)**

```bash --
git clone git@github.com:Pedronplay/42_rank_01.git
``` 
 Or go to DownGit and paste the link to ft_printf below 
```
https://github.com/Pedronplay/42_rank_01/tree/40b09bd4e421acb89f988f401f2b132d2dfbc318/ft_printf
```
<p>Go to <a href="https://minhaskamal.github.io/DownGit/#/home" target="_blank">DownGit</a> and copy the link of the folder you want to download, then click on Download button.</p>
<p>(Hold CTRL or CMD to open it in a new page.)</p>


2. **Usage**

To use the `ft_printf` function in your projects, include the header file `ft_printf.h` and link against the compiled library (`libftprintf.a`). You can compile the library using the provided Makefile.

```bash
cd ft_printf
make
``` 
<!-- ```c -->
<!-- #include "ft_printf.h" -->

### Makefile Rules

- `make`: Compile `ft_printf`.
- `make clean`: Delete all object files.
- `make fclean`: Delete all object files and the executable.
- `make re`: Recompile the project.

## Functionality

The `ft_printf` function accepts format specifiers similar to the standard `printf` function. Below are some of the supported format specifiers:

- `%s`: String
- `%d` or `%i`: Signed decimal integer
- `%c`: Character
- `%p`: Pointer address
- `%x`: Hexadecimal integer (lowercase)
- `%X`: Hexadecimal integer (uppercase)
- `%u`: Unsigned decimal integer

**Note:** This is a simplified overview. Please refer to the function implementation for a complete list of supported format specifiers and their usage.

## Example

```c
#include "ft_printf.h"

int main(void) 
{ 
    ft_printf("Hello, %s!\n", "world");
    ft_printf("The answer is %d.\n", 42);
    return (0);
}
``` 
Expected output:

Hello, world!
The answer is 42.

