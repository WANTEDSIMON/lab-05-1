# Inlämningsuppgift 1 | Labb 0.5 & Labb 1

---

How to: 

https://github.com/WANTEDSIMON/lab-05-1/blob/main/Lab1-HowTo-Guide.md

---

https://github.com/WANTEDSIMON/lab-05-1/blob/main/Lab0.5-HowTo-Guide.md

---

## Instruktioner

Denna examination består av två olika delar. Den första delen består av tre frågor som skall besvaras med fritextsvar. Varje fråga är kopplad till ett specifikt betygskriterie, så var noga med att kontrollera ditt svar mot kriteriet innan du lämnar in.

Den andra delen handlar om att du lämnar in en labbrapport för labb 0.5 och labb 1.

---

### Del 1 (testar kriterium 1 - 3)

Betygsmål, satsar du på på G eller VG:
Svara här:

---

#### Fråga 1 (testar kriterium 1)
Beskriv minst tre vanliga hot mot nätverksmiljöer. Beskriv även vanligt förekommande sårbarheter i nätverksmiljöer samt vilka metoder som vanligtvis används för att angripa dem.

### DDos Attack - Denial-of-service attack

En attack där syftet är att överbelasta ett system genom att skicka mycket stora mängder trafik till en server eller tjänst. Handlar om att man försöker sicka väldigt många förfrågningar stor mängd data.  Det kan till exempel handla om att tusentals eller till och med miljontals automatiserade förfrågningar skickas till en webbplats/nätverk under kort tid. Syften är att försöka överbelasta servern så den blir segare vilket med för att inte längre kan hantera vanliga användares trafik, vilket gör tjänsten otillgänglig. En eller flera attacker orsakar ekonomiska förluster för företag, särskilt inom e-handel eller online-tjänster där tillgänglighet är avgörande.

Detta utförs ofta med hjälp av så kallade "botnät/zombies".  ”Har för mig även att ping kan användas, om Man det sickas ut tillräckligt ping förfrågningar. Finns verktyg/extension på Chrome Web Store, exempel öppna upp väldigt många flickar till tjänsten. ”

Effekterna av en DDoS-attack kan vara allt från försämrad prestanda till att hela tjänsten går ner. Det finns sätt att skydda sig, till exempel genom att använda lastbalanserare, trafikövervakning, brandväggar.

### Phishing

Andra hotet jag tänker mig är Phishing attacker. Phishing är en form av "social engineering". Där någon försöker lura dig som användare/arbetare på företag. Exempel kan vara att man har en mailadress som är lik ett kundföretag kanske. Där man använder sig av någon annan bokstav som liknar deras originaladress. På mejlet man får kan det vara länk man trycker på som laddar ner virus, eller program som skulle kunna tillhöra kundens förfrågan ” trojan horse”. Virus i sin tur kan leda till ransomware attack om det blir riktigt alvarligt. Exempel om användaren som blev drabbat har administration rättigheter i ett system. De kan även få tag i uppgifter genom att skapa upp liknande hemsidor där då användaren skriver upp deras inloggningsuppgifter, men vet inte om att i själva verket skriver de in på en förfalskad sida.

Phishing är ett av de vanligaste hoten eftersom det riktar sig mot människors beteende och inte mot tekniska brister. Det kräver alltså inte mycket teknisk kunskap från angriparen, bara en förmåga att lura användare. Det kan ske via e-post, sms (så kallad smishing), telefonsamtal (vishing) eller via sociala medier.

Skydd mot phishing handlar mycket om utbildning och medvetenhet. Användare bör lära sig att vara kritiska till länkar och avsändare, samt använda tvåfaktorsautentisering för extra skydd. Organisationer kan också använda e-postfilter och säkerhetsverktyg som känner igen och blockerar phishingförsök.


### SQL injection

Hot nummer tre. Tänkte jag att företag använder databaser för hantering av data. Och att det bör vara en del i deras nätverk. Även om det inte är själva nätverket så tänker jag att det bygger på hårdvara som man koplar in i sitt nätverk. 

Så jag var intreserad i "SQL injection", är en av de vanliga webb hacking metoderna. Man plaserar in malicious code skadlig kod till SQL statements via Inmatning av webbsida. "SQL in Web Pages" Brukar hända när du frågar en användare för inmatning av användare nam/userid och istället för ett namn/id ger användaren dig en SQL-sats som du omedvetet kommer att köra på din databas. "Målet är att manipulera databasen genom att "injicera" (lägga till) skadlig SQL-kod i ett formulärfält, t.ex. ett inloggningsformulär eller ett sökfält. Om systemet inte validerar användarens inmatning ordentligt, kan denna kod köras av servern och ge angriparen tillgång till känslig information."

En attak som denna kan leda till att angriparen får åtkomst till alla användardata i databasen, till exempel namn, e-postadresser, lösenord eller till och med finansiell information. I värsta fall kan de också radera eller ändra innehållet i databasen.

Skydd mot SQL-injection inkluderar att alltid använda parametriserade SQL-frågor, validera all inmatning, samt att använda moderna ramverk och bibliotek som automatiskt hanterar dessa risker.


"Vanliga sårbarheter och metoder för angrepp"

Exempel: Ouppdaterad programvara, svaga lösenord, Bristande åtkomstkontroller.

