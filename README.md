# 42 School - Libft

## Description
This project is the first project available in the curriculum of School 42.	The goal of this assignment is to create a simple library, that can be used in some of the future project.


Working on this project, you will learn the basics of a C library.
Among the functions of the libft, we find some of the most used in C, such as strlen, strcopy, calloc...<br>
Click [here](https://github.com/TomWeimer/Libft/blob/main/fr.subject.pdf) to see the complete subject of this project. 

## Installation
```zsh
git clone https://github.com/TomWeimer/Libft libft
```
## Usage
To use a library in C you need to add, in the source file using the library, the following code:
```C
#include  "libft.h"
```
You also need to link the library:
```C
gcc  foo.c -lft
```
Or if the library is not in the standard path:
```C
gcc  foo.c -L<path_to_the_libft> -lft
```
## Content of the library
### Mandatory functions:
The functions bellow are reproductions of others library functions:
| Standard C functions   	|                     |                         |                         |                         |
|:------------------------| :-------------------|:------------------------|:------------------------|:------------------------|
| [ft_isalpha][1]	        |	[ft_strlen][6]		  | [ft_strlcpy][11]				    	| [ft_strrchr][16]  					  | [ft_strnstr][20] 	            |				  
|	[ft_isdigit][2]         |	[ft_memset][7]	    |	[ft_strlcat][12]	  	        | [ft_strncmp][17]  				    |	[ft_atoi][21]			            |
|	[ft_isalnum][3]         |	[ft_bzero][8]				| [ft_toupper][13]		            | [ft_memchr][18]						    | [ft_calloc][21]    	        |	  
|	[ft_isascii][4]		    	| [ft_memcpy][9]		 	| [ft_tolower][14]				      | [ft_memcmp][19]		            |	[ft_strdup] [22]	              |
| [ft_isprint][5]         |	[ft_memmove][10]		| [ft_strchr][15]               |                               |                         |

The functions bellow are a choice of School 42:		
| Additional 42 functions: |											|											|											|								|
|:----------------------|:--------------------|:--------------------|:--------------------|:--------------|
|	ft_substr							|	ft_strjoin					|	ft_putnbr_fd				|	ft_striteri					| ft_putstr_fd	|
|	ft_strtrim						| ft_split						|	ft_putendl					|	ft_putchar_fd				|	ft_strmapi		|
|	ft_itoa																
### Bonus functions:
The functions below aren't needed for validated the project:
| Additional 42 functions: 			|											|											|											|											|
|:----------------------|:--------------------|:--------------------|:--------------------|:--------------------|
|	ft_lstnew							|	ft_lstdelone				|ft_lstclear					|	ft_lstiter					|ft_lstmap							|	
|	ft_lstadd_front				| ft_lstadd_back			|ft_lstsize						|	ft_lstlast					|

[1]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_isalpha.c
[2]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_isdigit.c
[3]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_isalnum.c
[4]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_isascii.c
[5]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_isprint.c
[6]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strlen.c
[7]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_memset.c
[8]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_bzero.c
[9]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_memcpy.c
[10]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_memmove.c
[11]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strlcpy.c
[12]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strlcat.c
[13]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_toupper.c
[14]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_tolower.c
[15]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strchr.c
[16]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strrchr.c
[17]:https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strncmp.c
[18]:https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_memchr.c
[19]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_memcmp.c
[20]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strnstr.c
[21]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_atoi.c
[22]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_calloc.c
[22]: https://github.com/TomWeimer/Libft/blob/main/src/mandatory/ft_strdup.c
