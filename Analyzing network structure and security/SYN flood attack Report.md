## Cybersecurity Incident Report: SYN Flood Attack
- ### Identifying the type of attack that may have caused this network interruption  

<p align="justify">A denial-of-service attack could be one reason for the website's connection timeout error message. The logs indicate that when the web server receives an excessive number of SYN packet requests, it stops responding. This might be an instance of SYN flooding, a kind of DoS attack.</p>  

- ### Explaination of how the attack is causing the website malfunction  

<p align="justify">When users of the website attempt to connect to the web server, a web server The TCP protocol is used during a three-way handshake. There are three steps in the handshake:</p> 

1. The source sends a SYN packet to the destination asking to establish a connection.
2. To accept the connection request, the destination sends a SYN-ACK packet back to the source. Resources will be reserved by the destination so that the source can connect.
3. The source sends a last ACK packet to the destination confirming that they have been granted permission to join.

<p align="justify">A hostile actor will transmit a lot of SYN packets all at once in a SYN flood assault, overwhelming the server's capacity to reserve resources for the connection. There are no longer any server resources available for valid TCP connection requests when this occurs.</p>

<p align="justify">The logs show that the web server is overloaded and unable to handle the SYN requests from the visitors. When a visitor receives a connection timeout notification, the server is unable to establish a new connection.</p>
