## Javi Rodriguez / October 10, 2021

## Executive Summary 
Lab 6 covers internet architecture, internet security, internet programming, and the components of URLs. The internet uses different protocols to define how devices connect to each other, how data is sent and received, and how that data is secured when sent over the internet. This lab discusses vulnerabilities that exist in web browser and what you can do to minimize the risk of having your device compromised through those vulnerabilities. In this lab, we learn some of the basics of HTML and CSS. I used HTML and CSS to create a web site that discusses horror movies and give it an appropriate theme. Finally, lab 6 breaks down the components that make up URLs and what these components tell the user about a particular website.
## Internet Architecture
### Internet Protocol
#### IP Address
Internet Protocol (IP) address is a unique number assigned to a specific computer that is connected to the internet. IPv4 is the original version of an IP address. IPv4 addresses are made up of four numbers between 0 and 255, separated by dots. IPv4 can only have around four billion unique IP addresses which is not enough for the number of internet devices used today. IPv6 was developed to increase the number of available IP addresses. IPv6 addresses are made up of eight hexadecimal numbers, separated by colons. IPv6 has enough space for 340 undecillion addresses.
#### ICANN
ICANN is a not-for-profit public-benefit corporation with a mission of keeping the internet secure and stable. ICANN is the operator of Internet Assigned Numbers Authority (IANA) functions and allocates IP address blocks to the five Regional Internet Registries (RIR) around the world. Those RIRs then allocate smaller blocks to Internet Service Providers (ISP). The ISPs then assign address to individual internet connections. ICANN is at the top of the hierachy for distributing IP addresses.
### TCP/IP
#### Responsibility of TCP/IP
Transmission Control Protocol / Internet Protocol (TCP/IP) is responsible for defining the details of how data is sent and received through network communication hardware. TCP/IP is designed such that each computer has a unique IP address and each IP address can send and receive data over different ports.
#### Client-Server Model and TCP/IP
In a TCP/IP connection, the "server" is a computer that is "listening" for incoming connections and chooses to either accept or reject those connections. The "client" is a computer that attempts to initiate a connection with the server, therefore the client needs to know the IP address of the server to connect to. Once a connection between the client and server, data can be sent in either direction across the network. This connection remains open until either the client or server terminates the connection. 
#### Layers
Layers are important to changing technology because individual layers can be modified without affecting any of the other layers. This allows us to remain flexible and stops us from having to make changes to the entire software each time an individual layer is changed.
#### Application Layer
Application protocols run on the "application" layer. HTTP, FTP, POP3, SMTP, SNMP are application protocols that run on the application layer of the TCP/IP protocol suite.

## Internet Security
### HTTP and Client-Server Model
Hypertext Transfer Protocol (HTTP) is a protocol used for viewing web pages on the internet. The client requests a web page from a server by typing a domain in the browser in which http:// is then added to the beginning of the domain. The server then sends the information to view the web page back to the client. In HTTP, all information is sent in clear text.
### Protocols for Secure HTTP
Secure HTTP protects data by using either the Secure Sockets Layer (SSL) or Transport Layer Security (TLS) protocol. SSL uses public key encryption to secure data. When a computer connects to a web site that uses SSL, the web browser will ask the web site to identify itself. The web server will then send the computer a copy of its SSL certificate that is used to authenticate the site's identity. TLS is the latest standard cryptographic protocol and successor to SSL. TLS authenticates the server, client, and encrypts data.

## Securing your Web Browser
### Reasons to Secure Browser
As web browsers are frequently used, you should secure your browser to reduce the risk of your computer being compromised. An unsecure browser can lead to computer problems caused potentially by spyware being installed or even an intruder taking control of your computer. Attackers often compromise computers by exploiting vulnerabilities in web browsers through compromised or malicious websites. 
### Risk Explained
JavaScript is a scripting language that allows web page authors to add more interactivity to a web page. This capability can be abused by attackers introducing vulnerabilities such as Cross-Site Scripting. Cross-Site Scripting permits an attacker to leverage the trust that you have with a website. This could potentially allow an attacker to collect your personal data through another site.

## Internet Programming
### World Wide Web Consortium
Tim Berners-Lee is the inventor of the World Wide Web and director of the World Wide Web Consortium (W3C). W3C is a Web standards organization which develops specifications, guidelines, software, and tools to lead the Web to its full potential. The Extensible Markup Language (XML) is a standard that uses a text-based format for representing structured information such as documents, data, transactions, etc. XML is important for reliably sharing structured information locally and across networks between programs, between people, or between computers and people.
### HTML5 and CSS
Hyper Text Markup Language (HTML) is the standard markup language for creating web pages. HTML is used to describe the structure and content that makes up a web page. Cascading Style Sheet (CSS) is used to format the layout of a web page. CSS allows you to control the colors of fonts and backgrounds, the size of text, spacing between elements, etc. I used HTML and CSS to make a web page that talks about horror movies. I used HTML to display the text for the web page and link to a Rotten Tomatoes list of horror movies. I used CSS to change the background color to red, change the color of the text and link to white, change the sizes of and center the elements, and add a border around the paragraph.
### HTML and XML
Extensible Markup Language (XML) is used to store and transport data. XML does not do anything. HTML is designed to data, while XML is designed to carry data. Unlike HTML, XML does not have any predefined tags. XML's tags are defined by the author of the XML document.
## Components of a URL
#### Scheme: https
Every URL begins with the scheme. The scheme tells the browser what type of address the URL is so that the browser connects to it correctly. Typical schemes for web browsing are http and https. A scheme is always part of the URL but is not always displayed by the browser.
#### Domain: www.amazon.com
The domain name is the most prominent component of a URL. Different pages on the same site will typically use the same domain name. Each segment of the domain name separated by a period is called a domain.
#### Top level domain: .edu
The domain on the right of a URL is called the top-level domain. This domain usually gives you more information on what kind of site it is. The top-level domain .gov is used for government sites in the United States. The domain .edu is reserved for organizations with a focus on education like universities.
#### Default page: no file path provided
URLs that end with a domain name and no file path will usually load  a default page. This page is designed to help users navigate to a specific page on the site.
#### Parameters: result of search
Parameters are strings of characters that sometimes appear after the path Parameters can be seen after performing a search on a site like Google or YouTube.
#### Anchor: specific location on a page
The anchor tells the browser to load or scroll to a specific part of the page. The anchor also appears after the path and typically begins with a hashtag.

## Conclusion
In this lab, we discuss the protocols used to connect devices, send data, and secure data over the internet. The TCP/IP and HTTP protocols use client-server models in which one device acts as a "client" that requests a connection with, sends data to, and receives data from a "server". This lab also discusses some of the vulnerabilities in browsers and what you can do to make your browser more secure. My favorite part of this lab was using HTML and CSS to make a web page. I have used HTML and CSS before, but I never spent much time making web pages. I had a lot of fun styling my page to fit with my topic of horror movies. Lastly, this lab breaks down the components of a URL. I understood many of these terms already, but I learned what parameters and anchors are and how they are used.
