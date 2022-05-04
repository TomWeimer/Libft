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

| Standard C functions:  	| Equivalent libft: | Standard C functions:		| Equivalent libft:  	|	
|:------------------------| :-----------------|:------------------------| :-------------------|
|	isalpha	               	|	ft_isalpha	     	|	toupper									|	ft_toupper	     	 	|
|	isdigit              	 	|	ft_isdigit	     	|	tolower	           			|	ft_tolower      		|
|	isalnum	               	|	ft_isalnum	     	|	strchr									|	ft_strchr						|
|	isascii									|	ft_isascii				|	strrchr									|	ft_strrchr					|
|	isprint									|	ft_isprint				|	strncmp									|	ft_strncmp					|
|	strlen									|	ft_strlen					|	strnstr									|	ft_strnstr					|
|	memset									|	ft_memset					|	memcmp									|	ft_memcmp						|
|	memcpy									|	ft_memcpy					|	memchr									|	ft_memchr						|
|	memmove									|	ft_memmove				|	atoi										|	ft_atoi							|
|	strlcpy									|	ft_strlcpy				|	bzero										| ft_bzero						|
|	strlcat									|	ft_strlcat				|	calloc									|	ft_calloc						|
|strdup										|	ft_strdup					|													|											|

| Additional functions: |											|	|  	| Bonus functions: 			|											|
|:----------------------|:--------------------|-|---|:----------------------|:--------------------|
|	ft_substr							|	ft_strjoin					|	|   |ft_lstnew							|	ft_lstdelone				|
|	ft_strtrim						| ft_split						|	|   |ft_lstadd_front				| ft_lstadd_back			|
|	ft_itoa								|	ft_strmapi					|	|   |ft_lstsize							|	ft_lstlast					|
|	ft_striteri						|	ft_putchar_fd				|	|   |ft_lstclear						|	ft_lstiter					|
|	ft_putstr_fd					|	ft_putendl					|	|   |ft_lstmap							|											|
|	ft_putnbr_fd																|	|   |                     	|                     |



# Tester
