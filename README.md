   0x11. C - printf

This is a team project
Authors

[Noel K Langat](https://github.com/noelkips)

[Zeberio Morande](https://github.com/Zeb-0)

The project and the resources in this repository cover concepts
to write the prinf function that works like stadard library (printf.h)

Resources

[Secrets of printf](https://intranet.alxswe.com/rltoken/7Vw7aUWgwC7JYUrqI4bh4Q)
man printf (3)

Requirements
1. Allowed editors: vi, vim, emacs
2. All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
3. All your files should end with a new line
4. A README.md file, at the root of the folder of the project is mandatory
5. Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
6. You are not allowed to use global variables
7. No more than 5 functions per file
8. In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
9. The prototypes of all your functions should be included in your header file called main.h
10. Don’t forget to push your header file
11. All your header files should be include guarded
12. Note that we will not provide the _putchar function for this project

Tasks

0. I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life
Write a function that produces output according to a format.
	. Prototype: int _printf(const char *format, ...);
	. Returns: the number of characters printed (excluding the null byte used to end output to strings)
	. write output to stdout, the standard output stream
	. format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
		c
		s
		%
	. You don’t have to reproduce the buffer handling of the C library printf function
	. You don’t have to handle the flag characters
	. You don’t have to handle field width
	. You don’t have to handle precision
	. You don’t have to handle the length modifiers


1. Education is when you read the fine print. Experience is what you get if you don't
	. Handle the following conversion specifiers:
		d
		i
	. You don’t have to handle the flag characters
	. You don’t have to handle field width
	. You don’t have to handle precision
	. You don’t have to handle the length modifiers


2. With a face like mine, I do better in print
	. Handle the following custom conversion specifiers:
	. b: the unsigned int argument is converted to binary

3. What one has not experienced, one will never understand in print
	. Handle the following conversion specifiers:
		u
		o
		x
		X
	. You don’t have to handle the flag characters
	. You don’t have to handle field width
	. You don’t have to handle precision
	. You don’t have to handle the length modifiers

4. Nothing in fine print is ever good news
	Use a local buffer of 1024 chars in order to call write as little as possible.

5. My weakness is wearing too much leopard print
	Handle the following custom conversion specifier:
		S : prints the string.
		Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters)

6. How is the world ruled and led to war? Diplomats lie to journalists and believe these lies when they see them in print
	. Handle the following conversion specifier: p.
	. You don’t have to handle the flag characters
	. You don’t have to handle field width
	. You don’t have to handle precision
	. You don’t have to handle the length modifiers

7. The big print gives and the small print takes away
Handle the following flag characters for non-custom conversion specifiers:
	+
	space
	#

8. Sarcasm is lost in print
	. Handle the following length modifiers for non-custom conversion specifiers:
		l
		h
	. Conversion specifiers to handle: d, i, u, o, x, X

9. Print some money and give it to us for the rain forests
	Handle the field width for non-custom conversion specifiers.

10. The negative is the equivalent of the composer's score, and the print the performance
	Handle the precision for non-custom conversion specifiers.

11. It's depressing when you're still around and your albums are out of print
	Handle the 0 flag character for non-custom conversion specifiers.

12. Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection
	Handle the - flag character for non-custom conversion specifiers.

13. Print is the sharpest and the strongest weapon of our party
	. Handle the following custom conversion specifier:
	. r : prints the reversed string

14. The flood of print has turned reading into a process of gulping rather than savoring
	. Handle the following custom conversion specifier:
	. R: prints the rot13'ed string
