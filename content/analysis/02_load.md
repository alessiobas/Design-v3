---
Title: Load
Description: Report load speed
Template: reports
---

Utvärdering av webbplatsers laddningstid och användbarhet
===================================

I denna rapport kommer jag analysera tre olika webbplatsers laddningstid och användbarhet. Webbsidorna kommer analyseras med hjälp av inspekteraren på webbsidorna samt verktyg så som PageSpeed Insights och analysen utgår från 


Urval
-----------------------

Jag har valt att analyser tre olika universitets/högskolors webbsidor. Skolorna är BTH - Blekinge Tekniska Högskola, UU - Uppsala Universitet & UMU - Umeå Universitet.
- https://www.bth.se/
- https://www.uu.se/
- https://www.umu.se/

Valet föll på dessa skolors hemsidor då jag studerat på alla dessa skolor i olika perioder i mitt liv. Valet grundades även på hemsidornas liknande syfte och målgrupp och i förläning av det deras användbarhet.

Metod
-----------------------

I min analys har jag använt mig av Googles PageSpeed Insight som är ett verktyg för att mäta olika webbsidors prestanda utifrån olika parametrar. Verktyget visar hur lång tid det tar att ladda olika delar av webbsidan och hur bra sidan laddas på en mobil enhet och en dator. Verktyget ger även tips på vad som kan göras för att förbättra sidan prestanda. 

I analysen används även "inspektera" läget på webbsidan, det kallas för DevTools och jag använder webbläsaren Firefox för analysen. I DevTools kan jag se storleken på objekten som laddas när jag öppnar sidan och laddningstiden. En laddning av sidorna utan cache görs för att för att inte laddningstiden ska bero på om jag har delar av sidan i mitt cacheminne. 

Resultat
-----------------------
### Mätningar

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRdXCJ_RYFeW4iVpsXNRgRRIWQHARcK3fdyeo3E5dCX9qcw2Y0UoTkQ8OBccCwTPssEJPRSCHUZdpT7/pubhtml?widget=true&amp;headers=false" style="height: 700px;width: 1100px;"></iframe>

### BTH - Blekinge Tekniska Högskola

![me](%assets_url%/img/BTH_print.png)

BTH har inte speciellt bra prestanda på någon av undersökta sidor. Dock är prestandan vid laddning av sidorna på dator betydligt bättre än mobilt. Det tar mellan 1,1-5,1 sekunder för besökaren att börja använda sidan och runt 3-4 sekunder för besökaren att visuellt se hur innehållet på sidan ser ut vid besök via dator och mellan drygt 10-12 sekunder vid besök via mobil. Det tar mellan 4-6,5 sekunder för besökaren att interagera med sidorna via datorn och mellan drygt 16-21 sekunder att interagera med sidorna via mobil. Sidorna har en storlek på runt 5MB och laddningstiden för sidorna är runt 10 sekunder att i snitt. För snabbare laddning bör serverns första svarstid minskas, en enorm nätverksbelastning undvikas, DOM-trädet göras mindre och se till att all text förblir synlig medan webbteckensnitten läses in. 

### UU - Uppsala Universitet

![me](%assets_url%/img/UU_print.png)

UU har en väldigt hög prestanda vid besök via dator, över 90. Mobilt är prestandan också bra, men inte lika bra som via datorn. Besökaren kan börja använda sidorna efter 0,5 sekunder via datorn och runt 2 sekunder via mobil. Visuellt presenteras sidan via datorn efter ungefär 1 sekund och mobilt efter c.a. 4 sekunder. Besökaren kan interagera med sidan efter 0,5 sekunder via datorn och efter 5-8 sekunder via mobilen. Sidornas storlek ligger på 1,80-3,22 MB och laddningstiden är drygt 3 sekunder i genomsnitt. Bilder bör skickas i modernare bildformat och texten bör förbli synlig medan webbteckensnitten läses in för att korta ned sidans laddningstid.

### UMU - Umeå Universitet

![me](%assets_url%/img/UMU_print.png)

UMU har mycket bra prestanda på sina sidor både mobilt och via dator. Prestandan ligger på 80-100. Besökaren kan börja använda sidorna efter 0,5 sekunder via datorn och runt 2 sekunder via mobil. Visuellt presenteras sidan via datorn efter knappt 1 sekund och mobilt efter c.a. 3 sekunder. Besökaren kan interagera med sidan efter 0,5-1 sekunder via datorn och efter runt 4 sekunder via mobilen. Sidorna är runt 1,5MB stora och laddningstiden ligger på 1-2 sekunder i genomsnitt. JavaScript och CSS som inte används bör reduceras för snabbare laddningstid. Bildelement bör även ha width och height och bildinläsningen blir uppskjuten vid störa uppritningen av innehåll. Om detta hanteras kan laddningstiden minska, men inga av åtgärderna som rekommenderades för ökad laddningstid var kritiska. 


Analys
-----------------------

Den vanligaste förbättringarna som rekommenderas är att visa text med webbteckensnitten läses in. Bilder kan även modifieras för ökad snabbhet. UMU och UU har sidor som laddas snabbt och av dessa två är UMU snabbast och har högst användbarhet. UMUs prestanda får en även att lyfta på ögonbrynen när den enligt använt verktyg i stort sett är maximal. BTH har sidor som är stora och laddar långsamt. Att det tar upp till 21 sekunder att börja interagera med en sida via mobilen är väldigt lång tid och BTH borde verkligen se över förbättringsåtgärder och implementera dessa för att minska laddningstiden. 

Som måttstock tycker jag att en besökare borde kunna interagera med en sida via datorn efter 1,5-2,0 sekunder. Både UU och UMU får godkända betyg, medan BTHs sidor tar mer än dubbelt så lång tid att börja interagera med. Generellt tycker jag UU och UMU har snabba och användbara sidor, medan BTH borde förbättra deras sidor för att minska laddningstiden och öka användbarheten. 

Referenser
-----------------------

https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect

https://www.bth.se/

https://www.uu.se/

https://www.umu.se/

Övrigt
-----------------------

Alessio Basile är ensam författare till rapporten.
