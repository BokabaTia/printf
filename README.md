**#printf**

Group project on ALX Software Engineering Programme using C programming Language

Collaborators:  Tshiamo Bokaba and Nwosu Chukwuemeka

This printf project is a collaboration between Tshiamo Bokaba and Nwosu Chukwuemeka who are Software Engineering students of ALG(ALX and Holberton) programme. This project involves a function named "_printf" which would imitate the actual "printf" command located in the stdio.h library. This function contains some of the basic features and functions found in the man 3 of "printf".

**What you would learn from this project:**

--How to use git in a team setting
--Applying variadic functions to big projects
--The complexities of printf
--Managing a lot of flies and finding a good workflow

**General Requirements**

Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
You are not allowed to use global variables
No more than 5 functions per file
In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
The prototypes of all your functions should be included in your header file called main.h
Don’t forget to push your header file
All your header files should be include guarded
Note that we will not provide the _putchar function for this project

**Authorized functions and macros**
-write (man 2 write)
-malloc (man 3 malloc)
-free (man 3 free)
-va_start (man 3 va_start)
-va_end (man 3 va_end)
-va_copy (man 3 va_copy)
-va_arg (man 3 va_arg)

**Compilation**
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c


**Mandatory Tasks**

 Write function that produces output with conversion specifiers c, s, and %.
 Handle conversion specifiers d, i.
 Create a man page for your function.
 
**Advanced Tasks**

 Handle conversion specifier b.
 Handle conversion specifiers u, o, x, X.
 Use a local buffer of 1024 chars in order to call write as little as possible.
 Handle conversion specifier S.
 Handle conversion specifier p.
 Handle flag characters +, space, and # for non-custom conversion specifiers.
 Handle length modifiers l and h for non-custom conversion specifiers.
 Handle the field width for non-custom conversion specifiers.
 Handle the precision for non-custom conversion specifiers.
 Handle the 0 flag character for non-custom conversion specifiers.
 Handle the custom conversion specifier r that prints the reversed string.
 Handle the custom conversion specifier R that prints the rot13'ed string.
 All above options should work well together.
File Descriptions

_printf.c

contains the fucntion _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream.

_putchar.c


contains the function _putchar, which writes a character to stdout.
main.h *contains all function prototypes used for _printf.

man_3_printf

manual page for the custom _printf function.
functions.c functions1.c functions2.c

contains all function of each specifier used for _printf.
all function have its own description inside the file.

handle_print.c

contains arguments types used for _printf.

get_flags.c

contains all function for each flag use for _printf.

utils.c

contains some necessary functionalities for _printf.

ger_width.c

contains functions to get width for spcifics spcifiers.

writee_handlers.c

contains write functions.
