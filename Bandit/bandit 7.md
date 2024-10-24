This one is also easy but i complicated it a bit(stupid me). I was trying to find it using  "find .  -type f -name "data.txt" | grep "millionth" | sort" when this all wasn't needed.
I found out that using grep can give it a word and a file to serach in it.
grep <word> <filename> just giving this command will go to the file and search for the specific word.
If we want we can use "cat data.txt | grep millionth"