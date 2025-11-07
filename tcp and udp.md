Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) are two core transport layer protocols in computer networking. Below are the differences between them.

# Differences between TCP and UDP

| **Basis** | **Transmission Control Protocol (TCP)** | **User Datagram Protocol (UDP)** |
| --- | --- | --- |
| Type of Service | [**TCP**](https://www.geeksforgeeks.org/computer-networks/what-is-transmission-control-protocol-tcp/) is a connection-oriented protocol. Connection orientation means that the communicating devices should establish a connection before transmitting data and should close the connection after transmitting the data. | [**UDP**](https://www.geeksforgeeks.org/computer-networks/user-datagram-protocol-udp/) is the Datagram-oriented protocol. This is because there is no overhead for opening a connection, maintaining a connection, or terminating a connection. UDP is efficient for broadcast and multicast types of network transmission. |
| Reliability | TCP is reliable as it guarantees the delivery of data to the destination router. | The delivery of data to the destination cannot be guaranteed in UDP. |
| Error checking mechanism | TCP provides extensive [**error-checking**](https://www.geeksforgeeks.org/computer-networks/error-detection-in-computer-networks/) mechanisms. It is because it provides flow control and acknowledgment of data. | UDP has only the basic error-checking mechanism using [**checksums.**](https://www.geeksforgeeks.org/computer-networks/error-detection-code-checksum/) |
| Acknowledgment | An acknowledgment segment is present. | No acknowledgment segment. |
| Sequence | Sequencing of data is a feature of Transmission Control Protocol (TCP). this means that packets arrive in order at the receiver. | There is no sequencing of data in UDP. If the order is required, it has to be managed by the application layer. |
| Speed | TCP is comparatively slower than UDP. | UDP is faster, simpler, and more efficient than TCP. |
| Retransmission | Retransmission of lost packets is possible in TCP, but not in UDP. | There is no retransmission of lost packets in the User Datagram Protocol (UDP). |
| Header Length | TCP has a (20-60) bytes variable length header. | UDP has an 8 bytes fixed-length header. |
| Weight | TCP is heavy-weight. | UDP is lightweight. |
| Handshaking Techniques | Uses handshakes such as SYN, ACK, SYN-ACK | It's a connectionless protocol i.e. No handshake |
| Broadcasting | TCP doesn't support Broadcasting. | UDP supports Broadcasting. |
| Protocols | TCP is used by [**HTTP, HTTPs**](https://www.geeksforgeeks.org/computer-networks/difference-between-http-and-https-2/) , [**FTP**](https://www.geeksforgeeks.org/computer-science-fundamentals/file-transfer-protocol-ftp/) , [**SMTP**](https://www.geeksforgeeks.org/computer-networks/simple-mail-transfer-protocol-smtp/) and [**Telnet**](https://www.geeksforgeeks.org/computer-networks/introduction-to-telnet/) . | UDP is used by [**DNS**](https://www.geeksforgeeks.org/computer-networks/details-on-dns/) , [**DHCP**](https://www.geeksforgeeks.org/computer-networks/dynamic-host-configuration-protocol-dhcp/) , TFTP, [**SNMP**](https://www.geeksforgeeks.org/computer-networks/simple-network-management-protocol-snmp/) , [**RIP**](https://www.geeksforgeeks.org/computer-networks/routing-information-protocol-rip/) , and [**VoIP**](https://www.geeksforgeeks.org/computer-networks/voice-over-internet-protocol-voip/) . |
| Stream Type | The TCP connection is a byte stream. | UDP connection is a message stream. |
| Overhead | Low but higher than UDP. | Very low. |
| Applications | This protocol is primarily utilized in situations when a safe and trustworthy communication procedure is necessary, such as in email, on the web surfing, and in military services. | This protocol is used in situations where quick communication is necessary but where dependability is not a concern, such as VoIP, game streaming, video, and music streaming, etc. |
