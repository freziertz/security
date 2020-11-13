# SSL Certificate

Malengo ya kujifunza *SSL Certificate*

Baada ya kujifunza sehemu hii utakua na uwezo wa 

- kuelewa nini maana ya SSL certificate
- Utajua taarifa zilizomo kwenye SSL certificate

- Utakua na uwezo wa kueleza kwanini *SSL/ TLS ecryption* ni muhimu

- Utajifunza jinsi gani ya kupata *SSL certificate* ya bure
- Utakua na uwezo wa kueleza *SSL certificate* inafanyaje kazi

## SSL Certificate ni nini?

![SSL Certificate Secure Browsing](https://www.cloudflare.com/resources/images/slt3lc6tev37/2mkpUOPzl2jEPEERn2e57B/3b180ecab3ff7e0a5da1706434722573/ssl-certificate-secure-browsing.png)

*SSL certificate* ni kitu kile kinachofanya tovuti *( website )* kwenda kwenye ngazi ya juu kutoka *HTTP* kwenda *HTTPS* ambayo ni salama zaidi. *SSL certificate* ni data faili ambalo linakaa kwenye server halisi ya tovuti. *SSL Certificate* inawezesha encryption of data, kawaida inakua na funguo ya umma ya tovuti na utambulisho wa tovuti na taarifa zake muhimu. Kifaa kinachojaribu kuwasiliana na server asilia italisoma hilo fail ili kupata fungua ya umma na kuthibitisha utambulisho wa server. Funguo binafsi inafichwa sehemu salama

## SSL ni nini?

SSL ambayo mara nyingi inaitwa TLS, ni protokali inayofanya encryption ya mawasiliano ya mtandao yakiwa njiani na pia inafanya kazi ya kuthibitisha utambulisho wa server. Kila tovuti yenye https inatumia SSL/TLS. Angalia SSL ni nini na TLS ni nini ili kujifunza zaidi.

## Taarifa gani ambazo SSL certificate inakuwa nazo?

SSL certificate inajumisha:

- The [domain name](https://www.cloudflare.com/learning/dns/glossary/what-is-a-domain-name/) ambayo certificate imetolewa kwa ajili yake
- Certificate imetolewa kwa mtu gani, kampuni gani, kifaa gani
- imetolewa na mamlaka gani
- Saini ya kidigitali ya mamlaka iliyotoa
- domailni ndogondogo zinazohusishwa nayo
- Tarehe iliyotolewa
- Tarehe ya kuisha muda wake
- Funguo ya umma (funguo binafsi inawekwa sehemu salama ya siri kwenye)

Funguo ya umma na ya binafsi inayotumika kwenye SSL ni herufi zinazounda maneno marefu yanayotumika ku encrypting na decrepting  taarifa. taarifa zilizokuwa encrypted kwa funguo ya umma zinaweza kuwa decrepted kwa kutumia funguo binfsi na kinyume chake

#### Kwa nini tovuti zinahitaji SSL Certificate

Tovuti inahitaji SSL Certificate kwa ajili ya kuweka 

Taarifa za mtumiaji salama, 

Kuthibitisha mmiliki wa tovuti, 

Kuzuia waarifu kutengeneza tovuti mbadala ya bandia, 

na kuongeza uaminifu kwa mtumiaji.



**Encryption:** SSL/TLS encryption is possible because of the public-private key pairing that SSL certificates facilitate. Clients (such as web browsers) get the public key necessary to open a TLS connection from a server's SSL certificate.

SSL/TLS encryption inawezekana kwa sababu ya muunganiko wa funguo ya umma na ile ya binafsi ambazo zinawezeshwa na SSL cerificate.  Mtumiaji (program za mtandao ) zinapata funguo za umma zinazowezesha  kufungua mawasiliano ya TLS

**Authentication:** SSL certificates verify that a client is talking to the correct server that actually owns the domain. This helps prevent domain [spoofing](https://www.cloudflare.com/learning/ddos/glossary/ip-spoofing/) and other kinds of attacks.

**HTTPS:** Most crucially for businesses, an SSL certificate is necessary for an HTTPS web address. HTTPS is the secure form of HTTP, and HTTPS websites are websites that have their traffic encrypted by SSL/TLS.

In addition to securing user data in transit, HTTPS makes sites more trustworthy from a user's perspective. Many users won't notice the difference between an http:// and an https:// web address, but most browsers have [started tagging HTTP sites as "not secure"](https://blog.cloudflare.com/today-chrome-takes-another-step-forward-in-addressing-the-design-flaw-that-is-an-unencrypted-web/) in more noticeable ways, attempting to provide incentive for switching to HTTPS and increasing security