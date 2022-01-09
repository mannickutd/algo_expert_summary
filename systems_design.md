# Systems Design

## What are design fundamentals

### Underlying foundational knowledge
* From a brief description can you know where to start to build a system which is going to match the 
### Key characteristics
* availability
* redundancy
* latency
* throughput
### Actual components
* Load balancers
* Master/Slave
* Cluster
### Tech
* Real products that can be used to fulfill characteristics of the system.

## Client Server

### Client
A machine or process that requests data or service from a server.
A client could be be both the process and the machine at the same time.

### Server
A machine or service that provides data or service to a client(s), usually by listening over a network.

### Client-Server Model
Consists of clients requesting data or service from a server(s).

### DNS (Domain Name System)
Describes the entities and protocols involved in the translation from domain names into IP addresses.

### IP Address

### IP Internet Protocol
A set of rules for routing and addressing packets of data so that they can be sent over networks. IP Packet, consists of a an IP header which is the header length, packet length, time to live, and which transport protocol to use (tcp, udp) and a data layer which is a series of bytes.

### TCP Transport Communication Protocol
Network protocol built on top of IP. Allows for ordered, reliable data delivery between machines over the public internet by creating a connection.
TCP is usually implemented in the kernel, which exposes sockets to applications that they can use to stream data through an open connection.
TCP header and TCP data is included in the data part of the IP data part.

### HTTP Hypertext Transfer Protocol


### Network Layers OSI

#### Physical layer
Transmits raw bit stream over a physical medium.
#### Data link layer
Defines the format of the data on the network.
#### Network layer
Decides which physical route the data will take.
#### Transport layer
Transmits data using the transmission protocols including TCP and UDP.
#### Session layer
Maintains connections and is responsible for controlling ports and sessions.
#### Presentation layer
Ensures data is in usable format and is where data encryption occurs.
#### Application layer
Human-computer interaction layer, where application can access the network services.


## Storage

### Databases
Use either disk or memory that provide the ability to store data or to query the data. You access databases using network protocols. 
