# Libft

The Libft project is the first project at 42, aimed at building your own library of useful functions. These functions will be reused throughout the rest of the 42 curriculum, providing a foundation for future projects.

---

## About

The Libft project is an essential component of the 42 curriculum, introducing students to the process of writing their own library functions in C. By creating custom implementations of standard C library functions and additional utility functions, students gain a deeper understanding of fundamental programming concepts and build a strong foundation for their future projects.

If you're a 42 student, it's highly recommended that you go through the process of writing your code and testing it yourself rather than copying and pasting code that you only partially understand. Be patient and thorough.

## How to Use
1. **Clone the full repository: 42_rank_01 (Wich includes -libft -ft_printf -get_next_line)**

```bash
git clone git@github.com:Pedronplay/42_rank_01.git
```
**Or go to downgit and past the link to libft that is bellow**
```
https://github.com/Pedronplay/42_rank_01/tree/30613ee002173227ace84e4b57858f5a2b06b187/libft
```
<p>Go to <a href="https://minhaskamal.github.io/DownGit/#/home" target="_blank">DownGit</a> and copy the link of the folder you want to download, then click on Download button.</p>
<p>(Hold CTRL or CMD to open it in a new page.)</p>

2. Usage
To use the Libft library in your projects, simply include the header file \`libft.h\` and link against the compiled library (\`libft.a\`). You can compile the library using the provided Makefile.

1. **Enter the project folder and run \`make\`:**
```bash
cd libft/libft
make
```

2. **To use in your code, include the header:**
```c
#include "libft.h"
```

### Makefile Rules

- \`make\`: Compile libft **mandatory** files.
- \`make bonus\`: Compile libft **bonus** files.
- \`make all\`: Compile **mandatory** + **bonus** files.
- \`make clean\`: Delete all .o (object files) files.
- \`make fclean\`: Delete all .o (object file) and .a (executable) files.
- \`make re\`: Use rules \`fclean\` + \`all\`.


## Norminette
At 42 School, it is expected that almost every project is written following the Norm, which is the coding standard of the school.

## Mandatory
The mandatory functions in libft include both functions from the standard C library and other functions that are useful for character, string, and memory manipulation. These **34 mandatory functions** are essential to achieving a **grade of 100**.

### Functions

**Check and manipulate characters:**
Functions for checking whether a character is alphabetic, numeric, or ASCII, and for converting characters between upper and lower case.
| [**ft_isalpha**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_isalpha.c) | [**ft_isdigit**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_isdigit.c) | [**ft_isalnum**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_isalnum.c) |  
| ---------- | ---------- | ---------- |
| [**ft_toupper**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_toupper.c) | [**ft_tolower**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_tolower.c) | [**ft_isascii**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_isascii.c) |


**Manipulate strings:**
Functions for finding the length of a string, searching for substrings, and manipulating strings by trimming, splitting, joining, etc.
| [**ft_strlen**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strlen.c)  | [**ft_strlcpy**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strlcpy.c) | [**ft_strlcat**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strlcat.c) | [**ft_strchr**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strchr.c)  |
| ------------ | ------------ | ------------ | ------------ |
| [**ft_strrchr**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strrchr.c) | [**ft_strncmp**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strncmp.c) | [**ft_strnstr**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strnstr.c) | [**ft_substr**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_substr.c)  |
| [**ft_strjoin**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strjoin.c) | [**ft_strtrim**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strtrim.c) | [**ft_split**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_split.c)   | [**ft_strmapi**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strmapi.c) |
| [**ft_striteri**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_striteri.c) |              |              |              | 



**Manipulate memory:**
Functions for memory allocation, copying, setting, and comparing memory blocks.
| [**ft_calloc**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_calloc.c)  | [**ft_memset**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_memset.c)  | [**ft_bzero**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_bzero.c)   | [**ft_memcpy**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_memcpy.c)  |
| ----------------------------------- | ----------------------------------- | ---------------------------------- | ----------------------------------- |
| [**ft_memmove**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_memmove.c)| [**ft_memchr**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_memchr.c)  | [**ft_memcmp**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_memcmp.c) | [**ft_strdup**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_strdup.c)  |

**Manipulate numbers:**
Functions for converting strings to integers and vice versa.
| [**ft_atoi**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_atoi.c)  | [**ft_itoa**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_itoa.c)  |
| ------------------------------- | ------------------------------ |

**Write to a file descriptor:**
Functions for outputting characters, strings, and numbers to a file descriptor.
| [**ft_putchar_fd**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_putchar_fd.c) | [**ft_putstr_fd**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_putstr_fd.c)  |
| ----------------------------------------- | ---------------------------------------- |
| [**ft_putendl_fd**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_putendl_fd.c) | [**ft_putnbr_fd**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_putnbr_fd.c)  |


## Bonus **lists**
The bonus functions in libft are focused on list manipulation and are worth an additional 25 towards the final grade. To achieve a **grade of 125**, **all 9 bonus functions and 34 mandatory functions** must be completed accurately.
| [**ft_lstnew**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstnew.c)      | [**ft_lstadd_front**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstadd_front.c) | [**ft_lstsize**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstsize.c)     |
| --------------------------------------- | ---------------------------------------------- | ----------------------------------------- |
| [**ft_lstadd_back**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstadd_back.c) | [**ft_lstdelone**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstdelone.c)       | [**ft_lstclear**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstclear.c)    |
| [**ft_lstmap**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstmap.c)      | [**ft_lstlast**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstlast.c)           | [**ft_lstiter**](https://github.com/Pedronplay/42_rank_01/blob/30613ee002173227ace84e4b57858f5a2b06b187/libft/ft_lstiter.c)     |


