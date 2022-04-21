# C - printf
A group project on implementation and recreation of the C standard library function, printf.

## Authors
* Wasiu Sanusi <[The-Vast](https://github.com/The-Vast)>
* Gladys Oviawe <[gladys](https://github.com/gladysgodwin)>

## Description
printf or print function in C takes a formatting string and couple of optional variables as input and outputs strings to console while converting input variables to strings.
Printf takes multiple arguments and these functions are called variable length arguments function or vararg function. Take printf for consideration. User supply a string and input argumnets. Printf creates an internal buffer for constructing output string. Now printf iterates through each characters of user string and copies the character to the output string. Printf only stops at "%". "%" means there is an argument to convert. Arguments are in the form of char, int, long, float, double or string. It converts it to string and appends to output buffer. If the argument is string then it does a string copy. Finally printf may reach at the end of user sting and it copies the entire buffer to the stdout file.

Authorised functions and macros for the projects includes;

write (man 2 write)
malloc (man 3 malloc)
free (man 3 free)
va_start (man 3 va_start)
va_end (man 3 va_end)
va_copy (man 3 va_copy)
va_arg (man 3 va_arg)

Allowed editors: vi, vim, emacs.

## Usage
# printf
