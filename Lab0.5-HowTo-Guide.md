# Lab 0.5 - How To Guide

## 1. Starta GNS3 och skapa ett nytt projekt

- Öppna GNS3 > New Project > Döper projektet till, Lab-0-5

## 2. Skapa första privata nätverket (10.0.0.0/24)

- Dra in en switch från vänstra menyn > Dra in 2 st VPCS (Virtual PC).
- Koppla båda PC till switchen > Tilldela IP-adresser: PC1: 10.0.0.10/24 - PC2: 10.0.0.20/24

Gateway (senare på routern): 10.0.0.1

VPCS-konfiguration (högerklick > Console):

```bash
ip 10.0.0.10 255.255.255.0 10.0.0.1
```
(sedan samma för andra PC med annan IP)
