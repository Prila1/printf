0x11. C - printf

Group project by: Emmanuel Asiedu and Priscilla Yartey.

Task 1:
Write a function `_printf` that produces output according to a format string. It should handle conversion specifiers `%c`, `%s`, and `%%`.

Task 2:
Extend the `_printf` function to handle conversion specifiers `%d` and `%i`, which print signed integers.

Task 3:
Add support for a custom conversion specifier `%b`, which converts an unsigned integer argument to binary.

Task 4:
Extend `_printf` to handle conversion specifiers `%u`, `%o`, `%x`, and `%X`, which print unsigned integers in decimal, octal, and hexadecimal format (lowercase and uppercase).

Task 5:
Optimize the `_printf` function by using a local buffer of 1024 characters to minimize the number of calls to `write`.

Task 6:
Handle the custom conversion specifier `%S`, which prints strings and represents non-printable characters (ASCII value less than 32 or greater than or equal to 127) as `\x` followed by the ASCII code value in hexadecimal (uppercase).

Task 7:
Handle the conversion specifier `%p`, which prints pointers in hexadecimal format.

Task 8:
Add support for the flag characters `+`, `space`, and `#` for non-custom conversion specifiers.

Task 9:
Handle the length modifiers `l` and `h` for non-custom conversion specifiers (`d`, `i`, `u`, `o`, `x`, `X`).

Task 10:
Implement handling of the field width for non-custom conversion specifiers.

