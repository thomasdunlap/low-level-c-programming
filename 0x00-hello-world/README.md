## 0x00 C- Hello, World

This folder contains scripts to understand the C compiler and how to print simple strings using printf and puts.

|      File      |               Description                |
| :------------: | :--------------------------------------: |
| 0-Preprocessor | A script that runs a C file through the preprocessor and saves the result into another file. |
|   1-compiler   | A script that generates the assembly code of a C code and save it in an output file. |
|  2-assembler   | A script that compiles a C file but does not link. |
|     3-Name     | A script that compiles a C file and creates an executable named `cisfun`. |
|     4-puts     | A C program that prints exactly `"Programming is like building a multilingual puzzle`, followed by a new line. |
|   5-printf.c   | A C program that prints exactly `with proper grammar, but the outcome is a piece of art,`, followed by a new line. |
|    6-size.c    | A C program that prints the size of various types on the computer it is compiled and run on |
|   100-intel    | A script that generates the assembly code (Intel syntax) of a C code and save it in an output file. |
|  101-quote.c   | A C program that prints exactly `and that piece of art is useful - Dora Korpar, 2015-10-19`, followed by a new line, to the standard error. |

### Example of functions & programs output
--------------------------------------------

#### 4-puts
```
gcc 4-puts.c -o a && ./a
"Programming is like building a multilingual puzzle"
```
#### 5-printf.c
```
gcc 5-printf.c -o a && ./a
with proper grammar, but the outcome is a piece of art,
```
#### 6-size.c
```
gcc 6-size.c -o a && ./a
Size of a char: 1 byte(s)
Size of an int: 4 byte(s)
Size of a long int: 8 byte(s)
Size of a long long int: 8 byte(s)
Size of a float: 4 byte(s)

```
#### 100-quote.c
```
gcc 101-quote.c -o a && ./a
and that piece of art is useful - Dora Korpar, 2015-10-19
```
