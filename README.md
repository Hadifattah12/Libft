Libft

Description

Libft is a custom implementation of the standard C library functions, built as a foundational project at 42 Beirut. This library provides a set of essential functions for string manipulation, memory handling, and linked list operations.

Table of Contents

Libft

Description

Features

Installation

Usage

Functions

Bonus Part

Testing

License

Features

Implementation of standard C library functions (string, memory, and character operations).

Additional utility functions for handling strings and memory.

Bonus functions for linked list manipulation.

Compliant with the 42 coding standards (Norminette).

Installation

Clone the repository and compile the library:

This will generate libft.a, the static library file.

Usage

To use Libft in your projects, include the header file and link the library:

Compile your program with:

Functions

Part 1 - Standard Library Functions

Function

Description

ft_isalpha

Checks if a character is an alphabetic letter.

ft_isdigit

Checks if a character is a digit.

ft_isalnum

Checks if a character is alphanumeric.

ft_isascii

Checks if a character is within the ASCII table.

ft_isprint

Checks if a character is printable.

ft_strlen

Computes the length of a string.

ft_memset

Fills a memory block with a constant byte.

ft_bzero

Zeros out a memory block.

ft_memcpy

Copies a memory block.

ft_memmove

Moves a memory block safely.

ft_strlcpy

Copies a string with size limit.

ft_strlcat

Concatenates strings with size limit.

ft_toupper

Converts a lowercase letter to uppercase.

ft_tolower

Converts an uppercase letter to lowercase.

ft_strchr

Locates a character in a string.

ft_strrchr

Locates a character in a string (last occurrence).

ft_strncmp

Compares two strings up to n characters.

ft_memchr

Searches for a byte in memory.

ft_memcmp

Compares two memory blocks.

ft_strnstr

Finds a substring within a string.

ft_atoi

Converts a string to an integer.

ft_calloc

Allocates and zeroes out memory.

ft_strdup

Duplicates a string.

Part 2 - Additional Functions

Function

Description

ft_substr

Extracts a substring from a string.

ft_strjoin

Concatenates two strings.

ft_strtrim

Trims characters from the start and end of a string.

ft_split

Splits a string by a delimiter.

ft_itoa

Converts an integer to a string.

ft_strmapi

Applies a function to each character of a string.

ft_striteri

Applies a function to each character of a string (in-place).

ft_putchar_fd

Writes a character to a file descriptor.

ft_putstr_fd

Writes a string to a file descriptor.

ft_putendl_fd

Writes a string followed by a newline to a file descriptor.

ft_putnbr_fd

Writes an integer to a file descriptor.

Bonus Part

If you complete the mandatory part, you can implement additional linked list functions.

Function

Description

ft_lstnew

Creates a new linked list node.

ft_lstadd_front

Adds a node to the beginning of a list.

ft_lstsize

Counts the number of elements in a list.

ft_lstlast

Returns the last node of a list.

ft_lstadd_back

Adds a node to the end of a list.

ft_lstdelone

Deletes a node and frees its memory.

ft_lstclear

Deletes an entire linked list.

ft_lstiter

Iterates over a list and applies a function.

ft_lstmap

Maps a function to a list and creates a new list.

Testing

You can test your Libft using external testers:

License

This project is open-source and free to use. Feel free to modify and distribute it as needed.
