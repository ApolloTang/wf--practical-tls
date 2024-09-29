# Key Players



1. client
2. Server
3. Certificate Authority (CA)



## Client and Server

|| Client | Server                                     |
| ----------------------------------------: | -------------------------- | ------------------------------------------ |
| action                                    | initiale the TLS handshake | receiving the TLS handshake                |
| entity                                    | web brower, phone, IoT     | web server, load balancer, SSL Accelerator |
| Authentication by providing a certificate | Optionally and rarely      | Always authenticated                       |



## Certificate Authority

- Governing entity that issues certificates

- The client and server don't trust each other, but they trust the certificate authority. They trust the CA because it is the **Trust Anchor** (we trust what the trust anchor trusts). 

### Five main Certificate Authority:

- IdenTrust (Let's Encrypt)
- DigiCert (GeoTrust, Verisign, Thawte)
- Sectigo (formally known as Comodo
- GoDaddy
- GlobalSign



The above secures 98% of the internet; you can see the link to the break down of statistics:

http://w3techs.com/technologies/overview/ssl_certificate/all
