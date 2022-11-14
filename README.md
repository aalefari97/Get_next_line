# Get_next_line

- It is a function that reads a file and allows you to read a line ending with a newline character from a file descriptor. When you call the function again on the same file, it grabs the next line. This project deals with memory allocation and when to free and allocate memory to prevent leaks.

A (-1) is returned if an error occurred. A (0) is returned if the file is finished reading. And a (1) is returned if a line is read.


-> Repeated calls (e.g., using a loop) to your get_next_line() function should let
you read the text file pointed to by the file descriptor, one line at a time.

• Your function should return the line that was read.
If there is nothing else to read or if an error occurred, it should return NULL.

• Make sure that your function works as expected both when reading a file and when
reading from the standard input.
