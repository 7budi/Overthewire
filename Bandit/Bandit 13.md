This was a topic i know 1% of it i did some research and ssh(secure shell) protocol is a method for securely sending command to a host.
private key - Its is the one to be protected the most and should be on the client or local pc.
public key - it can be any where most of the time on the server.

ssh -i private.file username@host -p port
-i reads the file 