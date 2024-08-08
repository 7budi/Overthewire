Well at first it seem rather doable without any effort but it proved me wrong.
There was many unreadable characters inside the file so i thought of use unqi commend didn't work and then i thought i could be smart and use grep like the "grep  "=" "data.txt" " well damn I got an error.
I had to see if there is any other good options in grep manual and came out with the -a option which can prints binary files since the error i got when i used the command i mentioned earlier was something about the file being binary so i had the add the -a option.

Even if it really print it for me it printed the rubbish with it.

There is a command called "strings" that looks for printable strings in the file.
So I got to learn new command.
strings "data.txt" | grep "="