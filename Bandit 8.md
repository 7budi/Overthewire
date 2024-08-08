At first i was try to get the pass using grep but after a while remembered that i should know something inside the file for to grab it for me.
Then did some searching and found out that there is a "uniq" command that prints unique lines.
first i sorted it with sort and then pipped the "uniq" command with it.
Of course it didn't work b/c it was searching for unique lines not word.
So i did man uniq to see there is a better option and found -u which search for a unique word.
sort data.txt | uniq -u