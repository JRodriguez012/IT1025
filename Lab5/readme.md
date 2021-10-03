## Javi Rodriguez / Date

## Executive Summary 
Lab 5 covers diagramming with Lucidchart, the basics of networking, cybersecurity and encryption. Lucidchart is a diagramming tool that can be used for planning software, networks, etc. We learn some of the fundamental terms used in networking and the hardware that is linked together using different topologies to create a network. This lab 
also covers topics of cybersecurity such as the security triad, authentication, and access control models that are used to determine which users have access to specific information. Finally lab 5 explores cryptography, what encryption is and the different methods and ciphers used to encode and decode messages.

## Lucidchart
Lucidchart is a tool used for creating diagrams. It was incredibly easy to sign up and create a diagram for a program. I like being able to plan out the individual pieces of a program and seeing how the program flows as a whole. I think Lucidchart is a great tool for planning and visualizing programs. 

## Introduction to Networking

### Data Transmission
#### Packet: Unit of data. 
When a message is sent over the internet it is broken down into smaller pieces, called packets. A packet contains the sender's address, the destination address, a sequence number, and a piece of the overall message that is sent. Packets can take different routes to the destination and can arrive at different times, therefore the sequence number is used to reassemble packets in the correct order at their destination.
#### Packet-Switching: Technology that allows packets of data to be routed base on destination address.
When packets are sent over the internet, routers attempt to find to most optimal route for each packet. This results in packets taking different routes toward their destination. When the packets arrive, they are reassemble into the original message.
#### IP Address: Unique identifying number.
Every device on the internet is assigned a unique indentifying number called an IP (Internet Protocol) address. Originally the IPv4 standard was used for IP addresses with a format of four numbers with values of 0 to 255 seperated by a period. The limit of IPv4 addresses and the growth in use of the internet led to the new IPv6 standard. The IPv6 format has eight groups of four hexadecimal digits seperated by semi-colons.

#### DNS: Directory of IP address common names.
DNS (Domain Name Server) acts as a directory of websites on the internet. When access to a host is requested with a domain name, a DNS server returns the IP address of that host.

#### Protocol: Set of rules to allow devices to communicate.
A protocol is the set of rules that govern how communications take place on a network. FIle Transfer Protocol (FTP) sets the rules for transferring files from one host to another.

### Networking Hardware
#### Switch vs. Hub
A hub connects devices together on an internal network by accepting ethernet connections from those devices through its ports. A hub only knows whether a device is connected to it, it does not know to which device data is supposed to be sent. When data arrives to one of the hub's ports, that data is copied to all of its other ports. A switch is like a hub in that it connects devices on an internal network through ethernet connections. Unlike a hub, a switch stores physical addresses (MAC address) of the devices connected to it. When a switch receives data, it can direct that data to the intended destination port. Switches are preferred to hubs because they reduce unnecessary traffic on the network.

#### Router vs. Switch and Hub
Switches and hubs are used to exchange data within a local area network. They cannot be used to exchange data outside of their own network because they are not capable of reading IP addresses. The benefit of routers over hubs and switches is its ability to connect networks. A router routes data from one network to another based on their IP address. When a router receives a data packet, the router inspects the data's IP address and determines if the packet was meant for its own network or another network. If the data was meant for its own network it receives it. If the data was not meant for its own network it sends the data off to another network.
### Network Topologies
#### Single point of Failure
A single point of failure is a part of a network that, if it fails, will cause the entire network to go down. Topologies that experience this issue are the star, ring, and bus topologies.
#### Infrastrucutre vs. Wireless Mesh
The infrastructure topology uses a combination of wired and wireless devices. In an infrastructure topology, wired devices are physically connected to a switch and a wireless access point that allows wireless devices to connect to the network is also physically connected to the same switch. The wireless access point acts as a bridge between the wired and wireless networks. The wireless mesh topology is similar to the infrasture topology in that you have a wireless access point physically connected to a switch. But in a wireless mesh, each wireless access point will talk to other wireless access points that are not physically connected to the switch. When a device connects to a wireless access point, its connection is relayed between wireless access points until it reaches back to the modem. I think that the wireless mesh topology is better as the wireless network will remain up if any one of the wireless access points that are not connected to the switch fails. You also have the ability to extend your wireless network as wide as you want without the use of physical cables.
### Network Design
The design for my network uses an infrastructure topology. The router is connected to a switch which is connected to two computers, a printer, and a wireless access point. The wireless access point is used to connect wireless devices to the network.
### NSA/CSS
The National Security Agency's (NSA) role in U.S. cybersecurity is to prevent and eradicate threats towards U.S. national security systems.
## Cybersecurity and Encryption

