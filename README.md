Mandatory Tasks

 Write function that produces output with conversion specifiers c, s, and %.
 Handle conversion specifiers d, i.
 Create a man page for your function.
 
Advanced Tasks

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
