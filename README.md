# Libft

This project is part of the 42 school curriculum. Its main objective is to build a personal C library by reimplementing standard libc functions and adding useful utilities for future projects.

## Description

Libft is a C library coded from scratch. It includes custom implementations of standard C functions for memory handling, string manipulation, character checks, and linked list operations. Only a limited set of external functions (`write`, `malloc`, `free`) is allowed, and strict coding standards must be followed.

The project is divided into three parts: standard libc functions, additional utility functions, and bonus linked list functions.

## Contents

### Part 1: Libc Functions

- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_strlen`
- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_toupper`
- `ft_tolower`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_memchr`
- `ft_memcmp`
- `ft_strnstr`
- `ft_atoi`
- `ft_calloc`
- `ft_strdup`

### Part 2: Additional Functions

- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_striteri`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

### Bonus Part: Linked List Functions

Includes a custom `t_list` structure and functions to manipulate singly linked lists:

- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstadd_back`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`

## Compilation

To compile the library, run:

```bash
make

```
This will generate the static library file libft.a.

## Author

Developed by Elena as part of the 42 School curriculum.
