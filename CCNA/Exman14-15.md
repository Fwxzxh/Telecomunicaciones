# Introduction to Networks - Modules 14 -15 


1. **Which action is performed by a client when establishing communication with a server via the use of UDP
at the transport layer?**
	* the client randomly selects a source port number.

2. **Which transport layer feature is used to guarantee session establishment?**
	* TCP 3-way handshake

3. **What is the complete range of TCP and UDP well-known ports?**
	* 0 to 1023

4. **What is a socket?**
	* A combination of source IP address and port number or a destination IP address and port numbeer

5. **A PC is downloading a large file from a server.
The TCP window is 1000 bytes. 
The server is sending the file using 100-byte segments.
How many segments will the server send before it requires an acknowledgment from the PC?**
	* 10 segments
> **Explicación:** *Con una ventana de 1000 bytes, el host de destino aceptara segmentos hasta que los 1000 
bytes sean enviados.
Entonces el host manda un reconocimiento*.

6. **Which factor determines TCP window size?**
	* the amount of data the destination can process at one time

> **Explicación:** *La ventana es el número de bytes que se van a mandar antes de enviar un reconocimiento
del dispositivo de destino.
La ventana inicial es negociada en el inicio de sesción mediante el apreton de manos de tres pasos entre
la fuente y el destinop. 
Y es determinado por cuantos datos puede recibir el dispositivo de destino en una sección TCP.

7. **What does a client do when it has UDP datagrams to send?**
	* it just send the datagrams

8. **Which three fields are used in a UDP segment header? (choose three)**
	* Length
	* Source Port
	* Checksum
> **Explicación:** *Un header UDP consiste solo de el Puerto de origen y de destino, longitud, y checksum.*

9. **What are two roles of the transport layer in data communication on a network? (choose two)**
	* identifying the proper application for each communication stream
	* Tracking the individual communication between applications on the source and destination hosts
> **Explicación:** *La capa de transporte tiene unas cuantas responsabilidades.*
> * Rastrear las comunicaciones individuales entre aplicaciónes en 

