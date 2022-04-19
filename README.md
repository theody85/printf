# _printf

The printf project is a collaboration between Theodora Addeafi Gyambrah - [Theody85](https://github.com/Theody85) and Emmanuel Ayarma Jnr - [EJAyarma](https://github.com/EJAyarma).

## Description
_printf is a simple custom printf function that formats and prints data to the standard output."_printf" imitates the actual "printf" command located in the stdio.h library. It contains some of the basic features and functions found in the manual 3 of "printf".

The function has the following conversion specifies:

+ %c - prints a character
+ %d - prints a  integer
+ %s - prints a string
+ %i - prints an integer
+ % - prints percentage;
+ %b - print binary numbers
+ %u - print unsigned integers of type int
+ %x - print hexadecimal numbers in lowercase
+ %X - print hexadecimal numbers in uppercase
+ %o - print octal numbers
+ %r - prints string in reverse order 
+ %R - prints string in ROT13 encoding
+ %p - print pointer addresses
+ ' ' - print a space
+ # -  modifier for unsigned conversions
+ +: prints a plus sign in front of the number


## Installation
 you can clone this repository  and use the function on your local machine.

```bash 
git clone https://github.com/dev-ted/printf.git
```

## Adding man\_3\_prinf to you mandb

To add the man\_3\_prinf page to your mandb run this script

```bash
sudo ./install
```

# Usage
+ include the `main.h ` header file on the function for using _printf().
+ All the files are to be compiled on Ubuntu 14.04 LTS
```bash
Compile your code with `gcc -Wall -Werror -Wextra -pedantic *.c`
```

```c
#include <stdio.h>
#include "main.h"

int main(void)
{
    int i = 10;
    int print;
    char *s = "printf by Theodora & Emmanuel";
    _printf("%d %s %c\n", i, s, 'c');
     print =  _printf("%d", s); /* get number of characters */
     printf("%d\n", print); /* print number of characters */
    return 0;
}


```

## Copyright
Copyright (c) 2022 Theodora Addeafi Gyambrah Emmanuel Ayarma Jnr





