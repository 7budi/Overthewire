First tried to list if there is anything but found nothing except "-" file(I'm not sure it doesn't open).
then went around searching around ,alas, couldn't find anything but the sudo command didn't work i don't know why.


Finally found it, it was right in front of me it was the "-" file i couldn't open it because when i type "cat -" the cat commend interprets the - as an argument or option.

To solve it, it is needed to explicitly the file name using the relevant or absolute path
which is "cat ./-".