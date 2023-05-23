
# Backendutveckling och API:er #7: CRUD och MySQL i Node.js/Express

👋 Se Linus Rudbecks föreläsning från 22 maj ✅ 

**Syftet med denna workshop:** Grunder i MySQL och hur man kan använda sig av den databasen i Node.js

*Fokus är på MySQL! Linus började även gå igenom GraphQL, men det blir mer komplett workshop på det nästa vecka. Om du känner att du redan har koll på GraphQL går det givetvis bra att använda det istället för REST*

### Innan du börjar övningen:

**Ha koll på 🤓**

* Grunder i MySQL - ha koll på termer som tabell, kolumn, rad, primärnyckel, främmande nyckel
* Operationer för CRUD i MySQL som SELECT, INSERT, UPDATE, DELETE, WHERE (och om så behövs JOIN)
* Relationer i en relationsdatabas 1:1, 1:N, N:N. 

**Installera m.m 💻**

* [WAMP](https://www.wampserver.com/en/) (Windows) eller [MAMP](https://www.mamp.info/en/downloads/) (Mac OS). Starta databasen och adminitrera genom phpMyAdmin. För url till phpMyAdmin se instruktioner för WAMP respektive MAMP.
* Du kan använda [MySQL Workbench](https://dev.mysql.com/downloads/workbench/) för att skapa tabeller, testa förfrågningar, etc. Obs! Det kan förekomma problem med att programmet krashar med Mac OS. Dock är detta verktyg för att testa MySQL - detta kan även göras i phpMyAdmin
* För att använda MySQL i Node.js finns [Node.js MySQL driver ](https://www.npmjs.com/package/mysql). Dock bygger detta bibliotek på callbacks, för enkel dokumentation [se här](https://www.w3schools.com/nodejs/nodejs_mysql.asp). Du kan också ta inspiration från [Linus promisifierade variant på detta repot](https://github.com/linus-rudbeck/graphql_mysql_demo). Här finns även en GraphQL delar, moment som tillhör nästa veckas workshop.
* För att skissa på dina tabeller och relationer [kan du använda detta verktyg](https://app.diagrams.net/).



# 👩🏽‍💻 Övning: Skapa CRUD med MySQL i REST API Node.js/Express 

**Din uppgift:**


Skapa 2-3 tabeller med relationer sinsemellan. 
Exempelvis: albums - artists, books - categories, products - categories student - courses - enrollments. Eller välj vad du tycker passar bäst. 

Specifiera tabellerna och dess kolumner i ett ritprogram (se ovan) eller för hand.
Använd dig av MySQL Workbench eller PhpMyAdmin för att intiera tabellerna. Testa att du kan skapa nya rader, samt läsa ut uppdaterade tabeller.
 	
Skapa en expressapplikation i Node.js och skapa funktioner för CRUD med Node.js MySQL driver. Skapa ett (enkelt) REST API för att testa dina endpoints i Postman.


### Redovisning:
* Du redovisar fungerande operationer för CRUD med MySQL genom ett REST API där du testar dina endpoints med Postman 

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***


### 💁 Till nästa workshop - läs på om GraphQL

[Fördjupa dig i denna länk. Den som Linus visade på senaste föreläsningen
](https://buddy.works/tutorials/what-is-graphql-and-why-facebook-felt-the-need-to-build-it)


