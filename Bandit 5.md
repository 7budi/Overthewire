well this one was interesting.
This one had alot of directory and files that are executable and non-executable it would be very tiring to open every file so were are forced to use the "find" command.

I tried many thing like "find /inhere -type f" , "find / -type f" ,"find . -type f -size 1033" but non of them worked.

I had to do some research on how to find non-executable file and how to list it.

finally found it using "find . -type f -size -3k ! -executable -exec ls -al {} \\;"
