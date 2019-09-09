# TIRSDAG - www.simonskodebiks.com

###  What is your public IP address right now, and how did you find it?
	80.71.142.172.

	Jeg søgte den frem på whatismyip.com.

### What is your private IP address right now (do this both at home and in school), and who/what gave you that address?

	192.168.0.192. Den er tildelt af min router.

### What’s special about these address ranges?
	 10.0.0.0 – 10.255.255.255

	172.16.0.0 – 172.31.255.255 

	192.168.0.0 – 192.168.255.255

	De er alle private IP-adresser. Det stammer fra et gammelt system hvor man inddelte private IP-addresser i tre intervaller. 
	Alle IP addresser uden om intervallet er offentlige
### What’s special about this ip-address: 127.0.0.1?
	Det er Localhost, som bruges når man tilgår noget lokalt og kan bruges til at teste, i vores tilfælde, kode lokalt inden man deployer det.
### What kind of service would you expect to find on a server using these ports: 22, 23, 25, 53, 80, 443?
	SSH, portforwarding, filoverførsel, DNS, telnet, mailprotokollen, HTTP og lignende.
	What is the IP address of studypoints.dk and how did you find it?
	[157.230.21.145] jeg pingede den vha. CMD
### If you write https://studypoints.dk in your browser, how did “it” figure out that it should go to the IP address you discovered above?
	Det har den gjort vha. DNS, som ved at når jeg skriver https://studypoints.dk, så skal den pege på [157.230.21.145]
### Explain shortly the purpose of an ip-address and a port-number and why we need both
	Man bruger IP-adresser til at kunne identificere forskellige devices både lokalt og på WAM - i vores tilfælde internettet. 
	Hvert device der kan tilgå internettet eller bruges til at kommunikere med andre devices har en IP adresse(f.eks. bluetooth).
	Porte bruger man til at fortælle routeren til hvilken applikation den skal sende forespørgslen hen.
### What is your (nearest) DNS server,?
	192.168.0.1
### What is (conceptually) the DNS system and the purpose with a DNS Server?
	DNS servere hjælper med at indeksere internettet og fungere lidt som en stor adressebog, der kan omskrive IP-adresser til navne vi kan huske (f.eks. google.com)
### What is your current Gateway, and how did you find it?
	192.168.0.1 - fandt den vha. ipconfig /all i CMD
### What is the address of your current DHCP-Server, and how did you find it?
	192.168.0.1 - fandt den vha. ipconfig /all i CMD
### Explain (conceptually) about the TCP/IP-protocol stack
	TCP/IP-protokollen er et sæt instrukser, der fortæller både afsenderen og modtageren af data vha. internettet,
	hvordan dataen skal sendes. Den består af henholdsvis 4 eller 7 lag(OSI-modellen), alt afhængig af ens tolkning af protokollen.
	I 4-lagsmodellen består den af applikationslaget, transportlaget, internetlaget og det fysiske lag. 
### Explain about the HTTP Protocol (the following exercises will go much deeper into this protocol)
	HTTP Protokollen går grundlæggende ud på at man som klient kan lave 8 forskellige forespørgsler til en server.
	GET, HEAD, POST, PUT, DELETE, TRACE, OPTIONS og CONNECT.
### Explain (conceptually) how HTTP and TCP/IP are connected (what can HTTP do, and where does it fit into TCP/IP)
	HTTP benyttes på applikationsniveau og TCP/IP står for at forespørgslerne skal afsendes.


# ONSDAG
Overordnet så er alle opgaver løst, dog på nær den røde cookies opgave. Den gav jeg mig ikke i kast med. 
Jeg overså at man skulle skrive fejlkoder ned til opgaverne 1-6 og grundet tidspres her til sidst, nåede jeg ikke efter det.
###  Forklare begrebet HTTP Headers og demonstere udvalgte headers via en browsers NetVærksvindue
	Headers indeholder metadata, der skal bruges af modtageren til at afkode indholdet. 
###  Kunne læse og skrive henholdsvis Request og Response Headers på server
	Har fint styr på requestheaders, men er ikke fortrolig med responseheaders.
###  Kunne forklare om HTTP statuskoder og de forskellige ranges 2xx, 3xx, 4xx og 5xx
	Har fint styr på de forskellige typer af fejlbeskeder der kan opstå. 
###  Kunne forklare ideen med og  demonstrere hvordan HTTP tillader Sessions (state) oven på en stateles protokol
	Session bliver lagret enten server- eller clientside og bliver vedhæftet fremtidige forespørgsler i form af en cookie
	hvis det er clientside. 
### Kunne forklare ideen med og  demonstrere brug af HTTP-cookies
	Nåede ikke opgaven. 

# TORSDAG
Jeg har fået sat NginX op på min droplet, der er bundet op til mit domæne. Jeg har ikke tilføjet noget til selve hjemmesiden endnu,
men har tjekket at certifikatet er godkendt. Hvis du har lyst til at tjekke, så er URL'en Simonskodebiks.com.
