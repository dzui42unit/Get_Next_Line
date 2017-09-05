# Get_Next_Line

Realization of a function that allows to read the file by a string with the help my own library.

In odred to read a whole file the function can be called in a loop.

Prorotye: get_next_line(int fd, char **str);

First parameter: file descriptor.

Second: string to write in.

* get_next_line() returns 1 if the reading was sucessfull
* get_next_line() returns 0 if the file ended.
* get_next_line() returns -1 in case of error.
