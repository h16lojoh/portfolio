---
Title: Colors
Description: Redovisning av load.
Template: analysis_paper

# hidden: true
---

<!-- 

Välj ut 3 webbplatser som skall analyseras, berätta hur du gjorde urvalet.

Beskriv vilka verktyg du använde och hur du utförde arbetet för att samla in dina mätvärden. Det blir en kort beskrivning av din metod.

Skapa ett Excel-ark, till exempel Google Kalkylark, för att spara dina mätningar i. För allt du nu skall mäta, dokumentera det i Excel-arket. Länka till ditt Excel-ark så man ser rådatan.

För varje webbplats, gör följande:

Ta en snapshot (bild) på webbplatsen.
Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.
För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.
Diskutera och skriv en mening om hur webbplatsen kan förbättra sig.
Sammanfatta ditt resultat i en analys och skriv om vilka de vanligaste förbättringsåtgärderna verkar vara för ditt urval av webbplatser.

Rangordna dina webbplatser baserat på deras mätvärden och utse en vinnare i testet och kommentera resultatet.

Bestäm en gräns för absolut laddningstid som du själv uppfattar som snabb eller långsam webbplats. Skriv en mening om hur ditt urval av webbplatser klarar ditt gränsvärde och hur du upplever webbplatsernas snabbhet, rent generellt, i ditt urval.

I slutet av rapporten skriver du ett eget stycke med namnen på dina gruppmedlemmar.



-->

Webben och laddningstider
=======================

Bakgrund
-----------------------
I denna rapport kommer en analys över laddningstider på webbsidor dokumenteras och jämföras. Dokumentationen kommer att rangordna webbplatser som snabb, medel och långsam utifrån förbestämda kriterier över laddningstider. Utifrån resultatet kommer sedan en sammanfattning presenteras med den snabbaste webbplatsen och även lösningar som webbplatserna kan göra för att öka hastigheten. 

Med sidhastighet menas hastigheten för ett urval av sidor på en webbplats. Hastigheten kan beskrivas som "sidladdningstid", alltså den tid det tar att visa allt innehållet på en viss sida, eller "tid till första byte", hur lång tid det tar för din webbläsare att ta emot den första byten (Moz, 2020).

Enligt Google (2020) är sidhastighet viktigt för användarupplevelsen. Studier visar att användare vill kunna hitta svar på sina frågor så snabbt som möjligt när de söker på webben. Det är även så att indexeringen en webbplats får i googles sökresultat påverkas av hur snabb en webbplats är. En låg sidhastighet leder till att sökmotorer kan genomsöka färre sidor och detta påverka indexering negativt (Moz, 2020). Artikeln 'why speed matter' har en långsam sidladdning negativa inverkan på affärsmål. Till exempel fann BBC att de förlorade 10% av användarna för varje sekund som deras webbplats tog för att ladda.



Urval
-----------------------
<!-- 
Välj ut 3 webbplatser som skall analyseras, berätta hur du gjorde urvalet. För varje webbplats, gör följande: Välj ut tre sidor.
-->

De utvalda webbplatserna för analysen ingår i kategorin "köp och sälj annonsering".  
Sidorna som kommer att ingå i undersökningen är: Första sidan, kategorisidan för fordon och kontakt-sidan. 

Webbsplatserna och respektive sida som kommer att ingå i undersökningen är: 

<b>Blocket:</b>
<ul>
   <li>
      <a href="https://www.blocket.se">Länk: Första sidan</a>
   </li>
   <li>
      <a href="https://www.blocket.se/annonser/hela_sverige/fordon?cg=1000/">Länk: Fordon</a>
   </li>
   <li>
      <a href="https://blocket.zendesk.com/hc/sv">Länk: Kontakt</a>
   </li>
</ul>


<b>Tradera:</b>
<ul>
   <li>
      <a href="https://www.tradera.com/">Länk: Första sidan</a>
   </li>
   <li>
      <a href="https://www.tradera.com/fordon-batar-delar-10">Länk: Fordon</a>
   </li>
   <li>
      <a href="http://info.tradera.com/en/#humany-vanliga-fragor-och-svar=/contact">Länk: Kontakt</a>
   </li>
</ul>

<b>Cityboard:</b> 
<ul>
   <li>
      <a href="https://citiboard.se/">Länk: Första sidan</a>
   </li>
   <li>
      <a href="https://citiboard.se/fordon">Länk: Fordon</a>
   </li>
   <li>
      <a href="https://citiboard.se/contact">Länk: Kontakt</a>
   </li>
</ul>

Dessa webbplatser valdes främst för att undersöka webbsidor som innehåller många bilder. Genom att undersöka webbplatser inom samma kategori kan likheter och skillnader i laddningstider bland konkurrenter undersökas. Slutsatser kan dras utifrån dessa skillnader.

Metod
-----------------------

<!-- 
Beskriv vilka verktyg du använde och hur du utförde arbetet för att samla in dina mätvärden. 

Skapa ett Excel-ark-Google Kalkylark

Mät på både Mobile och Desktop. 
För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.
-->

För att ta reda på webbplatsers laddningstider kommer tre olika webbplatser undersökas. 
Undersökningen kommer göras på tre utvalda sidor för varje webbplats med hjälp av Google Pagespeed. Både mobil och desktop variant av webbplatserna kommer att undersökas. För varje sida kommer devtools flik networks användas för att notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. 
Mätningarna kommer att utföras totalt tre gånger och snittet av dessa kommer att respresentera resultatet för varje enskild sida. Ett Excel-ark används för att dokumentera resultaten av mätningarna.

Webbplatserna kommer få betygen: snabb, medel eller långsam. För att få betyget snabb måste snittet för google pagespeed resultat ligga mellan 90–100, för att få medel ska snittet ligga mellan 50–89 och långsam mellan 0–49.

