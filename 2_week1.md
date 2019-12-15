Computer Networking
- the name we give to the full scope of how computers communicate with each other

TCP/IP 5-Layer Network Model

(Bottom) 1. Physical 
- represents the physical devices that interconnect computers

2. data link (network access)
- responsible for defining a common way of interpreting these signals so network devices can communicate
e.g. Ethernet
-> defines a standard responsible for getting data to nodes on the same network or link

3. network layer
- allow different networks to communicate with each other through devices known as ROUTERS

A collection of networks connected together via routers is an INTERNET

IP is the heart of the Internet and most small networks around the world

4. Transport layer 
- sorts out which client and server programs are supposed to get that data
-> TCP (has mechanism ensure data is reliably delivered)
-> UDP(User Datagram Protocal) (does not ...)

5. Application layer
- the content of the package itself


Cables
- connect different devices to each other allowing data to be transmitted over them
-> copper e.g. cat5, cat5e, cat6
-> fiber

Crosstalk
- when an electric pulse on one wire is accidentally detected on another

Hub
- a physical layer device that allows for connections from many computers at once

Collision domain
- a network segment where only one device can communicate at a time

Switch>hub(layer level)
-> LAN(local area network)

router 
- a device that knows how to forward data between independent networks

Border Gateway Protocol(BGP)
- routers share data with each other via this protocol, which lets them learn about this most optimal paths to forward traffic

Bit
- the smallest representation of data that a computer can understand, 1s and 0s

Modulation
- a way of varying the voltage of this charge moving across the cable

Duplex communication
- the concept that info can flow in both directions across the cable

Simplex communication
- this process is unidirectional

Network ports are generally directly attached to the devices that make up a computer network

CSMA/CD
- used to determine when the communications channels are clear, adn when a device is free to transmit data

MAC address
- globally unique identifier attached to an individual network interface
-> 48-bit number normally represented by 6 groupings of two hexadecimal(16-digits) numbers

Octet
- in computer networking, any number that can be represented by 8 bits

OUI 
- the 3 octets of a MAC address

unicast transmittion
- always meant for just 1 receiving address
-> if the least signficiant bit in the first octet of a destination address is set to 0, it means that the ethernet frame is intended for only the destination address
-> if the least significant bit in the first octet of a destination address is set to one, it means that you are dealing with a multicast frame
-> broadcast

data packet
- an all-encompassing term taht represents any single set of binary data being sent across a network link






