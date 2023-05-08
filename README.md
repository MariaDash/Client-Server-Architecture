# Client-Server-Architecture
The IT industry is constantly trying hard to ensure large swaths of information, devices, and connections are as feasible as possible. The world continues to thrive in ways to stay connected for performing daily tasks. IT professionals have moved to a method known as client server architecture. Before explaining the architecture in detail and you start reading jargon such as servers, networks, data, clients and many more, let us understand the architecture in simple terms. Just like the analogy of ordering a pizza for delivery, a person calls the store to order, a store executive picks up the call to take the order and then delivers it. This is the simplest example to understand the fundamental principle of client server architecture as it best correlates with each step of the model.

## What is the Client Server Model?
The client server architecture is a distributed application framework which divides tasks between servers and clients either by residing in the same system or by communicating through a computer network. The client sends a request to another program to access the services provided by a server. The server runs multiple programs with shared resources and distributes work among several clients. The relationship between client and server is steered in a request-response messaging pattern while adhering to common communications protocols. The protocols define the rules, language, and the dialog patterns necessary to use. Usually, it adheres to the TCP/IP protocol suite.

![client server](https://www.interviewbit.com/blog/wp-content/uploads/2022/04/client-server-550x427.png)

TCP (Transmission Control Protocol) maintains a strong connection between client and server until the message exchange has completed. Also, it determines the best suitable way to distribute application data in the form of packets and pick it from the sender, forward in the network to ensure it reaches the receiver. It manages flow control and re-sends the dropped or garbled packets. IP (Internet Protocol) is a connectionless protocol that provides end-to-end data communication. It ensures the packet arrives at the destination address by specifying the flow of data from packetization, addressing, transmission, routing and finally receiving at the correct destination.
Requests from the clients are organized and prioritized in the scheduling system. Scheduling system also helps servers to cope up with all the requests received from distinct clients very quickly. The client server model expands the capability of a general-purpose computer by utilizing the shared resources of several hosts. The best examples of this approach are email, the world wide web, and network printing. In a simplified manner, two factors are involved: –

+ Servers are the ones that provide requested services.
+ Clients are the ones requesting for the services. 

Client server model also known as networking computing model in which a server hosts, delivers, and manages all the resources and services as requested by the client. Resources are shared among all connected computers because all these requests are delivered over a network. Normally, client server architecture is a basic arrangement where clients are located at the workstations while servers are located far away on the powerful machines in the network. This model is beneficial in the office environments where the clients and servers usually perform routine tasks. For example, a data processing system at a hospital. A client computer runs a basic application program for entering a patient’s information and the server computer fetches and manages the database, where information is stored permanently.

To understand this concept more closely, the following are the best client-server architecture examples that we encounter in our day-to-day life.

+ Mail application – Email servers applications help in sending and receiving emails through the medium of various software that allows email handling.
+ Web servers – These are high-speed computers used for hosting of various web portals. The server data of the website is requested by the clients using the internet.
+ File servers – These servers act as a centralized location for various files. The best daily life example is Google Docs. The files we store in Google Docs are stored in the cloud and easily accessible by your smartphones. The files can either be saved on the devices or can be accessed with Microsoft Office or Google Docs to modify it. Also, the files stored centrally can be used by multiple users at a time.

## Basic Components of Client Server Architecture
Clearly, three components are essential in the client server architecture to ensure its flawless working. Those are workstations, servers, and networking devices. Let us understand them in detail.

1. `Workstations` – Also known as client computers or service requestors, they are dependents of servers and send them requests for resources and services. A piece of server software and computer hardware requests to access shared files and databases. For example, Laptops, Smartphones, Tablets, Desktop computers or Chat applications. Client computing is classified as following-

     + Thick client/ Fat client – A thick client provides rich functionality, as it is least dependent on the server and able to perform most of the data processing tasks itself. ( e.g. games. The thick client has more functionality, as well as the ability to use the multi-user mode. In addition, the user will be able to interact with it offline, and the response will probably be faster.work with data due to their capacities (both software and hardware) )
        
     + Thin client- It is a lightweight computer relying heavily on the resources of the host computer. An application server performs all the data processing tasks. (e.g. PC with a browser.thin ones, in fact, act as a carrier of a graphical interface, and for processing they use the capabilities of a central server located in the data center and serviced by an external organization.)
        
     + Hybrid client- It is a combination of both thin client and thick client characteristics. A hybrid client still relies on a server for all the centralized data but is capable of local processing.
        
2. `Servers` – These are the fast-processing devices or computer programs that act as a centralized repository of programs, databases, network files, and several policies. They have huge storage space and robust systems to handle multiple requests by clients to share resources and distribute the work. Servers perform several roles, some of the most common ones are-

     + Application server- These servers host web applications in the network without any need of their own copy.
     + Database server- It maintains and shares a database for all the computer programs to ingest well-organized data and fetch whenever required such as spreadsheets or accounting software.
     + Computing server- These servers share an enormous amount of computer resources to the connected computers that need more RAM or CPU power for a personal computer.
     + Web server- They host all the web pages and facilities available on the World Wide Web.
     
3. `Networking devices` – The medium that connects client and servers in client server architecture are called networking devices. Also, they are used to perform other operations across the network. For example, a repeater is used to transfer data effectively between two bridges. A hub connects a server to several workstations. Bridges help in isolating network segmentation.

## How does Client Server Architecture Work?
Now that we have understood key elements of client server architecture, one provides services and the other consumes those desired services.  In general, a service is an abstraction of computer resources, and a client should only be concerned with raising requests to servers, and the server fulfills the request and delivers the response based on the well-known application protocol.

The exchange of messages in client and server happens in a request-response messaging pattern. For good inter-process communication, client and server should have a common language and both should follow proper rules and know what they want. All communication protocols that define language and rules of communication operate in the application layer. The server also implements an Application Programming Interface (API) to formalize the data exchange. The API is at the abstraction layer and ensures a specific content format is followed and facilitates parsing.

At a specific time, the server may receive requests from various clients and a limited number of tasks are performed at any moment relying on a scheduling system to prioritize the tasks. Denial of service attacks are developed to assure that servers are not overloaded with excessive requests or in case of cyber attack network resources are made unavailable temporarily or indefinitely. Encryption is another essential, if there is a flow of sensitive information between the client and the server to ensure security of the messages.

Let us understand its working with the help of an example of how the browser interacts with the server by following steps.

  + The user enters the uniform resource locator (URL) of the website or file in the web browser. The browser forwards the requests to the domain name system (DNS) server.
  + The DNS servers start searching for the address of the web server and revert with the IP address of the web server
  + After fetching a DNS server response, browsers send over an HTTP or HTTPS request to the IP of the web servers as provided by the DNS server.
  + The server delivers all the essential files of the web portal.
  + Browser renders the files and the website appears on the screen. The rendering is performed with the help of JIT or (Just in Time) Compiler
  + Client Server Architecture Work
   
![1-tier architecture](https://www.interviewbit.com/blog/wp-content/uploads/2022/04/Client-Server-Architecture-Work-800x511.png)

## Types of Client Server Architecture
The functionality of client server architecture is available in various tiers.
### 1-tier architecture 
1-tier architecture contains all sorts of settings on a single device such as configuration setting, marketing logic and data. This architecture is one of the most reliable sources despite the diversity of services. It often results in duplication of the work as the data resides in different variances. Following are the few layers of 1 tier architecture.

a. Presentation layer
b. Business layer
c. Data access layer

All the layers work integrated from a software package and data is stored on local devices.

![1 tier architecture](https://www.interviewbit.com/blog/wp-content/uploads/2022/04/1-tier-architecture-550x352.png)

In the thin client variant, the client embodies only the presentation component, while server absorbs application logic and data storage whereas in thick client, client encapsulates presentation as well as most of the part of application logic and server is responsible for the data storage. The mapping between the conceptual layers (Presentation, application logic, and data maintenance) are called tiers and lead to various types of architectures.

### 2-tier architecture
![2 tier architecture](https://www.interviewbit.com/blog/wp-content/uploads/2022/04/2-tier-architecture-380x886.png)

Having the best environment, this architecture assists the user interface to store at the client side and database at the server device. The business logic and database logic are maintained either on the client side or on the server’s side. When the business logic and database logic are available at the client’s end, the architecture is called “thick client thin server” ; however, if the business logic and database logic are handled at the server’s device, then it is called “thin client thick server”. This architecture is faster than 1 tier architecture as it does not have any intermediary between the client and the server. The best example of 2 tier architecture is the online ticket reservation system where there should be no confusion between two clients. The limitations of this framework are less security, and more users affects the performance of the system.

### 3-tier architecture
In 2-tier architecture, it has no intermediary, but a middleware set between the client and the server in the 3-tier client server architecture. If a client needs a piece of information from the server it will first reach the middle layer and then be dispatched to the server for more actions. The flow remains the same when a server sends a response to the client, it goes through middleware. Middleware has a provision to control and store the data logic and business logic offering optimized flexibility and enhanced performance of the architecture. The three main layers of the framework are:

  + Presentation layer (Users’ Tier)
  + Application layer (Business Tier)
  + Database Tier (Data Tier)
All the three layers are controlled at explicit ends. The presentation layer is controlled at the client’s device, while the business tier or middleware handles the application layer, and the server machine manages the database tier. Due to its 3-layer structure, it provides data control, better security of data, and outperformed data integrity. 

![3 tier architecture](https://www.interviewbit.com/blog/wp-content/uploads/2022/04/3-tier-architecture-800x276.png)

### N-tier architecture
Also known as multi-tier architecture, it is the most scaled form of the other types of architecture. An N-tier architecture comprises different layers with separate responsibilities and manages dependencies running on different machines to enhance the scalability of a system. N-tier servers can perform as open-layer programming in which layers can communicate freely or close layers when a layer communicates with the other one.

![N tier architecture](https://www.interviewbit.com/blog/wp-content/uploads/2022/04/N-tier-architecture-800x358.png)

## Difference Between Peer-to-Peer Network and Client Server Architecture
In addition to client server architecture, distributed computing applications use the peer-to-peer (P2P) application architecture. In this network, two or more peers (computers) pool resources and communicate through the decentralized system. Let us understand the difference between the two architectures.

Client server architecture	                                            Peer-to-peer architecture
It has two components i.e., clients and servers.	                      There is no difference between clients and servers.
It has a centralized data management system.	                          It has its own data and applications and a decentralized system
The purpose is to share information quickly.	                          Its purpose is to maintain connection among peers.
Data is provided only in response to a request raised from the client.	In this network, peers can request as well as provide a service.
It is suitable for small and large networks, both.	                    It is suitable for a few users, less than 10 devices.
‍
## Advantages of Client-Server Architecture
The advantages of client-server architecture are as follows:

  + The centralized network can leverage the control of processes and activities.
  + All the devices can be controlled centrally in a network.
  + Users can access any files at any time while residing at the central storage.
  + It has a good user interface, and a user can easily manage the system for organizing files.
  + A user can easily share resources across various platforms.
  + It requires less maintenance, therefore it is a cost-efficient model.
  + Data recovery is possible in this architecture.

## Disadvantages of Client-Server Architecture
The disadvantages of client-server architecture are mentioned below:

  + If the primary server is not working, the whole model is disrupted.
  + It is more prone to viruses, trojans, and malware.
  + Man in the Middle attacks are common as data packets can be spoofed during transmission.
  + The architecture needs a particular Operating system associated with networking.
  + Multiple users can cause traffic congestion at any time.
  + It needs highly technical stuff for maintaining the network such as server machines.

## Conclusion
A networking model is an act of establishing strategic alliances by communicating and exchanging data with various individuals, computers, or organizations. Client-server architecture is a part of a networking model that allows communication between two elements: clients (requestor) and server (provider of requested services) through networking devices. Big or small organizations leverage the power of networking to digitize their business. Improve knowledge base and scale their products with graphical user interface and shared database.

## FAQ’s
Q. What are variations on the client-server model?
A: Following are the variations on the client server model: –

  + Mobile Code
  + Mobile agents
  + Network computers
  + Thin clients
  + Mobile devices and spontaneous networking
Q: How many types of servers are there?
A: Mainly, there are 8 types of servers.

1. Web Server
2. Database Server
3. eMail Server
4. Web Proxy Server
5. DNS Server
6. FTP Server
7. File Server
8. DHCP Server

Q. Name two processes in the client server model for interaction?
A: The two processes in client-server model are: –

Sockets
Remote Procedure Calls (RPC)
Q: What Is Acid Property In Client Server Environment?
A: Andrew Reuter in 1983 coined the term ACID, which stands for Atomicity, Consistence, Isolation and Durability.

Takeaway
Client server model also known as the networking computing model in which a server hosts, delivers, and manages all the resources and services as requested by the client.



OSI Model
867.2k views
App Security
Essentials
Protocols
What Is the OSI Model
The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980s

The modern Internet is not based on OSI, but on the simpler TCP/IP model. However, the OSI 7-layer model is still widely used, as it helps visualize and communicate how networks operate, and helps isolate and troubleshoot networking problems.

OSI was introduced in 1983 by representatives of the major computer and telecom companies, and was adopted by ISO as an international standard in 1984.

OSI Model Explained: The OSI 7 Layers
OSI 7 layers

We’ll describe OSI layers “top down” from the application layer that directly serves the end user, down to the physical layer.

7. Application Layer

The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users. A few examples of application layer protocols are the Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).

6. Presentation Layer

The presentation layer prepares data for the application layer. It defines how two devices should encode, encrypt, and compress data so it is received correctly on the other end. The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.

5. Session Layer

The session layer creates communication channels, called sessions, between devices. It is responsible for opening sessions, ensuring they remain open and functional while data is being transferred, and closing them when communication ends. The session layer can also set checkpoints during a data transfer—if the session is interrupted, devices can resume data transfer from the last checkpoint.

4. Transport Layer

The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end. It is responsible for reassembling the segments on the receiving end, turning it back into data that can be used by the session layer. The transport layer carries out flow control, sending data at a rate that matches the connection speed of the receiving device, and error control, checking if data was received incorrectly and if not, requesting it again.

3. Network Layer

The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end. The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses (typically Internet Protocol addresses) to route packets to a destination node.

2. Data Link Layer

The data link layer establishes and terminates a connection between two physically-connected nodes on a network. It breaks up packets into frames and sends them from source to destination. This layer is composed of two parts—Logical Link Control (LLC), which identifies network protocols, performs error checking and synchronizes frames, and Media Access Control (MAC) which uses MAC addresses to connect devices and define permissions to transmit and receive data.

1. Physical Layer

The physical layer is responsible for the physical cable or wireless connection between network nodes. It defines the connector, the electrical cable or wireless technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.

Advantages of OSI Model
The OSI model helps users and operators of computer networks:

Determine the required hardware and software to build their network.
Understand and communicate the process followed by components communicating across a network. 
Perform troubleshooting, by identifying which network layer is causing an issue and focusing efforts on that layer.
The OSI model helps network device manufacturers and networking software vendors:

Create devices and software that can communicate with products from any other vendor, allowing open interoperability
Define which parts of the network their products should work with.
Communicate to users at which network layers their product operates – for example, only at the application layer, or across the stack.
OSI vs. TCP/IP Model
OSI vs. TCPIP models

The Transfer Control Protocol/Internet Protocol (TCP/IP) is older than the OSI model and was created by the US Department of Defense (DoD). A key difference between the models is that TCP/IP is simpler, collapsing several OSI layers into one:

OSI layers 5, 6, 7 are combined into one Application Layer in TCP/IP
OSI layers 1, 2 are combined into one Network Access Layer in TCP/IP – however TCP/IP does not take responsibility for sequencing and acknowledgement functions, leaving these to the underlying transport layer.
Other important differences:

TCP/IP is a functional model designed to solve specific communication problems, and which is based on specific, standard protocols. OSI is a generic, protocol-independent model intended to describe all forms of network communication.
In TCP/IP, most applications use all the layers, while in OSI simple applications do not use all seven layers. Only layers 1, 2 and 3 are mandatory to enable any data communication.


What is the TCP/IP Model?
TCP/IP Model helps you to determine how a specific computer should be connected to the internet and how data should be transmitted between them. It helps you to create a virtual network when multiple computer networks are connected together. The purpose of TCP/IP model is to allow communication over large distances.

TCP/IP stands for Transmission Control Protocol/ Internet Protocol. TCP/IP Stack is specifically designed as a model to offer highly reliable and end-to-end byte stream over an unreliable internetwork.

In this TCP/IP tutorial, you will learn:

TCP Characteristics
Four Layers of TCP/IP model
Application Layer
Transport Layer
Internet Layer
The Network Interface Layer
Differences between OSI and TCP/IP models
Most Common TCP/IP Protocols
Advantages of the TCP/IP model
Disadvantages of the TCP/IP model
TCP Characteristics
Here, are the essential characteristics of TCP IP protocol:

Support for a flexible TCP/IP architecture
Adding more system to a network is easy.
In TCP IP protocols suite, the network remains intact until the source, and destination machines were functioning properly.
TCP is a connection-oriented protocol.
TCP offers reliability and ensures that data which arrives out of sequence should put back into order.
TCP allows you to implement flow control, so sender never overpowers a receiver with data.
Four Layers of TCP/IP model
In this TCP/IP tutorial, we will explain different layers and their functionalities in TCP/IP model:

TCP/IP Conceptual Layers
TCP/IP Conceptual Layers
The functionality of the TCP IP model is divided into four layers, and each includes specific protocols.

TCP/IP is a layered server architecture system in which each layer is defined according to a specific function to perform. All these four TCP IP layers work collaboratively to transmit the data from one layer to another.

Application Layer
Transport Layer
Internet Layer
Network Interface
Four Layers of TCP/IP model
Four Layers of TCP/IP model


Application Layer
Application layer interacts with an application program, which is the highest level of OSI model. The application layer is the OSI layer, which is closest to the end-user. It means the OSI application layer allows users to interact with other software application.

Application layer interacts with software applications to implement a communicating component. The interpretation of data by the application program is always outside the scope of the OSI model.

Example of the application layer is an application such as file transfer, email, remote login, etc.

The function of the Application Layers are:
Application-layer helps you to identify communication partners, determining resource availability, and synchronizing communication.
It allows users to log on to a remote host
This layer provides various e-mail services
This application offers distributed database sources and access for global information about various objects and services.
Transport Layer
Transport layer builds on the network layer in order to provide data transport from a process on a source system machine to a process on a destination system. It is hosted using single or multiple networks, and also maintains the quality of service functions.

It determines how much data should be sent where and at what rate. This layer builds on the message which are received from the application layer. It helps ensure that data units are delivered error-free and in sequence.

Transport layer helps you to control the reliability of a link through flow control, error control, and segmentation or de-segmentation.

The transport layer also offers an acknowledgment of the successful data transmission and sends the next data in case no errors occurred. TCP is the best-known example of the transport layer.

Important functions of Transport Layers:
It divides the message received from the session layer into segments and numbers them to make a sequence.
Transport layer makes sure that the message is delivered to the correct process on the destination machine.
It also makes sure that the entire message arrives without any error else it should be retransmitted.
Internet Layer
An internet layer is a second layer of TCP/IP layes of the TCP/IP model. It is also known as a network layer. The main work of this layer is to send the packets from any network, and any computer still they reach the destination irrespective of the route they take.

The Internet layer offers the functional and procedural method for transferring variable length data sequences from one node to another with the help of various networks.

Message delivery at the network layer does not give any guaranteed to be reliable network layer protocol.

Layer-management protocols that belong to the network layer are:

Routing protocols
Multicast group management
Network-layer address assignment.
The Network Interface Layer
Network Interface Layer is this layer of the four-layer TCP/IP model. This layer is also called a network access layer. It helps you to defines details of how data should be sent using the network.

It also includes how bits should optically be signaled by hardware devices which directly interfaces with a network medium, like coaxial, optical, coaxial, fiber, or twisted-pair cables.

A network layer is a combination of the data line and defined in the article of OSI reference model. This layer defines how the data should be sent physically through the network. This layer is responsible for the transmission of the data between two devices on the same network.

Differences between OSI and TCP/IP models
Difference between OSI and TCP/IP model
Difference between OSI and TCP/IP model

Here, are some important differences between the OSI and TCP/IP model:

OSI Model	TCP/IP model
It is developed by ISO (International Standard Organization)	It is developed by ARPANET (Advanced Research Project Agency Network).
OSI model provides a clear distinction between interfaces, services, and protocols.	TCP/IP doesn’t have any clear distinguishing points between services, interfaces, and protocols.
OSI refers to Open Systems Interconnection.	TCP refers to Transmission Control Protocol.
OSI uses the network layer to define routing standards and protocols.	TCP/IP uses only the Internet layer.
OSI follows a vertical approach.	TCP/IP follows a horizontal approach.
OSI model use two separate layers physical and data link to define the functionality of the bottom layers.	TCP/IP uses only one layer (link).
OSI layers have seven layers.	TCP/IP has four layers.
OSI model, the transport layer is only connection-oriented.	A layer of the TCP/IP model is both connection-oriented and connectionless.
In the OSI model, the data link layer and physical are separate layers.	In TCP, physical and data link are both combined as a single host-to-network layer.
Session and presentation layers are not a part of the TCP model.	There is no session and presentation layer in TCP model.
It is defined after the advent of the Internet.	It is defined before the advent of the internet.
The minimum size of the OSI header is 5 bytes.	Minimum header size is 20 bytes.
Most Common TCP/IP Protocols
Some widely used most common TCP/IP protocol are:

TCP:
Transmission Control Protocol is an internet protocol suite which breaks up the message into TCP Segments and reassembling them at the receiving side.

IP:
An Internet Protocol address that is also known as an IP address is a numerical label. It is assigned to each device that is connected to a computer network which uses the IP for communication. Its routing function allows internetworking and essentially establishes the Internet. Combination of IP with a TCP allows developing a virtual connection between a destination and a source.

HTTP:
The Hypertext Transfer Protocol is a foundation of the World Wide Web. It is used for transferring webpages and other such resources from the HTTP server or web server to the web client or the HTTP client. Whenever you use a web browser like Google Chrome or Firefox, you are using a web client. It helps HTTP to transfer web pages that you request from the remote servers.

SMTP:
SMTP stands for Simple mail transfer protocol. This protocol supports the e-mail is known as a simple mail transfer protocol. This protocol helps you to send the data to another e-mail address.

SNMP:
SNMP stands for Simple Network Management Protocol. It is a framework which is used for managing the devices on the internet by using the TCP/IP protocol.

DNS:
DNS stands for Domain Name System. An IP address that is used to identify the connection of a host to the internet uniquely. However, users prefer to use names instead of addresses for that DNS.

TELNET:
TELNET stands for Terminal Network. It establishes the connection between the local and remote computer. It established connection in such a manner that you can simulate your local system at the remote system.

FTP:
FTP stands for File Transfer Protocol. It is a mostly used standard protocol for transmitting the files from one machine to another.

Advantages of the TCP/IP model
Here, are pros/benefits of using the TCP/IP model:

It helps you to establish/set up a connection between different types of computers.
It operates independently of the operating system.
It supports many routing-protocols.
It enables the internetworking between the organizations.
TCP/IP model has a highly scalable client-server architecture.
It can be operated independently.
Supports a number of routing protocols.
It can be used to establish a connection between two computers.
Disadvantages of the TCP/IP model
Here, are few drawbacks of using the TCP/IP model:

TCP/IP is a complicated model to set up and manage.
The shallow/overhead of TCP/IP is higher-than IPX (Internetwork Packet Exchange).
In this, model the transport layer does not guarantee delivery of packets.
Replacing protocol in TCP/IP is not easy.
It has no clear separation from its services, interfaces, and protocols.
Summary:
The full form of TCP/IP model explained as Transmission Control Protocol/ Internet Protocol.
TCP supports flexible architecture
Application layer interacts with an application program, which is the highest level of OSI model.
Internet layer is a second layer of the TCP/IP model. It is also known as a network layer.
Transport layer builds on the network layer in order to provide data transport from a process on a source system machine to a process on a destination system.
Network Interface Layer is this layer of the four-layer TCP/IP model. This layer is also called a network access layer.
OSI model is developed by ISO (International Standard Organization) whereas TCP/IP model is developed by ARPANET (Advanced Research Project Agency Network).
An Internet Protocol address that is also known as an IP address is a numerical label.
HTTP is a foundation of the World Wide Web.
SMTP stands for Simple mail transfer protocol which supports the e-mail is known as a simple mail transfer
SNMP stands for Simple Network Management Protocol.
DNS stands for Domain Name System.
TELNET stands for Terminal Network. It establishes the connection between the local and remote computer
FTP stands for File Transfer Protocol. It is a mostly used standard protocol for transmitting the files from one machine to another.
The biggest benefit of TCP/IP model is that it helps you to establish/set up a connection between different types of computers.
TCP/IP is a complicated model to set up and manage.
What are the different types of TCP/IP layers?
There are four types of TCP/IP layers.
Application layer
Transport layer
Internet layer
Network interface

https://www.guru99.com/tcp-ip-model.html
https://www.imperva.com/learn/application-security/osi-model/
