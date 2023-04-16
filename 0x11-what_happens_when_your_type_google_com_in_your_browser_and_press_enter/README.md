Have you ever wondered what happens when you type "https://www.google.com" on your browser?
When you enter "https://www.google.com" into your web browser and hit Enter, a series of actions occur in the background. In this article I will outline the sequence of events that take place when visiting a website.

DNS Request: The initial stage involves translating the domain name into an IP address through a DNS request. The Domain Name System (DNS) is responsible for converting domain names into computer-understandable IP addresses. To locate the IP address associated with the domain name, the browser sends a DNS request to a DNS server.

TCP/IP: Once the IP address is obtained, the browser utilizes the Transmission Control Protocol/Internet Protocol (TCP/IP) to establish a connection with the web server. TCP/IP is a communication protocol set that enables internet-based computer communication.

Firewall: Prior to establishing the connection, it passes through a firewall which checks whether the IP address has permission to access the website and verifies the validity of the request. The firewall will prevent access if the request is deemed invalid.

HTTPS/SSL: If the firewall permits the request, the browser and the server commence a secure HTTPS/SSL connection. HTTPS is a safer variant of HTTP that encrypts the browser-server communication. SSL(secure sockets Layer) is a protocol that establishes secure communication online.

Load-balancer: In cases where a website is hosted on multiple servers, the request is forwarded to a load balancer. Its function is to divide the incoming traffic across multiple servers to prevent any one server from being overwhelmed by excessive requests.

Web server: The request then goes to the responsible web server, which processes and responds to it.

Application server: If the website requires server-side processing or contains dynamic content, the request is forwarded to an application server. The application server processes the request and sends back a response.

Database: If the website needs to access data from a database, the browser sends the request to a database server. The server retrieves the data and sends it to an application server. The application server then sends the data to the web server, which ultimately delivers it to the browser.

Typing a website address in the browser and pressing Enter triggers a series of complex events. These include resolving the domain name, establishing a secure connection, distributing traffic, processing requests, retrieving data from databases, and sending responses back to the browser. Knowing this process can be useful for troubleshooting problems, enhancing performance, and developing better web applications.