Resultat
-----------------------

<h3>Google PageSpeed</h3>
<img src="../assets/img/googlepagespeed.PNG" alt="Screenshot av google pagespeed resultat" width="100%" height="auto">

<b>Första sida</b>
Blockets förstasida fick enligt Google pageSpeed resultatet 25 i medel för sidladdning, Tradera fick 12 och Cityboard fick 16.

<b>Kategori</b>
Blockets kategorisida fick 24 i medel, tradera fick 11 och cityboard fick 15.

<b>Kontakt</b>
Blockets kontaktsida fick 27 i medel, Tradera mätte 43 och cityboard 16.


<h3>Devtool Network</h3>
<img src="../assets/img/devtool.PNG" alt="Screenshot av devtool resultaten" width="100%" height="auto">

<b>Första sida</b>
Blocket fick i medel 4,0 sekunder i laddningstid, tradera fick 6,27 och cityboard fick 3,59. Blocket laddade in 4,4 MB resurser, tradera 6,5 och cityboard 4,7. Blocketssidstorlek var 63,9 KB, traderas var 16,6 KB och cityboards 29,5 KB.

<b>Kategori</b>
Blocket fick i medel 3,59 sekunder i laddningstid, tradera fick 5,92 och cityboard fick 2,24. Blocket laddade in 3,8 MB resurser, tradera 5,9 och cityboard 5,7. Blocketssidstorlek var 55,8 KB traderas var 29,4 och cityboards 31,8.

<b>Kontakt</b>
Blocket fick i medel 2,83 sekunder i laddningstid, tradera fick 2,23 och cityboard fick 1,56. Blocket laddade in 5,5 (MB) resurser, tradera 3,8 (MB) och cityboard 1,3 (MB). Blocketssidstorlek var 549,7 (B), traderas var 254 (B) och cityboards 14,1 (KB).


Analys
-----------------------
Webbplatserna skiljer sig från varandra i storlek så det är inte så förvånande att resultaten skiljer sig från varandra. 

Vid Google PageSpeed fick två av blockets sidor, första sida och kategorisida, bäst resultat jämfört med övriga. Vid första sidan kan detta bero på att både Tradera och cityboards förstasidor innehåller mycket bilder och länkar såsom utvalda bilder från olika kategorier till exempel 'senaste annonser' och liknande. Blocket innehåller däremot begränsat med länkar och bilder, där finns en sökruta, kategorimeny samt några bilder och länkar till 'Hitta bättre', 'Aktuellt på blocket' och 'Mer blocket', däremot finns inga kategoribilder. Traderas kontaktsida fick det högsta resultatet av alla mätta sidor, hela 43 i medel. Detta kan bero på att denna sidor innehåller noll antal bilder. Sidan innehåller enbart en sökruta och länkar till underkategorier kopplade till kontaktinformation. <b>Blockets webbplats</b> är vinnare när det kommer till Google PageSpeed då två av sidorna fick högst resultat. <b>Traderas kontakt-sida</b> är vinnare när det kommer till mätta sidor (ej webbplatsen i helhet).

Vid Devtools network laddade alla cityboards sidor in snabbast (2.67, 2.24, 1.56). Det kan eventuellt bero på att cityboard egentligen är skapad för att användas i mobilen, möjligtvis är innehållet såsom bilder mobilanpassade även när sidorna besöks på webben. Cityboard är vinnre när det kommer till laddningstid mätt med devtools.

Med de förbästämda värdena för snabb, medel och långsam är däremot alla webbplatserna klassade som långsamma. 

Moz (2020) har listat några tips på hur det går att öka sidhastighet. 
Några av dessa är:

<b>Aktivera komprimering</b>, som innebär att till exempel komprimera CSS-, HTML- och JavaScript-filer så att de inte överstiger 150 byte.
Filer såsom CSS, JavaScript och HTML kan även optimeras genom att ta bort mellanslag, oanvänd-kod och andra onödiga tecken. 

<b>Undvik onödiga omdirigeringar</b>, eftersom detta leder till att användaren får vänta ytterligare en gång när HTTP-begäran-svar-cykeln ska slutföras.

<b>Ta bort renderingsblockerande JavaScript</b>, eftersom webbläsare måste bygga ett DOM-träd genom att analysera HTML innan de kan göra en sida. Om ett script dyker upp i denna process måste scriptet köras innan processen kan fortsätta.

<b>Utnyttja cachning i webbläsaren</b> så att så mycket information som möjligt sparas. Då behöver inte webbläsaren ladda om hela sidan varje gång en användare återvänder till en sida.

<b>Optimera bilder</b> så att de inte är större än vad de behöver vara, att de har rätt filformat ​​och att de är komprimerade för webben.




<img src="../assets/img/blocket_bild.PNG" alt="Screenshot av blocket hemsida" width="100%" height="auto">
Blocket kategorisida
<img src="../assets/img/cityboard_bild.PNG" alt="Screenshot av cityboard hemsida" width="100%" height="auto">
citybord kategorisida
<img src="../assets/img/tradera_bild.PNG" alt="Screenshot av blocket hemsida" width="100%" height="auto">
tradera kategorisida

Referenser
-----------------------

Moz. (2020). Page speed. Hämtad 2020-12-03 från https://moz.com/learn/seo/page-speed
Google. (2020). Using page speed in mobile search. Hämtad 2020-12-03 från https://developers.google.com/search/blog/2018/01/using-page-speed-in-mobile-search
Web. (2020). Why speed matters. Hämtad 2020-12-03 från https://web.dev/why-speed-matters/

Övrigt
-----------------------
Louise Johansson
