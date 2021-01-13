---
Title: Projekt
Description: Redovisning av design-projekt.
Template: kmom

# hidden: true
---

<section>
   <h2>Kmom10</h2>
   <h3>1.1 För varje krav du implementerat, dvs 1-6, skriver du ett textstycke om ca 5-10 meningar där du beskriver vad du gjort och hur du tänkt.</h3>

   <h4>Kund 3</h4>

   <p>
   För webbplatsen valde jag att skapa en portfolio till kund nummer 3. Jag valde att kopiera grunden som byggts för me/portfolio. Jag valde att göra på detta sättet eftersom även me/portfolion var en portfolio-sida och jag visste att det skulle finnas en del likheter mellan dessa, och då återanvändbara element.
   <br>
   <br>
   Webbplatsen består utav tre sidor, en förstasida, en about-sida och en galleri-sida. Första sidan innehåller en sektion där kunden presenterar lite av sina kunskaper inom webbdesign, webbutveckling och webbprogrammering. Första sidan presenterar även några utvalda galleri-bilder. Galleri sidan presenterar projekt som kunden jobbar/har jobbat med. About sidan presenterar kunden och förmedlar vad för syfte webbplatsen har, att presentera/marknadsföra Bew Gorp. 
   <br>
   <br>
   På samtliga sidor används en flash/hero-bild, bilden är samma på alla sidor och föreställer kund 3. I navigationen finns kundens logga som föreställer initialerna B och G, loggan används även som favicon. Navigationen är responsiv och blir en hamburgarmeny vid mobil. Footern innehåller kontaktinformation. 
   <br>
   <br>
   Innehållet anser jag vara relevant för kunden. Webbplatsen presenterar kundens kunskaper, tidigare arbeten/verk, kontaktuppgifter och personlig presentation. På about-sidan finns den personliga presentationen av kunden. Webbplatsen är bildrik och Cimage används för att få rätt storlek på bilderna. De flesta bilderna återfinns på galleri-sidan som ämnar att visa upp tidigare arbeten/verk som kunden skapa. På första sidan visar kunden upp några utvalda arbeten som anses vara de mest se-värda för de som besöker webbplatsen.
   </p>

   <h4>Tema</h4>
   <p>
   Webbplatsens tema heter 'awesome'. Den bygger på temat från tidigare uppgifter. Temat är anpassat till kund nummer 3.
   Temat använder sig utav SASS. Koden är uppdelad i flera moduler och variabler används för återkommande färger och även style för border. Färgerna och typsnitten är valda så att de ska passa kundens önskemål. 
   <br>
   <br>
   Jag har medvetet använt mig utav designelement/principer för att uppnå en god design som passar kunden.
   På about-sidan finnas en länk till en dold sida som innehåller dokumentation över färger, typsnitt och designprinciper. Där diskuteras designvalen mer utförligt.
   </p>

   <h4>Tema alternativt</h4>

   <p>
   Webbplatsen använder även ett ytterligare tema som går att aktivera ifrån samtliga sidors footer. Temat skiljer sig från grundtema i utseende. Temat använder andra färger, typsnitt och stuktur. Temat är responsivt och uppnår 100% tillgänglighet.
   Bilder är även här anpassade med cimage. Mer om temat står på den dolda sidan.
   </p>

   <h4>Responsivitet och Tillgänglighet</h4>

   <p>
   Webbplatsen använder sig utav grid för att uppnå responsivitet. Bilder är anpassade med cimage och < image >/srcset för att även de ska vara optimerade för en responsiv design. Samtliga sidor uppnår 100% i “accessibility” enligt Lighthouse. 
   </p>

   <h3>1.2 Skriv ett allmänt stycke om hur projektet gick att genomföra. Problem/lösningar/strul/enkelt/svårt/snabbt/lång tid, etc. Var projektet lätt eller svårt? Tog det lång tid? Vad var svårt och vad gick lätt? Var det ett bra och rimligt projekt för denna kursen?</h3>

   <p>
   De tidigare uppgifterna i kursen har fungerat som en bra grund för utförandet av projektet. Det var relativt enkelt att komma igång med Pico då vi har gått igenom allt som krävs i tidigare kurs-moment. Det första steget jag gjorde var att visualisera en grafisk profil för min kund. Jag valde färger och typsnitt och jag klargjorde vad webbplatsens mål och syfte var. Jag började sedan med att skapa grunden för webbplatsen. Alla sidor, bilder som skulle användas och varje sidas sass- och twig-fil. Sedan började jag strukturera upp varje sidas html och sedan all css. Projektet tog ungefär lika långt tid som var förväntat enligt uppgiftsbeskrivningen. Det var ett riktigt roligt projekt. Projektet var lärorikt och det fanns tillräckligt med fasta mål samt "fria händer" moment.
   </p>

   <h3>1.3 Tankar om kursen och vad du anser om materialet och handledningen (ca 5-10 meningar). Feedback till lärarna och förslag till eventuella förbättringar. Är du nöjd/missnöjd? Kommer du att rekommendera kursen till dina vänner/kollegor? På en skala 1-10, vilket betyg ger du kursen?</h3>

   <p>
   Jag har varit väldigt nöjd med kursen. Det har som sagt varit väldigt lärorikt. Jag har kunskaper av HTML, CSS, JS och CMS sedan tidigare men Pico var nytt för mig. Det har varit en väldigt bra struktur på kursens upplägg och varje inlämningsuppgift har haft ett klart syfte som har kunnat uppnåtts med hjälp av studimaterial. 
   <br>
   <br>
   Det jag hade önskat mera är vägledning vad gäller optimala lösningar för att undvika att "hårdkoda" vissa element. Tex när det kommer till report-sidan och gallery-sida, min lösning blev att lägga in bilder i meta och sedan loopa igenom innehållet. Vid projektet ville jag ha flera ingånglänkar till övriga sidor, en i headern för 'about me' och en 'see more'-länk till galleri-sidan. Det var lite klurigt att komma på ett bra sätt att utforma dessa genom att loopa eller filtrera. Länken till den gömda sidan som diskuterar färger, typsnitt och designval blev desvärre hårdkodad då jag inte kom på en bättre lösning. Jag hade gärna haft en grundlig genomgång över detta tidigare i kursen. Vi fick dock ett bra exempel över detta vid bild-uppgiften, det var uppskattat!
   <br>
   <br>
   Jag skulle absolut rekomendera kursen och betyget är 10. Det var nog allt jag hade tänk att den skulle innehålla som den innehöll. Det var roligt att se att begreppet tillgänglighet togs upp och att vi fick lära oss att använda lighthouse. Pico CMS tycker jag även var ett bra CMS som ingång! Det var enkelt att förstå och kursupplägget gjorde att det inte blev för mycket på en och samma gång.
   </p>    
</section>

