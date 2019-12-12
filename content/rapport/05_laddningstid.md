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

Svenska friidrottsförbundets webbplats valde jag för att jag är där ofta och funderar ofta på varför den är så långsam. Svensk friidrotts veteranstatistik valde jag för att det är den långsammaste sidan som jag använder ofta. Men här kan jag ändå acceptera att den är långsam för det är mycket resultat och statistik på sidan. BTHs webbplats valde jag för att den känns så långsam men är den det i förhållande till de två andra?


Metod
-----------------------

Jag använde *Lighthouse* som undersöker webbplatsens innehåll och föreslår förbättringar för att göra sidan snabbare och mer användbar på både mobil och desktop. Jag använde *Lighthouse* med *DevTool i Google Chrome* men det kan användas från en webbplats med, se referens [1]. För att mäta laddningstider, kolla antalet förfrågningar och mängden data som skickas, så använde jag *Devtool i Google Chrome* och fliken *Network*. Jag gör tre laddningar på tre olika sidor, startsidan och två andra sidor, på webbplatsen och redovisar medeltiden här i rapporten. Vill du se rådatan, så se arket i referens [2]. I och med att jag använder *Devtool i Google Chrome* så valde jag att använda *Google Chrome* som webbläsare ocskå. Cachen var avstängd under mätningarna. Mätningarna gjordes om med CTRL-Shift-r (eller CTRL-R) så att webbläsaren inte skulle använda sina cachade objekt. *Lighthouse* var inställd på "No throttling".

För varje webbplats:  
1. Ta en snapshot (bild) på webbplats.  
2. Beskriv den upplevda känslan för sidan, snabb eller långsam   
3. Mät och utvärdera webbplatsen med *Lighthouse* (*Google PageSpeed*) för både mobil och desktop och notera resultaten. Redovisa SEO (sökmotoroptimering) i resultaten.
4. För varje sida, mät med *Devtools* flik *Network* och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida görs mätningen tre gånger och sen tas medelvärdet av mätvärdena. Jag gör samma mätning för startsidan samt två andra sidor på webbplatsen. Tiderna för de andra två sidorna visas bland rådatan.  
5. Diskutera och skriv en mening om hur webbplatsen kan förbättra sig.

Alla mätresultat noteras i rådata filen, se referens [2], och en sammanfattning noteras i tabellen för respektive webbplats under rubriken *Resultat*. Resultaten analyseras sedan under rubriken *Analys*.

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

Vad är lång laddningstid? Ja, 2-3 s är väl bra sen blir det lite för långt att vänta. Ingen av mina valda webbplatser klarar den gränsen. Jag upplever alla webbplatserna långsamma.

Det var bara BTHs webbplats som hade bra SEO enligt Lighthouse, de andra två webbplatserna får skärpa sig. En minimerad laddningstid och komprimerade bilder ger bättre användarvänlighet.

#### Svenska friidrottsförbundet

Sidan är tar för lång tid att ladda och det visar mätningarna. Däremot var Lighthousevärdena oväntat dåliga.  
Startsidan hade Lighthousevärden för mobil: performance 85, accessiblity 48, best practises 50 och SEO 55  
Förbättringsförslag mobil: massor, t ex  för lång tid till interaktion 5.6 s, för stor DOM storlek på 4021 element mot rekommenderade 1500 och kontrasten mellan bakgrund och text var inte bra.

Startsidan hade Lighthousevärden för desktop: performance 83, accessiblity 48, best practises 50 och SEO 67  
Förbättringsförslag desktop: ungefär samma som för mobil

#### Svensk friidrotts veteranstatistik

Sidan får lite bättre Lighthousevärden än jag väntade mig men laddningstiden är alldeles för lång.  
Startsidan hade Lighthousevärden för mobil: performance 20, accessiblity 63, best practises 71 och SEO 64  
Förbättringsförslag mobil: massor, t ex  för lång tid till första uppritning 8.9 s, för lång tid till interaktion 8.9 s och dokumentet använder inte viewport metatag för mobilskärmar.

Startsidan hade Lighthousevärden för desktop: performance 21, accessiblity 63, best practises 71 och SEO 78  
Förbättringsförslag desktop: ungefär samma som för mobil

#### BTHs webbplats

Sidan hade mycket bättre Lighthousevärden än jag väntade mig. Värdena var jättebra men laddningstiden är lite väl lång.  
Startsidan hade Lighthousevärden för mobil: performance 61, accessiblity 78, best practises 86 och SEO 97  
Förbättringsförslag mobil: massor, t ex  för långt speed index tid till interaktion 7,0 s,  minska svarstiden (TTFB) och möjligheter att förbättra namn och ettiketter (labels) vilket förbättrar semantiken.

Startsidan hade Lighthousevärden för desktop: performance 57, accessiblity 78, best practises 86 och SEO 100  
Förbättringsförslag desktop: ungefär samma som för mobil


Tävling
-----------------------

| Placering  | Webbplats | Laddningstid |
|------------|--------------|--------------|
| 1:a | BTHs webbplats | 6,1 s|
| 2:a | Svenska friidrottsförbundet | 6,7 s|
| 3:a | Svensk friidrotts veteranstatistik | 8,0 s|

Resultatordningen är samma som den upplevda ordningen. Grattis till BTH! Fast alla webbplatserna är ändå för långsamma.

Referenser
-----------------------

[1] Google PageSpeed Insight, https://developers.google.com/speed/pagespeed/insights/

[2] [Mätdata laddningstid](img/laddningstidData.pdf)

Övrigt
-----------------------

Författare: Marie Grahn  
Diskussionsgrupp: ingen
