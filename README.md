# <img src="https://logowik.com/content/uploads/images/423918.logowik.com.webp" style="width: 40px; height: auto;"> This project is part of my curriculum at School 42 <img src="https://logowik.com/content/uploads/images/423918.logowik.com.webp" style="width: 40px; height: auto;">

Welcome to my **Libft** project! This was my first dive into building a custom C library during my journey at **School 42**. This project helped me gain a deep understanding of the essential C functions by re-implementing them from scratch.

## 📋 Project Overview

Libft is a custom library that replicates functions from the standard C library (libc) and adds additional useful functions for future projects. It was an indispensable tool in my C programming toolkit during my cursus as we were often not allow to use other ones.

### Features

- **Standard C Functions**: Recreated essential C functions such as `ft_strlen`, `ft_memcpy`, `ft_atoi`, and more.
- **Memory Management**: Includes functions like `ft_calloc`, `ft_strdup` that manage memory allocation effectively.
- **String Manipulation**: Functions like `ft_substr`, `ft_strjoin`, `ft_split`, and `ft_strtrim` handle complex string operations.
- **Bonus Features**: Extra functions to manipulate linked lists, providing more flexibility in managing dynamic data structures.

## 🛠️ Functions Implemented

### Part 1 - Libc Functions
- `ft_isalpha`, `ft_isdigit`, `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_toupper`, `ft_tolower`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_memchr`, `ft_memcmp`, `ft_atoi`, `ft_calloc`, `ft_strdup`

### Part 2 - Additional Functions
- `ft_substr`, `ft_strjoin`, `ft_strtrim`, `ft_split`, `ft_itoa`, `ft_strmapi`, `ft_striteri`, `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus Part - Linked List Functions
- `ft_lstnew`, `ft_lstadd_front`, `ft_lstsize`, `ft_lstlast`, `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`, `ft_lstiter`, `ft_lstmap`

## 💡 What I Learned

- **Reinforced C Basics**: Through this project, I gained a deeper understanding of how standard C functions work.
- **Memory Management**: I learned how to manage memory allocation effectively, minimizing leaks and ensuring proper usage.
- **Linked Lists**: Implemented and manipulated linked lists, which helped me understand dynamic data structures.

## 🛠️ How to Use

`make` to compile without bonus functions.<br>
`make bonus` to compile bonus functions.