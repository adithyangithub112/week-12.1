### .

Both Secure Socket Layer and Transport Layer Security are the protocols used to provide security between web browsers and web servers. The main difference between Secure Socket Layer and Transport Layer Security is that, in SSL (Secure Socket Layer), the Message digest is used to create a master secret and it provides the basic security services which are **Authentication** and **confidentiality.** While in TLS (Transport Layer Security), a Pseudo-random function is used to create a master secret.

# Secure Socket Layer (SSL)

The Secure Socket Layer (SSL) is a cryptographic protocol designed to provide secure communication over a computer network. It was developed by **Netscape** in the 1990s to establish an encrypted link between the web server and a web browser. SSL operates by using encryption to secure the transmission of data ensuring that sensitive information such as credit card details and personal data remains confidential.

### Key Features of SSL

- Encryption: It uses encryption algorithms to protect data during transmission.
- Authentication: It verifies the identity of the server to ensure that data is sent to the correct destination.
- Data Integrity: It ensures that data has not been altered during the transmission.
- Fortezza algorithm: The Fortezza algorithm is a cryptographic system that was used in early versions of SSL (like SSL 3.0) to support strong encryption for secure communications.

# Transport Layer Security (TLS)

The Transport Layer Security (TLS) is the successor to SSL and is designed to provide improved security and efficiency. TLS was developed as an enhancement of SSL to the address various vulnerabilities and to the incorporate modern cryptographic techniques. The first version, TLS 1.0 was based on SSL 3.0 but included significant improvements. TLS continues to evolve with the newer versions offering enhanced the security features.

### Key Features of TLS

- Enhanced Encryption: It uses stronger encryption algorithms compared to SSL.
- Forward Secrecy: It supports forward secrecy which ensures that session keys are not compromised even if the server's private key is exposed.
- Improved Performance: It provides better performance and efficiency with the optimized algorithms and protocols.

# Difference Between Secure Socket Layer (SSL) and Transport Layer Security (TLS)

| **SSL** | **TLS** |
| --- | --- |
| SSL stands for Secure Socket Layer. | TLS stands for Transport Layer Security. |
| It supports the Fortezza algorithm. | It does not support the Fortezza algorithm. |
| It is the 3.0 version. | It is the 1.0 version. |
| In SSL( Secure Socket Layer), the Message digest is used to create a master secret. | In TLS(Transport Layer Security), a Pseudo-random function is used to create a master secret. |
| In SSL( Secure Socket Layer), the Message Authentication Code protocol is used. | In TLS(Transport Layer Security), Hashed Message Authentication Code protocol is used. |
| It is more complex than TLS(Transport Layer Security). | It is simple than SSL. |
| It is less secured as compared to TLS(Transport Layer Security). | It provides high security. |
| It is less reliable and slower. | It is highly reliable and upgraded. It provides less latency. |
| It has been depreciated. | It is still widely used. |
| It uses port to set up explicit connection. | It uses protocol to set up implicit connection. |
