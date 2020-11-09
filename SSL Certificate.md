# SSL Certificate

SSL Certificate
Learning Objectives
After reading this article you will be able to:

Understand what an SSL certificate is
Learn about the data recorded in an SSL certificate
Explain why SSL/TLS encryption is necessary
Learn how to get a free SSL certificate

## What is an SSL certificate?

![SSL Certificate Secure Browsing](https://www.cloudflare.com/resources/images/slt3lc6tev37/2mkpUOPzl2jEPEERn2e57B/3b180ecab3ff7e0a5da1706434722573/ssl-certificate-secure-browsing.png)



SSL certificates are what enable websites to move from [HTTP](https://www.cloudflare.com/learning/ddos/glossary/hypertext-transfer-protocol-http/) to [HTTPS](https://www.cloudflare.com/learning/ssl/what-is-https/), which is more secure. An SSL certificate is a data file hosted in a website's [origin server](https://www.cloudflare.com/learning/cdn/glossary/origin-server/). SSL certificates make [SSL/TLS encryption](https://www.cloudflare.com/learning/ssl/what-is-ssl/) possible, and they contain the website's public key and the website's identity, along with related information. Devices attempting to communicate with the origin server will reference this file to obtain the public key and verify the server's identity. The private key is kept secret and secure.

## What is SSL?

SSL, more commonly called TLS, is a protocol for encrypting Internet traffic and verifying server identity. Any website with an HTTPS web address uses SSL/TLS. See [What is SSL](https://www.cloudflare.com/learning/ssl/what-is-ssl/)? and [What is TLS](https://www.cloudflare.com/learning/ssl/transport-layer-security-tls/)? to learn more.

## What information does an SSL certificate contain?

SSL certificates include:

- The [domain name](https://www.cloudflare.com/learning/dns/glossary/what-is-a-domain-name/) that the certificate was issued for
- Which person, organization, or device it was issued to
- Which certificate authority issued it
- The certificate authority's digital signature
- Associated subdomains
- Issue date of the certificate
- Expiration date of the certificate
- The public key (the private key is kept secret)

The public and private keys used for SSL are essentially long strings of characters used for encrypting and decrypting data. Data encrypted with the public key can only be decrypted with the private key, and vice versa.

#### Why do websites need an SSL certificate?

A website needs an SSL certificate in order to keep 

user data secure, 

verify ownership of the website, 

prevent attackers from creating a fake version of the site, 

and gain user trust.

**Encryption:** SSL/TLS encryption is possible because of the public-private key pairing that SSL certificates facilitate. Clients (such as web browsers) get the public key necessary to open a TLS connection from a server's SSL certificate.

**Authentication:** SSL certificates verify that a client is talking to the correct server that actually owns the domain. This helps prevent domain [spoofing](https://www.cloudflare.com/learning/ddos/glossary/ip-spoofing/) and other kinds of attacks.

**HTTPS:** Most crucially for businesses, an SSL certificate is necessary for an HTTPS web address. HTTPS is the secure form of HTTP, and HTTPS websites are websites that have their traffic encrypted by SSL/TLS.

In addition to securing user data in transit, HTTPS makes sites more trustworthy from a user's perspective. Many users won't notice the difference between an http:// and an https:// web address, but most browsers have [started tagging HTTP sites as "not secure"](https://blog.cloudflare.com/today-chrome-takes-another-step-forward-in-addressing-the-design-flaw-that-is-an-unencrypted-web/) in more noticeable ways, attempting to provide incentive for switching to HTTPS and increasing security