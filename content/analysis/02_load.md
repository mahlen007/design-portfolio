---
Title: KMOM05 - Load
Description: Load.
Template: analys
---
# Load

Webbplatsers laddningstider
=======================

Vi ska analysera laddningstider för 3 olika webbplatser och jag har valt 3 olika kommunwebbplatser. Analysen görs med hjälp av olika webbsidor.

Urval
-----------------------
Jag har valt att studera 3 webbsajter som är kopplade till kommuner:
* www.nacka.se
* www.skovde.se
* www.stockholm.se

Jag började att välja Nackas webbplats, eftersom jag bor i Nacka. Sedan valde jag 2 andra sajter som är inom samma område. Då blev det Skövde, som jag kommer ifrån, och Stockholm, som jag har bott många år i.


Metod
-----------------------
Jag har använt mig av Google Pagespeed. Med hjälp av den webbplatsen kan få ett mått på prestanda. Jag får också reda på hur lång tid olika saker tar att ladda ner. Det går också att se hur det fungerar på en dator respektive en mobiltelefon. Vi kan också få tips på vad som är tar längst tid och vad man kan göra åt det.

Jag använder mig även av devtools i Firefox. Då kan jag få reda på laddtiden och hur mycket som laddas ner.

Resultat
-----------------------
## Nacka
![Nacka](../../portfolio/assets/img/nacka.jpg "Nacka")

Nacka mycket bra prestanda för datorer. Då ligger värdet på 96, eller snitt 98 för de 3 olika sidorna. Det tar bara 0,4 s innan man kan börja interagera med förstasidan. Det är mycket bra. Förstasidan laddar ner 1,53 Mb, vilket inte är särskilt mycket. Däremot för mobil uppkoppling är det mycket sämre. Då är det ca 7 sekunder innan man kan börja interagera med sidan.
Laddningstiden för de 3 olika sidorna är ca 1,8 sekunder.
Tipset för att sidorna ska ladda ner snabbare är att minska DOM-trädet, skjuta upp inläsning av bilder som inte visas på skärmen och minska arbetsbelastningen på modertråden.


### Skövde
![Skövde](../../portfolio/assets/img/skovde.jpg "Skövde")

Skövde har dålig prestande. Ca 70 för de olika sidorna. Det tar 2,4 s innan man kan börja interagera med förstasidan. Förstasidan som laddas ner är 7,3 Mb. Mobilt är det ännu värre då är tiden innan man kan interagera ca 16 sekunder.
Tipset för att sidorna ska ladda ner snabbare är att använda betydligt mindre bilder eller komprimerade bilder och moderna bildformat. Bara genom att minska bildstorleken så skulle sidan laddas in betydligt snabbare.

### Stockholm
![Stockholm](../../portfolio/assets/img/stockholm.jpg "Stockholm")

Stockholm har hyfsat bra prestanda för datorer. Då ligger värdet på 84 i snitt. Det tar 1,2 s innan man kan börja interagera med förstasidan. Det är bra. Förstasidan laddar ner 1,5 Mb, vilket inte är särskilt mycket. Däremot för mobil uppkoppling är det sämre. prestandan är i snitt 55. Då är det ca 4,3 sekunder innan man kan börja interagera med första sidan.
Laddningstiden för de 3 olika sidorna är ca 2,0 sekunder.
Tipset för att sidorna ska ladda ner snabbare är att se till att all text förblir synlig medan webbtecknen läses in och bilder av modernare bildformat.

Analys
-----------------------

### Förbättringsåtergärder
Det vanligaste rådet är att all text ska vara synlig innan rätt typsnitt har laddads in. Använd rätt storlek på bilderna och använd modernt bildformat.

### Rangordning av hastighet
Testets vinnare är Nacka kommuns webbplats. Nackas webbplats laddas snabbast. Den får väldigt bra prestandabetyg för datorer, men lite sämre för mobila plattformar.
Tvåa blir Stockholms webbplats. I vissa test är den lite snabbare än Nacka, men är generellt lite snabbare.
Skövdes webbplats är klart långsammats. Laddningen tar lång tid. Särskilt för mobila plattformar. De behöver anpassa bilder mycket bättre, men de behöver förbättra sin webbplats på många olika områden.

### Gräns för laddninstid

Jag tycker att en gräns kan vara ca 1 s innan man kan börja interagera med webbplatsen. Nackas webbplats klarar det med god marginal för datorer. Stockholms webbplats missar gränsen precis medan Skövdes webbplats inte ens är nära. För mobila plattformar klarar ingen webbplats den gränsen, men vi kanske är lite mer toleranta när det gäller mobila plattformar.

-----------------------
https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect&hl=sv

https://www.mozilla.org/sv-SE/firefox/new/

https://www.nacka.se/

https://skovde.se/

https://start.stockholm/

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRrRW-8QFp2KgqAEtB_BOE5T04EHLAURzyCD2TPuzW2BUI00WNDyau3v8cSpsrp-b3n3jtMyct4M8eG/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" frameborder="0" allowfullscreen></iframe>
</div>

Övrigt
-----------------------
Det är endast jag, Mattias Ahlén, som har arbetat med rapporten.
