# Lab1-HowTo-Guide

## 1. Starta GNS3 och skapa ett nytt projekt

- Öppna GNS3 > New Project > Döper projektet till, Lab-1

## 2. Ladda ner IOS-avbildningen ”vios-adventerprisek9-m.spa.159-3.m2.qcow2” för att använda med din Cisco IOS-router. 

- För att kunna Lägg till en Cisco IOS router via New Template > Routers > Cisco IOSv


## 3. Skapa det första privata nätverket med IP-adressområdet 10.0.0.x/24.
 - Inom detta nätverk, lägg till en switch och minst två virtuella PC-enheter.

- PC1: ip 10.0.0.10 255.255.255.0 10.0.0.1
- PC2: ip 10.0.0.20 255.255.255.0 10.0.0.1
 
## 4. Skapa det andra privata nätverket med IP-adressområdet 192.168.1.x/24.
- Nätverk två innehåller en switch och minst två virtuella PC-enheter.

- PC3: ip 192.168.1.10 255.255.255.0 192.168.1.1
- PC4: ip 192.168.1.20 255.255.255.0 192.168.1.1

## 5. Koppla ihop routern med switcharna

---

Steg i Bilder:

2. Lägg till  Cisco IOS router
<img src="img/img1.1.png">

3. Säter ihop nätverket ett
<img src="img/img1.2.png">

PC1:
<br>
<img src="img/img1.3.png">

PC2:
<br>
<img src="img/img1.4.png">

4. Säter ihop nätverket två
<img src="img/img1.5.png">

PC3:
<br>
<img src="img/img1.6.png">

PC4:
<img src="img/img1.7.png">

5. Koppla ihop Nätverken
<img src="img/img1.8.png">
