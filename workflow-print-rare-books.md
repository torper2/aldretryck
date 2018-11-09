
---
section: Hjälptexter katalogisering
title: Äldre tryck
order: 16
date: 2018-11-07
tags:
- under arbete
- äldre tryck
--- 

## Äldre tryck

Denna hjälptext beskriver ett antal vanligt förekommande egenskaper vid katalogisering av äldre tryck. Med äldre tryck avses skrifter som har framställts i handpress. Det omfattar nästan allt material som är tryckt före 1830. Nya Libris är anpassat efter katalogisering enligt RDA men äldre tryck katalogiseras enligt ISBD. Många anvisningar rör därför skillnader mellan RDA och ISBD. För instruktioner angående övriga egenskaper, se respektive hjälptext. För katalogiseringsanvisningar, se [Anvisningar för äldre tryck](http://www.kb.se/katalogisering/Katalogisering/aldre-tryck/ "Anvisningar för äldre tryck").

I vissa fall fungerar det ännu inte fullt ut att lägga till alla uppgifter som beskrivs i denna hjälptext. Arbete pågår med att förbättra gränssnittet. För att anmäla fel, använd detta formulär för [felrapportering](https://docs.google.com/forms/d/e/1FAIpQLSfOChJOGDoHUQguSF83F5XyTZiQL-yU47nvcqb6qwNT9GX7Aw/viewform). För att lämna synpunkter, använd detta formulär för  [ändringsförslag](https://docs.google.com/forms/d/e/1FAIpQLScgz_0enebhBn6uB8xvowkDBB4ax_dbvaobLSFfqFMoty6eQg/viewform).  


### Innehåll  

| [Adminmetadata](#adminmetadata) | [Instans](#instans) | [Verk](#verk) | 
| ------ | ----------- |  ----------- |
| [Skapad av](#skapad-av) | [Utgivningssätt](#utgivningssatt) | [Verkets titel](#verkets-titel) |
| [Uppgraderad  eller importerad av](#uppgraderad-eller-importerad-av) | [Titel](#titel) | [Språk](#sprak) |
|[Entry map](#entry-map)|[Upphovsuppgift](#upphovsuppgift) |[Medverkan och funktion](#medverkan-och-funktion) |
| [Katalogiserande instans](#katalogiserande-instans) | [Fingerprint](#fingerprint) | [Genre](#genre) |
| [Poststatus](#poststatus) | [Upplageuppgift](#upplageuppgift)|[Klassifikation](#klassifikation) |
|[Translitterering](#translitterering)| [Utgivning](#utgivning)| [Ämne](#amne) |
| [Systemnummer](#systemnummer) | [Tillverkning](#tillverkning) | [Innehållstyp](#innehallstyp) |
| [Katalogiseringsspråk](#katalogiseringssprak) | [Copyrightår](#copyrightar) | [Anmärkning om akademisk avhandling](#anmarkning-om-akademisk-avhandling) |
| [Katalogiseringsregler](#katalogiseringsregler) | [Omfång](#omfang)| |
| [Beskrivningsnivå](#beskrivningsniva) | [Övriga fysiska detaljer](#ovriga-fysiska-detaljer) |  |
| [Bibliografikod](#bibliografikod) |[Mått](#matt) | |
| [Systemteknisk anmärkning](#systemteknisk-anmarkning) | [Bilagor](#bilagor) | |
| | [Medietyp](#medietyp) | |
| | [Bärartyp](#barartyp) | |
|  | [Seriemedlemskap](#seriemedlemskap) | |
| | [Anmärkning](#anmarkning) | |
|  | [Innehållsanmärkning](#innehallsanmarkning) | |
| | [Målgruppsanmärkning](#malgruppsanmarkning) | |
| | [Annat bärarformat](#annat-bararformat) | | 



### Adminmetadata 
#### Katalogiseringssprak  
* Katalogiseringsspråk (descriptionLanguage = 040 ‡b)  
  Anges vid katalogisering enligt RDA. Låt uppgiften stå men lägg inte till den eftersom äldre tryck katalogiseras enligt ISBD.
  
#### Katalogiseringsregler  
* Katalogiseringsregler (descriptionConventions = 040 ‡e)  
  Äldre tryck katalogiseras enligt ISBD. Ta bort Katalogiserinsregler: rda genom att klicka på papperskorgen till höger om egenskapen.  

### Instans
#### Utgivningssatt
* Utgivningssätt (issuanceType)  
  Välj från lista.  
  ```Exempel: Monografisk resurs```
  
#### Titel  

##### Hela referenstiteln i Huvudtitel    
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)  
Till referenstiteln räknas all text före impressum, inklusive upphovs- och upplageuppgifter. Hela referenstiteln bör anges i Huvudtitel om syntaxen bryts eller om man skulle behöva ändra ordningsföjden på titel-, upphovs- och upplageuppgifterna.
<br/>```Exempel:```
  * ```Monografi: Tankar, om husbönders och tjänstefolks skyldigheter emot hwarannan inbördes, i anledning af Johan Christopher Schinmejers twänne predikningar, på tyska, öfwer desza ämnen, wälment meddelade af Olof Rönigk. Andra uplagan.```
  * ```Flerbandsverk: Abregé chronologique de l'histoire de France, par le sr. de Mezeray ... Premiere partie, tome III.```

##### Referenstiteln i Huvudtitel, Övrig titelinformation och upphovsuppgift
Referenstiteln kan anges i Huvudtitel, Övrig titelinformation och Upphovsuppgift om syntaxen inte bryts eller om ordningsföljden inte behöver ändras.
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 245 ‡a)<br/>
```Exempel: Napoleon, såsom menniska, hjelte och eröfrare.```
* Har titel/Titel/Övrig titelinformation (hasTitle/Title/subtitle = 245 ‡b)<br/>
```Exempel: Ett utkast till hans charakteristik (inledande versal eftersom huvudtiteln avslutas med punkt)```
* Upphovsuppgift (responsibilityStatement = 245 ‡c)<br/>
```Exempel: af E. M Arndt.```

#### Identifikator
Arbetsnoteringar i SB17- och COL-poster har placerats här (024).
* Identifikator/Värde (identifiedBy/value = 024 ‡a)<br/>
```Exempel: 840111g31```
* Identifikator/Typanmärkning (identifiedBy/typeNote = 024 ‡2)<br/>
```Exempel: SB17```

Vi rekommenderar inte att använda Fingerprint men möjligheten finns att ange det här. Ange förslagsvis uppgiften i Värde och Källa, som ungefär motsvaras av Oanalyserat fingerprint och Källa i MARC21. 
* Identifikator/Fingerprint/Värde (identifiedBy/fingerprint/value = 026 ‡e och ‡2)<br/>
  Klicka på papperskorgen till höger om ISBN.<br/>
  Klicka på det stora plustecknet i högermarginalen.<br/>
  Sök efter och välj Identifikator i sidorutan.<br/>
  Välj Fingerprint i rullgardinsmenyn Välj typ.<br/>
  Klicka på plustecknet till höger om Fingerprint.<br/>
  Sök efter och välj Värde i sidorutan.<br/>
  Sök efter och välj Källa i sidorutan.<br/>
  Skriv in uppgiften i Värde.<br/>
  Klicka på plustecknet till höger om Källa.<br/>
  Välj Termlista i sidorutan, Skapa lokal entitet.<br/>
  Klicka på plustecknet till höger om Termlista.<br/>
  Sök efter och välj Kod i sidorutan.<br/>
  Skriv in koden.
  
#### Upplageuppgift
* Upplageuppgift (editionStatement = 250 ‡a)  
  Upplageuppgifter i äldre tryck anges sällan här utan i sitt sammanhang, som del av titel- eller utgivningscitatet. Kan exempelvis användas när upplageuppgift saknas i trycket.  
  ```Exempel: [Ny udgave]```  
  
#### Utgivning  
* Utgivning (publication)  
  I RDA är det obligatoriskt att ange utgivningsort, utgivarnamn och utgivningsår. Tryck- eller copyrightår räknas exempelvis inte som utgivningsår. Dessa uppgifter måste därför klamras enligt RDA.
Nutida uppdelning av olika funktioner (utgivare, tryckare, distributör och försäljare) stämmer inte för handpresstiden. Tills vidare räknas därför tryckuppgifter som utgivningsuppgifter och klamras inte.
Impressum anges enbart i Plats om det finns någon tryck- eller utgivningsuppgift i trycket.
Impressum anges i Plats, Agent och Datum/År om det inte finns några tryck- eller utgivningsuppgifter i trycket.
 
##### Utgivningsplats (tryckort)
* Plats/Plats/Benämning (place/label = 264 -/1 ‡a)
Skriv in uppgiften under Benämning.
  <br/>```Exempel:```
  * ```Fullständiga tryckuppgifter i trycket: Götheborg, tryckt hos Sam. Norberg, 1825.```
  * ```Ofullständiga tryckuppgifter i trycket: [Stockholm] Tryckt hos Kongl. tryckeriet.```    
  * ```Tryckuppgifter saknas: [Jönköping?]``` 
  
##### Utgivarnamn (tryckare etc.)
* Agent/Agent/Benämning (agent/label = 264 -/1 ‡b)  
  Skriv in uppgiften under Benämning.  
  <br/>```Exempel:```
  * ```Tryckuppgifter saknas: [Curt?]```
  * ```Tryckuppgifter saknas: [utgivare okänd]```  
  
##### År och datum (tryckår) 
  * År (date = 008/07-10, 264 -/1 ‡c)  
  År ska alltid anges. Det får endast förekomma inom Primär utgivning. Det kan innehålla siffror (0-9) och bokstaven u. Det anges med fyra tecken. Om fullständigt tryckår står i trycket räcker det med att ange År. 
  <br/>```Exempel:```
    * ```"1652" i trycket: 1652```
    
* Start- och slutår (flerbandsverk)  
  Om årtalen anges utan klammer eller andra tecken utöver fyra positioner, räcker det att ange årtalen här.
 <br/>```Exempel:```
  * ```Startår: 1732```
  * ```Slutår: 1745```
  * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)```    
 
 Om tryckår saknas eller är ofullständigt använder man även Datum.     
    
  * Datum (date = 264 -/1 ‡c)
    Här anges tryckår som måste anges med fler än fyra tecken.  
  <br/>```Exempel:```
    * ```Tryckår saknas i trycket: [17uu?]```
    * ```Sannolikt tryckår: [1738?]```<br/>
    
    * ```Startår: 1732```
    * ```Slutår: 1745```
    * ```Typ av utgivningsdatum: Flera årtal (monografisk resurs)``` 
   
#### Tillverkning 
* Tillverkning (manufacture)
Används inte vid katalogisering av äldre tryck. I exempelvis SB17-poster har tryckuppgifter i normaliserad form lagt i 260 ‡e och ‡f. Dessa uppgifter har i nya Libris placerats här. Numera anger vi dock tryckorter och tryckare i Har biuppslag - Namn på orter och territorier (752 ‡a och ‡d).  
   
#### Omfang   
* Omfång/Omfång/Benämning (extent/Extent/label = 300 ‡a)  
  Enligt RDA ska man inte förkorta sidor, planschblad etc. Vi förkortar så länge vi katalogiserar enligt ISBD.  
  <br/>```Exempel:```
  * ```x, 692 s. (s. 687-692 opag., 687-688 annonser)```
  * ```5 vol. ([4], 412; [4] 448; 392; 408; 368 (s. 368 opag.) s., frontespis```    
  
#### Ovriga fysiska detaljer   
* Övriga fysiska detaljer (other physical details = 300 ‡b)  
  ```Exempel: 20 ill. (träsnitt)```

#### Matt 
* Mått/Mått/Benämning (hasDimensions/Dimensions/label = 300 ‡c)  
  ```Exempel: 8:o(12/6)``` 
  
#### Medietyp
* Medietyp (mediaType/Mediatype = 337 ‡b)  
  Anges vid katalogisering enligt RDA. Låt uppgiften stå men lägg inte till den eftersom äldre tryck katalogiseras enligt ISBD.
  
#### Barartyp
* Bärartyp (carrierType/CarrierType = 338 ‡b)  
  Anges vid katalogisering enligt RDA. Låt uppgiften stå men lägg inte till den eftersom äldre tryck katalogiseras enligt ISBD.
  
#### Numrering i seriell resurs   
* Har numrering av seriell resurs/Numrering av seriell resurs/Benämning (hasNumberingofSerials/NumberingofSerials/label = 362 0/- ‡a)<br/> Används i poster för seriella resurser. Uppgiften normaliseras vanligtvis inte när man katalogiserar äldre tryck.<br/>
  ```Exempel: Första bandet; första skriften-Andra bandet; nionde skriften```
  
#### Seriemedlemskap
* Seriemedlemskap/Seriemedlemskap/Ingår i serie (seriesMembership/SeriesMembership/inSeries)  
  Inte så ofta man behöver ange att en skrift ingår i en serie. Ofta räcker det då att ange Serieuppgift, Numrering inom serie och Indikator för seriebiuppslag. För fler exempel, se hjälptexten Tryckt monografi - Bok.  

##### Serieuppgift  
* Seriemedlemskap/Serieuppgift (seriesMembership/seriesStatement = 490 ‡a)  
  Skriv in uppgiften.  
   ```Exempel: Smärre skrifter hopsamlade```   

##### Numrering inom serie  
* Seriemedlemskap/Numrering inom serie (seriesMembership/seriesEnumeration = 490 ‡v, 830 ‡v)  
  Skriv in uppgiften.  
  ```Exempel: 1:1```  

##### Indikator för seriebiuppslag   
* Seriemedlemskap/Indikator för seriebiuppslag (marc:seriesTracingPolicy = 490 i1: 0/1)  
  Ange indikator 0 om endast serieuppgift och eventuell numrering inom serie ska anges.
  Skriv in uppgiften.
  ```Exempel: 0```   
 
#### Anmarkning
* Anmärkning/Anmärkning/Benämning (hasNote/Note/label = 500 ‡a)   
  Skriv in allmänna anmärkningar i Benämning.
  <br/>```Exempel:```
  * ```Fraktur```
  * ```Boktryckarmärke på sista sidan```
  <br/> Egenskapen Anmärkning om katalogiseringskälla (588 #a) är inte tillgänglig för närvarande. Ange den typen av anmärkningar här så länge. 
  * ```Exempel: S: Beskrivningen osäker, bygger på Kungliga bibliotekets exemplar som saknar titelblad och sannolikt [1] planschblad i början```

#### Citering i referatorgan    
  Det går inte att lägga in Citering i referatorgan (510) för närvarande. Alternativ lösning så länge är att kopiera en post som har följande egenskaper med:
* Indexerad i/Instans/Har titel/Titel (510 ‡a)
* Indexerad i/Instans/Anmärkning/Benämning (510 ‡c)

#### Namn på orter och territorier
  Här anges tryckorter i standardiserad form. Huvudsyftet är att samla upp namnformer som förekom under handpresstiden under en namnform. Använd i först hand Nationalencyklopedin vid fastställande av svenska ortnamn. För utländska ortnamn används de standardiserade namnformer för äldre tryckorter som finns i CERL Thesaurus.
  <br/><br/>Orter som har bytt namn och landtillhörighet<br/>
  I Voyager lade man till fält 751 eftersom man i fält 752 skulle ange nutida ortnamn och landtillhörighet. Det finns ingen motsvarighet till 751 i nya Libris. Det borde däremot vara tillåtet att ange två biuppslag på orter men man kan i dagsläget bara ange en ort.

##### Land  
* Har biuppslag - Namn på orter och territorier/Biuppslag - Namn på orter och territorier/Land / Överordnat territorium (marc:hasAddedEntryHierarchicalPlaceName/marc:countryOrLargerEntity = 752 ‡a)  
  Skriv in uppgiften.  
   ```Exempel: Sverige```   

##### Stad  
* Har biuppslag - Namn på orter och territorier/Biuppslag - Namn på orter och territorier/Stad, kommun (marc:hasAddedEntryHierarchicalPlaceName/marc:city = 752 ‡d)  
  Skriv in uppgiften.  
  ```Exempel: Stockholm```   
  
### Verk   

#### Instans av Verk/Text  
* Instans av Verk/Text (instanceOf/Work/Text)  
  Skapa verket som lokal entitet (bryt inte ut verket till en länkbar entitet). Vi rekommenderar att tills vidare skapa verket som lokal entitet. Vi återkommer med anvisningar för att skapa verk som länkbara entiteter. Denna hjälptext beskriver exempel på verk som lokal entitet. Det betyder att du anger de uppgifter som listas här nedan, under Instans av Verk, utan att klicka på länksymbolen (Länka entitet) vid Instans av Verk/Text.  
Läs mer om [Verk och Instans](https://librisbloggen.kb.se/2018/05/30/verk-och-instans-i-startversionen/).  

#### Verkets titel
 
Ange den föredragna titeln för verket här, vid behov. Följ [Anvisningar för katalogisering - RDA](http://www.kb.se/rdakatalogisering/Anvisningar/Allmanna-anvisningar/Sokingangar-for-verk-och-uttryck "Anvisningar för katalogisering - RDA").  
För översättningar och för verk som har givits ut under olika titlar på samma språk eller när samma titel har använts för olika verk, ska den föredragna titeln för verket anges.    

##### Verkets titel
* Har titel/Titel/Huvudtitel (hasTitle/Title/mainTitle = 240 1/0 ‡a)  
  "Originaltitel" för ett verk med primär medverkan anger du här.  
  Skriv in uppgiften.  
  ```Exempel: Soldier spy```  
  För en titel som börjar med bestämd eller obestämd artikel, ska artikeln fileras bort. Ange fileringsvärde genom att lägga till fileringsvärde och ange en siffra.  
  ```Exempel: Huvudtitel: En arbetsdag i skriftsamhället, fileringsvärde: 3```  
 
##### Verkets titel - huvuduppslag
*	Uttryck av/Verk/Har titel/Titel/Huvudtitel (expressionOf/Work/hasTitle/Title/mainTitle (= 130 ‡a)  
 "Originaltitel" för ett verk utan primär medverkande anger du här.  
Under Instans av Verk/Text, lägg till Uttryck av (plustecknet vid Instans av Verk/Text - Lägg till egenskaper under: Text, välj Uttryck av).  
Skapa verk som lokal entitet (plustecknet vid Uttryck av - Lägg till verk, välj Skapa lokal entitet, längst ner i sidorutan till höger), skriv "verk" i rutan Skapa lokal entitet. Klicka på Verk. Det läggs till under Uttryck av. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Har titel. Välj Titel. Ta bort Övrig titelinformation.    
Skriv in uppgiften under Huvudtitel.  
```Exempel: Bibeln```
*	Uttryck av/Verk/Har titel/Titel/Deltitel  
(expressionOf/Work/hasTitle/Title/partName = 130 ‡p)  
Lägg till eventuell deltitel (plustecknet vid Titel - lägg till egenskaper under: Titel, välj Deltitel).  
Skriv in uppgiften.  
```Exempel: Nya testamentet```
*	Uttryck av/Verk/Språk/Språk/Benämning  
(expressionOf/Work/language/Language/label = 130 ‡l)  
Lägg till eventuell benämning på språk som ska ingå i den föredragna titeln. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk (Lägg till språk) och välj Skapa lokal entitet. Lägg till Benämning (plustecknet vid Språk - Lägg till egenskaper under: Språk, välj Benämning.  
Skriv in uppgiften.  
```Exempel: Svenska```

##### Verkets titel - analytisk sökingång  
För att ange verk som ingår i det beskrivna verket, motsvarande fält 730 0/2 (analytisk sökingång) i marc:  
Under Instans av Verk/Text, klicka på plustecknet vid Verk (lägg till egenskaper under: Verk) och välj Har del. Följ sedan stegen ovan, från ”Skapa verk som lokal entitet”.  

##### Verkets titel - relaterade verk  
För att ange verk som är relaterade, men inte ingår i det beskrivna verket, motsvarande fält 730 0/_ (icke-analytisk sökingång) i marc:   
Under Instans av Verk/Text, lägg till Relation genom att klicka på plustecknet vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja Relation. Välj typ Relation. Lägg till Entitet genom att klicka på plustecknet vid Relation (Lägg till egenskaper under: Relation), välj Entitet. Skapa verk som lokal entitet (plustecknet vid Entitet - Lägg till verk). Följ sedan stegen ovan, från ”Välj Skapa lokal entitet”.  

#### Sprak 
* Språk (language = 008/35-37)  
  Ange textens språk. För en text på svenska, ange svenska. För att ange originalspråk för ett översatt verk, se Originalversion/Verk/Språk.  
  Länka till entitet.  
  ```Exempel: svenska (swe)```  
  För att ange att texten är på flera språk, t ex parallelltext, ange ytterligare en språkkod genom att klicka på plustecknet vid Språk (Lägg till språk) och söka fram ytterligare en entitet för ett språk och länka till den.  
  
##### Översättning  
För en översättning, ange även:  
* Språk/Språk/Benämning (Language/label = 240 ‡l)  
  Lägg till ytterligare en förekomst av Språk, under Språk (klicka på plustecknet vid Språk), skapa lokal entitet (klicka på Skapa lokal entitet längst ner i sidorutan till höger och lägg till Benämning (klicka på Lägg till egenskaper under: Språk).  
  Skriv in språket i klartext. Denna klartext - verkets (översättningens) språk - visas som ett tillägg till verkets titel i marcpostens 240 ‡l.  
  ```Exempel: Svenska```  

* Anmärkning: Språk (marc:LanguageNote = 041 i1: 1)  
  Ange om resursen är/innehåller en översättning.  
  För att lägga till uppgiften, klicka på plustecknet vid Instans av verk/Text och välj Anmärkning: Språk. Välj fras från lista.  
  ```Exempel: objektet är/innehåller översättning```  
  
* Originalversion/Verk/Språk (originalversion/Work/language = 041 ‡h)  
  Ange det språk som en översatt text är översatt från. För en text som är översatt från engelska till svenska, ange engelska här.   
  Klicka på Lägg till egenskaper under: Text, välj Originalversion, klicka på plustecknet vid Originalversion, välj Skapa lokal entitet (längst ner i sidorutan). Skriv Verk i rutan för Skapa lokal entitet och välj * Verk. Klicka på plustecknet vid Verk (Lägg till egenskaper under: Verk) och välj Språk. Klicka på plustecknet vid Språk. Sök fram språkentiteten och länka.  
  ```Exempel: engelska (eng)```  
För översättningar i flera led, länka först till det mellanliggande språket och därefter till originalspråket.  
  
###### Texten delvis översatt  
(041 0/- #a + 041 1/- #a #h)  
* Språk (language = 008/35-37) +
   Anmärkning: Språk: Objektet är/innehåller ej översättning (marc:languageNote = 041 0/- #a)   
* Har del/Verk/Språk (hasPart/Work/language = 041 ‡a) +  
  Anmärkning: Språk: Objektet är/innehåller översättning (marc:languageNote 041 1/-) +  
  Originalversion/Verk/Språk (originalVersion/Work/language = 041 ‡h)  
  För att ange att texten delvis är översatt, till exempel när en publikation innehåller parallelltext på två språk och den ena texten är en översättning: ange först Språk under Instans av Verk/Text (se Språk ovan). Sök fram och länka till entiteten för det språk som inte är en översättning. Klicka sedan på plustecknet vid Verk - Lägg till egenskap under: Text och välj Anmärkning: Språk. Välj Objektet är/innehåller ej översättning.   
 Lägg sedan till Har del under Instans av Verk/Text. Skapa verk som lokal entitet (plustecknet vid Har del - Lägg till resurs. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Verk och välj ++++ Verk.) Klicka på plustecknet vid den lokala entiteten Verk (Lägg till egenskaper under: Verk) och välj Språk. Sök fram och länka till entiteten för språket som texten är översatt till. Under den lokala entiteten Verk, lägg till Anmärkning: Språk och ange att resursen är/innehåller en översättning. Under Har del, lägg till Originalversion/Verk/Språk (se ovan under Översättning). Länka till entiteten för språket som resursen delvis är en översättning från.  
  
##### Parallelltext    
* Anmärkning/Anmärkning om språk/Anmärkning: Språk/Benämning (hasNote/marc:LanguageNote/marc:LanguageNote/label = 546 ‡a)  
  ```Exempel: Parallelltext på svenska och engelska```  
  Anmärkningen är under arbete och fungerar tyvärr ännu inte.  
  
#### Medverkan och funktion  
* Medverkan och funktion  
  Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)  
  
* Medverkan och funktion/Primär medverkan/Agent/Person (contribution/PrimaryContribution/agent/Person = 100 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
 ```Exempel: Lindgren, Astrid, 1907-2002```
* Medverkan och funktion/Primär medverkan/Funktion (contribution/PrimaryContribution/role = 100 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)  
  ```Exempel: relator/author (= Författare)```
  
* Medverkan och funktion/Medverkan/Agent/Person (contribution/agent/Person = 700 1/- ‡a)  
  Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet.   
  ```Exempel: Skoglund, Svante, 1960-```  
* Medverkan och funktion/Medverkan/Funktion (contribution/role = 700 ‡4)  
  Länka till entitet. Klicka på plustecknet vid Funktion (Lägg till funktion) och sök fram funktionskod. Skriv in kod eller utskriven form i sökrutan eller tryck på mellanslagstangenten för att se alla koder. Välj kod genom att klicka på plustecknet vid koden eller på koden.    
För en sorterad lista på koder, se Formathandboken för Libris/Voyager: [Funktions- och relationskoder](http://www.kb.se/katalogisering/Formathandboken/Funktionskoder/)    
  ```Exempel: relator/trl (= översättare)```  
  
#### Genre 
##### Saogf-termer  
* Genre/form – saogf-termer (genreForm = 655 -/7 ‡a, ‡2 saogf)  
  Länka till entitet.  
  För att söka efter entiteter inom saogf-termer, välj Genre/form i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
 ```Exempel: Självbiografier```  
  Se [instruktionsfilm](https://www.youtube.com/watch?v=wrqs310Nt0M&list=PLZVkEICvA5-GRT2oJQmLgq_2Pksx6zYPy&index=7)  

##### Litterär genre  
* Genre/form – litterär genre (genreForm = 008/33)  
  Länka till entitet.  
  För att söka efter entiteter inom Litterär genre, välj Litterär genre i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.   
  ```Exempel: 0 ( = ej skönlitterärt verk)```
  
##### Biografiskt material  
* Genre/form – biografiskt material (genreForm = 008/34)  
  Länka till entitet.  
  För att söka efter entiteter inom Biografiskt material, välj Biografiskt material i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.     
  ```Exempel: a (= självbiografi)```  
    
 ##### Festskrift     
* Genre/form – festskrift (genreForm = 008/30)  
  Länka till entitet.  
  För att söka efter entiteter inom Festskrift, välj Festskrift i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: Ja, resursen är en festskrift```    
    
 ##### Konferenspublikation       
* Genre/form – konferenspublikation (genreForm = 008/29)  
  Länka till entitet.  
  För att söka efter entiteter inom Konferenspublikation, välj Konferenspublikation i listan över typer, under Genre/form. Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.      
  ```Exempel: Ja, resursen härrör från konferens```   
     
##### Akademisk avhandling      
* Genre/form – akademisk avhandling (genreForm = 008/24-27)  
  Länka till entitet. För att söka efter entiteten Akademisk avhandling, välj Innehåll 1, Innehåll 3, Innehåll 2, i listan över typer, under Genre/form.  Skriv "avhandling" i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: Akademisk avhandling```     

#### Klassifikation 
* DDK-klassifikation  
  För att lägga till DDK-klassifikation:  
  * Om posten har Klassifikation/Klassifikation (till exempel SAB-klassifikation) men saknar Klassifikation/DDK-klassifikation, lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till egenskaper under: KLassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på den runda egenskap-knappen i verktygsmenyn (Lägg till egenskaper under: Instans). Välj Klassifikation. Klicka på plustecknet under Klassifikation (Lägg till Klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj DDK-klassifikation.  
   Skriv in uppgiften under Kod.  

* Klassifikation/DDK-klassifikation/Kod (classification/ClassificationDdc/code = 082 0/4 ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 327.12092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 082 ‡2)  
  ```full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 082 ‡2)  
   ```Exempel: 23/swe```  
  
##### Sekundär DDK-klassifikation  
Lägg till DDK-klassifikation (sekundär) genom att klicka på plusikonen vid Instans av Verk/Text (Lägg till egenskaper under: Text) och välja DDK-klassifikation (sekundär).  
Klicka sedan på plustecknet vid DDK-klassifikation (sekundär) (Lägg till ddk-klassifikation) och välj Skapa lokal entitet (längst ner i sidorutan till höger). Skriv in uppgiften under Kod.  
* Klassifikation/DDK-klassifikation/Kod (additionalClassificationDdc/ClassificationDdc/code = 083 0/- ‡a)  
  Skriv in uppgiften.  
  ```Exempel: 791.430233092```
* Klassifikation/DDK-klassifikation/Klassifikationsupplaga  
  (classification/ClassificationDdc/edition = 083 ‡2)  
  ```Exempel: full```  
*  Parallell upplagebeteckning/Upplagespecifik upphovsuppgift  
 (classification/ClassificationDdc/editionEnumeration = 083 ‡2)  
  ```Exempel: 23/swe``` 

##### SAB-klassifikation  
* SAB-klassifikation  
  För att lägga till annan klassifikation, till exempel SAB-klassifikation:  
  * Om posten har Klassifikation/DDK-klassifikation men saknar Klassifikation/Klassifikation (till exempel SAB-klassifikation), lägg till ytterligare en förekomst av Klassifikation (plustecknet vid Klassifikation - lägg till egenskaper under: KLassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation. Skriv in uppgiften under Kod.  
  * Om posten helt saknar Klassifikation, lägg till Klassifikation genom att klicka på den runda egenskap-knappen i verktygsmenyn (Lägg till egenskaper under: Instans). Välj Klassifikation. Klicka på plustecknet under Klassifikation (Lägg till egenskaper under: Klassifikation). Välj Skapa lokal entitet (längst ner i sidorutan till höger) och välj Klassifikation.  
   Skriv in uppgiften under Kod.  
* Klassifikation/Klassifikation/Kod (classification/Classification/code = 084 0/4 ‡a)  
     Skriv in uppgiften.  
  ```Exempel: Sei-e```   
* Klassifikation/Termlista/Termlista/Kod (classification/Classification/inScheme/ConceptScheme/code = 084 ‡2)  
 ```Exempel: kssb```  
* Klassifikation/Termlista/Termlista/Version (classification/Classification/inScheme/ConceptScheme/version = 084 ‡2)  
 ```Exempel: 8``` 

#### Amne  
* Ämne  
  Läs mer:  
  [Länka ämnesord](https://libris.kb.se/katalogisering/help/workflow-linked-entity-sh)   
  [Sammansatt, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-non-auth-sh)   
  [Kontrollerat, ej auktoriserat ämnesord](https://libris.kb.se/katalogisering/help/workflow-controlled-non-auth-sh)   
  [Okontrollerat ämnesord](https://libris.kb.se/katalogisering/help/workflow-uncontrolled-sh)

##### Allmänt ämnesord  
* Ämne - sao-term  (subject = 650 -/7 ‡a, ‡2 sao)  
  Länka till entitet.  
  ```Exempel: Säkerhetspolitik```

##### Allmänt ämnesord med underindelning   
Länka i första hand till färdiga sammansatta termer som entiteter. I övriga fall, skapa Sammansatt term som lokal entitet. (Plustecknet vid Ämne - Lägg till entitet, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv Sammansatt term i rutan Skapa lokal entitet, välj * Sammansatt term).  
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Under Termlista, sök fram och länka till entiteten "sao". (Plustecknet vid Termlista - Lägg till termlista, skriv sao i sökrutan Lägg till entitet, välj sao genom att klicka på plustecknet vid Svenska ämnesord (SAO), sao).  
  ```Exempel: sao```   
* Ämne/Sammansatt term/Termkomponenter/Allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 -/7 ‡a)      
  Under Termkomponenter, sök fram och länka till entiteten för det allmänna ämnesordet. (Plustecknet vid Termkomponenter - Lägg till entitet, välj typ Allmänt ämnesord, skriv sökbegrepp för ämnesordet i sökrutan Lägg till entitet, välj entitet genom att klicka på plustecknet vid entiteten - Lägg till.)      
  ```Exempel: Varumärken```    
* Ämne/Sammansatt term/Termkomponenter/Underindelning för allmänt ämnesord  
 (subject/ComplexSubject/termComponentList = 650 ‡x)   
  Under Termkomponenter, sök fram och länka till entiteten för det allmänna ämnesordet. (Plustecknet vid Termkomponenter - Lägg till entitet, välj typ Underindelning för allmänt ämnesord, skriv sökbegrepp för ämnesordet i sökrutan Lägg till entitet, välj entitet genom att klicka på plustecknet vid entiteten - Lägg till.)  
  ```Exempel: juridik och lagstiftning```   
  
##### Geografiska ämnesord  
* Geografiskt ämnesord (subject = 651 -/4 ‡a)  
  Sök fram och länka till entitet.  
  ```Exempel: Sverige```
  
##### Geografiskt ämnesord med geografisk underindelning  
Skapa Sammansatt term som lokal entitet. (Plustecknet vid Ämne - Lägg till entitet, välj Skapa lokal entitet, längst ner i sidorutan till höger. Skriv Sammansatt term i rutan Skapa lokal entitet, välj * Sammansatt term).  
* Ämne/Sammansatt term/Termlista (subject/ComplexSubject/inScheme = ‡2 sao)   
  Under Termlista, sök fram och länka till entiteten "sao". (Plustecknet vid Termlista - Lägg till termlista, skriv sao i sökrutan Lägg till entitet, välj sao genom att klicka på plustecknet vid Svenska ämnesord (SAO), sao).  
  ```Exempel: sao```  
* Ämne/Sammansatt term/Termkomponenter/Geografiskt ämnesord/Föredragen benämning  
 (subject/ComplexSubject/termComponentList/Geographic/prefLabel)  
 Under Termkomponenter, skapa Geografiskt ämnesord som lokal entitet. (Plustecknet vid Termkomponenter - Lägg till entitet. I  rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Geografiskt ämnesord och välj det). Skriv in det geografiska ämnesordet under Föredragen benämning.    
  ```Exempel: Tyskland```  
* Ämne/Sammansatt term/Termkomponenter/Underindelning för geografisk term/Föredragen benämning   
 (subject/ComplexSubject/termComponentList/GeographicSubdivision/prefLabel)  
  Under Termkomponenter, skapa Underindelning för geografisk term som lokal entitet. (Plustecknet vid Termkomponenter - Lägg till entitet. I rutan Skapa lokal entitet, längst ner i sidorutan till höger, skriv Underindelning för geografisk term och välj det). Skriv in termen för den geografiska underindelningen under Föredragen benämning.  
  ```Exempel: Bonn``` 
   
##### Kronologiskt ämnesord
* Ämne/Kronologiskt ämnesord (subject = 648 7/- ‡a, ‡2 sao)  
Länka till entitet. Om du inte får träff vid sökning på entiteter, pröva att söka på första ledet i ett sammansatt ord, t ex "1800" istället för "1800-talet".   
 ```Exempel: 1800-talet```  
  
##### Ämnesord Person  
* Ämne/Agent/Person (subject = 600 1/4- ‡a)      
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet (längst ner i sidorutan till höger).  
```Exempel: Lindgren, Astrid, 1907-2002```  
Läs [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)  
 
##### Ämnesord Organisation  
* Ämne/Agent/Organisation (subject/agent/Organization = 610 2/- ‡a)  
Länka till entitet. Börja alltid med att söka efter om agenten redan finns. Vid behov, skapa ny entitet för agent (se Skapa ny agent i hjälpsektionen). I undantagsfall, skapa lokal entitet (längst ner i sidorutan till höger).    
```Exempel: Svenska Röda korset```  
Läs mer:  
  [Auktoritetsgruppens rekommendationer](https://kundo.se/org/librisxl/d/kbs-auktoritetsgrupp-informerar-jraz/)   
  [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)       
 
#### Målgrupp     
 * Målgrupp (intendedAudience = 008/22)  
  Länka till entitet.  
  Trunkera genom att trycka på mellanslagstangenten eller med * i sökrutan. Välj rätt entitet genom att klicka på plustecknet vid entiteten eller på entiteten.    
  ```Exempel: j (= barn- och ungdom, 0-16 år)```  
  
#### Innehallstyp
* Innehållstyp/Innehållstyp (contentType/ContentType = 336 ‡b)   
  Länka till entitet.  
  ```Exempel: text (txt)```  
  För att lägga till ytterligare innehållstyp, till exempel "sti" = stillbild för en bilderbok med både text och bild, lägg till Har del under Instans av Verk, från plustecknet vid Text (Lägg till egenskaper under: Text). Skapa därefter Verk som lokal entitet genom att klicka på plustecknet vid Har del (Lägg till resurs). Välj Skapa lokal entitet och välj därefter ++ Verk i listan. Lägg därefter till Innehållstyp från plustecknet vid Verk (Lägg till egenskaper under: Verk). Sök fram och länka till entitet.
  
#### Anmarkning om akademisk avhandling    
* Anmärkning/Anmärkning om akademisk avhandling/Benämning (dissertation/Dissertation/label = 502 ‡a)  
  Lägg till anmärkning om akademisk avhandling (plustecknet vid Instans av Verk: Text - Lägg till egenskaper under: Text, välj Anmärkning om akademisk avhandling. Klicka på plustecknet vid Anmärkning om akademisk avhandling och välj Skapa lokal entitet (längst ner i sidorutan till höger).  
Skriv in anmärkningen under Benämning.    
  ```Exempel: Diss. Umeå : Umeå universitet, 2018```  

