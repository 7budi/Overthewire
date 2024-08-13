The Internet is a many routers that is owned by many ISP's(Internet Service Provider).
When we decide to speck on the other side of the internet,
we are putting data on the wire which is going to be handed from router to router owned by different ISP's all the way across the internet until it arrives to the other side. 
As soon as we put the data on the wire we no longer have any control over the data.
The most common data transferred on the internet is website.
A website is written in HTML and transferred with HTTP(which is not secure).

When a website data is transferred using HTTP it is transferred as it is(Usernames and password and other personal information will be seen) and anyone in between we see it or have access to it.

This is what SSL and TLS trying to solve.What SSL/TLS do is crate a secure,protected tunnel across the internet.

That's where HTTPS come from, an HTML is transferred with HTTP protected by SSL.

SSL/TLS can also protect other data transfer like SSL VPN.

SSL/TLS can not prevent the capture of the data instead the purpose of SSL/TLS is to protect the data in three ways:
 1. Confidentiality: Data is only accessible to the client and server(meaning it should be encrypted and unreadable to the listener), it's provided through the encryption.
 2. Integrity:Data is not modified between client and server(it doesn't prevent from being modified but it enables detection if the data is modified), it's provided through hashing.
 3. Authentication: It makes sure the the client and the server are indeed who they say they are(They do this by validating the identity of the two parties ) , it's provided through PKI(Public key Infrastructure).
 
"Tunnel" is just a conceptual illustration.

SSL(Secure Socket layer) is an example of hybrid cryptography which basically means it's a method of using symmetric and asymmetric cryptography to send secure communications.
TLS(Transport Layer Secure) is the sequel of SSL.
SSL and TLS follow the same process

SSL/TSL provide anti-replay protection by giving a sequence number for the data.

There is alot of topics I didn't touch but for now this is enough.

what I did was i just and went to the openssl site and copied the connecting to ssl command and pasted it.