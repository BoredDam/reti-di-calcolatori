# Reti-di-Calcolatori

## Argomenti Trattati

### Introduzione alle reti di calcolatori
- Cos'è una rete?
- Protocollo
- Stack dei protocolli
- Header
- Topologie di rete
- PAN, LAN, MAN, WAN

### Livello Applicazione
- Introduzione
- Paradigmi Client-Server e P2P
- Socket
- IP e Porte
- Accenni a TCP e UDP
- Telnet
- FTP
- HTTP
- Proxy Server
- SMTP, IMAP e POP3
- DNS (servizio solido! ;>)
- SNMP
  
### Livello di Trasporto
- Introduzione
- Multiplexing e Demultiplexing
- UDP
- RDT e i suoi automi
- Bandwidth e calcolo del throughput
- Stop-n-wait
- Modalità pipeline, Go-back-n e Selective Repeat
- TCP
- Stati del TCP
- 3-way handshake
- "4-way" handshake
- Struttura dei segmenti TCP (headers)
- Timer e calcolo del timer
- Fast-Retransmit
- Controllo del flusso (rwnd)
- Algoritmo di Nagle
- Controllo della congestione
- AIMD, TCP Tahoe e Reno
- ECN
- TCP Fairness
  
### Livello di Rete - Panoramica
- Routing vs Forwarding
- Data Plane vs Control Plane
- Software Defined Networking vs Traditional approach
- Introduzione generale agli argomenti
- Best Effort: Internet service model

### Livello di Rete - Piano dei Dati
- Router e struttura dei router
- IPv4
- Frammentazione
- Indirizzamento IPv4, classful e CIDR
- Maschere di Rete
- Protocollo ARP
- NAT
- IPv6
- Funzionalità aggiunte e rimosse di IPv6
- Neighbour Discovery Protocol
- EUI-64
- Da IPv4 a IPv6: tecniche usate
- ICMP
- Firewall e DMZ

### Livello di Rete - Piano di Controllo
- Algoritmi di instradamento
- Centralizzati vs Decentralizzati
- Statici vs Dinamici
- Sensibili vs Insensibili al carico
- Link-State routing
- Algoritmo di Dijkstra
- Flooding
- Distance Vector
- Poisoned Reverse
- Sistemi Autonomi (AS)
- RIP e OSPF
- BGP

### Livello di Collegamento
- Introduzione
- Servizi del DLL
- Dataframing
- Codifica a tre livelli
- Codifica a blocchi (4B5B e 8B10B)
- Quantità di informazioni
- Gestione degli errori
- Error Detection e Correction
- Controllo di parità
- CRC
- Distanza di Hamming
- Protocolli di gestione per l'accesso al canale condiviso
- Suddivisione del canale (TDMA, FDMA, CDMA)
- Accesso casuale (ALOHA, Slotted ALOHA, CSMA, CSMA/CD)
- Senza collisioni (Bitmap, Binary Backward Counting, Taking turns/Token ring)
- Ethernet
- Frame Ethernet
- Cavi
- RJ-45
- Codifica di Manchester e codifica di Manchester Differenziale
- Gigabit Ethernet
- Trellis Viterbi
- Strutture Ethernet
- Hub, Bridge e Switch
- VLAN


## Importante!
Questi appunti (e materiali in generale) non si pongono come alternativa ai materiali esposti a lezione, tantomeno alla frequenza stessa.
Si invitano quindi gli studenti interessati a seguire il corso, e ad affiancare i libri di testo a questi appunti, assieme a fonti online.
Tra queste, consiglio il libro *Reti di Calcolatori e Internet: un approccio top-down*, pagine Wikipedia (molto utile per headers e protocolli) e pagine RFC (per entrare nel dettaglio).

In caso di errori importanti negli appunti, invito caldamente a mandarmi un messaggio su Telegram (o Instagram), o ad aprire una issue.

### Da aggiungere agli appunti

- Protocollo BOOTP (Boostrap Protocol)
- Protocollo RARP (Reverse ARP)
