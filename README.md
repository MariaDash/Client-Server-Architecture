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

     + Thick client/ Fat client – A thick client provides rich functionality, as it is least dependent on the server and able to perform most of the data processing tasks itself.
        
     + Thin client- It is a lightweight computer relying heavily on the resources of the host computer. An application server performs all the data processing tasks.
        
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
