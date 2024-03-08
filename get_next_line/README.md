# GET_NEXT_LINE

The get_next_line project is a crucial exercise at 42, challenging students to implement their version of a function that reads a line from a file descriptor. This function is particularly useful for reading files or input streams line by line in C programming.

---

## About

The get_next_line project at 42 offers a crucial lesson in file handling and string manipulation in C. Implementing the get_next_line function enables the extraction of a single line from a file descriptor, emphasizing file I/O operations, memory management, and buffer handling.

The project also delves into the utilization of static variables, enhancing students' understanding of efficient memory management and ensuring smooth operation even with varying buffer sizes. Through hands-on implementation and thorough testing, students gain invaluable insights into the intricacies of file processing in C.

## How to Use

1. **Clone the full repository: 42_rank_01 (Which includes -libft -ft_printf -get_next_line)**

```bash --
git clone git@github.com:Pedronplay/42_rank_01.git
``` 
 Or go to DownGit and paste the link to ft_printf below 
```
https://github.com/Pedronplay/42_rank_01/tree/68c648cefed73cdba9110c745daf5bacc9aca0e6/get_next_line
```
<p>Go to <a href="https://minhaskamal.github.io/DownGit/#/home" target="_blank">DownGit</a> past the link then click on Download button.</p>
<p>(Hold CTRL or CMD to open it in a new page.)</p>

2. **Usage**

To use the `get_next_line` function in your projects, include the header file `get_next_line.h`. You can compile the source files using the provided Makefile.

```bash
cd get_next_line
```

## Example

```c
#include "get_next_line.h"

int	main(void)
{
	int	fd;
	char	*line;
 	int i = 0;

	fd = open("poem", O_RDONLY);
	while ((line = get_next_line(fd)))
	{

		printf("%s", line);
		free(line);
	}
}
```

Expected output:

The program will print the contents of the "poem" file located in the project folder. 
To read different files, simply change the file name. 
This example uses a while to read the full "poem", if you only want to read a single line, remove the code from the while loop.

## BONUS PART


## Example 
```c
#include "get_next_line.h"
#include "stdio.h"

int     main(void)
{
        int     fd;
        int     fd2;
        char    *line;
        char    *line2;

        fd = open("poem", O_RDONLY);
        fd2 = open("get_next_line_bonus.c", O_RDONLY);
        line = get_next_line(fd);
        line2 = get_next_line(fd2);
        printf("%s", line);
        printf("%s", line2);
        free(line);
}
```
Expected output:
The program will print the first line of the "poem" file located in the project folder, and then will print the first line of the "get_next_line_bonus.c" file.
It will look like this: 
```
Gnarly/* ************************************************************************** */
```



