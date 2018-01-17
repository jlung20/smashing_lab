# smashing_lab

This was done in CS 33, fall quarter 2017. I uploaded only the files of greatest interest. "bad.txt" was invoked as an argument in a slightly modified version of thttpd that contained a vulnerability. Further assistance was provided by the lack of a stack protector or address sanitizer and the use of gdb to provide a dependable return address. Anyway, "bad.txt" contains machine code that unlinks "target.txt" as well as a return address to a point within the buffer.
