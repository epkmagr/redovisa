Några matbutikers webbdesign
=======================

Företaget *Sök Under* har bett mig att göra en analys av aktuell webbplatsdesign och trender för några matbutiker. De är intresserade av följande kriterier:

<b>Prestandamätningar:</b>  

* Laddningstid
* Betyg med *Lighthouse* mobil och desktop

<b>Designelement:</b>  

* Bilder
* Färger
* Former

<b>Designprinciper:</b>  

* Balans  
* Unity (enhetlighet)  
* Variation

Urval
-----------------------

Jag utgick ifrån matbutiker som finns i Karlskrona och föreslog några för kunden. Det är också butiker som jag har handlat i och är bekant med deras sortiment. Kunden och jag kom fram till att följande webbplatser skulle undersökas:  

1. [Citygross](https://www.citygross.se/)  
2. [ICA Maxi Karlskrona](https://www.ica.se/butiker/maxi/karlskrona/maxi-ica-stormarknad-karlskrona-8917/start/)  
3. [Willys](https://www.willys.se/)  
4. [Hemköp](https://www.hemkop.se/)  
5. [Lidl](https://www.lidl.se/)  

Metod
-----------------------

Jag använde *Lighthouse* som undersöker webbplatsens innehåll och föreslår förbättringar för att göra sidan snabbare och mer användbar på både mobil och desktop. Jag använde *Lighthouse* med *DevTool i Google Chrome* men det kan användas från en webbplats med, se referens [1]. *Lighthouse* var inställd på "No throttling".  

För att mäta laddningstider och mängden data som skickas, så använde jag *Devtool i Google Chrome* och fliken *Network*. Jag gör tre laddningar av webbplatsens  startsida och redovisar medeltiden här i rapporten. Vill du se rådatan, så se arket i referens [2]. Cachen var avstängd under mätningarna. Mätningarna gjordes om med CTRL-Shift-r (eller CTRL-R) så att webbläsaren inte skulle använda sina cachade objekt.  

I och med att jag använder *Devtool i Google Chrome* så valde jag att använda *Google Chrome* som webbläsare för att undersöka webbplatserna.

#### Allmänt

* Kommentera webbplatsens mål och syfte. Varför finns webbplatsen till? Trender?      
* Kommentera webbplatsens design och vad som kännetecknar den rent allmänt.
* Ta en snapshot (bild) på webbplatsens startsida.  

#### Prestanda

* Beskriv den upplevda känslan för startsidan, snabb eller långsam  
* Mät och utvärdera webbplatsen med *Lighthouse* (*Google PageSpeed*) för både mobil och desktop och notera resultaten. Redovisa SEO (sökmotoroptimering) i resultaten.  
* För varje webbplats startsida, mät med *Devtools* flik *Network* och notera sidans laddningstid tillsammans med sidans totala storlek. Mätningen görs tre gånger och sen tas medelvärdet av mätvärdena.   
* Analysera och skriv en mening om hur webbplatsen kan förbättra sig.  

Alla mätresultat noteras i rådata filen, se referens [2], och en sammanfattning noteras i tabellen för respektive webbplats under rubriken *Resultat*. Resultaten analyseras sedan under rubriken *Analys*.

#### Designelement

* Lyft fram de designelement; bilder, färger och former, som kännetecknar webbplatsens design och exemplifiera.

#### Designprinciper

* Lyft fram de designprinciper; balans, unity (enhetlighet) och variation, som kännetecknar webbplatsens design och exemplifiera.  

Resultat
-----------------------

Här är resultaten från min undersökning av några matbutikers webbplatser.

#### Allmänt

Alla webbplatsernas mål är att sälja sina matvaror. De försöker presentera dem på ett attraktivt sätt och få dig att välja just dem. De har många fina bilder och mycket bra information. De har förutom matvaror också andra tjänster som recept, matkassar, onlineshopping etc som ska locka dig att klicka runt på webbplatsen.

En trend är onlineshopping som Citygross, ICA Maxi Karlskrona och Willys på Slottsbacken har anammat. Hemköp erbjuder det bland annat i Stockholmsområdet men inte i Karlskrona. Lidl erbjuder inte onlineshopping. Det finns två varianter; leverans hem och hämta i butik. På Citygross, ICA Maxi Karlskrona och Willys på Slottsbacken kan du hämta i butik. För en avgift på 99 kr så kör ICA Maxi Karlskrona hem dina varor.

En annan trend är inspiration till matlagning och recept och det erbjuder alla butikerna. Recepten är med vackra bilder, informativa och lätta att följa. Vissa butiker har speciella kockar knutna till sig, som t ex Hemköp har systrarna Eisenman.

En trend som jag väntat mig mer av var klimatfrågan, som ju är väldigt aktuell. På Lidls webbplats hittar jag enkelt information om Lidl och klimatfrågan. På de andra webbplatserna får jag leta lite mer, som t ex scrolla längst ner på Citygross startsida.

### Citygross

Webbplatsens design är, vid första anblicken, lite rörig med massor av bilder och information. Sen tycker jag att det blir bra när jag tittat ett litet tag och hittat matvarorna. Loggan är enkel och har hög igenkänningsfaktor.

Kännetecknet är loggan som är gul och så står det "Citygross" med blå text i den.

Citygross erbjuder matvaror, recept, matkassar och onlineshopping. Du hittar dessa tjänster i navigationsbaren överst.

#### Snapshot

[FIGURE src=image/proj/citygross.jpg class="right" caption="Citygross startsida."]  

#### Prestanda

| Upplevd känsla  | Betyg Lighthouse Desktop | Betyg Lighthouse Mobil | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns lite långsam | 91/100 | 91/100 | 6,0 s 11,4 MB |

#### Designelement

| Bilder  | Färg | Former |
|------------|--------------|--------------|
| En stor, högupplöst flashbild drar blickarna till sig och i dess underkant finns 4 snabblänkar till tjänsterna onlineshopping, matkassar, veckans erbjudande och hitta din butik. 4 bilder (2x2 i mobil) under som hanterar områden som inspiration, matvaror, recept och catering. Övriga bilder är ganska små. Bilderna är responsiva. | Vit bakgrund, gul logga och gula accentpunkter som varukorg, ljusgrått för sökfält och knappar, som t ex lägg-till-knapp för onlineshopping, grått på menyn under flashbilden. Lägg-till-knappen blir gul när du hovrar över den. På undersidorna är det mer gult och ljusgrått. | Fyrkanter, streck, hjärta för matvaror du gillar, ikoner för varukorg samt frågor och svar |

#### Designprinciper

| Balans | Unity (enhetlighet) | Variation |
|------------|--------------|--------------|
| Bra balans med flashbild och de 4 bilderna under.  | Sidan är lite rörig men blir bättre när du tittat på den ett litet tag. Bra enhetlighet med formerna, t ex bildernas former är likadana. Bra enhetlighet på undersidorna med menyn till vänster och det gula. | Bra variation med bilder, först 1, sen 4x1, sen 2x4, sen 2x2 och sen 4x2. Bra att det du hovrar över blir gult. |

### ICA Maxi Karlskrona

Här har jag valt webbplatsen för ICA Maxi Karlskrona då den generella webbplatsen för ICA Maxi var en karta för hela ICA konsernen. ICA Maxi har liknande webbplatser för olika orter.

ICA Maxi Karlskrona är enkel samtidigt som den är skrikig med ett erbjudande. Enkelheten är att de presenterar inte en massa matvaror direkt på första sidan utan ett erbjudande och sina tjänster.

Kännetecknet är loggan som är vit med röd text överst "MAXI" och under "ICA" med röd text och "STORMARKNAD" med svart text.

ICA Maxi Karlskrona erbjuder catering, erbjudanden, onlineshopping, matvaror, matkassar och Hemtex24H. Du hittar dessa i navigationsbaren överst.

#### Snapshot

[FIGURE src=image/proj/icamaxi.jpg class="right" caption="ICA Maxi Karlskronas startsida."]  

#### Prestanda

| Upplevd känsla  | Betyg Lighthouse Desktop | Betyg Lighthouse Mobil | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns lite långsam | 91/100 | 92/100 | 4,5 s 5,8 MB |


#### Designelement

| Bilder  | Färg | Former |
|------------|--------------|--------------|
| Jättestor bild med maxiklipp, dock ej högupplöst. Mindre bilder under *Akuellt*. Mycket bra att bilderna under *Hos oss kan du även handla* är med ljusbakgrund och så är knapparna röda. | Bakgrunden är vit förutom under *Akuellt* där den är ljust beige och texten mörk med röda inslag. Även en del rosa inslag. Det röda blir rosa när du hovrar över det, vilket syns bra på knappar och mindre bra på röd text. | Fyrkanter, knappar med rundade hörn, pil för att förstärka *Aktuellt*, streck |

#### Designprinciper

| Balans | Unity (enhetlighet) | Variation |
|------------|--------------|--------------|
| Startsidan som sådan känns inte så balanserad men inom varje sektion som t ex *Aktuellt* är det balans i form av bilder, rutor och knappar. | Startsidan är inte enhetlig som helhet men varje sektion som t ex *Aktuellt* är enhetlig. Undersidorna är enhetliga med startsidan. | Bilden med maxiklipp fångar ens uppmärksamhet. Bilderna under aktuellt zoomar in när du hovrar över dem. Undersidorna hänger ihop med startsidan men är lite varierade. Det finns ett mönster under navigationsbaren överst som förstärker rubriken och maxiklippet samt information om butiken, onlineshopping, matkassar och catering. |

### Willys

Webbplatsens design är tilltalande och enkel. Sparsmakat med färger men med en hel del bilder. En flashbild i blått med "Gott nytt år!" tilltalar mig mer än ICA Maxis illröda erbjudande. Willys har en hamburgermeny samt en meny under loggan.

Kännetecknet är loggan som är vit bakgrund och sen står det "WiLLY:s" i svart text fast med röda L.

Willys erbjuder matvaror och onlineshopping.

#### Snapshot

[FIGURE src=image/proj/willys.jpg class="right" caption="Willys startsida."]  

#### Prestanda

| Upplevd känsla  | Betyg Lighthouse Desktop | Betyg Lighthouse Mobil | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns ok, varken snabb eller långsam | 91/100 | 91/100 | 5,0 s 4,8 MB |


#### Designelement

| Bilder  | Färg | Former |
|------------|--------------|--------------|
| Stor flashbild i härliga blå färger drar till sig uppmärksamheten. Diskreta bilder presenterar matvarorna. För att förstärka *Willys hämta* har de två färgstarka bilder i rött, svart och grått över footern. | Bakgrunden är vit med ljusgrå ramar runt olika områden. Gult för erbjudanden. Plustecknet för onlineshopping förstärks med rött. I footern är det starka färger med röd fyrkant överst och sen svart bakgrund och ljus text. | Fyrkanter, rundade hörn i sökfältet, ramar i ljusgrått och streck. Tydliga plus- och minustecken gör det enkelt med onlineshopping. Formen handlelista gör det enkelt att lägga till matvaran i onlineshopping. |

#### Designprinciper

| Balans | Unity (enhetlighet) | Variation |
|------------|--------------|--------------|
| Sidan är enkel och balanserad. Lätt att hitta på. Mindre information än Citygross och ICA Maxi. | Enhetliga färger och storlekar på bilderna. Matvarubilderna är mycket enhetliga. Lättare med enhetlighet då Willys erbjudande av tjänster är mindre än Citygross och ICA Maxi. | Sidan är varierad med olika färger, former och områden. |

### Hemköp

Webbplatsens design är relativt enkel med stora bilder och en röd-rosa färgskala. Webbplatsen har en hamburgermeny och en stor flashbild. På flashbilden är det enkelt att hitta hur du blir bonuskund, onlineshopping och var närmaste butik är.

Kännetecknet är loggan som har vit bakgrund med röd text "Hemköp" i enkel skrivstil.

Hemköp erbjuder matvaror, onlineshopping och recept.

#### Snapshot

[FIGURE src=image/proj/hemkop.jpg class="right" caption="Hemköps startsida."]  

#### Prestanda

| Upplevd känsla  | Betyg Lighthouse Desktop | Betyg Lighthouse Mobil | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns ganska snabb | 90/100 | 90/100 | 4,7 s 5,3 MB |


#### Designelement

| Bilder  | Färg | Former |
|------------|--------------|--------------|
| Stor flashbild med systrar som erbjuder recept och med snabblänkar i underkant. Därefter ganska stora bilder på *Aktuell hos oss*, veckans erbjudanden och recept. | Bakgrunden är beige med mörk textfärg och orangeröda fält. Inslag av gult och rosa. Bilderna är transparenta med vit bakgrundsfärg. Footern är orangeröd med vit text. Förutom footern så är färgerna behagliga. | Fyrkanter, streck, logga för varje tjänst t ex huvud med lurar i kundtjänst, pilar, tydliga plus- och minustecken för onlineshopping inom en ram med rundade hörn - snyggt. |

#### Designprinciper

| Balans | Unity (enhetlighet) | Variation |
|------------|--------------|--------------|
| Alla fyrkanter med bilder i är balanserade och i samma storlek utom flashbilden. I receptbilderna får både bild och lite text plats. | Väldigt enhetlig sida med tanke på samma storlek på fyrkanterna. Sidan är bra responsiv men enhetligheten försvinner då antalet bilder på matvarorna ökar med storleken på skärmen men det är ju bara ett problem just när du förstorar. | Bilderna för *Aktuellt hos oss* och matvarorna är olika och lätta att skilja åt. Den starka färgen i footern gör att den sticker ut. |

### Lidl

Webbplatsens design är väldigt rörig med många bilder. Flashbilden är naturligtvis aktuell, just nu nyårstema. Under flashbilden har du erbjudenden från denna och nästa vecka uppdelat i kategorier, t ex *Kött och chark*, *Frukt och grönt*.

Kännetecknet är loggan som är en mörkare blå kvadrat med en gul cirkel med röd kant inne i kvadraten och så står det Lidl med blå och röd text i den. I:et är rött och resten av bokstäverna är blå. Samma blå som kvadraten och samma röda som kanten runt cirkeln.

Lidl erbjuder matvaror, andra varor som kläder, recept, information om hållbarhet och sociala medier.

#### Snapshot

[FIGURE src=image/proj/lidl.jpg class="right" caption="Lidls startsida."]  

#### Prestanda

| Upplevd känsla  | Betyg Lighthouse Desktop | Betyg Lighthouse Mobil | Laddningstid |
|------------|--------------|--------------|--------------|
| Känns ganska snabb | 100/100 | 97/100 | 2,1 s för 4,1 MB  |

Snabbaste laddningstiden! Dessutom den enda sidan där *Lighthouse* inte klagade på kontrasten mellan bakgrundsfärg och textfärg.

#### Designelement

| Bilder  | Färg | Former |
|------------|--------------|--------------|
| Många bilder i olika storlekar. Först en stor flashbild och sen under den bilder med olika teman t ex *Kött och chark* och *Duka till nyårsfest*. Under det kommer transparenta bilder med ljus bakgrund på *Veckans utvalda favoriter*. Bilderna på recepten är ganska stora och inbjudande. | Bakgrunden är vit generellt men på vissa bilder och områden är den ljusgrå. Textfärgen är väldigt mörk, nästan svart. Lilds färger syns mest i loggan och i informationen om att de stöttar svenska handbollslandslagen. Footern är grå med vit text. | Fyrkanter av olika storlekar, cirklar för att "highlighta" färskt kött i *Kött och chark*-rutan. Streck, pil och logga för olika tjänster som t ex *Butiker och öppetider* och *Sociala medier*.|

#### Designprinciper

| Balans | Unity (enhetlighet) | Variation |
|------------|--------------|--------------|
| Sidan är rörig pga det händer så mycket och inte speciellt balanserad. Det är för mycket information överst på sidan med 3 navigationsbarer över varandra. | Sidan är inte enhetlig som helhet men inom varje område så är det enhetligt. Undersidorna är enhetliga. Sidan med matvaror är bra balanserad och enhetlig.| Stor variation i storleken på bilderna. Receptsidorna har en varierad bakgrund som liknar en planka. |

Analys
-----------------------

Vad är lång laddningstid? Ja, 2-3 s är väl bra sen blir det lite för långt att vänta. Vilken matbutik var snabbast och vilken var bäst? Samma?

Tävling, snabbaste matbutiken
-----------------------

Endast Lidl klarar gränsen på 2-3 s med 2,1 s och är klart snabbast. De andra webbplatserna hade laddningstider mellan 4,6 s och 6,0 s, vilket är ganska lika tider. Jag upplever att Lidl är ganska snabb men det gör jag även med Hemköp. Varför då? En anledning kan vara att Hemköps startsida är vilsam medan Lidls är rörig och har mycket att titta på.


| Placering  | Webbplats | Laddningstid |
|------------|--------------|--------------|
| 1:a | Lidl | 2,1 s|
| 2:a | ICA Maxi Karlskrona | 4,5 s|
| 3:a | Hemköp | 4,7 s|
| 4:a | Willys | 5,0 s|
| 5:a | Citygross | 6,0 s|



Tävling, bästa matbutiken
-----------------------

Vilken av dessa matbutiker har den bästa webbplatsen? Om man tänker på alla kriterier jag undersökt samt känslan som jag har när jag tittat runt på webbplatsen så blir resultatet så här:

| Placering  | Webbplats | Kommentar |
|------------|--------------|--------------|
| 1:a | Willys| Enkel och snygg design. något skrikig röd färg. Billigast. Saknar dock recept. |
| 2:a | Citygross | Mycket information som är bra strukterad och varierad. Bra balans på sidan. Skulle kunna vara lite snabbare. |
| 3:a | Hemköp | Enkel och tydlig men lite tråkig hemsida. |
| 4:a | ICA Maxi Karlskrona | Den röda färgen är skrikig. |
| 5:a | Lidl | Sidan är alldeles för rörig. Snabb laddningstid. |

Förbättringsförslag, Lighthouse
-----------------------

#### Citygross

Lighthouse värden för mobil: performance 83, accessiblity 82, best practises 79 och SEO 91
Förbättringsförslag mobil: t ex för lång tid till interaktion 6.6 s, för stor DOM storlek på 3123 element mot rekommenderade 1500 och kontrasten mellan bakgrund och text var inte bra.

Lighthouse värden för desktop: performance 95, accessiblity 84, best practises 79 och SEO 91
Förbättringsförslag desktop: här var tid till interaktion bättre, liksom DOM storleken men kontrasten är inte bra.

#### ICA Maxi Karlskrona

Lighthouse värden för mobil: performance 88, accessiblity 81, best practises 79 och SEO 92
Förbättringsförslag mobil: t ex  för lång tid på "Max Potential First Input Delay dvs längsta uppgiften på 250 ms, kontrasten mellan bakgrund och text var inte bra, hittade 14 sårbarheter i front-end JavaScript bibliotek.

Lighthouse värden för desktop: performance 92, accessiblity 81, best practises 79 och SEO 91
Förbättringsförslag desktop: samma som mobil fast tiden för "Max Potential First Input Delay" på 220 ms är bättre.

#### Willys

Lighthouse värden för mobil: performance 90, accessiblity 79, best practises 64 och SEO 100
Förbättringsförslag mobil: t ex kontrasten mellan bakgrund och text var inte bra, använder inte passiva lyssnare för att förbättra scroll prestandan, hittade 13 sårbarheter i front-end JavaScript bibliotek.

Lighthouse värden för desktop: performance 89, accessiblity 72, best practises 64 och SEO 100
Förbättringsförslag desktop: samma som för mobil.

#### Hemköp

Lighthouse värden för mobil: performance 91, accessiblity 65, best practises 64 och SEO 90
Förbättringsförslag mobil: t ex för stor DOM storlek på 1591 element mot rekommenderade 1500, knapparna har inte namn som går att accessa och kontrasten mellan bakgrund och text var inte bra.

Lighthouse värden för desktop: performance 94, accessiblity 65, best practises 64 och SEO 90
Förbättringsförslag desktop: samma som mobil men DOM storleken är större här 1783 element.

#### Lidl

Lighthouse värden för mobil: performance 98, accessiblity 81, best practises 64 och SEO 97
Förbättringsförslag mobil: t ex för lång tid på Max Potential First Input Delay dvs längsta uppgiften på 750 ms , för stor DOM storlek på 1762 element mot rekommenderade 1500 och se till att texten syns när webfonten laddas.

Lighthouse värden för desktop: performance 95, accessiblity 82, best practises 57 och SEO 100
Förbättringsförslag desktop: samma som mobil men här var tiden på Max Potential First Input Delay ännu längre 1,180 ms och behöver förbättras mer, och
det var lite fler överdrivet stora DOM element 1893.


Referenser
-----------------------

[1] [Google PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/)

[2] [Mätdata laddningstid och SEO](img/proj/Kmom10MatningarLaddningstidOchSEO.pdf)

Övrigt
-----------------------

Författare: Marie Grahn  
Diskussionsgrupp: ingen