- Svaga lösenord: Att användaren använder samma lösen på flera ställen. Lösenord som är lätt att lista ut. Använder för få bokstäver samt tecken. Angreppsmetoder - "Brute force-attacker"

- Ouppdaterad programvara: inte använder senast updatering, vilken kan leda till säkerhetsbrister som någon listat ut hur man kommer in. Angreppsmetoder - "Skadlig kod (malware)"


---

#### Fråga 2 (testar kriterium 2)
Förklara vilka typer av hårdvara som vanligtvis finns i en professionell nätverkstopologi samt förklara deras roll i nätverket. Beskriv även hur man konfigurerar dessa. Slutligen beskriver du även hur man vanligtvis installerar ett operativsystem för nätverkshantering.

Router: En router (eller "ruttare" på svenska) fungerar som en trafikledare mellan olika nätverk, till exempel mellan ett lokalt nätverk (LAN) och internet. Routern har en IP-adress på det lokala nätverket och hanterar adressering, NAT (Network Address Translation) och brandväggsregler. Den avgör vilken väg datan ska ta för att nå rätt mottagare, oavsett om det är en enhet inom det lokala nätverket eller utanför.

Vanlig konfigurering görs via webbläsare, t.ex. genom att skriva in IP-adressen 192.168.1.1

Switch: Är en nätverkskomponent som kopplar ihop flera enheter inom ett LAN, t.ex. datorer, skrivare och servrar. Till skillnad från en enkel hub, är en switch "smart" – den lär sig vilken MAC-adress som är kopplad till varje port och skickar endast datatrafik till rätt mottagare, vilket förbättrar prestanda och säkerhet.

nätversk kabbel: Oftast av typen Ethernet (t.ex. Cat5e, Cat6), används för att koppla ihop routrar, switches och enheter i nätverket. Kabeln möjliggör snabb och stabil dataöverföring, ofta upp till 1 Gbps eller mer. I professionella nätverk används oftast Cat6 eller Cat6a för att klara högre hastigheter och längre avstånd utan störningar.

#### Fråga 3 (testar kriterium 3)
Beskriv hur man bäst genomför en felsökning och hur man övervakar trafiken på ett nätverk. Redogör även för hur verktyget Wireshark används för detta ändamål samt vilka de viktigaste funktionerna i Wireshark är.

Felsökning och trafikövervakning i nätverk – med fokus på Wireshark:
Att kunna felsöka och övervaka ett nätverk på ett systematiskt sätt är avgörande för att kunna upprätthålla en säker och stabil IT-miljö. När nätverket inte fungerar som det ska, kan orsakerna vara många: felaktig konfiguration, trasig hårdvara, överbelastning eller till och med säkerhetsintrång. För att identifiera problemet använder man både logiskt tänkande och specialiserade verktyg – där Wireshark är ett av de mest kraftfulla.

---

### Del 2 (testar kriterium 5 - 10)
I denna del skall du skriva en labbrapport som baseras på Labb 0.5 och Labb 1 som du genomförde tidigare i kursen. Labbrapporten skall ha följande struktur:

---

#### Labb 0.5:

- Vilka steg var mest utmanande och varför?

1. Installationen av Gns3,
Uppkom problem när jag satte med Gns/Ubunto. Exempel stav fel på komandon, samt blandat med vilka steg som krävdes för instalation, maskingen blev krupt. 
  
- Hur löste du de problem som uppstod under konfigureringen?

1.1 Exempel stav fel på komandon:
Insåg att jag glömt numer 3 vid instalation av Gns3.

1.2 Samt blandat med vilka steg som krävdes för instalation:
Blev tydligare med att se video för installationen, "Komma igång i kursen, installation" kunde ha strukturerats upp lite tydligare. Eftersom stegen blev enkalare att uppfata under video. 

1.3 Maskingen blev krupt: Blev tvungen att instalera om maskinen, eftresom "Vad jag uppfattade" hårdisken för ubuntu maskinen blev krupt. 



- Vilken ny kunskap har du förvärvat genom denna uppgift? Var detaljerad och beskriv implementationsdetaljer och de steg ni var tvungna att ta för att fullfölja laborationen.

Kanske att jag tidigare är van med packet tracer. Så detta var en ny miljö att arbeta utifrån. har väll även suttit med rikdiga hårdvara och vet kosntnaden som förekommer och att man behöver ha plats för switchar är rätt klumpiga och bökiga (24 port).


---

#### Labb 1:

- Vilka steg var mest utmanande och varför?

1. Stegen hur man gör allt var inte lika simpel som lab 0.5.

2. Även konfigurering av NAT nod. Blev lite svårt hur man skulle structurera upp kommandon.

3. Även att skriva vilka portar som användes. Blev bakofram men fungerar för att komma ihog kopplingen när allt följer samma strukture :),

- Hur löste du de problem som uppstod under konfigureringen?

1. Valde att structurera upp strukturen för vare steg i Laben, för att tydligöra vad som behövdes samt kommandon.

3. Vale att gå vidare emd det jag skrev....

3. Uppfatade senare man kunde trycka på en knapp i Gns somgör det automatisk.


- Vilken ny kunskap har du förvärvat genom denna uppgift? Var detaljerad och beskriv implementationsdetaljer och de steg ni var tvungna att ta för att fullfölja laborationen.
