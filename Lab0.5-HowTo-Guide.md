# Lab 0.5 - How To Guide

## 1. Starta GNS3 och skapa ett nytt projekt

- Öppna GNS3 > New Project > Döper projektet till, Lab-0-5

## 2. Skapa en switch (lägg in Switch från Switches / Devices)

-  Dra in "Ethernet Switch" från Switches eller Devices och släpp den i arbetsytan

## 3. Lägg till två VPC-enheter

-  Lägg till två "VPC" från End Devices eller Devices och släpp dem på arbetsytan

##  4. Anslut VPC-enheterna till switchen

- Anslut VPC 1 & 2 till switchen med hjälp av "Ethernet Cable" (Add a link)

##  5. Tilldela IP-adresser till VPC-enheterna

 - VPC1: ip 192.168.1.2 255.255.255.0
 - VPC2: ip 192.168.1.3 255.255.255.0

## 6. Testa kommunikationen:
 Från VPC1, pinga VPC2: ping 192.168.1.3
---

Steg i Bilder:

2. Skapa en switch
![image](https://github.com/user-attachments/assets/79294c93-d546-41a5-8638-0a41b58e8b2f)

3.Lägg till två VPC-enheter
![image](https://github.com/user-attachments/assets/8a8ebe1a-dbd4-4d4f-a787-eca52775cc76)

4. Anslut VPC-enheterna till switchen
![image](https://github.com/user-attachments/assets/e48c6e2b-44f3-4a1c-9273-206b9418cc03)

5. Tilldela IP-adresser till VPC-enheterna
![image](https://github.com/user-attachments/assets/11324e9e-6005-4647-a9e3-6911a42c420e)
![image](https://github.com/user-attachments/assets/6f9d0f73-910e-4b06-a970-d9e672823029)

6. Testa kommunikationen:
![image](https://github.com/user-attachments/assets/3feb88ca-7c1f-49ca-82b6-7e7af576582b)

