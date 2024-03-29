# Executive Summary
The purpose of this lab is to explore the protocols that provide support for internet communication such as IP, TCP/IP, and HTTP. Additionally the lab will describe Internet programming methodologies and practice creating a web page using HTML and CSS.
## Internet Architecture
### Internet Protocol
An IP address, or Internet Protocol Addresss, is a set if numbers assigned to a computer network interface. There are two major types of IP, IPV4 and IPV6. IPV4 which was created in the 1980's is a string of four numbers all between 0 and 225 that are separated by dots i.e. 192.0.2.53. IPV6 was standardized in 1996 and is a significantly longer string of numbers that is written in hexadecimal form in order to fit more infomration into fewer digits. The segments of IP in IPV6 are separated by colons such as 2001:0db8::53. 

ICANN, the Internet Corporation for Assigned Names and Numbers, is a major contributor to the global internet. They are the operator of Internet Assigned Numbers Authority (IANA) functions. This means that they allocate IP addresses to the five regional internet registeries which then allocate them to smaller operators which eventually assign them to the individual internet connections we are used to encountering. 
### TCP/IP
TCP/IP, Transmission Control Protocol / Internet Protocol, is a network protocol that defines the details of how data is sent and recieved through the various network hardware components. It follows the client server model using a device as the client and another device as a server too. Information is sent when the client knows the IP address of the server so information can be sent. 
When using TCP/IP a layered protocol stack is one of the smartest ways to do it. This approach allows for one part of the protocol to be changed without affecting the other layers of it. With the frequency of changes in technology, you do not want to have to constantly rewrite yourr entire protocol. This method allows for specific parts to be changed as needed instead of haing to change the entire thing. 
In the application layer, things like software will run using protocols such as HTTP, FTP, POP3, SMTP, and SNMP. 
### Internet Security
HTTP or hypertext transfer protocolis probably the most widely used protocol today as it is what allows webpages to be viewed. It supports the client server model by allowing public data transfer and the viewing of web pages to anyone. HTTPS is a secure version of HTTP that encrypts the data transferred between compuers and over the internet. It does this using SSL or secure sockets layer that uses public key encryption or using TLS or transport layer security which is the latest cryptographic protocol and is similar to SSL in that it verifies the server, client and encrypts the data. 
### Securing Your Web Browser
With today's technology it is important to secure your web browser. This can be done by disabling things that come preinstalled on web browsers which can cause vulerabilities. If you are using a unsecure web browser hackers may be able to install spyware without your knowledge. A lot of websites today use cookies which store specific information in ordr to allow individual visitors to be identified which hackers may be able to obtain. 
## Internet Programming
### World Wide Web Consortium
Tim Berners-Lee is the inventor and director of the World Wide Web. He founded W3C to develop interoperable technologies in order to lead the web to its full potential. There are many standards involved with W3C. One that is important is web architecture which focuses on technologies and principles which sustain the Web, including HTTP which was discussed previously. 
### HTML5 and CSS
HTML5 is the standard markup language for creating web pages. It is a series of elements each with their own function that tells a browser how to display the content. CSS or cascading style sheet is used to format the layout of a webpage and can be used to control multiple pages at once which saves time.  For my webpage I used the CSS Internal format to display the content with a background color, border, and colored heading.
### HTML and XML
XML and HTML are two very different things. XML was created to carry data so it requires a separate program to run or display it. HTML was created to display data. 
## Components of a URL
### Scheme 
A scheme tells the browser what type of address a page is so the browser can connect correctly typically this is http or https. 
### Domain
A domain is made up of several parts and is the most prominent part of the web page name. 
#### Top Level Domain
The top level domain is the end part of the domain such as the .edu you may see at the end of a webpage URL. 
### Default Page
The default page is what loads when you enter a web address but don't specify a certain file path. For example www.amazon.com will take you to the homepage of Amazon.
### Parameters
At the end of the path sometimes a URL will have a string of random characters beginning with a question mark.
### Anchor 
Also at the end of the path is the anchor. This tells the browser to load a specific part of the page. 
# Conclusion
The purpose of this lab is to explore the protocols that provide support for internet communication such as IP, TCP/IP, and HTTP. Additionally the lab will reviewed Internet programming methodologies and practice creating a web page using HTML and CSS. The most difficult part was using the relative path to display the image on the web page and I ended up having to use the absolute path to the original website to get it to display correctly. Overall, the information regarding creating the web page using HTML was the most interesting and is something I look forward to getting more familiar with. 
