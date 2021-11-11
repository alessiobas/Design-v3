---
Title: About
Description: This is an about me page
---

Om
==========================

Mer information kommer publiceras på denna sida. Nedan följer ett stycke som kort förklarar vilka tekniker som används för att skapa denna webbplats. 

Sidan är byggd med hjälp av HTML/SASS. Stylen är skriven med hjälp av SASS som är det språk som temats uppbyggnad är definierat i. Texten på sidan är skriven i markdown. Temat är i sin tur uppbyggt med hjälp av olika moduler för att skapa en struktur i källkoden. Det medför flera fördelar att bygga sidan med hjälp av moduler, där den främst är just struktur, men det är även ett bra sätt att möjliggöra för andra programmerare att bygga vidare på sidan. Flertalet style val är definierade i olika variabler, där variablerna ligger i en egen modul. Vidare är sidans typografi skapad med hjälp av olika externa fonts och ikonerna på sidan är skapade via Font Awesome. Typografin har skapats genom att sätta en bra grund där t.ex. alla html element har en font-size på 100% (förutom vid en viss brytpunkt där texten är större för större skärmar) och alla p element är 1em. Sidans typografiska element har även definierats på ett sätt som leder till en vertikal rytm som skapar en harmoni på sidan och underlättar vid läsning.

Sidans responsivitet är skapad med dels media queries, där queriesen är definierade med hjälp av min/max-width. Bilden i headern döljs när sidan blir mindre och den större bilden på sidans startsida är satt till max-width: 100%; & height: auto; så den aldrig är större än sidans bredd (för att undvika horisontella scrollbars vid mindre skärmar).