### Information Systems Security

#### Security Triad
Confidentiality, Integrity, and Availability (CIA) make up the security triad. For the approach of amazon.com online chat, confidentiality would restrict your personal information and messages to only being seen by you or employees who handle customer support. Integrity would ensure to you that you are messaging with an actual amazon representative. Availability would guarantee that your account information could be accessed or updated by you or someone authorized to do so at any time.
#### Authentication
Entering your house requires authentication because you need a key to unlock the door. This could be converted to multi-factor authentication with an alarm system. You would the key to unlock the door and the code to disable the alarm system. Checking emails require authentication as you need to know your email address and password. Many email services provide multi-factor authentication by texting a code to a linked phone number. Using a debit card requires authentication as you need your physical card. Debit cards use multi-factor authentication with a 4 digit pin or requiring a signature after use.
#### ACL and RBAC
Access Control List (ACL) and Role-Based Access Control (RBAC) are access control models that determine which users are authorized to read, modify, add, or delete information. ACLs give individual users access to information resources. The advantage of ACLs is that they are simple to understand and maintain with a small number of users and resources. But as the number of users and information resources grow, ACLs become harder to maintain as it is much more tedious when a administrator has to add or remove a user from a large set of information resources. RBACs assign roles to users and then those roles are assigned access to information resources. The advantage of RBACs is that users and roles can be managed seperately which simplifies administration and improves security. The disadvantage of RBACs is the inability to give an individual user specific rights without creating an entirely new role.
#### Ciphertext, Public Key and Private Key
Encryption is a process of encoding data so that it can only be accessed by authorized individuals. Ciphertext is an encoded plain text message that can only be read after being decoded. Public key encryption uses two keys, a public key and a private key. You use the public key to encode a message, transforming your plaintext message into ciphertext, and send it. The recipent then uses the private key to decode the message, transforming the ciphertext into a plaintext message.
#### Public Key Cryptography
Public key encryption allows users to use a shared key to send secure messages without knowing anything about each other.
### Cryptography
#### Encryption
cryptography is a growing field

shofjewhqfxo yi q whemydw vyubt

The orignal message is encrypted using a shift of 16, meaning each letter in the encrypted message derives 16 positions away from the original letter. Therefore, 'a' becomes 'q', 'b' becomes 'r', 'c' becomes 's', etc. To decrypt the message, you must subtract the shift of 16 from each letter.

#### Frequency Fingerprint
In my message "frequency fingerprint exploration is really cool", the most frequent letter is 'e' which is typically the most frequent letter in a message. The letters 'a' and 't' do not appear very often in my message which is unusual. The frequency fingerprint would be different for different languages as there are different characters in other languages that do not exist in english, but each language would have it's own frequency fingerprint.
#### Polyalphabetic Cipher
A polyalphabetic cipher is a cipher that uses multiple shifts. A shift word is used to encrypt the message as each letter in the shift word is converted to a number that is its position in the alphabet. Then that sequence of numbers is repeated throughout the message to be encrypted. Finally, each letter is encrypted by shifting according to the number below it.
#### Polyalphabetic Example
My secter message "hello my name is" uses the shift word "javi". After being encrypted the message becomes "rfhuy nu wkna rc". The frequency fingerprint of the message is much more evenly distributed than the caesar cipher.
#### Brute-Force
A brute-force attack decrypts a ciphertext by attempting every possible decryption key. Brute-force attacks are very effective against the Caesar cipher because there are not that many possible keys that can be used.
## Conclusion
Include your professional conclusion here...

