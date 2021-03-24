## Printf

It is a custom implementation of the C programming function printf. This project is an application of the C programming skills that Holberton School Cohort 14 students have learned since they started the . Prototype: int _printf(const char *, ...); Examples String

Input: _printf("%string", 'This is a string.'); Output: This is a string. Character

Input: _printf("The first letter of the alphabet is %c\n", 'A'); Output: The first letter of the alphabet is A. Integer

Input: _printf("There are %i dozens in a gross", 12); Output: There are 12 dozens in a gross Decimal:

Input: _printf("%d", 1000); Output: 1000

Project requirements All files will be compiled on Ubuntu 14.04 LTS Programs and functions will be compiled with gcc 4.8.4 using the -Wall -Werror -Wextra and -pedantic flags. The code must follow the Betty style Global variables are not allowed Allowed functions and macros: write (man 2 write) malloc (man 3 malloc) free (man 3 free) va_start (man 3 va_start) va_end (man 3 va_end) va_copy (man 3 va_copy) va_arg (man 3 va_arg)

Mandatory tasks Write a function that produces an output with the conversion specifiers c, s and %. Handle the conversion specifiers d, i. Create a man page for your function

<img src="https://user-images.githubusercontent.com/70784906/112387354-a7fdc380-8cbf-11eb-9ebd-3c6bbd55bfb0.jpg" width="30%"></img>
