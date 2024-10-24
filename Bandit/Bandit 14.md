IP Address is a numerical label such as 194.0.0.1 that is assigned to devise connected to a computer network that uses the internet protocol for communication.
IP addressses serve two main function: network interface identification and location addressing.


The **Internet Protocol** (**IP**) is the [network layer](https://en.wikipedia.org/wiki/Network_layer "Network layer") [communications protocol](https://en.wikipedia.org/wiki/Communications_protocol "Communications protocol") in the [Internet protocol suite](https://en.wikipedia.org/wiki/Internet_protocol_suite "Internet protocol suite") for relaying [datagrams](https://en.wikipedia.org/wiki/Datagram "Datagram") across network boundaries. Its [routing](https://en.wikipedia.org/wiki/Routing "Routing") function enables [internetworking](https://en.wikipedia.org/wiki/Internetworking "Internetworking"), and essentially establishes the [Internet](https://en.wikipedia.org/wiki/Internet "Internet").

In [computer networking](https://en.wikipedia.org/wiki/Computer_networking "Computer networking"), **localhost** is a [hostname](https://en.wikipedia.org/wiki/Hostname "Hostname") that refers to the current computer used to access it. The name _localhost_ is reserved for [loopback](https://en.wikipedia.org/wiki/Loopback "Loopback") purposes.[[1]](https://en.wikipedia.org/wiki/Localhost#cite_note-rfc6761-1) It is used to access the [network services](https://en.wikipedia.org/wiki/Network_service "Network service") that are running on the host via the loopback network interface. Using the loopback interface bypasses any local [network interface hardware](https://en.wikipedia.org/wiki/Network_interface_controller "Network interface controller").


### Ports
Any server machine makes its services available to the Internet using numbered **ports**, one for each service that is available on the server. For example, if a server machine is running a Web server and an FTP server, the Web server would typically be available on port 80, and the FTP server would be available on port 21. Clients connect to a service at a specific IP address and on a specific port.

In [computer networking](https://en.wikipedia.org/wiki/Computer_network "Computer network"), a **port** or **port number** is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service. At the software level, within an [operating system](https://en.wikipedia.org/wiki/Operating_system "Operating system"), a port is a logical construct that identifies a specific [process](https://en.wikipedia.org/wiki/Process_(computing) "Process (computing)") or a type of [network service](https://en.wikipedia.org/wiki/Network_service "Network service"). A port at the software level is identified for each [transport protocol](https://en.wikipedia.org/wiki/Transport_protocol "Transport protocol") and address combination by the port number assigned to it. The most common transport protocols that use port numbers are the [Transmission Control Protocol](https://en.wikipedia.org/wiki/Transmission_Control_Protocol "Transmission Control Protocol") (TCP) and the [User Datagram Protocol](https://en.wikipedia.org/wiki/User_Datagram_Protocol "User Datagram Protocol") (UDP); those port numbers are 16-bit [unsigned numbers](https://en.wikipedia.org/wiki/Unsigned_number "Unsigned number").

I wanted to take note of this because they are very essential.
At first I was try to ssh it but something told me I was doing it wrong.
After a while I went and saw how telnet is used and found out how to get the password.
telnet localhost 30000.
