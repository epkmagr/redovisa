Utvärdering av laddningstider
=======================

Uppgiften handlar om att välja ut tre olika webbplatser och testa dem för att mäta hur snabbt de laddas och om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.

Urval
-----------------------

Jag utgick ifrån webbplatser som jag gärna besöker och som jag dessutom tycker är långsamma.

Jag valde följande webbplatser:  
1. [Svenska friidrottsförbundet:](http://www.friidrott.se/)  
2. [Svensk friidrotts veteranstatistik:](http://www.friidrott.info/veteran/)  
3. [BTHs webbplats:](https://www.bth.se)  

Svenska friidrottsförbundets webbplats valde jag för att jag är där ofta och hittar där all information jag behöver om friidrott, tävlingar och resultat. Svensk friidrotts veteranstatistik valde jag för att jag är nyfiken på hur den är uppbyggd och dessutom är det en sida där jag kollar hur mina tävlingsresultat ligger till jämfört med andras. Båda dessa webbplatser är jag ofta på och varenda gång så tänker jag på hur långsamma de är. BTHs webbplats valde jag för att den känns så långsam men är den det i förhållande till de två andra?


Metod
-----------------------

Jag använde *Lighthouse* som undersöker webbplatsens innehåll och föreslår förbättringar för att göra sidan snabbare och mer användbar på både mobil och desktop. Jag använde *Lighthouse* från DevTool i Google Chrome men det kan användas från sin webbplats med, se ref [1]. Jag använde Devtool i Google Chrome, under Networks så kollade jag laddtiden och om cache används eller inte. Jag gör tre laddningar på tre olika sidor på webbplatsen och redovisar medeltiden här i rapporten. Vill du se rådatan, så se arket i referens [2]. I och med att jag använder Devtool i Google Chrome så valde jag att använde Google Chrome som webbläsare ocskå. Cachen var avstängd under mätningarna. Mätningarna gjordes om med CTRL-Shift-r (eller CTRL-R). *Lighthouse* var inställd på "No throttling".

För varje webbplats:  
1. Ta en snapshot (bild) på webbplats.  
2. Beskriv den upplevda känslan för sidan, snabb eller långsam  
3. Undersök med *Lighthouse*, notera betyget för både mobil och desktop
4. För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida görs mätningen tre gånger och ta medelvärdet av mätvärdena. Jag gör samma mätning för startsidan samt två andra sidor på webbplatsen. Tiderna för de andra två sidorna visas bland rådatan.
5. Diskutera och skriv en mening om hur webbplatsen kan förbättra sig.

Alla resultat noteras i tabellen för respektive webbplats under rubriken *Resultat*. Resultaten analyseras sen under rubriken *Analys*.

Resultat
-----------------------

Här kommer resultaten från min studie av de tre webbplatserna Svenska friidrottsförbundet, Svensk friidrotts veteranstatistik och BTHs webbplats.

### Svenska friidrottsförbundet

Detta är svenska friidrottsförbundets webbplats med massor av information om friidrottsförbundet, friidrott, tävlingar, resultat, regler, utbildning, media, antidoping etc.

#### Snapshot

[FIGURE src=image/friidrottSe.png class="right" caption="Svenska friidrottsförbundets startsida."]  

#### Resultat

| Upplevd känsla  | Betyg Lighthouse mobil | Betyg Lighthouse desktop | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns ganska långsam | 55/100 | 67/100 | 6,7 s |


### Svensk friidrotts veteranstatistik

Den här webbplatsen är ideell och innehåller veteranresultat genom åren i friidrott. Veteran inom friidrotten är du från och med det år du fyller 35 år. Webbplatsen innehåller årsbästalistor, veteranrekord och bästa resultat genom tiderna.

#### Snapshot

[FIGURE src=image/veteranStatistik.png class="right" caption="Startsida för svensk veteranstatistik i friidrott."]

#### Resultat

| Upplevd känsla  | Betyg Lighthouse mobil | Betyg Lighthouse desktop | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns mycket långsam | 64/100 | 78/100 | 8,0 s |


### BTHs webbplats

Den här webbplatsen presenterar Blekinge Tekniska Högskola, BTH, för studenter, forskare och anställda på skolan. Allt som du som student och anställd kan tänkas behöva ska finnas här.

#### Snapshot

[FIGURE src=image/bth.png class="right" caption="Startsida för Blekinge Tekniska Högskola."]

#### Resultat

| Upplevd känsla  | Betyg Lighthouse mobil | Betyg Lighthouse desktop | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns långsam | 97/100 | 100/100 | 6,1 s |


Analys
-----------------------

Vad är lång laddningstid? Ja, 2-3 s är väl bra sen blir det lite för långt att vänta. Det var bara BTHs webbplats som hade bra SEO enligt Lighthouse, de andra två webbplatserna får skärpa sig.

#### Svenska friidrottsförbundet

Sidan är tar för lång tid att ladda och det visar mätningarna. Däremot var Lighthousevärdena oväntat dåliga.
Startsidan hade Lighthouse värden för mobil: performance 85, accessiblity 48, best practises 50 och SEO 55  
Förbättringsförslag mobil: massor, t ex  för lång tid till interaktion 5.6 s, för stor DOM storlek på 4021 element mot rekommenderade 1500 och kontrasten mellan bakgrund och text var inte bra.

Startsidan hade Lighthouse värden för desktop: performance 83, accessiblity 48, best practises 50 och SEO 67  
Förbättringsförslag desktop: ungefär samma som för mobil

#### Svensk friidrotts veteranstatistik

Sidan får lite bättre Lighthousevärden än jag väntade mig och laddningstiden är alldeles för lång.
Startsidan hade Lighthouse värden för mobil: performance 20, accessiblity 63, best practises 71 och SEO 64  
Förbättringsförslag mobil: massor, t ex  för lång tid till första uppritning 8.9 s, för lång tid till interaktion 8.9 s och dokumentet använder inte viewport metatag för mobilskärmar.

Startsidan hade Lighthouse värden för desktop: performance 21, accessiblity 63, best practises 71 och SEO 78  
Förbättringsförslag desktop: ungefär samma som för mobil

#### BTHs webbplats

Sidan hade mycket bättre Lighthousevärden än jag väntade mig. Laddningstiden är lite väl lång.  
Startsidan hade Lighthouse värden för mobil: performance 61, accessiblity 78, best practises 86 och SEO 97  
Förbättringsförslag mobil: massor, t ex  för långt speed index tid till interaktion 7,0 s,  minska svarstiden (TTFB) och möjligheter att förbättra namn och ettiketter (labels) vilket förbättrar semantiken.

Startsidan hade Lighthouse värden för desktop: performance 57, accessiblity 78, best practises 86 och SEO 100  
Förbättringsförslag desktop: ungefär samma som för mobil


Tävling
-----------------------

| Placering  | Webbplats | Laddningstid |
|------------|--------------|--------------|
| 1:a | BTHs webbplats | 6,1 s|
| 2:a | Svenska friidrottsförbundet | 6,7 s|
| 3:a | Svensk friidrotts veteranstatistik | 8,0 s|

Resultatordningen är samma som den upplevda ordningen. Fast alla webbplatserna är för långsamma.

Referenser
-----------------------

[1] Google PageSpeed Insight, https://developers.google.com/speed/pagespeed/insights/

[2] [Mätdata laddningstid](img/laddningstidData.pdf)

Övrigt
-----------------------

Författare: Marie Grahn  
Diskussionsgrupp: ingen
