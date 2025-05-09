## Inlämningsuppgift 1 - Återskapa en hemsida
Obligatorisk inlämningsuppgift i par för **BY-SUVNET WEBBUTVECKLING** av:
* Sophia Wennersten
* Christine Blomstrand

## Webbsida att återskapa
https://www.lagerhaus.se/utomhus-1/balkong/hangmatta-kramvit

## Avgränsningar (men vi gjorde vissa ändå!)
[X] Body-sektionen "Liknande produkter" (eftersom den är identisk sektion "Andra gillade också").
[X] Blå pil-knappar
[X] Chatt-knappen
- Bilder "utanför skärm" för att indikera bildkaruseller
- Interaktiva element så som knappar, bildkaruseller behöver inte vara interaktiva


## Responsivitet
HEADER
[X] 0 -> 630 Mindre text i övre blå header, liten vit "endast online" 
[X] 1023 -> 1279 Stort sökfält försvinner och övre header är blå, vit "endast online" blir större
[X] 1280 -> Bredaste med fler ikoner i header, vit övre header och stort sökfält

BODY (ÖVRE)
[X] 630 -> 799 EN Stor produktbild, liten breadcrumb, "lägg i varukorg" som aside i botten av sidan, Matcha med ligger under produktinfo, i kolumn med prod-bilder
[X] 800 -> Fler produktbilder, större breadcrumb, "lägg i varukorg" mitt i produktinformationen

BODY (UNDRE)
"Andra gillar"-karusell 
[X] Skalar med sidan men går från 2-bilder till 3 vid 768 (printscreena båda karusell-scenarion!!)

FOOTER
[X] 0 -> 767 Footer lista med footer-headers som dropdowns 
[X] 768 -> 799 LagerHaus-info med soc.medie-loggor längst ned, footer-headers med synliga underkategorier
[X] 800 -> 897 LagerHaus-info med soc.medie-loggor till vänster,  footer-headers (2kolumner!) med synliga underkategorier till höger
[X] 898 -> 1167 samma som steget innan MEN 3 kolumner footer-headers 
[X] 1168 -> samma som steget innan MEN 4 kolumner footer-headers


## Skärmdumper på följande skärmbredder från originalsidan:
<- 630 / w-xs
630 - 39.38 rem / "w-1.5xl"
768 - 48 rem / w-3xl
800 - 50 rem / "w3.5xl"
898 - 56.13 rem / w-4xl
1023 - 63.94 rem / w-5xl
1168 - 73 rem / w-6xl
1280 - 80 rem / w-7xl


## Uppgiftskrav från David

Krav för väl godkänt:
[X] 1. Din projektmapp innehåller minst en HTML fil och en CSS fil samt en README.md
[X] 2. I README.md filen ska det tydligt framgå vilken sida du har valt att återskapa och
eventuella avgränsningar du har valt att göra och varför, en länk till originalhemsidan
- samt ditt namn.
[X] 3. Git och Github har använts (repot ska vara publikt så jag kommer åt det)
[X] 4. Minst en skärmdump på orginalhemsidans utseende skall finns i er projektmapp
[X] 5. Elementen på sidan skall vara såpass responsiva att de stannar kvar i bild
[X] 6. Färger, storlekar och avstånd skall vara snarlika orignalhemsidans
[X] 7. Uppgiften skall vara inlämnad i tid! (projektmappen zippas ihop och lämnas in i
läroplattformen som grupp)

Krav för väl godkänt:
[X] 1. Kraven för godkänt är uppfyllda
[X] 2. Elementen på sidan skall vara fullt responsiva - alltså matcha orginalhemsidans
responsivitet
[X] 3. Det ska finnas flera skärmdumpar på orginalhemsidans utseende för olika
skärmstorlekar - minst en för mobil, en för tablet, och en för desktop.
[X] 4. Färger, storlekar och avstånd skall matcha orignalhemsidans
[X] 5. Ett ikonset (css fil från FontAwesome eller MaterialUI) ska laddas in i head taggen,
ikoner från filen skall sedan användas på minst ett ställe i html-koden.
[X] 6. Koden skall vara logiskt strukturerad med tydliga kommentarer för dess uppbyggnad