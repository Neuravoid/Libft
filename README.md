# Libft

Libft is a library of essential C functions, created to simplify common operations like string manipulation, memory management, and linked list handling.

## Table of Contents
- [Mandatory Part](#mandatory-part)
- [Bonus Part](#bonus-part)

## Mandatory Part

1. **ft_atoi** - Converts a string (`const char *str`) to an integer (`int`). It skips whitespace characters and supports optional signs (+ or -).
2. **ft_bzero** - Sets a specified memory area (`void *s`) to zero; fills `n` bytes with `0`.
3. **ft_calloc** - Allocates memory for `count * size` elements and fills the allocated memory with zero.
4. **ft_isalnum** - Checks if the character is alphanumeric (letter or digit).
5. **ft_isalpha** - Checks if the character is alphabetic (A-Z or a-z).
6. **ft_isascii** - Checks if the character is an ASCII character.
7. **ft_isdigit** - Checks if the character is a digit.
8. **ft_isprint** - Checks if the character is printable.
9. **ft_itoa** - Converts an integer (`int`) to a string.
10. **ft_memchr** - Searches for a character (`int c`) in a given memory area (`void *s`).
11. **ft_memcmp** - Compares two memory areas.
12. **ft_memcpy** - Copies data from one memory area (`const void *src`) to another (`void *dst`).
13. **ft_memmove** - Moves data between two memory areas, even if they overlap.
14. **ft_memset** - Fills a memory area (`void *s`) with a specified value (`int c`).
15. **ft_putchar_fd** - Writes a character to a specified file descriptor.
16. **ft_putendl_fd** - Writes a string followed by a newline to a file descriptor.
17. **ft_putnbr_fd** - Writes an integer to a file descriptor.
18. **ft_putstr_fd** - Writes a string to a file descriptor.
19. **ft_split** - Splits a string into an array of strings based on a specified delimiter.
20. **ft_strchr** - Finds the first occurrence of a character in a string.
21. **ft_strdup** - Creates a duplicate of a string.
22. **ft_striteri** - Applies a specified function to each character in a string.
23. **ft_strjoin** - Concatenates two strings.
24. **ft_strlcat** - Safely concatenates strings within a specified buffer (`dst`).
25. **ft_strlcpy** - Safely copies a string into a specified buffer.
26. **ft_strlen** - Returns the length of a string.
27. **ft_strmapi** - Creates a new string by applying a function to each character of the input string.
28. **ft_strncmp** - Compares two strings up to a specified length.
29. **ft_strnstr** - Searches for a substring within a string and returns the starting position.
30. **ft_strrchr** - Finds the last occurrence of a character in a string.
31. **ft_strtrim** - Trims specified characters from the beginning and end of a string.
32. **ft_substr** - Returns a substring from a given string.
33. **ft_tolower** - Converts a character to lowercase.
34. **ft_toupper** - Converts a character to uppercase.

## Bonus Part

1. **ft_lstadd_back** - Adds a new node (`t_list *new`) to the end of a linked list (`t_list *lst`).
2. **ft_lstadd_front** - Adds a new node to the beginning of a linked list.
3. **ft_lstclear** - Clears and deletes all nodes in the linked list.
4. **ft_lstdelone** - Deletes a specified node from the list.
5. **ft_lstiter** - Applies a function (`f`) to each node in the list.
6. **ft_lstlast** - Returns the last node of the linked list.
7. **ft_lstmap** - Creates a new list by applying a function to each node in an existing list.
8. **ft_lstnew** - Creates a new linked list node.
9. **ft_lstsize** - Returns the number of nodes in the linked list.
